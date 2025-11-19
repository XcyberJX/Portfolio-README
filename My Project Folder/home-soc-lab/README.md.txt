# Home SOC Lab

This folder documents my beginner-friendly *Home Security Operations Center (SOC) Lab**. 
The goal of this project is learn how logs flow from endpoints into a SIEM and how analyst detect suspicious activity.

---

## Lab Overview
**Purpose:**
To build practical skills in monitoring, log analysis, and detection using virtual machins and open-source tools.

##Components:**
- **Windows 10 VM** - endpoint to generate logs
- **Linux VM** (Ubuntu) - can act as attacker or server
- **SIEM** - Wazuh, Splunk FRee, or Elastic STack
- **Virtualization** - VirtualBox / VMware

---

## Architect Diagram
(Insert my diamgram here)

Example: 

---

## Setup Steps
1. Install VirtualBox / VMware  
2. Deploy Windows 10 VM  
3. Deploy Ubuntu VM  
4. Install SIEM (Elastic / Wazuh / Splunk)  
5. Connect endpoint logs to SIEM  
6. Verify data ingestion  

Detailed setup instructions are in `setup.md`.

---

## Log Sources Configured
- Windows Event Logs  
- Sysmon (optional)  
- Linux auth logs  
- Network events  

---

## Screenshots
All screenshots proving SIEM ingestion live in the `/screenshots` folder.

---

## Skills Demonstrated
- Lab deployment  
- Endpoint monitoring  
- Log ingestion setup  
- Basic SIEM configuration

More features will be added as I improve the lab.
