# 🔐 Wazuh Brute Force Attack Detection Lab

## 📌 Overview
This project demonstrates detection of brute force attacks using Wazuh SIEM and Kali Linux.

## 🛠️ Tools Used
- Wazuh SIEM
- Kali Linux
- Ubuntu
- SSH brute force simulation
- Linux
- Powershell

## ⚙️ Setup
1. Install Wazuh Manager using Ubuntu
2. Install victim window
3. Configure wazuh-agent on victim-window
4. Setup Kali Linux attacker machine

## 🚨 Attack Simulation
- Used Hydra to perform SSH brute force attack using code -
hydra -l administrator -P /usr/share/wordlists/rockyou.txt -t 10 ssh://192.168.29.72

## 📊 Detection
- Wazuh detected multiple failed login attempts with eventis 4625 
- Alerts generated in dashboard

## 📸 Screenshots
<img width="1920" height="1003" alt="Total Count" src="https://github.com/user-attachments/assets/905ccc83-e23f-46d4-b3f6-d3d049026ad0" />
<img width="1920" height="1003" alt="timestamp" src="https://github.com/user-attachments/assets/8331397e-805a-4285-92f6-2cb6eb1dbf69" />
<img width="1920" height="1003" alt="target-username" src="https://github.com/user-attachments/assets/95b21eaf-817d-4138-bfff-124244aab371" />


## 🎯 Learning Outcome
- Understanding SIEM detection rules
- Log analysis
- Attack simulation
