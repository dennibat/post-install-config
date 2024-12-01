<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" height="75%" width="100%"alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<!-- <h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com) -->

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<h3 align="center">Configure Roles</h3>
<br />
<p>
  Admin Panel -> Agents -> Roles.
</p>
<p>
  Supreme Admin:
</p>
<p>
  <img src="https://i.imgur.com/ukslQVO.png" height="75%" width="100%" alt="Definitions"/>
  <img src="https://i.imgur.com/ssyKLMc.png" height="75%" width="100%" alt="Permissions"/>
  <img src="https://i.imgur.com/URylw24.png" height="75%" width="100%" alt="More Permissions"/>
  <img src="https://i.imgur.com/KY6XfSB.png" height="75%" width="100%" alt="Even More Permissions"/>
  
<br />
<br />
<h3 align="center">Configure Departments</h3>
<br />
<p>
  Admin Panel -> Agents -> Departments.
</p>
<p>
  System Administrators:
</p>
<p>
  <img src="https://i.imgur.com/ovAYm6A.png" alt="System Administrators"/>
  <img src="https://i.imgur.com/nldv6nj.png" height="75%" width="100%" alt="System Administrators"/>
</p>
<br />
<br />
<h3 align="center">Configure Teams</h3>
<br />
<p>
  Admin Panel -> Agents -> Teams.
</p>
<p>
 Online Banking:
</p>
<p>
  <img src="https://i.imgur.com/ycV6LVv.png" height="75%" width="100%" alt="Level II Support"/>
</p>
<br />
<br />
<h3 align="center">Allow anyone to create ticket</h3>
<br />
<p>
  Admin Panel -> Settings -> User Settings.
</p>
<p>
  Make sure "Require registration and login to create tickets" is not selected:
</p>
<p>
  <img src="https://i.imgur.com/7FHscyn.png" height="75%" width="100%" alt="ticket creations"/>
</p>
<br />
<br />
<h3 align="center">Configure Agents (workers)</h3>
<br />
<p>
  Admin Panel -> Agents -> Add New.
</p>
<p>
  Jane Doe:
</p>
  <img src="https://i.imgur.com/hk2Iwh2.png" height="75%" width="100%" alt="agent one access"/>
<p>
  John Doe:
</p>
<p>
  <img src="https://i.imgur.com/mYnbAMb.png" height="75%" width="100%" alt="agent two"/>
  <img src="https://i.imgur.com/j6g5x3V.png" height="75%" width="100%" alt="agent two access"/>
</p>
<h3 align="center">Configure Users (customers)</h3>
<br />
<p>
  Admin Panel -> Users -> Add New.
</p>
<p>
  Karen User:
</p>
  <img src="https://i.imgur.com/R4dYj8m.png" height="75%" width="100%" alt="user access"/>
<p>
 Ken User.
  </p>
  <img src="https://i.imgur.com/BFQGHZ4.png" height="75%" width="100%" alt="user access"/>
</p>
<br />
<br />
<h3 align="center">Configure SLA</h3>
<br />
<p>
  Admin Panel -> Manage -> SLA.
</p>
<p>
  Sev-A (1 hour, 24/7).
</p>
<p>
  Sev-B (4 hours, 24/7).
</p>
<p>
  Sev-C (8 hours, business hours):
</p>
<p>
  <img src="https://i.imgur.com/kYLCHh8.png" height="75%" width="100%" alt="sev one"/>
  
</p>
<br />
<br />
<h3 align="center">Configure Help Topics</h3>
<br />
<p>
  Admin Panel -> Manage -> Help Topics.
</p>
<p>
  Business Critical Outage.
</p>
<p>
  Personal Computer Issues.
</p>
<p>
  Equipment Request.
</p>
<p>
  Password Reset.
</p>
<p>
  <img src="https://i.imgur.com/fDRzJZV.png" height="75%" width="100%" alt="business critical outage"/>
  
</p>
<br />
<br />
<p>
  And just like that, we’ve finished configuring osTicket! I hope this tutorial has been helpful in guiding you through the setup. Now it’s time to dive into the real challenge: practicing how to triage and resolve tickets effectively.
</p>
<p>
 Mastering this skill is essential for any help desk specialist. Remember, you’re not just solving technical issues—you’re the first point of contact between a company and its customers. How you handle these interactions can shape the entire customer experience, making your role crucial in maintaining trust and satisfaction with the products or services your organization provides.
</p>
