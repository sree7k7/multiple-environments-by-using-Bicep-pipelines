# multiple-environments-by-using-Bicep-pipelines
Manage multiple environments by using Bicep and Azure Pipelines

Follow [this](https://learn.microsoft.com/en-us/training/modules/manage-multiple-environments-using-bicep-azure-pipelines/1-introduction) link to get an overview of azure pipelines.

### To create a multi-stage pipeline use the following template:
[template](https://azuredevopsdemogenerator.azurewebsites.net/?name=bicepenvironments)

1. Create the project
2. Clone the repository
3. Open in Visual code
4. create resource groups
 - az group create --name ToyWebsiteTest --location northeurope
 - az group create --name ToyWebsiteProduction --location northeurope
5. Create a service connection
 - 
