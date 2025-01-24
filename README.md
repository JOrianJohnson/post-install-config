<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket. This lab is part 2 to the "OsTicket-Prerequisites and Installation" lab<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles, Departments & Teams
- Allow Users to Create Tickets
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/2T65kV4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/7yxP3jI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/W8mMxjk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First you want to log into the OsTicket browser and make sure you are on the "Admin Panel".If it shows "Agent Panel" in the top right corner that means you are in the admin panel and vice versa. Look at picture # 1 for reference.Then click agents\roles\add new role, create a "Supreme Admin". This person can do every task and has all permissions/access. Repeat this to perform the next two steps which are: configuring the departments and teams (create a "System Administrators Department" & "Online Banking team"). 
</p>
<br />

<p>

</p>
<p>
Next, go to settings\users\settings again and make sure the box titled "require registration and login to create tickets" is unchecked. This is will allow everyone to make tickets without having to register or login to the company's system. 
</p>
<br />

<p>
<img src="https://i.imgur.com/CUDhCF3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<img src="https://i.imgur.com/W8mMxjk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here you will create two new test agents ("John Joe" and "Karen John"). Assign John to "System Administrators" department with "Supreme Admin" permissions add him to "Support" team. All of these options are located under the "Access & Teams" tabs on the same agent screen. Next add "Karen John" the same way but instead to the "Online Banking" team. 
</p>
<br />

<p>
<img src="https://i.imgur.com/O6oYc3Z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this step you will configure how customers and employees use the ticketing system software. Go to the agent panel\Users\tab\create new user, and create two new generic users named "Kenny" and "Kari" with email addresses, phone numbers are optional. Any name or email combonation is fine since these are both just test accounts for the third and final part of this entire demonstration. 
</p>
<br />

<p>
<img src="https://i.imgur.com/ULNyAo6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, a "Service Level Agreement" (SLA) needs to be created. You will create three SLAs by going to admin panel\manage\SLA, to create all three of the SLAs. "Sev-A" - set the time needed to be responded to within 1 hour on a 24/7 schedule. "Sev-B" - set the time needed to be responded to within 4 hours on a 24/7 schedule. "Sev-C"- set the time needed to be responded to within 8 hours on a regular business hour time frame.
</p>
<br />

<p>
<img src="https://imgur.com/yu9Oybh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The last step is to configure "Help Topics". In this step you will create the help ticket names in OsTicket for users to select when they are having specific issues. The tickets will also need to be assigned to a "Department" along with a "SLA Severity/Priority". You can even auto assign certain help desk ticket topics to a group like "Supporrt" or "Online Banking" depending on the severity. For example, A user will or employee will create a ticket with a help topic titled "Business Critical Outage"\priority level\"emergency"\"Sev-A" SLA\sent to the "System Administrators" group\auto-assigned to the "support team" or to an individual agent like John. This is how to setup 
osTicket support tickets from the admin level post Installation.
