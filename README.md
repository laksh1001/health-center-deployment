# Automated Health Center Deployment & Infrastructure

This repository contains Infrastructure as Code (IaC) and bash automation scripts designed to provision a Linux server and automatically deploy a fully functional web application.

## 🛠️ Technologies Used
* **Infrastructure:** Vagrant, VirtualBox
* **Operating System:** Linux (CentOS/RedHat based)
* **Web Server:** Apache (httpd)
* **Automation & Monitoring:** Bash Scripting

## 📂 Repository Contents
* `Vagrantfile`: Provisions the isolated local Linux server environment.
* `websetup.sh`: An automation script that installs Apache, downloads external web assets, handles file extraction, and configures the web server.
* `firstscript.sh`: A custom system monitoring tool that tracks CPU load, memory utilization, and disk space health.

## 🚀 How to Run the Project

**1. Spin up the infrastructure:**
```bash
vagrant up    
<img width="1915" height="964" alt="Screenshot 2026-06-11 154721" src="https://github.com/user-attachments/assets/513c1f5c-6050-445e-8041-0f5b11f46e52" />
<img width="1913" height="965" alt="Screenshot 2026-06-11 154654" src="https://github.com/user-attachments/assets/82b0ea80-2ac4-412c-b718-f964cf9f9ad3" />
<img width="1897" height="670" alt="Screenshot 2026-06-11 164758" src="https://github.com/user-attachments/assets/a75bbbe9-959a-49ac-aad0-4cdcd692ccf0" />
<img width="937" height="894" alt="Screenshot 2026-06-11 164245" src="https://github.com/user-attachments/assets/38ed4d85-7e08-4380-ae41-a7b1072378c6" />
