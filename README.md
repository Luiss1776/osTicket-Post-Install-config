<p align="center">
<img src="https://i.imgur.com/iTQ63zq.png"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used 👨‍💻 </h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used 💻 </h2>

- Windows 10 🪟 </b> (21H2)

<h2>Post-Install Configuration Objectives 📝 </h2>

- Configure Roles 
- Configure Departments & Teams
- Configure Agents (The Employees)
- Configure Users (The Customers)
- Configure SLA & Help Topics 

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/bkS19Ot.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
CONFIGURING ROLES

- First go to the Admin panel, scroll down to agents, and click "Add new role." Once clicked, we can now name our new role and allow any permissions such as tickets, tasks, or knowledge bases you may want an agent to have. For this example, we will check in all the boxes under permissions for, Tickets and tasks. Once done, click, “Add role” and osTicket should successfully deploy the new role into the database.
</p>
<br />

<p>
<img src="https://i.imgur.com/VCxXwWP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
CONFIGURING DEPARTMENTS

- By configuring departments we will go to the admin panel, click agents, scroll to departments, and click add new departments. Once clicked, fill out any information needed for the osTicket new department section. For this example, we will create the departments with default settings. The new department created should be added in the Departments section once completed. 

CONFIGURING TEAMS 

- Adding Teams allows you to pull Agents from different Departments and arrange them to handle a specific matter or user via a Help Topic or Ticket Filter. 

- To configure a team, go to the admin panel, click agents, scroll to team's, and then hit add a "new team." Fill out any information required from osTicket in the team section, including team names or members that need to be added.

</p>
<br />

<p>
<img src="https://i.imgur.com/NOoEeYE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
CONFIGURING AGENTS. 
  
- Agents are given access to the help desk with the intent to respond and resolve the tickets. When adding an Agent to the help desk, they will need to be assigned to a Primary Department and given a Primary Role for the Tickets/Tasks routed to that department. 

- By doing this, we will add a few agents by going to the admin panel. Once in the admin panel, we will go to agents and scroll to, “Add New Agent” and fill out any information for the agent including username and password. Finally, once this is done, the users have now been entered into the database.


</p>
<br />

<p>
<img src="https://i.imgur.com/tHaENIW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
CONFIGURING USERS
  
- Users are clients or customers that send tickets through the osTicket regarding an issue. Users can be added or deleted from the User Directory of the help desk at any time. Note, if the user is deleted the tickets of the user must also be deleted.

- We will configure these users by going into the agent panel on the top right of osTicket. When clicked, scroll down to the add new user tab, and enter any information regarding the user. When done, the new users will now be entered into the osTicket database. 
</p>
<br />

<p>
<img src="https://i.imgur.com/FcPASDs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
CONFIGURING SLA's 

- To configure SLA’s we will go back to the admin tab on the top right of osTicket. Once clicked scroll to manage and then down to SLAs. For this example, we will create 3 SLA’s regarding their severity. When done you can create a new SLA by hitting the button, “add new.” Enter any information regarding the SLA’s in the osTicket database. The 3 examples and severities should be similar to the ones above regarding their categories and priorities in a certain time frame. 

CONFIGURING HELP DESK TOPICS

- Users can choose a help desk topic based on the users needs, such as, password resets, login issues or equipment refresh. by doing this, we will configure help desk topics by going into the admin panel, scroll to, “Add new Help Topic.” From there, you can enter the topic and any details needed regarding the issue. When done press save and the new help topic will be store into the osTicket database.
</p>
<br />
