<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

After successfully installing osTicket, the following configuration steps are essential to ensure its effective utilization:

1. Define User Roles

2. Organize Departments

3. Set Up Support Teams

4. Allow Ticket Creation

5. Configure Agent Profiles

6. Add User Profiles

7. Establish SLA Policies

8. Categorize Help Topics

Completing these configuration tasks will optimize osTicket for your support or helpdesk operations, ensuring smoother ticket management and customer support.

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Roles:
  
 - Go to the "Admin Panel."
   
 - Click on "Agents," then select "Roles."
   
 - Create a role named "Supreme Admin."
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Departments:

- In the "Admin Panel," click on "Agents," then choose "Departments."
  
- Create a department called "System Administrators."
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Teams:

- Still in the "Admin Panel," click on "Agents," and then select "Teams."
  
- Create two teams named "Level I Support" and "Level II Support."
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Allow Anyone to Create Tickets:

- In the "Admin Panel," go to "Settings" and click on "User Settings."
  
- Enable "Registration Required: Require registration and login to create tickets."
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Agents (Workers):

- In the "Admin Panel," click on "Agents," and choose "Add New."
  
- Create agent profiles for "Jane" and "John."
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Users (Customers):

- In the "Agent Panel" (not Admin), go to "Users," then select "Add New."
  
- Create user profiles for "Karen" and "Ken."
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLA (Service Level Agreements):

- In the "Admin Panel," select "Manage," and then click on "SLA."
  
- Create SLA policies named "Sev-A" (1 hour, 24/7), "Sev-B" (4 hours, 24/7), and "Sev-C" (8 hours, business hours).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Help Topics:
  
- In the "Admin Panel," choose "Manage," and click on "Help Topics."
  
- Create help topics for different types of issues, such as "Business Critical Outage," "Personal Computer Issues," "Equipment Request," and "Password Reset."
</p>
<br />

These steps will help you set up and configure osTicket for your support or helpdesk needs. Each action is explained in a simple way to make the setup process easier, even if you're new to osTicket.



















