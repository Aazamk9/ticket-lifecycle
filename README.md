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


<h2>Ticketing System</h2>


<h3>Opening Tickets</h3> Inorder to open up a ticket and be ready to solve it you must do the following:

- Input the customer's contact info
- Select a Help Topic which directly correlates to the customer's issue (eg. customer states that password and account cannot be accesed, this directly correlates to the "Password Reset" Help Topic)
- Create a brief summary of what the issue(s) are and start troubleshooting

<h4>Note The Following*</h4>

- If you are running test tickets on your end, you can create these tickets and make random scenarios using these help topics and the two users you have created.
- Actively communicate the "user" and "agent" together by going back and forth with essentially, yourself
- Create a ticket, see the issue, factor the problem into more smaller problems, communicate with the user to further work the issue, and finally, get to the bottom of the problem and resolve!


<h2>Lifecycle Stages</h2>

- SLAs (Service Level Agreements) in osTicket define how quickly different types of issues should be addressed based on their severity. These are essentially rules or policies set up to ensure timely responses and resolutions.


<h3>Ticket Severity</h3>

<h4>Urgent</h4>Tickets marked as "Urgent" are typically the highest priority. These usually involve critical issues that significantly impact operations or customers. SLAs for urgent tickets often include very short response and resolution times to address the problem swiftly.

<h4>High</h4> High-priority tickets still require quick attention but may not be as immediate as urgent ones. They involve important issues that affect productivity or customer satisfaction but don’t have the same level of urgency as critical issues.

<h4>Medium</h4> Medium-priority tickets are less critical than high and urgent ones. These issues need to be resolved in a timely manner but can be addressed after more urgent tickets have been handled.

<h4>Low</h4> Low-priority tickets involve minor issues or requests that do not significantly impact operations. These can be addressed after higher-priority issues and often have the longest response and resolution times.
