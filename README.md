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
  
![image](https://github.com/Chrismcclendon0/post-install-config/assets/144953146/f5cc4bdd-281e-4d01-a6aa-e8a8b2cbc267)


</p>
<p>
First we will configure "Roles". Admin Panel -> Agents -> Roles. Give all access to yourself as an Admin(named "Supreme Admin"). Next Configure new Departments, Admin Panel -> Agents -> Departments, create Dept.(System Administrators). Once completed configure two teams (Level 1 and Level 2 support). Located in Admin Panel -> Agents -> Teams. 

![image](https://github.com/Chrismcclendon0/post-install-config/assets/144953146/237efa6f-3735-4a00-abb4-99edd796b7f3)

![image](https://github.com/Chrismcclendon0/post-install-config/assets/144953146/e7c42269-8e4d-4581-8508-574484abe6df)


![image](https://github.com/Chrismcclendon0/post-install-config/assets/144953146/f6ca3376-90e1-4686-a5a3-c99009123ae4)


![image](https://github.com/Chrismcclendon0/post-install-config/assets/144953146/2e7c10dc-5a30-4301-804e-9395ecb26722)




We want to allow anyone to be able to create tickets for right now. Admin Panel -> Settings -> User Settings
Registration Required: Require registration and login to create tickets. Configure Agents(Workers):Admin Panel -> Agents -> Add New. Then create 2 new agents. (1.Jane 2. John) Configure Users(Customers) Agent Panel -> Users -> Add . Create 2 new users (1.Karen 2. Ken)

![image](https://github.com/Chrismcclendon0/post-install-config/assets/144953146/2a6a54cc-44a7-4a23-ab3a-175965eccc43)

Configure SLA: Admin Panel -> Manage -> SLA
Create three different categories based on severity (Sev). Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), Sev-C (8 hours, business hours).

![image](https://github.com/Chrismcclendon0/post-install-config/assets/144953146/700d538b-ffa9-46c6-98ba-d8a048ce5842)


Configure Help Topics: Create four common help topics. Admin Panel -> Manage -> Help Topics.
"Business Critical Outage",
"Personal Computer Issues",
"Equipment Request", and "Password Reset".

