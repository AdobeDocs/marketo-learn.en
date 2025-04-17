---
title: Migrating to Adobe Identity Management
description: This tutorial will help you navigate the migration of your Marketo Engage subscriptions and users to the Adobe Admin Console.
role: Admin
level: Intermediate, Experienced
recommendations: noDisplay, noCatalog
last-substantial-update: 2024-07-26
feature: Marketing
exl-id: 8368a148-c0c8-462f-b166-9efc412c4a0f
---
# Migrating to Adobe Identity Management

Adobe is enhancing how you manage your Adobe Marketo Engage subscriptions and users. We are bringing increased productivity to your organization by migrating your Marketo Engage subscriptions and users to the Adobe Admin Console.

This tutorial will help you navigate the migration so you can start managing Adobe Marketo Engage along with other Adobe accounts and products for your users in a central location. The migration is necessary and will not affect your marketing workflow, content, integrations, or assets.

## Pre-Migration Checklist for Marketo Engage Administrators {#pre-migration-checklist-for-marketo-engage-administrators}

To ensure your organization can migrate Adobe Marketo Engage to the Adobe Admin Console, we recommend following the checklist below to manage the upcoming changes.

### 1. Identify your System Administrator(s) and IT Team and discuss actions they may need to take {#identify-your-system-administrators}

* If you're not sure who the System Administrators are within your organization, contact your Adobe Account team, or reach out to Adobe Support `marketocares@marketo.com`.

* Confirm the Adobe Admin Console (or Adobe Org) to which your Marketo Engage subscription(s) will be migrated. You likely have an Adobe Admin Console for [Dynamic Chat](/help/dynamic-chat/dynamic-chat-overview.md){target="_blank"}, a native conversation automation tool in Marketo Engage. Marketo Engage subscription(s) must be deployed in the same organization as Dynamic Chat.

* Work with your IT team to allowlist all Adobe domains listed [at the top of this article](https://experienceleague.adobe.com/en/docs/marketo/using/getting-started/initial-setup/configure-protocols-for-marketo){target="_blank"} to prevent disruption to Marketo Engage access after the migration to Adobe Identity.

* **Optional:** [Implement Single Sign On (SSO)](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/subscription-and-user-migration/understanding-marketo-subscription-and-user-migration-to-the-adobe-admin-console#subscription-migration-complete){target="_blank"} before user migration.

   >[!NOTE]
   >
   >There are differences between Marketo Engage supported SSO and Adobe Admin Console SSO. As such, changes to your configuration may need to be implemented.

* **Optional:** Customize the [desired maximum session life](https://helpx.adobe.com/enterprise/using/authentication-settings.html#advanced-settings){target="_blank"} prior to user migration for Marketo Engage users to remain authenticated.  

* Learn what to communicate with your System Administrators in the [Sample Email section](#announce-the-migration-timeline).

### 2. Familiarize yourself with the changes and impacts of migrating to Adobe Identity {#familiarize-yourself-with-the-changes}

In the video below, the Marketo Engage Product Management team walks you through the migration journey and what to expect.

>[!VIDEO](https://video.tv.adobe.com/v/3430920t3/?t=170/?quality=12&learn=on){transcript=true}

More help on this topic for Marketo Engage administrators can be found in the following help articles:

* [User Setup checklist](https://experienceleague.adobe.com/en/docs/marketo/using/getting-started/initial-setup/user-setup){target="_blank"}

* [Adobe Identity Management Overview](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview){target="_blank"}

* [Understanding Marketo Subscription and User Migration to the Adobe Admin Console](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/subscription-and-user-migration/understanding-marketo-subscription-and-user-migration-to-the-adobe-admin-console){target="_blank"}

* [Migrating to Adobe Identity with Migration Console](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/subscription-and-user-migration/migrating-to-adobe-identity){target="_blank"}

* [Understand how to use Adobe Admin Console](https://helpx.adobe.com/enterprise/using/admin-console.html){target="_blank"}

### 3. Announce the migration timeline and preparation needed to your internal teams {#announce-the-migration-timeline}

* Mark the migration date on your Marketo Engage administrators' and users' calendars once scheduled.

  * You can modify the migration date in **Admin** > **Migration Console** > **Pre-Migration** to better suit your internal timeline. Learn more about rescheduling and the limitations of [modifying your migration date](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/subscription-and-user-migration/migrating-to-adobe-identity#pre-migration){target="_blank"}.

* **Send an email to your System Administrators**

Below is a sample email to send to your Admins. Typically, your IT department manages all your Adobe licenses.

+++ Sample email to send to your System Administrators

**Subject: Support Needed&mdash;Migration of Marketo Engage Subscriptions to Adobe Admin Console**

Dear `[IT Administrator/NAME]`,

Our Marketo Engage subscription will soon be migrated to the Adobe Identity Management System. The `[Marketing Operation team]` needs your help to complete some required steps before user migration begins, to minimize the impact on Marketo Engage users.

`1.` Confirm if the organization already manages other Adobe products in Adobe Admin Console(s) and if Marketo Engage will be migrated to the same console.

* Marketo Engage subscription(s) must be in the same organization as Dynamic Chat, a native conversation automation tool integrated with Marketo Engage.

* If you have questions or concerns regarding the Admin Console, please contact Adobe Support at `marketocares@marketo.com` and CC us.

`2.` Be on the lookout for an email from Adobe with the subject line "Action required to manage user access to Adobe Marketo Engage `[Package Tier]`." This email was sent after Marketo Engage licenses were provisioned on our Admin Console. Only System Administrators will receive this email. Please inform us promptly when you receive it.

* Adobe may seek consent from you, the System Administrator of the Admin Console, to automatically migrate users to our organization's existing console. In the email with the subject line "Action required to manage user access to Adobe Marketo Engage `[Package Tier]`," click the "Get Started" button to navigate to the consent page.

`3.` After migration, Marketo Engage will go from being served from experience.adobe.com to Adobe Experience Cloud. Please allowlist all Adobe domains listed [at the top of this article](https://experienceleague.adobe.com/en/docs/marketo/using/getting-started/initial-setup/configure-protocols-for-marketo){target="_blank"} to prevent disruption to our Marketo Engage access.

`4.` **Optional:** Set up SSO (Single Sign On) in the Adobe Admin Console.

* To benefit our users who log in with SSO on their Adobe Identity moving forward, please assist with SSO setup in the Adobe Admin Console before user migration occurs.

`5.` **Optional:** Set a longer [maximum session life](https://helpx.adobe.com/enterprise/using/authentication-settings.html#advanced-settings){target="_blank"} in the Adobe Admin Console.

* To prevent users from having to sign in frequently, please customize the session life in the Advanced Settings with a longer duration.

We appreciate your cooperation during this transition. Let me know when you have completed these steps so I can proceed with the migration.

Regards,

`[Your Name]`

+++

* **Send an email to Marketo Engage users**

Below is a sample email for Marketo Engage users who do **not** have administrator privileges.

+++ Sample email announcing the upcoming migration

**Subject: Important Update&mdash;Migration of Marketo Engage Subscriptions to Adobe Admin Console**

Dear Marketo Engage users,

We have an important announcement regarding our Marketo Engage instance and how you will sign in. Adobe is moving Marketo Engage subscriptions and users to the Adobe Admin Console to enable us to centralize all their product administration in one location. This will not affect marketing workflows, content, integrations, or assets.

**Key Details:**

* **Migration Date**: `[Specify the scheduled date - please find this in Marketo Engage under Admin > Migration Console > Pre-migration]`

* **Timing**: Migration starts around midnight local time for our subscription.

* **Impact**: There will be no product access loss during user migration. If you are logged in when your account is being migrated, you will be logged out and prompted to log back in within minutes using Adobe Identity after the migration.

* **Benefits**: Authenticate Marketo Engage and other Adobe products by using a single Adobe identity&mdash;either an Adobe ID or Adobe Federated ID (SSO).

**What You Need to Do:**

`1.` **Prepare**: Email verification is required for you to be migrated to an Adobe Identity.

i. You have received an Email Verification Request email with a link (stays valid for 3 days). If your link is expired, you can resend the verification email from within Marketo Engage by clicking your "My Profile" icon, then navigating to **My Account** > **Account Settings** > **Resend Verification**.

ii. An active user session is required for the email verification success. Please sign in to your Marketo Engage subscription using your identity provider (IdP) URL first.

`2.` **Onboard**: Once your user account is migrated, you will receive an email from Adobe regarding the changes to your sign-in method.

i. Accept the new invitation by clicking the 'Accept Invitation' button and signing in using Adobe Identity.

ii. On the Adobe login page, please sign in with an existing Adobe ID.

iii. You must first log in to the Marketo Engage instance for any previously bookmarked URL on the engage-xx.marketo.com domain you're navigating to.

`3.` **Contact**: If you have any questions or need assistance after your account is migrated, or if your account isn't migrated and you lost access to Marketo Engage, please reach out to the Marketo Engage migration team at `[your internal contact email/phone]`.

We appreciate your cooperation during this transition. Thank you for your understanding and commitment to keeping our systems secure.

Regards,

`[Your Name]`

+++
