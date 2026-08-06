<div align="center">
  
  <img src="https://img.icons8.com/color/120/000000/server.png" alt="Server Logo" width="100"/>

  # 👑 SCRIPT FATEH 96
  
  **Premium Auto-Installer Script for Virtual Private Servers**

  ![OS Requirement](https://img.shields.io/badge/OS-Ubuntu_20.04-orange?style=for-the-badge&logo=ubuntu)
  ![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)
  ![Version](https://img.shields.io/badge/Version-Premium-blue?style=for-the-badge)

</div>

---

## ⚠️ IMPORTANT NOTICE: OS VERSION
> **ATTENTION:** This script is strictly designed for **Ubuntu 20.04**. If your Ubuntu VPS version is higher than 20.04 (e.g., 22.04 or 24.04), you **MUST** downgrade to version 20.04 before installing the main script. Please refer to the Downgrade Guide section below.

---

## 🚀 HOW TO INSTALL SCRIPT FATEH 96

**Step 1: Register VPS IP**
You must register your VPS IP address to gain installation access permission.
🔗 **Check / Register here:** 
https://raw.githubusercontent.com/Fatehfadz/permission/refs/heads/main/access

**Step 2: Run the Main Installer**
Copy and paste the following command into your VPS terminal:
```bash
apt install -y && apt update -y && apt upgrade -y && wget -q https://github.com/Fatehfadz/fateh86/raw/refs/heads/main/install
```
🆙 UPDATE SCRIPT (Optional)
To update your system to the latest version, run this update command:
```
wget -q https://github.com/Fatehfadz/source/raw/refs/heads/main/update.sh
```



------ 
🔄 OS DOWNGRADE GUIDE (To Ubuntu 20.04)
Use these commands only if your VPS is running an OS higher than Ubuntu 20.04.

Run the following commands in the terminal:

```
wget https://github.com/Fatehfadz/source/raw/refs/heads/main/reinstall.sh
chmod +x install-ulang
./install-ulang
```
Instructions When the Script is Running:

Select Option: 2 (Ubuntu)

Select Version: 1 (20.04)

Confirmation: Type Y and press Enter.

Wait for the downgrade process to complete (it takes approximately 10 minutes). Once finished, your system will be running a clean installation of Ubuntu 20.04.

🛠️ REBUILD SCRIPT UTILITY
If you need a rebuild utility after reinstalling, use the following command sequence:
```
cd root
rm install-ulang-vps
wget [https://github.com/hokagelegend9999/genom/raw/refs/heads/main/install-ulang-vps 
chmod +x install-ulang-vps
./install-ulang-vps
```


