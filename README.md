HOW TO INSTALL SCRIPT FATEH 96
1. FIRST REGISTER THE VPS IP THAT WE WILL INSTALL IN THE FOLLOWING LINK:
=== https://raw.githubusercontent.com/Fatehfadz/permission/refs/heads/main/access

2. Copy and paste the following installer script into the VPS where you want to perform the installation:
```
apt install -y && apt update -y && apt upgrade -y && wget -q https://raw.githubusercontent.com/Anggabayuwijaya599/installsinggah/refs/heads/main/vpn && chmod +x vpn && ./vpn
```
3. Enter the domain that was pointed to Cloudflare during the installation script.
4. Wait for the installation process to complete. Do not disconnect during installation, as it will restart from the first step.
If the installation asks for a reboot, press ENTER to reboot.
5. The installation process is complete and the VPS is ready to use.

=================================If the Ubuntu VPS version is higher than Ubuntu 20.04, you must downgrade to Ubuntu 20.04.========================

Copy and paste the following link to downgrade the VPS to Ubuntu 20.
```
wget https://github.com/Fatehfadz/source/raw/refs/heads/main/reinstall.sh
chmod +x install-ulang
./install-ulang
```
Select option 2 (Ubuntu).
Select version 1 (20.04).
When prompted, type 'Y' (and press Enter).
Wait for the process to complete (approximately 10 minutes).
Once finished, the system will be running Ubuntu 20.04.
Rebuild script:
```
cd root
rm install-ulang-vps
wget https://github.com/hokagelegend9999/genom/raw/refs/heads/main/install-ulang-vps
chmod +x install-ulang-vps
./install-ulang-vps
```

UPDATE SCRIPT (OPTIONAL):
```
wget -q https://raw.githubusercontent.com/Anggabayuwijaya599/SinggahVpn/refs/heads/main/update.sh && chmod +x update.sh && ./update.sh
```
