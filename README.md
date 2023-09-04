
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Setup Azure Vrtual Machine with Windows 10 and Remote Desktop into it 
- Enable ISS for Windows
- Download and install PHP Manager for ISS (PHPManagerForIIS_V1.5.0.msi)
- Download and install the neccessary Rewrite Module (rewrite_amd64_en-US.msi) 
- Create a folder on the VM's C drive named "PHP" (C:\PHP)
- Download and unzip PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) into C:\PHP 
- Download and install VC_redist.x86.exe
- Download, install, and setup MySQL 5.5.62 (mysql-5.5.62-win32.msi)
- Item 9


<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/IgbrEn1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Using Microsoft Azure, create a VM running Windows 10 as an OS. Then use Remote Desktop to access the VM.
</p>
<br />

<p>
<img src="https://i.imgur.com/RuPQuTO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Within the VM, enable ISS with CGI and all Common HTTP Features.
</p>
<br />

<p>
<img src="https://i.imgur.com/hcQFl5N.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download and install PHP Manager for ISS
</p>
<br />

<p>
<img src="https://i.imgur.com/7ODsGuO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download and install the Rewrite Module 
</p>
<br />

<p>
  
<img src="https://i.imgur.com/FLd0ipI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a folder on the C drive named "PHP"
</p>
<br />

<p>
<img src="https://i.imgur.com/nyWgG61.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download and unzip PHP 7.3.8 into C:\PHP
</p>
<br />

<p>
<img src="https://i.imgur.com/GNK6mjC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download and install VC_redist.x86.exe
</p>
<br />

<p>
<img src="https://i.imgur.com/OdErKBP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download and install MySQL 5.5.62
</p>
<br />

<p>
<img src="https://i.imgur.com/cypfNOi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Setup MySQL: Select Typical Setup Type
</p>
<br />

<p>
<img src="https://i.imgur.com/nyWgG61.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next step here
</p>
<br />

<p>
<img src="https://i.imgur.com/nyWgG61.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next step here
</p>
<br />
