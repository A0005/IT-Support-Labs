<h1>Ticket 27: Password Policy (Group Policy)</h1>

<h2>Description</h2>
This lab example shows how set and maintain Group Policies and unlock a users account..

<h2>Environments Used </h2>

- <b>MacBook Pro (Intel)</b>
- <b>VMware Fusion</b>
- <b>Windows 11</b>
- <b>Windows Server 2022</b>


<h2>Program walk-through:</h2>

1 - On the Windows Server virtual machine open Server Manager. Then select Tools > Group Policy Management. <br/>
<img width="900" alt="1" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/74a713ef-a77a-4cbd-8d9f-b8c627146f9a">
<br />

2	- Expand Forrest > Domains > Domain Name and select Default Domain Policy. <br/>
<img width="900" alt="2" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/987a0707-ff15-4652-97ca-41bb85deedf6">
<br />

3	- Under Computer Configuration expand Security Settings then Account Policies/Password Policy. Here you can see the current policy that is set. <br/>
<img width="900" alt="3" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/40831bc7-45bd-4803-af9f-3d115398b39a">
<br />

4 - Right-click Default Domain Policy and select Edit. <br/>
<img width="900" alt="4" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/176e6909-e7e4-4ffa-8317-85ca868c41c6">
<br />

5	- Under Computer Configuration expand Policies > Windows Settings > Security Settings > Account Policies and double-click Password Policy. Select Minimum password length Properties, set it to 8 then click Apply and OK. <br/>
<img width="900" alt="5" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/d3921562-1720-4643-92b3-8a83a4ccd5fc">
<br />

6	- Under Security Settings double-click Account Lockout Policy. Select Account lockout duration Properties and set it to 30 minutes then click Apply. <br/>
<img width="900" alt="6" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/f0d41afd-a4f2-4125-bd26-1480a0db0adb">
<br />

7 - Select OK. <br/>
<img width="900" alt="7" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/a5e22807-6af0-47f4-8ab9-887c61b2549c">
<br />

8	- Select OK. <br/>
<img width="900" alt="8" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/87b120cd-0eb1-4726-ab3e-6b5a47012cfc">
<br />

9	- Log into the Windows 11 virtual machine and open CMD. Run net accounts (This will show the current policies that are set). Run gpupdate /force (This will update the system with the lastest policies). Run net accounts again to see the new policies that were set. <br/>
<img width="900" alt="9" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/50448f83-69fc-4b7e-86a9-39fc6b13ad89">
<br />

10 - Sign out of the Windows 11 virtual machine. <br/>
<img width="900" alt="10" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/eb29f05d-fb6d-4666-8577-9ddabd1e35ab">
<br />

11 - Log in using a wrong password a five times till you get this error. This is an example when a user enters their password wrong a couple of times, they will be locked out and will need to contact help desk in order to unlock their account. <br/>
<img width="900" alt="11" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/5f165253-683b-4c65-ae4e-b226fef14a43">
<br />

12 - Back on the Windows Server 2022 virtual machine open Active Director Users and Computers. <br/>
<img width="900" alt="12" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/26d45616-3b7d-4a31-bb62-d1f945113043">
<br />

13 - Search for the user with the locked account, right-click their name and select Properties. <br/>
<img width="900" alt="13" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/f9b8886c-f6dc-4e2f-9c37-9ec8cb7b0266">
<br />

14 - Select the Account tab then check the box that says Unlock Account. Click Apply and OK. <br/>
<img width="900" alt="14" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/bc8b02cc-bff2-4324-b310-74417d04e1c5">
<br />

15 - Say the user forgot their password. You can reset their password by right-clicking their name and select Reset Password. <br/>
<img width="900" alt="15" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/ff530dd2-ab64-40eb-8e8c-a6bd6221f73d">
<br />

16 - Here you can reset the users password. <br/>
<img width="900" alt="16" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/fbf680cc-d95c-4ed8-9c4a-1ad22a137a35">
<br />

17 - On the Windows 11 virtual machine the user can also change their password by themselves by clicking Alt+Ctr+Del. Select Change a password. <br/>
<img width="900" alt="17" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/00eb1c0e-0b3e-41be-88f9-2261775045c2">
<br />

18 - Here they can reset their password but they need to remember the old one. <br/>
<img width="900" alt="18" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/80505c55-cb65-4880-8ed3-96690855ca90">
<br />

19 - And if the new password they entered does not meet the password policy they will get this error message. <br/>
<img width="900" alt="19" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/f1f932e7-7392-4bde-89d9-2e851afa82e2">
<br />

20 - Proof of completing the lab. <br/>
<img width="900" alt="20" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/2c2b37ee-e2a8-4fed-8fcc-dbd3dcf43e51">
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
