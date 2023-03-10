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

<h2>Post-Install Configuration</h2>

**Part 3 (Post Installation Setup)**

Configure Roles
- Admin Panel -> Agents -> Roles
- "Supreme Admin"

Configure Departments
- Admin Panel -> Agents -> Departments
- "System Administrators"

Configure Teams
Admin Panel -> Agents -> Teams
- "Level I Support"
- "Level II Support"

Allow anyone to create tickets
- Admin Panel -> Settings -> User Settings
- Registration Required: Require registration and login to create tickets 

Configure Agents (Workers)
- Admin Panel -> Agents -> Add New<br>Ex: "Davvid"</br>

Configure Users (Customers)
- Agent Panel -> Users -> Add New<br>Ex: "Esther"</br>

Configure SLA (Service-Level Agreements)
- Admin Panel -> Manage -> SLA<br>Ex: "SEV-A (1 hour, 24/7)"</br>


Configure Help Topics
- Admin Panel -> Manage -> Help Topics<br>Ex: "Personal Computer Issues"</br>


<h2>Example Screenshots</h2>

<p>
<img src="https://i.imgur.com/aEr2CXl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configuring Roles as an Admin using the ticketing system.
</p>
<br />


<p>
<img src="https://i.imgur.com/89MEr3J.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configuring Agents (Help Desk Professionals!) using the ticketing system.
</p>
<br />


<p>
<img src="https://i.imgur.com/Fj2pEFs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configuring Users (Customers!) using the ticketing system.
</p>
<br />


