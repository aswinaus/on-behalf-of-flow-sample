Demonstrate On-Behalf-Of flow. Acquire a token using MSAL JS 2.0 and call the backend api which performs SharePoint operations impersonating the user represented by userAssertion, using the OBO flow.

Pre-requisites for setting up this sample application

Create a sharepoint list call it as OBOTest
Update the Web.config with Tenant, Audience, ClientId, AppKey, AADInstance, RedirectUri.
Update the App.config with Tenant, ClientId, AADInstance, TodoListScope(Backend app with Sharepoint permissions), TodoListBaseAddress
Update the TodoListController.cs with AzureADAppId, certificateThumbprint(thumbprint of the certificate uploaded to App which is registered in AAD with SharePoint permissions,spscopes(SharePoint Tenant with .default) and tenantId.
