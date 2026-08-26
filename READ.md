# LAB 09c - Implement Azure Container Apps

## Overview

In this lab, I implemented and deployed an Azure Container App using Azure Portal.

The lab demonstrates how to create an Azure Container Apps environment, deploy a containerized application, configure application ingress, and verify the application through its public URL.

---

## Architecture

```text
Azure Subscription
        |
        v
Resource Group: az104-rg9
        |
        v
Container Apps Environment
my-environment
        |
        v
Container App
my-app
        |
        v
Simple Hello World Container
        |
        v
Application URL
