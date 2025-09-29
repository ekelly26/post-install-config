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

- Acknowledge Agent Panel vs Admin Panel
- In Admin Panel, configure roles (Supreme Admin), Departments (Ticket visibility, Help Desk vs SysAdmins vs Networking), and Teams (Ex: Online Banking)
- In User Settings in Admin Panel, allow anyone to create tickets by unchecking "unregistered users can create tickets" and require registration login to create tickets
- Configure and Add New Agents (workers) in the Admin Portal - - Jane (Dept: SysAdmins) and John (Dept:Support)
- Switch to Agent Panel and configure new users (customers) - - Karen, Ken
- Switch back to Admin Panel and configure SLA - - SEV-A, SEV-B, and SEV-C
- Configure help topics (for when users create tickets) -- Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset, and Other

<h2>Configuration Steps</h2>

<p>
<img width="1203" height="731" alt="image" src="https://github.com/user-attachments/assets/a950a671-a338-4525-ba57-17af7e53e505" />
<img width="1201" height="919" alt="image" src="https://github.com/user-attachments/assets/22323805-edb0-49b5-a1bf-65429b3bdf40" />
<img width="1215" height="844" alt="image" src="https://github.com/user-attachments/assets/033494b0-d0a6-499b-8d84-c98083fc273a" />



<p>
</p>
<br />
-In Admin Panel, configure roles (Supreme Admin), Departments (Ticket visibility, Help Desk vs SysAdmins vs Networking), and Teams (Ex: Online Banking). Each of these functions are found within the admin portal. It will try to start you in the settings tab sometimes, but the agents tab is the section above the settings tabs on the far right.

<p>
<img width="1199" height="851" alt="image" src="https://github.com/user-attachments/assets/0f03aaf2-dba1-4a46-b6ef-9ba534524f60" />
<img width="1186" height="496" alt="image" src="https://github.com/user-attachments/assets/8962762a-e0a2-446a-abf6-670b1cb08f63" />
 <img width="1204" height="488" alt="image" src="https://github.com/user-attachments/assets/d9491dda-38d5-41d1-b110-7858f7e8c30c" />


<p>
In User Settings in Admin Panel, allow anyone to create tickets by unchecking "unregistered users can create tickets" and require registration login to create tickets.  Then, configure and Add New Agents (workers) in the Admin Portal Ex: Jane (Dept: SysAdmins) and John (Dept:Support). Then, switch to the Agent Panel and configure users(customers) Ex: Karen, Ken


<br />

<p>
<img width="1201" height="827" alt="image" src="https://github.com/user-attachments/assets/903c4539-ed8b-47a6-9d74-2e1637eaacfc" />
 <img width="1214" height="822" alt="image" src="https://github.com/user-attachments/assets/cafdaa76-e22e-47e1-bee4-83507ca7437c" />
 <img width="1196" height="826" alt="image" src="https://github.com/user-attachments/assets/05e3e63f-dffc-437e-bec9-b12f8deaa42f" />
 <img width="1201" height="529" alt="image" src="https://github.com/user-attachments/assets/e7f653b5-d957-4cb5-ae43-82c45dbff2a9" />
 <img width="1283" height="710" alt="image" src="https://github.com/user-attachments/assets/9c2ecc66-3170-4ceb-a787-b160160f4f43" />

</p>
<p>
Switch back to the Admin Portal and configure SLAs (SEV-A, SEV-B, SEV-C). Then, configure Help Topics (For when users create tickets) (Business Critical Outage, Personal Computer Issues, Equipment Reset, Other)
<br />
