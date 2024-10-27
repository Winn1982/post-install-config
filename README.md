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

I created a new user named Jane Doe,I gave her Supreme Admin rights,her primary department is SysAdmins, and for her assigned team she will be a part of Online Banking.

![image](https://github.com/user-attachments/assets/92afb186-e002-443e-bf7b-28205a6b87a9)
![image](https://github.com/user-attachments/assets/54088aa5-b3d2-4571-a010-606f4f11cf4f)

I created another user named John Does,he is in the support department and was given expanded access. 

![image](https://github.com/user-attachments/assets/8b66e2fe-1da3-4140-89d2-259ad0d1a54a)
![image](https://github.com/user-attachments/assets/c2fd5883-4abd-4407-bbdb-50d0efc81e3c)

I then went to the agent panel, clicked on users, and created a new user named Karen and John.

![image](https://github.com/user-attachments/assets/40321b81-b8ff-4e06-becc-d6ee51724aaa)
![image](https://github.com/user-attachments/assets/290eb5ef-f6d4-44c5-91c9-24d5ccda33a7)
![image](https://github.com/user-attachments/assets/688c8049-f44e-451f-a783-1af7ec6904ec)

I configured/created new SLA agreements. Sev-A is the most serious of incidents and has an hour response time. Sev-B is less serious and has a response time of 4 hours. Sev-C is the least critical and has a response time of 8 hours. There is a default SLA with a grace period of 18 hours. 




