# Week 3 - Infrastructure as Code Security with Terraform and Checkov

## Objectives
- Install Terraform
- Create Infrastructure as Code (IaC)
- Install Checkov
- Scan Terraform code for security issues
- Integrate Checkov into Jenkins Pipeline

## Tools Used
- Terraform
- Checkov
- Jenkins

## Terraform Resources Created
- AWS S3 Bucket
- AWS S3 Bucket ACL
- AWS Security Group

## Scan Results
Passed checks: 11

Failed checks: 10

## Security Findings
- Public S3 bucket access detected
- Security group allows SSH from 0.0.0.0/0
- Additional IaC misconfigurations identified by Checkov

## Screenshots
See screenshots folder.
