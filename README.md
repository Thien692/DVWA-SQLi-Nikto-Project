# DVWA-SQLi-Nikto-Project

This is a hands-on ethical hacking project where I set up a vulnerable environment using **DVWA (Damn Vulnerable Web Application)** and performed vulnerability scans using **SQLMap** and **Nikto**.

---

## 🔧 Lab Setup

- **Environment**: VirtualBox with 2 VMs (Attacker & Victim)
- **Victim Machine**: DVWA hosted on Apache2 & MariaDB (Linux Debian)
- **Attacker Machine**: Kali Linux

---

## ⚙️ Tools Used

- **DVWA**: Web application designed for testing web vulnerabilities
- **Nikto**: Web server scanner to detect insecure files and configurations
- **SQLMap**: Automated tool for detecting and exploiting SQL Injection vulnerabilities

---

## 🔍 What I Did

1. Set up and configured DVWA on the victim VM.
2. Scanned the web server with **Nikto** to detect:
   - Missing headers (e.g., X-Frame-Options)
   - Insecure HTTP methods
3. Used **SQLMap** to exploit SQLi on the `id` parameter:
   - Detected Boolean-based & Time-based SQL Injection
   - Identified backend DBMS: MySQL (MariaDB fork)

---

## 📷 Screenshots

You can find screenshots of:
- Cookie session inspection
- SQLMap payloads
- Nikto scan results
- Successful login and exploitation

---

## 📚 Skills Gained

- Vulnerability Scanning (Nikto)
- SQL Injection Exploitation (SQLMap)
- Ethical hacking lab design
- HTTP header & method analysis

---

## 🚨 Disclaimer

> All testing was conducted in an isolated lab environment for ethical and educational purposes only. Never run these tools against systems you do not own or have explicit permission to test.
