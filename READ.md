## 1. Open Azure Container Apps

I opened the Azure Portal and selected **Container Apps**.

![Azure Container Apps](screenshots/01-container-apps.png)
## 2. Configure Basics

I configured the Container App with the following settings:

- Resource Group: `az104-rg9`
- Container App Name: `my-app`
- Region: `East US`

![Basics Configuration](screenshots/02-basics.png)
## 3. Create Container Apps Environment

I created a new Container Apps Environment named `my-environment`.

![Container Apps Environment](screenshots/03-environment.png)
## 4. Configure Container

I enabled the quickstart image and selected **Simple hello world container**.

![Container Configuration](screenshots/04-container.png)
## 5. Configure Application Ingress

I enabled application ingress and configured the application to accept external traffic on port `80`.

![Application Ingress](screenshots/05-ingress.png)
## 6. Review and Create

I reviewed the configuration and verified that the validation passed before creating the Container App.

![Review and Create](screenshots/06-review-create.png)
## 7. Deployment Completed

The Azure Container App deployment completed successfully.

![Deployment Completed](screenshots/07-deployment.png)
## 8. Container App Overview

After deployment, I opened the Container App overview and verified the Application URL.

![Container App Overview](screenshots/08-overview.png)
## 9. Test the Application

I opened the Application URL in a browser and verified that the Hello World application was running successfully.

![Hello World Application](screenshots/09-hello-world.png)

