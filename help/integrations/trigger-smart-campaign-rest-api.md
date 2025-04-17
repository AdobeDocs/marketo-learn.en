---
title: Tutorial - How to trigger a Smart Campaign in Marketo Engage using the REST API and tokens
description: Learn how to trigger a Smart Campaign in Marketo Engage using the REST API, and personalize the email using My Tokens.
feature: REST API
role: Admin, Developer
level: Experienced
---
# How to trigger a Smart Campaign in Marketo Engage using the REST API and tokens

This tutorial walks you through how to trigger a Smart Campaign in Marketo Engage using the REST API, and personalize the email using My Tokens. This use case is ideal for customer-triggered notifications like webinar reminders, onboarding steps, or post-purchase follow-ups.

## Use case {#use-case}

A person registers for a webinar through an external platform (e.g., custom app, Pendo, Eventbrite). You want to automatically:

* Trigger a reminder email from Marketo Engage
* Personalize it with:
  * The person's first name
  * Webinar title
  * A unique join link

This can be done using the REST API and My Tokens.

## Step 1: Create the Smart Campaign {#step-one}

1. Go to **Marketing Activities**, and under your [Programs](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs){target="_blank"} folder, create a new [Smart Campaign](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/smart-campaigns/understanding-smart-campaigns){target="_blank"} called `Send Webinar Reminder`.

1. In the **Smart List** tab, [add a trigger](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger){target="_blank"} to allow the campaign to be called via the API:

   * Select **Campaign is Requested** as the trigger
   * Set the **Source** to `Web Service API`

![Smart List trigger setup](assets/trigger-smart-campaign-rest-api-1.png)

## Step 2: Define the email content {#step-two}

Create or edit an [email asset](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/assets/emails){target="_blank"} that references both Person and [My Tokens](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/tokens/managing-my-tokens){target="_blank"}.

>[!NOTE]
>
>Make sure to insert the tokens directly into the email content, as shown below.

```html
Hi {{lead.First Name:default=Customer}}

You're registered for **{{my.WebinarTitle}}**.

Join here: {{my.JoinLink}}
```

If you're using a token to dynamically inject an image URL (e.g., `{{my.WebinarImage}}`), you must wrap the token in an HTML image tag:

```html
<img src="{{my.WebinarImage}}" alt="Webinar banner" />
```

>[!IMPORTANT]
>
>Marketo Enagage **will not** render the image unless the token is placed inside a valid image tag.

![Email editor showing token usage](assets/trigger-smart-campaign-rest-api-2.png)

## Step 3: Add tokens to the program {#step-three}

To pass values dynamically via API, the tokens must already exist in Marketo Engage. You'll need to create them under the **My Tokens** tab of your Program.

1. Go to the **My Tokens** tab of your parent Program.

2. Drag in a **Text token** from the right-side panel for each dynamic value.

  * `{{my.WebinarTitle}}` - Text token
  * `{{my.JoinLink}}` - Text token
  * `{{my.WebinarImage}}` - Text token (this will be used as the `src` in an `<img>` tag)

![My Tokens tab in campaign](assets/trigger-smart-campaign-rest-api-3.png)

## Step 4: Set campaign qualification rules and activate campaign {#step-four}

1. Configure the [qualification rules](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/smart-campaigns/using-smart-campaigns/edit-qualification-rules-in-a-smart-campaign){target="_blank"} to control how often a person can run through the Smart Campaign.

1. Once configured, click **Activate** to enable the Smart Campaign to receive API-triggered requests.

![Smart Campaign qualification rule](assets/trigger-smart-campaign-rest-api-4.png)

## Step 5: Trigger the campaign via REST API {#step-five}

### Find the Campaign ID {#find-the-campaign-id}

To trigger a Smart Campaign via API, you'll need the **campaign ID**:

1. Find and select the Smart Campaign you want to trigger.

1. Look at the URL in your browser. It will look something like this: `https://app-XXX.marketo.com/#/classic/SC`**1234**`A1ZN38`.

1. The 4 digits after `SC` is your campaign ID, in the above example the Smart Campaign ID is '1234'

Use the following endpoint:

```
POST /rest/v1/campaigns/{campaignId}/trigger.json
```

Example:

```
POST /rest/v1/campaigns/1234/trigger.json
```

### Example Request Body {#example-request-body}

```json
{
  "input": {
    "leads": [
      {
        "id": 1002200
      }
    ],
    "tokens": [
      {
        "name": "{{my.WebinarTitle}}",
        "value": "Scaling Customer Engagement in 2025"
      },
      {
        "name": "{{my.JoinLink}}",
        "value": "https://webinars.company.com/join/abc123"
      },
      {
        "name": "{{my.WebinarImage}}",
        "value": "https://experienceleague.adobe.com/en/docs/marketo-learn/tutorials/events/media_1c6f338a518ada11550084c8ab3a6bbf554ff6eac.jpeg"
      }
    ]
  }
}

```

>[!IMPORTANT]
>
>Replace `1002200` in the body example above with the correct person ID from your Marketo Engage instance.

## Authorization {#authorization}

All Marketo REST API requests require an OAuth 2.0 access token.

To retrieve your access token, use the following endpoint:

```
GET /identity/oauth/token?grant_type=client_credentials&client_id=XXX&client_secret=YYY
```

Once you receive your access token, include it as a _query parameter_ in all API requests:

```
Authorization: Bearer YOUR_ACCESS_TOKEN
```

## Best Practices {#best-practices}

* Add fallback/default values to your tokens for testing and QA
* Use `{{lead.token}}` for person fields and `{{my.token}}` for campaign-scoped dynamic values
* Marketo Engage supports up to 100 people per request
* Persons must meet the Smart List criteria, otherwise, they are silently skipped

## Summary {#summary}

With this approach, you can personalize communications using Smart Campaigns that are triggered from external platforms via API. This is useful for scenarios like webinar registration confirmations, onboarding emails, and transactional notifications&mdash;all while injecting real-time data using My Tokens.
