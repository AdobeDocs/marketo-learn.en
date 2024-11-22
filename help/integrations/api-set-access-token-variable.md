---
title: Marketo How to API Video - How to set the Access token in a variable
description: Learn how to set up the Postman application and how to leverage variables to save data into the variable for reusability purposes.
feature: REST API
role: Admin, Developer
level: Advanced
doc-type: Technical Video
duration: 772
last-substantial-update: 2024-08-06
jira: KT-15548
exl-id: 4da86ed6-1072-4e0e-a648-16587badaeb3
---
# API Help - How to set the Access token in a variable

Learn how to set up the Postman application and leverage variables to save data into the variable for reusability purposes. You will also learn how to make your first Marketo Engage REST API call to get the access token.

>[!PREREQUISITES]
>
>Before starting this video, create an API Only username with an AOI role and create a Launchpad service. Follow the steps in the articles below:
>
>* [Create an API Only User Role](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/users-and-roles/create-an-api-only-user-role){target="_blank"}
>
>* [Create an API Only User](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/users-and-roles/create-an-api-only-user){target="_blank"}
>
>* [Create a Custom Service for Use with REST API](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/additional-integrations/create-a-custom-service-for-use-with-rest-api){target="_blank"}

**References used in this video:**

* Marketo auth endpoint: `{{{}base_url{}}}/identity/oauth/token?grant_type=client_credentials&client_id={{{}client_id{}}}&client_secret={{{}client_secret{}}}`

* JS script to grab acccess_token from the response body (places under the Scripts: tab):

```
var jsonData = pm.response.json();
pm.environment.set("access_token", jsonData.access_token);
```

* [Marketo Engage Developers documentation](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication){target="_blank"}

>[!VIDEO](https://video.tv.adobe.com/v/3429275/?learn=on)
