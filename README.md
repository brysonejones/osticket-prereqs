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

- IIS (Internet Information Services)
- PHP Manager
- MySQL
- osTicket v1.15.8
- HeidiSQL

<h2>Installation Steps</h2>
I created a VM in Azure for osTicket.
<img width="1710" alt="OsTicket Azure resources" src="https://github.com/brysonejones/osticket-prereqs/assets/163891519/24dfa2cc-82b6-4ee0-9a11-7ad5b710a3ca">
</p>
<p>
Connected to the VM with Remote Desktop.
<img width="1710" alt="OsTicket RDP connection" src="https://github.com/brysonejones/osticket-prereqs/assets/163891519/59ed0c5f-53a6-478b-8603-5a49011fef0a">
</p>
<p>
The first step I did was setup Internet Information Services.
<img width="1710" alt="IIS setup" src="https://github.com/brysonejones/osticket-prereqs/assets/163891519/5fc4af7a-c50e-4896-8bbc-3e530d9f944c">
</p>
<p>
Here I installed the prerequisite MySQL server that is important for setting up osTicket.
<img width="1424" alt="MySQL Installation" src="https://github.com/brysonejones/osticket-prereqs/assets/163891519/38e3cfb7-8948-4204-a42c-073e559e4153">
</p>
<p>
I enabled PHP IMAP and Intl extensions that were not initially there to help osTicket run better.
<img width="1710" alt="PHP extensions for osTicket" src="https://github.com/brysonejones/osticket-prereqs/assets/163891519/063ce1b6-1f72-435e-a0b6-9ea0a5b46fdd">
</p>
<p>
I setup a database client through HeidiSQL that connects to the MySQL database osTicket.
<img width="1141" alt="HeidiSQL-osTicket-database " src="https://github.com/brysonejones/osticket-prereqs/assets/163891519/07321c81-280f-475a-9a37-692cbcc3bec9">
</p>
<p>
By the end I setup osTicket successfully and logged in as an administrator.
<img width="1710" alt="osTicket successful installation" src="https://github.com/brysonejones/osticket-prereqs/assets/163891519/4ac56e30-6dca-490b-b75a-1f9be131043a">
<img width="1710" alt="osTicket login" src="https://github.com/brysonejones/osticket-prereqs/assets/163891519/6c011305-2984-49fd-9291-1a87dd74cae6">

