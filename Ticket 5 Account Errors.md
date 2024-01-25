<h1>Ticket 5 Account Errors</h1>

<h2>Description</h2>
This lab example shows how to solve account errors related to a user that can not sign in with their credentials becasue their domain is not availabe.

<h2>Environments Used </h2>

- <b>MacBook Pro (Intel)</b>
- <b>VMware Fusion</b>
- <b>Windows Server 2022</b>
- <b>Windows 10</b>

<h2>Program walk-through:</h2>

1 - For this ticket this is the error that a user received. <br/>
<img width="900" alt="1" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/12f7e4c0-8ade-42a9-abcc-21014691abbd">
<br />

2	- First login with your local admin account (.\username). <br/>
<img width="900" alt="2" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/ad25191a-4c10-4acd-82f3-4a60834b5f7d">
<br />

3	- Navigate to the Internet Protocol Version 4 (TCP/IPv4) Properties. As we can see it is optaining DNS server automatically. <br/>
<img width="900" alt="3" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/2d47d9ae-793e-4ed1-84a4-e5856d5c7281">
<br />

4 - Select Use the following DNS server addresses and enter the Windows Server 2022 IP address. Select OK and restart the Windows 10 VM. The user should be able login this time. <br/>
<img width="900" alt="4" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/fa2ce35d-ec04-4d98-b794-821584d7ad5c">
<br />

5 - If the previous solution did not work, then navigate to the Computer Name/Domain Changes so we can remove the Windows 10 VM from the domain and rejoin it. <br/>
<img width="900" alt="5" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/31c92cd4-ee48-423e-9a21-80f209a7ed4a">
<br />

6 - Select Workgroup and enter in Workgroup (all caps). Then select OK. br/>
<img width="900" alt="6" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/474cb657-0cb5-4670-8fd0-6db3f5f39e72">
<br />

7 - Select OK. <br/>
<img width="900" alt="7" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/41f3617c-f795-48e0-94d5-9b081656ac03">
<br />

8 - Enter in the domain admin credentials. Then select OK. <br/>
<img width="900" alt="8" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/18cc89c8-369f-4529-919c-bd98ae64ee86">
<br />

9 - Select OK. <br/>
<img width="900" alt="9" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/9eb5de21-d0fb-4ae5-8ae9-2e237dd47d5f">
<br />

10 - Select OK. <br/>
<img width="900" alt="10" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/8c358d96-31d0-4d2b-84a1-a384c7520250">
<br />

11 - Select Restart Now. <br/>
<img width="900" alt="11" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/35e6745f-4e5e-4ac5-98e8-7c89d00b58b5">
<br />

12 - Login with the local admin account. <br/>
<img width="900" alt="12" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/7fc75d5c-0f8f-4425-89fa-eb601245c7e6">
<br />

13 - Navigate to the Computer Name/Domain Changes and this time join the VM back into the domain. Choose Domain and enter in the domain name. Then select OK. <br/>
<img width="900" alt="13" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1a224b83-b20e-45a3-a112-ab31a96a0062">
<br />

14 - Enter in the domain admin credentials. Then select OK. <br/>
<img width="900" alt="14" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/fb577a68-1bfa-4b78-896d-8fa1d350e7c8">
<br />

15 - Select OK and restart the VM. <br/>
<img width="900" alt="15" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/82d84d3d-e785-4017-a2bb-1135e72cde8b">
<br />

16 - Enter in a domain user credentials and login. <br/>
<img width="900" alt="16" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/14fe5f54-f574-4192-9440-b9abf4a9ed35">
<br />

17 - Open CMD. Run whoami (prints the effective username of the current user when invoked). Run whoami /fqdn (Displays the user name in fully qualified domain name (FQDN) format). Run whoami /user (prints the effective username of the current user when invoked). <br/>
<img width="900" alt="17" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/081a62a6-485c-45f2-8dab-a9f2cddba803">
<br />

18 - Proof of completing the lab. <br/>
<img width="900" alt="18" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/154b8e57-93ba-46c3-9669-2b8c9946db87">
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
