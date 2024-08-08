<h1>Active-Directory-Lab</h1>
<h2>Description</h2>
This fun and straightforward home lab setup uses VirtualBox to create a virtual network environment featuring Windows Server 2019 and Windows 10. The lab focuses on Active Directory Domain Services (AD DS) setup, including configuring NAT for internet access, a single DHCP scope for IP management, and leveraging PowerShell for creating 1000 users. It's a hands-on project to learn and practice AD concepts in a controlled, home-based environment.

(Currently being worked on, full instructions can be found on the PDF file given in this Repository)
<br />


<h2>Languages Used</h2>

- <b>PowerShell</b>

<h2>Environments Used</h2>

- <b>VirtualBox</b>
- <b>Windows Server 2019</b>
- <b>Windows 10</b>

<h2>What is Used</h2>

- <b>AD DS - Active Directory Domain Services</b>
- <b>NAT - Network Address Translation</b>
- <b>DHCP</b>

<h2>1. The Main Setup of the Active Directory Infrastructure</h2>

<p align="center">
1. The Main Setup: <br/>
<img src="/Images/1.Setup.PNG" height="80%" width="80%"/>
<br />
<br />
</p>

<h2>2. Setting up the Virtual Machines in VirtualBox</h2>

<p align="center">
2.1. Setting up the Virtual Machines: <br/>
<img src="/Images/2.1. Setting up the Virtual Machines.PNG" height="80%" width="80%"/>
<br />
<br />
2.2. Focusing on the Initial Network Setups: <br/>
<img src="/Images/2.2. Focus on Initial Network Setups.PNG" height="80%" width="80%"/>
<br />
<br />
2.3. NAT Network for DC: <br/>
<img src="/Images/2.3. NAT Network for DC.PNG" height="80%" width="80%"/>
<br />
<br />
2.4. Internal Network for DC: <br/>
<img src="/Images/2.4. Internal Network for DC.PNG" height="80%" width="80%"/>
<br />
<br />
2.5. Internal Network for Client1 Machine: <br/>
<img src="/Images/2.5. Internal Network for Client1 Machine.PNG" height="80%" width="80%"/>
<br />
<br />
2.6 NAT Network Connecting to Home Router: <br/>
<img src="/Images/2.6 NAT Network Connecting to Home Router.PNG" height="80%" width="80%"/>
<br />
<br />
2.7 Autoconfig IPv4 Address Internal Network: <br/>
<img src="/Images/2.7 Autoconfig IPv4 Address Internal Network.PNG" height="80%" width="80%"/>
<br />
<br />
2.8 Setting up an IP Address, Subnet Mask and DNS Server Address for Internal Network: <br/>
<img src="/Images/2.8 Setting up an IP Address, Subnet Mask and DNS Server Address for Internal Network.PNG" height="80%" width="80%"/>
<br />
<br />
</p>

<h2>3. Setting Up the Active Directory Domain Services</h2>

<p align="center">
3.1. Setting Up Active Directory Users and Computers with ADMINS Organisational Unit and an Admin User: <br/>
<img src="/Images/3.1. Setting Up Active Directory Users and Computers with ADMINS Organisational Unit and an Admin User.PNG" height="80%" width="80%"/>
<br />
<br />
3.2. Admin Works: <br/>
<img src="/Images/3.2. Admin Works.PNG" height="80%" width="80%"/>
<br />
<br />
</p>

<h2>4. Setting up the DHCP and Network Connections</h2>

<p align="center">
4. Setting up NAT: <br/>
<img src="/Images/4. Setting up NAT.PNG" height="80%" width="80%"/>
<br />
<br />
4.1 NAT Internet Connection Set Up: <br/>
<img src="/Images/4.1 NAT Internet Connection Set Up.PNG" height="80%" width="80%"/>
<br />
<br />
4.2 DHCP Setup with IP Address Range: <br/>
<img src="/Images/4.2 DHCP Setup with IP Address Range.PNG" height="80%" width="80%"/>
<br />
<br />
4.3 DHCP Lease Duration: <br/>
<img src="/Images/4.3 DHCP Lease Duration.PNG" height="80%" width="80%"/>
<br />
<br />
4.4 DHCP Default Gateway: <br/>
<img src="/Images/4.4 DHCP Default Gateway.PNG" height="80%" width="80%"/>
<br />
<br />
4.5 DHCP Domain Name and DNS: <br/>
<img src="/Images/4.5 DHCP Domain Name and DNS.PNG" height="80%" width="80%"/>
<br />
<br />
4.6 Internal Network is now Setup: <br/>
<img src="/Images/4.6 Internal Network is now Setup.PNG" height="80%" width="80%"/>
<br />
<br />
</p>

<h2>5. PowerShell and User Creations</h2>

<p align="center">
5. Powershell and Dummy User Setup: <br/>
<img src="/Images/5. Powershell and Dummy User Setup.PNG" height="80%" width="80%"/>
<br />
<br />
5.1 Downloaded Folder with txt file with 1000 users: <br/>
<img src="/Images/5.1 Downloaded Folder with txt file with 1000 users.PNG" height="80%" width="80%"/>
<br />
<br />
5.2 Opening (Admin) with Windows PowerShell ISE: <br/>
<img src="/Images/5.2 Opening (Admin) with Windows PowerShell ISE.PNG" height="80%" width="80%"/>
<br />
<br />
5.3. Open PowerShell Script, Navigate to Folder and Running Script: <br/>
<img src="/Images/5.3. Open PowerShell Script, Navigate to Folder and Running Script.PNG" height="80%" width="80%"/>
<br />
<br />
5.4. Script Ran and Successfully Made Users: <br/>
<img src="/Images/5.4. Script Ran and Successfully Made Users.PNG" height="80%" width="80%"/>
<br />
<br />
</p>

<h2>6. Client Machine Connecting to Domain</h2>

<p align="center">
6. Focus on Client Machine: <br/>
<img src="/Images/6. Focus on Client Machine.PNG" height="80%" width="80%"/>
<br />
<br />
6.1 Sucessfully Tested Client1 working off Internal Network and Gaining Internet Access: <br/>
<img src="/Images/6.1 Sucessfully Tested Client1 working off Internal Network and Gaining Internet Access.PNG" height="80%" width="80%"/>
<br />
<br />
6.2 Connecting to Domain: <br/>
<img src="/Images/6.2 Connecting to Domain.PNG" height="80%" width="80%"/>
<br />
<br />
6.3 Successfully connected to Domain: <br/>
<img src="/Images/6.3 Successfully connected to Domain.PNG" height="80%" width="80%"/>
<br />
<br />
</p>

<h2>7. Final Checks</h2>

<p align="center">
7.1 Proof of Lease: <br/>
<img src="/Images/7.1 Proof of Lease.PNG" height="80%" width="80%"/>
<br />
<br />
7.2 Proof of Computer: <br/>
<img src="/Images/7.2 Proof of Computer.PNG" height="80%" width="80%"/>
<br />
<br />
7.3 Proof of Client Machine connected to Domain: <br/>
<img src="/Images/7.3 Proof of Client Machine connected to Domain.PNG" height="80%" width="80%"/>
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
