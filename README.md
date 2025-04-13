# 🔍 Nmap Master Guide by Waleed Yousafzai 🛡️  
*Your Ultimate Ethical Hacking Companion for Network Scanning & Pentesting*  

[![Nmap Course](https://img.shields.io/badge/YouTube-Nmap_Course-FF0000?style=for-the-badge&logo=youtube)](https://www.youtube.com/playlist?list=PLKzQIXgxD4FpHSeh7MexJRCQrZIQV2v0h)  
[![Lab Setup](https://img.shields.io/badge/YouTube-Lab_Setup-FF0000?style=for-the-badge&logo=youtube)](https://www.youtube.com/playlist?list=PLKzQIXgxD4Fplje9rKeq7FgHTiScpu-l8)  

---

## 📚 Table of Contents  
- [🚀 Getting Started](#-getting-started)  
- [💡 Core Concepts](#-core-concepts)  
- [🚨 Advanced Techniques](#-advanced-techniques)  
- [🎯 Real-World Labs](#-real-world-labs)  
- [🎥 Video Courses](#-video-courses)  
- [📝 Cheat Sheet](#-cheat-sheet)  
- [🤝 Contribute](#-contribute)  

---

## 🛠️ Getting Started  

### What You'll Learn  
- 🎯 **Nmap Fundamentals**: Master syntax, flags, and scanning techniques  
- 🔥 **Host Discovery**: Find live devices in seconds  
- 🕵️ **Stealth Tactics**: Bypass firewalls like a pro  
- 🤖 **Scripting Engine (NSE)**: Automate attacks & vulnerability detection  

### Lab Setup  
🔧 Need a lab? Follow my step-by-step tutorials:  
[![Lab Setup Playlist](https://img.shields.io/badge/WATCH_LAB_SETUP-FF0000?style=flat&logo=youtube)](https://www.youtube.com/playlist?list=PLKzQIXgxD4Fplje9rKeq7FgHTiScpu-l8)  

---

## 💡 Core Concepts  

### 1. Target Specification 🎯  

nmap -p21,22,80 192.168.1.5    # Specific ports
nmap -iL targets.txt            # Scan from file
nmap 192.168.1.1-100 --exclude 50-60


2. Host Discovery 🌐

nmap -sn 192.168.1.0/24        # Fast ping scan
nmap -PS80,443 -PA21 target_ip # SYN/ACK stealth

3. Service Detection 🔓
nmap -sV --version-intensity 5 target_ip
nmap -sU -p53,67 target_ip     # UDP services

🚨 Advanced Techniques
Firewall Evasion 🎩
nmap -f -D decoy1,decoy2,ME target_ip  # Fragment + Decoys
nmap -S 192.168.1.100 -e eth0 target_ip # Spoof IP

Timing Optimization ⏱️
nmap -T5 --min-rate 1000 target_ip    # Speed demon mode
nmap --scan-delay 500ms target_ip     # Avoid IDS

🎯 Real-World Labs
Lab 1: Metasploitable Recon
Goal: Map all services on a vulnerable VM
nmap -A -p- 192.168.1.5

Lab 2: Firewall Evasion Challenge
nmap -f --script=firewall-bypass target_ip

🎥 Video Courses
Nmap Course
https://www.youtube.com/playlist?list=PLKzQIXgxD4FpHSeh7MexJRCQrZIQV2v0h

🤝 Contribute
Found a bug? Want to add labs?


📌 Resources
Official Nmap Documentation

Kali Linux Setup Guide

🌟 Crafted by Waleed Yousafzai
Pentester | Educator | Open-Source Advocate

📜 License: MIT
⚠️ Ethical Note: Always obtain proper authorization for scanning

GitHub Stars

**Key Features**:
- 🎨 Modern shield badges for visual hierarchy
- 🖥️ Syntax-highlighted code blocks
- 🔗 Interactive YouTube playlist links
- 📱 Mobile-responsive structure
- 🔍 Clear section navigation
- 💾 Download-ready cheat sheet link
- 🤝 Clear contribution guidelines

