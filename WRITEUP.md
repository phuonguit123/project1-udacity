# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

*For **both** a VM or App Service solution for the CMS app:*
- Cost: comparison between a VM and an App Service in the same tier, a VM is cheaper than an App Service, for example, when I choose basic
tier and choose dev/test lisence, West US region, the same OS for both VM and App Service, the cost for a VM is 32.12 (instance A1)
while the cost for an App Service is 54.75 (instance B1).
- Scalability: Azure App Service can be scaled up to 100 instances with app service environment, a VM can be scaled up to 1000 nodes per scale set,
a VM can be scaled up in the future, it's easier to scale apps horizontally or vertically in Azure App Service,  based on the pricing tier.
- Availability: With many datacenters in the world, my apps can be available in any Microsoft's infrastructure. The monthly uptime percentage is about 99%,
this is a high number
- Workflow: Developers can easily deploy their apps in App Service to build, test, etc..., because App Service supports many platform such as GitHub,...,
and easier to configure to deploy than VMs

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
- If I want to choose an exact number of CPU or RAM to scale in the future, VMs can help me that, because the Azure App Service doesn't allow me to 
type the number I want.
- Because the App Service is PaaS, so I can't change the OS I want in the future, but with VMs, I can do that.
- If I want to use the programming language that App Service does not support, I will use VMs to install the programming language I need easily.