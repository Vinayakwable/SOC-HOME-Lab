🛡️ SOC Home Lab — Threat Detection & Incident Investigation

� A hands-on Security Operations Center (SOC) home lab built for log monitoring, threat detection, alerting, and incident investigation. 

📌Project Overview

This project simulates a small Security Operations Center (SOC) environment using virtual machines.
The lab demonstrates how a SOC analyst can:
📥 Collect endpoint logs
🔎 Search and analyze security events
🚨 Detect suspicious activity
📊 Build security dashboards
🔔 Configure SIEM alerts
🕵️ Investigate security incidents
📝 Document findings and evidence
The entire environment is built in an isolated home lab using VirtualBox.

🖥️ Lab Environment
Component :🐧 Ubuntu | Role: Splunk Server
Component : 🪟 Windows | Role: Monitored Endpoint
Component : 🐉 Kali Linux | Role: Attacker / Simulation
Component : 🔐 Splunk | Role: SIEM
Component : 📡 Universal Forwarder | Role: Log Collection
Component :🌐 VirtualBox | Role: Virtualization

📌 SOC Workflow

Attack / Suspicious Activity
            ↓
      Windows Endpoint
            ↓
    Windows Event Logs
            ↓
 Splunk Universal Forwarder
            ↓
    Splunk Enterprise
            ↓
      SPL Detection
            ↓
        Alert 🚨
            ↓
   Incident Investigation
            ↓
      Evidence & Report

🎯 Project Objectives

VirtualBox Lab Setup ✅
Ubuntu Splunk Server ✅
Windows Endpoint ✅
Kali Attacker ✅
Splunk Universal Forwarder ✅
Windows Security Logs ✅
SPL Searches ✅
Security Dashboards ✅
Brute-Force Detection ✅
Port-Scan Detection ✅
Security Alerts ✅
Incident Investigation ✅


🛠️ Technologies Used
SIEM : Splunk Enterprise
Operating Systems : Ubuntu Server, Windows, Kali Linux
Security Tools : Nmap, Windows Event Viewer, Windows Filtering Platform, Splunk Universal Forwarder
Virtualization : Oracle VirtualBox
Detection : SPL, Windows Security Event IDs, Network connection analysis      


🔎 Detection Use Cases

🚨 1. Brute-Force / Multiple Failed Logins
🚨 2.Possible port scan 
🚨 3.Blocked Network Connection 
🚨 4.Successful Login Monitoring 


🚨 Splunk Alerts
Brute Force - Multiple Failed Logins>5 failed logins / 5 min ✅
Possible Port Scan - High Connections>10 connections / 1 min ✅

📊 Splunk Dashboard
The SOC dashboard contains:
🔐 Authentication Monitoring
Failed Login Activity
Successful Login Activity
Failed Logins by Account

🌐 Network Monitoring
Network connection activity
Allowed connections
Blocked connections
Suspicious source IPs

🚨 Detection
Brute-force activity
Possible port scanning
Security event monitoring

📚 Skills Demonstrated

SOC Operations:
Security monitoring
Alert analysis
Log analysis
Incident investigation
Threat detection

Splunk:
SPL searches
Event filtering
Statistics
Time-based analysis
Dashboards
Alerts

Windows Security:
Windows Event Logs
Authentication events
Network security events
Windows Filtering Platform

Networking:
TCP/IP
IP addressing
Network connections
Port scanning
Firewall behavior

Linux:
Ubuntu administration
Kali Linux
CLI operations

🧠 Key SOC Analyst Concepts Practiced
Log Collection
      ↓
Normalization
      ↓
Detection
      ↓
Alerting
      ↓
Triage
      ↓
Investigation
      ↓
Evidence Collection
      ↓
Incident Documentation

⚠️ Disclaimer
This project was performed in an isolated and authorized home laboratory environment for educational and defensive cybersecurity purposes.
No unauthorized systems or external targets were tested.

👨‍💻 Author
Vinayak Wable
Cyber Security Enthusiast
Focus Areas:
SOC Analyst • SIEM • Threat Detection • Incident Response • Network Security
