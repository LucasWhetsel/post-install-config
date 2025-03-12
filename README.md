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

- Configure Roles, Departments, Teams, and Users
- Configure SLA
- Configure Help Topics
- Allow anyone to create tickets


<h2>Configuration Steps</h2>

Now that we have successfully installed osTicket, we have to use the Admin panel to configure multiple settings within the platform. First, we added the title "Supreme Admin" to the roles section. This role will have all permissions within osTicket. Next, we add Sysadmins to the departments section. 

![image](https://github.com/user-attachments/assets/e6f3a277-aa85-4db6-953d-ce6e9c968246)

Next, we go to teams and create a new team called Online Banking. The agents we create will be apart of this team. Also, we need to go to user settings  and uncheck the box that requires registrations and login to create tickets. This means that everyone will be allowed to create tickets. We then create two agents, Jane and John. They will both be given the Supreme Admin role in the sysadmins department. 

![image](https://github.com/user-attachments/assets/dd46380d-587d-4a45-ad7f-9186f6648bce)


