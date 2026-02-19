# Terraform AWS Cloud Basics 🚀

A hands-on project for learning AWS Infrastructure as Code (IaC) and modern DevOps practices. This repository serves as a demonstration of cloud resource management and automated CI/CD workflows.

## 🛠️ Project Overview

This project automatically provisions a foundational infrastructure in AWS:
* **VPC & Networking:** Creates a VPC, a public subnet, an Internet Gateway, and associated routing tables.
* **Compute (EC2):** Deploys an EC2 instance using Amazon Linux 2023.
* **Provisioning:** Automatically installs and starts an Nginx web server using `user_data` scripts.
* **Region:** `eu-north-1` (Stockholm).

## 🤖 CI/CD Automation

The project utilizes **GitHub Actions** to ensure code quality and security with every push and pull request:

1. **Terraform Format:** Ensures consistent code style across the project.
2. **Terraform Validate:** Verifies the syntax and internal consistency of the configuration.
3. **Terraform Plan:** Generates an execution plan using AWS credentials securely managed via GitHub Secrets.



## 🚀 How to Use

1. Initialize Terraform: `terraform init`
2. Preview changes: `terraform plan`
3. Deploy to AWS: `terraform apply`

## 🎯 Purpose

This project is part of my professional learning path toward **Cloud and DevOps** roles. It demonstrates my ability to bridge the gap between infrastructure development and automated quality assurance.
