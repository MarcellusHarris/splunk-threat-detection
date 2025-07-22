#  Splunk Threat Detection & Log Analysis Project

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
![Platform](https://img.shields.io/badge/Platform-Splunk-blueviolet)
![Project Type](https://img.shields.io/badge/Project-Threat--Detection-red)

This project showcases how Splunk can be used to detect suspicious activity across enterprise logs. It includes custom dashboards, mapped alerts based on the MITRE ATT&CK framework, and analysis techniques for identifying potential threats using real-world-style scenarios.

##  Presentation
View the full walkthrough:  
**[Splunk Threat Detection Slides (Google Slides)](https://docs.google.com/presentation/d/1MgRZ0GU5EhEWFDaDAdu7tRQI3nGlzzlW365Y1LsfOZI/edit?usp=sharing)**

##  Project Features

This Splunk project simulates a real-world security monitoring scenario using enterprise log data. It includes:

-  **Suspicious PowerShell Detection**: SPL query to identify encoded or obfuscated PowerShell usage.
-  **Custom Dashboards**: Visualizations to track anomalies, user behavior, and script-based threats.
-  **Detection Rules**: Custom correlation searches to trigger alerts based on attacker patterns.
-  **Event Correlation**: Demonstrates how to connect multiple log sources for deeper threat context.
-  **Sample Data Sources**: Includes Windows Event Logs and user activity logs to simulate realistic behavior.

---

## Tools & Technologies
- **Splunk Enterprise**
- **Windows Event Logs & Sysmon**
- **MITRE ATT&CK**
- **Sigma Rules**
- **PowerShell Logging**

---

## Project Goals
- Detect privilege escalation, persistence, and lateral movement
- Use real log data to simulate a compromise
- Build dashboards with queries and visualizations
- Trigger custom alerts based on suspicious activity

---

## Outcome
This hands-on project strengthened my ability to:

- Identify adversary behavior using Splunk  
- Create efficient detection rules  
- Understand event correlation in enterprise environments

---

## Repo Structure
splunk-threat-detection/
├── README.md
├── screenshots/
│   ├── dashboard.png
│   └── powershell-alert.png
└── LICENSE

---

##  Dashboard Overview

This screenshot shows the custom Splunk dashboard built to detect suspicious PowerShell activity and other threat behaviors across endpoints.

![Dashboard Overview](./dashboard-overview.png.pdf)





