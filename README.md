<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles 
- Configure Departments
- Configure Teams 
- Configure Agent (workers) 
- Configure Users (customers)
- Configure SLA
- Configure Health Topics 

<h2>Configuration Steps within osTicket</h2>


<h3> Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Roles.html">Roles</a></h3>
<ul>
<li>Click Admin Panel--> Agents-> Roles</li>
<li>Supreme Admin</li>
</ul>


<p>
  <img width="80%" alt="Screen Shot 2023-09-25 at 11 20 19 PM" src="https://github.com/Wilsielouidor/post-install-config/assets/142513380/19291e92-2f49-49bc-8791-04b766ba1c1d">

</p>



<p>
<img width="80%" alt="Screen Shot 2023-09-25 at 11 40 22 PM" src="https://github.com/Wilsielouidor/post-install-config/assets/142513380/f97d8045-e313-471f-952a-0e1f97d4e9ac">

</p>

<p>
<img width="80%" alt="Screen Shot 2023-09-25 at 11 43 06 PM" src="https://github.com/Wilsielouidor/post-install-config/assets/142513380/2863ca12-6d53-4c28-a0d3-07185fcfc538">


</p>
<br />

<p>
Type in Supreme Admin under Definition tab
</p>

<p>
<img width="80%" alt="Screen Shot 2023-09-25 at 11 46 45 PM" src="https://github.com/Wilsielouidor/post-install-config/assets/142513380/d3209fe4-89fa-4688-a360-13c38f615957">

</p>

Go to Permissions and Check all boxes under Tickets, Tasks and Knowledgebase--> Click Add role on the bottom.

<p> <img width="961" alt="Screen Shot 2023-09-25 at 11 54 09 PM" src="https://github.com/Wilsielouidor/post-install-config/assets/142513380/d2397f0b-1e63-4e7d-ac3e-1c2aae0e9515">

</p>

<h3> Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Roles.html">Departments</a></h3>
<ul> 
<li>Click Admin Panel--> Agents-> Department--> Add new departments</li>
<li>Name: System Administrator-> click create department (which is at the bottom when you scroll done if you don't see it)</li>
</ul>
<p>
<img width="80%" alt="Screen Shot 2023-09-26 at 11 30 50 PM" src="https://github.com/Wilsielouidor/post-install-config/assets/142513380/9f1ce150-e166-4ead-ba98-a9d4f598064b">

</p>
<br />


<h3> Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Teams.html">Teams</a></h3>
<ul>
<li>Click Admin Panel--> Agents-> Teams--> As default there is already a Level I so Add Level II </li>
</ul>
<p>
<img width="80%" alt="Screen Shot 2023-10-02 at 5 18 32 PM" src="https://github.com/Wilsielouidor/post-install-config/assets/142513380/2dca711e-813a-4008-99f4-170603fd7903">


</p>
<br />

<p>
  
<h3>Allow Anyone to Create Tickets</h3>
  <ul>
  <li>Admin panel->settings-> user settings </li>
  <li>Registration required: Recquire registration and login to create tickets </li>
  </ul>
  </p> 
  <br />
  
<p>
<img width="80%" alt="Screen Shot 2023-10-02 at 5 07 38 PM" src="https://github.com/Wilsielouidor/post-install-config/assets/142513380/1e7d0115-e45c-4d0b-8944-0ffcc9bf5853">


</p>

<p>

<h3>Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Agents.html">Agent(Workers)</a></h3>
  <ul>
  <li> Admin Panel->Agents-> Add new </li>
  <li>Mateo do</li>
    <ul> 
    <li>Email address mateo.do@osticket.com </li>
    <li>Create username: mateo.do</li>
    <li>Note: Make sure to uncheck box “require password reset email”</li>
    <li>Under access tab you can add agent to a specific department and role </li>
    <li>Department: System Administrators </li> 
    <li>Role: Supreme Admin</li> 
    <li>Extended access: Support-> Supreme Admin </li> 
    <li>Team: Level II support </li>
    <li>Click Create once your done with this agent </li>
    </ul>
  <li>Millie</li>
    <ul> 
    <li>email address: millie.do@osticket.com </li>
    <li>Create a username  (millie.do) and password </li>
    <li>Note: make sure to uncheck box “require password reset email”</li>
    <li>Under access-> Primary Department: Support, View only </li>
    <li>Extended access: Maintenance-> Limited access</li>
    <li>Click create when your done </li>
</ul>


</ul>
</p>
<p>
<img width="80%" alt="Screen Shot 2023-10-02 at 4 56 01 PM" src="https://github.com/Wilsielouidor/post-install-config/assets/142513380/768ee9e7-2c95-4ef1-8efb-ca31ccbabb3c">


<img width="80%" alt="Screen Shot 2023-10-02 at 4 59 48 PM" src="https://github.com/Wilsielouidor/post-install-config/assets/142513380/ec8decdb-d96d-4ec4-a338-b2a12da41425">

</p>
<br />

<p>

<h3>Configure <a href="https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html">Users (Customers)</a></h3>
  <ul>
  <li> Agent Panel->Users-> Add new </li>
    <ul>
     <li>Karen Doe</li>
      -Email Address: Karen@osticket.com ->Add Full Name-> Click Add User
    <li>Ken Doe</li>
      -Email Address: Ken@osticket.com-> Add Full Name-> Click Add User 
    </ul>
</ul>
</p>
<p>
  <img width="80%" alt="Screen Shot 2023-10-02 at 6 47 13 PM" src="https://github.com/Wilsielouidor/post-install-config/assets/142513380/6be11bc3-41e1-494a-a1c4-c95a6d8e6cdc">
</p>
<p>
<img width="80%" alt="Screen Shot 2023-10-02 at 6 45 21 PM" src="https://github.com/Wilsielouidor/post-install-config/assets/142513380/c2c98828-a431-4cd2-9b6a-0f6cd9616cca">

</p>
<br />

<p>

<h3>Configure <a href="https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html">SLA</a></h3>
<ul>
  <li> Admin Panel-> Manage-> SLA </li>
  <li>Sev-A (Grace period: 1 hour, Schedule: 24/7)</li>
  <li>Sev-B (Grace Period: 4 hours, Schedule: 24/7)</li>
  <li>Sev C (Grace Period: 8 hours, Schedule: Business hours) </li>
</ul>

<p>
<img width="80%" alt="Screen Shot 2023-10-02 at 5 50 12 PM" src="https://github.com/Wilsielouidor/post-install-config/assets/142513380/6925d09f-4b97-4a34-bdbe-fc216fbf7bdf"> 
</p>

<p>

<img width="80%" alt="Screen Shot 2023-10-02 at 6 03 13 PM" src="https://github.com/Wilsielouidor/post-install-config/assets/142513380/a238248c-c946-41fe-8bd8-f4a3b0ef13f2">

</p>
  
<h3>Configure Help Topics</a></h3>
<ul>
  <li> Admin Panel -> Manage -> Help Topics-> Add New Help topics-> Type in each topic individually that is listed Below</li>

<li> Business Critical Outage</li>
<li>Personal Computer Issues</li>
<li>Equipment Request</li>
<li>Password Related Issues</li>

</ul>

<p><img width="80%" alt="Screen Shot 2023-10-02 at 6 58 22 PM" src="https://github.com/Wilsielouidor/post-install-config/assets/142513380/15de241a-6d94-4a57-9b5c-a834bd312f8b">

</p>

<p><img width="80%" alt="Screen Shot 2023-10-02 at 7 04 22 PM" src="https://github.com/Wilsielouidor/post-install-config/assets/142513380/eaae1e10-8ad4-41a3-aa98-5c3745ed5f1e">
</p>

<br />

<p><img width="80%" alt="Screen Shot 2023-10-02 at 7 13 30 PM" src="https://github.com/Wilsielouidor/post-install-config/assets/142513380/06c2ebb2-abac-4e11-aca9-658fbb37d4e3">
</p>
