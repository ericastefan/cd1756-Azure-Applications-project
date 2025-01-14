# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

Cost: Azure App Service is more cost-effective than Virtual Machines. It offers various plan options, including Free and paid plans, to test or deploy an app.

Scalability: Azure App Service includes built-in auto-scaling features, enabling you to scale up or out effortlessly. It automatically adjusts resources based on demand.

Availability: Azure App Service offers global scale with high availability. You can host your app anywhere in Microsoft's  datacenter , and the App Service SLA guarantees high availability.

Workflow: Azure App Service supports automated deployments from GitHub. With GitHub we can create workflows in their GitHub repository to build, test, package, release, and deploy to Azure.

### Assess app changes that would change your decision.

Virtual Machine had too much steps/instructions and prequisites and installs. If it had a more plug-in-play capability like WebApp, I would have chosen it over WebApp.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
