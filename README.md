<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>
Stage 1: Intake - Creating a Ticket

Open osTicket.
- Select Open a New Ticket.
Fill in:
- Email Address: karen@osTicket.com
- Name: Karen Karen
- Choose Business Critical Outage from the Help Topic dropdown.
   - In Issue Summary, enter: "Entire mobile online banking is down."
   - In Details, write: "Customers are reporting a 404 error when accessing online banking."
- Click Create Ticket.
![image](https://github.com/user-attachments/assets/8cb3ff9c-40f5-4dca-9434-768d839c8955)
![image](https://github.com/user-attachments/assets/16ad6a76-19d7-444a-8a8d-eb2ff25aa8f1)

Step 2: Assignment and Communication

- Sign into osTicket as an Agent.
  - Log in with the credentials for jane.doe (created in the previous tutorial).
  - Locate and select the ticket created in Step 1.
![image](https://github.com/user-attachments/assets/3ba178ca-65c1-4bb0-9825-50cb0b653093)

-Set Priority to Emergency 
  - (Mobile online banking down impacts revenue).
- Assign the ticket to Jane Doe.
- Choose SLA Plan: SEV-A
  - (Business-impacting, critical incident).
- Select Department: System Administrators (responsible for mobile banking infrastructure).
- In the Response text box, enter:
  - "Coordinating with the Sys Admin Team to restore mobile banking services."
    - Click Post Reply.
![image](https://github.com/user-attachments/assets/e99e4fec-af5d-47bb-9ae0-1cf6e9dc4789)
![image](https://github.com/user-attachments/assets/d8a42d90-ab5a-4d58-acae-373adc37e5c7)

Stage 3: Working the Issue
Jane is collaborating with the System Administrator team on the back end to resolve the issue.

Stage 4: Resolution
1. After resolving the issue, return to the ticket to update the end user.  
2. In the **Response** text box, write:  
   *"Jerry from System Engineering identified and fixed a failed load balancer. Mobile banking is now operational."*  
3. Set **Ticket Status** to **Resolved**.  
4. Click **Post Reply**.  
5. The ticket will move to the **Closed** tab since it has been resolved.

![image](https://github.com/user-attachments/assets/3fad8f1d-02bf-40f1-a898-94569edf7bb0)
![image](https://github.com/user-attachments/assets/5cf0769b-3437-4886-8f71-a28355c8cc26)

The ticket should now appear under the Closed tab, indicating it has been resolved.
