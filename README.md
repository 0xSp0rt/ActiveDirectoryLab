<h1>Active Directory Home Lab</h1>


<h2>Description</h2>
In this lab, we are going to walk through how to create an Active directory home lab environment using Microsoft Azure Virtual machine. Configuring and running this lab on an Azure windows 10 virtual machine will help develop your understanding of how active directory and azure virtual machines work, using a virtual machine makes it easier to run through this a couple of times which is highly recommended to help you build yours without using or needing a walkthrough. Let me know if you have any questions or anything is unclear.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Azure VM</b>
- <b>Azure Vnet</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Windows server 2019</b>

<h2>Program walk-through:</h2>

<p align="left">
Create a resource virtual network on Azure: To do this, it's important to create a resource group for all the resource to be grouped in. <br/>
<img src="https://imgur.com/XAFCAx9" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
