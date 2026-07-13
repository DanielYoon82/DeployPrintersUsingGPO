<h1>Home Lab - Deploying Printer Using Group Policy (GPO) in Active Directory</h1>

<h2>Description</h2>
In this virtual machine I demonstrate deploying a printer and assigning an OU using GPO. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Windows 10</b> 

<h2>Environments Used </h2>

- <b>Windows Server 2019</b>

<h2>Program walk-through:</h2>


- <b>Creating Print Services on Server Manager</b> <br />
First, to access the Printer Services, installation needs to occur. Adding, choosing the proper options, and installing has been done.
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinteradd1.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br /> 
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinteradd2.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinteradd3.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>

- <b>Adding Printer on Server Manager</b> <br />
The Printer Services is now availabe. The following is the step by step demonstration on how to add the printer in Server Manager. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter1.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter2.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter3.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter4.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter5.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter6.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter7.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter8.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter9.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter10.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter11.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter6.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />
</p>

- <b>Congifuring Group Membership</b> <br/>
The head of the Marketing Department requested to add the new hire added to their group. I right-click on the new user and choose properties.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser4.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

The "Member Of" tab was chosen then a group added. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser5.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

"Check Names" option was chosen for marketing to verify the group was correct completing group configuration.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser6.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

- <b>Deleting and Disabling User Accounts</b> <br/>
HR has notified me that one employee will no longer will be with the company and another will be taking a temporary leave. I am tasked with deleting and disabling their accounts. First, I will delete Robert's account to take effect immediately. I right-click on the user and choose delete.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser7.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

For the user that will be taking a temporary leave, I right-click and choose disable. Upon the employee's return, I will enable the user to restore accessibility. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser8.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

- <b>Unlocking Account and Resetting Password</b> <br/>
An employee called and stated that her account has been locked out due to multuple log in attempts and forgetting her password. A request was made to also reset the password. I first right-click on users and find the name.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser9.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

I navigate to the account tab and choose the box "Unlock Account" and click apply successfully unlocking the account. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser10.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

I then proceed with right-clicking the user and choose the reset password option. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser11.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

Password has been chosen and the user has been notified to change the password at next logon achieving user resolution. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser12.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

- <b>Summary</b> <br />
I demonstrated using Windows Active Directory with modeling a VM in creating, configuring, deleting, and disabling user accounts. In addition, unlocking and resetting a password was carried out using real-world scenarios. These common tasks are vital to user management protocol and done offhand frequently. 
<br />
<br />
