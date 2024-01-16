<h1>Ticket 3: Access to the sales folder</h1>

<h2>Description</h2>
This lab example shows how to create, share and map a folder.

<h2>Environments Used </h2>

- <b>MacBook Pro (Intel)</b>
- <b>VMware Fusion</b>
- <b>Windows Server 2022</b>
- <b>Windows 10</b>

<h2>Program walk-through:</h2>

1 - In the Server 2022 VM open file explore. Then double click Local Disk (C:). <br/>
<img width="900" alt="1" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/cfa50e93-f094-425f-84e1-4d53e4d318d2">
<br />

2	- Inside Local Disk (C:) right click then select New > Folder. Name it groupfiles. <br/>
<img width="900" alt="2" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/149c1770-f9d0-4a1b-b6b1-f543283a4907">
<br />

3	- Inside the folder groupfiles create another folder and name it Sales. <br/>
<img width="900" alt="3" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/3fb0f3fa-2359-4b0a-b512-36c8a452ccf6">
<br />

4 - Go back and right click on the folder groupfiles then select Properties. <br/>
<img width="900" alt="4" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1caf547a-c65f-4fbe-b790-309993eeb71a">
<br />

5 - Select Advanced Sharing. <br/>
<img width="900" alt="5" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/0440ddec-e9cb-40c1-b2d0-50d1933c37e6">
<br />

6 - Check the box that says Share this folder then select Permissions. <br/>
<img width="900" alt="6" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/ca6dbfb1-cb6d-435b-992c-96363990bc41">
<br />

7 - Check both boxes Full Control and Change for the Everyone group. Then select Apply and OK. <br/>
<img width="900" alt="7" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1fc7d60a-04ea-4ade-a014-2de8f9c55794">
<br />

8 - As you can see the groupfiles folder has been shared to everyone on the network. <br/>
<img width="900" alt="8" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/3874b66a-2c75-4737-923a-92eaf3a97568">
<br />

9 - This time go in to the Sales folder's Advanced Sharing, check the box that says Share this folder then select Permissions. <br/>
<img width="900" alt="9" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/875aa1ea-4910-42ee-826a-abcb26be4d36">
<br />

10 - Select Add. <br/>
<img width="900" alt="10" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1fd2fb43-b06e-4496-b8cf-d5ca1afbea5d">
<br />

11 - Enter the user that needs access to the Sales folder in the field (select check names) then select OK. Then select Apply and OK to all the settings. <br/>
<img width="900" alt="11" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/3044cf8c-89a8-48fb-86eb-837829ed658e">
<br />

12 - Log/Remote into the users PC. <br/>
<img width="900" alt="12" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/03be8b60-387c-4dd9-a65f-c9d36786fd22">
<br />

13 - Open file explorer and navigate to the Shared path (\\servername\groupfiles). You can see that it will pop up for you. <br/>
<img width="900" alt="13" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/c856e4a5-7ca0-42dd-8d5a-9724ac0219d6">
<br />

14 - Double click the Sales folder. <br/>
<img width="900" alt="14" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/6359c821-8a86-4efb-b958-3f60c7012210">
<br />

15 - As you can see the user now has access to the Sales folder. <br/>
<img width="900" alt="15" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/6d2f6418-deec-4fb2-a0d9-79c047ec5103">
<br />

16 - Now let's map the drive for the user. Right click on This PC then select Map network drive. <br/>
<img width="900" alt="16" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/c5e6024f-483d-43bd-a41e-9672f94c108c">
<br />

17 - Enter in the network path for the Sales folder (\\servername\groupfiles\Sales) then select Finish. <br/>
<img width="900" alt="17" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/680c45cc-550d-4826-821a-a3fb95c2187f">
<br />

18 - Confirmation that the Sales folder has been mapped for the user. <br/>
<img width="900" alt="18" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/86814d57-32cc-411a-80e5-50047b6857bf">
<br />

19 - Proof of completing the lab. <br/>
<img width="900" alt="19" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/3d5b4fcf-e03f-4232-afe4-98dd224d3bc4">
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
