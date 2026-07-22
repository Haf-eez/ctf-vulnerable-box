# 🧠 Custom CTF Vulnerable Box (Ubuntu)

## 📌 Overview
This project is a custom-built Capture The Flag (CTF) virtual machine designed to simulate real-world cybersecurity vulnerabilities across multiple domains.

It includes 10 challenges across web exploitation, cryptography, network security, forensics, and privilege escalation.

## 📄 Full Technical Documentation
Detailed report explaining the design, vulnerabilities, and walkthrough:

[Download Full Report](./CTF-Vulnerable-Box.pdf)

## 🖥️ Environment Setup
- OS: Ubuntu 20.04 LTS  
- Network: Host-only (isolated lab environment)  
- Attacker Machine: Kali Linux  

## ⚙️ Services & Tools
- Apache2 (Web server)
- PHP (Vulnerable web apps)
- OpenSSH (Remote access)
- Custom TCP services (Ports 4444, 9001)
- Cron jobs (Privilege escalation simulation)

## 🎯 Challenge Categories

### 🌐 Web Exploitation
- SQL Injection (Authentication bypass)
- Stored XSS (Admin session compromise)

### 🔐 Cryptography
- Vigenère cipher decryption
- AES-256 encrypted file (weak key management)

### 🌍 Network Exploitation
- Banner leakage (Port 4444)
- Debug interface abuse (Port 9001)

### 🧪 Forensics
- PCAP traffic analysis
- Polyglot file (PNG + RAR + QR + Base64)

### ⬆️ Privilege Escalation
- Sudo misconfiguration
- PATH hijacking via cron job

## 🧠 What This Project Demonstrates
- Real-world attack simulation  
- Security misconfiguration exploitation  
- Detection & forensic analysis techniques  
- Understanding of attacker workflows  

## 📥 Download CTF Box
👉 [https://apiitlk-my.sharepoint.com/:f:/g/personal/cb013270_students_apiit_lk/IgAbKbNSP8P1QqQ0AuGBj6NJASF8Vs0PZj8hRxvxlqNnO14?e=8HFcWD]

## 🚀 How to Run
1. Import VM into VirtualBox / VMware  
2. Set network to Host-only  
3. Start machine  
4. Attack from Kali Linux  

## ⚠️ Disclaimer
This project is for educational purposes only. Do not deploy in production environments.
