<p align="center">
<img src="https://i.imgur.com/AsXa2kY.jpeg" alt="Proton VPN"/>
</p>

<h1>VPN Setup and Usage (Proton VPN) </h1>
In this tutorial, we install and setup a free, open-source VPN (Proton VPN). <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Proton VPN


<h2>Operating Systems Used </h2>

- Windows 10 (21H2)


<h2>High-Level Steps</h2>

- Check Home/Office IP Address Using whatismyipaddress.com
- Create a Virtual Machine inside Microsoft Azure
- Remote Desktop into the Azure VM. Re-check IP Address
- Download & Signup for Proton VPN
- Connect to the VPN and check IP Address

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/6RvDoR1.png" height="80%" width="80%" alt="Initial IP Address Check"/>
</p>
<p>
Check your initial IP Address (wherever you start the lab) using whatismyipaddress.com and record it. We will compare this to the address in your Azure VM, as well as the address once we are connected to the VPN. 
</p>
<br />

<p>
<img src="https://i.imgur.com/1lgZFDn.png" height="80%" width="80%" alt="Creating Azure VM"/>
</p>
<p>
Create your Virtual Machine in Microsoft Azure. The full process of creating a VM is shown in this lab (--------). It is from inside this Virtual Machine that we will download and connect to Proton VPN.
</p>
<br />

<p>
<img src="https://i.imgur.com/PDNiJJA.png" height="80%" width="80%" alt="Remote Desktop into Azure VM"/>
</p>
<p>
Open Remote Desktop Connection (On Windows), or ---- if using a Mac. Copy and paste the public IP Address of your Azure VM to connect to it. Then, enter the login information you chose when creating your VM. Once you do this, check your IP address once again, noticing that it is different from your home address. 
</p>
<br />

<p>
<img src="https://i.imgur.com/aO0BJqN.png" height="80%" width="80%" alt="Download and Singup for Proton VPN"/>
</p>
<p>
Google "Proton VPN" and download it within your VM. Create an account. 
</p>
<br />

<p>
<img src="https://i.imgur.com/sTahwVX.png" height="80%" width="80%" alt="Connect to the VPN and Check IP Address"/>
</p>
<p>
Once signed up for Proton VPN, choose a destination country's server to connect to. Once connected, check your IP address for the last time, comparing it to the other two. The Azure VM that you created has a different IP address than your home address. Once you connect to the VPN, your VM's IP address changes. 
<br />
