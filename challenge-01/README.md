# DevOps Project Challenge: Deploying a Flask Application on EKS using Terraform

## Overview

This project involves the deployment of an Amazon EKS (Elastic Kubernetes Service) cluster using Terraform. The primary objective is to containerize and deploy a Python Flask application within this environment. Key components of this challenge include the creation of a VPC, deployment of a managed EKS cluster, containerization of the Flask application, and the use of Helm charts for deployment. Additionally, the project will incorporate ArgoCD for continuous deployment and utilize an Ingress controller for application exposure.

## Detailed Instructions

1. **VPC Creation**
   - Construct a Virtual Private Cloud (VPC) ensuring an adequate number of IP addresses. While a 10.0.0.0/16 CIDR range is recommended, you are free to select an alternative CIDR range that suits the project requirements.

2. **EKS Cluster Deployment**
   - Utilize Terraform to deploy an Elastic Kubernetes Service (EKS) cluster.
   - The cluster should include a managed Node group to ensure efficient scaling and management.

3. **Python Flask Containerization**
   - Dockerize a Python Flask application. Ensure that the container is optimized for a Kubernetes environment.

4. **Helm Chart for Flask Application**
   - Develop a Helm chart for the deployment of the Python Flask application. This chart should define all necessary Kubernetes resources and configurations.

5. **ArgoCD Integration**
   - Deploy ArgoCD within the EKS cluster.
   - Configure ArgoCD to manage the deployment of the Flask application, ensuring continuous deployment is achieved.

6. **Application Exposure via Ingress Controller**
   - Expose the Flask application externally using an Ingress controller.
   - You may choose between ALB (AWS Load Balancer) Ingress or Nginx Ingress controller, based on your preference or project requirements.

## Expected Outcomes

By the end of this challenge, you will have a fully functioning EKS environment with a deployed Python Flask application, managed via ArgoCD and accessible through an Ingress controller. This setup should demonstrate proficiency in key DevOps practices, including infrastructure as code, containerization, continuous deployment, and Kubernetes resource management.
