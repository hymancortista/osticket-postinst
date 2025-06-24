<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

Configure Roles (for grouping permissions)<br />
Admin Panel -> Agents -> Roles<br />
- Supreme Admin

Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)<br />
Admin Panel -> Agents -> Departments<br />
- SysAdmins

Configure Teams<br />
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)<br />
- Online Banking

Allow anyone to create tickets<br />
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)<br />
- Registration Required: Require registration and login to create tickets 

Configure Agents (workers)<br />
Admin Panel -> Agents -> Add New<br />
- Jane (Dept: SysAdmins)
- John (Dept: Support)

Configure Users (customers)<br />
Agent Panel -> Users -> Add New<br />
- Karen
- Ken

Configure SLA<br />
Admin Panel -> Manage -> SLA<br />
- Sev-A (Grace Period: 1 hour, Schedule: 24/7)
- Sev-B (Grace Period: 4 hours, Schedule: 24/7)
- Sev-C (Grace Period: 8 hours, Business Hours)

Configure Help Topics (For when users create a ticket)<br />
Admin Panel -> Manage -> Help Topics<br />
- Business Critical Outage
- Personal Computer Issues
- Equipment Request
- Password Reset
- Other

