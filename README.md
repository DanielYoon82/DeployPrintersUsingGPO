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
First, to access the Printer Services, installation needs to occur. Adding, choosing the proper options, and installation has been executed.
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
<br /> 

- <b>Adding Printer on Server Manager</b> <br />
The Print Services is now availabe. The following is the step by step demonstration on how to add the printer in Server Manager. <br />
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

- <b>Sharing the Printer</b> <br/>
Next, is the step by step process of sharing the printer.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter12.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter13.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter14.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

Printer has been added successfully. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter15.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

- <b>Creating GPO and Assigning Access</b> <br/>
Next is a demonstration on integrating GPO to assign an OU.  <br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter17.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter19.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter20.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter21.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter22.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

- <b>Confirming Printer Deployment</b> <br/>
Finally, confirmation using RDP that user has access to the printer. The user is accessed remotely using the proper credentials.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter23.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/DeployPrintersUsingGPO/blob/main/image/Deployprinter24.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

- <b>Summary</b> <br />
I demonstrated deploying a printer with modeling a VM in creating printer access, assigning GPO, and confirming using RDP that user has access to the printer. 
<br />
<br />
