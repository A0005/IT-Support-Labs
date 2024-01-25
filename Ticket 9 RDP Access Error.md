<h1>Ticket 9 RDP Access Error</h1>

<h2>Description</h2>
This lab example shows how to solve a user trying to acces another users machine through RDP.

<h2>Environments Used </h2>

- <b>MacBook Pro (Intel)</b>
- <b>VMware Fusion</b>
- <b>Windows 10</b>
- <b>Windows 11</b>

<h2>Program walk-through:</h2>

1 - Start up both Windows 10 VM and Windows 11 VM. Log into your Windows 10 VM open Remote Desktop Connection. <br/>
<img width="900" alt="1" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/48f2ce28-2d67-43ab-b5c4-014ed4d2133e">
<br />

2	- Type in wendy (the user on the Windows 11 VM that is joined to the domain). Then hit Connect. <br/>
<img width="900" alt="2" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/bf0a505c-b3cb-4d27-aaf4-b01d74404def">
<br />

3	- You will get an error message saying that the user can not remote into the Windows 11 VM for three reasons. Select OK. <br/>
<img width="900" alt="3" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/f6c35786-4c08-4ee1-a1c7-d682951d7400">
<br />

4 - In the Windows 11 VM login with the domain user and navigate to the Remote Desktop settings. You can see that this VM is denying access through RDP. <br/>
<img width="900" alt="4" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/0c9aa4a2-6f61-441d-ac0d-60a13718953c">
<br />

5 - In the search bar type in (sysdm.cpi) and Run as administrator. <br/>
<img width="900" alt="5" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/dfeab037-3f7a-4808-b680-d9ac747616e1">
<br />

6 - Enter in the domain admin credentials. <br/>
<img width="900" alt="6" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/0ab08e0e-2828-4d88-9576-fc69c8d25036">
<br />

7 - Select the Remote tab then choose Allow remote connections to this computer. Then select Apply and OK. <br/>
<img width="900" alt="7" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1d4b2f61-f2d2-499d-a372-2aa6bada41d6">
<br />

8 - Now you can see that we can remote into this VM from another device. <br/>
<img width="900" alt="8" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/7cd99358-5c14-4e45-b0cb-a1f31d9363d1">
<br />

9 - Back in the Windows 10 VM open Remote Desktop Connection.  <br/>
<img width="900" alt="9" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/48f2ce28-2d67-43ab-b5c4-014ed4d2133e">
<br />

10 - Type in wendy (the user on the Windows 11 VM that is joined to the domain). Then hit Connect. <br/>
<img width="900" alt="10" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/b525fb87-2b0b-4a06-8ea6-b3d5a7d645cd">
<br />

11 - Login with the users Windows 10 credentials. <br/>
<img width="900" alt="11" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/c1318ae9-dbc1-46b7-99d6-c1e81dbdd37d">
<br />

12 - This time we get a different error saying that the user account (Windows 10 user) is not authorized for remote login. <br/>
<img width="900" alt="12" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/5eb4aa65-8b88-41e3-a905-a1769db1c74e">
<br />

13 - Back in the Windows 11 VM search for Computer Management and Run as administrator. <br/>
<img width="900" alt="13" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/450f5658-8591-4fff-b19a-ae335181e6b5">
<br />

14 - Enter in the domain admin credentials. Then select Yes. <br/>
<img width="900" alt="14" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/fa5cb8d6-c675-4257-9072-ca05a0c51f95">
<br />

15 - Expand Local User and Groups and select the Groups folder. Then double click on the Remote Desktop Users. <br/>
<img width="900" alt="15" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/e79db709-6792-406b-9083-4d7d4203a3ab">
<br />

16 - Select Add. <br/>
<img width="900" alt="16" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/4bf2da4f-b531-4005-a1b2-48f0e71b6f8d">
<br />

17 - Enter in Domain Users then select OK. <br/>
<img width="900" alt="17" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/a816a3a5-27c4-4b8d-a154-26ec4f8df4a3">
<br />

18 - Select Apply then OK. <br/>
<img width="900" alt="18" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1fcb7153-4951-45d2-8e9f-5692b66b865b">
<br />

19 - Back on the Windows 10 VM try to remote into the Windows 11 VM. Enter in the Windows 10 domain user credentials. <br/>
<img width="900" alt="19" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/5ad1d58c-917c-46bf-9c53-76f3861e02df">
<br />

20 - Select Yes and you will remote into the Windows 11 VM from the Windows 10 VM. <br/>
<img width="900" alt="20" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1c7fdcdf-fbb1-4a1f-94e4-b76a9354583d">
<br />

21 - Proof of completing the lab. <br/>
<img width="900" alt="21" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/75b5a66a-c520-42fd-8da8-09994e44eaf8">
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
