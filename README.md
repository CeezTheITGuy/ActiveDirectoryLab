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
VirtualBox Installation: <br/>
<img src="https://i.imgur.com/e5GawOn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Server 2019 ISO Downloads:  <br/>
<img src="https://i.imgur.com/AAF3P6J.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Windows 10 ISO Downloads:  <br/>
<img src="https://i.imgur.com/PPgj5np.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating Internal NIC and Assigning IP:  <br/>
<img src="https://i.imgur.com/C2tQmav.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Installing DNS, DHCP, Remote Access and Active Directory:  <br/>
<img src="https://i.imgur.com/C1ZQ9fX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
DHCP Configuration:  <br/>
<img src="https://i.imgur.com/XhuSmD6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
PowerShell Script Execution:  <br/>
<img src="https://i.imgur.com/HdvnHVh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Client Virtual Machine Creation:  <br/>
<img src="https://i.imgur.com/vNq9YF9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Pinging the Domain from the Client:  <br/>
<img src="https://i.imgur.com/Y6vJnqJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
