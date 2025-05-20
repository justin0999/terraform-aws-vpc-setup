# Terraform AWS VPC Setup

This project creates a basic AWS VPC architecture using Terraform. It's something I built as part of my DevOps learning journey to better understand how to provision infrastructure as code using real-world best practices.

It includes:
- A custom VPC
- A public and a private subnet
- An internet gateway
- A route table and association
- Variable file for configuration
- EC2 instance (Amazon Linux 2)
- Security Group allowing SSH and HTTP
- Add SSH key pair for EC2 login
- User data script for bootstrapping instance
---

## 💻 Tech Used

- **Terraform**
- **AWS (VPC, Subnets, IGW, Route Tables)**
- Tested in **us-east-1** region

---

## 📁 Project Structure

```bash
terraform-aws-vpc-setup/
├── main.tf
├── provider.tf
├── variables.tf
├── outputs.tf
├── terraform.tfvars
└── README.md
