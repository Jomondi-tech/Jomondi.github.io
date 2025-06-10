---
layout: page
title: Lab Challenges
permalink: /labs/
---

# 🧪 Lab Challenges

As part of the **Cybershujaa Cloud and Network Security track**, I’ve worked through a variety of hands-on labs that simulate real-world cybersecurity scenarios. These challenges have helped me sharpen my practical skills in network analysis, server security, and protocol understanding. Below are a few highlights.

---

## 🔍 Lab 1: Packet Analysis with Wireshark

**Problem Statement:**  
Understand how the OSI and TCP/IP models function by capturing and analyzing real-time network traffic.

**Approach:**  
- Used Wireshark to monitor and filter packets for HTTP, DNS, and ICMP protocols.
- Identified different OSI layers involved in communication.
- Tracked the lifecycle of a TCP handshake and DNS query.

**Tools Used:**  
Wireshark, Linux terminal (ping, curl)

**Screenshots:**  
![TCP Handshake](../assets/images/lab1-tcp-handshake.png)

**Key Lessons Learned:**  
- Gained practical experience in dissecting packet headers.
- Strengthened understanding of protocol-layer interactions.

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
