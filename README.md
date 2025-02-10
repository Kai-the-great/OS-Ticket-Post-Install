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

- Configure Departments 
- Configure Team 
- Configure Agents 
- Service Level Agreemnet (SLA)
- Help Topics

<h2>Configuration Steps</h2>


<img width="1440" alt="Screenshot 2025-01-16 at 12 31 27 PM" src="https://github.com/user-attachments/assets/15b05361-c848-40d9-bbb5-752f46b5eaad" />

<p>

</p>
<p>
1. Configure Departments:
Navigate to Admin Panel → Agents → Departments to create and manage departments. Departments allow you to organize agents and define access controls for ticket handling.
</p>
<br />

<img width="1440" alt="Screenshot 2025-01-16 at 12 40 00 PM" src="https://github.com/user-attachments/assets/8ea9368a-7cf4-4ffc-a289-1ea6b40b2d87" />

<p>

</p>
<p>
2. Configure Teams:
Go to Admin Panel → Agents → Teams to create teams within departments. Teams enable multiple agents to collaborate on ticket resolutions efficiently.

</p>
<br />

<img width="1440" alt="Screenshot 2025-01-16 at 12 39 11 PM" src="https://github.com/user-attachments/assets/0f9adc68-852b-4f83-843b-174cd52468ea" />

<p>

</p>
<p>
3. Add and Configure Agents:
In Admin Panel → Agents → Add New, you can add new agents and assign them to specific departments. This ensures that tickets are routed to the appropriate personnel.
</p>
<br />

<img width="1440" alt="Screenshot 2025-01-16 at 12 43 41 PM" src="https://github.com/user-attachments/assets/19356de4-fa03-4672-8807-20865d397c22" />
</p>

4. Define Service Level Agreements (SLA):
Access Admin Panel → Manage → SLA to establish response time policies:

Sev-A: 1-hour grace period, 24/7 support
Sev-B: 4-6 hour grace period, 24/7 support
Sev-C: 8-hour grace period, business hours support

<br />


<img width="1440" alt="Screenshot 2025-01-16 at 12 47 07 PM" src="https://github.com/user-attachments/assets/655e47e1-22dc-4419-919b-11dfa2131061" />
</p>

5. Set Up Help Topics:
Navigate to Admin Panel → Manage → Help Topics to define ticket categories. Help topics ensure that user inquiries are directed to the appropriate department or team for faster resolution.


