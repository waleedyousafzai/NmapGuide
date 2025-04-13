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
```bash
nmap -p21,22,80 192.168.1.5    # Specific ports
nmap -iL targets.txt            # Scan from file
nmap 192.168.1.1-100 --exclude 50-60
