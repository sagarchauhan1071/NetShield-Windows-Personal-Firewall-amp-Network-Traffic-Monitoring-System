# 🛡️ NetShield – Windows Personal Firewall & Network Traffic Monitoring System

NetShield is a Windows-based defensive cybersecurity application designed to provide real-time visibility into network activity, monitor active connections, map network activity to running processes, and assist with Windows Defender Firewall management.

The project focuses on **network monitoring, firewall management, security logging, suspicious activity detection, and security reporting**.

---

## 📌 Project Overview

Modern systems continuously communicate with internal and external networks through multiple applications and background processes. Identifying which applications are communicating, which IP addresses they connect to, and which ports are being used can be difficult using standard Windows tools alone.

**NetShield** provides a centralized security dashboard that helps users monitor and understand network activity on a Windows system.

It combines network connection monitoring, process mapping, firewall management, event logging, alerts, and reporting into a single application.

---

## 🎯 Objectives

- Monitor active network connections in real time
- Identify processes responsible for network connections
- Display source and destination IP addresses
- Monitor ports and network protocols
- Check Windows Defender Firewall status
- Manage firewall rules
- Log network and security events
- Detect potentially suspicious connection patterns
- Generate security alerts
- Display network statistics
- Generate security reports
- Provide a centralized defensive security interface

---

## ✨ Key Features

### 🔹 Real-Time Network Monitoring

Monitor active network connections and display information such as:

- Local IP address
- Local port
- Remote IP address
- Remote port
- Protocol
- Connection status
- Associated process

---

### 🔹 Process-to-Network Mapping

NetShield maps network connections to the processes responsible for them.

Example:

```text
Process       Remote IP        Port     Protocol
-------------------------------------------------
chrome.exe    142.x.x.x        443      TCP
python.exe    127.0.0.1        5000     TCP
svchost.exe   13.x.x.x         443      TCP
