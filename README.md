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

- Configure Agents (Workers)
- Configure Teams
- Configure Departments (Ticket Visibility)
- Configure Roles (Grouping Permissions)
- Acknowledge Agent Panel vs Admin Panel


</p>


--Admin Panel : Used by administrators to configure the system, including roles, departments, teams, SLAs, and other settings--
</p>

<img src="https://i.imgur.com/5Wk2mmD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/RCZX42W.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

--Agent Panel : Used by agents (support staff) to manage tickets assigned to them.--

<img src="https://i.imgur.com/vG1zXlx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


</p>

--ADMIN ROLES :


<img src="https://i.imgur.com/9Qj1rPY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/5N95hnK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Configure Roles (Grouping Permissions)
Navigate to: Admin Panel -> Agents -> Roles .
Create a new role:
Role Name : Supreme Admin.
Assign all permissions to this role for full administrative control.
<p>


--Adding A role through agent--


<img src="https://i.imgur.com/aXAkFrq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>

-Adding a Departement :


<img src="https://i.imgur.com/exHiTew.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/Qj0rPKx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


Configure Departments (Ticket Visibility)
Navigate to: Admin Panel -> Agents -> Departments .
Create the following departments:
Help Desk : General support.
SysAdmins : System administration-related tickets.
Networking : Networking-related tickets.
Assign tickets to specific departments based on their visibility and purpose.

<p>

<p>


Adding a group :
<p>


<img src="https://i.imgur.com/XRFVJRy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
--Adding a New helpdesk Agent--

<p>

  
<img src="https://i.imgur.com/fLR8VsP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

