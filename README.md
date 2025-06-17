# AWS Infrastructure with Terraform

## Overview
This project provisions a basic EC2 instance using Terraform on AWS.

## Files
- `main.tf` – Defines provider and EC2 instance resource.
- `variables.tf` – Stores input variables.
- `outputs.tf` – Outputs the EC2 instance ID.

## Steps to Use
1. Install Terraform and configure AWS CLI credentials.
2. Run `terraform init` to initialize the directory.
3. Run `terraform plan` to review the changes.
4. Run `terraform apply` to create the resources.
5. Run `terraform destroy` to clean up.

## Notes
- Replace the AMI ID with one valid in your region.
- You can expand this project to include S3, IAM, VPC, etc.
