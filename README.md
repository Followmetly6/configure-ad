<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Installed and configure Active Directory Domain Services (promoted new domain)
- Setup file and folder shares and assigned permissions
- Used PowerShell to automate the creation of thousands of users

<h2>Deployment and Configuration Steps</h2>


<p>
- Set up resources in Azure; Create domain controller VM, Set domain controllers NIC privage IP address to be static, Create Client VM (Windows 10).
</p>
<br />

<p>
- Ensure Connectivity between client and domain controller with ping. 
</p>
<br />

<p>
- Install Active Directory.
</p>
<br />

<p>
- Create admin and normal user account in AD; Create an Organizational Unit, Create new employee, Add empoloyee to account admin.
</p>
<br />

<p>
- Create a bunch of additional users; Observed the new accounts, attempted logging in as new users. 
</p>
<br />
