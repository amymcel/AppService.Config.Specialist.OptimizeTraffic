# OptimizeTraffic2AppService
App Service Lab Configuration for ELX Config Specialize Training

[![Deploy To Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https://raw.githubusercontent.com/amymcel/AppService.Config.Specialist.OptimizeTraffic/main/azuredeploy.json)


## This arm deployment will:

1. Crate two App Service Plan - one in East US, one in West US
2. Create two App Services - one under each app service plan
3. Create a virtual network
4. Create an Application Gateway on the virtual network
5. Create a public IP address for the Application Gateway
6. Create an Azure Front Door resource

