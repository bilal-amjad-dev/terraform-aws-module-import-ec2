# terraform-aws-module-import-ec2

This project demonstrates how to use `terraform import` to bring an **existing EC2 instance** (created manually in the AWS Console) under **Terraform management** using a simple module structure.

✅ No need to recreate or destroy the instance — just import and manage it with Terraform!

---

## 🚀 Steps to Use

### 1️⃣ Launch an EC2 Instance Manually

- Go to the [AWS EC2 Console](https://console.aws.amazon.com/ec2/)
- Launch an instance using Amazon Linux 2 (or any AMI)
- After launch, **copy the Instance ID** (e.g., `i-0123456789abcdef0`)

<img width="1600" height="900" alt="Image" src="https://github.com/user-attachments/assets/d9264c04-dbb8-48af-b104-b0d5bb40d998" />

<img width="1600" height="900" alt="Image" src="https://github.com/user-attachments/assets/dd35d4cc-20da-4b03-a6e8-edca5e9e63de" />

<img width="1600" height="900" alt="Image" src="https://github.com/user-attachments/assets/ef70859a-8e92-45a3-8286-e81fbf61585c" />

<img width="1600" height="900" alt="Image" src="https://github.com/user-attachments/assets/b50913e8-5ceb-48a1-bae1-63cebca7ed11" />



---

### 2️⃣ Clone the Repository
Clone the repository in vs code

<img width="1600" height="900" alt="Image" src="https://github.com/user-attachments/assets/6d372b5d-09a3-4b6f-ae4b-aa07433b351e" />



### 3️⃣ Initialize Terraform


<img width="1600" height="900" alt="Image" src="https://github.com/user-attachments/assets/6f890e80-5bd8-49f7-91f0-1cf31927e5c6" />
```bash
terraform init
```

### 4️⃣ Terraform import

<img width="1600" height="900" alt="Image" src="https://github.com/user-attachments/assets/125b37fe-afaf-4f77-8d24-f0ed69aa2e47" />


### 5️⃣ Terraform destroy

<img width="1600" height="900" alt="Image" src="https://github.com/user-attachments/assets/8b6b532e-8c26-435e-92ec-60d2ce1ad03f" />

<img width="1600" height="900" alt="Image" src="https://github.com/user-attachments/assets/ddd78398-d949-4738-9497-61c37e896557" />













