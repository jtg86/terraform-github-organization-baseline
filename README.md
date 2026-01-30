# GitHub Infrastructure as Code (Terraform)

This repository demonstrates how GitHub repositories and settings
can be managed declaratively using Terraform.

The project is intended as a practical example of Infrastructure as Code,
showing how common GitHub configuration can be versioned and reproduced
consistently.

## What this creates
- GitHub repository
- Repository settings
- Optional labels and metadata

## Prerequisites
- Terraform
- GitHub personal access token with appropriate scopes

## Usage
1. Configure variables in `terraform.tfvars`
2. Run `terraform init`
3. Run `terraform plan`
4. Apply with `terraform apply`

## Notes
This is a demonstration project and not a complete production baseline.
