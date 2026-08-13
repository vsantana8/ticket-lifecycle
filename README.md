<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution (EXAMPLE 1)</h1>
Here is my first example outlining the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- osTicket System

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Synopsis</h2>

In this scenario, user, Karen, will submit a ticket for an issue. John from IT will receive this ticket, update the ticket's urgency, SLA, and more based on the information provided. Then, John will assign to Jane, another IT agent.

<h2>Setting the Stage</h2>
Below are the steps I used to set the stage prior to moving forward with my first example scenario.
My Steps while working on Mac mini machine~

1. Open Chrome browser>visit Microsoft Azure portal (portal.azure.com)>log in.
2. On Azure>Click on Virtual Machines.
3. Click on my Windows 10 22H2 system I created previously and named Ticket System-vm, and click "Start".
4. Return to Mac dashboard and open Remote Desktop application.
5. On Remote Desktop>Click on my virtual machine, Ticket System-vm and log in.
6. Open 2 windows of Chrome browser.
7. In the first browser, (Browser 1) visit the osTicket portal by entering "localhost/osTicket/scp/login.php" in the search and the "return" key
<img width="1367" height="755" alt="image" src="https://github.com/user-attachments/assets/4c0551b5-1e48-452d-944b-90d05965fb32" />

<h>Lifecycle Stages</h2>

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
19. Update Department by hovering over "Support" status and click it.  Department > drop down > to "SysAdmins" > click Transfer.

<img width="1364" height="1006" alt="image" src="https://github.com/user-attachments/assets/aa696af7-a8ff-4492-a8e7-778f8580c5c9" />
<img width="1366" height="1008" alt="image" src="https://github.com/user-attachments/assets/b1b65a18-8315-4b79-a94e-570d59c9ab35" />
<img width="640" height="281" alt="image" src="https://github.com/user-attachments/assets/5b61374a-5662-4c35-b0ed-b55c3140e8a3" />
<img width="1366" height="1008" alt="image" src="https://github.com/user-attachments/assets/1100c1d3-b2fc-4e30-bafe-4aaed68e179c" />
<img width="640" height="272" alt="image" src="https://github.com/user-attachments/assets/e781a1b0-fb14-4eff-8adc-3141b22d04c4" />

21. Sign out of OsTicket System.
22. Sign back in as agent, Jane. Click on the open ticket from user, Karen.

<img width="1367" height="755" alt="image" src="https://github.com/user-attachments/assets/fe8db461-4621-4d6f-a50d-90b87ae39701" />

<img width="1363" height="762" alt="image" src="https://github.com/user-attachments/assets/7c682104-ee39-417d-bfb1-377896891c3c" />

23. After some investigation for the root cause, add a note of the conclusion in blank field. Click "Post reply."
24. After trial and error, add another note providing an update in blank field. Click "Post reply." 

<img width="1383" height="1004" alt="image" src="https://github.com/user-attachments/assets/0ff335aa-37af-4e05-a734-1717bc2e6230" />
<img width="1368" height="1043" alt="image" src="https://github.com/user-attachments/assets/79673d54-16a8-40b6-a48e-b10400eee36c" />
<img width="1368" height="1043" alt="image" src="https://github.com/user-attachments/assets/b2f14c84-9c2b-4ae8-a9a2-595f1b182877" />

25. Update ticket status by hovering over "Open" and click it. > Ticket status > drop down > "Resolved" > Add reason > click close.
26. Ticket will disappear from "Open" tickets. It's completed.

<img width="1137" height="577" alt="image" src="https://github.com/user-attachments/assets/dca19966-4dd8-46d4-8e8c-7553c9744d45" />
<img width="1137" height="577" alt="image" src="https://github.com/user-attachments/assets/72b52652-148c-4eb7-8132-29561934f68f" />
<img width="639" height="215" alt="image" src="https://github.com/user-attachments/assets/740417ef-7ce1-47f9-a497-4068fe3bba75" />
<img width="1377" height="532" alt="image" src="https://github.com/user-attachments/assets/9e5ad30d-56f5-4c1b-8664-842c5581abc3" />


<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution (EXAMPLE 2)</h1>
Here is my second example outlining the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies & Operating Systems Used are the SAME as above.</h2>

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
7. In the first browser, (Browser 1) visit the osTicket portal by entering "localhost/osTicket/scp/login.php" in the search and the "return" key
<img width="1367" height="755" alt="image" src="https://github.com/user-attachments/assets/4c0551b5-1e48-452d-944b-90d05965fb32" />

8. In the second browser, (Browser 2) visit the Support Center to submit a ticket by entering "localhost/osTicket". Then, submit a ticket as user, Ken: Click "Open Ticket" >filled in the blanks> Click "Create".

<img width="1523" height="940" alt="image" src="https://github.com/user-attachments/assets/5ce471b4-3990-4bba-9b10-49b72f03cd14" />


9. Go to Browser 1, sign in as agent, John, who will work this ticket. Click on open ticket > review ticket > contact end user, Ken, for more information. Add note in blank field > "Post Reply". 
<img width="1537" height="888" alt="image" src="https://github.com/user-attachments/assets/db95f72a-fc32-44d0-bc5c-cf974d28bf63" />
<img width="1533" height="745" alt="image" src="https://github.com/user-attachments/assets/f6a023f7-ccba-423c-9e90-26e659e424f6" />
<img width="1528" height="933" alt="image" src="https://github.com/user-attachments/assets/9ae9db65-c2e3-417e-a3e4-bbc6246f222a" />
<img width="1494" height="968" alt="image" src="https://github.com/user-attachments/assets/96d7c173-381a-4d73-be08-556058c6599f" />

10. Update Priority Level to "High." Hover mouse over "Normal" > Click it > drop down > "High" > Update.
<img width="494" height="195" alt="image" src="https://github.com/user-attachments/assets/0db12f71-4880-4a58-9c87-827d54df00e4" />

11. Update SLA Plan by hovering over "Default SLA" > Click it > drop down > Select "Sev-B" > Add note > Update.
    
<img width="1547" height="702" alt="image" src="https://github.com/user-attachments/assets/e008a29e-46b2-41ef-9683-b01b0d6ee543" />
13. <img width="487" height="189" alt="image" src="https://github.com/user-attachments/assets/6b2b8637-aa82-411f-bfa5-500c5205dbb8" />

12. Reached out to Desktop Admins, connected with Josh, and received more information regarding Adobe Reader and posted an update in the ticket. > Add note in blank field > "Post Reply."
13. Relayed information to Ken. After a conversation with Ken, learned the software is working from catalog now. Add note in blank field > "Post Reply."
14. Update Ticket Status from "Open" to "Closed" > Add note > Close.
15. Open ticket will disappear from "Open" list.

<img width="930" height="470" alt="image" src="https://github.com/user-attachments/assets/fafa2164-a8c7-4b71-a993-d5ba03fbe639" />
<img width="1126" height="512" alt="image" src="https://github.com/user-attachments/assets/e7196662-f9df-478e-8103-f44d291887cc" />
<img width="1509" height="933" alt="image" src="https://github.com/user-attachments/assets/29ebb907-c87b-4e14-aeea-f3d099aa2282" />
<img width="1418" height="573" alt="image" src="https://github.com/user-attachments/assets/2dc02d77-a770-420d-ba0d-305d9e14a839" />
<img width="578" height="196" alt="image" src="https://github.com/user-attachments/assets/da5bb73c-1a8e-422d-b727-8c17a36f89f0" />
<img width="1477" height="552" alt="image" src="https://github.com/user-attachments/assets/0f4ebedf-1d13-4403-9a02-886231d455dd" />



<p>

</p>
<p>
<p>
</p>
<p>
</p>
<br />
