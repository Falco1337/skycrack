# Skycrack Wifi Security

Advanced WiFi security assessment tool for authorized penetration testing and network security auditing.

## ⚠️ Legal Disclaimer

**This tool is for EDUCATIONAL and AUTHORIZED testing purposes ONLY!**

- Only use on networks you OWN or have EXPLICIT WRITTEN PERMISSION to test
- Unauthorized access to computer networks is ILLEGAL
- The author assumes NO responsibility for misuse of this tool
- By using this tool, you confirm you have proper authorization

## Features

- 🚀 **Multi-Method Deauth Attack** - 3 simultaneous deauthentication methods
- 📡 **Signal-Based Client Targeting** - Automatically selects strongest client
- 🔄 **Auto Channel Tracking** - Adapts to AP channel changes
- 🎯 **PMKID Attack Support** - Fallback method for WPA3/WPA2 networks
- 💣 **MDK4 Integration** - Aggressive deauth for protected APs
- 📊 **Real-time Client Monitoring** - Detects and tracks connected devices
- 💰 **Auto-cracking** - Integrated with rockyou.txt wordlist
- 🖥️ **Multi-Terminal Support** - Works with GNOME, KDE, XFCE, Xterm

## Requirements

### System Requirements
- Linux OS (Kali Linux, Ubuntu, Parrot OS recommended)
- Root/sudo access
- Compatible WiFi adapter (must support monitor mode & packet injection)

### Dependencies

```bash
# Core tools (required)
sudo apt-get update
sudo apt-get install -y aircrack-ng

# Optional but recommended (for advanced features)
sudo apt-get install -y mdk4 hcxdumptool hcxtools

# Wordlist (for password cracking)
sudo apt-get install -y wordlist
sudo gunzip /usr/share/wordlists/rockyou.txt.gz
