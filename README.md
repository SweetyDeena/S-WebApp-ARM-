Publish Azure Static Web Apps using an ARM Template

Using these templates, we can deploy Azure Static Web Apps.

Running the deployment
->To deploy a template, sign in to either the Azure CLI or Azure PowerShell
     az login
     
->Create a resource group
     az group create --name resourceGroupName --location "Central US"
     
->Deploy template
     az deployment group create --name DeployLocalTemplate --resource-group $resourceGroupName --template-file <PATH-TO-demoapp.JSON> --parameters <PATH-TO-demoapp.PARAMETERS.JSON> 
  
   

  
 
