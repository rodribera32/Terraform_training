# Terraform AWS Example

## Prerequisites

Before you begin, make sure you have the following installed:

- [Terraform](https://www.terraform.io/downloads.html)

## Configuration

1. Export environment variables
```bash
  $env:AWS_ACCESS_KEY_ID="your_access_key"
  $env:AWS_SECRET_ACCESS_KEY="your_secret_access_key"
```
2. Initialize Terraform:

```bash
  terraform init
```
3. To check the infrastructure defined in this configuration, run:
```bash
  terraform plan
```
4. To create the infrastructure defined in this configuration, run:
```bash
  terraform apply
```

5. To destroy the infrastructure and clean up the resources created by Terraform, run:
```bash
  terraform destroy
```
