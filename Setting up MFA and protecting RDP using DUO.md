<h1>Setting up MFA and protecting RDP using DUO</h1>

<h2>Description</h2>
This lab example shows how to set up MFA on Windows Server 2022 and protect RDP using DUO.

<h2>Environments Used </h2>

- <b>MacBook Pro (Intel)</b>
- <b>VMware Fusion</b>
- <b>Windows Server 2022</b>
- <b>DUO</b>

<h2>Program walk-through:</h2>

1 - First create a free trial account on https://duo.com/. Then log into the admin portal. Expand the Users tab and select Add User. <br/>
<img width="900" alt="1" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/527bdf1c-1099-45db-85c4-5c48b884c5cd">
<br />

2	- Enter a username then select Add User. An object that represents a user of the programs and services you use Duo to secure is called a Duo user. Both usernames and username aliases for Duo users must be distinct. <br/>
<img width="900" alt="2" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/ef586d7f-1879-4909-b05d-db460da937a5">
<br />

3	- Enter your Full name and Email. Then scroll down and select Save Changes. <br/>
<img width="900" alt="3" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/b1cf6197-0546-4fc3-b597-3a878cb75367">
<br />

4 - Select Bulk Enroll Users. In the Users CSV enter your username followed by a comma and email (username,example@outlook.com). Then select Send Enrollment Links. <br/>
<img width="900" alt="4" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/5d1b1649-7592-4939-839f-b80865728193">
<br />

5 - Open your email and click on the enrollment link. Select how you would like to receive your MFA. I chose Duo Mobile. <br/>
<img width="900" alt="5" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/b2c6dafc-87fc-4b61-bbf5-639be1541898">
<br />

6 - Enter your phone number. <br/>
<img width="900" alt="6" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/75072d30-f2b4-41ba-8452-cf3571c27347">
<br />

7 - Scan the QR code using your Duo Mobile app. <br/>
<img width="900" alt="7" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/8e6098fe-e306-423d-8c88-941d86ab5258">
<br />

8 - Confirmation that the enrollment was a success. To utilize any or all of your Duo applications, a user simply needs to finish the enrolling and activation process once. <br/>
<img width="900" alt="8" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/2b9c6a69-4468-449e-8e8b-6a4a2e0d4029">
<br />

9 - Start up your Windows Server 2022 machine and log into your Duo admin portal using a web browser. <br/>
<img width="900" alt="9" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/b1b50a54-d4bc-435a-8052-556a5fc634f3">
<br />

10 - Select the Applications tab. <br/>
<img width="900" alt="10" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1225d3d3-173d-457b-9436-1107f593eaf3">
<br />

11 - Select Protect an Application. <br/>
<img width="900" alt="11" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/17a391dc-e01d-4799-8e5a-a024b13baf33">
<br />

12	- Search for rdp then select Protect. Microsoft provides the Remote Desktop mechanism (RDP), a secure network communication mechanism that enables users to do remote tasks on other computers. Using an encrypted communication channel, it enables safe information sharing between machines that are connected remotely.<br/>
<img width="900" alt="12" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/e55d2c6f-8f96-462d-a886-cae3e28f4f75">
<br />

13	- Confrimation Microsoft RDP has been added to the protected applications. Select RDP documentation. <br/>
<img width="900" alt="13" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/23b33dac-9590-441c-acbf-d13aec8436e5">
<br />

14 - Scroll down and select Duo Authentication for Windows Logon installer package to download it. <br/>
<img width="900" alt="14" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/7b8af780-2c85-4488-9c68-c7280cb95b6a">
<br />

15 - After the download completes open the installer package then select Next. <br/>
<img width="900" alt="15" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/62b53bbd-a08e-4cad-af58-39081c6db602">
<br />

16 - Enter your API Hostname (you can find this back on your admin portal when you added Microsoft RDP to the protected applications) then select Next. <br/>
<img width="900" alt="16" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/cdd4bf6a-1cf9-4d13-89d8-5afa1e3d2643">
<br />

17 - Enter your Integration Key and Secret Key (you can find both of these back on your admin portal when you added Microsoft RDP to the protected applications) then select Next. <br/>
<img width="900" alt="17" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/af82627e-3250-42a6-85b1-95a73a4c129a">
<br />

18 - Keep the default and select Next. <br/>
<img width="900" alt="18" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/08d5e005-5a27-4d47-a148-ecf7c1db0959">
<br />

19 - Keep the default and select Next. <br/>
<img width="900" alt="19" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/9d3c1e11-19e6-4d6e-ac42-265fe8cc81fc">
<br />

20 - Keep the default and select Next. <br/>
<img width="900" alt="20" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/70c0df39-c757-4586-ae38-865e93f6eca9">
<br />

21 - Select Install. <br/>
<img width="900" alt="21" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/7decdccb-cb80-41ff-85dd-26300d8ef6ca">
<br />

22 - Select Finish. <br/>
<img width="900" alt="22" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/dce3f93a-0bfe-44ee-b654-7536337b4362">
<br />

23 - Now you can use an application like Microsoft Remote Desktop to RDP into your server or you can restart your server and log in with your password. <br/>
<img width="900" alt="23" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1ece638f-13cd-4b62-9eee-23d9e279a4c4">
<br />

24 - After successfully entering your password, you will be prompted to complete an MFA authentication. Proceed and utilize the method that you established to approve this action. <br/>
<img width="900" alt="24" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/76aef88c-9443-4636-8ec5-ddd29a2ca6f5">
<br />

25 - Confirmation of successfully setting up MFA and protecting RDP using DUO. <br/>
<img width="900" alt="25" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/179037ef-2018-49db-bdc9-b547392712c5">
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
