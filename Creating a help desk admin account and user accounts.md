<h1>Creating a help desk admin account and user accounts</h1>

<h2>Description</h2>
This lab example shows how to create a help desk admin account, organization units, and user accounts through Active Directory and PowerShell.

<h2>Environments Used </h2>

- <b>MacBook Pro (Intel)</b>
- <b>VMware Fusion</b>
- <b>Windows Server 2022</b>
- <b>PowerShell ISE</b>

<h2>Program walk-through:</h2>

1 - Start up your Server 2022, open Server Manager then navigate to Active Directory Users and Computers. <br/>
<img width="900" alt="1" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/3efa965c-4553-4a4a-a5fa-26e4f54b8afb">
<br />

2	- Let’s create an Organizational Unit by right clicking on your domain then select New > Organizational Unit. An organization whose resources are rationally distinct from those of other, comparable organizations is represented by an organizational unit (OU). OUs are used to maintain data segregation and manage resource access.  <br/>
<img width="900" alt="2" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/afb652de-5e88-4f0c-ae4d-90f67ec4c95e">
<br />

3	- Give it a name then select OK. <br/>
<img width="900" alt="3" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/d226c9b4-b576-4f2c-9710-5b1a6026ccf7">
<br />

4 - Now let's create a user by right clicking on the OU you just created and select New > User. The directory service in Active Directory is used by the AD user to identify people. This contains their name, department, job title, address, location, login information, and permissions. The basis of all contemporary operating systems is the user account. <br/>
<img width="900" alt="4" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/c39a9d51-5fd0-4700-ab5d-45d65472a3fc">
<br />

5 - Enter the user’s details then select Next. <br/>
<img width="900" alt="5" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/06b5401c-83e5-4d41-8aff-98f646e57f9c">
<br />

6 - Enter a password and confirm it. Since this is a lab uncheck the box that says User must change password at next logon. Then select Next. <br/>
<img width="900" alt="6" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/ac09879f-14a8-4181-b3b8-ea3cea94fdff">
<br />

7 - Select Finish. <br/>
<img width="900" alt="7" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/16544276-afc3-4380-9ca6-163458c7c1a0">
<br />

8 - Confirmation user has been created. <br/>
<img width="900" alt="8" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/c71a6ae9-3773-413a-a2a2-174abb924c51">
<br />

9 - Right click on the user and select Properties. <br/>
<img width="900" alt="9" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/2fadb72d-47b1-4e64-bd5f-cabdcde43635">
<br />

10 - Select the Member Of tab. <br/>
<img width="900" alt="10" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/d1af7954-2531-4dee-b81d-77ef2d68279b">
<br />

11 - Select Add. <br/>
<img width="900" alt="11" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1853344b-c462-4503-853b-885f2e47b499">
<br />

12 - Enter Domain Admins, select Check Names then OK. <br/>
<img width="900" alt="12" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/41700a1f-93cc-42aa-8ef8-2161665912f6">
<br />

13 - The user is now part of the Domain Admins group. Users within the domain can be assigned administrative roles using Active Directory (AD)'s Domain Admins group. It belongs to the Administrators group by default and all the rights that go along with that. <br/>
<img width="900" alt="13" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/2656eb2d-1640-4626-acaa-3a928c6a7324">
<br />

14 - Select Apply then OK. <br/>
<img width="900" alt="14" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/382dc4d7-3acd-48e4-841e-b1e8d7979176">
<br />

15 - Right click on the windows startup icon and Sign out. <br/>
<img width="900" alt="15" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/8312e31a-110b-45a2-b167-078a4260551d">
<br />

16 - Select Other user. <br/>
<img width="900" alt="16" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/97a1244a-8c26-4083-8279-ffc213290e56">
<br />

17 - Log in with the user that you created. <br/>
<img width="900" alt="17" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/ae72aebc-938a-4600-9901-22bdc658f266">
<br />

18 - Open Active Directory Users and Computers and create two more OUs. Here I created the Sales and HR OUs. <br/>
<img width="900" alt="18" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/36ea361e-886c-4d9a-a62f-4a1d18c42fde">
<br />

19 - Select View then Advanced Features. <br/>
<img width="900" alt="19" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/ff016af1-7aee-4912-bc5a-89d5ee435a8e">
<br />

20 - Right click on the new OU that you created here for example will be the HR. <br/>
<img width="900" alt="20" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/e9de6c13-6332-4a1e-a382-63b50cdebc77">
<br />

21 - Double click on the distinguishedName. <br/>
<img width="900" alt="21" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/edaae7d6-e17b-45f6-8ab0-aa31c50d67a0">
<br />

22 - Copy the vaule. We will use this when we create a script to add users to this OU. <br/>
<img width="900" alt="22" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/f05c6388-2238-411d-9e76-8ddff468c93d">
<br />

23 - Search Windows PowerShell ISE and run it as an administrator. <br/>
<img width="1042" alt="23" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/d8875924-0666-4359-9781-2df87561b621">
<br />

24 - Beside the word Script click on the drop down arrow. <br/>
<img width="900" alt="24" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/f9c2db4b-001f-4c56-8fd2-1e6a74e2196a">
<br />

25 - Click File > Save As. <br/>
<img width="900" alt="25" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/4959c44c-0947-41f4-aec6-f3eca38c59b8">
<br />

26 - Name it userEntry.ps1 then select Save. <br/>
<img width="900" alt="26" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/e274c458-2e86-4f03-abe4-342f36036b92">
<br />

27 - Here we are going to add a user to Active Directory using this script. Create this script then run it. (Paste the value of the distinguishedName that we copied earlier in the -path). <br/>
<img width="900" alt="27" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/3156accc-c34d-48a2-a8d5-f182d523f147">
<br />

28 - Edit this script with a different user then run it. (Make sure to add both users to the different OUs that you created). <br/>
<img width="900" alt="28" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/3343fdb7-ed76-4aa3-82aa-d08365f661e4">
<br />

29 - Confrimation that the user James has been added to the Sales OU with an enabled account and password. <br/>
<img width="900" alt="29" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/3d342ffd-fca7-4c2e-bd47-c66d8969ba36">
<br />

30 - Confrimation that the user Wendy has been added to the HR OU with an enabled account and password. <br/>
<img width="900" alt="30" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/8fcd6cec-46d2-43c9-8d4f-dc8e5b07ddd4">
<br />

31 - The use of this script is useful.  It will make it easier for you to enter multiple users. <br/>
<img width="900" alt="31" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/42c6452a-f6b3-4840-8769-0f446f33d4bc">
<br />

</p>
