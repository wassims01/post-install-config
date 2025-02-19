<p align="center"> <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket Logo" style="width: 50%;"/> </p>
<h1 align="center" style="font-size: 50px;">osTicket - Post-Install Configuration</h1>
<p style="font-size: 30px;"> This tutorial outlines the post-install configuration of the open-source help desk ticketing system, osTicket. It covers essential steps to configure agents, teams, departments, roles, and more. </p>

<h2 style="font-size: 40px;">Video Demonstration</h2>
<p style="font-size: 30px;"> - <strong><a href="https://www.youtube.com">YouTube: How To Configure osTicket, Post-Installation</a></strong> </p>

<h2 style="font-size: 40px;">Environments and Technologies Used</h2>
<ul style="font-size: 30px;"> 
<li><strong>Microsoft Azure</strong> (Virtual Machines/Compute)</li> 
<li><strong>Remote Desktop</strong></li> 
<li><strong>Internet Information Services (IIS)</strong></li> 
</ul>

<h2 style="font-size: 40px;">Operating Systems Used</h2>
<p style="font-size: 30px;"> - <strong>Windows 10</strong> (21H2) </p>

<h2 style="font-size: 40px;">Post-Install Configuration Objectives</h2>
<ul style="font-size: 30px;"> 
<li>Configure Agents (Workers)</li> 
<li>Configure Teams</li> 
<li>Configure Departments (Ticket Visibility)</li> 
<li>Configure Roles (Grouping Permissions)</li> 
<li>Understand the Difference Between Agent Panel and Admin Panel</li> 
</ul>

<h2 style="font-size: 40px;">Admin Panel vs. Agent Panel</h2>
<h3 style="font-size: 35px;">Admin Panel</h3>
<p style="font-size: 30px;"> The Admin Panel is used by administrators to configure the system, including roles, departments, teams, SLAs, and other settings. </p>
<p align="center"> <img src="https://i.imgur.com/5Wk2mmD.png" alt="Admin Panel Screenshot" style="width: 80%;"/> <img src="https://i.imgur.com/RCZX42W.png" alt="Admin Panel Screenshot" style="width: 80%;"/> </p>

<h3 style="font-size: 35px;">Agent Panel</h3>
<p style="font-size: 30px;"> The Agent Panel is used by agents (support staff) to manage tickets assigned to them. </p>
<p align="center"> <img src="https://i.imgur.com/vG1zXlx.png" alt="Agent Panel Screenshot" style="width: 80%;"/> </p>

<h2 style="font-size: 40px;">Configuring Roles</h2>
<p style="font-size: 30px;"> Roles are used to group permissions for agents. Follow these steps to configure roles: </p>
<ol style="font-size: 30px;"> 
<li>Navigate to: <strong>Admin Panel -> Agents -> Roles</strong>.</li> 
<li>Create a new role: 
<ul> 
<li><strong>Role Name</strong>: Supreme Admin</li> 
<li>Assign all permissions to this role for full administrative control.</li> 
</ul> 
</li> 
</ol>
<p align="center"> <img src="https://i.imgur.com/9Qj1rPY.png" alt="Configuring Roles Screenshot" style="width: 80%;"/> <img src="https://i.imgur.com/5N95hnK.png" alt="Configuring Roles Screenshot" style="width: 80%;"/> </p>

<h2 style="font-size: 40px;">Adding a Role Through Agent</h2>
<p align="center"> <img src="https://i.imgur.com/aXAkFrq.png" alt="Adding a Role Screenshot" style="width: 80%;"/> </p>

<h2 style="font-size: 40px;">Configuring Departments</h2>
<p style="font-size: 30px;"> Departments are used to organize tickets based on their visibility and purpose. Follow these steps to configure departments: </p>
<ol style="font-size: 30px;"> 
<li>Navigate to: <strong>Admin Panel -> Agents -> Departments</strong>.</li> 
<li>Create the following departments: 
<ul> 
<li><strong>Help Desk</strong>: General support.</li> 
<li><strong>SysAdmins</strong>: System administration-related tickets.</li> 
<li><strong>Networking</strong>: Networking-related tickets.</li> 
</ul> 
</li> 
</ol>
<p align="center"> <img src="https://i.imgur.com/exHiTew.png" alt="Adding a Department Screenshot" style="width: 80%;"/> <img src="https://i.imgur.com/Qj0rPKx.png" alt="Adding a Department Screenshot" style="width: 80%;"/> </p>

<h2 style="font-size: 40px;">Adding a Group</h2>
<p align="center"> <img src="https://i.imgur.com/XRFVJRy.png" alt="Adding a Group Screenshot" style="width: 80%;"/> </p>

<h2 style="font-size: 40px;">Adding a New Help Desk Agent</h2>
<p align="center"> <img src="https://i.imgur.com/fLR8VsP.png" alt="Adding a New Agent Screenshot" style="width: 80%;"/> </p>

