---
title: Migrating to Adobe Identity Management
description: Description coming soon.
role: User
level: Beginner
hide: yes
hidefromtoc: yes
feature: Marketing
exl-id: 8368a148-c0c8-462f-b166-9efc412c4a0f
---
# Migrating to Adobe Identity Management

Adobe is enhancing how you manage your Adobe Marketo Engage subscriptions and users. We are bringing increased productivity to you and your organization by migrating your Marketo Engage subscriptions and users to the Adobe Admin Console.

This tutorial enables you to navigate the migration so you can manage Adobe Marketo Engage along with other Adobe accounts and products for your users in a central location. The migration is necessary and will not affect your marketing workflow, content, integrations, or assets.

## Pre-Migration Checklist for Marketo Engage Administrators {#pre-migration-checklist-for-marketo-engage-administrators}

To ensure your organization can migrate Adobe Marketo Engage to the Adobe Admin Console, we recommend you follow the checklist below to manage the upcoming changes.

### 1. Identify your System Administrator(s) and discuss actions they may need to take {#identify-your-system-administrators}

* If you're not sure who the System Administrators are within your organization, contact your Adobe Account team, or reach out to Adobe Support `marketocares@marketo.com`.

* Confirm the Adobe Admin Console (or Adobe Org) to which your Marketo Engage subscription(s) will be migrated.  Marketo Engage subscription(s) must be deployed in the same organization as Dynamic Chat, a native conversation automation tool integrated with Marketo Engage. 
`TBD LINK TO https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/subscription-and-user-migration/understanding-marketo-subscription-and-user-migration-to-the-adobe-admin-console#subscription-migration-complete`

* Learn more about how to communicate with your System Administrators in the [Sample Email section](#announce-the-migration-timeline).

### 2. Familiarize yourself with the changes and impacts of migrating to Adobe Identity {#familiarize-yourself-with-the-changes}

In the video below, the Marketo Engage Product Management team walks you through the migration journey and what to expect.

<iframe title="Adobe Video Publishing Cloud Player" width="854" height="480" src=https://video.tv.adobe.com/v/3430920t3/?t=170frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen scrolling="no"></iframe>

More help on this topic for Marketo Engage administrators:

* [User Setup checklist](https://experienceleague.adobe.com/en/docs/marketo/using/getting-started/initial-setup/user-setup){target="_blank"}

* [Adobe Identity Management Overview](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview){target="_blank"}

* [Understanding Marketo Subscription and User Migration to the Adobe Admin Console](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/subscription-and-user-migration/understanding-marketo-subscription-and-user-migration-to-the-adobe-admin-console){target="_blank"}

* [Migrating to Adobe Identity with Migration Console](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/subscription-and-user-migration/migrating-to-adobe-identity){target="_blank"}

* [Understand how to use Adobe Admin Console](https://helpx.adobe.com/enterprise/using/admin-console.html){target="_blank"}

### 3. Announce the migration timeline and preparation needed to your internal teams {#announce-the-migration-timeline}

* Mark the migration date on your Marketo Engage administrators' and users' calendars once scheduled.

You can modify the migration date in **Admin** > **Migration Console** > **Pre-Migration** to align better with your internal timeline. Learn more about rescheduling and the limitations of [modifying your migration date](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/subscription-and-user-migration/migrating-to-adobe-identity#pre-migration){target="_blank"}.

* Send an email to communicate with your System Administrators.

Below is a sample email for you to send to your System Administrators. Typically, your IT department manages all your Adobe licenses.

`---------------------------------------------------`

**Subject: Support Needed&mdash;Migration of Marketo Engage Subscriptions to Adobe Admin Console**

Dear `[IT Administrator/NAME]`,

Our Marketo Engage subscription will soon be migrated to the Adobe Identity Management System. The [Marketing Operation team] needs your help to complete some required steps before user migration begins, to minimize the impact on Marketo Engage users

`1.` Confirm if the organization already manages other Adobe products in Adobe Admin Console(s) and if Marketo Engage will be migrated to the same console.

* Note that Marketo Engage subscription(s) must be in the same organization as Dynamic Chat, a native conversation automation tool integrated with Marketo Engage.

* If you have concerns or questions regarding the Admin Console that will have Marketo Engage added to, please contact the Support team at `marketocares@marketo.com` and include us in your communication.

`2.` Be on the lookout for an email from Adobe with the subject line "Action required to manage user access to Adobe Marketo Engage `[Package Tier]`." This email was sent after Marketo Engage licenses were provisioned on our Admin Console. Only System Administrators will receive this email. Please inform us promptly when you receive it.

* Adobe may seek consent from you, who's the System Administrator of the Admin Console, to automatically migrate users to our organization's existing console. In the email with the subject line "Action required to manage user access to Adobe Marketo Engage `[Package Tier]`.", click the "Get Started" button to navigate to the consent page.

`3.` **Optional:** Setting up SSO (Single Sign On) on the Adobe Admin Console.

* To benefit our users to log in with SSO on their Adobe Identity moving forward, we request you to assist with SSO setup on Adobe Admin Console before user migration occurs. 
We appreciate your cooperation during this transition. Let me know when you have completed these steps so that I can proceed with user migration with Marketo Engage.
Regards,

`[Your Name]`

`---------------------------------------------------`

* Send an email to Marketo Engage users.

Below is a sample email you can use to announce the upcoming migration to your Marketo Engage users who do not have administrators' privileges.

`---------------------------------------------------`

**Subject: Important Update&mdash;Migration of Marketo Engage Subscriptions to Adobe Admin Console**

Dear Marketo Engage users,

We have an important announcement regarding our Marketo Engage instance and how you will sign in. Adobe is moving Marketo Engage subscriptions and users to the Adobe Admin Console to enable their customers to centralize all their product administration in one place. This will not affect marketing workflows, content, integrations, or assets.

Key Details:

* Migration Date: [Specify the scheduled date - please find this in Marketo Engage under **Admin** > **Migration Console** > **Pre-migration**]

* Timing: Migration starts around midnight local time for our subscription. 

* Impact: There will be no product access loss during user migration. If you are logged in when your account is being migrated, you will be logged out and prompted to log back in within minutes using Adobe Identity after the migration.

* Benefits: Authenticate Marketo Engage and other Adobe products by using a single Adobe identity, either an Adobe ID or Adobe Federated ID (SSO).

What You Need to Do:

`1.` Prepare: Email verification is required for you to be migrated to an Adobe Identity. 

i. You have received an Email Verification Request email with a link (stays valid for 3 days). If your link is expired, you can resend the verification email by going to **Admin** > **My Account** > **Account Settings** and clicking **Resend Verification**.
ii. An active user session is required for email verification success. Please sign in to your Marketo Engage subscription using your identity provider (IdP) URL first.

`2.` Onboard: Once your user account is migrated, you will receive an email from Adobe regarding the changes to your sign-in method. 

i. Accept the new invitation by clicking the 'Accept Invitation' button and signing in using Adobe Identity. 
ii. On the Adobe login page, please sign in with an existing Adobe ID. 

`3.` Contact: If you have any questions or need assistance after your account is migrated or if your account isn't migrated and you lost access to Marketo Engage, please reach out to the Marketo Engage migration team at [your internal contact email/phone].

We appreciate your cooperation during this transition. Thank you for your understanding and commitment to keeping our systems secure.

Best,

[Your Name]

`---------------------------------------------------`
