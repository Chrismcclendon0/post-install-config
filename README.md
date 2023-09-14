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


<h2>Configuration Steps</h2>

<p>
  
![image](https://github.com/Chrismcclendon0/osTicket-Post-Installation-Configuration/assets/144953146/3fb14c96-67fd-47ba-a1f8-02609f7e0a4a)

</p>
<p>
First we will configure "Roles". Admin Panel -> Agents -> Roles. Give all access to yourself as an Admin(named "Supreme Admin"). Next Configure new Departments, Admin Panel -> Agents -> Departments, create Dept.(System Administrators). Once completed configure two teams (Level 1 and Level 2 support). Located in Admin Panel -> Agents -> Teams. 

![image](https://github.com/Chrismcclendon0/osTicket-Post-Installation-Configuration/assets/144953146/0d019a40-0a14-47bf-914d-35b40c25051d)

![image](https://github.com/Chrismcclendon0/osTicket-Post-Installation-Configuration/assets/144953146/1fd7c266-084d-43c3-97d7-424d91d21046)

![image](https://github.com/Chrismcclendon0/osTicket-Post-Installation-Configuration/assets/144953146/2ee861a9-6e23-47a3-8817-fc17af782289)

![image](https://github.com/Chrismcclendon0/osTicket-Post-Installation-Configuration/assets/144953146/4618b84c-6399-4b24-8e11-e3381984c08a)


We want to allow anyone to be able to create tickets for right now. Admin Panel -> Settings -> User Settings
Registration Required: Require registration and login to create tickets. Configure Agents(Workers):Admin Panel -> Agents -> Add New. Then create 2 new agents. (1.Jane 2. John) Configure Users(Customers) Agent Panel -> Users -> Add . Create 2 new users (1.Karen 2. Ken)

![image](https://github.com/Chrismcclendon0/osTicket-Post-Installation-Configuration/assets/144953146/14ea886f-4aad-46e7-a52c-20fe9f413af6)

Configure SLA: Admin Panel -> Manage -> SLA
Create three different categories based on severity (Sev). Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), Sev-C (8 hours, business hours).

![image](https://github.com/Chrismcclendon0/osTicket-Post-Installation-Configuration/assets/144953146/f80c7a57-6bef-4f11-8681-be5866a9d267)

Configure Help Topics: Create four common help topics. Admin Panel -> Manage -> Help Topics.
"Business Critical Outage",
"Personal Computer Issues",
"Equipment Request", and "Password Reset".

