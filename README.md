<p align="center">
<img src="https://1000logos.net/wp-content/uploads/2020/06/Microsoft-Azure-Logo-2017.png" height="50%" width="50%" alt="Microsoft Azure Logo"/>
</p>

<h1 align="center"> How to create a VPN (Virtual Private Network) <br>
  on a Virtual Machine</h1>
This tutorial outlines the implementation of a VPN, using Proton VPN, within an Azure Virtual Machine. VPN is a service that creates a secure and private internet connection through the use of an encrypted tunnel and a remote server. It helps keep data and information safe, by staying anonymous.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Protocol
- Proton VPN

<h2>Operating Systems Used</h2>

- Windows 10 Pro (VM)

<h2>Steps</h2>

<p>
Step 1: Create a Virtual Machine in Microsoft Azure Cloud.
</p>
<p>
<img src="https://i.ibb.co/C2PkQ1L/Screenshot-2024-03-24-171433.png" height="60%" width="60%" alt="Creating VM in Azure" border="0">
<br />

<p>
Step 2: Connect to the Virtual Machine using Remote Desktop Protocol with the Public IP Address assigned by Azure.
</p>
<p>
<img src="https://i.ibb.co/NyxyyW3/Screenshot-2024-03-24-171801.png" height="70%" width="70%" alt="Connecting to VM" border="0"></p>
<br />

<p>
Step 3: Within the VM, find out what the current Public IP Address and location is by going to 'WhatIsMyIPAddress.com'.
Results shown "172.210.49.154, Virginia"
</p>
<p>
<img src="https://i.ibb.co/5kMDTJC/Screenshot-2024-03-24-172119.png" height="70%" width="70%" alt="IP Address at WhatIsMyIPAddress.com" border="0"></p>
<br />

<p>
Step 4: Browse to Proton VPN website to create a free account and download the software.
</p>
<p>
<img src="https://i.ibb.co/gZdCgJ0/Screenshot-2024-03-24-173134.png" height="70%" width="70%" alt="Proton VPN download" border="0"></p>
<br />

<p>
Step 5: Click 'Quick Connect' (or any location of choice) to create a tunnel to a server in a different location.
</p>
<p>
<img src="https://i.ibb.co/XjXC0Rd/Screenshot-2024-03-24-173324.png" height="70%" width="70%" alt="Connect to VPN" border="0"></p>
<br />

<p>
Step 6: In my example, the VPN is connected to a server from the Netherlands.
</p>
<p>
<img src="https://i.ibb.co/L1sQPHG/Screenshot-2024-03-24-173620.png" height="70%" width="70%" alt="VPN example in the Netherlands" border="0"></p>
<br />

<p>
step 7: Browse to 'WhatIsMyIPAddress.com' again. It now shows that we are located in the Netherlands.
</p>
<p>
<img src="https://i.ibb.co/nQtGpVj/Screenshot-2024-03-24-173757.png" height="70%" width="70%" alt="Seeing IP address in Netherlands" border="0"></p>
<br />

<p>
Step 8: Browse to 'Google.com'. Here we can also see the text is in a different language (Frysk).
</p>
<p>
<img src="https://i.ibb.co/wS0HgZq/Screenshot-2024-03-24-174032.png" height="70%" width="70%" alt="Google example different language" border="0"></p>
<br />
