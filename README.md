# Azure Sentinel (SIEM) Lab

<h2>Description</h2>
Project consists of setting up Azure Sentinel (SIEM) and connecting it to a live virtual machine acting as a honey pot. I will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to look up the attackers Geolocation information and plot it on the Azure Sentinel Map
<br />


<h2>Languages and Utilities Used</h2>

- <b>?</b>
- <b>?</b> 

<h2>Environments Used </h2>

- <b>?</b>

<h2>Program walk-through:</h2>

<p align="center">
Download VirtualBox: <br/>
<img src="https://i.imgur.com/1wDBSFK.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
<br />
Download Windows 10:  <br/>
<img src="https://i.imgur.com/cjeEatE.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
<br />
Create Our Virtual Machines: <br/>
<img src="https://i.imgur.com/kM6dSo7.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/KLTudBx.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/FPVMWwU.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
<br />
Rename Ethernet:  <br/>
<img src="https://i.imgur.com/ZFhr4hc.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/FBo87Nd.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
<br />
Set Up IP addressing:  <br/>
<img src="https://i.imgur.com/Edqk2T8.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
<br />
Rename the PC:  <br/>
<img src="https://i.imgur.com/5p8YYib.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
<br />
Install Active Directory Domain Services:  <br/>
<img src="https://i.imgur.com/IpYnW5e.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/aapgL14.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
<br />
Post Deployment Configuration:  <br/>
<img src="https://i.imgur.com/7sjsBRo.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/HGDNZca.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
Create Our own dedicated Domain:  <br/>
<img src="https://i.imgur.com/qsf7p1c.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
Create an Organizational Unit:  <br/>
<img src="https://i.imgur.com/SZKKkf2.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
  Create a New User:  <br/>
<img src="https://i.imgur.com/JWsHShj.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
Make a Domain Admin:  <br/>
<img src="https://i.imgur.com/8rjuEkm.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/JFQJECE.jpeg" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
Routing and Remote Access:  <br/>
<img src="https://i.imgur.com/W0zCqKM.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/373Fl1t.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
Install NAT:  <br/>
<img src="https://i.imgur.com/X5hZl4h.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/7vItjcg.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/isib70F.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
Set Up a Dhcp Server on our Domain:  <br/>
<img src="https://i.imgur.com/QMvHO1V.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/m09ARAH.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
DHCP Scope:  <br/>
<img src="https://i.imgur.com/C8zhxTe.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
Configure DHCP Options:  <br/>
<img src="https://i.imgur.com/dDdUmEf.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
Add an IP address for a Router:  <br/>
<img src="https://i.imgur.com/zBAF3JF.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
Source Code for the Powershell Script:  <br/>
<img src="https://i.imgur.com/RUqLiNy.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/cfQQKqW.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/1dIsqv2.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
Setting up Windows 10 VM in Virtualbox:  <br/>
<img src="https://i.imgur.com/QBsDfve.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <img src="https://i.imgur.com/xzmDzfk.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
Create a New VM:  <br/>
<img src="https://i.imgur.com/ELelgrO.png" height="80%" width="80%" alt="Active Directory Steps"/>
  <br />
<br />
Add the Domain Controller:  <br/>
<img src="https://i.imgur.com/C8gKyS0.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
<br />
Address Leases + Showing that CLIENT1 is connected to DNS:  <br/>
<img src="https://i.imgur.com/2Son4E1.png" height="80%" width="80%" alt="Active Directory Steps"/>
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
