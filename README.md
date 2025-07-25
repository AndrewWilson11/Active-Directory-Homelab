<h1>Active Directory Homelab</h1>

<h2>Description</h2>
This project will document my experience using Oracle VirtualBox to explore Active Directory and complete an assortment of different tasks.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Command Prompt</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
-  <b>Server 2022</b>
-  <b>Oracle VirtualBox</b>

<h2>Program walk-through:</h2>

<p align="center">
Installing Windows: <br/>
<img src="https://imgur.com/M2yes1V.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />
Active Directory Setup:  <br/>
<img src="https://imgur.com/K6Q2hmA.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/6P0rDO3.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating a user in AD using "Copy", and looking them up using Command Line:  <br/>
<img src="https://imgur.com/Y9n00eD.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/oYzDSwU.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />
Installing RSAT Tools on a separate machine, setting static IP's, and connecting it to the domain:  <br/>
<img src="https://imgur.com/hzUToNF.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/mfZ76B7.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/T01OMDe.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/eDyN0KN.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />
Password reset for the "Helpdesk" user so they can log into to our domain:  <br/>
The user is connected, logged in, and has access!:  <br/>
<img src="https://imgur.com/SWGwkeQ.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/aUGBE9t.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating OU's and changing Password Policy in Group Policy Management:  <br/>
<img src="https://imgur.com/1fR1aHP.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/E8NeQ5s.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/TmYXtgh.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/ha9FptN.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/cCAuqLA.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/6IoIDfi.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/HkZD2fU.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />
Unlocking an Account for a User (patty):  <br/>
<img src="https://imgur.com/KNKAObi.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/v9yIco5.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/5RPGm5E.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />
Re-Enabling a disabled account(patty):  <br/>
<img src="https://imgur.com/woE6al1.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/ezMnPTi.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/XxIm9Ls.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/5RPGm5E.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />
User cannot log in due to disabled computer (helpdesk):  <br/>
<img src="https://imgur.com/G1BoYwt.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/uLuxxZj.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/dxW1R87.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating Share Folders:  <br/>
<img src="https://imgur.com/2tlOBFy.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/hSYxzTL.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/VxgCR3j.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating security groups for the share folders and adding a user:  <br/>
<img src="https://imgur.com/w8ypX1w.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/9QpVOlN.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/EpqMgQE.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/wa29Yjg.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />
Adding group permissions to the share folders:  <br/>
<img src="https://imgur.com/vBaCRGR.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/6abrJB1.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />
User patty now has access to the share folders, and newtwork drive has been mapped for the "hr" folder:  <br/>
<img src="https://imgur.com/6f5OSgP.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/SF79Z4Z.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/sXUaK4R.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />
Giving the user patty another share drive from the "personal" share folder:  <br/>
<img src="https://imgur.com/ZFqubLa.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/kz1owva.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />





<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
