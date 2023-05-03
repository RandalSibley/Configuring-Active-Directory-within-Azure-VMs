<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.

In this video, I will be installing Active Directory. I will start by creating my resource groups in Azure.  I will create virtual network with two virtual machines. One VM as the domain controller (DC) on the Windows 2022 server, and the other VM as the client on Windows 10 pro. I will use remote desktop to connect with the VM and begin to install Active Directory.


In this next video I will join the Client-1 VM to the domain (randy.com).  Next in the Azure Portal, I will set Client-1’s DNS settings to the domain controllers private IP address. I will then Login to Client-1 with Remote Desktop as the original local admin, and join it to the domain. I will then create new organizational units and permit access for all users to Remote Desktop. Create a bunch of additional users by copying a pre-written script into PowerShell_ise, by logging in as an administrator.  Lastly, I will attempt to log into Client-1 with one of the new user accounts.


In this last video, I will complete this example by deleting all resource groups from the Azure virtual network environment.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/n2uKckw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this photo I am creating a virtual network with two virtual machines. One VM as the domain controller (DC) on the Windows 2022 server, and the other VM as the Client on Windows 10 pro.
</p>
<br />

<p>
<img src="https://i.imgur.com/Bq2wVab.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this photo I am setting Client-1’s DNS settings to the domain controllers private IP address. 
</p>
<br />

<p>
<img src="https://i.imgur.com/zFufgQ8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this photo I am deleting all resource groups from the Azure virtual network environment.
</p>
<br />
