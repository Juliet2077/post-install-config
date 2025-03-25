# post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- configure roles, Departments, and teams in the admin panel
- Allow anyone to create tickets in the admin panel
- configure agents(workers) and users(customers)
- configure SLA (sev-A,sev-B,sev-C)
- configure help topics for when users create a ticket

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  In the Admin panel on the Agents tab, go to roles and create a new role and name it supreme Admin. To set up departments for Ticket visiblity go to the departments tab and create a new department called (SysAdmins). To finish Instal Teams in the Admin Panel on the Agents tab, go to roles and teams(witch pulls agents from different departments) and name it 'online banking'. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To allow anyone to create tickets, Go to the Admin Panel, go to settings, then user settings and UNCHECK the one that says unregistered users can create tickets. Also CHECK the tab Registration required to require agents to have a registration adn login to create tickets.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Now add new Agents 'jane'assign to the department SysAdmins, and 'john'assign department Support.Configure users go to the agent panel click on users, click add new to create users 'Karen' and 'Ken'.
</p>
<br />
