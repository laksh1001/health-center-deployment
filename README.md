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
