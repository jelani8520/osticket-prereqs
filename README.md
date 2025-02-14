# osticket-prereqs
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

- enable information services or iis
- install web platform installer
- setup the username and password
- install c++ redistributable
- configure premission and install os ticket 

<h2>Installation Steps</h2>
  
</p><p>
Before installing osTicket, make sure your server meets these requirements:
Web Server: Apache or Nginx PHP: Version 7.3 or higher Database: MySQL 5.6+ or MariaDB 10.0+ Required PHP Extensions: GD Library mbstring MySQLi XML cURL ZIP
  in my case i used those config on a virtual machine in microsoft azure
  after looking at my homelab checklist i procced to extract the files for the proper installation
</p>
<br />
<img width="1680" alt="Screen Shot 2025-02-14 at 12 03 17 PM" src="https://github.com/user-attachments/assets/b878c245-367e-4750-b169-05b4466ea0b0" />

<p> 11111
<img width="1680" alt="Screen Shot 2025-02-14 at 12 08 37 PM" src="https://github.com/user-attachments/assets/ff4e4980-d1ed-4992-97e5-f81e6facce28" />

<p

 in the picture above it shows all the files needed for installation 
</p>
<br />
<img width="1680" alt="Screen Shot 2025-02-14 at 12 13 21 PM" src="https://github.com/user-attachments/assets/fed43315-7572-4684-a2a7-72021f1f38e2" />
111111

<img width="1680" alt="Screen Shot 2025-02-14 at 12 16 39 PM" src="https://github.com/user-attachments/assets/a68a9fb3-f720-42df-b9ea-6f2563482ab7" />
111111

<img width="1680" alt="Screen Shot 2025-02-14 at 12 21 45 PM" src="https://github.com/user-attachments/assets/d3a4ab4d-feb5-4c2d-9d90-aa5752e55770" />


after configuring and downloading c++ version (2015-2022) i also need to configur mysql server  so i used windows c: to look and observe the files in php manager and procced to download said file

<img width="1680" alt="Screen Shot 2025-02-14 at 12 26 23 PM" src="https://github.com/user-attachments/assets/b5fe763b-bc16-46ee-af67-f07e619c02e7" />
lllllll
<img width="1680" alt="Screen Shot 2025-02-14 at 12 37 09 PM" src="https://github.com/user-attachments/assets/8a2890f3-7a95-422b-8696-d19e85b8762f" />





iis is essential for hosting and managing web-based applications and services on  windows servers in this  instance is being installed for the use of the ticketing system to be functional 

<img width="1680" alt="Screen Shot 2025-02-14 at 12 49 30 PM" src="https://github.com/user-attachments/assets/1cf2c25c-8df2-43b0-8333-c54f99516d5f" />

php manager simplifies the installation and management of php on your server , ensuring that its configured correctly for the php-based ticketing system
<img width="1680" alt="Screen Shot 2025-02-14 at 12 54 43 PM" src="https://github.com/user-attachments/assets/a5151c50-6f05-4d37-958a-568f8b810563" />


<img width="1680" alt="Screen Shot 2025-02-14 at 1 02 02 PM" src="https://github.com/user-attachments/assets/0c8e6478-7bf8-4014-8195-5a4b43984bba" />

111





<br />
