# 👨‍💻 TryHackMe CTF Player (C++ Fun Console App)

This repository contains a fun and beginner-friendly **C++ program** that prints out a TryHackMe-themed banner with my CTF alias, current global rank, and a motivational message to keep hacking and learning.

---

## 🧱 1. Overview

| Field           | Details                                  |
|----------------|-------------------------------------------|
| 🧑‍💻 Alias       | Sovereign10 (Tirthak)                     |
| 🌐 Platform     | [TryHackMe](https://tryhackme.com)       |
| 🌍 Global Rank  | Under 350,000                            |
| ⚙️ Language     | C++                                       |
| 🧠 Project Type | Console Output / Fun Display Program     |

---

## 🖥️ 2. Output Preview
TryHackMe CTF Player
Alias : Sovereign10 (Tirthak)
Global Rank : Under 350,000
Platform : TryHackMe - Learn Cybersecurity
Keep Hacking. Stay Curious. 🕵️‍♂️

---

## 📦 3. Files Included

| File Name   | Description                               |
|-------------|-------------------------------------------|
| `main.cpp`  | Main C++ source file                      |
| `README.md` | Project description and usage instructions|

---

## ⚙️ 4. How to Run

### 💻 Using Terminal (with g++)

```bash
#include <iostream>
using namespace std;

int main() {
    cout << "============================\n";
    cout << "   TryHackMe CTF Player\n";
    cout << "============================\n";
    cout << "Alias       : Sovereign10 (Tirthak)\n";
    cout << "Global Rank : Under 350,000\n";
    cout << "Platform    : TryHackMe - Learn Cybersecurity\n";
    cout << "============================\n";
    cout << "Keep Hacking. Stay Curious. 🕵️‍♂️\n";
    return 0;
}

```

# 🖥️ Windows Networking Commands — Complete Guide for Beginners

Welcome to your personal networking command reference! This document covers the most essential Windows command-line networking tools — perfect for beginners and future cybersecurity professionals.

Each section includes:
- ✅ **Description**
- 🧠 **Example**
- 🎯 **Use Case**
- ⚡ **Tips/Shortcuts**

---

## 📌 Table of Contents

- [ipconfig](#-ipconfig)
- [ipconfig /all](#-ipconfig-all)
- [ping](#-ping)
- [tracert](#-tracert)
- [nslookup](#-nslookup)
- [netstat](#-netstat)
- [netstat -abon](#-netstat--abon)

---

## 🔌 `ipconfig`

✅ **Description**:  
Displays basic IP address, subnet mask, and default gateway.

🧠 **Example**:
```bash
ipconfig
```

🎯 **Use Case**:  
Check your current IP settings and verify network setup.

⚡ **Tips/Shortcuts**:  
Use `ipconfig /release` and `ipconfig /renew` to refresh your IP.

---

## 🔎 `ipconfig /all`

✅ **Description**:  
Displays detailed configuration information for all network adapters.

🧠 **Example**:
```bash
ipconfig /all
```

🎯 **Use Case**:  
Check if DHCP is enabled, find MAC address, or see DNS server info.

⚡ **Tips/Shortcuts**:  
Use this to troubleshoot DNS and DHCP issues.

---

## 🛰️ `ping`

✅ **Description**:  
Sends ICMP packets to check if a host is reachable.

🧠 **Example**:
```bash
ping example.com
```

🎯 **Use Case**:  
Test connectivity to a website or another device.

⚡ **Tips/Shortcuts**:  
Add `-t` to ping continuously until stopped (Ctrl + C).

---

## 🛣️ `tracert`

✅ **Description**:  
Traces the route that packets take to reach a host.

🧠 **Example**:
```bash
tracert example.com
```

🎯 **Use Case**:  
Identify where connection slowdowns or packet losses happen.

⚡ **Tips/Shortcuts**:  
Use it when ping fails to understand *where* the failure occurs.

---

## 🌍 `nslookup`

✅ **Description**:  
Looks up DNS records and resolves domain names to IPs.

🧠 **Example**:
```bash
nslookup example.com
nslookup example.com 1.1.1.1
```

🎯 **Use Case**:  
Verify if a domain resolves correctly and test different DNS servers.

⚡ **Tips/Shortcuts**:  
Use `nslookup` to check DNS poisoning or misconfiguration.

---

## 📡 `netstat`

✅ **Description**:  
Displays current TCP/IP network connections and ports.

🧠 **Example**:
```bash
netstat
```

🎯 **Use Case**:  
Check what remote servers you're connected to.

⚡ **Tips/Shortcuts**:  
Use `netstat -h` to see all options.

---

## 🧠 `netstat -abon`

✅ **Description**:  
Shows all connections, listening ports, program names, and PIDs.

🧠 **Example**:
```bash
netstat -abon
```

🎯 **Use Case**:  
Investigate which program opened which port. Great for troubleshooting malware or suspicious connections.

⚡ **Tips/Shortcuts**:
- `-a`: All ports (active and listening)
- `-b`: Shows executable responsible
- `-o`: Shows Process ID (PID)
- `-n`: Shows addresses in numeric form

---

## 🧠 Bonus Learning Tactics Used in This Guide

- ✅ Real-world analogies to make terms relatable
- ✅ Clean formatting for GitHub & PDF reading
- ✅ Short and practical command blocks for copy-paste ease
- ✅ No fluff — just what matters

---

🧠 **Review & Practice Plan**

Open Command Prompt and try these:

```
ipconfig
ipconfig /all
ping google.com
tracert google.com
nslookup google.com
netstat
netstat -abon
```

💪 Keep practicing — each command makes you more confident and job-ready.

---

✍️ *Generated and compiled by ChatGPT for learning productivity and future reference.*
