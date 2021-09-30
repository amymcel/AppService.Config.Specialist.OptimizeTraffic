# OptimizeTraffic2AppService
App Service Lab Configuration for ELX Config Specialist Training

[![Deploy To Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Famymcel%2FAppService.Config.Specialist.OptimizeTraffic%2Fmain%2Fazuredeploy.json)

## This arm deployment will:

1. Create two App Service Plan - one in East US, one in West US
2. Create three App Services - two under one app service plan, one under the other app service plan
3. Create a virtual network
4. Create an Application Gateway on the virtual network
5. Create a public IP address for the Application Gateway
6. Create an Azure Front Door resource

