<h1>Ticket 11: VPN Client</h1>

<h2>Description</h2>
This lab example shows how to use a VPN to connect to an organization's environment.

<h2>Environments Used </h2>

- <b>MacBook Pro (Intel)</b>
- <b>VMware Fusion</b>
- <b>Windows Server 2022</b>
- <b>Windows 10</b>
- <b>SoftEther VPN</b>

<h2>Program walk-through:</h2>

1 - Start up your Windows Server 2022, open a web browser and navigate to SoftEther's official website. Select Download then Download SoftEther VPN. <br/>
<img width="900" alt="1" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/d6d4db7b-ae1c-4ca3-a60b-b6e9de3a820d">
<br />

2	- Select Download SoftEther VPN. <br/>
<img width="900" alt="2" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/6c3b7b3f-cd7c-494d-b062-af935e37dafe">
<br />

3	- Under Select Component choose SoftEther VPN Server Manager for Windows. <br/>
<img width="900" alt="3" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/6f1f69b6-8a99-4b63-a07c-101b4b07e708">
<br />

4 - Under Select Platform choose Windows. <br/>
<img width="900" alt="4" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/82e78671-d93e-4020-b84b-6ff7025a2a44">
<br />

5 - Under the Download Files choose then first link and open the file after completing the download. <br/>
<img width="900" alt="5" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1a1f8c4d-d78e-4494-bf0c-48bbf628078b">
<br />

6 - Select Next. <br/>
<img width="900" alt="6" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/3805b8cb-052c-4253-8db9-dec5afbbc4f4">
<br />

7 - Choose SoftEther VPN Server then select Next. <br/>
<img width="900" alt="7" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/07332c2a-bb39-4989-aaa6-861d3ffb46e2">
<br />

8 - Agree to the terms then select Next. <br/>
<img width="900" alt="8" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/ba1c6c65-fe96-42a3-a0b5-f8875715fcd4">
<br />

9 - Select Next. <br/>
<img width="900" alt="9" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/d188318d-ffab-4b4e-a258-fa9fbfc71a6f">
<br />

10 - Select Next. <br/>
<img width="900" alt="10" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/ff32655c-b41e-4367-ae6e-9659a3975ef4">
<br />

11 - Select Next. <br/>
<img width="900" alt="11" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/ef2d7390-f4ae-45f4-95f9-26d8bf811ca5">
<br />

12 - Select Finish. <br/>
<img width="900" alt="12" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/4ab7cf79-0356-4fe9-ba6a-2a397046f682">
<br />

13 - Select your local host then choose Edit Setting. <br/>
<img width="900" alt="13" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/8f163136-fbf0-4159-a049-523c0d897d42">
<br />

14 - Enter a name in the Setting Name field. For the Host Name enter your Windows Server 2022 IP Address. For the Password enter in your domain admin password. Then select OK. <br/>
<img width="900" alt="14" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1bece2d5-378e-47c0-aab9-05b773919269">
<br />

15 - Select Connect. <br/>
<img width="900" alt="15" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/32dbf18d-c681-4c15-8feb-3dacbaf6cc9a">
<br />

16 - Enter your domain admin password then select OK. <br/>
<img width="900" alt="16" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/5b7a67e6-5e46-4e3e-807f-2c3f205e1451">
<br />

17 - Select OK. <br/>
<img width="900" alt="17" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/25032f56-c81c-4c8c-be52-7b6e2050b7af">
<br />

18 - Check the box Remote Access VPN Server then select Next. <br/>
<img width="900" alt="18" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/2f1d0788-7a72-44da-82ef-f60d986e4cfd">
<br />

19 - Select Yes. <br/>
<img width="900" alt="19" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/8e269b14-7c3e-4d68-8da5-018586dc124c">
<br />

20 - Give the Virtual Hub Name a name then select OK. <br/>
<img width="900" alt="20" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/f11b98f6-9db3-42a7-8b01-37809a3eb62d">
<br />

21 - Select Exit. <br/>
<img width="900" alt="21" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/90f82665-5441-46c4-8af4-c014f813df57">
<br />

22 - Check both boxes Enable L2TP Server Function (L2TP over IPSec) and Enable L2TP Server Function (Raw L2TP with No Encryption). Then select OK. <br/>
<img width="900" alt="22" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/4eb8a84e-1d64-41ad-be52-9993e8e148b1">
<br />

23 - Check the button Disable VPN Azure then select OK. <br/>
<img width="900" alt="23" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/f0faee3c-58f8-46fa-b779-abc91e7f2042">
<br />

24 - Select Create Users. <br/>
<img width="900" alt="24" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/897566e6-d2b5-476a-8a9a-3afc3e61fbe0">
<br />

25 - Enter a User Name and Full name. Create a password in the Password Authentication Settings. (This is the credentials a user will use when connecting to an organization over VPN). Then select OK. <br/>
<img width="900" alt="25" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/632299c1-d0d9-484b-b312-eeb3506ecd16">
<br />
26 - Select OK. <br/>
<img width="900" alt="26" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/89f8fa67-add1-4508-8076-a81f8a3308df">
<br />

27 - Start up a Windows 10 virtual machine that is not on a domain of an organization. Open a web browser and navigate to SoftEther's official website. Select Download then Download SoftEther VPN. Under Select Component choose SoftEther VPN Client. Under Select Platform choose Windows. Under the Download Files choose then first link and open the file after completing the download.  <br/>
<img width="900" alt="27" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/79a6a782-3259-4c08-b3a6-b5f74d0673c0">
<br />

28 - Select Next and continue the installation similar to the one you installed on the Windows Server 2022. <br/>
<img width="900" alt="28" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/9e5ba34e-43bc-4936-bc34-96303b38edf5">
<br />

29 - Double-click Add VPN Connection. <br/>
<img width="900" alt="29" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/038e3b09-2c63-4034-96fe-62c2bbbaa3ed">
<br />

30 - Enter a name for the Setting Name. Enter the Windows Server IP Address for the Host Name. For the Virtual Hub Name select the drop down arrow and it should automatically pick up the name you created on the Server VPN. For the User Authentication Setting enter the username and password you created on the VPN Server. Then Select OK.<br/>
<img width="900" alt="30" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/a046057e-8eaa-43f5-9675-e9010a538411">
<br />

31 - Right-click on the VPN connection you created and select Connect. <br/>
<img width="900" alt="31" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/8a1df931-cb3e-4480-872c-5a1990d536da">
<br />

32 - VPN connection was successfull select Close. Open CMD and run ipconfig to see that you a receiving an IP Address from the organization's network. <br/>
<img width="900" alt="32" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/0fa1d61a-b898-4114-b401-e031f2fc142a">
<br />

33 - Proof of completing the lab. <br/>
<img width="900" alt="33" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/3e87d188-79af-4cb9-bf18-3f9eb300f883">
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
