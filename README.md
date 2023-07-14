![Screenshot 2023-07-14 143143](https://github.com/isobarh/osTicket---Post-Install-Configuration/assets/139295370/da728f66-32ad-45e0-8787-c4f0bcc7657b)![Screenshot 2023-07-14 143143](https://github.com/isobarh/osTicket---Post-Install-Configuration/assets/139295370/eabd0e96-f861-4714-a784-f43125c3b0ce)<p align="center">
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

-(Create Virtual Machine in Azure)

-Create a Resource Group

-Create a Windows 10 Virtual Machine (VM) with 2-4 Virtual CPUs

-When creating the VM, allow it to create a new Virtual Network (Vnet)

-Name: Vm-osticket

-Username: labuser (for example/whatever you chose)

-Password: osTicketPassword1! (for example/whatever you chose)

![Annotation 2023-07-12 214439](https://github.com/isobarh/osTicket---Post-Install-Configuration/assets/139295370/7c856841-2a31-4483-ba63-c5990ba2c2ce)

![Annotation 2023-07-12 214539](https://github.com/isobarh/osTicket---Post-Install-Configuration/assets/139295370/75892253-bf9f-48d8-ab86-a0f271caccc8)


<h2>Configuration Steps</h2>

-Configure Roles

-Admin Panel -> Agents -> Roles

-Supreme Admin

![Screenshot 2023-07-14 141653](https://github.com/isobarh/osTicket---Post-Install-Configuration/assets/139295370/9af0fe6d-e47f-4342-92fa-a340c629fd80)

![Screenshot 2023-07-14 142148](https://github.com/isobarh/osTicket---Post-Install-Configuration/assets/139295370/429e572b-2a04-466e-a793-1bc1b890c006)

![Screenshot 2023-07-14 142334](https://github.com/isobarh/osTicket---Post-Install-Configuration/assets/139295370/89ab9909-4a78-4d3c-860a-82a200671d97)

![Screenshot 2023-07-14 142451](https://github.com/isobarh/osTicket---Post-Install-Configuration/assets/139295370/b6bb8a42-4c20-49e0-8bfa-918c86c6efd8)

![Screenshot 2023-07-14 142544](https://github.com/isobarh/osTicket---Post-Install-Configuration/assets/139295370/dcde5d34-9aad-48ad-acb8-5aafce546d50)

![Screenshot 2023-07-14 142617](https://github.com/isobarh/osTicket---Post-Install-Configuration/assets/139295370/a66bde35-606c-4545-b07e-4f024ae12ba0)

![Screenshot 2023-07-14 142635](https://github.com/isobarh/osTicket---Post-Install-Configuration/assets/139295370/d8dc832e-112e-4db0-9303-a105699b38b4)

![Screenshot 2023-07-14 142708](https://github.com/isobarh/osTicket---Post-Install-Configuration/assets/139295370/dc72a4db-426c-4fa2-ac0c-62b2d28eca21)


-Configure Departments

-Admin Panel -> Agents -> Departments

-System Administrators

![Screenshot 2023-07-14 142730](https://github.com/isobarh/osTicket---Post-Install-Configuration/assets/139295370/f61175f0-5200-419a-acbd-d3e8e2cf188d)

![Screenshot 2023-07-14 142925](https://github.com/isobarh/osTicket---Post-Install-Configuration/assets/139295370/c1a84b9d-3f58-4d09-a87e-c381aebab111)

![Screenshot 2023-07-14 142950](https://github.com/isobarh/osTicket---Post-Install-Configuration/assets/139295370/fa54b703-96bd-4f8e-963c-a1b587646aaa)


Configure Teams
Admin Panel -> Agents -> Teams
Level I Support
Level II Support

![Screenshot 2023-07-14 143039](https://github.com/isobarh/osTicket---Post-Install-Configuration/assets/139295370/0ce5ec23-4905-4f72-90ea-5d8f568d22a7)





Allow anyone to create tickets
Admin Panel -> Settings -> User Settings
Registration Required: Require registration and login to create tickets 


Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane
John


Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken


Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)


Configure Help Topics
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset


