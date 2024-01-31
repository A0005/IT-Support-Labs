<h1>Ticket 12: Deploy Software (Chrome)</h1>

<h2>Description</h2>
This lab example shows how to deploy a software (Chrome) using PDQ Deploy.

<h2>Environments Used </h2>

- <b>MacBook Pro (Intel)</b>
- <b>VMware Fusion</b>
- <b>Windows Server 2022</b>
- <b>Windows 11</b>
- <b>PDQ Deploy</b>

<h2>Program walk-through:</h2>

1 - Start up your Windows Server 2022 VM, open a web browser, naviagte to PDQ's offical website and select Start a free trial. <br/>
<img width="900" alt="1" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/bc61ac7f-33f9-4e9b-95c1-7ed5074d40e1">
<br />

2	- After signing up select Download PDQ Deploy and Inventory. <br/>
<img width="900" alt="2" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/425b6d6a-e9c1-4d61-adaa-7cf62da06f24">
<br />

3	- On the Deploy tab select Download installer then open the file once the download completes. <br/>
<img width="900" alt="3" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/0804a63d-58ff-4ac1-86f8-d8b039a0b1cc">
<br />

4 - Select Next. <br/>
<img width="900" alt="4" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/46ec6956-04b6-4cb9-9388-d58316502dc2">
<br />

5 - Agree to the terms then select Next. <br/>
<img width="900" alt="5" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/2bc87b3f-a3fc-4b81-9e23-f00e733f526d">
<br />

6 - Select Next. <br/>
<img width="900" alt="6" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/2035a186-5732-4908-a826-ef0fa3d75d71">
<br />

7 - Select Install. <br/>
<img width="900" alt="7" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/f1ba3380-73eb-4641-ae1e-40884df01d8c">
<br />

8 - Select Finish. <br/>
<img width="900" alt="8" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/704a37c5-bfb0-49a5-8d74-f2ee14fcd5cd">
<br />

9 - Select Next. <br/>
<img width="900" alt="9" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/607a6fdb-a936-44f1-8d7a-c0f1852549f0">
<br />

10 - Select Enter license key. <br/>
<img width="900" alt="10" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/80e21ef5-702d-4d3b-a78a-cfbb2c300f29">
<br />

11 - Go back to the web browser and on the Deploy tab select Copy license key then paste it here. Then select OK. <br/>
<img width="900" alt="11" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/db59c1ac-927c-4e34-ab09-4970a5a6084d">
<br />

12 - Select Next. <br/>
<img width="900" alt="12" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/c9309cc4-e8a3-4d9a-b4ac-01b2de5ead87">
<br />

13 - Select Next. <br/>
<img width="900" alt="13" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/6f3707fc-3b91-4fd9-85a7-c07a5a564e51">
<br />

14 - Enter in the domain admin password. Then select Finish. <br/>
<img width="900" alt="14" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/7783ce77-825a-4223-bd2a-ae3ae80aeb36">
<br />

15 - Back on the web browser download chrome for windows in msi file type.  <br/>
<img width="900" alt="15" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/4a7065b1-4faa-4042-b266-f8525969ffb2">
<br />

16 - Open the PDQ Deploy application and select New Package from the action bar. <br/>
<img width="900" alt="16" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/43bc0f9e-b5a8-496f-9615-f5aa953705cc">
<br />

17 - In the Properties tab name the application chrome. <br/>
<img width="900" alt="17" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1897e27c-5c94-417f-9b43-00c64ce7c2f7">
<br />

18 - On the Steps tab select Install. <br/>
<img width="900" alt="18" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/014511c5-20f0-4d55-96e0-593e231ff218">
<br />

19 - For the Step Title name it step 1. For the Install File navigate to the chrome msi file type that you downloaded earlier. Then select Save and close this package. <br/>
<img width="900" alt="19" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/d145d258-19d9-407c-89d5-70ed50a1e61c">
<br />

20 - Select the chrome package you just created then select Deploy > Deploy Once. <br/>
<img width="900" alt="20" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/965ed874-eec7-4a9f-9f01-749b763a214a">
<br />

21 - Select Choose Targets > Active Directory > Computers. <br/>
<img width="900" alt="21" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/ff64fe3c-380f-49b0-9037-ae63386d9984">
<br />

22 - In the computers filter in the middle choose the computer you want to deploy the chrome package to then choose the > arrow to move it to the other side. Then select OK. <br/>
<img width="900" alt="22" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/83be7c87-90da-43ed-bcc8-91c5df7f65dd">
<br />

23 - Select Deploy Now. (Before deploying make sure the computer you are deploying to is on, connected to the domain and is able to be pinged from the Windows Server 2022). <br/>
<img width="900" alt="23" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/7424781a-f051-4dea-bab2-61747a4743eb">
<br />

24 - Proof of completing the lab. <br/>
<img width="900" alt="24" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/54d5229f-1ec9-416a-91af-a94f5c94d683">
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
