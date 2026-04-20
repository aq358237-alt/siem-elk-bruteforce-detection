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

### Hydra Attack
![Hydra Attack](screenshots/hydra-attack.png)

### SSH Logs
![SSH Logs](screenshots/ssh-logs.png)

### Failed Logins
![Failed Logins](screenshots/failed-logins.png)

### Kibana Dashboard
![Kibana](screenshots/kibana-dashboard.png)
(Add your images here)

## 🚀 Result
Successfully detected brute-force attack using SIEM.

## 🧠 Skills
SIEM | ELK | Log Analysis | Cybersecurity
