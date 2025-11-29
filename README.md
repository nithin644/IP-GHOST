<h1 align="center">IPGHOST</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-success?style=flat-square">
  <img src="https://img.shields.io/badge/Language-Bash-blue?style=flat-square">
  <img src="https://img.shields.io/badge/Anonymity-Tor-orange?style=flat-square">
</p>

<p align="center">
  <b>IPGHOST – Automatic IP Changer over Tor</b><br>
  Rotate your IP address automatically using Tor. Supports Debian, Kali, Ubuntu, Arch, RHEL and more.
</p>

---

## 🔥 Overview

**IPGHOST** is a powerful Bash-based anonymization tool that automatically changes your IP address at custom intervals using the **Tor network**.  

It detects your current IP + location and switches identity without restarting Tor.  
This tool is built for:

- Bug bounty hunters  
- Pentesters  
- OSINT researchers  
- Privacy-focused users  
- Red teamers  

---

## ✨ Features

✔ Automatically rotates IP via Tor  
✔ Displays new IP + country + region + city  
✔ Works on **ANY Linux distro** (Debian, Kali, Arch, Fedora, RHEL)  
✔ Auto-installs dependencies (tor, curl, jq)  
✔ Customizable interval & number of cycles  
✔ Infinite mode (change IP forever)  
✔ Clean color UI  
✔ Built-in Tor service control  
✔ Graceful exit & cleanup  

---

## 📌 Requirements

- Linux OS  
- Root / sudo privileges  
- Tor installed (auto-installed by script)  

---

## 📥 Installation

```bash
git clone https://github.com/nithun618/IPGHOST
cd IPGHOST
chmod +x ipghost.sh install.sh
sudo bash install.sh
