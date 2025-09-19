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
- Configured NSG and firewall rules for any source to try remote login  

<img width="1403" height="720" alt="Screenshot 2025-09-19 at 12 02 58 AM" src="https://github.com/user-attachments/assets/a58fdd65-fc1c-40b0-b813-7196bb153f67" />

<img width="1003" height="747" alt="Screenshot 2025-09-19 at 12 24 30 AM" src="https://github.com/user-attachments/assets/f7ceb0cb-6cb4-497c-8161-c8953e1ec3fc" />




---

## 2. Configuring Log Analytics
- Set up a **Log Analytics Workspace**  
- Connected the VM to the workspace  
  
<img width="80%" height="80%" alt="Screenshot 2025-09-19 at 12 35 57 AM" src="https://github.com/user-attachments/assets/9f6b1661-86bb-4435-9906-bb0e00aba133" />


---

## 3. Integrating Microsoft Sentinel
- Enabled **Microsoft Sentinel** on the workspace  
- Configured **data connectors** for Windows Security Events   

<img width="80%" height="80%" alt="Screenshot 2025-09-19 at 12 56 36 AM" src="https://github.com/user-attachments/assets/c9a8c382-a062-421d-9f30-79f71b499054" />


---

## 4. Collecting and Analyzing Security Events
- Queried security events using KQL 
- Built a query to display geographic locations of attacks  

<img width="80%" height="80%" alt="Screenshot 2025-09-11 at 7 31 56 PM" src="https://github.com/user-attachments/assets/a77a2b66-0e5f-42af-82d5-e476f3c18c05" />


---

## 5. Building Dashboards
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
