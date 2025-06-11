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
![Hack the box completion](/assets/htb.png)


**Key Lessons Learned:**  
- Developed fluency with Wireshark’s interface and filtering syntax.  
- Understood how attackers can be detected through traffic patterns and anomalies.  
- Learned to trace entire conversations (TCP streams) and reconstruct data flow.  
- Recognized the importance of network traffic analysis in SOC and blue team environments.

---

✅ *This module deepened my practical understanding of real-time and forensic packet analysis—an essential skill for cybersecurity analysts and network defenders.*

---

## 🧪 Lab 2: Examine TCP/IP and OSI Models in Action

**Problem Statement:**  
To gain a deeper understanding of how the TCP/IP and OSI networking models operate in real-world scenarios by capturing and analyzing network traffic. The goal was to identify and map data flows to their corresponding layers and understand the interaction between protocols.

**Approach:**  
- Used **Wireshark** to capture live traffic on my local machine while browsing the web and using other network services.  
- Identified protocol types (e.g., Ethernet, IP, TCP, HTTP) and matched them to OSI layers.  
- Followed TCP streams to understand connection setup (three-way handshake), data transmission, and teardown.  
- Compared the TCP/IP model's 4 layers with the OSI model’s 7 layers using actual packet data.

**Tools Used:**  
- Wireshark  
- Mozilla Firefox / Chrome  
- Linux Terminal  
- Ping, Traceroute, and Netstat utilities  

**Screenshots:**  
![OSI Model Packet Analysis](/assets/images/lab2-osi-model-traffic.png)

**Key Lessons Learned:**  
- Understood the real-time application of theoretical network models through packet analysis.  
- Mapped various protocols (e.g., ARP, DNS, TCP, HTTP) to OSI and TCP/IP model layers.  
- Gained hands-on experience in interpreting packet headers and payloads.  
- Reinforced how data encapsulation and de-encapsulation occur across layers during transmission.

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
