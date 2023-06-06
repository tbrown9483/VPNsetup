<p align="center">
<img src="https://www.howtogeek.com/wp-content/uploads/2022/11/ProtonVPN-logo-on-a-white-background.jpg?height=200p&trim=2,2,2,2" height="80%" width="80%" alt="ProtonVPN logo"/>
</p>

<h1>Proton VPN: How to Deploy a Virtual Private Network</h1>
This tutorial outlines the steps necessary to deploy and monitor a virtual private network through utilization of Microsoft Azure.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Proton VPN service
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 11</b> 

<img src="https://i.imgur.com/xGyF9PR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
First step is, from your host computer, browser www.whatismyipaddress.com and note the local host IP
</p>
<img src="https://i.imgur.com/GUFTAPh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/XfxDs1i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/jjVwthM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now create and deploy a virtual machine in Microsoft Azure in a different region of the world. When deploying the VM make sure to take note of the username and password assigned to the machine. Once operational browse to www.whatismyipaddress.com and take note of it's(from here on out known as "VM1") IP address.
</p>
<br />

<p>
<img src="https://i.imgur.com/jTpYdNE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/4osXwQc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now you will, from the host PC, sign in or sign up for Proton VPN. From VM1 you will enter your login credentials for Proton and download the client application. Once the app is running, you will select another foreign region to browse the internet from.
</p>
<br />

<p>
<img src="https://i.imgur.com/PcYnpb1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once the VM has displayed that is in fact browsing in a different location, be sure to go back into your Resource Group on Azure and delete them to avoid incurring more cost.
</p>
<br />
