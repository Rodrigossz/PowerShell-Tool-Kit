# PowerShell Commands for Azure Regions

Listed all in the same file.

## Azure Search Regions

 ```((Get-AzResourceProvider -ProviderNamespace Microsoft.Search).ResourceTypes `
 | Where-Object ResourceTypeName -eq searchServices).Locations```
 
 
 ## Azure Locations and Regions

 ```Get-AzureRmLocation |Format-Table```
 
 
