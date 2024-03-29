<h1>Azure Honeypot</h1>

<h2>Description</h2>
This project is to install a honeypot that will act as a target for attackers, this will allow us to gather information on how these attackers operate. This includes the deployment and network configuration of Azure Cloud resources to host our Honeypot. We will utilize PuTTY, a SSH client for intitial installation of T-pot. T-pot demonstrates live cyber attacks from all over the world, providing information such as attacks by country, attacker IP sources, associated APT's and related CVE's.
<br />


<h2>Utilities and Repositories Used</h2>

- <b>[Azure](https://azure.microsoft.com/en-us)</b>
- <b>[PuTTY](https://www.putty.org/)</b> 
- <b>[T-Pot](https://github.com/telekom-security/tpotce?tab=readme-ov-file#post-install)</b>


<h2>Environments Used </h2>

- <b>Debian 11</b> 

<h2>Program walk-through:</h2>

<p align="center">
Download and Install PuTTY then Connect: <br/>
<img src="https://i.imgur.com/H6V8GVQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<p align="center">
Update and Upgrade Packages: <br/>
<img src="https://i.imgur.com/vmLr0Dh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">
Install Git and then T-pot Configuration: <br/>
<img src="https://i.imgur.com/P8AhxEi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Connect to the Machine via Browser <br/>
<img src="https://i.imgur.com/GtSlmOw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Navigate to the Attack Map: <br/>
<img src="https://i.imgur.com/c6FhMBN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Navigate to Kibana and Open the T-pot Dashboard  <br/>
<img src="https://i.imgur.com/il5mpbC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/WL3UiuU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
You Can Research Some of the Provided CVE's From the Dashboard:  <br/>
<img src="https://i.imgur.com/8nKIgcO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select an IP address of an Attacker and Navigate to Spiderfoot to Scan for Further Information:  <br/>
<img src="https://i.imgur.com/WmfqYRL.png?1" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/ymF8dbI.png?1" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
