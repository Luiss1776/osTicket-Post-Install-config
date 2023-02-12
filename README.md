<p align="center">
<img src="https://i.imgur.com/2W88MPA.png"/>
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

- Configure Roles 
- Configure Departments & Teams
- Configure Agents (The Employees)
- Configure Users (The Customers)
- Configure SLA & Help Topics 

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/StaKLhK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
CONFIGURING ROLES 

First go to the Admin panel, scroll down to agents, and click "Add new role." Once clicked, we can now name our new role and allow any permissions such as tickets, tasks, or knowledge bases you may want an agent to have. For this example, we will check in all the boxes under permissions for, Tickets and tasks. Once done, click, “Add role” and osTicket should successfully deploy the new role into the database.
</p>
<br />

<p>
<img src="https://i.imgur.com/VCxXwWP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configuring Departments 

By configuring departments we will go to the admin panel, click agents, scroll to departments, and click add new departments. Once clicked, fill out any information needed for the osTicket new department section. For this example, we will create the departments with default settings. The new department created should be added in the Departments section once completed. 

Configure teams 

Adding Teams allows you to pull Agents from different Departments and arrange them to handle a specific matter or user via a Help Topic or Ticket Filter. 

To configure a team, go to the admin panel, click agents, scroll to team's, and then hit add a "new team." Fill out any information required from osTicket in the team section, including team names or members that need to be added.

</p>
<br />

<p>
<img src="https://i.imgur.com/NOoEeYE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Agents. 


</p>
<br />
