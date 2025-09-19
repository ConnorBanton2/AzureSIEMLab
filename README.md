<h1> Azure SIEM Lab (Guided Project)</h1>


<h2>Description</h2>
This project was completed as a guided lab, where I followed step-by-step instructions to build a basic Security Operations Center (SOC) in Microsoft Azure. I deployed a virtual machine (VM), exposed it as a honeypot, and integrated Microsoft Sentinel to analyze real-world attack data.

<br />

<h2>Project walk-through:</h2>

<h2>1. Setting up the environment</h2> 
* Create a resource group to hold the project resources <br/>
* Deploy a virtual network to host our virtual machine <br/>
<br/>
<img width="80%" height="80%" alt="Screenshot 2025-09-18 at 11 49 32 PM" src="https://github.com/user-attachments/assets/e2bcfd79-1baf-431c-bcb5-ac7973875b8b"/>
<br/>
* Deploy a Windows 10 Pro virtual machine <br/>
<br/>
<img width="80%" height="80%" alt="Screenshot 2025-09-18 at 11 56 20 PM" src="https://github.com/user-attachments/assets/cb18b974-af33-45ac-92c7-53e9896664ea" />
<br />
<br />
<h2>2. Exposing our machine</h2>  
* Configure the rules of our Network Security Group to allow traffic to enter our machine from anywhere <br/>
<br/>
<img width="1403" height="720" alt="Screenshot 2025-09-19 at 12 02 58 AM" src="https://github.com/user-attachments/assets/8543bea1-58cd-4917-80b4-7e72a722fed4" />


<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
