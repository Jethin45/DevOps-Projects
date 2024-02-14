
# Project 02: Infrastructure as Code (IaC)

```markdown
# Infrastructure as Code (IaC)

## Overview
This project focuses on defining and managing infrastructure as code using tools like Terraform or Ansible. The goal is to provision and configure infrastructure resources in a consistent and repeatable manner.

## Tools Used
- IaC Tool (e.g., Terraform, Ansible)
- Cloud Provider (e.g., AWS, Azure)

## Steps
1. **Step 1: Choose IaC Tool and Cloud Provider**
   - Select an IaC tool suitable for the project (e.g., Terraform).
   - Choose a cloud provider (e.g., AWS).

2. **Step 2: Define Infrastructure Components**
   - Write IaC scripts to define infrastructure components (e.g., VMs, networks).
   - Organize code into modules for modularity.

   ```hcl
   # Example Terraform script
   resource "aws_instance" "example" {
     ami           = "ami-0c55b159cbfafe1f0"
     instance_type = "t2.micro"
   }
