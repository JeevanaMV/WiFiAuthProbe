# Deauther

## ⚠️ Disclaimer
This tool is provided **strictly for educational and research purposes only**.  
Do **not** use it for illegal activities. It must only be run on networks and devices that you own or have explicit permission to test.  

By using this tool, you agree:
- You will not engage in unauthorized or unlawful actions.
- You are fully responsible for any outcomes that result from its usage.  

The authors and contributors shall **not be held liable** for misuse, damages, or legal consequences.  
Use responsibly, ethically, and in compliance with applicable laws.

---

## 📖 Introduction
**Deauther** is a command-line utility that allows security researchers and penetration testers to explore Wi-Fi networks in a controlled and authorized environment.  

It provides functionality to:
- Scan for nearby wireless networks  
- Enumerate clients connected to an access point  
- Perform controlled deauthentication tests (with authorization)  

This project is intended as a **learning resource** for Wi-Fi security concepts.

---

## ✅ Pre-requisites
Before installing, ensure the following are available in your environment:
- Linux-based OS  
- **Python 3**  
- **Aircrack-ng** suite  

---

## ⚙️ Installation
Clone the repository and set up the tool:

```bash
# Clone this repository
git clone https://github.com/JeevanaMV/WiFiAuthProbe.git

# Move the repository to /opt
sudo mv WiFiAuthProbe /opt/deauther

# Create a symbolic link
sudo ln -s /opt/deauther/deauther /usr/local/bin/deauther

# Make it executable
sudo chmod +x /opt/deauther/deauther
