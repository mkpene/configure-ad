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

- Setup Resources in Azure
- Ensure Connectivity between the client and Domain Controller
- Install Active Directory
- Create an Admin and Normal User Account in AD
- Setup Remote Desktop for non-administrative users on Client-1
- Create a bunch of additional users and attempt to log into client-1 with one of the users

<h2>Deployment and Configuration Steps</h2>


![image](https://github.com/mkpene/configure-ad/assets/142267681/149eea87-97ef-437a-881e-9ee5015a66ff)

<p>
I logged into the Azure portal and navigated to the "Virtual Machines" section. I initiated the creation of two virtual machines, one for the domain controller and another for the client. I selected the appropriate operating systems, configurations, and resource specifications for each machine.
</p>
<br />


![image](https://github.com/mkpene/configure-ad/assets/142267681/1c6ec953-0e58-4b53-ab7e-8317df4cfde0)

<p>
I started with the domain controller virtual machine. After its deployment, I accessed it through Remote Desktop. Then, I proceeded to install the Active Directory Domain Services role using the Server Manager. This initiated the promotion of the machine to a domain controller. Within the Active Directory Users and Computers console on the domain controller, I created user accounts and security groups, mirroring the network users I wanted to simulate.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
