# 🛠️ DevOps Project: Deploy eCommerce Website using Terraform & Ansible

## 🚀 Stack
- **Terraform**: Provision AWS EC2, VPC, Security Groups
- **Ansible**: Install Node.js, MongoDB, and Nginx
- **AWS EC2**: Ubuntu 22.04 LTS
- **Source**: [GitHub - ecommerce-app](https://github.com/21CSA32/ecommerce-app)

## 🔧 Usage

### 1. Setup Terraform
```bash
cd terraform
terraform init
terraform apply -auto-approve
```

### 2. Note the EC2 IP and update `ansible/inventory.ini`

### 3. Run Ansible Playbook
```bash
cd ../ansible
ansible-playbook -i inventory.ini playbook.yml
```

## 🌐 Access App
```
http://<EC2_PUBLIC_IP>
```

---
Made with 💻 by Litheesh