# Terraform-Setup

# 🚀 Jenkins Infrastructure Setup for Python REST API Deployment

This repository provisions the AWS Cloud infrastructure required to create **Jenkins host server** using Terraform. The Jenkins server is configured to integrate with a separate Git repository that contains Terraform code for deploying a **Python REST API application**.

## 📌 Project Overview

This project includes:

- 🔧 Infrastructure setup for Jenkins (on AWS EC2)
- ⚙️ Jenkins configuration to:
  - Pull Terraform code from an external Git repository - https://github.com/nikhilreddy56/RestAPI-Python.git
  - Provision Cloud infrastructure (VPC, other Networking components, Hosted Zone for DNS, Certificate using AWS Certificate Manager, EC2, RDS, Load Balancer)
  - Deploy a Python-based REST API application

- ## 📋 Prerequisites

Before you begin, make sure you have the following:

- 🛡️ **AWS Account** with appropriate IAM permissions
- 💻 **Terraform CLI** installed (v1.0+ recommended)
- 🐙 **Git** installed and access to both repositories
- 🔐 **SSH Key Pair** for accessing Jenkins EC2
- 🐍 **Python**
- 🌐 **Internet Access** to download Jenkins and plugins

## 🛠️ Stack Used

- **Cloud Provider:** AWS (can be modified)
- **Infrastructure as Code:** Terraform
- **CI/CD Tool:** Jenkins
- **Application:** Python REST API (Flask/FastAPI)
- **Version Control:** Git

## 📂 Repo Structure


<img width="570" height="285" alt="image" src="https://github.com/user-attachments/assets/cd81b5c4-91f8-46dc-b499-ce4b3f01fa05" />


Https connection established from Internet to Jenkins host server 
<img width="570" height="285" alt="image" src="https://github.com/user-attachments/assets/46d98c8c-9796-4ab2-a640-133b27ce0c8f" />



