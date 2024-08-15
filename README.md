# Azure Sentinel (SIEM) Lab

<h2>Description</h2>
Project consists of setting up Azure Sentinel (SIEM) and connecting it to a live virtual machine acting as a honey pot. I will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to look up the attackers Geolocation information and plot it on the Azure Sentinel Map
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b>
- <b>ipgeolocation.io</b> 

<h2>Environments Used </h2>

- <b>Microsoft Azure</b>

<h2>Program walk-through:</h2>

<p align="center">
Create Azure Subscription: <br/>
<img src="https://i.imgur.com/Ryj3QSg.png" height="40%" width="40%" alt="Active Directory Steps"/>
<img src="https://i.imgur.com/J9UyvsN.png" height="40%" width="40%" alt="Active Directory Steps"/>
<br />
<br />
Create Virtual Machine:  <br/>
<img src="https://i.imgur.com/vInWpJ8.png" height="60%" width="60%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/g2kbtvB.png" height="40%" width="40%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/bqhyNcF.png" height="40%" width="40%" alt="Active Directory Steps"/>
<br />
<br />
Create Log Analytics Workspace: <br/>
<img src="https://i.imgur.com/43hhhij.png" height="40%" width="40%" alt="Active Directory Steps"/>
 <img src="https://i.imgur.com/lXFG3sF.png" height="40%" width="40%" alt="Active Directory Steps"/>
<br />
<br />
Enable gathering VM logs in Security Center:  <br/>
<img src="https://i.imgur.com/dXW46eD.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/8Rgkbfl.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
<br />
Connect Log Analytics to VM:  <br/>
<img src="https://i.imgur.com/HBrw453.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
<br />
Setup Microsoft Sentinel:  <br/>
<img src="https://i.imgur.com/AknTfOj.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
<br />
Log into VM with Remote Desktop:  <br/>
<img src="https://i.imgur.com/TTIX3lU.png" height="40%" width="40%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/EnG8lGl.jpeg" height="40%" width="40%" alt="Active Directory Steps"/>
<br />
<br />
Observe Event Viewer Logs in VM:  <br/>
<img src="https://i.imgur.com/QufTs1i.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/5zvQew6.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
Turn off Windows Firewall on VM:  <br/>
<img src="https://i.imgur.com/pA7dQgq.jpeg" height="80%" width="80%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/b1gw0RI.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
Download PowerShell Script:  <br/>
<img src="https://i.imgur.com/MgsPGt3.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/JJ535gu.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
  Get Geolocation.io API Key:  <br/>
<img src="https://i.imgur.com/zaYu9Sp.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
Run Script To get Geo Data from attackers:  <br/>
<img src="https://i.imgur.com/lc0fcKM.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
Create custom log in LAW to bring in our custom log:  <br/>
<img src="https://i.imgur.com/br9P4QP.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/4DnxAyS.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/GA0oeWi.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/jw2Sbo3.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
Create custom fields/extract fields from raw custom log data:  <br/>
<img src="https://i.imgur.com/ZfV0E8O.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
Setup Azure Sentinel map with Latitude and Longitude:  <br/>
<img src="https://i.imgur.com/vCQo21h.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/qv2oLYC.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
Honeypot was successful! Attacks from Ukraine/Russia/France/UK:  <br/>
<img src="https://i.imgur.com/VIld59X.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
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
