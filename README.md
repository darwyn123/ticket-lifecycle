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

- Set the Priority, Assign Department, Assigned To, and the SLA Plan accordingly to the ticket.
- In this example:
    - Priority is set to "Emergency" because all the teller systems are down.
      <p>
<img width="864" height="421" alt="Update Priority" src="https://github.com/user-attachments/assets/3aa3777a-fd07-4b6f-918d-9f0ed45bb78c" />
</p>
    - Assign Department to Support
    <p>
<img <img width="864" height="421" alt="Update Department" src="https://github.com/user-attachments/assets/c8ede814-aea3-414b-9b41-3afd4e8388e6" />
</p>
    - Assigned To Agent Jane Doe
    <p>
<img <img width="864" height="421" alt="Update Assign To" src="https://github.com/user-attachments/assets/ba2df420-8e6f-44b4-bba7-e60a4baf4c22" />
</p>
    - The SLA Plan is set to Sev-A (response/resolution time in 1 hour)
    <p>
<img <img width="864" height="421" alt="Update SLA Plan" src="https://github.com/user-attachments/assets/c0bdd3f7-18a5-4290-8da8-c334aa482ebf" />
</p>

<br />

<h2>Working the Issue</h2>

- Navigate to localhost/osTicket/scp/login.php, and log in as the Agent that will work on the ticket.

<p>
<img <img width="1018" height="613" alt="Jane log in" src="https://github.com/user-attachments/assets/c4d24da6-a7a9-4c2b-94f7-c01345ae09aa" />
</p>

- The Tickets window shows:
   - The ticket number
   - The last time it was updated
   - The subject
   - Who submitted the ticket
   - Priority level
   - Who it is assigned to
- Click on the ticket to open it, than begin working on issue.

<p>
<img <img width="869" height="326" alt="Ticket Window Jane" src="https://github.com/user-attachments/assets/a0b1daf4-779b-43fc-afd8-63005fc5136d" />
</p>

- Once you open the ticket, you can review all ticket items and the history of the ticket items.
- The bottom section is where you can leave a reply for the user who submitted the ticket and an internal note to notify management if the ticket has been resolved.

<p>
<img <img width="869" height="782" alt="Jane looking at history" src="https://github.com/user-attachments/assets/2e919fe4-8fb5-4fa3-9649-b3e2cafd37ef" />
</p>

- Once you have identified a solution to the problem, you can then use the Post Reply section to write a note to the user explaining everything, including the solution.

<p>
<img <img width="869" height="754" alt="Post Reply" src="https://github.com/user-attachments/assets/e4eb25d2-b9e2-44b3-8ebc-52825df8e758" />
</p>



<br />

<h2>Resolution</h2>

- Before the Agent presses the orange Post Reply button to send the message to the user, it is important to navigate to the Ticket Status and change the from Open (current) to Closed.

<p>
<img <img width="869" height="701" alt="Closed" src="https://github.com/user-attachments/assets/3135e600-1dcd-4ca5-8f9b-89b89b4ce424" />
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
