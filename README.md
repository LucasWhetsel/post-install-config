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

We now add a user, karen, and we will use her to send in tickets to our "Online Banking" team. 

![image](https://github.com/user-attachments/assets/91481697-bae1-4ce2-a189-bf944231dfe2)

After this, we are going to create three SLA plans. They are named Sev-A, Sev-B, and Sev-C. Sev-A will have a 1 hour grace period, Sev-B will be 4 hours, and Sev-C will be 8 hours. 

![image](https://github.com/user-attachments/assets/7f64be66-8d4d-48fd-8fd8-dd3d0f5e1636)

To finish off this post installation configuration, we added about five new help topics for the users to choose from. These include Business Critical Outage, personal computer issues, equipment request, password reset, and other. 

![image](https://github.com/user-attachments/assets/d7c4b33c-e58f-4255-bee1-15cb6a5d0255)








