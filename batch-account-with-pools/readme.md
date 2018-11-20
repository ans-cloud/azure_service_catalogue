# Azure Batch Account and Pool

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fans-cloud%2Fazure_service_catalogue%2Fmaster%2Fbatch-account-with-pools%2FazureDeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fans-cloud%2Fazure_service_catalogue%2Fmaster%2Fbatch-account-with-pools%2FazureDeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

Use Azure Batch to run large-scale parallel and high-performance computing (HPC) batch jobs efficiently in Azure. Azure Batch creates and manages a pool of compute nodes (virtual machines), installs the applications you want to run, and schedules jobs to run on the nodes.

This template creates an Azure Batch account, Storage Account resources and a Batch Pool using a Windows image selected from the Azure Marketplace. The nodes within the pool will be configured with Automatic Updates enabled.