# VulnHub Writeups – Penetration Testing Practice

Welcome to my VulnHub Writeups repository!  
This repository contains detailed penetration testing walkthroughs for vulnerable machines hosted on [VulnHub](https://www.vulnhub.com/).  
Each writeup follows a professional pentesting methodology and is designed for learning, practicing, and sharpening ethical hacking skills.

---

## 📜 Contents

### 1. Kioptrix Level 1
- **Objective:** Gain root access to the Kioptrix Level 1 target machine.
- **Techniques Used:**
  - Network Reconnaissance (ping sweep, Nmap scanning)
  - Service Enumeration (HTTP, SMB)
  - Exploit Research & Weaponization
  - Remote Code Execution (RCE)
  - Privilege Escalation
  - Persistence & Post-Exploitation
- **Exploits:**
  - `OpenLuck` kernel exploit (HTTP service)
  - Samba `trans2open` buffer overflow
- **Outcome:** Full root compromise & persistence established.
- **Full Writeup:** [kiopetrix-1.docx](./kiopetrix-1.docx)

---

## 🛠 Methodology

Each writeup generally follows these steps:
1. **Reconnaissance** – Identifying live hosts and open ports.
2. **Scanning** – Service/version detection and vulnerability identification.
3. **Enumeration** – Gathering system/service information.
4. **Weaponization** – Preparing the exploit code or payload.
5. **Exploitation** – Gaining access through vulnerabilities.
6. **Privilege Escalation** – Obtaining higher-level permissions.
7. **Post-Exploitation** – Persistence, data extraction, and cleanup.

---

## ⚠ Disclaimer

These writeups are for **educational purposes only**.  
Do not attempt these techniques on systems without proper authorization.  
All activities were performed in a **controlled lab environment**.

---

## 📩 Contact

If you’d like to discuss these writeups, share feedback, or collaborate on similar projects, feel free to connect:
- GitHub: [YourGitHubProfile](https://github.com/Antonymaged)
- LinkedIn: [YourLinkedInProfile](https://www.linkedin.com/in/antony-maged-9622bb266)