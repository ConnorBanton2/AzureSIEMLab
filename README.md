<h1> Azure SIEM Lab (Guided Project)</h1>


<h2>Description</h2>
This project was completed as a guided lab, where I followed step-by-step instructions to build a basic Security Operations Center (SOC) in Microsoft Azure. I deployed a virtual machine (VM), exposed it as a honeypot, and integrated Microsoft Sentinel to analyze real-world attack data.

<br />

<h2>Project overview:</h2>

This document provides a detailed step-by-step walkthrough of how I built a SIEM solution in Azure as part of a guided project.

---

## 1. Setting up the Environment
- Created a **Resource Group** in Azure to hold project resources  
- Deployed a **Virtual Network** to host the VM  
- Created a **Windows 10 Pro Virtual Machine**  
- Configured **RDP access** for remote login  

📸 *Screenshot example:*  
![Resource Group](./screenshots/resource-group.png)

---

## 2. Configuring Log Analytics
- Set up a **Log Analytics Workspace**  
- Connected the VM to the workspace  
- Verified data ingestion from Windows event logs  

📸 *Screenshot example:*  
![Log Analytics](./screenshots/log-analytics.png)

---

## 3. Integrating Microsoft Sentinel
- Enabled **Microsoft Sentinel** on the workspace  
- Configured **data connectors** for Windows Security Events  
- Created a **basic analytic rule** to detect failed logins  

📸 *Screenshot example:*  
![Sentinel Dashboard](./screenshots/sentinel-dashboard.png)

---

## 4. Collecting and Analyzing Security Events
- Generated failed login attempts on the VM  
- Queried events using **KQL** (e.g., failed RDP logins)  
- Built a query to display geographic locations of attacks  

📸 *Screenshot example:*  
![KQL Query](./screenshots/kql-query.png)

---

## 5. Building Dashboards
- Created visual dashboards in Sentinel  
- Built an **Attack Map** showing global login attempts  
- Monitored attack frequency and sources in real-time  
<img width="80%" height="80%" alt="Screenshot 2025-09-17 at 12 35 44 PM" src="https://github.com/user-attachments/assets/5b05ab17-45ff-434d-84a9-22d7e1ce5d7b" />

 

---

## 📚 References
- Guided project followed from [this YouTube video](https://www.youtube.com/watch?v=g5JL2RIbThM&t=2933s)

---


</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
