# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

The chosen deployment solution for this project is Azure App Service.

Justification

Azure App Service was selected because it provides a managed and scalable environment that simplifies application deployment. It eliminates the need to manage operating systems, web servers, and infrastructure configuration, allowing developers to focus on the application itself.

Additionally, App Service offers built-in scaling, high availability, and integration with GitHub for automated deployment, making it an efficient solution for hosting the CMS application. The availability of a free pricing tier also makes it an economical choice for development and educational purposes.
### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
The decision to use Azure App Service may change if the application requirements evolve.

If the application required greater control over the underlying operating system, specialized networking configurations, or installation of custom system-level software, then deploying the application on a Virtual Machine would be more appropriate. A VM would allow full control over server configuration and infrastructure management.

Additionally, if the application needed to support complex background processing, custom security configurations, or advanced networking setups, a VM-based deployment might be necessary. In such cases, the flexibility of managing the infrastructure directly would outweigh the convenience of a managed platform like Azure App Service.