# LAB 09c - Implement Azure Container Apps

## Objective

In this lab, I implemented and deployed an Azure Container App using Azure Portal.

## Architecture

Azure Subscription
    ↓
Resource Group: az104-rg9
    ↓
Container Apps Environment: my-environment
    ↓
Container App: my-app
    ↓
Simple Hello World Container
    ↓
Application URL

## Task 1: Create Azure Container App

### Resource Group

`az104-rg9`

![Resource Group](screenshots/01-container-app.png)

### Container App

Container App name:

`my-app`

Region:

`East US`

![Basics](screenshots/02-basics.png)

### Container Apps Environment

Environment name:

`my-environment`

![Environment](screenshots/03-environment.png)

### Container Image

Quickstart image:

`Simple hello world container`

![Container](screenshots/04-container.png)

### Application Ingress

Ingress was enabled to allow external traffic.

Port:

`80`

![Ingress](screenshots/05-ingress.png)

## Task 2: Test and Verify

The deployment completed successfully.

![Deployment](screenshots/06-deployment.png)

The Container App was running successfully.

I opened the Application URL and verified that the Hello World application was displayed.

![Application](screenshots/07-application.png)

## Key Takeaways

- Azure Container Apps is a serverless platform for running containerized applications.
- Container Apps reduces the need to manage infrastructure.
- Container Apps supports long-running applications and microservices.
- Application ingress allows users to access the application over the internet.
- The application was successfully deployed using the Simple Hello World container.
