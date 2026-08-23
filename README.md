# Terraform AWS STS GetCallerIdentity

This project demonstrates how to use Terraform to retrieve AWS account identity information using the AWS STS `GetCallerIdentity` API.

## What This Project Does

The project uses Terraform to:

- Retrieve the AWS account ID
- Retrieve the AWS caller ARN
- Retrieve the AWS caller User ID
- Display the results using Terraform outputs

## Terraform Files

- `main.tf` - AWS provider configuration
- `data.tf` - AWS STS caller identity data source
- `output.tf` - Outputs AWS account and identity information
- `.terraform.lock.hcl` - Terraform provider dependency lock file
- `.gitignore` - Files and directories excluded from Git

## Commands

Initialize Terraform:

```bash
terraform init
