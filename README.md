<h1>Implementing an IT Security Policy</h1>

<h2>Tools and Software Used</h2>

- <b>Group Policy Management Console (GPMC)</b> 
- <b>Active Directory Users and Groups</b>
- <b>Windows Defender Antivirus</b> 
- <b>Security Compliance Toolkit (SCT)</b>

 

<h2>Environments Used </h2>

- <b>vWorkstation (Windows: Server 2022)</b> 
- <b>Switch01 (Linux: Debian 11)
- <b>pfSense-office (FreeBSD:pfSense)</b>
- <b>pfSense-dc (FreeBSD:pfSense)</b>
- <b>DomainController01 (Windows: Server 2019)</b>
- <b>Android01 (Android OS)</b>


 
<h2>Description</h2>
Project consists of implementing several different functional security policies: implement password protection and antivirus policies using Microsoft's Group Policy Management Console,implementing multiple policies using a Microsoft-issued security baseline,and exploring best pratices for a mobile device security policy.
<br />

### Section 1

<h2>Implement a Password Protection Policy:</h2>








<p align="center">
Show the newly configured Domain Password Policy Settings: <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the successful password change message:  <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the logged on user account: <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>

 <h2>Implement an Antivirus Policy:</h2>







<p align="center">
Show the newly configured Domain Real-time protection Policy settings: <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the grayed-out real-time threat protection settings:  <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>










 ### Section 2

<h2>Apply a Windows Security Baseline:</h2>










<p align="center">
Show the Microsoft's recommended Password and Account Lockout policy settings: <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the linked MSDomainSecurity2019 object:  <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the Password and Account Lockout policy settings: <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>


 <h2>Implement a Mobile Device Security Policy:</h2>










<p align="center">
Show the results of the Goodle Play Protect scan: <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the updated "last successful check for update" timestamp: <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the Android lock screen" timestamp: <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the encryption set-up explanation: <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the Find My Device settings" timestamp: <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>












</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
