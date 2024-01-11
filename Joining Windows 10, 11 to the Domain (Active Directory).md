<h1>Joining Windows 10, 11 to the Domain (Active Directory)</h1>

<h2>Description</h2>
This lab example shows how to join Windows 10, 11 VMs to the Domain (Active Directory).

<h2>Environments Used </h2>

- <b>MacBook Pro (Intel)</b>
- <b>VMware Fusion</b>
- <b>Windows 10</b>
- <b>Windows 11</b>

<h2>Program walk-through:</h2>

1 - To join the Windows 10 VM  to the domain, first make sure the Network Adaptar is set to Private to my Mac (this is if you are using a Mac Intel and VMware Fusion). <br/>
<img width="900" alt="1" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/fd66ac07-eda4-4a3b-bbc6-cf291813c9c7">
<br />

2	- Then start up the Windows 10 VM and like we did on the Windows Server 2022 VM fill in the Internet Protocol Version 4(TCP/IPv4) Properties (Making sure the IP address is different from any other device on the domain). <br/>
<img width="900" alt="2" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/8831ea25-8bab-46f9-a28e-0ab9ea017bf0">
<br />

3	- Also to join the Windows 11 VM to the domain, first make sure the Network Adaptar is set to Private to my Mac (this is if you are using a Mac Intel and VMware Fusion). <br/>
<img width="900" alt="3" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/765cc493-d233-43ce-87ba-b65fce072044">
<br />

4 - Then start up the Windows 11 VM and like we did on the Windows Server 2022 VM fill in the Internet Protocol Version 4(TCP/IPv4) Properties (Making sure the IP address is different from any other device on the domain). <br/>
<img width="900" alt="4" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/2b411bcb-8e28-401f-9864-c74e9a54d80d">
<br />

5 - Start the Windows Server 2022 VM and let it run in the background. In the Windows 10 VM navigate to the System in the settings, scroll down and select Advanced system settings. <br/>
<img width="900" alt="5" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1e03a6d5-dedd-4734-8fb4-96172a1dbb91">
<br />

6 - Select the Computer Name tab. <br/>
<img width="900" alt="6" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/764b0ba4-c378-4f19-94d5-9f2a43e116fc">
<br />

7 - Select Change. <br/>
<img width="900" alt="7" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/12163dee-e4c3-4a4e-8c57-cc69ce8fe1a8">
<br />

8 - Select the Domain button and enter you domain name. Then select OK. <br/>
<img width="900" alt="8" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/c006958e-2195-47df-a75f-aced631fb901">
<br />

9 - Enter in the helpdesk domain admin account credentials we created in the previous lab then select OK. <br/>
<img width="900" alt="9" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/87ad36e0-bc6c-4385-a003-f1fa308b65d0">
<br />

10 - Joining the Windows 10 VM to the domain was a success. Select OK. <br/>
<img width="900" alt="10" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/7c0021f3-555d-48a9-8c2b-4b8179e9b6a9">
<br />

11 - Select OK. <br/>
<img width="900" alt="11" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/01367638-0bdf-435f-b940-79f6f3ca8538">
<br />

12 - Select Close. <br/>
<img width="900" alt="12" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/86eb03bd-81e6-4360-8c33-c532b7e1e17d">
<br />

13 - Select Restart Now. <br/>
<img width="900" alt="13" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/969ad181-a5d8-4a35-97bb-74f84a7b7284">
<br />

14 - Now in the Windows 11 VM navigate to the System in the settings and select Domain or workgroup. <br/>
<img width="900" alt="14" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/5da6aa0d-88b7-489f-b3ac-3500fcdee05c">
<br />

15 - Like in the Windows 10 VM join the Windows 11 VM to the domain using the same steps. <br/>
<img width="900" alt="15" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/2d62aac4-57fc-48ff-8a70-dc2c2b178217">
<br />

16 - On the Windows Server 2022 VM, select the Computers folder in the Active Directory Users and Computers. You can see that James (Windows 10 VM) and Wendy (Windows 11 VM) has been added successfully to the domain.  <br/>
<img width="900" alt="16" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/2fc34de7-e9f7-4e4c-8e6a-39fd2bc70a3b">
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
