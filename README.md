<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution (EXAMPLE 1)</h1>
Here is my first example outlining the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

My Steps while working on Mac mini machine~

1. Open Chrome browser>visit Microsoft Azure portal (portal.azure.com)>log in.
2. On Azure>Click on Virtual Machines.
3. Click on my Windows 10 22H2 system I created previously and named Ticket System-vm, and click "Start".
4. Return to Mac dashboard and open the Remote Desktop application.
5. On Remote Desktop>Click on my virtual machine, Ticket System-vm and log in.
6. Open 2 windows of Chrome browser.
7. In the first browser, (Browser 1) visit the osTicket portal by entering "localhost/osTicket/scp/login.php" in the search and the "return" key.
<img width="1086" height="1003" alt="image" src="https://github.com/user-attachments/assets/df8170db-5b98-4b25-8912-c39091fa2407" />
8. In the second browser, (Browser 2) visit the Support Center to submit a ticket by entering "localhost/osTicket". Then, submit a ticket as user, Karen: Click "Open Ticket" >filled in the blanks> Click "Create".
<p>
<img width="1330" height="633" alt="image" src="https://github.com/user-attachments/assets/c6ab9794-85d0-47af-8305-c75d2750bc82" />
<img width="1326" height="959" alt="image" src="https://github.com/user-attachments/assets/8eb00c9b-1ecf-4485-9330-419c9405444a" />
</p>
<p>

  The following steps will be solely on Browser 1.
  
9. Browser 1> osTicket portal> log in as agent, John. See open ticket from user, Karen.
</p>
<br />
<img width="1366" height="1008" alt="Screenshot 2026-08-11 at 10 01 23 PM" src="https://github.com/user-attachments/assets/bbf75bc1-a233-4eab-8a15-c46f8175e6c3" />

<img width="1371" height="923" alt="image" src="https://github.com/user-attachments/assets/7c479983-e02e-4494-b659-b98b668cdfd8" />

10. Browser 1> Click on ticket and review notes from user, Karen.
<img width="1369" height="1005" alt="image" src="https://github.com/user-attachments/assets/3c0592ce-b9c1-4b4f-8ac7-3669c58a1e35" />

11. Scroll up and update the Priority status to Emergency by hovering over "Normal" and clicking it.
12. Priority Level > drop down > to "Emergency." Add reason.
    <img width="645" height="265" alt="image" src="https://github.com/user-attachments/assets/f1235a96-718a-4518-851f-503ca10d0f6b" />
    <img width="1372" height="1007" alt="image" src="https://github.com/user-attachments/assets/2dfa24d2-ccd7-4bc6-8c86-5e9a41129f84" />

13. Update SLA by hovering over SLA status "Normal" and clicking it.
14. SLA> drop down > to "Sev-A." Sev-A is chosen for the highest priority. Add reason.

<img width="646" height="248" alt="image" src="https://github.com/user-attachments/assets/0e9a51cf-ca3c-45de-8055-8a8be2cee693" />
<img width="637" height="236" alt="image" src="https://github.com/user-attachments/assets/f0720cf6-5883-4119-a6f0-9d2d9982ec75" />

15. Update Help Topic by hovering over Help Topic status "General Inquiry / Other".
16. Help Topic > drop down > to "Business Critical Outage," which applies more to the ticket subject matter and issue rather than a general inquiry.
<img width="1363" height="1003" alt="image" src="https://github.com/user-attachments/assets/7ddbb3da-cee5-4852-906b-9c26c7b560f3" />
<img width="638" height="315" alt="image" src="https://github.com/user-attachments/assets/05d0452a-bd78-49f9-871a-ec47895769bf" />
<img width="641" height="244" alt="image" src="https://github.com/user-attachments/assets/e6b10695-01e3-4e9d-9a6f-b45eba371f27" />

17. Add escalation note to ticket history in blank field > click "Post Reply".
18. Assign task to agent, Jane. Go to Assigned To and hover over "Unassigned" and click it. > Assignee > drop down > Jane > Assign.
19. Update Department by hovering over "Support" status and click it.
20. Department > drop down > to "SysAdmins" > click Transfer.

<img width="1364" height="1006" alt="image" src="https://github.com/user-attachments/assets/aa696af7-a8ff-4492-a8e7-778f8580c5c9" />
<img width="1366" height="1008" alt="image" src="https://github.com/user-attachments/assets/b1b65a18-8315-4b79-a94e-570d59c9ab35" />
<img width="640" height="281" alt="image" src="https://github.com/user-attachments/assets/5b61374a-5662-4c35-b0ed-b55c3140e8a3" />
<img width="1366" height="1008" alt="image" src="https://github.com/user-attachments/assets/1100c1d3-b2fc-4e30-bafe-4aaed68e179c" />
<img width="640" height="272" alt="image" src="https://github.com/user-attachments/assets/e781a1b0-fb14-4eff-8adc-3141b22d04c4" />

21. Sign out of OsTicket System.
22. Sign back in as agent, Jane.


UP TO HERE********************************************

<p>
</p>
<p>
</p>
<br />
