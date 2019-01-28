# Retrieving_Values_From_KeyVault_Azure
The following code shows how to retrieve values from your key vault once assigned permissions in Azure

<h1>Classes To Add</h1>
<ul>
   <li>KeyVault.cs</li>
</ul>

<h1>Dependacies Required</h1>

The two dependacies below allow you to access the key vault using your current directory for authentication. It testing this is the user
and once deployed this becomes the app. You must grant access to the Key Vault in azure to the user or app to get the Key Vault Values.

<ul>
    <li>"Microsoft.Azure.KeyVault"</li>
    <li>"Microsoft.Azure.Services.AppAuthentication"</li>
</ul>
