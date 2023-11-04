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

- Create Domain Controller VM and Client VM in Azure
- Use same resource group for both VMs
- Ensure both VMs are in same Vnet
- Ensure connectivity between Client VM and Domain Controller VM
- Install Active Directory
- Create an Admin and Normal User account in AD
- Join Client VM to your domain
- Setup Remote Desktop for non-admin users on Client VM
- Create additional users and attempt to login to Client VM with one of the users


<h2>Deployment and Configuration Steps</h2>

1. Create Domain Controller VM and Client VM in Azure

  <img src="https://i.imgur.com/SUPxbo7.png" height="80%" width="80%" alt="Installation Steps"/>


2. Use same resource group for both VMs


3. Ensure both VMs are in the same Vnet


4. Install Active Directory

   
<img src="https://i.imgur.com/q0Aei7i.png" height="80%" width="80%" alt="Installation Steps"/>


5. Create an Admin and Normal User account in AD

  <img src="https://i.imgur.com/Wf0HKHa.png" height="80%" width="80%" alt="Installation Steps"/>


6. Join Client VM to your domain

  <img src="https://i.imgur.com/v9YqtBy.png" height="80%" width="80%" alt="Installation Steps"/>


7. Setup Remote Desktop for non-admin users on Client VM


8. Create additional users and attempt to login to Client VM with one of the users

   <img src="https://i.imgur.com/dIVP8DM.png" height="80%" width="80%" alt="Installation Steps"/>

