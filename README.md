# siem-elk-bruteforce-detection
# SIEM Project: SSH Brute Force Detection using ELK Stack

## 🔥 Overview
This project demonstrates detection of SSH brute-force attacks using ELK Stack in a virtual lab.

## 🧱 Lab Setup
- Kali Linux (Attacker)
- Ubuntu (Target + SIEM)
- ELK Stack
- Filebeat

## ⚙️ Architecture
Kali → SSH Attack → Ubuntu → Logs → ELK → Detection

## ⚔️ Attack Simulation
hydra -l <username> -P passwords.txt ssh://<target-ip>

## 📊 Detection
Logs analyzed from:
/var/log/auth.log

Detected:
- Failed password attempts
- Attacker IP

## 📸 Screenshots
(Add your images here)

## 🚀 Result
Successfully detected brute-force attack using SIEM.

## 🧠 Skills
SIEM | ELK | Log Analysis | Cybersecurity
