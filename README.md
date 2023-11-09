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

- Configure different Roles, Departments, and Teams inside osTicket
- Change settings to allow anyone to create tickets
- Setup and configure different Agents, Users, and SLA


<h2>Configuration Steps</h2>

Part 3 (Post Installation Setup)
- Admin Panel vs Agent Panel - Two different Panels you can toggle between

![image](https://github.com/WesGough/post-install-config/assets/150361198/3ed0d8af-1f47-45c6-9782-eeaa714fbcc5)


- Login with credentials at osTicket portal http://localhost/osTicket/scp/login.php 

![LOGIN](https://github.com/WesGough/post-install-config/assets/150361198/26b6787d-013c-45a5-867b-13c54e70b2e8)
  
- Configure Roles - Admin Panel -> Agents -> Roles
- Create New Supreme Admin Role and enable all permissions
  

![image](https://github.com/WesGough/post-install-config/assets/150361198/c2dacf6f-b652-49a0-bc6d-1fd6f29b095a)


- Configure Departments - Admin Panel -> Agents -> Departments -> System Administrators
- Create New System Admin Role 

![image](https://github.com/WesGough/post-install-config/assets/150361198/4b25330e-a999-4870-9678-0c7e8a889138)

- Configure Teams - Admin Panel -> Agents -> Teams -> Level l Support -> Level 2 Support

![image](https://github.com/WesGough/post-install-config/assets/150361198/76aa6478-7477-477f-8573-73fc3c0817fa)

- Allow anyone to create tickets - Admin Panel -> Settings -> User Settings (Registration Required: Require registration and login to create tickets)

![image](https://github.com/WesGough/post-install-config/assets/150361198/dbaa4130-e6a1-46a6-b447-4c374219df1e)

- Configure Agents (workers) - Agent Panel -> Agents -> Add New -> John or Jane
- Create a couple new users and change the access and permissions to whatever you want

![image](https://github.com/WesGough/post-install-config/assets/150361198/d433f3b7-0aab-4fa9-9909-826a878f1bf3)

- Configure Users (customers) - Agent panel -> Users -> Add New -> Karen or Ken
- Configure SLA - Admin Panel -> Manage -> SLA (Sev-A 1 hour, 24/7) (Sev-B 4 hours, 24/7) (Sev-c 9 hours, 24/7)
- Configure Help Topics - Admin Panel -> Manage -> Help Topics (Business Critical Outage) (Personal Computer Issues) (Equipment Request) (Passwork Reset)

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
