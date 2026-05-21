# Terraform EKS Cluster ☸️🚀

![Terraform](https://img.shields.io/badge/IaC-Terraform-7B42BC?style=for-the-badge&logo=terraform)
![AWS](https://img.shields.io/badge/Cloud-AWS-232F3E?style=for-the-badge&logo=amazonaws)
![Kubernetes](https://img.shields.io/badge/Orchestration-Kubernetes-326CE5?style=for-the-badge&logo=kubernetes)
![Docker](https://img.shields.io/badge/Container-Docker-blue?style=for-the-badge&logo=docker)
![DevOps](https://img.shields.io/badge/DevOps-Cloud_Native-black?style=for-the-badge&logo=devops)
![GitHub](https://img.shields.io/badge/Version_Control-GitHub-black?style=for-the-badge&logo=github)

---

# 📌 Overview

This repository demonstrates how to provision a fully automated **Amazon EKS (Elastic Kubernetes Service) Cluster** using **Terraform Infrastructure as Code (IaC)**.

The project is designed for DevOps and Cloud engineers who want to automate Kubernetes cluster creation on AWS using Terraform best practices.

It includes:

- AWS EKS Cluster Setup
- Terraform Infrastructure Automation
- VPC & Networking Configuration
- EKS Managed Node Groups
- IAM Roles & Policies
- Security Groups
- Kubernetes Cluster Provisioning
- kubectl Configuration
- Scalable Infrastructure Deployment

Amazon EKS is a managed Kubernetes service that simplifies running Kubernetes on AWS. Terraform is commonly used to provision and manage EKS infrastructure declaratively. :contentReference[oaicite:0]{index=0}

---

# 🚀 Features

- Infrastructure as Code (IaC)
- Automated EKS Cluster Provisioning
- AWS Cloud Automation
- Kubernetes Cluster Setup
- Managed Node Groups
- Terraform Modules
- VPC & Subnet Configuration
- IAM Role Automation
- Scalable Infrastructure
- Production-Ready Deployment Workflow

---

# ☸️ What is Amazon EKS?

Amazon Elastic Kubernetes Service (EKS) is a managed Kubernetes service that allows users to deploy, manage, and scale containerized applications using Kubernetes on AWS infrastructure. :contentReference[oaicite:1]{index=1}

---

# 🏗️ Architecture

```text
Developer
    │
    ▼
Terraform Configuration
    │
    ▼
AWS Infrastructure
    │
    ├── VPC
    ├── Subnets
    ├── Security Groups
    ├── IAM Roles
    ├── EKS Control Plane
    └── Worker Nodes
    │
    ▼
Kubernetes Cluster
