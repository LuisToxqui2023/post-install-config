<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />




<h2>Configuration Steps</h2>

<p>
After configuring the osTicket, we will do system administration and post-installation setup. First, we will configure new roles within the help desk. From the upper right side click the Admin Panel --> Agents --> Roles. We will then create a Supreme Admin. Click on "Add new role," then enter the desired name of the new role. You can modify any role's permissions, so we will give the Supreme Admin all permissions. Keep in mind roles are used to determine an agent's permission so not all agents are given full access.

</p>
<br />

![postosticket1](https://github.com/user-attachments/assets/fa7e97dd-f4cc-4828-956d-f1e2eb7c39a3)


<p>
Select the "Departments" located in the agents tab. There we will be able to create a new department. Each agent is assigned to a specific department on their assigned role within the helpdesk. We are creating the "System Administrators" department where the Supreme Admins will be designated. The department tab can be set up for other specific settings, such as SLAs, managers, and email settings.
</p>
<br />

![postosticket2](https://github.com/user-attachments/assets/85b8fa1a-4972-4bb6-a3c7-ce778648c83d)

<p>
After configuring a new department, we will set up a new team. Teams allow you to gather agents from different departments. For example, you can create a help topic that correlates with a product you produce, and assign it to a team of agents that specialize in that particular product. To set up a team, go to Agents --> Teams. A Level I support team has been created by default, in this example, we will create a Level II Support Team.
</p>
<br /> 

![postosticket3](https://github.com/user-attachments/assets/54a66000-ed97-4bac-8569-329d73b2aedf)


<p>
Now that we have set up a new team we will create a new setting that will allow anyone to create tickets. Admin Panel --> Setting --> User Settings.
</p>
<br /> 

![postosticket4](https://github.com/user-attachments/assets/46bfe20b-5962-4533-a91e-6bf57bbe783d)

<p>
It is time to create Agents. Agents are the employees of the helpdesk that work on solving tickets. Agents are assigned  to primary departments and are given a primary role for tickets sent to their department. Agents can be given access to other departments other than their own, they can also have different roles depending on which department they are in. Permissions, Access, and Teams are assigned in the Agents tab.
</p>
<br /> 

![postosticket5](https://github.com/user-attachments/assets/472c4912-634c-4ecb-bd41-7bca257470a8)

<p>
After creating some agents we will create users. Users are customers that create tickets when they are having issues. A user is identified with their E-mail address. To create a user follow this path Agent Panel->Users->User Directory->Add new
</p>
<br /> 

![postosticket6](https://github.com/user-attachments/assets/653dffb7-6986-4ada-8b6d-1ab51f1e0723)

<p>
SLAs Plans provide a length of time in which the help desk is expected to take in order to solve a specific ticket. SLA Plans are created by going to Admin Panel->Manage->SLA Plans. Each SLA has a schedule and within that schedule there is a grace period. In this example SEV-A has a 24/7 and a one hour grace period.
</p>
<br />

![postosticket7](https://github.com/user-attachments/assets/65f6f850-69bc-4ea9-ae7f-0b6834099138)

<p>
Help topics help users categorize their tickets. In the example below we have made a help topic for "Business Critical Outage" this can be if customers cannot access mobile banking.
</p>
<br /> 

![postosticket8](https://github.com/user-attachments/assets/702ad052-4c91-40ad-ae77-85cc07e46e59)

