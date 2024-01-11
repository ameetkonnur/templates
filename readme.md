---
description: This template will deploy jugalbandi resources to your Azure Subscription.
page_type: sample
products:
- azure
- azure-resource-manager
- azure-open-ai
- azure-speech
- azure-translate
- azure-container-app
- azure-storage
languages:
- json
---
# Create Jugalbandi QA Service API on Azure

This ARM template requires you to have atleast Contributor Permissions at the Subscription Level.

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Fsubscription-deployments%2Fsubscription-role-assignment%2Fazuredeploy.json)


*NOTE: Role assignments use a GUID for the name, this must be unique for every role assignment on the subscription.  The roleAssignmentName parameter is used to seed the guid() function with this value, change it for each deployment.  You can supply a guid or any string, as long as it has not been used before when assigning the role to the subscription.*
