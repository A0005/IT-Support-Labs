<h1>Ticket 25: Machine Backup</h1>

<h2>Description</h2>
This lab example shows how to backup a user's whole system using Veeam.

<h2>Environments Used </h2>

- <b>MacBook Pro (Intel)</b>
- <b>VMware Fusion</b>
- <b>Windows 11</b>
- <b>Windows Server 2022</b>
- <b>Veeam</b>


<h2>Program walk-through:</h2>

1 - In the Windows 11 virtual machine open a web browser and search for veeam free backup. Select Free Backup Software For Windows, VMware, & More. <br/>
<img width="900" alt="1" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/602beaba-b990-425f-a8df-3e851851876a">
<br />

2	- Select Download Now. <br/>
<img width="900" alt="2" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/5d2b900a-8120-4f6c-bd92-1e57345f2558">
<br />

3	- Complete the registration form then select DOWNLOAD FREE. <br/>
<img width="900" alt="3" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/2f18d619-4de5-4f36-bc74-75d8a3e89e17">
<br />

4 - Scroll down, find Standalone Veeam Agent for Windows Free and select Download. <br/>
<img width="900" alt="4" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/4b728026-ef3d-4d94-a99a-b7ee7768f837">
<br />

5	- Check the agreement box and select ACCEPT. <br/>
<img width="900" alt="5" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/d24b81d6-558f-4ba0-8133-c8297eb6bd27">
<br />

6	- Once the download completes select the folder icon. <br/>
<img width="900" alt="6" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/82b5f319-0aa5-45cb-bf30-b91259079357">
<br />

7 - Right-click the VeeamAgentWindows folder and select Extract all. <br/>
<img width="900" alt="7" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/daca39bc-15ae-4dbb-bdc5-72e93a0e9939">
<br />

8	- Now inside the folder that you extracted right-click on the VeeamAgentWindows program and select Run as administrator. <br/>
<img width="900" alt="8" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/8ee6aee7-095b-4f81-97dc-6bd6ac1aefab">
<br />

9	- Enter in your admin credentials then select Yes. <br/>
<img width="900" alt="9" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/6fb3048c-2d77-44d2-81bc-32e2f3194042">
<br />

10 - Select Next. <br/>
<img width="900" alt="10" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/6ad3a6b3-13ff-4e28-adf0-c5dbd81da7d6">
<br />

11 - Select I Accept. <br/>
<img width="900" alt="11" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/d9347250-e32c-49e4-9a60-e142c3372aaa">
<br />

12 - Uncheck the box and select Finish. <br/>
<img width="900" alt="12" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/a58c1573-d959-4e83-a22c-8c2da55b40c7">
<br />

13 - Click on the drop down arrow on the taskbar and double-click the Veeam program. <br/>
<img width="900" alt="13" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/bfa488bb-3a94-4247-95fe-e3b335eb8c2a">
<br />

14 - Select No. <br/>
<img width="900" alt="14" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/cb875c78-0d21-41ef-b28e-68a46f6a33a8">
<br />

15 - Select the three lines at the left corner then choose Add New Job. <br/>
<img width="900" alt="15" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/eeaa2d76-b203-4fb3-823f-ca21ad284259">
<br />

16 - Select Next. <br/>
<img width="900" alt="16" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/9209a75c-6f1f-4794-a278-0b00c8b58bc9">
<br />

17 - Select Next. <br/>
<img width="900" alt="17" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/6c7f160f-e5b0-4c89-ada7-c23a5214f1ca">
<br />

18 - Choose Shared folder then select Next. <br/>
<img width="900" alt="18" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/5d4bd153-caa9-4e38-ab4f-9285e83577be">
<br />

19 - On the Windows Server 2022 virtual machine, create a Backup folder, share it and give all users full permissions. <br/>
<img width="900" alt="19" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/b0ccba6f-e68c-401e-a9a4-bca57db0bfef">
<br />

20 - Now back to installed Veeam on Windows 11. Enter in your shared folder path then check the box that says This share requires access credentials and enter in your admin credentials. Then select Next. <br/>
<img width="900" alt="20" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/b6864cf2-6d30-463f-9e8e-501f8504cf10">
<br />

21 - Select Apply. <br/>
<img width="900" alt="21" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/7a24b647-0b7a-497c-b523-da4bb596632d">
<br />

22 - Select Finish. <br/>
<img width="900" alt="22" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/55733463-8e13-4882-a70a-9a0c5e7f989e">
<br />

23 - We created a job and now the Windows 11 system will back up into the backup folder on the Windows Server 2022. <br/>
<img width="900" alt="23" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/275a84d5-b3e8-4e4d-a7df-93a2c3d99b8c">
<br />

24 - Proof of completing the lab. <br/>
<img width="900" alt="24" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/b872c752-2d1f-4248-a676-78fceb4f1a15">
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
