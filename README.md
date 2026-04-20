# SIEM Project: SSH Brute Force Detection

## Overview
This project demonstrates detection of SSH brute-force attacks using a SIEM setup.

## Lab Setup
- Kali Linux (Attacker)
- Ubuntu (Target)
- ELK Stack

## Attack
Hydra was used to perform brute-force attack on SSH.

## Detection
Logs from /var/log/auth.log were analyzed to detect failed login attempts.

## Screenshots

### Hydra Attack
![Hydra](screenshots/hydra-attack.png)

### Logs
![Logs](screenshots/ssh-logs.png)

### Failed Attempts
![Failed](screenshots/failed-logins.png)

### Kibana
![Kibana](screenshots/kibana-dashboard.png)

