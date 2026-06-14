# Kubernetes Multi-Environment Setup

This project demonstrates how to manage multiple environments (Dev, UAT, etc.) within a single Kubernetes cluster using namespaces, labels, and RBAC policies.

## Key Concepts
- **Namespaces**: Isolate environments within the same cluster
- **Labels & Selectors**: Route and organize workloads per environment
- **Deployments & Services**: Separate configurations for each environment
- **ConfigMaps & Secrets**: Environment-specific configurations
- **Ingress Controller (NGINX)**: Manage external traffic routing to services

## Benefits
- Better resource isolation
- Secure access control
- Easy environment management
- Reduced infrastructure cost by using a single cluster

## Example Structure
- dev-namespace
- uat-namespace
- dev-deployment.yaml
- uat-deployment.yaml

## Goal
To safely run multiple environments in one Kubernetes cluster without conflicts, ensuring proper security and separation of workloads.
