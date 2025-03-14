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
<p>
  
- See first:
  -To create VM: [Azure Compute and Networking](https://github.com/victoriadeery/azure-computing-and-networking),
  -To install osTicket: [osTicket: Prerequisites and Installation](https://github.com/victoriadeery/osticket-prereqs), 
  -To configure osTicket for the practice below: [osTicket: Post-Installation Configuration](https://github.com/victoriadeery/post-install-config)
- Resources:
  - Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php
  - End Users osTicket URL: http://localhost/osTicket 
<p>
<img src="https://github.com/user-attachments/assets/4ad69531-5182-447e-bf4b-6ba7583dfb03" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Open a new ticket at http://localhost/osTicket/ as enduser, Karen, who inputs "report a problem" for the help topic when it is a more severe issue that needs to be filed under the help topic "business critical issue."
  <p>
<img src="https://github.com/user-attachments/assets/919a6ca1-c618-4e6d-be45-300c05d6a24f" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  </p>
 2. Log into the admin login page as agent John and observe  the ticket’s properties: Priority, Department, SLA, Assigned To. Set properties to the ticket. Notice the message looks serious so ideally call them to gauge the severity by their tone of voice and details, but at least message them if that is not possible, as it seems serious. Now change the ticket for accuracy. Select SLA default plan and change it from default to Sev-A with description "wide impact. customers unable to do online banking". Change the help topic by selecting its "report a problem" and changing it to  "business critical outage" with the note "no customers able to access online banking" and change the assignment to "online banking" or "jane doe"  with the note "customers not able to access online banking portal, assigning to Jane Doe who is part of the online banking team". Change priority from normal to emergency. If the page is refreshed, all of these changes will show recorded.

</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/905f6453-efe6-465b-8e5b-69e6cdd9ae62" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3. Go to the admin login page and log in as agent Jane. If the ticket was assigned to online banking, click "online banking" next to assignment and write a note for the team like "I'll take this ticket" then give a response such as "I suspect the problem might be related to the recent updates. We have tested them sufficiently, but we will test them further and roll them back if it is determined that was the cause." Then suppose Jane was correct in her assumption and fixed the problem, she would send another messgae like "It was determined that the root cause was the recent update. We rolled it back, notified the vender, and are waiting for a proper fix. Online banking should now be up and running." Then set the status to "resloved"
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. As the end user create a ticket for "accounting department needs adobe upgrade, broken" (help topic: general inquiry, other) (issue summary:accounting dept needs adobe upgrade) (message:it looks like many people in the accounting department  can not use their adobe software.) and then Work the ticket to completion as John. Note, the client requested an upgrade but that might noe be whats needed, so be sure to inspect their computer and figure out why the problem is happening. 
<p>
  
</p>
As usual, first reach out to the client and gather details. 
<p>
  
</p>In this supposed conversation with end user Karen, you find out only two people and not the whole department is dealing with this issue, so change the severity to Sev-C. Then assign it to yourslef as John Doe. pick up at 24 minutes
<br />
