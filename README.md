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
Enabling IIS (Internet Information Services) turns a Windows machine into a web server, allowing it to host websites and web applications by serving static and dynamic content over HTTP/HTTPS. It provides features like authentication, logging, security, and application pools for better resource management. Enabling CGI (Common Gateway Interface) within IIS allows the server to execute external scripts, such as Perl, Python, or PHP, to generate dynamic content in response to user requests. This is useful for running legacy applications, processing form data, and interacting with databases. Together, IIS and CGI enable a Windows server to efficiently handle web traffic and execute dynamic scripts for web applications.


</p>
<br />
<img width="1680" alt="Screen Shot 2025-02-14 at 12 03 17 PM" src="https://github.com/user-attachments/assets/b878c245-367e-4750-b169-05b4466ea0b0" />

<p> configuring PHP settings, enabling or disabling PHP extensions, and setting the default PHP version for different websites. This tool helps streamline PHP deployment on IIS, making it easier to manage PHP-based applications 
  
  <img width="1680" alt="Screen Shot 2025-02-14 at 12 08 37 PM" src="https://github.com/user-attachments/assets/ff4e4980-d1ed-4992-97e5-f81e6facce28" />

 Rewrite Module 2 is an extension for Internet Information Services (IIS) that allows you to create powerful URL rewriting rules. It enables web administrators to modify request URLs, redirect users, enforce SEO-friendly URLs, and implement security measures like HTTPS redirection.    
<br />
<img width="1680" alt="Screen Shot 2025-02-14 at 12 13 21 PM" src="https://github.com/user-attachments/assets/fed43315-7572-4684-a2a7-72021f1f38e2" />
Microsoft Visual C++ (2015-2022) Redistributable is a runtime package that provides the necessary libraries, components, and dependencies required to run applications developed using Microsoft Visual C++. It includes standard C and C++ runtime libraries like MSVCR (Microsoft C Runtime) and MSVCP (Microsoft C++ Standard Library), which are essential for many Windows applications. It supports applications built using Visual Studio 2015, 2017, 2019, and 2022.
Ensures compatibility by providing the necessary DLLs (e.g., vcruntime140.dll, msvcp140.dll) for software to run properly.
Required by many third-party programs, games, and system utilities.

<img width="1680" alt="Screen Shot 2025-02-14 at 12 16 39 PM" src="https://github.com/user-attachments/assets/a68a9fb3-f720-42df-b9ea-6f2563482ab7" />
MySQL Server Instance Configuration is the process of setting up and customizing a MySQL database server to optimize performance, security, and operational efficiency. It involves selecting the server type, configuring the network settings (such as the default port 3306 and remote access permissions)
<img width="1680" alt="Screen Shot 2025-02-14 at 12 21 45 PM" src="https://github.com/user-attachments/assets/d3a4ab4d-feb5-4c2d-9d90-aa5752e55770" />


after configuring and downloading c++ version (2015-2022) i also need to configur mysql server  so i used windows c: to look and observe the files in php manager and procced to download said file

<img width="1680" alt="Screen Shot 2025-02-14 at 12 26 23 PM" src="https://github.com/user-attachments/assets/b5fe763b-bc16-46ee-af67-f07e619c02e7" />

To register a new PHP version in PHP Manager for IIS, first download and extract the desired PHP version from windows.php.net. Open IIS Manager (inetmgr), select your server, and double-click PHP Manager. Click "Register New PHP Version", browse to the php-cgi.exe file inside the PHP folder (e.g., C:\PHP\php-8.1.0\php-cgi.exe), and confirm. PHP Manager will update IIS settings automatically. Finally, restart IIS using iisreset to apply the changes. This ensures IIS runs the newly registered PHP version for web applications
<img width="1680" alt="Screen Shot 2025-02-14 at 12 37 09 PM" src="https://github.com/user-attachments/assets/8a2890f3-7a95-422b-8696-d19e85b8762f" />

iis is essential for hosting and managing web-based applications and services on  windows servers in this  instance is being installed for the use of the ticketing system to be functional 

<img width="1680" alt="Screen Shot 2025-02-14 at 12 49 30 PM" src="https://github.com/user-attachments/assets/1cf2c25c-8df2-43b0-8333-c54f99516d5f" />

php manager simplifies the installation and management of php on your server , ensuring that its configured correctly for the php-based ticketing system
<img width="1680" alt="Screen Shot 2025-02-14 at 12 54 43 PM" src="https://github.com/user-attachments/assets/a5151c50-6f05-4d37-958a-568f8b810563" />

after configuring php i was able to download and see osticket installer 
<img width="1680" alt="Screen Shot 2025-02-14 at 1 02 02 PM" src="https://github.com/user-attachments/assets/0c8e6478-7bf8-4014-8195-5a4b43984bba" />   





<br />
