<p align="center">
<img src="https://i.imgur.com/BVY0tP3.png" alt="Microsoft Azure logo"/>
</p>

<h1>Azure - Compute and Networking</h1>
This tutorial outlines the steps on how to create resource groups with Microsoft Azure using windows and Linux (Ubuntu), at the same time a Virtual Network and Subnet will be created as well.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: Create Azure Resource Group using windows](https://www.youtube.com/watch?v=M0o89nmoRH0)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Azure Subscription
- Remote Desktop Connection

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Creating Resource group Stages</h2>

- Create resource group
- Create virtual network/subnet
- Create two VM1(windows) and VM2(Linux)

<h2>Steps</h2>

<p>
<img src="https://i.imgur.com/6m7uODN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a Resource Group.
Create a Windows 10 Virtual Machine.
Create a Linux (Ubuntu).
</p>
<br />

<p>
<img src="https://i.imgur.com/c5dDMFF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Use Remote Desktop to connect to your Windows 10 Virtual Machine.
Open Wireshark and filter for ICMP traffic only.
From The Windows 10 VM, open command line or PowerShell and attempt to ping a public website (such as www.google.com) and observe the traffic in WireShark.
</p>
<br />

<p>
<img src="https://i.imgur.com/e9nMyIh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Back in Wireshark, filter for SSH traffic only.
From your Windows 10 VM, “SSH into” your Ubuntu Virtual Machine (via its private IP address).
Type commands (username, pwd, etc) into the linux SSH connection and observe SSH traffic spam in WireShark.
</p>
<br />
