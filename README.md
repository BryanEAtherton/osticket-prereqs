
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

- Setup and access Azure Vrtual Machine with Windows 10 OS
- Enable ISS for Windows
- Download and install:
  - PHP Manager for ISS (PHPManagerForIIS_V1.5.0.msi)
  - Rewrite Module (rewrite_amd64_en-US.msi)
  - PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) into C:\PHP 
  - VC_redist.x86.exe
- Download, install, and setup MySQL 5.5.62 (mysql-5.5.62-win32.msi)
- Register PHP withhin IIS
- Item 10


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
Download and unzip/extract PHP 7.3.8 into C:\PHP
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
<img src="https://i.imgur.com/OdErKBP.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/cypfNOi.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download and install MySQL 5.5.62 and selelct Typical Setup Type
</p>
<br />

<p>
<img src="https://i.imgur.com/2c8eQZ6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Setup MySQL
</p>
<br />

<p>
<img src="https://i.imgur.com/G8gSdDI.png" height="40%" width="30%" alt="Disk Sanitization Steps"/> 
<img src="https://i.imgur.com/K5FDi0c.png" height="40%" width="30%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/CgadVOQ.png" height="40%" width="30%" alt="Disk Sanitization Steps"/>
</p>
<p>
Setup MySQL: Standard Configuration, Install as a Windows Service, Create and Confirm a Password
</p>
<br />

<p>
<img src="https://i.imgur.com/hpdttum.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/sxSbYCx.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open IIS as an administrator, Register PHP using C:\PHP\php-cgi.exe, Restart IIS
</p>
<br />

<p>
<img src="https://i.imgur.com/GPqbP8o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download osTicket, Copy/extract the upload folder into C:\inetpub\wwwroot
</p>
<br />

<p>
<img src="https://i.imgur.com/gmphOsR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From the wwwroot folder, rename "upload" to "osTicket"
</p>
<br />

<p>
<img src="https://i.imgur.com/Ha8UZZR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open IIS, navigate to "osTicket" folder under Connections, select "Browse *:80 (http)" under Manage Folder
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

<p>
<img src="https://i.imgur.com/nyWgG61.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next step here
</p>
<br />
