---
title: Essential Program Pre-launch QA Process for Success
description: Learn how you as a Marketo Engage admin can develop a program pre-launch QA process to help your internal teams build and launch programs more accurately and efficiently.
feature: Administration


role: Admin
level: Beginner
doc-type: Tutorial
last-substantial-update: 2023-09-08
jira: KT-13888
thumbnail: KT-13888.jpeg
---

# Essential Program Pre-launch QA Process for Success

Learn how you as a Marketo Engage admin can develop a program pre-launch QA process to help your internal teams build and launch programs more accurately and efficiently. We use the Program Pre-launch Checklist authored by Adobe Marketo Champion, Grace Brebner, as an example, and walk you through the key elements to watch out for and requirements for each.

If you are a Marketo Engage admin or on the Marketing Operation team, reviewing the program configuration properly is crucial to avoid customer-facing mistakes. Though you can learn from your mistakes along the way to limit mistakes, it will not be a scalable process. Designing and running a program pre-launch QA process between builders and power users/reviewers helps save you time, prevent errors, and train your internal users more quickly.

In this tutorial, you willlearn how a Marketo Engage admin can develop a program pre-launch QA process to help your internal teams scale. We will use the Program Pre-launch Checklist authored by Adobe Marketo Champion, Grace Brebner, as an example, and walk you through the key elements and requirements.

## Why you should design a program pre-launch QA process?

If you are newer to Marketo Engage, you may not know what to check for when building out a program. Even for seasonal Marketo Engage admins, reviewing the programs based on your memory is risky. This is when a program pre-launch checklist comes into play. It not only helps drive your program QA processes more smoothly, but also trains your builders to look out for common pitfalls.

* **Timesaving:** Without having an established QA process in place, it will ultimately add time to your program build process and take more time to take your marketing programs to the market. Once you set up your own program pre-launch list and have your internal users familiarize themselves with the QA process, they become more accurate in program configuration by using it.
* **Self-enablement:** Having your Marketing team go through the checklists that are relevant to the programs they are building provides a structured curriculum to train your internal users. Every time they work through the checklist to perform self-review, it builds up their muscle memory. Even if you are an experienced Marketo Engage admin reviewing others' programs, having a checklist to check off prevents you from overlooking common pitfalls.

## Get started with designing your program prelaunch QA process.

**Step 1:** To start off, answer the following questions to think through your QA process:

Who will be able to serve the reviewer and approver role? If you are in a smaller organization, the Marketo Engage admins may play hybrid roles of Marketing and Marketing Operations. It is recommended that you have a non-builder Marketo Engage Consider power users to audit the programs. A new pair of fresh eyes helps spot issues.

How would the builders and the reviewers collaborate and document notes and changes? You could keep things organized in a spreadsheet or within a project management platform. Reference the checklist below and convert the template into the format that works best for your organization. Your team can simply clone the template each time they build and review the program for launch.

**Step 2:** Now go through the program prelaunch checklists line by line to familiarize yourself with the program QA scope.

Rules of thumb to keep in mind:

* This program pre-launch checklist isn't designed to be one size fits all. Use what's relevant, ignore or delete what's not, and customize it for your organization's needs. You could also divide up the checklists to use only pieces that are relevant to your program build.
* You should define your requirements clearly. Consider your acceptance criteria for each element and edit them in your offline template.

**Step 3:** Develop a guideline for your internal teams to use the program prelaunch checklist and test run the QA process until it's more streamlined. Here's an example:

* Builders should clone the program prelaunch checklist to check, note, and approve as they go down the checklist.
* Have your builders do a self-review in one column and have the reviewers document their notes in another column next to the requirements.
* Only have the reviewers fill out the 'Final Checks' section. This section asks the reviewer to repeat several key checks to ensure that changes are made properly throughout the QA process.

**Step 4:** There may be items that are missing or not applicable as your team conducts this exercise a few times. Revisit this checklist (for example, quarterly) to update the review items and acceptance criteria to fine-tune your program QA process.

## Example Template: Program Pre-launch Checklist

>[!BEGINTABS]

>[!TAB Key Details and Planning]

|#|Review|Questions to ask|Example|Acceptance Criteria|Additional Resources|
|---|---|---|---|---|---|
|1|**Program type**| Is it appropriate? |If an Engagement program, is it logical? If Default, is it logical?| If you cannot answer this question with a **yes**, you may need to change your program type.| [Understanding Programs](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.html)|
|2| **Channel**|Is the channel appropriate? Do the Channel Steps / program statuses support the program's success management? | If set up as a newsletter, does this make sense and do the program statuses support the purpose of the program, or are you trying to twist something pre-existing but not suitable?| If you cannot answer this question with a **yes**, you need to either change your channel or discuss the creation of a new one with a Marketo Engage admin| [Create a Program Channel](https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/create-a-program-channel.html)|
|3|**Program Naming Convention**| Is this set following your naming conventions correctly? Link to your naming convention tool or spreadsheet if you have one.| Formula: [PROGRAM TYPE] - [DATE] [CATEGORY]: [SHORT DESCRIPTION]|If you cannot answer this question with a **yes**, or aren't sure, review your naming conventions and if necessary, update the name of your program.||
|4|**Period Cost**|Has the program had a period cost tag assigned?||If you cannot answer this question with a **yes**, add a period cost in, even if it's just zero! |[ Using Period Costs in a Program](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/programs/working-with-programs/using-period-costs-in-a-program.html)|
|5|**Success**| Has the program's objective and success metric been clearly identified? Do you know how you're going to measure it? Is it being marked with a program status change?||If you cannot answer this question with a **yes**, you will not have an easy means of understanding whether your campaign had any impact. Identify what your primary objective is, and then a means of measuring it - even if it's a manual list import after 7 days.||
|6|Audience|Has the program's audience been clearly identified?||If you cannot answer this question with a **yes**, find out before you plan to send.||
|7|**Tokens**|Have all required program tokens been updated?||**Yes, or N/A**: If you can't answer with a yes, or don't know whether it applies, check your program 'Tokens' tab, and see whether the program contains any local tokens that must be updated||[Understanding My Tokens in a Program](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program.html)|

>[!TAB Web Personalization Campaigns]

|#|Review|Questions to ask|Acceptance Criteria|
|---|---|---|---|
|1|**Design**|Is the design consistent with your brand guidelines?|Is the segment chosen appropriate, and does it apply to the right domains? Is the segment being sent to Google Analytics?|
|2|**Testing**|Has it been tested across devices? browsers? Does it both render cleanly and function?| If you cannot answer with a yes, you should test this across devices and browsers.|
|3|**Data**|Has it been tested across devices? browsers? Does it both render cleanly and function?|If you cannot answer with a yes, you should test this.|
|4|**Tracking**|If you have a form in the campaign, are hidden UTM fields in place to track sources of submissions? Have these been tested?|**Yes or no:** If you answer no, understand that your ability to track which sources directed people to this form will be limited.|
|5|**GDPR/CASL Compliance**|If data is captured through the form, is the opt-in compliant and do you provide a collection statement with a functioning Privacy Policy link?|Understand your relevant compliance environment: if you cannot answer this question with a yes, you must update the Privacy Policy section to ensure it is compliant. **If you do not know, seek appropriate advice from your Legal team.**|
|6|**Google Analytics Integration**|Is your Web Personalization integrated with Google Analytics?|**Yes or no**: If answering no, understand that your ability to track what web personalization impact will be limited.|
|7|**Segments**|Is the segment chosen appropriate, and does it apply to the right domains? Is the segment being sent to Google Analytics?|If you cannot answer with a yes, you need to update it.|

>[!TAB Forms]

|#|Review|Questions to ask|Acceptance Criteria|
|---|---|---|---|
|1|**Responsive**|Is the form device responsive?|f you cannot answer this with a yes, you should update the CSS to make it responsive or it may impact your performance.|
|2|**Design**|Is the design of the form brand consistent?|If you cannot answer this with a yes, you either need a good reason for it or you must update the CSS to make it on brand.|
|3|**Data Flow**|Does all data map to fields as intended? Have you checked a test record's activity log to prove this?|If you cannot answer with a yes, you should fix and test the mapping.|
|4|**Tracking**|Are hidden UTM fields in place to track sources of submissions to this form? Have these been tested?|Yes or no: If answering no, understand that your ability to track what sources directed people to this form will be limited.|
|5|**GDPR/CASL Compliance**|If data is captured through the form, is the opt-in compliant and do you provide a collection statement with a functioning Privacy Policy link?|Know your relevant compliance environment: If you cannot answer this question with a yes, you must update to ensure it is compliant. If you do not know, seek appropriate advice.|

>[!TAB Smart Campaigns]

|#|Review|Questions to ask|Acceptance Criteria|
|---|---|---|---|
|1|**Accuracy**|Have all necessary Smart Campaigns been checked, reviewed, and considered accurate?|If you cannot answer with a yes, you should fix and check these before proceeding.|
|2|**Send count**|If your email sending campaign is a batch campaign (not triggered) look at the count of leads in the 'schedule' tab - do the numbers align to what you expect? Is it below the abort threshold?|If you cannot answer with a yes, you should fix and check these before proceeding.|
|3|**Master Rules**|Are master segmentations/lists being used if appropriate or where appropriate?|**Yes / N/A**.: Master lists/segmentations are designed to reduce the number of fields you must reference and reduce the risk of human error. You should be very confident of your rules if not using master lists/segmentations.|
|4|**Attribution**|If the program is acquiring new leads (e.g., an event program) are attribution settings included as required? Is the acquisition program being mapped?|**Yes / N/A:** If you are importing leads to your program, or your program will be acquiring new leads, you should have acquisition program settings used.|
|5|**Engagement Programs**|If documenting an engagement program, are there campaigns in place to ensure members are added, paused, and restarted as appropriate? Have these steps been sense-checked by others?|**Yes / N/A:** If this is an engagement program, and you cannot answer with a yes without good reason, don't activate until this is in place.|
|6|**Subscription Preferences**|Have all necessary subscription preference factors been included? |**Yes / N/A:** If you're unsure, ask your Marketo Engage admin. You'll need a good reason to proceed with N/A (e.g., operational sends).|
|7|**Program Status**|Are there flow steps included to update program statuses? |f you cannot answer with a yes, you should to add these into your smart campaign flow steps (see [Change Program Status- Product Documentation](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-campaigns/program-flow-actions/change-program-status.html))|
|8|**Broader Impact**|Are any flow steps sending alerts/writing to fields that sync to other teams/systems? If so, has volume been considered and have stakeholders for those teams/systems been advised?  |**Yes / No / N/A:** Any answer is okay but if it does map you should usually inform the team that owns the system. If you're not sure, ask your admins.|
|9|**Scoring Impact**|Have any implications to lead scoring been considered? |**Yes / N/A:** If you can't answer yes or not applicable, ask your admin.|
|10|**RCM Impact**|Have any implications to the lead lifecycle model been considered?||
|11|**Nurture Impact**|Have any implications to existing nurture programs been considered? Have you ensured people will not be bombarded by multiple communications?|   **Yes / N/A:** If you can't answer yes or not applicable, ask your admin.|
|12|**Reporting Success**|Is program success being measured logically? Is the success reasonable - not too close in the process? Not too far to achieve? Do you have a strategy for how you will report on and measure success to communicate internally?|If you can't answer yes, rethink your success metric definition.|

>[!TAB Lists]

|#|Review|Questions to ask|Acceptance Criteria|
|---|---|---|---|
|1|**Logic**|If smart lists are being used to identify any part of the audience, has the logic been checked, reviewed, and considered accurate?|If you cannot answer with a yes, you should fix the smart list set up, and check these before proceeding.|
|2|**List Import Processes**|If static lists are being used to identify any part of the audience, is the data source trustworthy and has the import been done accurately & according to your list import processes?|If you cannot answer with a yes, you should fix the list data and check these before proceeding.|
|3|**Exclusions**|Are any required exclusions being included (for example competitors, unsubscribe, black blocklists)| **Yes / N/A:** You must have unsubscribes filtered out unless you have a very good, legally compliant reason not to. You should be very confident of your content, campaign rules and legal basis if not including any of these.|
|4|**Master Lists**|Are master lists/segmentations being used where appropriate?    |**Yes / N/A:** Master lists/segmentations are designed to reduce the number of fields you must reference and reduce the risk of human error. You should be very confident of your rules if not using master lists/segmentations.|

>[!TAB Audience]

|#|Review|Questions to ask|Acceptance Criteria|
|---|---|---|---|---|
|


>[!TAB Email Asset Testing Checklist]

|#|Review|Questions to ask|Acceptance Criteria|
|---|---|---|---|---|
|1|||||
|2|||||
|3|||||
|4|||||
|5|||||
|6|||||
|7|||||
|8|||||
|9|||||
|10|||||
|11|||||
|12|||||
|13|||||
|14|||||
|15|||||
|16|||||
|17|||||
|18|||||
|19|||||
|20|||||
|21|||||
|22|||||

>[!TAB Final Checks - BEFORE YOU HIT SEND]

|#|Review|Questions to ask|Acceptance Criteria|
|---|---|---|---|---|
|1|||||
|2|||||
|3|||||
|4|||||

>[!TABSEND]

## What's Next?

Click here[LINK] to download the editable program pre-launch checklist for you to customize. Remember this should be adapted to suit your organization's workflow. Developing an effective QA process keeps you accountable and limit customer-facing mistakes.

### Authors

**Grace Brebner** - Adobe Marketo Champion 
*Director of Client Strategy, APAC Region, 
Digital Pi, LLC - A Merkle Company*

**Amy Chiu**
*Adoption & Retention Marketing Manager
Adobe*
