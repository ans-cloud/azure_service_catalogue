# Windows Virtual Machine ScaleSet Deployment

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fans-cloud%2Fazure_service_catalogue%2Fmaster%2Fvmss-windows%2FazureDeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fans-cloud%2Fazure_service_catalogue%2Fmaster%2Fvmss-windows%2FazureDeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template will build a Windows Virtual Machine ScaleSet with the version of Windows OS you select. It will also build an accompanying Azure Load Balancer and load balancer rules to allow access to port 80 on the ScaleSet instances.