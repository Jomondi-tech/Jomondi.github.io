---
layout: page
title: Lab Challenges
permalink: /labs/
---

# 🧪 Lab Challenges

As part of the **Cybershujaa Cloud and Network Security track**, I’ve worked through a variety of hands-on labs that simulate real-world cybersecurity scenarios. These challenges have helped me sharpen my practical skills in network analysis, server security, and protocol understanding. Below are a few highlights.

---

## 🌐 Lab 1: HTB Academy – Introduction to Network Traffic Analysis

**Problem Statement:**  
Learn how to analyze network traffic to identify and interpret key communication protocols and events, forming the foundation for threat detection and incident response.

**Approach:**  
- Completed the HTB Academy module on **Network Traffic Analysis**.
- Used **Wireshark** to inspect `.pcap` files capturing various types of network activity.
- Identified TCP three-way handshakes, DNS lookups, HTTP requests, and suspicious patterns (e.g., FTP logins, plaintext credentials).
- Applied filtering techniques (e.g., `http.request`, `tcp.stream eq 1`) to isolate relevant packets.

**Tools Used:**  
- Wireshark  
- HTB Academy Labs  
- Kali Linux (for optional analysis in terminal)  

**Screenshots:**  
*Include your own if applicable, e.g., packet filter views, credential capture, stream follow output*  
`assets/htb.png`

**Key Lessons Learned:**  
- Developed fluency with Wireshark’s interface and filtering syntax.  
- Understood how attackers can be detected through traffic patterns and anomalies.  
- Learned to trace entire conversations (TCP streams) and reconstruct data flow.  
- Recognized the importance of network traffic analysis in SOC and blue team environments.

---

✅ *This module deepened my practical understanding of real-time and forensic packet analysis—an essential skill for cybersecurity analysts and network defenders.*

---

## 🔐 Lab 2: Hardening a Linux Server

**Problem Statement:**  
Secure an Ubuntu web server against common attack vectors using system hardening best practices.

**Approach:**  
- Configured UFW firewall and blocked all non-essential ports.
- Installed and configured Fail2ban to mitigate brute-force login attempts.
- Removed default Apache modules and updated system packages.

**Tools Used:**  
Ubuntu Server, Apache2, UFW, Fail2ban, SSH

**Screenshots:**  
![Fail2Ban Configuration](../assets/images/lab2-fail2ban.png)

**Key Lessons Learned:**  
- Learned how to reduce the attack surface of a public server.
- Understood basic intrusion prevention and log analysis.

---

## 🔑 Lab 3: SSH Key Authentication and Root Access Restrictions

**Problem Statement:**  
Replace password-based SSH login with key-based authentication to improve remote access security.

**Approach:**  
- Generated SSH key pair using `ssh-keygen`.
- Copied the public key to the server using `ssh-copy-id`.
- Disabled password authentication and root login in `/etc/ssh/sshd_config`.

**Tools Used:**  
SSH, Linux CLI, OpenSSH

**Key Lessons Learned:**  
- Improved understanding of secure remote administration.
- Learned how to troubleshoot SSH access and configuration.

---

## 🧠 Ongoing CTF Challenges (Personal Labs)

**Examples:**  
- Web-based login bypass using SQL injection
- Basic reverse engineering of encoded strings in Python
- Port scanning and enumeration of vulnerable boxes in local lab

**Tools Used:**  
Burp Suite, nmap, sqlmap, Python, netcat

**Key Lessons Learned:**  
- Each challenge sharpens analytical thinking.
- Reinforced core skills in information gathering and exploitation.

---

📌 *This section will be continuously updated with more labs from the Cybershujaa training and personal projects. Want to learn more? [Contact me](/contact/) or check out my [GitHub](https://github.com/jomondi).*
