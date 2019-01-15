# Clean-up Azure deployments
Azure Powershell commands to clean up `old` deployments within Azure.

## Examples 

1. Leave the last 75 deployments in a resource groupwhere a single resource group is defined  (i.e. via `Azure DevOps`)

    Optimize-ResourceGroupDeployments 
    
    
1. Leave the last 50 deployments in the resource group `cleanme`

    Optimize-ResourceGroupDeployments -ResourceGroupName 'cleanme' -SkipLast 50
