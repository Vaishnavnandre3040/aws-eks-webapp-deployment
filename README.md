
# EKS Web Application Deployment Project

## Project Overview

This project demonstrates the deployment of a containerized web application on Amazon EKS (Elastic Kubernetes Service).

The application image was hosted on Docker Hub and deployed to an EKS cluster using Kubernetes Deployments and Services.

## Technologies Used

* AWS EKS
* Kubernetes
* Docker
* Docker Hub
* kubectl
* eksctl
* AWS IAM

## Architecture

User → AWS Load Balancer → Kubernetes Service → Pods

## Implementation Steps

1. Created an EKS Cluster using eksctl.
2. Configured kubectl access to the cluster.
3. Deployed a web application using a Kubernetes Deployment.
4. Created a LoadBalancer Service to expose the application externally.
5. Verified pod availability and service accessibility.
6. Accessed the application using the AWS Load Balancer DNS endpoint.

## Kubernetes Resources

### Deployment

* Deployment Name: webapp-deployment
* Replicas: 4

### Service

* Service Type: LoadBalancer
* Target Port: 80
* Service Port: 8080

## Key Learnings

* Kubernetes Deployments
* Replica Management
* Service Types
* AWS EKS Cluster Management
* Load Balancer Integration
* Rolling Updates
* Pod Scheduling

## Screenshots

Screenshots included in the repository demonstrate:

* EKS Cluster Creation
* Worker Nodes
* Deployments
* Pods
* Services
* Load Balancer
* Application Access
