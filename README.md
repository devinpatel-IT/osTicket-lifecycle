# osTicket-lifecycle

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- osTicket (Enterprise Ticketing System Platform)
- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Internet Information Services (IIS)


<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> ()

<h2>Lifestyle Stages</h2>

- Three different tickets will be examined with corresponding resolution process.
- Intake
- Communication
- Resolution


<h2>INTAKE</h2>

_<b>3 different tickets have been submitted and are in queue!</b>_

<p>

<img width="1210" height="525" alt="Screenshot 2025-08-05 163756" src="https://github.com/user-attachments/assets/3f868d40-bc73-4105-af18-2722fea8c2c8" />

</p>

<br/>

<h2>TICKET 711979 - ONLINE BANKING SYSTEM OUTAGE</h2>

<p>
<img width="1096" height="1191" alt="Screenshot 2025-08-05 163936" src="https://github.com/user-attachments/assets/31b32e2c-0777-4866-a742-38ad6cf081e8" />
</p>

_<strong>EXPLANATION OF TICKET LIFECYCLE:</span></strong>_

<p>
1.) The ticket was created by User 1 and they explained that the online banking system is not 
    working properly.

2.) Agent two received the ticket at the help desk and updated the SLA level from
    default to Severity level A, indicating that the issue is crticial to business operations     and must be resolved within one hour.

3.) Agent Two then changes the priority level from Normal to Emergency and assigns the ticket     to the Online Banking team, which is appropriate team for critical Online Banking related     issues. 

4.) Agent One, who is a memeber of the online banking team claims the ticket. The report that
    a recent update may have cause these issues.

5.) Agent One works on rolling back the updates and fixes the issue

6.) The issue has been resolved and the ticket is closed.

</p>

<br />

_<b>2. ESTABLISHED TEAMS (explanation below)</b>_

<p>
<img width="1112" height="421" alt="Screenshot 2025-08-05 164236" src="https://github.com/user-attachments/assets/89db05df-6540-4a28-921d-03485a471e2c" />
</p>

_<strong>1. Level 1 suppport team</span></strong>_

<p>
Purpose:
The Level 1 Support Team acts as the first line of defense for all incoming support tickets. They handle common issues, provide general assistance, and triage requests before escalation.

Key Responsibilities:
Receive and respond to initial customer inquiries or issues.

Perform basic troubleshooting for banking services (e.g., login issues, account access problems).

Categorize, prioritize, and document tickets clearly.

Resolve low-complexity issues or known problems using standard procedures.

Escalate complex or specialized cases to the appropriate teams (e.g., Online Banking Team, IT, or Level 2 support).

Monitor open tickets to ensure timely responses and customer satisfaction.

Ticket Examples:
Password reset requests

Unable to access mobile/online banking

Incorrect account balances displayed

Help navigating the banking portal

_<strong>2. Online Banking Team</span></strong>_

Purpose:
The Online Banking Team is a specialized technical group that manages and supports issues specifically related to the bank’s online banking platform. They are responsible for maintaining a secure, functional, and reliable user experience across the digital banking ecosystem.

Key Responsibilities:
Handle tickets escalated from Level 1 involving online banking functionality.

Investigate and resolve platform-specific bugs or outages.

Support backend operations of mobile apps, internet banking, and digital account services.

Coordinate with developers, cybersecurity teams, and infrastructure teams as needed.

Test and validate fixes for reported issues before deployment.

Provide feedback and documentation to help the Level 1 team better resolve recurring issues.

Ticket Examples:
Failed funds transfer through online banking

Online bill payment issues

Errors during account registration via the website/app

MFA (multi-factor authentication) not functioning properly

Security concerns or suspicious online activity

Workflow Summary
Customers submit tickets through web/app/phone.

Level 1 Support Team triages and resolves simple/general issues.

Tickets requiring technical investigation or platform expertise are escalated to the Online Banking Team.


</p>
<br />

_<b>2. CREATE SAMPLE USERS </b>_

<img width="1110" height="476" alt="Screenshot 2025-08-05 164357" src="https://github.com/user-attachments/assets/bcfbd1ec-abc7-44b7-b913-0bd391e78434" />

<p>These are employees that will submit tickets to the help desk</p>

<br/> 

_<b>2. CREATE SAMPLE AGENTS </b>_

<img width="1137" height="479" alt="Screenshot 2025-08-05 164224" src="https://github.com/user-attachments/assets/383d3034-3ddd-4ac7-a9b1-c92af8ec6845" />

<p>These are help desk employees that will triage tickets</p>

<br/>

Please continue to next repository to view ticketing system lifecycle.
[osTicket Lifecycle](https://github.com/devinpatel-osTicket-lifecycle) 


