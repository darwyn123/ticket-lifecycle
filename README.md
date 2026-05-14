<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


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

<h2>Intake</h2>

- Open a Web Browser and navigate to localhost/osTicket/index.php, and click the blue Open a New Ticket button.

<p>
<img <img width="762" height="444" alt="Blue Botton Login" src="https://github.com/user-attachments/assets/f37e445c-ad13-4481-8093-c6d26dbf149f" />
</p>

- Fill out the following:
  - Email Address: type in the user's email
  - Full Name: type in the user's name
  - Help Topic: Select the help topic type
  - Issue Summary: Breif summary of the issue on issue title, and in the second field explain more the issue.

- Click Create Ticket

<p>
<img <img width="762" height="782" alt="Create Ticket" src="https://github.com/user-attachments/assets/f36375d7-83ad-4200-a8c7-5d616e965170" />
</p>

<br />

<h2>Assignment & Communication</h2>

- Navigate to localhost/osTicket/scp/login.php, and log in as the administrator that will assign an Agent to work on the ticket created.

<p>
<img <img width="1024" height="600" alt="John Login" src="https://github.com/user-attachments/assets/1793d3d2-e253-45ea-9654-ad924f460628" />
</p>

- Navigate to Tickets -> Click on the ticket under the Ticket column.

<p>
<img <img width="864" height="334" alt="Open Ticket as John" src="https://github.com/user-attachments/assets/fa254027-6be2-4a77-a3e0-e4a6d694d2d7" />
</p>

- Select the Priority, Assign Department, Assigned To, and the SLA Plan accordingly to the ticket.
- In this example:
    - Priority is set to High
      <p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
    - Assign Department is set to
    <p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
    - Assigned To 
    <p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
    - The SLA Plan is set to
    <p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

- Within the ticket tab, you can see the thread of any updates to the ticket and submit updates upon assignment. Once finished, click the orange Post Reply button and the ticket gets assigned to the appropriate department and your customer gets notified of this change.
      
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<h2>Working the Issue</h2>

- Navigate to localhost/osTicket/scp/login.php, and log in as the Agent that will work on the ticket.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

- Once logged in, the Tickets window shows. It will show the ticket number, the last time it was updated, the subject, who submitted the ticket, priority level, and who it is assigned to. The Agent must click on the ticket number to open it so that they can begin working through the problem.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

- Once the ticket is opened, you can review all ticket items and the history of the ticket items. This includes who submitted the ticket, who assigned the ticket, and any other ticket activity. The bottom section is where you can leave a reply for the user who submitted the ticket and an internal note to notify management if the ticket has been resolved.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

- Once the Agent (Luke Skywalker) has reviewed all of the ticket details and identified a solution to the problem, the Agent can then use the Post Reply section to write a note to the user (Jane Doe) explaining everything, including the solution, in a professional manner.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>



<br />

<h2>Resolution</h2>

- Before the user presses the orange Post Reply button to send the message to the user, it is important to navigate to the Ticket Status drop-down menu and change the value from Open (current) to Closed.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

- Then, osTicket will take the Agent back to the Tickets tab. The Agent will then see a confirmation that the reply was posted successfully. As pictured below, ticket #325542 by Jane Doe is no longer showing in the Open tickets section. Additionally, there is a visual confirmation banner at the top that says Ticket #325542: Reply posted successfully.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

- To view tickets that have been closed, Agents can navigate to Tickets > Closed > and then click the appropriate time frame that this ticket is from. From here, the Agent should see closed ticket in question.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />
