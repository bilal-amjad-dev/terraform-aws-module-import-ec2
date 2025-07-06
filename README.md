# terraform-aws-module-import-ec2

This project demonstrates how to use `terraform import` to bring an **existing EC2 instance** (created manually in the AWS Console) under **Terraform management** using a simple module structure.

✅ No need to recreate or destroy the instance — just import and manage it with Terraform!

---

## 🚀 Steps to Use

### 1️⃣ Launch an EC2 Instance Manually

- Go to the [AWS EC2 Console](https://console.aws.amazon.com/ec2/)
- Launch an instance using Amazon Linux 2 (or any AMI)
- After launch, **copy the Instance ID** (e.g., `i-0123456789abcdef0`)

---

### 2️⃣ Clone the Repository
Clone the repository in vs code

### 3️⃣ Initialize Terraform

```bash
terraform init
```
