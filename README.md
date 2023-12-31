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

- Windows 10</b>

<h2>List of Prerequisites</h2>
 
- Before installing your prerequisites, you must enable a couple of features so you're able to run the osTicket software with no issues by pressing your "WIN" key and typing "turn windows feature on or off". When that is open follow the pathway I will type out. Internet Information Service -> Web Management Tools -> Check "IIS Management Console" Then World Wide Web Services -> Application Development Features -> Check "CGI" and "Common HTTP Features" that are 5 folders under "CGI".
- PHP Manager for IIS
- IIS URL Rewrite Module
- PHP (the latest version available for you)
- MySQL
- Microsoft Visual C++ (x86)
- HeidiSQL


<h2>Installation Steps</h2>

<p>

 ![Screenshot 2023-07-12 143930](https://github.com/trentree/osticket-prereqs/assets/129711900/99c21d58-e3ea-4aee-b7f6-47d1d0912afb)

</p>
<p>
No Special actions are needed when downloading "PHP Manager for IIS". This is just adding the feature into your IIS software.
</p>
<br />

<p>

![Screenshot 2023-07-12 143938](https://github.com/trentree/osticket-prereqs/assets/129711900/aec49d96-aa0d-4bb9-931f-db574f14811e)

</p>
<p>
This software also does not need any special actions when downloading. This will allow you to create rules to implement URLs that are easier for other users to remember and easier for search engines to find. 
</p>
<br />

<p>

![Screenshot 2023-07-15 140010](https://github.com/trentree/osticket-prereqs/assets/129711900/b60ecb9c-3e7b-451e-b602-28bd3db8ec6b)

</p>
<p>
Before downloading this software, create a separate folder on any drive. For example:"C:\PHP". Once your folder is created, you may proceed to download the PHP software. This software allows you to script languages for web development.
</p>
<br />

<p>

![Screenshot 2023-07-12 143910](https://github.com/trentree/osticket-prereqs/assets/129711900/8215c423-4af7-4915-9434-3639d0190882)

</p>
<p>
Also, no special actions are needed to be taken while downloading this. Usually, this software comes with the Windows operating system but this was downloaded for safety measures. PHP requires Microsoft C++ to work properly.
</p>
<br />

<p>
 
![Screenshot 2023-07-12 143922](https://github.com/trentree/osticket-prereqs/assets/129711900/fc7a9534-2235-4761-aa64-d5966c26cf6a)

</p>
<p>
When downloading the MySQL software, you will want to run "Typical Setup" and just install everything else as default.
</p>
<br />

<p>

![Screenshot 2023-07-15 125841](https://github.com/trentree/osticket-prereqs/assets/129711900/5ff0719e-c57f-4a31-99a9-2347ba8ff69e)

</p>
<p>
Finally, we enter a username and password to be able to login to osTicket.
</p>
<br />
