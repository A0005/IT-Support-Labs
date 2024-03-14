<h1>Ticket 30: Working with Intune</h1>

<h2>Description</h2>
This lab example shows how to add a computer to Intune.

<h2>Environments Used </h2>

- <b>MacBook Pro (Intel)</b>
- <b>VMware Fusion</b>
- <b>Windows 11</b>
- <b>Intune</b>
- <b>Microsoft Office 365</b>
- <b>Azure</b>

<h2>Program walk-through:</h2>

1 - Log into your Microsoft Office 365 admin account and make sure the user you want to add has the Intune license. In this case the user Amy has the Microsoft Intune Plan 1 license. <br/>
<img width="900" alt="1" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/8260e542-1a38-442d-86f6-afa9bb21b657">
<br />

2	- Log into azure.portal.com with your Microsoft Office 365 admin account and select Microsoft Entra ID. <br/>
<img width="900" alt="2" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/da2e48b4-b386-4b91-a84b-8c9e5ed9991a">
<br />

3	- Select Mobility (MDM and WIP). <br/>
<img width="900" alt="3" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/0facd735-1fc2-4776-844a-6ec4103854c9">
<br />

4 - Double-click Microsoft Intune. <br/>
<img width="900" alt="4" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/ce1d64cd-9857-4c4e-8ada-1576f325a05c">
<br />

5	- For the MDM user scope make it All then save. <br/>
<img width="900" alt="5" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/cb9d64c0-6165-4db8-b49e-26336017da9f">
<br />

6	- Back on your Microsoft Office 365 admin account open the Admin app. <br/>
<img width="900" alt="6" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/76f48425-c722-43b1-b87c-3e2434aa19cf">
<br />

7 - Open Endpoint Manager. <br/>
<img width="900" alt="7" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/46852ac9-f84e-4de9-9528-ffac411bd117">
<br />

8	- Select Devices. <br/>
<img width="900" alt="8" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/771f8d2b-ff8e-4846-b0a5-136d9044d76f">
<br />

9	- Under Device onboarding select Enrollment.  <br/>
<img width="900" alt="9" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/46158e5e-350c-49ae-ba9f-39373edb9ffd">
<br />

10 - Select Automatic Enrollment. <br/>
<img width="900" alt="10" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/eb9d041c-e9f6-4483-b336-3b3d11a1cfb8">
<br />

11 - Make sure the MDM user scope is set to All. <br/>
<img width="900" alt="11" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/4c5ec316-fcf6-4665-97f3-73c49f42db8c">
<br />

12 - Now log into the users computer using your admin credentials. <br/>
<img width="900" alt="12" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/93ab8fdc-a8ce-469a-9f9c-71868a4a3ee2">
<br />

13 - Right-click the Windows icon then select System. <br/>
<img width="900" alt="13" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/05bcafb5-4fb2-4c2d-a337-892285affdff">
<br />

14 - Select Accounts from the left column. <br/>
<img width="900" alt="14" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/86ee9b2f-bf69-45b0-a668-e042bb2cdcd9">
<br />

15 - Select Access work or school. <br/>
<img width="900" alt="15" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/7b3d9118-ff77-4bdb-8a7c-f4e91cb22457">
<br />

16 - Select Connect. <br/>
<img width="900" alt="16" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/c066c141-7ab0-4a17-8d38-60dec6f3f296">
<br />

17 - Log in with your Microsoft Office 365 admin account. <br/>
<img width="900" alt="17" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/10fda780-382a-41d5-a5c1-dae7df67bdc9">
<br />

18 - This computer is now being added to Intune. <br/>
<img width="900" alt="18" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/87e3fe6a-7b7f-40e7-80e6-e4a2cb58110a">
<br />

19 - Here you can see the computer is now being managed by Intune. <br/>
<img width="900" alt="19" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/c9d521d4-6e83-4481-9046-26d9f87574c2">
<br />

20 - Now back your Azure portal in Microsoft Entra ID under devices you can see that the device (wendy) has been added. <br/>
<img width="900" alt="20" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/533663b1-5231-4b5c-bbb4-1601f813c8bb">
<br />

21 - In Microsoft Intune admin center you can also see the computer added. <br/>
<img width="900" alt="21" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/64903a66-1ba4-4ae4-8109-5a4c0a2ac0c0">
<br />

22 - Proof of completing the lab. <br/>
<img width="900" alt="22" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/3dcaa2ea-41f0-4395-8c30-895a3c629162">
<br />

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
