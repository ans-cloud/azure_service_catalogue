# Linux Virtual Machine Deployment with KeyVault integration

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fans-cloud%2Fazure_service_catalogue%2Fmaster%2Fvm-linux-keyvaultx%2FazureDeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fans-cloud%2Fazure_service_catalogue%2Fmaster%2Fvm-linux-keyvault%2FazureDeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template allows you to deploy an Ubuntu Linux VM. This will deploy a A2 size VM in the resource group location and return the fully qualified domain name of the VM. You will also specify an IP address or IP address range for allowed SSH access as well as specifiying tag values for the VM owner, environment, application and business criticality.

The password for the VM is specified using a KeyVault Secret. An Azure KeyVault and secret is required to deploy the template.