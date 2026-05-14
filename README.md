# terraform-aws
Provisioned AWS EC2 infrastructure using Terraform and automated cloud resource creation through Infrastructure as Code.
# Infrastructure Provisioning on AWS using Terraform

## Project Overview
This project automates AWS infrastructure provisioning using Terraform.
It creates an EC2 instance, configures security groups for SSH and HTTP access, and deploys a Dockerized application on AWS EC2.

---

## Architecture
Terraform → AWS EC2 → Security Group → Docker → Application Deployment

---

## Tech Stack
- Terraform
- AWS EC2
- AWS Security Groups
- Linux
- Docker

---

## Features
- Automated EC2 provisioning using Infrastructure as Code
- Security group configuration for SSH and HTTP access
- Public IP generation
- Docker installation on EC2
- Application deployment using Docker container

---

## Setup Steps
1. Configure AWS CLI credentials
2. Write Terraform configuration (`main.tf`)
3. Run:

terraform init

terraform plan

terraform apply

4. SSH into EC2 instance
5. Install Docker
6. Pull Docker image
7. Run application container

---

## Terraform Output
Displays:
- EC2 public IP
- Infrastructure creation status

---

## Key Learnings
- Infrastructure as Code (IaC)
- AWS resource provisioning
- Security group configuration
- Troubleshooting AMI compatibility issues
- Docker deployment on cloud infrastructure
---

## Screenshots
<img width="1919" height="1012" alt="Screenshot 2026-05-14 083750" src="https://github.com/user-attachments/assets/72c81b72-ad24-49e1-aee4-dfc517bf0ba6" />
<img width="478" height="53" alt="Screenshot 2026-05-14 083804" src="https://github.com/user-attachments/assets/91645e7b-f141-45ef-bc27-58946ee4a276" />
<img width="1919" height="872" alt="Screenshot 2026-05-14 083834" src="https://github.com/user-attachments/assets/087dcc25-6349-4d32-8216-af191ea26aa8" />
<img width="1919" height="1018" alt="Screenshot 2026-05-14 083913" src="https://github.com/user-attachments/assets/d682b88f-da77-4e5b-ae20-0d7350615730" />
