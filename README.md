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

- Downloaded PHP Manager  for IIS
- Downloaded the Rewrite Module
- Downloaded PHP 7.3.8
- Downloaded VC_redist.x86
- Downloaded MySQL 5.5.62
- Downloaded Heidi SQL

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/6UB9URN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I installed OsTicket on a Windows 10 virtual machine I created in Microsoft Azure. I then enabled (php_imap.dll); (php_intl.dll); and (php_opcache.dll).
</p>
<br />

<p>
<img src="https://i.imgur.com/OVTL0af.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I then used HeidiSQL to create a session. Next, I created a database called osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/DNl3MXC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lastly, I finished creating the osTicket enviornment by connecting osTicket to the database I made in Heidi SQL.
</p>
<br />
