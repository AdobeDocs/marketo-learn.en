---
title: Essential Program Pre-launch Quality Assurance QA Process for Success
description: Learn how to develop a program pre-launch QA process to help your internal teams build and launch programs more accurately and efficiently.
feature: Administration
role: Admin
level: Beginner
doc-type: Tutorial
last-substantial-update: 2023-10-06
jira: KT-13888
thumbnail: KT-13888.jpeg
---

# Essential program pre-launch quality assurance process for success

If you are a [!DNL Marketo Engage] administrator or on the Marketing Operation team, reviewing the program configuration properly is crucial to avoid customer-facing mistakes. Though you can learn from your mistakes along the way to limit mistakes, it is not a scalable process. Designing and running a program pre-launch quality assurance (QA) process between builders and power users/reviewers helps save you time, prevent errors, and train your internal users more quickly.

In this tutorial, you learn how a [!DNL Marketo Engage] administrator can develop a program pre-launch QA process to help your internal teams scale. The Program Pre-launch Checklist, authored by Adobe Marketo Champion, Grace Brebner, is used as an example to walk you through the key elements and requirements.

## Why should you design a program pre-launch QA process?

If you are newer to [!DNL Marketo Engage], you may not know what to check for when building out a program. Even for seasonal [!DNL Marketo Engage] admins, reviewing the programs based on your memory is risky. This is when a program pre-launch checklist comes into play. It not only helps drive your program QA processes more smoothly, but also trains your builders to look out for common pitfalls.

* **Timesaving:** Without having an established QA process in place, it ultimately adds time to your program build process and take more time to take your marketing programs to the market. Once you set up your own program pre-launch list and have your internal users familiarize themselves with the QA process, they become more accurate in program configuration by using it.
* **Self-enablement:** Having your Marketing team go through the checklists that are relevant to the programs they are building provides a structured curriculum to train your internal users. Every time they work through the checklist to perform self-review, it builds up their muscle memory. Even if you are an experienced [!DNL Marketo Engage] administrator reviewing others' programs, having a checklist to check off prevents you from overlooking common pitfalls.

## Get started with designing your program prelaunch QA process.

**Step 1:** To start off, answer the following questions to think through your QA process:

Who is able to serve the reviewer and approver role? If you are in a smaller organization, the [!DNL Marketo Engage] admins may play hybrid roles of Marketing and Marketing Operations. It is recommended that you have a non-builder [!DNL Marketo Engage] Consider power users to audit the programs. A new pair of fresh eyes helps spot issues.

How would the builders and the reviewers collaborate and document notes and changes? You could keep things organized in a spreadsheet or within a project management platform. Reference the checklist below and convert the template into the format that works best for your organization. Your team can simply clone the template each time they build and review the program for launch.

**Step 2:** Now go through the program prelaunch checklists line by line to familiarize yourself with the program QA scope.

Rules of thumb to keep in mind:

* This program pre-launch checklist isn't designed to be one size fits all. Use what's relevant, ignore or delete what's not, and customize it for your organization's needs. You could also divide up the checklists to use only pieces that are relevant to your program build.
* Define your requirements clearly. Consider your acceptance criteria for each element and edit them in your offline template.

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
|1|**Program type**| Is it appropriate? |If an Engagement program, is it logical? If Default, is it logical?| **Yes:** <br>If you cannot answer this question with a yes, you may need to change your program type.| [Understanding Programs](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.html)|
|2| **Channel**|Is the channel appropriate? Do the Channel Steps / program statuses support the program's success management? | If set up as a newsletter, does this make sense and do the program statuses support the purpose of the program, or are you trying to twist something pre-existing but not suitable?|**Yes:** <br>If you cannot answer this question with a yes, you must either change your channel or discuss the creation of a new one with a [!DNL Marketo Engage] administrator| [Create a Program Channel](https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/create-a-program-channel.html)|
|3|**Program Naming Convention**| Is this set following your naming conventions correctly? Link to your naming convention tool or spreadsheet if you have one.| Formula: [PROGRAM TYPE] - [DATE] [CATEGORY]: [SHORT DESCRIPTION]|**Yes:** <br>If you cannot answer this question with a yes, or aren't sure, review your naming conventions and if necessary, update the name of your program.||
|4|**Period Cost**|Has the program had a period cost tag assigned?||**Yes:** <br>If you cannot answer this question with a yes, add a period cost in, even if it's just zero! |[ Using Period Costs in a Program](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/programs/working-with-programs/using-period-costs-in-a-program.html)|
|5|**Success**| Has the program's objective and success metric been clearly identified? Do you know how you're going to measure it? Is it being marked with a program status change?||**Yes:** <br>If you cannot answer this question with a yes, you won't have an easy means of understanding whether your campaign had any impact. Identify what your primary objective is, and then a means of measuring it - even if it's a manual list import after 7 days.||
|6|**Audience**|Has the program's audience been clearly identified?||**Yes:** <br>If you cannot answer this question with a yes, find out before you plan to send.||
|7|**Tokens**|Have all required program tokens been updated?||**Yes or not applicable** <br>If you can't answer with a yes, or don't know whether it applies, check your program 'Tokens' tab. See whether the program contains any local tokens that must be updated||[Understanding My Tokens in a Program](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program.html)|

>[!TAB Web Personalization Campaigns]

|#|Review|Questions to ask|Acceptance Criteria|
|---|---|---|---|
|1|**Design**|Is the design consistent with your brand guidelines?|**Yes:** <br>If you cannot answer this with a yes, you either need a good reason for it or you must redesign the assets.|
|2|**Testing**|Has it been tested across devices? browsers? Does it both render cleanly and function?|**Yes:** <br>If you cannot answer with a yes, you should test this across devices and browsers.|
|3|**Data**|If there is a form in the campaign, has the form been tested? Do all triggers flow as expected? Do all form fields map accurately? Can you prove this, having checked a persons record's activity log - not just the fields?|**Yes:** <br>If you cannot answer with a yes, you should test this.|
|4|**Tracking**|If you have a form in the campaign, are hidden UTM fields in place to track sources of submissions? Have these been tested?|**Yes or no:** If you answer no, understand that your ability to track which sources directed people to this form is limited.|
|5|**GDPR/CASL Compliance**|If data is captured through the form, is the opt-in compliant and do you provide a collection statement with a functioning Privacy Policy link?|**Yes:** <br>Understand your relevant compliance environment: if you cannot answer this question with a yes, you must update the Privacy Policy section to ensure it is compliant. **If you do not know, seek appropriate advice from your Legal team.**|
|6|**Google Analytics Integration**|Is your Web Personalization integrated with Google Analytics?|**Yes or no:** If answering no, understand that your ability to track what web personalization impact is limited.|
|7|**Segments**|Is the segment chosen appropriate, and does it apply to the right domains? Is the segment being sent to Google Analytics?|**Yes:** <br> If you cannot answer with a yes, you must update it.|

>[!TAB Landing Pages]

|#|Review|Questions to ask|Acceptance Criteria|
|---|---|---|---|
|1|**Design**|Is the design consistent with the brand? <br>Does it use the appropriate template?|**Yes:** <br> If you cannot answer this with a yes, you either need a good reason for it or you must redesign it.|
|2|**Testing**|Has it been tested across devices and browsers? Does it both render cleanly and function?|**Yes:** <br>If you cannot answer with a yes, you should test the preview link across devices and browsers.|
|3|**URL**|Has the page URL been customized? Is it logical/does it follow naming conventions?|**Yes:** <br>If you cannot answer with a yes, you should update the page URL.|
|4|**Meta/OG tags**|Have the OG tags been set? The title, description, images, and so on. These impact how the page displays in social sharing.|**Yes:** <br>If you cannot answer with a yes, you should update all the tags.|
|5|**Robots**|What are the settings? Do they make sense given your needs?||**Yes:** <br>If you cannot answer this with a yes, you should update it.|
|6|**Personalization**|If your page has any personalized elements(for example, Dynamic Content, Snippets) on it, have you tested them? Do they all work as expected?|**Yes / Not applicable** <br>If you can't answer yes or n/a, go test!| 
|7|**Images**| Have all images used been compressed properly? If there is text overlaying any images, is it clearly legible? Do you have the right to use these images & are they on brand?|**Yes / Not applicable** <br> All images (if any are used) should be compressed to improve email load speed.|
|8|**Copy**|Have you reviewed the copy for any grammar errors? Is the copy on tone of voice for your brand? Does your copy make it clear what the page's objective is?|**Yes / Not applicable** <br> If you can't answer yes or N/A, review your copy.|  
|9|**Forms**|If the landing page has a form on it, is the right form being referenced? If you are using a non-Marketo landing page, check the embed code from the form asset page as well, ensure it isn't affected by the old URL structures depreciated in August 2023.|**Yes / Not applicable** <br> If you can't answer yes (or not applicable), fix it!|
|10|**Thank You**|If there's a form on your page, does the page display a success message/redirect to a thank you page on submission as appropriate? |**Yes / Not applicable** <br> If you can't answer yes (or not applicable), fix your post-submission settings.|
|11|**GDPR/CASL Compliance*|If data is captured through the form, is the opt-in compliant and do you provide collection statement w/functioning Privacy Policy link?|**Yes:** <br>Know your relevant compliance environment: if you cannot answer this question with a yes, you must update to ensure it is compliant. If you do not know, seek appropriate advice.|
|12|**Tracking**|Do you have Google Analytics, Tag manager, and/or Munchkin settings applied to the page as intended? Should this landing page have Munchkins on or off by default?|**Yes / Not applicable**<br>If you can't answer yes or not applicable, confirm with your [!DNL Marketo Engage] administrator.| 

>[!TAB Forms]

|#|Review|Questions to ask|Acceptance Criteria|
|---|---|---|---|
|1|**Responsive**|Is the form device responsive?|**Yes:** <br>If you cannot answer this with a yes, you should update the CSS to make it responsive or it may impact your performance.|
|2|**Design**|Is the design of the form brand consistent?|**Yes:** <br>If you cannot answer this with a yes, you either need a good reason for it or you must update the CSS to make it on brand.|
|3|**Data Flow**|Does all data map to fields as intended? Have you checked a test record's activity log to prove this?|**Yes:** <br>If you cannot answer with a yes, you should fix and test the mapping.|
|4|**Tracking**|Are hidden UTM fields in place to track sources of submissions to this form? Have these been tested?|**Yes or no:** If answering no, understand that your ability to track what sources directed people to this form is limited.|
|5|**GDPR/CASL Compliance**|If data is captured through the form, is the opt-in compliant and do you provide a collection statement with a functioning Privacy Policy link?|**Yes:** <br>Know your relevant compliance environment: If you cannot answer this question with a yes, you must update to ensure it is compliant. **If you do not know, seek appropriate advice.**|

>[!TAB Smart Campaigns]

|#|Review|Questions to ask|Acceptance Criteria|
|---|---|---|---|
|1|**Accuracy**|Have all necessary Smart Campaigns been checked, reviewed, and considered accurate?|**Yes:** <br>If you cannot answer with a yes, you should fix and check these before proceeding.|
|2|**Send count**|If your email sending campaign is a batch campaign (not triggered) look at the count of leads in the 'schedule' tab - do the numbers align to what you expect? Is it below the abort threshold?|**Yes:** <br>If you cannot answer with a yes, you should fix and check these before proceeding.|
|3|**Master Rules**|Are master segmentations/lists being used if appropriate or where appropriate?|**Yes or not applicable:** Master lists/segmentations are designed to reduce the number of fields you must reference and reduce the risk of human error. You should be confident of your rules if not using master lists/segmentations.|
|4|**Attribution**|If the program is acquiring new leads (for example, an event program) are attribution settings included as required? Is the acquisition program being mapped?|**Yes or not applicable:** If you are importing people to your program, or your program will be acquiring new people, you should use acquisition program settings.|
|5|**Engagement Programs**|If documenting an engagement program, are there campaigns in place to ensure members are added, paused, and restarted as appropriate? Have these steps been sense-checked by others?|**Yes or not applicable:** If this is an engagement program, and you cannot answer with a yes without good reason, don't activate until this is in place.|
|6|**Subscription Preferences**|Have all necessary subscription preference factors been included? |**Yes or not applicable:** If you're unsure, ask your [!DNL Marketo Engage] administrator. You need a good reason to proceed with N/A (for example, operational sends).|
|7|**Program Status**|Are there flow steps included to update program statuses? |**Yes:** <br>If you cannot answer with a yes, you should add these into your smart campaign flow steps (see [Change Program Status- Product Documentation](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-campaigns/program-flow-actions/change-program-status.html))|
|8|**Broader Impact**|Are any flow steps sending alerts/writing to fields that sync to other teams/systems? If so, has volume been considered and have stakeholders for those teams/systems been advised?  |**Yes, no or not applicable:** Any answer is okay but if it does map you should usually inform the team that owns the system. If you're not sure, ask your admins.|
|9|**Scoring Impact**|Have any implications to  lead / person  scoring been considered? |**Yes or not applicable:** If you can't answer yes or not applicable, ask your administrator.|
|10|**RCM Impact**|Have any implications to the person lifecycle model been considered?|**Yes or not applicable:** If you can't answer yes or cot applicable, ask your administrator.|
|11|**Nurture Impact**|Have any implications to existing Engagement Programs been considered? Have you ensured people will not be bombarded by multiple communications?|   **Yes or not applicable:** If you can't answer yes or not applicable, ask your administrator.|
|12|**Reporting Success**|Is program success being measured logically? Is the success reasonable - not too close in the process? Not too far to achieve? Do you have a strategy for how you report on and measure success to communicate internally?|**Yes:** <br>If you can't answer yes, rethink your success metric definition.|

>[!TAB Lists]

|#|Review|Questions to ask|Acceptance Criteria|
|---|---|---|---|
|1|**Logic**|If smart lists are being used to identify any part of the audience, has the logic been checked, reviewed, and considered accurate?|**Yes:** <br>If you cannot answer with a yes, you should fix the smart list set-up, and check these before proceeding.|
|2|**List Import Processes**|If static lists are being used to identify any part of the audience, is the data source trustworthy and has the import been done accurately & according to your list import processes?|**Yes:** <br>If you cannot answer with a yes, you should fix the list data and check these before proceeding.|
|3|**Exclusions**|Are any required exclusions being included (for example competitors, unsubscribe blocklists)| **Yes or not applicable:** You must have unsubscribes filtered out unless you have a very good, legally compliant, reason not to. You should be confident of your content, campaign rules, and legal basis if not including any of these.|
|4|**Master Lists**|Are master lists/segmentations being used where appropriate?    |**Yes or not applicable:** Master lists/segmentations are designed to reduce the number of fields you must reference and reduce the risk of human error. You should be confident of your rules if not using master lists/segmentations.|

>[!TAB Audience]

|#|Review|Questions to ask|Acceptance Criteria|
|---|---|---|---|
|1|**Legal Basis**|You have an appropriate legal basis for contacting your audience - either: <ul><li>**Explicit:** They have explicitly opted in to receive marketing communications from your brand</li><li>**Inferred (where compliant):** They have provided you with their contact details and can reasonably expect that you will use this information to contact them.</li><li>**Deemed (where compliant):** You have obtained their contact details from a public source and can reasonably assume that the content is relevant to them, given the public source.</li></ul>|**Yes and state the basis:** Be sure whatever basis you choose is valid in your compliance environment. If you cannot answer with a yes, hold off on launching the program and seek clarification regarding the legal basis for contacting this audience.|
|2|**Data Sources**|If you are identifying your audience through an import list, is your data source trustworthy?|**Yes or not applicable:**<br>If you cannot answer with a yes, seek clarification on the data source.|
|3|**List Purchasing**| Has the audience been sourced through list purchasing or sponsorship activities?|**No if source = list purchasing:**<br> List purchasing is bad practice, illegal in many places, and often a breach of your contract with your Marketing Automation platform.<br><br>**Yes, if source = sponsorship** <br>In sponsorship & competition cases, ensure that the data capture was compliant. It is best practice to be clear in the first communication about how you received their info, and to make opt-out easy for people.|
|4|**Relevance**|The information you are about to send this audience is relevant to them and to their relationship with you.|**Yes:** <br>If you cannot answer with a yes, stop and consider carefully why you are sending to these people. Sending information that is not relevant to them or their relationship with you is likely to adversely affect performance and deliverability, and may be a breach in your compliance environment.|
|5|**Expectation**|This audience expects to hear from you.|**Yes:** <br>If you cannot answer with a yes, stop and consider carefully why you are sending to these people. Sending to an audience who does not want or expect to hear from you is likely to adversely affect performance, deliverability, and may be a breach in your compliance environment.|


>[!TAB Email Asset Testing Checklist]

|#|Review|Questions to ask|Acceptance Criteria|
|---|---|---|---|
|1|**Sender email address**|Checked with brand owner, confirmed to be safe for use?|**Yes:** <br>If you cannot answer with a yes, you should check the sender email before proceeding.|
|2|**Sender name**|Checked with brand owner, confirmed to be safe for use?|**Yes:** <br>If you cannot answer with a yes, you should check before proceeding.|
|3|**Reply-to address**|Checked with brand owner, confirmed to be safe for use?|**Yes:** <br> If you cannot answer with a yes, you should check before proceeding.|
|4|**Preheader settings**|Pre-header has been set according to best practice (min. 80 char, full sentences, front load the valuable bits)?|**Yes:** <br><br>If you cannot answer with a yes, you should update before proceeding.|
|5|**Copy Proofing**| No spelling or grammar issues found; tone is brand appropriate?| **Yes:** <br>If you cannot answer with a yes, you should fix before proceeding.|
|6|**Scannability**| Can you comprehend the key information in this email at a scan? | **Yes or not applicable:** <br>Email best practice suggests that it's important to ensure your email's key message can be understood at a scan. If you choose not to apply this practice, be aware it may impact your email's performance.|
|7|**Unsubscribe**|The email has a functional unsubscribe link, which you have tested.|**Yes or not applicable:**<br>Not applicable should only be valid if the email is operational. Be confident that unsubscribe is not required, if in doubt, inclusion is safer.|
|8|**Text Version**| A text version of the email has been created, and you have sent yourself a test of the text version?|**Yes:**<br> If you cannot answer with a yes, you should test before proceeding.|
|9|**Text Version Optimization**|The layout of the text version has been optimized? No HTML comments are visible, all relevant content is included.|**Yes:**<br> Auto-generated text versions can be awful to read - it's worth optimizing them.|
|10|**Text Version Hyperlinks and UTMS**| Hyperlinks work and include UTMs, across:<ul><li>Header section</li><li>Image areas (if included)</li><li>Body</li><li>CTA(s)</li>Footer</li></ul>|**Yes:**<br> If you cannot answer with a yes, you should fix and check these before proceeding. Automatic text versions don't pull through variables reliably!|
|11|**HTML/Main Version**|A HTML/primary version of the email has been created, and you have sent yourself a test of it?|**Yes (unless plain text only):**<br> If you cannot answer with a yes, you should send yourself a test before proceeding.|
|12|**Images**|All images have alt text, and none are broken?|    **Yes or not applicable:**<br>. If you cannot answer with a yes, you should fix and check these before proceeding (unless there are no images).|
|13|**Image Compression**|All images were saved for web from your image-editing software, and then compressed before uploading, and email load time is acceptable?<br><br>*Note: Your Hero Images should be below 120 kb, and all smaller images should be smaller. High load times impact performance.*|**Yes or not applicable:**<br>All images (if any are used) should be compressed to improve load speed.|
|14|**HTML Version Hyperlinks and UTMs**| Hyperlinks work and include UTMs, across:<ul><li>Header section</li><li>Image areas (if included)</li><li>Body</li><li>CTA(s)</li>Footer</li></ul>|**Yes:**<br> Don't send broken links. If you can't answer yes, fix before continuing.|
|15|**Dynamic content**| <li>Does your email have dynamic content in it?</li><li> Have you tested it across multiple scenarios?</li>|**Yes:**<br> If you cannot answer with a yes, you should test this before proceeding.|
|16|**Legal requirements**|<ul><li>Have you misrepresented any offer?</li><li>Are any required disclaimers included in accordance with your compliance environment?</li></ul>|**Yes:**><br> If you cannot answer with a yes, you should fix and check these before proceeding.|
|17|**Peer reviewed**|Have you had another peer [!DNL Marketo Engage] user review your test email?|**Yes:**<br> If you cannot answer with a yes, this should be done before you send.|
|18|**Operational sends**|Has the email been set to operational (meaning that it bypasses unsubscribe settings)? If so, do you have a valid reason for this?|**Yes or No:**<br> If answering with yes, you should have a valid reason for sending as an operational email. If you're not sure, ask your [!DNL Marketo Engage] administrator.|
|19|**A/B and Champ/Challenger Testing**|Are you running any champion/challenger testing on the email?|**Yes or no:**<br>If you're not doing any testing, think about whether you may be missing an opportunity to learn more about your audience.|
|20|**Client Testing**| Have you run the email through your client testing software? (for example, Litmus or Email on Acid or [Marketo Email Deliverability Power Pack](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/email-deliverability-power-pack-how-to-import-a-seed-list.html))<ul><li>Any display issues with major email clients have been identified and either corrected or logged as a non-urgent template fix?</li><li>Any load speed issues have been identified and attempts made to improve?</li><li>Any subject line/preview line issues have been identified and resolved?</li></ul>|**Yes or not applicable:**<br>. If you cannot answer with a yes (unless you don't have testing software) this should be done before you send.|
|21|**Spam Testing**| Have you run the email through spam process?<ul><li>Any blocklisting flags are raised for awareness.</li><li>Any inbox placement/email client flags are identified, potential causes sought and attempts to resolve are made?</li></ul>Use [Marketo's Inbox Tracker functionality](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/inbox-tracker/inbox-tracker-tutorials.html) for this if you have it included in your contract, or tools like Litmus or Email on Acid.|**Yes or not applicable:**<br>If you cannot answer with a yes (unless you don't have testing software) this should be done before you send.|
|22|**Additional Analytics**|Does the email have additional analytics code included?|**Yes or not applicable:**<br>       If you cannot answer with a yes (unless you don't have additional analytics software) this should be done before you send.|

>[!TAB Final Checks - BEFORE YOU HIT SEND]

|#|Review|Questions to ask|Acceptance Criteria|
|---|---|---|---|
|1|**Asset approval**|Ensure that finalized program assets and champion/challenger tests are fully approved and have no final changes in draft mode.|**Yes:**<br> If you cannot answer with a yes, this must be done before you send.|
|2|**Smart Campaign accuracy**|Do the smart campaigns reference the right assets?|**Yes:**<br> If you cannot answer with a yes, this must be fixed before you send.|
|3 |**Checklist steps**|Have all the above checks been completed?    |**Yes:**<br> If you cannot answer with a yes, this should be done before you send.|
|4|**Stakeholder approval**|Has the campaign received final sign-off from stakeholders?|**Yes:**<br> If you cannot answer with a yes, this should be done before you send.|

>[!ENDTABS]

## What's Next?

Click here[LINK] to download the editable program pre-launch checklist for you to customize. Remember this should be adapted to suit your organization's workflow. Developing an effective QA process keeps you accountable and limit customer-facing mistakes.

### Authors

**Grace Brebner** 
Adobe Marketo Champion 
*Director of Client Strategy, APAC Region, Digital Pi, LLC - A Merkle Company*

**Amy Chiu**
*Adoption & Retention Marketing Manager, Adobe*

![Amy Chiu](/help/tutorial-inherited-instance/_assets/authors/Adobe_Author_Amy_Chiu.jpg){width="15%"}
