<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Active Directory Deployed in the Cloud (Azure)</h1>
Using MS Azure to create Active Directory Infrastructure<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Configure VM's in MS Azure
- Ping VM1 and VM2 After Configuration From Azure
- Enable Active Directory W/ Configs
- Creating Users Then Testing Users

<h2>Deployment and Configuration Steps</h2>

<p>
</p>Step 1. 
<img src="https://i.imgur.com/A7IOE19.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Setup both VM's to make sure static IP option is selected so private IP does not change
</p>
<br />

<p>
<img src="https://i.imgur.com/oOUDJck.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
DNS Settings Setup
</p>
<br />

<p>
</p>Step 2.
<img src="https://i.imgur.com/2nBiijw.png" height="45%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/ErgzJwe.png" height="45%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
From VM1, pinging VM2 Private IP address to show the DNS is set to VM2's private IP. VM1's private IP is 10.0.0.4, VM2's is 10.0.0.5. As you can see after ipconfig /all, the hostname is VM1 but DNS is 10.0.0.5
</p>
<br />
