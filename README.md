# AWS Infrastructure Provisioning with Terraform

This project provisions basic AWS infrastructure using Terraform, including an EC2 instance, an S3 bucket, and a Security Group with custom rules.

## 🛠️ Tools & Technologies
- Terraform
- AWS (EC2, S3, VPC, Security Groups)
- IAM Access Keys (configured securely)
- AWS CLI

## 📌 Features
- Launches EC2 instance with a specified AMI and key pair.
- Creates a versioned S3 bucket.
- Defines Security Group rules.
- Outputs public IP and bucket name.


## 🚀 How to Run
```bash
terraform init
terraform plan
terraform apply

