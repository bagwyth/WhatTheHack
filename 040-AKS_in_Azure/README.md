# AKS - Integration with Azure Components

## Introduction

This What The Hack has an objective studying in depth the integration surface between AKS and different Azure services. Some are optional components (for example monitoring), but others are required to successfully operate Kubernetes clusters on Azure (such as networking or storage).

## Learning Objectives

In this hack you will start by deploying a 3-tier application to AKS with very specific networking requirements.

The complexity will quickly evolve towards security and storage, finishing with the last challenge focusing on Arc technology.

## Challenges

- Challenge 1: **[Containers](Student/01-containers.md)**
   - Get familiar with the application for this hack, and roll it out locally or with Azure Container Instances
- Challenge 2: **[Networking](Student/02-aks_private.md)**
   - Deploy the application in an AKS cluster with strict network requirements
- Challenge 3: **[Monitoring](Student/03-aks_monitoring.md)**
   - Monitor the application, either using Prometheus or Azure Monitor
- Challenge 4: **[Secrets](Student/04-aks_secrets.md)**
   - Harden secret management with the help of Azure Key Vault
- Challenge 5: **[Security](Student/05-aks_security.md)**
   - Explore AKS security concepts such as Azure Policy for Kubernetes
- Challenge 6: **[Storage](Student/06-aks_storage.md)**
   - Evaluate different storage classes by deploying the database in AKS
- Challenge 7: **[Service Mesh](Student/07-aks_mesh.md)**
   - Explore the usage of a Service Mesh to further protect the application
- Challenge 8: **[Arc for k8s/data](Student/08-arc.md)**
   - Leverage Arc for Kubernetes to manage a non-AKS cluster, and Arc for data to deploy a managed database there

You can find the source code and documentation for the required containers [here](Student/resources/README.md).

## Prerequisites

- Access to an Azure subscription (owner privilege is required in some exercises)

## Contributors

- Adrian Joian
- Gitte Vermeiren
- Jose Moreno
- Victor Viriya-ampanond