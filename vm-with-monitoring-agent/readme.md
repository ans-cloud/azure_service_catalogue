# Windows Virtual Machine with Log Analytics

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fans-cloud%2Fazure_service_catalogue%2Fmaster%2Fvm-with-monitoring-agent%2FazureDeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fans-cloud%2Fazure_service_catalogue%2Fmaster%2Fvm-with-monitoring-agent%2FazureDeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template allows you to deploy a simple Windows VM using a few different options for the Windows version, using the latest patched version. This will deploy a VM in the resource group location and return the fully qualified domain name of the VM. You will also specify an IP address or IP address range for allowed RDP access as well as specifiying tag values for the VM owner, environment, application and business criticality.

The VM will have an 128GB Managed OS Disk and a 1TB Managed Data Disk attached.

As part of the deployment a new vNet and subnet are also deployed along with a Network Security Group and a Public IP address.

This templatealso installs the Monitoring Agent extension and onboards the VM to a specified workspace. 