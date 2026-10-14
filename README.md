# 🚀 Hyper V Ubuntu Server & Docker Web Hosting Lab
A comprehensive, highly detailed technical log documenting the end-to-end process of setting up a local virtualization environment on Windows using Hyper-V, provisioning an Ubuntu Server LTS virtual machine, bridging network adapters, and deploying a containerized web server via Docker and Docker Compose.

## 🛠️ Infrastructure and Tech Stack
* **Host OS:** Windows 11 Pro
* **Hypervisor:** Windows Hyper-V
* **Guest OS:** Ubuntu Server 26.04.1 LTS
* **Networking:** External Virtual Switch bridged to the Realtek PCIe GbE Family Controller
* **Containerization:** Docker Engine and Docker Compose Plugin
* **Web Stack:** Nginx with custom HTML/CSS

## 📋 Execution Log
### Step 1: Hyper-V Feature Activation and External Network Bridging
1. **Enable Hyper-V**
     * Opened Window's start menu and searched for ***Turn Windows features on or off***.
     * Selected ***Hyper-V*** and ensured ***Hyper-V Management Tools*** and the ***Hyper-V Platform*** are fully enabled.
3. **Configure the External Virtual Switch**
