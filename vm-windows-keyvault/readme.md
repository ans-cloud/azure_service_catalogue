# Windows Virtual Machine Deployment with KeyVault integration

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fans-cloud%2Fazure_service_catalogue%2Fmaster%2Fvm-windows-keyvault%2FazureDeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fans-cloud%2Fazure_service_catalogue%2Fmaster%2Fvm-windows-keyvault%2FazureDeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template allows you to deploy a simple Windows VM using a few different options for the Windows version, using the latest patched version. This will deploy  VM in the resource group location and return the fully qualified domain name of the VM. You will also specify an IP address or IP address range for allowed RDP access as well as specifiying tag values for the VM owner, environment, application and business criticality.

The parameters file can be used to specify a keyvault and secret rather than using a clear text password.