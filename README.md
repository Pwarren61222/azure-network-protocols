<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Create Vitual Machine 1 usuing windows
- Create Virtual Machine 2 using Ubuntu
- Open Remote Deskstop and login using public IP address
- Open Wireshark and Powershell

<h2>Actions and Observations</h2>

<p>
<img src="https://imgur.com/Q0d6gdy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Observed ICMP(Internet Control Messaging Protocal)." Protocal that ping uses, which is used to test connectivity between networks."
</p>
<br />

<p>
<img src="https://imgur.com/xgJTqtL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Observed DHCP traffic(Dynamic host configuration protocal)." Used to automatically assign IP address."
</p>
<br />

<p>
<img src="https://imgur.com/X2ltqGi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Observed SSH traffic(Secure Shell). "very simialr to remote desktop except you get access to the command line."
</p>
<br />
