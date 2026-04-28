# 🚀 SkyCrack - WiFi Security Assessment Tool

![SkyCrack Logo](skycrack.png)

**A professional WiFi network security testing tool for authorized penetration testing and security assessments.**

![Python Version](https://img.shields.io/badge/Python-3.6%2B-blue.svg)
![License](https://img.shields.io/badge/License-Educational%20Only-red.svg)
![Platform](https://img.shields.io/badge/Platform-Linux-green.svg)

---

## ⚠️ Legal Disclaimer

> **IMPORTANT**  
> This tool is designed for **educational purposes and authorized security testing only**.

- ✅ Only use on networks you own or have explicit written permission to test  
- ❌ Unauthorized access to computer networks is illegal in most jurisdictions  
- ⚠️ The author assumes no liability for misuse of this tool  
- 📜 Always comply with local laws and regulations  

---

## 📋 Table of Contents

- [✨ Features](#-features)
- [🔧 Requirements](#-requirements)
- [⚙️ Installation](#️-installation)
- [▶️ Usage](#️-usage)
- [🧠 How It Works](#-how-it-works)
- [🛠 Troubleshooting](#-troubleshooting)
- [🤝 Contributing](#-contributing)
- [📜 Legal Notice](#-legal-notice)

---

## ✨ Features

- 🔍 **Automated WiFi Interface Detection**  
  Automatically identifies available wireless interfaces  

- 📡 **Monitor Mode Setup**  
  Configures monitor mode with automatic interference handling  

- 🌐 **Network Scanning**  
  Scans and displays nearby WiFi networks  

- 👥 **Client Discovery**  
  Identifies connected clients with signal strength analysis  

- 🤝 **Handshake Capture**  
  Captures WPA/WPA2 handshake packets  

- ⚡ **Multi-Method Deauth Attack**  
  Uses multiple deauthentication techniques  

- 🔓 **Password Cracking**  
  Integrates with `aircrack-ng` for password cracking  

- 🧹 **Automatic Cleanup**  
  Restores network settings after testing  

---

## 🔧 Requirements

### 💻 System Requirements

- **Operating System**: Linux (Kali Linux, Ubuntu, Parrot OS recommended)  
- **Python Version**: 3.6 or higher  
- **Privileges**: Root access required  
- **WiFi Adapter**: Must support monitor mode & packet injection  

---

### 🧰 Required Tools

Make sure the following tools are installed:

- `aircrack-ng` (includes `airodump-ng`, `aireplay-ng`, `aircrack-ng`)  
- `airmon-ng`  
- `iwconfig`  
- `ip`  

---

## ⚙️ Installation

### 🐧 Ubuntu / Debian / Kali Linux

```bash
sudo apt-get update
sudo apt-get install aircrack-ng
sudo apt-get install wordlists
