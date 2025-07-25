# 🛠️ Roboshop Terraform + Ansible Automation

This repository demonstrates **end-to-end automation** of the Roboshop 🛍️ e-commerce application using **Terraform** for cloud infrastructure and **Ansible** for configuration management. It follows DevOps best practices to deliver a **modular, scalable, and production-ready** microservices architecture.

---

## ✨ Project Highlights

- 🧱 **Terraform** provisions AWS infrastructure (VPC, EC2, Security Groups)
- 🤖 **Ansible** automates service configuration and deployment
- 🔁 Microservices are managed via **modular roles**
- 🌐 Supports **multi-environment** (dev/stage/prod) deployments
- 🚀 Fast, repeatable, and version-controlled automation

---

## 📦 Services Automated via Ansible Roles

| 🧩 Role       | ⚙️ Description                                 |
|--------------|-----------------------------------------------|
| `catalogue`  | 📦 Node.js-based product catalogue service     |
| `frontend`   | 🌐 Nginx-based frontend web UI                 |
| `user`       | 👤 User service integrated with MongoDB        |
| `cart`       | 🛒 Cart service backed by Redis                |
| `shipping`   | 🚚 Shipping microservice using MySQL           |
| `payment`    | 💳 Python-based payment service                |
| `mongodb`    | 🗃️ MongoDB database installation & setup       |
| `redis`      | 🔄 Redis key-value store configuration         |
| `mysql`      | 🛢️ MySQL DB for shipping service               |
| `rabbitmq`   | 🐇 RabbitMQ setup for service communication     |

## 🧪 How to Deploy

### Provision AWS Infrastructure (Terraform)
```bash
cd terraform
terraform init
terraform apply -auto-approve
