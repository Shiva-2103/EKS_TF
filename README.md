
# 🚀 Terraform EKS Cluster on AWS

This project uses Terraform to provision a basic **Amazon EKS (Elastic Kubernetes Service)** cluster on AWS.

## 📁 Project Structure

- `main.tf` – Defines AWS VPC, EKS cluster, subnets, IAM roles, and node group.
- `variables.tf` – Input variables like AWS region.
- `outputs.tf` – Outputs like EKS cluster name and endpoint.

## ✅ Prerequisites

- AWS account with IAM user/role access
- AWS CLI configured (`aws configure`)
- Terraform installed

## ⚙️ Usage

```bash
# Step 1: Initialize Terraform
terraform init

# Step 2: Preview the plan
terraform plan

# Step 3: Apply the configuration
terraform apply

# Step 4: To delete all resources:
terraform destroy

```bash
