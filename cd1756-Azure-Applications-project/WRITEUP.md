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
a VM can be scaled up in the future