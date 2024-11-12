<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com/watch?v=8bkXbgbJEGk&t=179s)
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
<h3>Step 1: Download osTicket</h3>

1. Get the latest version from the osTicket website.
  
![snapshot](https://github.com/user-attachments/assets/da8ba679-06cb-49a5-8a2d-f289cf5ab521)

>
<p> 
<br />
<br />
<p>
<h3>Step 2: Unzip the osTicket File</h3>

1. Right-click the downloaded .zip file (example -> osTicket-vX.X.X.zip).</p>
2. Select Extract All and choose a destination folder (example -> C:\osticket).</p>
   
  
![step 2 image](https://github.com/user-attachments/assets/97f1a53f-809c-401c-b52b-92044fc21670)


>
<p> 
<br />
<br /> 
<p>
<h3>Step 3: Install XAMPP (Local Server)</h3>

1. Download and install XAMPP from XAMPP's offical website.</p>
2. During installation, select Apache and MySQL for the services.</p>
3. Once installed, open the XAMPP Control Panel and start both Apache and MySQL.</p>

![step 3 image](https://github.com/user-attachments/assets/7d3b87f6-9eb0-4b74-9676-f43da7c738af)

>
<p> 
<br />
<br /> 
<p>
<h3>Step 4: Move osTicket Files to XAMPP's Document Root</h3>
  
1. Open File Explorer and go to the XAMPP document root, which is usually located at -> C:\xampp\htdocs\</p>
2. Copy the extracted osTicket folder and paste it into the htdocs directory.</p>
  
![step 4 image](https://github.com/user-attachments/assets/3126b1a9-7e13-446f-b4bf-53c815ad7999)

>
<p> 
<br />
<br /> 
<p>
<h3>Step 5: Create a MySQL Database for osTicket</h3>
  
1. Open your web browser and go to -> http://localhost/phpmyadmin/</p>
2. Click on Databases and create a new database (example -> osticket)</p>
3. Create a user with full privileges for this database.
  
![step 5 image](https://github.com/user-attachments/assets/d16be413-cdde-4407-b788-f7bafe9ab59c)

>
<p> 
<br />
<br /> 
<p>
<h3>Step Step 6: Run the osTicket Installation Wizard</h3>

1. Open your browser and go to -> http://localhost/osticket/</p>
2. The osTicket installation wizard will open. Follow the on-screen steps:
   - Enter the database details (name, user, and password).
   - Set up the admin email and SMTP settings.</p>

![step 6 image](https://github.com/user-attachments/assets/1f52f139-247d-4d1f-aef7-f3d5340a583c)

3. After installation, delete the setup folder for security.     
       
