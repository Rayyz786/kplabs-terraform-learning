markdown
# AWS EC2 Infrastructure Blueprint

A streamlined, modular Infrastructure as Code (IaC) baseline built to validate declarative resource syntax, state compilation, and basic provisioning blocks using HashiCorp Terraform.

## 📐 Architecture Scope

This project functions as a localized staging lab to evaluate clean-room virtual instance deployments within an isolated AWS infrastructure framework. It abstracts compute resource declarations to verify compliance with structural enterprise code syntax policies.

## 🛠️ Infrastructure Component Breakdown

The infrastructure runtime environment is provisioned across a single core configuration file:

* **`ec2.tf`**: Contains the primary structural block initializing the virtual compute layer (`aws_instance`). It targets a standardized Linux machine image blueprint (`ami-00c39f71452c08778`) scaled down to standard free-tier capacity parameters (`t2.micro`) to test execution velocity with zero operational budget overhead.

## 🚀 Execution & Pipeline Orchestration

To run this layout natively within an automated pipeline framework or local command-line interface, execute the following life cycle controls:

```bash
# Initialize the backend and download official hashicorp cloud plugins
terraform init

# Validate structural syntax and parameter integrity
terraform validate

# Review the execution plan to inspect planned cloud adjustments
terraform plan

# Apply the declarative state changes to build target infrastructure
terraform apply -auto-approve
```

## 🔒 Security Configuration Policy
To safeguard proprietary corporate intellectual property, production-grade network to
