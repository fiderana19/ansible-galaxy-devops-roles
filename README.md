# 📚 Ansible Galaxy DevOps Roles Library

This repository serves as a centralized library of **Ansible Roles**. It aggregates industry-standard roles to provision, secure, and monitor production-ready infrastructures.

## 🏗️ Roles Overview

The library is organized into functional categories to cover the entire server lifecycle:

### 🔐 System & Security
*   **geerlingguy.security**: Basic system hardening and security configurations.
*   **geerlingguy.firewall**: Advanced firewall management.
*   **geerlingguy.ntp**: Time synchronization (essential for log consistency).

### 🐳 Containerization & Web Services
*   **geerlingguy.docker**: Complete Docker engine and Docker Compose installation.
*   **geerlingguy.nginx**: High-performance Web Server and Reverse Proxy setup.
*   **geerlingguy.certbot**: Automated SSL certificate management via Let's Encrypt.

### 🗄️ Database Management
*   **geerlingguy.mysql** & **geerlingguy.postgresql**: Automated deployment of relational database engines.

### 📈 Monitoring & Observability
*   **cloudalchemy.prometheus**: Metrics collection and alerting.
*   **cloudalchemy.grafana**: Data visualization and professional dashboards.

## ⚙️ Setup & Installation

This project follows **Infrastructure as Code (IaC)** best practices by managing dependencies via a requirements file.

To install or update all roles locally, run:

```bash
ansible-galaxy install -r requirements.yml -p ./roles/
```

-----

## ⭐️ Star

Don't hesitate to give a star, it will gives me a motivation for my projects and my progress.