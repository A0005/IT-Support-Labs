<h1>Windows Server 2022</h1>
<h2>Description</h2>
This lab example shows how to set up a virtual Windows Server 2022 on VMware Fusion using a MacBook Pro (Intel) serving as the host machine.
<br />

<h2>Environments Used </h2>

- <b>MacBook Pro (Intel)</b>
- <b>VMware Fusion</b>
- <b>Windows Server 2022</b>
- <b>SpaceSniffer</b>

<h2>Program walk-through:</h2>

1 - First download the Server 2022 ISO from Microsoft's website and VMware Fusion from VMware's website. Then install VMware Fusion and register your license. Finally open VMware Fusion and select New from the drop down arrow. <br/>
<img width="900" alt="1" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/592bbbb7-57a9-49ae-8b1a-2bd6d7fc31b9">
<br />

2	- Select create a custom virtual machine then Contiune. <br/>
<img width="900" alt="2" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/feba0f65-2c9a-4420-9030-54097c491680">
<br />

3	- Select Microsoft Windows > Windows Server 2022 then Contiune. <br/>
<img width="900" alt="3" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/02a58ed0-4a09-4933-9cfb-fc962cbf5901">
<br />

4 - Keep the default and select Contiune. <br/>
<img width="900" alt="4" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/4d363085-2ab3-40ba-968f-153207055df4">
<br />

5 - Keep the default and select Continue. <br/>
<img width="900" alt="5" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/b57198c5-377a-469c-a417-cdd1be96151a">
<br />

6 - Select Customize Settings. <br/>
<img width="900" alt="6" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/c6d7969c-20b6-47f0-a82f-987490788290">
<br />

7 - Give your virtual machince a name then select save. <br/>
<img width="900" alt="7" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/379d5246-6908-4ef0-8c9d-b0be3294f823">
<br />

8 - Here you can customize the performance of your Server 2022 virtual machine depending on your host's resources. But an important step is to select CD/DVD (SATA). <br/>
<img width="900" alt="8" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/49fe888d-0598-4694-9704-9ab399d1a01b">
<br />

9 - Check the box that says Connect CD/DVD Drive then select the drop down menu and browse for the Server 2022 ISO that you downloaded. <br/>
<img width="900" alt="9" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/ab207a77-6e5a-404a-8257-f1de373d0afd">
<br />

10 - After that you can exit out of the Customize Settings and right click on your Server 2022 virtual machine and select Start Up. <br>
<img width="900" alt="10" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/4ad934e3-d01a-4138-899d-768eb39db39c">
<br />

11 - Select Next. <br/>
<img width="900" alt="11" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/dad3cbdd-06a1-4f87-b2be-30561c37fca3">
<br />

12 - Select Install now. <br/>
<img width="900" alt="12" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/0da2597f-258d-4f76-b77a-0684f48e71f2">
<br />

13 - Choose  Windows Server 2022 Datacenter Evaluation (Desktop Experience) then select Next. <br/>
<img width="900" alt="13" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/9d35810a-2d2a-4657-9764-8b297127d880">
<br />

14 - Check the box to agree to the software license terms then select Next. <br/>
<img width="900" alt="14" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/a4d1f7cf-7963-4533-9596-0d4d82f451d8">
<br />

15 - Select Custom. <br/>
<img width="900" alt="15" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/590698f7-a706-46dc-be94-6d5dd47acce4">
<br />

16 - Select New. <br/>
<img width="900" alt="16" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/b9b62905-2b52-40cd-9849-439214343a61">
<br />

17 - Select Apply. <br>
<img width="900" alt="17" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/c6307098-4770-4513-bddf-b4f868086de4">
<br />

18 - Select OK. <br/>
<img width="900" alt="18" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1f4b0987-9649-46f8-a563-1db0fedebbf3">
<br />

19 - Verify that the Partition you chose is of the Primary type then select Next. <br/>
<img width="900" alt="19" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/ec6139fc-9921-477e-8350-f154c8ecedff">
<br />

20 - The installation has begun; after it is finished, the virtual machine will restart itself. <br/> 
<img width="900" alt="20" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/169b53d4-b490-4a90-89c7-9639b88645cb">
<br />

21 - Create a password and reenter it again then select Finish. <br/>
<img width="900" alt="21" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1f082234-52f5-4669-a9db-d4f41eb3160b">
<br />

22 - Choose Virtual Machine from the taskbar on your host machine, then select Send Ctrl-Alt-Del. This is something you will have to do each time you wish to access the Server. <br/>
<img width="900" alt="22" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/6f3e0ba9-5dae-4d20-bac5-36f04e8fa96b">
<br />

23 - Enter your password and hit enter. <br/> 
<img width="900" alt="23" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/48374e15-b70b-41d9-8f0a-f6016f2fc87f">
<br />

24 - The Windows Server 2022 has been installed. <br/>
<img width="900" alt="24" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/7caf62a9-0673-4f9a-a3d6-38c561973f42">
<br />

25 - SpaceSniffer is a usefull tool that you can download from the internet. SpaceSniffer is a trustworthy, practical, and cost-free program for scanning data on Windows computers. You can clearly see how files and folders are organized on the computer's hard drive by using this program.<br/>
<img width="900" alt="25" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1d9ca08f-0e2b-434c-9864-d0ea750b73ac">
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
