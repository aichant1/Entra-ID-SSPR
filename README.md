<h1>Microsoft Entra ID – Self-Service Password Reset (SSPR) Configuration and Testing</h1>


<h2>Description</h2>
This lab simulates a real world identity management scenario where an administrator configures Microsoft Entra ID Self-Service Password Reset (SSPR) to allow users to securely reset their passwords without help desk intervention.
<br />


<h2>Environments Used</h2>

- <b>Microsoft Entra ID (formerly Azure AD)
- Microsoft Entra Admin Center
- Web Browser (Cloud-based configuration)
- Cloud-only user account (test account)</b>

<h2>Key Tasks Performed</h2>

Navigated Microsoft Entra Admin Center

Created a new cloud-only user

Configured Self-Service Password Reset (SSPR) policy

Defined required authentication methods

Registered user security information

Simulated real world password reset scenario

Validated successful reset process

<h2>Skills Demonstrated </h2>

- <b>Identity & Access Management (IAM)
- User Provisioning 
- SSPR Configuration
- Authentication Security
- Cloud Administration
- End-User Support Automation </b>

<h2>Lab walk-through:</h2>

<p align="center">
Created department-based security groups (IT-Users, Finance-Users, HR-Users).
These groups simulate role-based access control (RBAC) used in enterprise environments to assign permissions based on department. <br/> <br/>
<img width="80%" height="80%" alt="Screenshot 2026-02-13 at 11 17 57 PM" src="https://github.com/user-attachments/assets/ffff51ec-2eb7-4591-9487-c8a885a26752" />
<br />
<br/>
Created a CSV file to simulate HR onboarding data. <br/> <br/>
<img width="80%" height="80%" alt="Screenshot 2026-02-13 at 11 20 56 PM" src="https://github.com/user-attachments/assets/1b13a076-f2aa-4fba-8585-a2537ba64e26" />
<br />
<br />
Developed a PowerShell script to automate Active Directory user provisioning. <br/> <br/>
<img width="80%" height="80%" alt="Screenshot 2026-02-14 at 12 15 16 AM" src="https://github.com/user-attachments/assets/e3b77b07-36a4-43cf-b76b-81429d04e007" />
<br />
<br />
Executed the PowerShell provisioning script (Provision-NewHires.ps1) from the C:\ directory.  <br/> <br/>
<img width="80%" height="80%" alt="Screenshot 2026-02-16 at 10 23 18 PM" src="https://github.com/user-attachments/assets/573f918a-8dfb-4396-bf20-fd5a3690515a" />
<br />
<br />
Verified that the script exported a structured CSV report containing. <br/> <br/>
<img width="80%" height="80%" alt="Screenshot 2026-02-16 at 11 37 46 PM" src="https://github.com/user-attachments/assets/4c203c65-2645-4c02-92f4-bccc93de07ff" />
