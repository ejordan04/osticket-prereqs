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

- Install/Enable IIS
- Install Web platform installer
- Install C++ redistributable
- Install MySQL and set up username and password
- Configure Permissions and install osTicket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/Eg8S3ni.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Open the control panel by using the Windows search bar then click Programs/Turn Windows features on or off/Internet Information Services. Next, make sure IIS Management Console has a checkmark (Located under Web Management Tools). Finally, enable CGI and Common HTTP Features located under World Wide Web Services/Application Development Features. 
</p>
<br />

<p>
<img src="https://i.imgur.com/NtQTh5N.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/Xw9nUZD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now we need to install the Web platform installer along with other various files such as the PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi), Rewrite Module (rewrite_amd64_en-US.msi), and PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip).
</p>
<br />

<p>
<img src="https://i.imgur.com/Frg9Gbt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install Microsoft Visual C++ 2015-2022 Redistributable.
</p>
<br />

<p>
<img src="https://i.imgur.com/odVg0rF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  <p>
<img src="https://i.imgur.com/ShNxpr5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install and setup MySQL with Typical Setup and Standard Configuration then create a password. 
</p>
<br />

<p>
<img src="https://i.imgur.com/ZwfgomO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<p>
<img src="https://i.imgur.com/kbUsbIF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<p>
<img src="https://i.imgur.com/Z43bw9K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<p>
<img src="https://i.imgur.com/3RWdApe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Install osTicket and enable these extensions: php_imap.dll, php_intl.dll, and php_opcache.dll. Navigate to ost-config.php located in C:\inetpub\wwwroot\osTicket\include\ost-config.php. Configure its permissions to Everyone. After that, continue setting up osTicket in the browser. When finished click "Install Now!".
</p>
<br />
