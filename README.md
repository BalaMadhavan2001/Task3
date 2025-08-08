# Terraform Docker Container Project


## 🧱 Objective
Provision a local Docker container (NGINX) using Terraform on an EC2 Ubuntu instance.

---

## 🛠️ Tools Used
- Terraform (~> 1.8)
- Docker
- Git
- AWS EC2 (Ubuntu)

---

## 📁 Files
- `main.tf` – Terraform configuration to provision Docker image and container
- `plan.log` – Terraform plan output
- `apply.log` – Terraform apply output
- `destroy.log` – Terraform destroy output

---

## 🚀 How to Use

### 1. Clone the Repository
```bash
git clone https://github.com/BalaMadhavan2001/Task3.git
cd Task3
```

### 2. Initialize Terraform
```bash
terraform init
```

### 3. Review Infrastructure Plan
```bash
terraform plan
```

### 4. Apply to Create Container
```bash
terraform apply
```

Access the NGINX container via:
```
http://<EC2-PUBLIC-IP>:8080
```

### 5. Check Terraform State
```bash
terraform state list
```

### 6. Destroy Infrastructure
```bash
terraform destroy
```

---

## 🔒 Security Group Note
Make sure port 8080 is open in your EC2 security group:
- Type: HTTP
- Port: 8080
- Source: Anywhere or your IP

---

## 👨‍💻 Author
Bala Madhavan – [GitHub Profile](https://github.com/BalaMadhavan2001)
