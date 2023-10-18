<h1>Active Directory Home Lab</h1>


<h2>Description</h2>
In this lab, we are going to walk through how to create an Active directory home lab environment using Microsoft Azure Virtual machine. Configuring and running this lab on an Azure windows 10 virtual machine will help develop your understanding of how active directory and azure virtual machines work, using a virtual machine makes it easier to run through this a couple of times which is highly recommended to help you build yours without using or needing a walkthrough. Let me know if you have any questions or anything is unclear.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Azure VM</b>
- <b>Azure Virtual network</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Windows server 2019</b>

<h2>Program walk-through:</h2>

<p align="left">
Create a resource group on Azure: To do this, it's important to create and name the resource group for all the resource to be grouped in, for this demonstration we're using Rgroup-demo. <br/>
<img src="https://imgur.com/XAFCAx9.jpg" height="80%" width="80%" alt="Active Directory VM homelab"/>
<br />
<br />
 Virtual network steps 1: Setting up a virtual network is important for setting up the Active directory domain server for later, setting up this virtual network allows us to configure our ip address and subnet reservation which could be useful for endpoints or vms trying to connect to the AD-DS server. <br/>
<img src="https://imgur.com/kMxuPzO.png" height="80%" width="80%" alt="Active Directory VM homelab"/>
 
 Virtual network steps 2: Created the virtual network under the Rgroup-demo resource group and named the virtual network "AD-Vnet" <br/>
<img src="https://imgur.com/yHjlTcY.png" height="80%" width="80%" alt="Active Directory VM homelab"/>
 
 Virtual network steps 3: Configured the virtual network ip address to 172.16.0.0/16 and added a subnet configured with an ip address range of 172.16.0.0/24 <br/>
<img src="https://imgur.com/U45TxhE.png" height="80%" width="80%" alt="Active Directory VM homelab"/>
 
 Virtual network steps 4: Finalized and created the virtual network <br/>
<img src="https://imgur.com/DLcZoM0.png" height="80%" width="80%" alt="Active Directory VM homelab"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
