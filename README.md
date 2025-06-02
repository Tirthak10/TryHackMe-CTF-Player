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
<pre> ```cpp #include <iostream> using namespace std; int main() { cout << "============================\n"; cout << " TryHackMe CTF Player\n"; cout << "============================\n"; cout << "Alias : Sovereign10 (Tirthak)\n"; cout << "Global Rank : Under 350,000\n"; cout << "Platform : TryHackMe - Learn Cybersecurity\n"; cout << "============================\n"; cout << "Keep Hacking. Stay Curious. 🕵️‍♂️\n"; return 0; } ``` </pre>

```bash
g++ main.cpp -o tryhackme_ctf
./tryhackme_ctf
