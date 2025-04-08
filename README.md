<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Installation Arrangements</h1>
This lesson demonstrates the subsequent arrangement steps necessary for the osTicket help desk platform.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure's Virtual Machine Platform
- Microsoft Windows App
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Formatting Goals</h2>

- Arrangement of Roles
- Arrangement of Departments
- Arrangement of Teams
- Arrangement of Agents (Employees)
- Arrangement of Users (Customers)
- Arrangement of Service Level Agreement (SLA)
- Arrangement of Help Topics 

<h2>Formation Steps</h2>

<p>
<img width="1118" alt="Screenshot 2025-03-29 at 3 12 46 PM" src="https://github.com/user-attachments/assets/aa5d0fe0-0ac0-4e2d-8bfb-eab37fbe1ac4" />
</p>
<p>
Now that I have completed the osTicket installation, I began the process of establishing each necessary arrangement within the network. The first of which was making an administrative role under the "Roles" section. I therefore signed into my administrator account into osTicket. I then double-clicked on "Admin Panel" > clicked on "Agents," > "Add New Role," > and then entered the title "Supreme Admin." From there, I gave the said account complete authorization for "Permissions," including for "Tickets," "Tasks," and "Knowledgebase."
</p>
<br />

<p>
<img width="1099" alt="Screenshot 2025-03-29 at 3 25 23 PM" src="https://github.com/user-attachments/assets/781dcaa7-d37a-4349-80ab-2f07fdf971fa" />

</p>
<p>
Following the arrangement of "Roles," I continued forward with the "Departments" stage. I created another department, in addition to "Maintainence" and "Support," for the special use of the "Supreme Admin" role. This particular department was also established in the "Top-Level Department" category.
</p>
<br />

<p>
<img width="1099" alt="Screenshot 2025-03-29 at 3 53 18 PM" src="https://github.com/user-attachments/assets/d419849a-2eff-4b3b-8f40-6f1a520ccfdf" />

</p>
<p>
The third arrangement in this post-installation started with the development of "Teams." At this stage, I clicked on "Agent" > "Teams" > and then "Add New Team." I named the group, for the purpose of this exercise, "Online Banking" with one administrative member at this point in its construction.
  
</p>
<p>
<img width="1099" alt="Screenshot 2025-03-29 at 4 14 11 PM" src="https://github.com/user-attachments/assets/13add156-b2fe-46e0-96cf-e68d067e6dc5" />

</p>
<p>
Having laid the foundation with "Roles," "Departments," and "Teams," I made two separate agents or employees with differing access levels and differing departments. The first agent account  was for "Jane Doe." The second account was for "John Doe." I gave Jane's account access to the "Supreme Admin" role, the "SysAdmin" department, and to the "Online Banking" team. In regards to John Doe, on the other hand, I only gave his account limited access with the "Support" department and with "read-only" privileges.
</p>
<p>
<img width="1099" alt="Screenshot 2025-03-31 at 1 57 29 PM" src="https://github.com/user-attachments/assets/d6fb0ee0-c521-46e7-aec4-2d2f8549f900" />
</p>
<p>
The next stage in my osTicket arrangement was the creation of "User" or customer accounts. I made one by the name of Karen, and another one by the name of Ken. Each one of them received "Guest" level status with their respective emails and usernames. I did this by simply clicking on "Agent Panel" > "Users" > and then "Add New." From there, I established their accounts by filling out their respective information into the required fields.
</p>
<p>
<img width="1099" alt="Screenshot 2025-03-31 at 2 38 21 PM" src="https://github.com/user-attachments/assets/735ffd71-ba5b-4c59-af3f-f4927b763eb8" />
</p>
<p>
The sixth arrangement step revolved around the establishment and management of Service Level Agreements (SLAs). I started by clicking on "Admin Panel" > "Manage" > and then "SLA." At this point, I clicked on "Add New SLA Plan" and created three different severity levels for sorting any incoming tickets. I named the first and most severe level, "Sev-A." It had a grace period of 1 hour and a schedule of 24/7. I named the second and intermediate level, "Sev-B." It had a grace period of a maximum of 4 hours and a schedule of 24/7. I named the last and least severe level, "Sev-C." This plan had a grace period of 8 hours, and a schedule consisting of Monday through Friday, 8am to 5pm with the inclusion of U.S. holidays.
</p>
<p>
  <img width="1099" alt="Screenshot 2025-03-31 at 2 55 05 PM" src="https://github.com/user-attachments/assets/f6ab7402-f58a-4c64-80d9-3e20010e48bc" />
</p>
<p>
With all of the prior post-install steps completed, I concluded the process by creating osTicket "Help Topics." I began by clicking on "Admin Panel" > "Manage" > "Help Topics" > and then "Add New Help Topic." I then outlined 5 additional help topics to aid users in creating their tickets. I further classified them with these titles: "Business Critical Outage" with the parent topic of "Report a Problem;" "Personal Computer Issues" with the parent topic of "Report a Problem;" "Equipment Request" with the parent topic of "General Inquiry;" "Password Reset" with the parent topic of "Report a Problem;" and lastly, "Other" with the parent topic of "General Inquiry."
<p>
<br />
