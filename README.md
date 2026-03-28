# Virtualized IDS/IPS and Network Monitoring Lab

---

## 📌 Overview

This project demonstrates a **virtualized SOC monitoring lab** using a pfSense firewall integrated with **IDS/IPS (Suricata & Snort)** to detect and analyze network attacks.  
The lab simulates real-world attacker behavior from Kali Linux and monitors traffic inside a protected internal network.

The goal is to build a **Blue Team detection environment** for security monitoring and threat analysis.

---

## 🎯 Objectives

- Build virtualized IDS/IPS lab environment  
- Simulate attacks using Kali Linux  
- Monitor traffic using pfSense firewall  
- Detect threats using Suricata & Snort  
- Analyze network traffic using Zeek & Tshark  
- Protect internal network assets  

---

## 🛠️ Tools & Technologies

- VMware Workstation / VirtualBox  
- pfSense Firewall  
- Suricata IDS  
- Snort IDS/IPS  
- Kali Linux (Attacker)  
- Windows 10 (Target)  
- Ubuntu Server (Defender)  
- Zeek Network Monitor  
- Tshark Packet Analyzer  

---

## 🌐 Network Architecture

| Component | IP Address | Role |
|-----------|------------|------|
| Kali Linux | 192.168.230.140 | Attacker |
| pfSense WAN | 192.168.230.2 | Firewall WAN |
| pfSense LAN | 192.168.131.1 | Gateway |
| Windows 10 | 192.168.131.2 | Target Machine |
| Ubuntu Defender | 192.168.131.131 | Monitoring Server |

WAN Network: **192.168.230.0/24**  
LAN Network: **192.168.131.0/24**

---

## 🏗️ Architecture Diagram
<img src="https://github.com/Prashant42125/Virtualized-IDS-IPS-and-Network-Monitoring-Lab/blob/main/Networking_ids_ips_project.png" width="900">

---

## ⚙️ Lab Workflow

1. Kali Linux launches attack from WAN network  
2. Traffic reaches pfSense firewall  
3. Suricata/Snort inspect packets  
4. IDS generates alerts  
5. Traffic forwarded to LAN network  
6. Windows 10 acts as victim machine  
7. Ubuntu server monitors traffic using Zeek  
8. Tshark captures packets for analysis  

---

## 🚨 Attacks Simulated

- Nmap Port Scanning  
- SYN Scan  
- Service Detection Scan  
- DDoS Traffic Simulation  
- Network Reconnaissance  

---

## 🔍 Detection Components

### pfSense Firewall
- Network perimeter security  
- Traffic filtering  
- IDS/IPS integration  

### Suricata
- Signature-based detection  
- Real-time alerts  
- Threat monitoring  

### Snort
- Intrusion detection  
- Network signature analysis  

---

## 📊 Monitoring Tools

### Zeek
- Network behavior analysis  
- Protocol logging  
- Traffic visibility  

### Tshark
- Packet capture  
- Traffic inspection  
- Forensic analysis  

---

## 📈 Data Collected

- Source IP addresses  
- Destination IP  
- Port scan attempts  
- Suspicious traffic  
- Attack signatures  
- Network logs  
- Alert events  

---

## 🧠 Skills Demonstrated

- IDS/IPS Deployment  
- Network Security Monitoring  
- Threat Detection  
- SOC Analysis  
- Packet Analysis  
- Firewall Configuration  
- Blue Team Operations  

---

## 👤 Author

**Prashant**  
CEHv13 | SOC Analyst | Blue Team | Threat Detection Enthusiast
