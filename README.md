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
- Configure Departments/Teams
- Configure Agents/Users
- Configure SLAs
- Configure Help Topics

<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/5b1c1e43-0633-4fa1-acb8-9156d58f0226)

</p>
<p>
Use the following link to take you to the osTicket log in screen - http://localhost/osTicket/scp/login.php - and log in with the username and password you created. Once logged in, we are going to configure roles, departments, teams, agents, SLAs and Help Topics. 

</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/5fab6cf7-59a5-425d-b759-28c20ed529f0)
![image](https://github.com/user-attachments/assets/e939e9cf-c8f6-410d-842c-eac0ca17ccea)
![image](https://github.com/user-attachments/assets/9051e13f-3d50-46c0-a818-0f223b34c653)

</p>
<p>
First, we are going to configure roles. To do this, click Admin Panel in the top right corner, click agents, roles, and Add New Role. We are going to name the new role Supreme Administrators. Be sure to click Permissions and allow it all available permissions under Tickets, Tasks and Knowledgebase. Once added, you will be able to see your newly added Supreme Administrators role.
</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/b45fce72-cb95-4147-9173-48af704ea61b)
![image](https://github.com/user-attachments/assets/09e26c9f-3827-42e9-96da-8719a856b09b)

</p>
<p>
Next, we will configure a new department. On the Agents tab in the Admin Panel, click departments and Add New Department. Name the new department System Administrators. No need to select an SLA, schedule or manager at this time. 
</p>
<br />

![image](https://github.com/user-attachments/assets/51ac2a90-de9f-47e5-b5bd-acb9dcd00d50)
![image](https://github.com/user-attachments/assets/a9dbee7c-a3fb-4645-a6d9-c73e43afcd49)
![image](https://github.com/user-attachments/assets/99c8f0ec-0e2d-48b9-838f-d6ab639a9510)
![image](https://github.com/user-attachments/assets/acef2aba-5173-4d37-b9d6-f25466fcdb6d)
![image](https://github.com/user-attachments/assets/c2916268-296d-44f1-9f29-ef973cfe30c1)


Next, we will be adding in two agents, Jane and John Doe. On the Agents tab in the Admin Panel, click Add New Agent. Start by adding in Jane Doe, with a username of Jane-Doe and a password. Under Access, set Jane's department to System Administrators, make her role Supreme Administrators, and add support under extended access. Allow her permission to create, delete, edit, manage account and user directory. No need to assign her to a team yet. Next, we will create John Doe. We will create John's account just like Jane's, only we're going to change his department to Support and his role to Expanded Access. 

![image](https://github.com/user-attachments/assets/9fdef37a-60f2-4eac-8d26-a7bf8660b621)
![image](https://github.com/user-attachments/assets/273cccaf-40fe-40f0-9229-7fb09d8df270)
![image](https://github.com/user-attachments/assets/7f103087-7960-4989-bc4f-51eb0a66d52b)
![image](https://github.com/user-attachments/assets/158780af-c6ef-48d0-93b1-152a2cb59e77)


Next, we will configure three SLA plans. In the Admin Panel, click Manage, SLA, and Add New SLA Plan. The first SLA Plan will be called SEV-A, it will have a grace period of one hour and be set to a 24/7 schedule. The second SLA Plan will be called SEV-B, and it will have a grace period of 4 hours and set to a 24/7 schedule. The last SLA Plan will be called SEV-C, and it will have a grace period of 8 hours and set to a schedule of Monda-Friday 8am - 5pm with U.S. Holidays. 

![image](https://github.com/user-attachments/assets/9a3785d8-978e-4b9c-a2bd-625fd5349aff)
![image](https://github.com/user-attachments/assets/17c2230e-5316-4781-93ec-928ae9ed3ca5)
![image](https://github.com/user-attachments/assets/79d7f02f-3176-45b8-b124-7f690af9220d)
![image](https://github.com/user-attachments/assets/86b84d11-beb9-4cec-b8d5-90d15b464618)


Next, we are going to configure four help topics. In the Admin Panel, click manage, Help Topics and select Add New Help Topic. Add Buisness Critical Outage, Equipment Request, Password Reset and Personal Computer Issues. 


![image](https://github.com/user-attachments/assets/11f00c48-aa86-4c9b-aaca-925149848058)
![image](https://github.com/user-attachments/assets/24705015-36e8-4dd3-b015-bc765aab8497)
![image](https://github.com/user-attachments/assets/8b086a84-d3bb-4235-82d4-0d1fe7788817)


Lastly, we are going to configure two users, Karen and Ken Smith. To do so, click on the Agent Panel in the top right corner, click on the Users tab and select Add User. First add Karen Smith with Karen@mail.com as her email. Next, add Ken Smith with Ken@mail.com as his email. 
