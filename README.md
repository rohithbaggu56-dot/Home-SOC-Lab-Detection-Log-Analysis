## 🛡️ Home SOC Lab | SIEM, Firewall Monitoring & AI-Assisted Detection

![Splunk](https://img.shields.io/badge/Splunk-SIEM-000000?style=for-the-badge&logo=splunk&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-Network_Analysis-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Windows](https://img.shields.io/badge/Windows_Event_Logs-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_Log_Analysis-333333?style=for-the-badge&logo=linux&logoColor=white)


## Summary
This project documents my Home SOC Lab built to practice SOC Analyst (L1) skills such as log analysis, alert investigation, phishing analysis, and basic network traffic analysis using real tools and workflows.The lab was later expanded with pfSense firewall monitoring, Wazuh SIEM integration, and AI-assisted alert triage using AIRIA to simulate a real SOC environment.

## 🎯Objective
To gain hands-on experience with SOC fundamentals by simulating a small lab environment and practicing detection, investigation, and log analysis from a defender’s perspective.
- Understand network visibility using firewall telemetry
- Practice endpoint monitoring using Wazuh agents
- Explore AI-assisted log triage and investigation workflows

## 🔭Project Scope
This lab focuses on SOC Analyst (L1) fundamentals and does not include advanced detection engineering or automation.Additional scope included firewall monitoring, centralized log collection, and AI-assisted investigation workflows to replicate real SOC analyst operations.
## 🔎 SOC Workflow Simulation
1. Attack traffic generated from Kali Linux
2. Network activity inspected through pfSense firewall
3. Endpoint logs collected using Wazuh agents
4. Logs forwarded to Splunk for analysis
5. Dashboards used to identify anomalies
6. AIRIA AI assisted alert triage and investigation
7. Indicators of Compromise (IOCs) documented

## 🧪Lab Architecture
<img width="2816" height="1536" alt="Gemini_Generated_Image_9zlyo09zlyo09zly" src="https://github.com/user-attachments/assets/16442680-488c-46d7-84b9-a7e51915e88e" />

**Endpoints**
- Windows 10 VM – Primary endpoint for log analysis
- Ubuntu Linux VM – Linux log and process monitoring
- Kali Linux VM – Traffic generation and analysis support

**Monitoring & Analysis**
- Splunk – Centralized log ingestion and searching
- Windows Event Viewer – Native Windows log analysis
- Wireshark – Network traffic capture and analysis
- Sysmon – for advanced Windows telemetry
 ### 🔐 Security & Monitoring Expansion
 - **pfSense Firewall**
  - Network segmentation and traffic control
  - Monitored internal lab communication
  - Simulated enterprise firewall visibility

- **Wazuh SIEM**
  - Endpoint agents deployed on Windows and Linux
  - Collected authentication and system activity logs
  - Supported detection and alert monitoring

- **AIRIA AI Agent**
  - Assisted log triage during investigations
  - Helped identify suspicious behavior patterns
  - Used as AI-supported SOC analyst workflow

## ⚒️What I Did in This Lab

- Designed and built a multi-VM SOC lab environment
- Collected and analyzed Windows security event logs
- Investigated authentication and system-related events
- Performed log searching and analysis using Splunk
- Captured and analyzed network traffic using Wireshark
  ## DNS Log Analysis (Splunk)

- Ingested DNS logs in JSON format into Splunk
- Analyzed queried domains and DNS record types
- Identified frequently accessed domains and internal queries
- Practiced SOC-style investigation using search and aggregation



## Skills Practiced
- Log Analysis & Alert Investigation  
- Windows and Linux Fundamentals for SOC  
- Basic Network Traffic Analysis  
- Incident Investigation Workflow  

## 💻Lab Screenshots
**1. Virtualized Home SOC Lab Environment (local VMs, NAT networking)**
<img width="1920" height="1080" alt="Home-lab setup" src="https://github.com/user-attachments/assets/fa8ae1ea-7d7d-4bde-9f35-297603b8b60d" />


**2. Windows Event Viewer – Security Event Logs (Windows 10 VM)**
<img width="1897" height="689" alt="Windows-Event-Viewer" src="https://github.com/user-attachments/assets/dc5c4cb2-2582-453b-aece-2482591ab5b2" />


**3. Linux authentication log analysis (OpenSSH)**
<img width="1910" height="922" alt="Ubuntu-SSH-log analysis" src="https://github.com/user-attachments/assets/decf839d-d7b9-46de-9258-ac9d1bc41660" />
OpenSSH log file analyzed for practice and investigation purposes.



**4. Splunk – DNS Log Analysis**
<img width="1920" height="961" alt="Splunk-Dns log-Search" src="https://github.com/user-attachments/assets/61901e89-5de8-48bc-8273-ee437e07fa6a" />


**5. Wireshark – DNS Response Analysis**
<img width="1903" height="975" alt="Wireshark-Dsn analysis" src="https://github.com/user-attachments/assets/e5ff993d-f406-45d2-92b5-ca0830d61c57" />


## 📝Key Takeaways
- Understood how attacker activity appears in logs  
- Improved confidence in reading Windows and Linux logs  
- Learned how SIEM tools support SOC investigations  

---
🔗 **Navigation**  
⬅️ [Back to Portfolio](https://github.com/rohithbaggu56-dot)
---
