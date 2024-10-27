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

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA's
- Configure Help Topics (when creating tickets)

<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/d6094651-f3de-4f17-b591-b5aa5ef10d5e)

I logged into the Windows 10 Pro virtual machine and logged into Admin/Analyst login page. I went to the admin panel, agents, and then roles. I created a new role and name it "Supreme Admin". 
</p>
<br />

![image](https://github.com/user-attachments/assets/3c555291-1a99-458f-a2d4-dbc6e396fb65)

I then created a new department and named it "SysAdmins".
</p>
<br />

![image](https://github.com/user-attachments/assets/4ba790f3-c004-4c1f-aceb-26fe3443fe52)

I created a new team named "online banking". 
</p>
<br />

![image](https://github.com/user-attachments/assets/5496d6a3-66b1-40b3-9465-d766eddd90b5)

I then went into user settings and ensured that Require Registration and Login to create tickets were unchecked. This ensures that anyone can create a ticket (for lab purposes). 

![image](https://github.com/user-attachments/assets/4891123d-22fd-4c8a-b8d9-92dc64a3fe15)
![image](https://github.com/user-attachments/assets/75c3e5f9-9cfc-4ea2-9e19-944e3a3044c6)
![image](https://github.com/user-attachments/assets/00c2e261-2d76-451e-bcff-f7416f60d72b)

I created a new user named Jane Doe, I gave her Supreme Admin rights, her primary department is SysAdmins, and for her assigned team she will be a part of Online Banking 

