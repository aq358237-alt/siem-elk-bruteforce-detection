# 🔐 SIEM Project: SSH Brute Force Detection using ELK Stack

## 🔥 Key Highlight
Built a fully isolated cybersecurity lab to simulate real-world attacks and detect them using SIEM (ELK Stack).

---

## 📌 Overview
This project demonstrates detection of SSH brute-force attacks using log analysis and SIEM techniques.

---

## 🧱 Lab Setup
- Kali Linux (Attacker)
- Ubuntu (Target + SIEM)
- ELK Stack (Elasticsearch, Kibana)
- Filebeat (Log forwarding)

---

## ⚙️ Architecture

Kali → SSH Attack → Ubuntu → Logs → ELK → Detection

---

## ⚔️ Attack Simulation

```bash
hydra -l username -P passwords.txt ssh://<target-ip>

