<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Deploying Fine Grained Pswd Policies</h1>
This tutorial outlines the implementation of deploying fine grained pswd policies with with group policy in Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploying Fine Grained Pswd Policies](https://youtu.be/cG7M3Z-Cek4)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services

  

<h2>Operating Systems Used </h2>

- Windows Server 2022

<h2>High-Level Deployment and Configuration Steps</h2>

- Create a security group and add member to the group
- Using ADSI Edit to set password setting cainter
- Using PowerShell to verify changes


<h2>Deployment and Configuration Steps</h2>

<p>



</p>
<p>
Diagram
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/962a1fba-aa60-4e62-b84b-51a39d812355" height="80%" width="80%""/>
<img src="https://github.com/user-attachments/assets/b6cfff32-ae38-4d13-8a42-35976bfd1bdb" height="80%" width="80%""/>
<img src="https://github.com/user-attachments/assets/b1adc27c-b71d-4079-a9a2-fce06efce53f" height="80%" width="80%""/>

</p>
<p>
In my Default Domain Policy, I was able to make Password Policy changes to enforcing password history, Min pswd age, min pswd length, and pswd meet complexity.
</p>
<br />


<p>
 <img src="https://github.com/user-attachments/assets/03c8b628-0414-4066-b075-0e075ffb9ceb" height="80%" width="80%""/>
  <img src="https://github.com/user-attachments/assets/1d067147-fb2d-49c4-8ffe-41e7c591aaea" height="80%" width="80%""/>
<img src="https://github.com/user-attachments/assets/739a5e45-5c4c-401a-9926-8ffda7ba7b9f" height="80%" width="80%""/>

</p>
<p>On Account Lockout Policy, I was able to make changes to account lockout duration, account lockout threshold ,and reset account counter.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/84c8b40c-a464-4221-a9e1-21b1f92c0882" height="80%" width="80%""/>
 <img src="https://github.com/user-attachments/assets/04b2af17-5ff1-4c4a-ba42-ea49040d1a28" height="80%" width="80%""/>
 <img src="https://github.com/user-attachments/assets/79b32517-7207-4559-9e26-8079eb12d0f9" height="80%" width="80%""/>
 <img src="https://github.com/user-attachments/assets/9dbbe008-e1bd-4c93-a05b-2f41a0384bdd" height="80%" width="80%""/>
  <img src="https://github.com/user-attachments/assets/d7f7ffbb-652c-49a6-94b9-9562780f09b0" height="80%" width="80%""/>
   <img src="https://github.com/user-attachments/assets/0d774c5d-0e57-4584-a443-ec05ed80eeb2" height="80%" width="80%""/>
 <img src="https://github.com/user-attachments/assets/2315b7af-1553-434b-83bd-a2dfb919bca0" height="80%" width="80%""/>
<img src="https://github.com/user-attachments/assets/874421b2-2d9f-4190-9c3e-9354e311c63a" height="80%" width="80%""/>
  <img src="https://github.com/user-attachments/assets/9390ea91-9307-4865-9ffb-abdeabac30e6" height="80%" width="80%""/>
  <img src="https://github.com/user-attachments/assets/81d98b20-4eb4-4d57-a45c-3f47c3973205" height="80%" width="80%""/>
  <img src="https://github.com/user-attachments/assets/d1c0eb2c-1b65-41c5-9a49-14f00171507f" height="80%" width="80%""/>
  <img src="https://github.com/user-attachments/assets/b7ee9b08-9ae7-4974-ab3b-91b1f9d98c14" height="80%" width="80%""/>
  <img src="https://github.com/user-attachments/assets/4cfd3ab0-38c5-4ff5-ad32-ae39017abe1d" height="80%" width="80%""/>
</p>


