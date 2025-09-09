# 🚀 Deploy Nginx with Ansible in Containers (Playbook + Roles)

## 📌 Description
This project demonstrates how to **deploy and configure Nginx web servers inside Docker containers using Ansible**.  
It is implemented in two ways:  

1. **Flat Playbook** – a single YAML playbook that installs and configures Nginx.  
2. **Roles** – a modular and reusable structure using Ansible roles.  

The automation ensures:  
- ✅ Nginx is installed inside containers  
- ✅ The service is started and restarted automatically using **handlers**  
- ✅ The web server listens on **port 8080** (instead of default port 80)  
- ✅ A **dynamic HTML page** is deployed, showing host-specific info (hostname/IP)  

---
