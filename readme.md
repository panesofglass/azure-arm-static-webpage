# Azure Blob Storage Static Web Sites ARM Template

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fpanesofglass%2Fazure-arm-static-webpage%2Fmaster%2Fazuredeploy.json)  [![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fpanesofglass%2Fazure-arm-static-webpage%2Fmaster%2Fazuredeploy.json)

The repository contains a all-in-one ARM template that creates an Azure Blob Storage Static Web sites, deploys html files to it from a git repository, and integrates it with an Azure CDN.

## How it works
The template uses an Azure Container Instance (ACI) to run docker images that uses either the Azure CLI to enable static hosting from blob storage.
