# Azure SIEM Lab (Guided Project)

## Project Overview
This project is based on a guided walkthrough I followed to gain hands-on experience creating a Security Information and Event Management (SIEM) solution in **Microsoft Azure** using Microsoft Sentinel. The goal here was to simulate a basic home SOC environment by deploying a honeypot VM, forwarding logs to Azure Log Analytics, and integrating Sentinel to detect and analyze real-world attack data.

---

## 1. Setting up the Environment
- Created a Resource Group in Azure to hold project resources  
- Deployed a Virtual Network to host the VM  
- Created a Windows 10 Pro Virtual Machine  
- Configured NSG and firewall rules for any source to try remote login  

![Resource Group](https://github.com/user-attachments/assets/a58fdd65-fc1c-40b0-b813-7196bb153f67)  
![Virtual Machine](https://github.com/user-attachments/assets/f7ceb0cb-6cb4-497c-8161-c8953e1ec3fc)

---

## 2. Configuring Log Analytics
- Set up a Log Analytics Workspace  
- Connected the VM to the workspace  

![Log Analytics](https://github.com/user-attachments/assets/9f6b1661-86bb-4435-9906-bb0e00aba133)

---

## 3. Integrating Microsoft Sentinel
- Enabled Microsoft Sentinel on the workspace  
- Configured data connectors for Windows Event Logs   

![Sentinel Setup](https://github.com/user-attachments/assets/c9a8c382-a062-421d-9f30-79f71b499054)

---

## 4. Collecting and Analyzing Security Events
- Queried security event logs using **KQL**  
- Built a query to display geographic locations of attacks  

![KQL Query](https://github.com/user-attachments/assets/a77a2b66-0e5f-42af-82d5-e476f3c18c05)

---

## 5. Building Dashboards
- Built an Attack Map showing global login attempts  
- Monitored attack frequency and sources in real-time  

![Attack Map](https://github.com/user-attachments/assets/5b05ab17-45ff-434d-84a9-22d7e1ce5d7b)

---

## Reference
- Guided project followed from [Josh Madakor on YouTube](https://www.youtube.com/watch?v=g5JL2RIbThM&t=2933s)  
- *This was a guided project, all steps were completed hands-on by me.*
