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
- Windows 11 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Setup Domain Controller in Azure
  - Create a Resourse Group, Virtual Network and Subnet
  - Create a Domain Controller Virtual Machine
  - Create a Client Virtual Machine (Make sure to assign to the same region as the Domain Controller) 
  - Set NIC private IP Address of the Domain Controller to Static
  - Set DNS Server of the Client to the private IP Address of the Domain Controller
- Step 4

<h2>Deployment and Configuration Steps</h2>


<p>
Create a Resourse Group, Virtual Network and Subnet
</p>
<br />


![4-1a](https://github.com/user-attachments/assets/d1086edd-4957-4def-8ab3-9710f653a009)
![4-1](https://github.com/user-attachments/assets/449425f9-4e98-48f5-8cc0-fc1778b4bb81)


<p>
Create a Domain Controller Virtual Machine with the Winders Server 2022 operating system.
</p>
<br />


![4-1b](https://github.com/user-attachments/assets/3db79072-1976-4b01-bbde-e65b9f0a2db2)


<p>
Create a Client Virtual Machine (Make sure to assign to the same region as the Domain Controller)
</p>
<br />


![4-1c](https://github.com/user-attachments/assets/dfa28b68-a930-4acf-a5c1-b5c840d1bef8)


<p>
Set NIC private IP Address of the Domain Controller to Static. This ensure the private IP address never changes. 
</p>
<br />


![4-2](https://github.com/user-attachments/assets/5ec259b3-892e-49b7-8394-ded6a4c86d23)

<p>
Set DNS Server of the Client to the private IP Address of the Domain Controller
</p>
<br />


<p>
Sample line
</p>
<br />


<p>
Sample line
</p>
<br />


<p>
Sample line
</p>
<br />


<p>
Sample line
</p>
<br />


<p>
Sample line
</p>
<br />
