<h1>Active Directory Home Lab</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
In this tutorial, I established a domain controller featuring Active Directory, equipped with two network adapters—one for external internet access and the other for an internal network. Ensured clarity by adjusting default IPs. Assigned internal network IP addresses while allowing the external network to obtain IPs automatically from the home network. Installed Active Directory, created a domain, and established an admin user for management. Configured RAS and NAT to facilitate internet access for the internal network. Implemented DHCP on the server for automated IP assignments, executed a PowerShell script to generate users in Active Directory, and successfully created and connected a client VM to the domain. Checked and verified IP settings, internet connectivity, and user login for a comprehensive evaluation. Skillfully managed tasks such as adapter configuration, IP adjustments, Active Directory setup, RAS and NAT configuration, DHCP implementation, and PowerShell scripting.
<br />


<h2>Applications and Enviornments Used</h2>

- <b>Oracle VirtualBox</b> 
- <b>Windows 10</b>
- <b>Windows Server 2019</b> 
- <b>PowerShell</b>

<h2>Program walk-through:</h2>

<p align="center">
Domain Controller Creation: <br/>
<img src="https://i.imgur.com/MugCxS4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Differentiation between Internal and External Internets:  <br/>
<img src="https://i.imgur.com/eJHxZO0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
IP Assignment:  <br/>
<img src="https://i.imgur.com/3YlIchJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Active Directory Installation:  <br/>
<img src="https://i.imgur.com/UhwJgHS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Domain Creation:  <br/>
<img src="https://i.imgur.com/V2dFqWa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Admin User Created:  <br/>
<img src="https://i.imgur.com/pEJMUIU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
RAS Installation:  <br/>
<img src="https://i.imgur.com/QVSxrxw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
NAT Configuration:  <br/>
<img src="https://i.imgur.com/nxE3wjy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
DHCP Installation:  <br/>
<img src="https://i.imgur.com/WcT0vCz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
IP Address Range:  <br/>
<img src="https://i.imgur.com/xzfhOTl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Scope Creation:  <br/>
<img src="https://i.imgur.com/CvufFLg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Powershell Script for Fake Users:  <br/>
<img src="https://i.imgur.com/9N82vIM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Client VM Created and Named:  <br/>
<img src="https://i.imgur.com/zigGe8Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
IP Config Test:  <br/>
<img src="https://i.imgur.com/QoaEuya.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Internet Connection Test:  <br/>
<img src="https://i.imgur.com/DW9w1IW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Lease Given to Client:  <br/>
<img src="https://i.imgur.com/39991Yc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Client Joins Domain:  <br/>
<img src="https://i.imgur.com/Nd0fnwk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Logging in with Created User:  <br/>
<img src="https://i.imgur.com/bhzfZZc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/61mdT4b.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
