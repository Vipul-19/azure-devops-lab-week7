# Week 7 - DevOps & IaC Lab

## 📋 Project Overview

This project demonstrates Infrastructure as Code (IaC) using Terraform and CI/CD using GitHub Actions to deploy a static website to Azure Storage.

## 🏗️ Architecture

- **Infrastructure**: Azure Resource Group + Storage Account (Static Website)
- **IaC Tool**: Terraform
- **CI/CD**: GitHub Actions
- **Deployment Target**: Azure Storage Static Website

## 📁 Project Structure
```
azure-devops-lab-week7/
├── .github/
│   └── workflows/
│       └── deploy.yml          # GitHub Actions workflow
├── terraform/
│   ├── main.tf                 # Main Terraform configuration
│   ├── variables.tf            # Variable definitions
│   └── outputs.tf              # Output values
├── website/
│   └── index.html              # Static website content
├── RESEARCH.md                 # Terraform vs Bicep analysis
└── README.md                   # This file
```

## 🚀 Deployment Instructions

### Prerequisites

1. Azure subscription
2. Azure CLI installed
3. Terraform installed
4. Git installed
5. GitHub account

### Local Deployment

1. Clone the repository
2. Login to Azure: `az login`
3. Navigate to terraform directory: `cd terraform`
4. Initialize Terraform: `terraform init`
5. Apply configuration: `terraform apply`
6. Note the output URL

### Automated Deployment

Pushes to `main` branch automatically trigger deployment via GitHub Actions.

## 🏷️ Cost Tracking Tags

All resources are tagged with:
- **Environment**: Development
- **Project**: Week7-DevOps-Lab
- **Owner**: Student
- **ManagedBy**: Terraform
- **CostCenter**: Training

## 🔗 Live Website

[Your website URL will appear here after deployment]

## 📊 Terraform vs Bicep

See [RESEARCH.md](RESEARCH.md) for detailed comparison.

## ✅ Deliverables Completed

- [x] Terraform repository with provider, state, and variables
- [x] Resource Group provisioned
- [x] Storage Account with Static Website enabled
- [x] GitHub Actions workflow YAML
- [x] Successful pipeline run
- [x] Resources tagged for cost tracking
- [x] Terraform vs Bicep research

## 🎓 Learning Outcomes

1. Infrastructure as Code with Terraform
2. Azure Resource Management
3. CI/CD with GitHub Actions
4. Static website hosting on Azure
5. Cost management through tagging
6. Git workflow (branch, commit, push)

## 🛠️ Technologies Used

- Terraform 1.6+
- Azure CLI
- GitHub Actions
- Azure Storage (Static Website)
- HTML/CSS/JavaScript

## 👤 Author

Vipul Patil

## 📅 Date

25/11/2025
