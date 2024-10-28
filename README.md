<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com/watch?v=Olh1z-RNEhQ)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- XAMPP or WAMP: For an integrated web server, PHP, and MySQL.
- PHP: Version 7.2 or higher (included in XAMPP/WAMP).
- MySQL: Comes with XAMPP/WAMP.
- Composer: For managing PHP dependencies.
- Mail Server: For email functionality 

<h2>Installation Steps</h2>

<p>

![snapshot](https://github.com/user-attachments/assets/da8ba679-06cb-49a5-8a2d-f289cf5ab521)


>
<p> 
  
1. Download osTicket: Get the latest version from the osTicket website.
2. Extract Files: Unzip the downloaded file to your web server's document root.
3. Create Database: Open phpMyAdmin (via XAMPP/WAMP) and create a new database for osTicket.
</p>
<br />

<p>

![tthhrhrhr](https://github.com/user-attachments/assets/b7251a6c-9ef1-4c27-862f-f5e8affa6bb2)



<p>

4. Configure Settings: Rename include/ost-sampleconfig.php to include/ost-config.php and update database credentials in this file.
5. Set Permissions: Ensure the include and attachments folders are writable by your web server.
6. Access Installation Wizard: Open your web browser and navigate to http://localhost/osticket to start the installation.
</p>
<br />

<p>
![hyhhyhyyh](https://github.com/user-attachments/assets/c00b463c-4659-41e4-8435-862e73ff615d)

<p>

7. Follow Installation Steps: Fill in the required fields in the installation wizard, including database details and admin account information.
8. Complete Installation: After the setup, follow prompts to finalize the installation.
9. Remove Setup Files: Delete the setup/ directory for security reasons.
</p>
<br />
