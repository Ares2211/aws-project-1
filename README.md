# AWS Project 1 - EC2 + S3 + IAM + CloudFormation

## Architecture

CloudFormation
    ↓
EC2 Instance (Amazon Linux 2023)
    ↓
IAM Instance Profile
    ↓
IAM Role
    ↓
S3 Bucket

---

## Features

- Infrastructure as Code using CloudFormation
- EC2 deployment with Amazon Linux 2023
- IAM Role based S3 access
- Secure SSH access using KeyPairs
- Security Group integration
- Resource tagging support

---

## Tech Stack

- AWS EC2
- AWS S3
- AWS IAM
- AWS CloudFormation
- AWS CLI
- Git

---

## Deployment Command

```bash
aws cloudformation create-stack --stack-name devops-project1 --template-body file://template1.yaml
CI/CD test update
