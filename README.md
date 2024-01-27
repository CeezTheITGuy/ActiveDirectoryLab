<h1>Active Directory Home Lab</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
In this tutorial, I guided the process of establishing a comprehensive Active Directory lab on a personal computer using Oracle VirtualBox. Initially, I covered the installation of VirtualBox and acquiring ISO files for Windows 10 and Server 2019. The primary virtual machine, designated as the domain controller, was configured with two network adapters—one for internet access and the other for the VirtualBox private network. After installing Server 2019 and configuring IP addresses, I set up both DNS and Active Directory on the domain controller. Routing was then established to enable private network clients to access the internet through the domain controller. Following this, I configured DHCP on the domain controller to automate IP address assignments. A PowerShell script was executed to generate a thousand users in Active Directory. Another virtual machine, named "client1," was created and connected to the private VirtualBox network. Windows 10 was installed on this client machine, which was subsequently joined to the domain. The tutorial concluded with logging into the client machine using one of the domain accounts. Throughout the process, I applied skills in VirtualBox usage, Windows Server 2019 installation, DNS and Active Directory configuration, networking setup, and PowerShell scripting.
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
