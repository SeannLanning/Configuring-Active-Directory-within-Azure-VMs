<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
Outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>Configuration Steps</h2>

- Create virtual machines in Azure. One being used as the Domain Controller and the second VM to be used as the Client VM
- Ensure proper connectivity between both virtual machines by implementing them on the same virtual network in Azure (test by pinging the private IP address of the Domain Controller VM from Client VM)
- Install Active Directory Domain Services
- Configure admin and normal account users in Active Directory
- Join Client VM to created domain
- Setup Remote Desktop for non-administrative users
- Create numerous 'test' users to ensure directory is working properly

