# Cluster connection

### Connect to the cluster

###### Install the Azure CLI

Follow instructions for your OS on https://docs.microsoft.com/en-us/cli/azure/install-azure-cli


###### Login to azure
````bash
az login
````

###### Install kubectl (if not already installed)
````bash
az aks install-cli
````

###### Connect the kubectl cli

````bash
az aks get-credentials --resource-group ArcticRiskPlatform --name production
````
