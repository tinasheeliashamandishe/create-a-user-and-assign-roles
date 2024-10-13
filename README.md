<h1>Entra IDL: Creating a user</h1>

<h2>Description</h2>
This lab will configure a user in Microsoft Entra ID.<br /><br />

Entra ID, previously known as Azure Active Directory (Azure AD), is Microsoft's identity and access management service. It provides features for managing user identities and access to resources, both on-premises and in the cloud. Key functionalities include:<br /><br />

<b>Single Sign-On (SSO):</b> Users can access multiple applications with one set of credentials.<br />
<b>Multi-Factor Authentication (MFA):</b> Enhances security by requiring additional verification methods.<br />
<b>Conditional Access:</b> Allows organizations to enforce security policies based on user, location, device, and other conditions.<br />
<b>Identity Protection:</b> Monitors for potential security risks and responds with automated actions.<br />
<b>Self-Service Password Reset (SSPR):</b> Enables users to reset their passwords without IT intervention.<br />


<h2>Environments Used </h2>

- <b>Microsoft Azure</b>

<h2>Lab walk-through:</h2>

<p align="center">

<h4>Step 1</h4> 
Create 2 Storage Account resources and create containers in them.<br/>
<img src="https://i.imgur.com/ZSdcwpC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/th6llVb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<h4>Step 2</h4> 
Enable blob versioning and chnage feed on your blobs.<br/>
<img src="https://i.imgur.com/OgjCPzN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h4>Step 3</h4> 
Create a replication rule.<br/>
<img src="https://i.imgur.com/AYnwzO7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h4>Step 4</h4> 
Confirm that objects have been replicated.<br/>
<img src="https://i.imgur.com/SuS0aoZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/JDDSocA.png" height="80%" wi
