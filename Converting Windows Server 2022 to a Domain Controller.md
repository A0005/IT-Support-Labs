<h1>Converting Windows Server 2022 to a Domain Controller</h1>

<h2>Description</h2>
This lab example shows how to convert Windows Server 2022 to a Domain Controller.

<h2>Environments Used </h2>

- <b>MacBook Pro (Intel)</b>
- <b>VMware Fusion</b>
- <b>Windows Server 2022</b>

<h2>Program walk-through:</h2>

1 - Start up your Server 2022 and right click on the windows startup button then choose System. <br/>
<img width="900" alt="1" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/a4d72f76-f44a-45a1-9420-f99006e075c8">
<br />

2	- Select Rename this PC. <br/>
<img width="900" alt="2" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/8820f990-b709-405c-9503-c1045359968b">
<br />

3	- Enter your new name then select Next. <br/>
<img width="900" alt="3" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/bc885724-fd15-4669-8fc3-92a57fdccf58">
<br />

4 - Select Restart now. <br/>
<img width="900" alt="4" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/7b1dbf2f-8958-4828-a345-2466e2d99468">
<br />

5 - After your Server 2022 restarts you can go back to confirm that the name has been changed. <br/>
<img width="900" alt="5" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1dcc1402-ff21-4111-a625-0ce5f1e43eb8">
<br />

6 - To turn the server into a domain controller and add computers to the domain later on, we must configure it to have a static IP address. Turn off your server and naviagte to the network adapter settings. Make sure it is set to Private to my Mac (this is if you are using a Mac Intel and VMware Fusion). Then start you server again. <br/>
<img width="900" alt="6" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/d11c7b67-31a6-4de2-a714-bb00ccc44288">
<br />

7 - On your taskbar you can see a computer icon. Right click it and select Open Network and Internet settings. <br/>
<img width="900" alt="7" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/cf3ccf87-739b-46a6-839d-652e7803d337">
<br />

8 - Select Change adapter options. <br/>
<img width="900" alt="8" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/85ca950d-eeca-49f3-9871-6711051f9ef5">
<br />

9 - Right click your virtual Ethernet and select Properties. <br/>
<img width="900" alt="9" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/584e2836-e93a-4f61-820c-2fc7c6be77af">
<br />

10 - Double click Internet Protocol Version 4(TCP/IPv4). <br/>
<img width="900" alt="10" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/d4728b16-62ff-45d9-a1ca-dcb7eea8d053">
<br />

11 - Enter your preferred IP settings or you can use this example. Then select OK. <br/>
<img width="900" alt="11" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/a5beb0b5-5347-4c92-a27d-36502fd6133f">
<br />

12 - Right click the windows startup logo and select Restart.  <br/>
<img width="900" alt="12" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/6942a727-d8c9-40b8-91da-69e94de56259">
<br />

13 - When you server restarts, Server Manager should open up straight away. If not cilck on the windows start up icon then select Server Manager.  <br/>
<img width="900" alt="13" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/a94a84c0-8b90-4433-ae73-bbe547e77deb">
<br />

14 - Now we need to install Active Directory Domain Services. Select Manage then Add Roles and Features. <br/>
<img width="900" alt="14" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1e86ecbd-bad6-48fd-bd98-b0e2ade00be9">
<br />

15 - Select Next. <br/>
<img width="900" alt="15" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/ebf705b2-d5d7-4adb-96d7-6a0b31ef97dd">
<br />

16 - Select Next. <br/>
<img width="900" alt="16" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/934cac36-1729-487e-b330-057749a44d01">
<br />

17 - Select Next. <br/>
<img width="900" alt="17" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/59f8ced7-d6c5-4a58-8b1a-b25ef2faf4d2">
<br />

18 - Click on Active Directory Domain Services. <br/>
<img width="900" alt="18" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/adaeb541-f6ce-4cd3-bf4c-82ae929cc6a9">
<br />

19 - Select Add Features. <br/>
<img width="900" alt="19" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/89042e27-e9b2-494f-ab65-30ac27ede6ee">
<br />

20 - Select Next. <br/>
<img width="900" alt="20" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/178a1dd4-7f42-449f-b21d-ca3584cbf8c7">
<br />

21 - Select Next. <br/>
<img width="900" alt="21" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/bc67efd1-6d6e-4a88-bf42-004f901f5751">
<br />

22 - Select Next. <br/>
<img width="900" alt="22" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/61ded300-bdb0-4fe7-bd4a-d9173c916c8d">
<br />

23 - Select Install. <br/>
<img width="900" alt="23" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/0e57da72-c374-4a1a-a372-355f6a5d0c16">
<br />

24 - Select Promote this server to a domain controller. <br/>
<img width="900" alt="24" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/5787d5f9-8ead-42c9-8a78-fef406a063a3">
<br />

25 - Select Add a new forest. Then enter your Root domain name and select Next. <br/>
<img width="900" alt="25" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/2b9b7cd0-f34a-4698-bbc8-85106eaba579">
<br />

26 - Enter your Password and confirm it then select Next. <br/>
<img width="900" alt="26" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/f3e76455-6f32-4704-b589-c6783478f9f5">
<br />

27 - Select Next. <br/>
<img width="900" alt="27" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/ee2fbbce-eae0-4010-a8e6-6940f1a7a60b">
<br />

28 - Select Next. <br/>
<img width="900" alt="28" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/a1d70f78-6f0e-4e5e-b647-df4390d2c873">
<br />

29 - Select Next. <br/>
<img width="900" alt="29" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/ca4f56e3-d495-46b4-8a16-ebe1e0cbcf02">
<br />

30 - We are going to contiune the rest of the installation using PowerShell. Select View script. <br/>
<img width="900" alt="30" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/a3f13fe1-f8b1-4df0-9624-54ea180aeb0b">
<br />

31 - Copy the whole script then close it. <br/>
<img width="900" alt="31" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/e9647ebb-f6ef-419b-ae16-316285247b86">
<br />

32 - Click Cancel then Yes. <br/>
<img width="900" alt="32" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/d377812b-8a55-4e11-b9c4-6bf6a386be4a">
<br />

33 - Select Close. <br/>
<img width="900" alt="33" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/93df8855-e071-4f27-87fd-9dc2d8a5d6e3">
<br />

34 - Close the Server Manager. <br/>
<img width="900" alt="34" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/b5d1892e-85dc-4e38-9003-fcf89fc6c725">
<br />

35 - Search for PowerShell then select Run as administrator. <br/>
<img width="900" alt="35" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/b542cbd8-6172-4a24-a66c-fe6677c70dd6">
<br />

36 - Paste in the script you copied before and hit enter. <br/>
<img width="900" alt="36" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/7d9f240f-a642-4dbb-abe7-1bba4b95a12d">
<br />

37 - Enter the passwords you created when configuring Active Directory Domain Services. <br/>
<img width="900" alt="37" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/bc03cb26-5aab-4a3e-aa1c-31404e53827d">
<br />

38 - Confirmation Active Directory Domain Services is installing. <br/>
<img width="900" alt="38" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/7752e5c6-e096-40c6-8b41-d0796a834111">
<br />

39 - The server will restart automatically. Select Close. <br/>
<img width="900" alt="39" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/297fb5c8-6921-46bc-bfb9-10a681fcae74">
<br />

40 - When the server restarts here you have the option to log in as the domain admin or local admin. Log in as the domain admin. <br/>
<img width="900" alt="40" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/c929be47-3a91-46aa-96ed-7a9663482728">
<br />

41 - On the Server Manager select Tools then Active Directory Users and Computers. <br/>
<img width="900" alt="41" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/db582e44-6f72-432e-99a0-33bc190f1e50">
<br />

42 - Confirmation that Active Directory Domain Services has been successfully installed. <br/>
<img width="900" alt="42" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/874c541c-bdbf-465d-b139-e9a53faf7759">
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
