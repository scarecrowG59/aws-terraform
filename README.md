# aws-terraform
Banking Case Study: Secure and Scalable Financial Data Management System Using AWS


# AWS Final Project & Assignments

This repository contains my final infrastructure deployment project using Terraform, along with individual AWS hands-on lab assignments.

## 📁 Structure

- `final-project/` – Full Terraform-based deployment (EC2, RDS, Lambda, Step Functions, CloudWatch, IAM)
- `aws-assignments/` – AWS service labs with screenshots and CLI/console outputs
  - VPC + Subnet Setup
  - EC2 with Security Groups
  - IAM Role & Policy
  - KMS encryption
  - CloudTrail
  - SQS, SNS, Lambda integration

## ✅ Final Project Description

The final project provisions a secure and scalable banking-like backend with:

- Encrypted RDS using KMS
- Lambda functions connected to Step Functions
- IAM policies with least privilege
- CloudTrail audit logging
- CloudWatch alarms and logs

## 🧪 Requirements

- Terraform >= 1.4
- AWS CLI installed & configured
- AWS account with necessary permissions

## ⚙️ Quick Start

```bash
cd final-project
terraform init
terraform apply
