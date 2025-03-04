<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>List of Prerequisites</h2>

- Remote Desktop
- osTicket Installation File
- IIS
- PHP Manager
- Rewrite Module
- VC Redist
- MySQL
- HeidiSQL

<h2>Installation Steps</h2>

<p>
  
![image](https://github.com/user-attachments/assets/24f61bbc-c45d-47fd-a4cb-a66f005333ef)

</p>
<p>
Created a virtual machine named "osTicket" and opened up remote desktop to access the virtual machine.
</p>
<br />

<p>

![Running IIS](https://github.com/user-attachments/assets/354bbf03-2a1c-409f-b4ed-6adbf6758e1b)

</p>
<p>
Installed osTicket-Installation-Files, CGI, PHP Manager, Rewrite Module, VC Redist & MySQL. Then, opened IIS.
</p>
<br />

<p>
  
![registering PHP](https://github.com/user-attachments/assets/439cf7d8-fda4-4c16-b89b-6f745bd92202)

</p>
<p>
Registered PHP from within IIS.
</p>
<br />

<p>
  
![Put osTicket installed folder in wwwroot folder](https://github.com/user-attachments/assets/4ad888f5-6a47-4207-9a7b-49d1f9615178)

</p>
<p>
Unziped osTicket-v1 zip file and put the "upload" folder into "c:\inetpub\wwwroot." Then, renamed the folder from "upload" to "osTicket."
</p>
<br />

<p>
  
![opened osTicket installer website](https://github.com/user-attachments/assets/c7c8095d-057d-4d1b-bc24-b10010a97b20)

</p>
<p>
Opened osTicket Installer website.
</p>
<br />

<p>
  
![enabled php items for osTicket site setup](https://github.com/user-attachments/assets/58bed7d8-ef55-4950-bf52-3b3cb4faa20a)

</p>
<p>
Opened PHP manager and enabled remaining php extensions for the osTicket installer site.
</p>
<br />

<p>
  
![osTicket website finished installing with database setup fully](https://github.com/user-attachments/assets/6c28a755-9c75-43e1-89d4-39fe4ce3775d)

</p>
<p>
Assigned Permissions to everyone and installed HeidiSQL, creating a database called "osTicket." Put MySQL credentials and osTicket is fully installed in the browser.
</p>
<br />

<p>
  
![osTicket help desk main page installed](https://github.com/user-attachments/assets/a21daee9-fbc8-4aea-bb38-28933ab15196)

</p>
<p>
Help Desk Login page and Main page is created.
</p>
<br />

<p>
  
![osTicket End Users page created](https://github.com/user-attachments/assets/d064dde9-fbda-42cb-bbfd-25cc1ae4b30f)

</p>
<p>
Created osTicket page for End Users.
</p>
<br />
