# SOC-HOME-Lab
SOC Home Lab — Windows Threat Detection and Incident Investigation

PROJECT OVERVIEW
This project is a personal Security Operations Center 
home lab designed to simulate security monitoring, 
attack detection, alerting, and incident investigation.

The lab uses Splunk Enterprise as the SIEM,
Windows as the monitored endpoint, 
Ubuntu as the Splunk server, and Kali Linux as the attacker machine.

LAB ARCHITECTURE

Splunk Server: Ubuntu
Monitored Endpoint: Windows
Attacker Machine: Kali Linux
SIEM: Splunk Enterprise
Log Forwarder: Splunk Universal Forwarder
Network Monitoring: Windows Security Event Logs
Attack Tool: Nmap


OBJECTIVE

Collect Windows Security logs in Splunk
Detect failed login attempts
Detect possible brute-force attacks
Detect suspicious network connections
Detect possible port-scanning activity
Create Splunk dashboards
Configure security alerts
Investigate suspicious activity


TECHNOLOGIES USED 

Splunk Enterprise
Splunk Universal Forwarder
Windows Event Logs
Ubuntu Linux
Kali Linux
Nmap
VirtualBox
SPL
Windows Filtering Platform


DETECTION USE CASE

1.Failed login detection
2.Brute-force detection
3.Successful login monitoring
4.Network connection monitoring
5.Blocked connection monitoring
6.Possible port-scan detection

Example Event IDs
4624 — Successful login
4625 — Failed login
4672 — Special privileges assigned
5156 — Network connection allowed
5157 — Network connection blocked


CURRENT PROJECT STATUS

Virtual lab setup: Completed
Splunk installation: Completed
Windows log forwarding: Completed
Kali setup: Completed
SPL searches: Completed
Dashboard creation: Completed
Alert creation: Completed
Incident investigation: Completed
GitHub documentation: Completed


DISCLAIMER

This project was performed in an isolated and authorized 
home lab environment for educational and defensive 
cybersecurity purposes.
