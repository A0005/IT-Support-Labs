<h1>Ticket 29: Account and access removal</h1>

<h2>Description</h2>
This lab example shows how to remove a user's account and access.

<h2>Environments Used </h2>

- <b>MacBook Pro (Intel)</b>
- <b>VMware Fusion</b>
- <b>Windows 11</b>
- <b>Windows Server 2022</b>
- <b>Microsoft Office 365</b>

<h2>Program walk-through:</h2>

1 - In the Windows Server 2022 open Active Directory. Find the user account you want to disable, right-click on the user’s name and select Disable Account. <br/>
<img width="1048" alt="1" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/617bbc81-6e44-41b0-b67d-c936d9c4ee8d">
<br />

2	- Select OK. Now the user's account is disabled and can not login. <br/>
<img width="900" alt="2" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/10ed981b-8563-49ee-bf2d-7af9b1293cc3">
<br />

3	- Log into Microsoft Office 365 with your admin credentials and open the Admin app. Find the user's name that you are removing. Double-click their name, select the License and apps tab, and uncheck all their licenses. Then select Save changes. <br/>
<img width="900" alt="3" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/cb940674-cd1e-4112-960c-cd8aa2ed9fe6">
<br />

4 - Successfully removed their licenses. <br/>
<img width="900" alt="4" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/7b055013-4601-4199-958e-1c9320069b23">
<br />

5	- In the Exchange admin center under Mailboxes search for the user. Choose the user's name and select Convert to shared mailbox. <br/>
<img width="900" alt="5" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/56bfd748-206b-4364-80f9-c69e3dba0465">
<br />

6	- Select Confirm. <br/>
<img width="900" alt="6" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1e6cd8f2-b1e7-461c-9a5e-2e8b8953291c">
<br />

7 - Mailbox has been successfully converted into a shared mailbox. <br/>
<img width="900" alt="7" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/108617a1-3ada-4c41-b0b4-e0fb7da4b1b8">
<br />

8	- In the Microsoft 365 admin center under Shared mailboxes you can see the user's account is a shared mailbox. <br/>
<img width="900" alt="8" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/2b5bc04a-1d24-4bf5-9374-7e79cf17cde2">
<br />

9	- Log into the user's computer using your domain admin credentials.  <br/>
<img width="900" alt="9" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/6799e098-141c-452d-afd7-e7d8b034eebf">
<br />

10 - Search for reset pc. Then select Reset this PC. <br/>
<img width="900" alt="10" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/3b33e583-05e7-438b-acac-9ddf85648bf3">
<br />

11 - Select Reset PC. <br/>
<img width="900" alt="11" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/7f9e1d10-e5c9-4228-abf0-880b7687e02e">
<br />

12 - Select Remove everything. <br/>
<img width="900" alt="12" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/3bfbc29b-a368-4b59-90fe-a0e8d2649122">
<br />

13 - Select Local reinstall. <br/>
<img width="900" alt="13" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/eb25653b-14c5-4503-8748-4f648a4191b7">
<br />

14 - Select Change settings. <br/>
<img width="900" alt="14" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/01760123-2257-4c78-8d6f-f1a73229f18a">
<br />

15 - Say Yes to both options then select Confirm. <br/>
<img width="900" alt="15" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/180d655d-6fa9-4e01-812e-05132ec402bf">
<br />

16 - Select Next and the whole computer will be resetted. <br/>
<img width="900" alt="16" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/b11a5cff-951c-44a8-b17d-4a28f15c1022">
<br />

17 - Proof of completing the lab. <br/>
<img width="1440" alt="17" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/9e300454-5c47-42d7-ba43-c2d5ff4beeaa">
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
