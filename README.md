# azure-network-protocols
<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Create 2 wirtual machine
- Login to Remote Desktop with IPaddress
- Download Wireshark in remote desktop
- Setup VM2 then start Pinging IP in Powershell and read result in wireshark
- Ping several Command in wireshark to see the result

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/XU2re1z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create Ressource Groups and Virtual Machines which all the setups are in the first link, for this Lab we will get IPaddress the Virtual Machine 1 and remot it (remote desktop; just reseach on the windows search bar then login with a Virtual Machine when you were creating the account) login to desktop with virtual loging we will download wireshark and read the traffic.
</p>
<br />

<p>
<img src="https://i.imgur.com/JRMLKhu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After downloaded wireshark, we can read the Ethernet traffic as we can see in the post.
</p>
<br />

<p>
<img src="https://i.imgur.com/w7roGlU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this post we can see, we filter our connection wireshark on ICMP (internet control messaging protocol) this is the information pinged and show the connection traffic between both machine. and the icmp result shows with the IP are the same on the windows powershell. actually it gives message on all the traffic address we are searching or pinging on the windows powershell copmmand (just to know if you want to ping IP's with not stop chechking just add -t at the end)
</p>
<br />

<p>
<img src="https://i.imgur.com/FFnzi2j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this post we filter our connection wireshark on SSH (Secure Shell) to connect to another computer on the powershell we tap the command follow the username and IPaddress process with yes and password than you are connect that computer and you can read as well on the wireshark that the ssh traffic will start coming through.
</p>
<br />

<p>
<img src="https://i.imgur.com/VBrgRTS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DPGlLNz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/qQWz585.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/IDFiMPj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/XaSZZcM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
