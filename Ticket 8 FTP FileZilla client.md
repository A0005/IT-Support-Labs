<h1>Ticket 8: FTP FileZilla client</h1>

<h2>Description</h2>
This lab example shows how to set up a FTP server on Windows Server 2022, install FileZilla client on Windows 11 and connect to the FTP server through it.

<h2>Environments Used </h2>

- <b>MacBook Pro (Intel)</b>
- <b>VMware Fusion</b>
- <b>Windows Server 2022</b>
- <b>Windows 11</b>

<h2>Program walk-through:</h2>

1 - Start up your Windows Server 2022 VM and in Server Manager select Manage > Add Role and Features. <br/>
<img width="900" alt="1" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/e4853268-7300-4687-92e5-b546ad44538e">
<br />

2	- Select Next. <br/>
<img width="900" alt="2" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/66606e20-4ac0-496c-af62-f390a2a85d7c">
<br />

3	- Select Next. <br/>
<img width="900" alt="3" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/858c40b9-c9e4-480c-9cea-4bbd20fc3a20">
<br />

4 - Select Next. <br/>
<img width="900" alt="4" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/e25a9df8-972a-4650-8e46-283cd61faa13">
<br />

5 - Select Web Server (IIS). <br/>
<img width="900" alt="5" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1c5e31e0-1da8-458e-a834-fcc780a3a687">
<br />

6 - Select Add Features. <br/>
<img width="900" alt="6" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/8033dfbf-ffa0-4a6b-90fd-4c462762bd56">
<br />

7 - Select Next. <br/>
<img width="900" alt="7" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/9da594e0-509b-4f7d-b716-f9407dd0dfcd">
<br />

8 - Select Next. <br/>
<img width="900" alt="8" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/5265b595-78fa-48b1-9d35-28dd836d249a">
<br />

9 - Select Next. <br/>
<img width="900" alt="9" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/609465d8-99bf-43d1-a3fd-a98b73bf8ebc">
<br />

10 - Scroll down and check the FTP Server, FTP Service and FTP Extensibility boxes. Then select Next. <br/>
<img width="900" alt="10" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/a1af6841-4807-45dd-b098-6ce90509740d">
<br />

11 - Select Install. <br/>
<img width="900" alt="11" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/28ef03f9-6863-4caf-a8c7-d8d006cf31d7">
<br />

12 - The Web Server had been installed successfully. Select Close. <br/>
<img width="900" alt="12" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/742411f3-0796-4921-a5af-68c2f246d7a7">
<br />

13 - Navigated to the (C:) drive and double click on the inetpub folder. <br/>
<img width="900" alt="13" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/e2d467c6-ea2e-4b0c-91d8-b6f438709c49">
<br />

14 - Right-click inside the folder then select New > Folder and name it ftpdemo. <br/>
<img width="900" alt="14" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1f2da5a8-9c9b-4b80-957f-6c46113ad139">
<br />

15 - Right-click on the ftpdemo folder and select Properties. <br/>
<img width="900" alt="15" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/3eda6cf3-4d94-4112-8de5-ad8358dfebaa">
<br />

16 - Select the Security tab choose Users (YourDomainName\Users) and select Edit. <br/>
<img width="900" alt="16" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/c4b83d7b-4797-43b6-9533-5fedc0b95952">
<br />

17 - Choose Users (YourDomainName\Users) again and check the Full control box then select Apply and OK. <br/>
<img width="900" alt="17" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/8611a7d2-4f10-49b3-a97c-b3655741269c">
<br />

18 - Select OK. <br/>
<img width="900" alt="18" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/9bd64dc0-c1a5-453a-a7bd-33f896393be0">
<br />

19 - Back on the Server Manager select Tools > Internet Information Systems (IIS) Manager. <br/>
<img width="900" alt="19" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/08a40fa4-e887-404a-9798-99baec90b242">
<br />

20 - Expand your DC, right-click on the Sites folder and choose Add FTP Site. <br/>
<img width="900" alt="20" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/fae45188-5fa3-438d-b64f-da695edb83ae">
<br />

21 - Give the FTP site a name and for the Physical path navigate to the ftpdemo folder we just created in the inetpub folder. Then select Next. <br/>
<img width="900" alt="21" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/3e046935-e5f3-49ea-90bb-94234b6acfbd">
<br />

22 - For the IP Address click on the drop box and select your Windows Server 2022 IP. Check the No SSL button then select Next. <br/>
<img width="900" alt="22" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/315dba44-bd48-4e6a-9a98-f8ca7c34906d">
<br />

23 - Check the Basic box, under Allow access to click on the drop box and choose Specified users and enter in the name Administrator. Check the Read and Write box then select Finish. <br/>
<img width="900" alt="23" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/2ad61643-6f6b-4294-8c24-165c530ac289">
<br />

24 - Type firewall on the search box and open Windows Defender with Advanced Security. <br/>
<img width="900" alt="24" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/7a8ca140-cc35-4743-86a6-7b88ec5580de">
<br />

25 - Select Inbound Rules then choose New Rule. <br/>
<img width="900" alt="25" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/bd6dc0b2-d5ba-4642-9053-3e907effd2c5">
<br />

26 - Check the Predefined button, click on the drop down arrow for AllJoyn Router and choose FTP Server. Then select Next. <br/>
<img width="900" alt="26" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/31948c90-8096-499c-9956-582079b32d65">
<br />

27 - Select Next. <br/>
<img width="900" alt="27" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/0988adbd-1921-4938-9f14-c719d871f7cf">
<br />

28 - Check in all the three boxes and select Next. <br/>
<img width="900" alt="28" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/cbdf50db-12b6-42ae-b3ce-324aeb5d37d8">
<br />

29 - Select Finish. <br/>
<img width="1042" alt="29" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/0b190aa3-0bd8-49b2-8472-f79d3b908fb7">
<br />

30 - Start up your Windows 11 VM, on the web browser open FileZilla offical website and select Download FileZilla Client for Windows. <br/>
<img width="900" alt="30" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/2a4322a1-1d24-4ebb-94f0-fc746d17428d">
<br />

31 - Select Download on the first column. <br/>
<img width="900" alt="31" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/85d98d19-a4cf-49bb-a296-5e4eaca33afb">
<br />

32 - Double-click on the FileZilla setup. <br/>
<img width="900" alt="32" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/8540be78-fea5-4b04-9042-38234b390b90">
<br />

33 - Enter in your domain admin credentials. <br/>
<img width="900" alt="32" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/535d02dd-5358-422f-9b3b-28dd7db3ccf0">
<br />

34 - Select I Agree. <br/>
<img width="900" alt="33" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/2961de18-e62f-447d-b288-65b6a8b491b0">
<br />

35 - Choose the Decline buttion then select Next. <br/>
<img width="900" alt="34" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/9a008639-689f-480d-a923-b284cc26f81a">
<br />

36 - Select Next. <br/>
<img width="900" alt="35" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/6e5671fe-1e25-4985-80f6-99f634bfcc7c">
<br />

37 - Check the Desktop Icon box then select Next. <br/>
<img width="900" alt="37" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/d2568cbd-6c8c-48ad-a50b-83499ebbfcbb">
<br />

38 - Select Next. <br/>
<img width="900" alt="38" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/ba069ee9-9a12-4946-8f34-199709045966">
<br />

39 - Select Install. <br/>
<img width="900" alt="39" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/7936c407-b8bc-4eba-835b-33ec5063829a">
<br />

40 - Select Finish. <br/>
<img width="900" alt="40" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/63c189e5-f126-4350-848a-d862a86c403c">
<br />

41 - FileZilla should open up automatically. Select OK. <br/>
<img width="900" alt="41" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/cb42115f-2b72-4136-9658-aebbfd39c0aa">
<br />

42 - In the host enter in the Windows Server 2022 IP Address, Username will be Administrator (This will be your Domain Administrator), Password will be your Domain Administrator's password. Then select Quickconnect. <br/>
<img width="900" alt="42" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/7399972e-f4ae-4d14-8ac5-e486f833261b">
<br />

43 - Select OK. <br/>
<img width="900" alt="43" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/4d6119a0-f783-46eb-8fc6-f2d177c3242d">
<br />

44 - Select OK. <br/>
<img width="900" alt="44" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/8dc0d248-2622-41d5-8084-8dc37537e5e8">
<br />

45 - Now we are connected to the FTP Server. On the Remote site area, right-click inside the ftpdemo folder and choose Create new file. <br/>
<img width="900" alt="45" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/2f0a72b6-f28e-4cc3-ac76-46b9853b2220">
<br />

46 - Name it the Windows 11 username. Then select OK. If you go back to the ftpdemo folder on the Windows Server 2022 you will see the file that you just created. <br/>
<img width="900" alt="46" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/7b447baa-232b-4c4a-9b1d-cc863b7009ed">
<br />

47 - Proof of completing the lab. <br/>
<img width="900" alt="47" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/b9efa705-3e29-4cda-947c-5b1c3be5415a">
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
