# New Azure Subscription

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fans-cloud%2Fazure_service_catalogue%2Fmaster%2Fsubscription-deployment%2FazureDeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fans-cloud%2Fazure_service_catalogue%2Fmaster%2Fsubscription-deployment%2FazureDeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template will create a new Azure Subscription.

You must have an owner, contributor, or Azure subscription creator role on an invoice section or owner or contributor role on a billing profile or a billing account to create subscriptions.

Additionally, since you are doing an ARM template deployment, you need to have write permissions on the root object. So if you're creating the ARM deployment under a management group, you need to have write permissions on the management group. Note that the action is purely to create an ARM deployment, if a subscription is created, it is created only in the management group specified in the ARM template.

You will need details of you billing accounts and invoices to proceed. Visit <a href=https://docs.microsoft.com/en-us/azure/cost-management-billing/manage/programmatically-create-subscription?tabs=rest-getEnrollments%2Crest-EA%2Crest-getBillingAccounts%2Crest-getBillingProfiles%2Crest-MCA%2Crest-getBillingAccount-MPA%2Crest-getCustomers%2Crest-getIndirectResellers%2Crest-MPA#create-subscriptions-using-arm-templates> here </a> for a description of how to obtain these details