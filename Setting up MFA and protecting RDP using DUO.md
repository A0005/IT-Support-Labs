<h1>Setting up MFA and protecting RDP using DUO</h1>

<h2>Description</h2>
This lab example shows how to set up MFA on Windows Server 2022 and protect RDP using DUO.

<h2>Environments Used </h2>

- <b>MacBook Pro (Intel)</b>
- <b>VMware Fusion</b>
- <b>Windows Server 2022</b>
- <b>DUO</b>

<h2>Program walk-through:</h2>

1 - First create a free trial account on https://duo.com/. Then log into the admin portal. Expand the Users tab and select Add User. <br/>
<img width="900" alt="1" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/527bdf1c-1099-45db-85c4-5c48b884c5cd">
<br />

2	- Enter a username then select Add User. An object that represents a user of the programs and services you use Duo to secure is called a Duo user. Both usernames and username aliases for Duo users must be distinct. <br/>
<img width="900" alt="2" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/ef586d7f-1879-4909-b05d-db460da937a5">
<br />

3	- Enter your Full name and Email. Then scroll down and select Save Changes. <br/>
<img width="900" alt="3" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/b1cf6197-0546-4fc3-b597-3a878cb75367">
<br />

4 - Select Bulk Enroll Users. In the Users CSV enter your username followed by a comma and email (username,example@outlook.com). Then select Send Enrollment Links. <br/>
<img width="900" alt="4" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/5d1b1649-7592-4939-839f-b80865728193">
<br />

5 - Open your email and click on the enrollment link. Select how you would like to receive your MFA. I chose Duo Mobile. <br/>
<img width="900" alt="5" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/b2c6dafc-87fc-4b61-bbf5-639be1541898">
<br />

6 - Enter your phone number. <br/>
<img width="900" alt="6" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/75072d30-f2b4-41ba-8452-cf3571c27347">
<br />

7 - Scan the QR code using your Duo Mobile app. <br/>
<img width="900" alt="7" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/8e6098fe-e306-423d-8c88-941d86ab5258">
<br />

8 - Confirmation that the enrollment was a success. <br/>
<img width="900" alt="8" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/2b9c6a69-4468-449e-8e8b-6a4a2e0d4029">
<br />

9 - Start up your Windows Server 2022 machine and log into your Duo admin portal using a web browser. <br/>  
<img width="900" alt="9" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/b1b50a54-d4bc-435a-8052-556a5fc634f3">
<br />

10 - Select the Applications tab. <br/>
<img width="900" alt="10" src="https://github.com/A0005/IT-Support-Labs/assets/103763124/1225d3d3-173d-457b-9436-1107f593eaf3">
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
