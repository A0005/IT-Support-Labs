<h1>Ticket 26: Machine Restore</h1>

<h2>Description</h2>
This lab example shows how to restore a user's whole system onto a new machine using Veeam.

<h2>Environments Used </h2>

- <b>MacBook Pro (Intel)</b>
- <b>VMware Fusion</b>
- <b>Windows 11</b>
- <b>Windows Server 2022</b>
- <b>Veeam</b>


<h2>Program walk-through:</h2>

1 - Complete Ticket 25 in order to continue this lab. Select Recovery media. <br/>
<img width="900" alt="1" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/c81ab9af-053b-4107-ab0c-3973c1246e79">
<br />

2	- Select Next. <br/>
<img width="900" alt="2" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/0d98cbff-d09a-47e2-b74b-5ea72b8df5bd">
<br />

3	- Select Next. <br/>
<img width="900" alt="3" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/6f7b14b1-c652-42d2-9b99-daea689aab26">
<br />

4 - Select Create. <br/>
<img width="900" alt="4" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/5ca37873-0d59-4e06-b63b-38a819f33ec9">
<br />

5	- After the whole processes completes select Finish. <br/>
<img width="900" alt="5" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/df8dae30-42d8-4712-8722-23655f57d196">
<br />

6	- Naviagte to the Documents folder for the Admin user and move the ISO either to a USB or shared folder. (In my case I moved it to a USB drive) <br/>
<img width="900" alt="6" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/05e567ec-0639-46d4-86e3-8edd632ae29f">
<br />

7 - Create a new virtual machine exactly like the Windows 11 with the same specs and add in the ISO that we just created. Boot up the virtual machine and select Bare Metal Recovery. <br/>
<img width="900" alt="7" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/db92235f-f93f-4df6-b356-b5089d6f6481">
<br />

8	- Choose Network storage then Select Next. <br/>
<img width="900" alt="8" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/32ede744-d58b-475b-81d6-6d0a961117d1">
<br />

9	- Select Next. <br/>
<img width="900" alt="9" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/97886c3c-23f9-40fe-ae0b-1234149904da">
<br />

10 - Enter in your shared folder path then check the box that says This share requires access credentials and enter in your admin credentials. Then select Next. <br/>
<img width="900" alt="10" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/14323a53-ebca-4810-af0e-eee3458463aa">
<br />

11 - Select Next. <br/>
<img width="900" alt="11" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/94632e2e-733e-4089-89fd-233826c4f243">
<br />

12 - Select Next. <br/>
<img width="900" alt="12" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/431aa9c7-2aa9-48d8-8739-d2a3ef5d8377">
<br />

13 - Select Next. <br/>
<img width="900" alt="13" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/dab747eb-9ace-41b1-908b-9287d7ec19e2">
<br />

14 - Select Restore. <br/>
<img width="900" alt="14" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/022c2acb-df60-4782-9c21-cb665575b014">
<br />

15 - After the whole processes completes select Finish. <br/>
<img width="900" alt="15" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/9be6cab7-cf26-486d-bdcf-45afe8c51a5a">
<br />

16 - Select Yes. <br/>
<img width="900" alt="16" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/4aed10a8-bcbf-4dd9-be80-5e0ba08aa4e1">
<br />

17 - System has been fully restored login into the Windows 11 virutal machine. <br/>
<img width="900" alt="17" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/a496cbb8-6ef0-4526-a785-ff4f773b4506">
<br />

18 - Proof of completing the lab. <br/>
<img width="900" alt="18" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/e71e5fd6-ddde-4d66-ac64-33fc7673600a">
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
