<p align="center">
<img src="https://imgur.com/bWA2WCL.png" alt="Nessus Logo"/>
</p>

<h1>Nessus Vulnerability Management Tutorial</h1>
This tutorial outlines the use and implementation of Nessus.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Nessus Essentials Activation Code
- Deprecated Version of Firefox

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Setting up our resources in Azure.
- Downloading and installing Nessus Essentials.
- Ensuring connectivity with the VM.
- Creating, configuring, and inspecting noncredentialed scans.
- Creating, configuring and inspecting credentialed scans.
- Installing a deprecated Firefox version.
- Remediating sample vulnerabilities.

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, set up your RG and VM in Azure. Use a Windows 10 VM. You'll only need one for this tutorial, so feel free to use whichever vcpu count you want.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we'll need to get an activation key for, and download and install Nessus Essentials on your physical computer. Click through all prompts and follow the activation and installation steps. Use <a href="https://www.tenable.com/products/nessus/nessus-essentials">this link</a> to navigate to get your activation code. This will take some time in the final stages of installation.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now, we'll use Remote Desktop to access the VM. Click through all of the initial setup prompts.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you're in, open the Command Prompt on both the VM and your physical computer. Get the IPv4 address from your VM and ping it using your physical computers Command Prompt. Notice that it times out. Go to wf.msc on the VM, click on Defender Firewall Properties, and disable the first three tabs. Ping the VM again, and notice that it goes through.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
