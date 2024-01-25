<h1>Ticket 10: Website access issues</h1>

<h2>Description</h2>
This lab example shows how to solve a website access issue for a user. There are numerous reasons why a user cannot access a website, however in this lab, we will simulate a situation in which a user ran a script that prevented them from visiting a specific website.

<h2>Environments Used </h2>

- <b>MacBook Pro (Intel)</b>
- <b>VMware Fusion</b>
- <b>Windows 11</b>
- <b>Windows PowerShell ISE</b>

<h2>Program walk-through:</h2>

1 - Start up your Windows 11 VM and login. Search for Windows PowerShell ISE and Run as Administrator. <br/>
<img width="900" alt="1" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/09790b4d-96c0-4daa-9188-9c7e035bb5de">
<br />

2	- Enter in your domain admin credentials. <br/>
<img width="900" alt="2" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/e6a907a8-4277-4776-9d5b-181f5183a9b7">
<br />

3	- Create the following script and save it as document.ps1. <br/>
<img width="900" alt="3" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/fb4fa4e4-c975-43b5-af40-e666c6a6e4ae">
<br />

4 - Highlight (Set-ExecutionPolicy RemoteSigned) then on the action bar select Run Selection. <br/>
<img width="900" alt="4" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/e4debf1d-7336-4a0d-9f82-30b181d6c53a">
<br />

5 - Select Yes to All. <br/>
<img width="900" alt="5" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/8779acc9-8ae8-4812-83e1-af38d8c2bdf0">
<br />

6 - This time select Run Script from the action bar. <br/>
<img width="900" alt="6" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/cd0d7195-d633-414f-924f-706925c3b9fa">
<br />

7 - The script successfully ran. <br/>
<img width="900" alt="7" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/de550f00-ba54-45bd-8efc-98c4d9a7548b">
<br />

8 - Open a web browser and go to jobskillshare.org (or the website that you added in the script). You will see that the user is not able to reach the site. <br/>
<img width="900" alt="8" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/ae6ceb7b-c3a9-4efe-8cba-71790dd3bc37">
<br />

9 - But if the user navigated to Google's search engine they are able to. <br/>
<img width="900" alt="9" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/7f1dd8e6-17de-40c2-99e8-bf73e1d8fff7">
<br />

10 - Open CMD and ping the website jobskillshare.org (or the website that you added in the script). User is able to ping the site. Run ipconfig /flushdns (By using the flush DNS command, you can clear this cache and make your device retrieve the data from the DNS once more.) Now try to go back and see if the site is reachable from the web browser. <br/>
<img width="900" alt="10" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/be66bf36-9497-413c-81a9-833bee4d4a6c">
<br />

11 - If the website is still unreachable search for WordPad and Run as Administrator. <br/>
<img width="900" alt="11" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/6daa4ea7-cddf-4dc0-9b09-2ad1811759da">
<br />

12 - Enter in your domain admin credentials.  <br/>
<img width="900" alt="12" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/c5ec3e16-d322-4db8-a61c-88990ea245af">
<br />

13 - Select File then Open. <br/>
<img width="900" alt="13" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/d7d788c2-f99d-4896-9fbc-6a3557704d21">
<br />

14 - Navigate to (This PC > (C:) Drive > Windows > System32 > drivers > etc). In the drop down menu choose All Documents and double-click on hosts. <br/>
<img width="900" alt="14" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/a052b27e-c85c-47b6-9286-abd8ff8032b6">
<br />

15 - Scroll all the way to the bottom and you can see the reason that the user is unable to reach this website jobskillshare.org (or the website that you added in the script) is because when we ran the script it added an IP Address (1.2.3.4) infront of jobskillshare.org (or the website that you added in the script). <br/>
<img width="900" alt="15" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/41850734-138e-4f8e-a7de-36b931c00f3c">
<br />

16 - Remove the last line and then select File > Save and the user will be able to access the website. <br/>
<img width="900" alt="16" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/24e06d30-64fb-410a-9ec6-121a86969e19">
<br />

17 - Proof of completing the lab. <br/>
<img width="900" alt="17" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/ade84297-dab4-4be1-90b2-5b3186e12010">
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
