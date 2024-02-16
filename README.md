<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1> Active Directory: Practical Scenario Simulation </h1>


<p>Welcome to the "Active Directory: Practical Scenario Simulation" project. In this project, we'll simulate various scenarios to enhance our understanding of user provisioning, administration, and problem-solving within Active Directory.</p>

<h2>Prerequisites</h2>

- Building the Foundation: Preliminary Setup for Active Directory and Network Traffic Analysis between Azure VMs
- Active Directory Deployment and Configuration
- Active Directory: User Creation

<h2>Key Objectives</h2>

<h4>Scenario Simulation</h4>

- Engage in practical simulations of diverse scenarios, such as password resets, group membership changes, and account deactivations.

<h4>Troubleshooting Scenarios</h4>

- Develop troubleshooting skills by simulating scenarios where users encounter access issues, and learn to identify and resolve these challenges effectively.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Active Directory Domain Services

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)



<h1>Scenarios</h1>

<h3>&#9312; User Account Creation </h3>

<h4>Background:</h4>

<p>A new software developer, John Smith, has been hired to join the IT department at your company. As part of the onboarding process, the IT help desk needs to create a new user account for John in Active Directory.</p>

<p><strong>First create a new user account named "John Smith" with the username "john_smith" and a temporary password.</strong></p>

<img width="324" alt="john smith" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/1a695e10-9cb3-4013-bd48-0ed2b9f3c31d">

<p><strong>NOTE: Set the account to require a password change at the next login.</strong></p>


<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong> Assign John to the "Developers" security group in Active Directory.</strong></p>

<img width="340" alt="developers" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/a1f6ef6a-5c02-41c5-a331-eddde3b2e0f0">

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<p><strong>Then ensure that John's account is located in the appropriate Organizational Unit (OU) for IT staff.</strong></p>

<img width="340" alt="check" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/3344b604-0705-45d7-8e22-90fc583bf55a">

<br>
<br>

- Communicate the login credentials and temporary password to John through a secure channel.
- Document the date and time of account creation for auditing purposes.
  
<h4>Considerations:</h4>

- The temporary password should meet the company's password policy requirements.
- Ensure that John has the necessary permissions and group memberships to access the resources required for his role.

<h3>&#9313; Password Reset </h3>

<h4>Background:</h4>

<p> Sarah Thompson, a marketing executive, contacts the IT help desk reporting that she has forgotten her password and is unable to access her computer and email. The help desk needs to assist Sarah in resetting her password in Active Directory.</p>

<p><strong> Locate Sarah's user account and initiate a password reset.</strong></p>

<img width="383" alt="reset password" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/c74f2c28-6fd8-4d3e-b3ed-7e16d14d1364">


<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Set a temporary password for Sarah that complies with the company's password policy.</strong></p>

<img width="383" alt="enable acc" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/85e43120-0d23-4cb8-a8e2-6e64005a7303">

<p><strong>NOTE: Make sure to click the highlighted boxes to ensure the user’s account is unlocked and enable them to set their own password. </strong></p>

- Communicate the temporary password to Sarah through a secure channel and instruct her to change it immediately upon login.
- Provide guidance on how to change the password using the company's self-service password reset tool if available.
- Document the date and time of account creation for auditing purposes.

<h4>Considerations:</h4>

- Ensure that the chosen temporary password is strong and complies with the company's password policy.
- Remind Sarah to update the password on any additional devices or applications where the old password was saved.

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3>&#9314; Group Membership Update </h3>

<h4>Background:</h4>

<p>Emma Rodriguez, a systems analyst, has recently been promoted to a managerial role within the IT department. As part of her new responsibilities, Emma now requires access to specific network resources and project folders. The IT help desk needs to update Emma's group memberships in Active Directory accordingly.</p>

<p><strong>Locate Emma's user account and review her current group memberships.</strong></p>

<img width="304" alt="Emma " src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/e0f15108-dcdb-477d-8de4-5f3747e5ea07">

<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Remove Emma from the "Systems Analysts" group and add her to the "IT Managers" group.</strong></p>

<img width="303" alt="IT managers" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/5120932a-c9de-45d9-9419-383bf839bbc4">

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<p><strong>Confirm that Emma now has the necessary access rights to project folders and relevant network resources.</strong></p>

<img width="600" alt="image" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/aadea113-c15b-4135-93d8-8b4ebf48de04">


- Communicate the group membership update to Emma, along with any additional instructions or changes in access.
- Document the whole process


<h4>Considerations:</h4>

- Ensure that Emma's new group memberships align with her managerial responsibilities.
- Communicate the changes to other relevant parties, such as the IT security team, to maintain awareness.
- Verify that Emma's access permissions are correctly configured after the group membership update.

<h3>&#9315; Account Deactivation </h3>

<h4>Background:</h4>

<p>Mark Johnson, a network administrator, has recently resigned from the company. The IT help desk needs to deactivate Mark's user account in Active Directory to prevent unauthorized access and ensure the security of company resources.</p>

<p><strong>Locate Mark's user account and initiate the account deactivation process.</strong></p>

<img width="421" alt="makr" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/0a51e96b-9dce-4bf6-a22f-92943f6e8a20">

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<p><strong>Disable Mark's account to prevent further logins while retaining the account details for reference.</strong></p>

<img width="470" alt="disable" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/da07b6af-1ba3-467a-b0a0-8109afc37bfb">

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<p><strong>You may receive a confirmation dialog; click "Yes" to confirm the disabling of the user account.</strong></p>

<img width="223" alt="disable 2" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/5b5bdfe6-996d-4ff3-8201-4cd9549bdd46">

<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Remove Mark from all security groups to revoke his access to network resources.</strong></p>

<img width="295" alt="remove mark" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/1613e604-3e4c-462f-8c30-ea0dd7fed0bf">

<br>
<br>

<p><strong> Confirm with other relevant departments (e.g., HR) that Mark's departure aligns with company policies and document the whole process.</strong></p>

<h4>Considerations:</h4>

- Ensure a smooth transition of Mark's responsibilities to other team members.

-  Communicate the account deactivation to other departments, such as HR and security, for coordinated efforts.

-  Retain Mark's user account details for historical records and potential future reference.
   
-  Conduct a review of Mark's access rights to identify and update any shared resources associated with his account.

<h3>&#9316; Organizational Unit (OU) Management </h3>

<h4>Background:</h4>

<p>The Sales department has recently undergone a reorganization, resulting in the creation of a new team focused on international sales. The IT help desk needs to reflect this change in the Active Directory structure by creating a new Organizational Unit (OU) for the International Sales team and moving relevant user accounts into the new OU.
</p>

<p><strong>Create a new Organizational Unit named "International Sales" within the Sales department's organizational structure.</strong></p>

<img width="323" alt="International Sales" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/19db8909-74bf-4e02-8b5d-353bce7818ee">

<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Move the user accounts of team members, such as Alex Turner and Maria Sanchez, to the newly created OU.</strong></p>

<img width="307" alt="Alex Turner to IS " src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/ff044b9d-17ee-4b8d-8b40-0f55dff95070">

<img width="305" alt="Maria to IS" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/641b24cb-156c-4a32-8edd-bc9041ca3741">

<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong> Verify that the users now appear under the "International Sales" OU in Active Directory.
</strong></p>

<img width="296" alt="Verify" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/8c4884d1-e16a-48a6-a492-6cc12f6e91e8">

<br>
<br>

<p><strong>Communicate the organizational change to relevant stakeholders, such as department heads and team leaders.
</strong></p>

<h4>Considerations:</h4>

- Ensure that the new OU structure aligns with the company's organizational hierarchy.

- Confirm that the appropriate Group Policy settings apply to the users within the new OU.
  
- Communicate any changes in access permissions or policies resulting from the OU reorganization to the IT security team.



<h2> Final Thoughts </h2>

<p>
In summary, Active Directory is crucial for managing user accounts and network resources. The scenarios provided cover common IT help desk tasks, such as creating user accounts, resetting passwords, updating group memberships, and handling account deactivation. These scenarios serve as practical exercises for training IT personnel and highlight the importance of Active Directory in maintaining a secure and organized digital environment. </p>








