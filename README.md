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

## Screenshots
- Terraform apply success
- AWS EC2 running instance
- Application running in browser

---

## Key Learnings
- Infrastructure as Code (IaC)
- AWS resource provisioning
- Security group configuration
- Troubleshooting AMI compatibility issues
- Docker deployment on cloud infrastructure
