# OptimizeTraffic2AppService
App Service Lab Configuration for ELX Config Specialize Training

[![Deploy To Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Famymcel%2FAppService.Config.Specialist.Vnet.2%2Fmain%2Fazuredeploy.json)

## This arm deployment will:

1. Crate two App Service Plan - one in East US, one in West US
2. Create two App Services - one under each app service plan
3. Create a virtual network
4. Create an Application Gateway on the virtual network
5. Create a public IP address for the Application Gateway
6. Create an Azure Front Door resource

