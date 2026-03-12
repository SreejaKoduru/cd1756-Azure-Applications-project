# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

For deploying the CMS application, two possible Azure resources were considered: Microsoft Azure Virtual Machines and Azure App Service. These services were analyzed based on cost, scalability, availability, and workflow.

Cost Analysis

Running an application on Azure Virtual Machines generally results in higher costs because the user must pay for the virtual machine compute resources, storage, networking, and maintenance. Even a small VM instance may incur a noticeable cost if it runs continuously.

In contrast, Azure App Service offers a free tier and several low-cost plans. These pricing options make it a more economical solution for small applications, student projects, and development environments where minimal infrastructure is required.

Scalability Analysis

With Azure Virtual Machines, scaling the application requires manual configuration. Developers may need to resize the VM, create additional VMs, and configure load balancers to distribute traffic. This process requires more time and infrastructure management.

Azure App Service provides built-in scalability features. Developers can easily scale the application vertically by increasing the service plan size or horizontally by increasing the number of instances directly through the Azure Portal. This makes scaling much easier and faster.

Availability Analysis

Ensuring high availability with Azure Virtual Machines requires additional configuration such as availability sets, multiple virtual machines, and load balancers. Without these configurations, a single VM failure could cause the application to go offline.

Azure App Service provides built-in high availability because it runs on Microsoft-managed infrastructure. Azure automatically manages the underlying servers, ensuring that the application remains available even if one host machine fails.

Workflow Analysis

Deploying an application on Azure Virtual Machines requires developers to manage the entire environment, including operating system setup, web server installation, software updates, and security patches. This increases the complexity of the deployment process.

Azure App Service simplifies the workflow by providing a managed hosting environment. Developers can deploy applications directly from GitHub using built-in continuous integration and deployment features. This reduces the amount of infrastructure management required and allows developers to focus more on application development.

The chosen deployment solution for this project is Azure App Service.

Justification

Azure App Service was selected because it provides a fully managed environment that simplifies application deployment and maintenance. Developers do not need to configure or maintain operating systems, servers, or infrastructure components, which significantly reduces operational complexity.

Additionally, Azure App Service offers built-in scalability, high availability, and integration with GitHub for automated deployments. These features make it a suitable platform for hosting the CMS application while keeping deployment simple and efficient. The availability of a free pricing tier also makes it a cost-effective solution for development and educational purposes.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

The decision to use Azure App Service may change if the application requirements become more complex or require greater infrastructure control.

For example, if the CMS application required custom operating system configurations, installation of specialized software, or advanced networking configurations, then deploying the application on Microsoft Azure Virtual Machines would be more appropriate. Virtual Machines provide full control over the operating system and server configuration, which allows developers to customize the environment according to application requirements.

Additionally, if the application needed complex background processing, custom security configurations, or integration with specialized system-level tools, a VM-based deployment would provide the flexibility required to manage these advanced workloads.
