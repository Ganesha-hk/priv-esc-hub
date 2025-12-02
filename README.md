# ⚡ Priv-Esc Hub

A curated collection of *Privilege Escalation techniques, scripts, exploits, and notes* for both Linux and Windows.  
Focused on *real-world offensive security*, red teaming, and penetration testing.

---

## 🔥 Features

- 🧪 *Linux Priv-Esc* – kernel exploits, SUID abuse, capabilities, PATH hijacking  
- 🪟 *Windows Priv-Esc* – misconfigurations, UAC bypass, weak service perms  
- 💉 *Privilege Escalation Scripts* – automated enumeration + exploit helpers  
- 📄 *Cheatsheets & Methodologies*  
- 🧰 Ready-to-use *payloads + commands*  
- 🛠 Tools for detection & escalation paths  

---

## 🧭 Directory Structure


priv-esc-hub/
├── linux/
│   ├── scripts/
│   ├── exploits/
│   └── cheatsheets/
├── windows/
│   ├── scripts/
│   ├── exploits/
│   └── cheatsheets/
└── resources/
    ├── links.md
    └── notes.md


---

## 🛠 Offensive Tools Used

| Category | Tools |
|---------|-------|
| Recon | Nmap, RustScan, LinPEAS, WinPEAS |
| Exploitation | Metasploit, Impacket, BloodHound |
| Enum | PowerUp, PowerView, Seatbelt |
| Scripting | Python, Bash, PowerShell |

---

## 📌 Priv-Esc Focus Areas

### 🐧 *Linux*
- Weak file/folder permissions  
- SUID/SGID binaries  
- Cronjobs  
- Kernel exploits  
- Capabilities abuse  
- Docker/LXC breakout  
- PATH hijacking  

### 🪟 *Windows*
- Unquoted service paths  
- Weak service permissions  
- Registry escalation  
- Token impersonation  
- UAC bypass techniques  
- DLL hijacking  

---

## 📂 Scripts Included

- linux-enum.sh — Quick Linux privilege escalation scanner  
- win-enum.ps1 — Windows enumeration script  
- capability-checker.sh — Scan for Linux capabilities  
- service-perm-check.ps1 — Service permission misconfig finder  

---

## ⚔ For Red Teamers

This repo is designed for:

- Penetration Testers  
- Red Team Operators  
- Bug Bounty Hunters  
- OSCP/OSWP/CRTP learners  
- Anyone learning *post-exploitation & escalation*

---

## 🧩 Disclaimer

This project is for *educational and ethical security testing only*.  
Do not use it for illegal activity.

---

## 🔥 ASCII Banner


██████╗ ██████╗ ██╗██╗   ██╗     ███████╗███████╗██╗  ██╗
██╔══██╗██╔══██╗██║╚██╗ ██╔╝     ██╔════╝██╔════╝██║  ██║
██████╔╝██████╔╝██║ ╚████╔╝█████╗█████╗  ███████╗███████║
██╔══██╗██╔══██╗██║  ╚██╔╝ ╚════╝██╔══╝  ╚════██║██╔══██║
██████╔╝██║  ██║██║   ██║        ██║     ███████║██║  ██║
╚═════╝ ╚═╝  ╚═╝╚═╝   ╚═╝        ╚═╝     ╚══════╝╚═╝  ╚═╝


---

## ⭐ Contributions  
PRs, scripts, exploits & notes are welcome.

---
✅ Additional repos (recon, exploits, automation, etc.)

Just tell me!
