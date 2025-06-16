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


# 🖥️ Windows Command Line Networking & System Essentials ROOM on TryHackMe

> 🚀 This guide is a complete reference to essential **Windows Command Line (CMD)** commands for system info and network diagnostics. It includes **descriptions, examples, use cases, and tips** — perfect for cybersecurity learners, system admins, and power users.

---

## 📋 Table of Contents

1. [System Commands](#-system-commands)
   - `ver`
   - `systeminfo`
   - `set`
   - `cls`
2. [Help & Navigation](#-help--navigation-commands)
   - `help`
3. [File Management](#-file--folder-management)
   - TBD
4. [Network Configuration & Troubleshooting](#-network-configuration--troubleshooting)
   - `ipconfig`
   - `ping`
   - `tracert`
   - `nslookup`
   - `netstat`

---

## 🖥️ System Commands

### 🔹 `ver`

- ✅ **Description:** Displays the Windows operating system version.
- 🧠 **Example:**  
  ```cmd
  ver
  ```
- 🎯 **Use Case:** Quick check of the OS version when writing scripts or logging system information.
- ⚡ **Tip:** Useful in forensic logs and documentation to confirm the system's build.

---

### 🔹 `systeminfo`

- ✅ **Description:** Shows detailed information about your system including OS version, hardware config, RAM, and network interfaces.
- 🧠 **Example:**  
  ```cmd
  systeminfo | more
  ```
- 🎯 **Use Case:** Collect system specs for audit, incident response, or documentation.
- ⚡ **Tip:** Use `| more` to view large output one page at a time. Use `CTRL + C` to exit paging.

---

### 🔹 `set`

- ✅ **Description:** Displays environment variables, including the PATH.
- 🧠 **Example:**  
  ```cmd
  set
  ```
- 🎯 **Use Case:** Check where CMD looks for executables (`Path=`). Useful in debugging commands not found.
- ⚡ **Tip:** Combine with `findstr` to filter:
  ```cmd
  set path
  ```

---

### 🔹 `cls`

- ✅ **Description:** Clears the screen of previous commands.
- 🧠 **Example:**  
  ```cmd
  cls
  ```
- 🎯 **Use Case:** Start fresh when things get too cluttered.
- ⚡ **Tip:** No confirmation — instantly wipes terminal view.

---

## 📘 Help & Navigation Commands

### 🔹 `help`

- ✅ **Description:** Lists available commands and provides basic syntax help.
- 🧠 **Example:**  
  ```cmd
  help dir
  ```
- 🎯 **Use Case:** Look up how to use a command without Googling.
- ⚡ **Tip:** Works with most native CMD commands.

---

## 📁 File & Folder Management

_Coming soon…_

---

## 🌐 Network Configuration & Troubleshooting

### 🔹 `ipconfig`

- ✅ **Description:** Shows network adapter configuration (IP address, Subnet, Gateway).
- 🧠 **Example:**  
  ```cmd
  ipconfig
  ```
- 🎯 **Use Case:** Identify your machine’s IP address or troubleshoot connectivity issues.
- ⚡ **Tip:** Add `/all` for more info (DNS, DHCP):
  ```cmd
  ipconfig /all
  ```

---

### 🔹 `ping`

- ✅ **Description:** Sends ICMP packets to check if a host is reachable.
- 🧠 **Example:**  
  ```cmd
  ping example.com
  ```
- 🎯 **Use Case:** Diagnose whether a website/server is online and reachable.
- ⚡ **Tip:** Great for latency checks. Shows average round-trip time.

---

### 🔹 `tracert`

- ✅ **Description:** Traces the path packets take to a host.
- 🧠 **Example:**  
  ```cmd
  tracert example.com
  ```
- 🎯 **Use Case:** Identify where the network path is slow or broken (which hop is failing).
- ⚡ **Tip:** Add `-d` to skip DNS lookup for faster results.

---

### 🔹 `nslookup`

- ✅ **Description:** Resolves domain names to IP addresses using DNS.
- 🧠 **Example:**  
  ```cmd
  nslookup example.com
  nslookup example.com 1.1.1.1
  ```
- 🎯 **Use Case:** Test DNS resolution and troubleshoot domain issues.
- ⚡ **Tip:** Try custom DNS servers (e.g., Google `8.8.8.8`, Cloudflare `1.1.1.1`).

---

### 🔹 `netstat`

- ✅ **Description:** Shows active connections, listening ports, and associated processes.
- 🧠 **Example:**  
  ```cmd
  netstat -abon
  ```
- 🎯 **Use Case:** Discover what services are using your network. Helps spot malware or unauthorized access.
- ⚡ **Tips:**
  - `-a`: All connections and listening ports.
  - `-b`: Shows executable involved.
  - `-o`: Shows process ID (PID).
  - `-n`: Skip DNS lookup for speed.

---

## 🧠 Summary Cheatsheet

| Command         | Purpose                       | Quick Example                |
|----------------|-------------------------------|------------------------------|
| `ver`          | Show OS version               | `ver`                        |
| `systeminfo`   | System details                | `systeminfo | more`          |
| `set`          | View env variables            | `set path`                   |
| `ipconfig`     | View IP config                | `ipconfig /all`              |
| `ping`         | Check connectivity            | `ping google.com`            |
| `tracert`      | Trace route to a server       | `tracert example.com`        |
| `nslookup`     | DNS resolution                | `nslookup example.com`       |
| `netstat`      | Show active connections       | `netstat -abon`              |
| `help`         | Command syntax help           | `help dir`                   |
| `cls`          | Clear terminal                | `cls`                        |

---

> 🔐 **Pro Tip for Cybersecurity Learners:** Mastering the CLI is essential for working on remote systems, automating audits, and spotting vulnerabilities quickly.
