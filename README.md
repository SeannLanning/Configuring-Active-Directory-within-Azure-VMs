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

<h2>Configuration Steps</h2>

- Create virtual machines in Azure. One being used as the Domain Controller and the second VM to be used as the Client VM
- Ensure proper connectivity between both virtual machines by implementing them on the same virtual network in Azure (test by pinging the private IP address of the Domain Controller VM from Client VM)
- Install Active Directory Domain Services
- Configure admin and normal account users in Active Directory
- Join Client VM to created domain
- Setup Remote Desktop for non-administrative users
- Create numerous 'test' users to ensure directory is working properly


![image](https://github.com/SeannLanning/Configuring-Active-Directory-within-Azure-VMs/assets/70045086/c832abbd-a577-4639-af2f-6f402e55d1dc)

![image](https://github.com/SeannLanning/Configuring-Active-Directory-within-Azure-VMs/assets/70045086/a269d928-713e-42c3-9110-cedcab5af33b)

![image](https://github.com/SeannLanning/Configuring-Active-Directory-within-Azure-VMs/assets/70045086/1545511e-6e77-48c7-9623-37c6f4ff35a9)

![image](https://github.com/SeannLanning/Configuring-Active-Directory-within-Azure-VMs/assets/70045086/2947d07d-cce7-48bb-b14e-0cce4b7e5b34)
