<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
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
Type in Supreme  Admin under Definition tab
</p>

<p>
<img width="80%" alt="Screen Shot 2023-09-25 at 11 46 45 PM" src="https://github.com/Wilsielouidor/post-install-config/assets/142513380/d3209fe4-89fa-4688-a360-13c38f615957">

</p>

Go to Permisions and Check all boxes under Tickets, Tasks and Knowledgebase--> Click Add role on the bottom.

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
<img width="80%" alt="img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps">

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
<img width="60%" alt="Screen Shot 2023-09-27 at 11 03 58 PM" src="https://github.com/Wilsielouidor/post-install-config/assets/142513380/2fec58cf-636e-41e0-99a7-078f1b587ff8">

</p>

<p>

<h3>Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Agents.html">Agent(Workers)</a></h3>
  <ul>
  <li> Admin Panel->Agents-> Add new </li>
  <li>Karen, Ken, Lisa, Mateo</li>
</ul>
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>

<h3>Configure <a href="https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html">Users (Customers)</a></h3>
  <ul>
  <li> Agent Panel->Users-> Add new </li>
     <li>Karen Doe</li>
      -Email Address: Karen@osticket.com ->Add Full Name-> Click Add User
</ul>
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>

<h3>Configure <a href="https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html">SLA</a></h3>
<ul>
  <li> Admin Panel-> Manage-> SLA </li>
  <li>Sev-A (1 hour, 24/7)</li>
  <li>Sev-B (4 hours, 24/7)</li>
  <li>Sev C (2 hours, business hours) </li>
</ul>
<p>


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
  
<h3>Configure Help Topics</a></h3>
<ul>
<li> Business Critical Outage </li>
<li>Personal Computer Issues</li>
<li>Equipment Request</li>
<li>Password Reset</li>

</ul>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
