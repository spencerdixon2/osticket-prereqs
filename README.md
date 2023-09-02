<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)



<h2>Installation Steps</h2>

<p>
<img width="1247" alt="Screen Shot 2023-09-01 at 7 17 19 PM" src="https://github.com/spencerdixon2/osticket-prereqs/assets/143224941/68e28817-463c-4f30-a523-2e6e6c711593">
</p>
<p>
Install / Enable IIS in Windows WITH
CGI and Common HTTP Features
World Wide Web Services -> Application Development Features ->
[X] CGI
[X] Common HTTP Features
AND IIS Management Console
Internet Information Services -> Web Management Tools -> IIS Management Console
	[X] IIS Management Console

</p>
<br />

<p>
<img width="1206" alt="Screen Shot 2023-09-01 at 7 23 03 PM" src="https://github.com/spencerdixon2/osticket-prereqs/assets/143224941/1dd4fcb5-934d-4835-b7fd-09117208a1ad">


</p>
<p>
From the Installation Files, download and install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi)
</p>
<br />

<p>
<img width="1204" alt="Screen Shot 2023-09-01 at 7 25 26 PM" src="https://github.com/spencerdixon2/osticket-prereqs/assets/143224941/24268a4f-f27e-4239-80ea-070c6962dd67">

</p>
<p>
From the Installation Files, download and install the Rewrite Module (rewrite_amd64_en-US.msi)
</p>
<br />
<img width="1207" alt="Screen Shot 2023-09-01 at 7 27 23 PM" src="https://github.com/spencerdixon2/osticket-prereqs/assets/143224941/3727d77a-56a3-4e90-9ae3-4a74b7ac0037">


Create the directory C:\PHP


<img width="1292" alt="Screen Shot 2023-09-01 at 7 30 35 PM" src="https://github.com/spencerdixon2/osticket-prereqs/assets/143224941/302686e5-ef95-417d-8894-1552721fd2e7">


From the Installation Files, download PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) and unzip the contents into C:\PHP


<img width="1203" alt="Screen Shot 2023-09-01 at 7 33 42 PM" src="https://github.com/spencerdixon2/osticket-prereqs/assets/143224941/856db3ca-251c-473f-a827-7f604c1b647e">


From the Installation Files, download and install VC_redist.x86.exe.


<img width="1200" alt="Screen Shot 2023-09-01 at 7 35 19 PM" src="https://github.com/spencerdixon2/osticket-prereqs/assets/143224941/4f32ae18-cf04-4c57-af18-b53ab5877ac1">


From the Installation Files, download and install MySQL 5.5.62 (mysql-5.5.62-win32.msi)
Typical Setup ->
Launch Configuration Wizard (after install) ->
Standard Configuration ->


<img width="1190" alt="Screen Shot 2023-09-01 at 7 40 30 PM" src="https://github.com/spencerdixon2/osticket-prereqs/assets/143224941/c5f16703-2c70-4640-bafb-878a5d42ea3c">


Register PHP from within IIS


<img width="1198" alt="Screen Shot 2023-09-01 at 7 52 00 PM" src="https://github.com/spencerdixon2/osticket-prereqs/assets/143224941/f2f06fbc-6305-4cb7-a11e-17433dacfe28">
