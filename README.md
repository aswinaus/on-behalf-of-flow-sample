Pre-requisites

Create a sharepoint list call it as OBOTest
Update the Web.config with Tenant, Audience, ClientId, AppKey, AADInstance, RedirectUri.
Update the App.config with Tenant, ClientId, AADInstance, TodoListScope(Backend app with Sharepoint permissions), TodoListBaseAddress
Update the TodoListController.cs with AzureADAppId, certificateThumbprint(thumbprint of the certificate uploaded to App which is registered in AAD with SharePoint permissions,spscopes(SharePoint Tenant with .default) and tenantId.
