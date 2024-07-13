

<h1>Active Directory - Domain Controller and Client VMs + PowerShell Script</h1>

<h2>Description</h2>
In this lab I used VirtualBox to build two VMs. One serves as a Domain Controller on windows server 2016, in order to run Active Directory. the secodn VM is a client which is able to connect to the internet through NAT. I used a script in PowerShell to add 1,000 users to the Organization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>VirtualBox, PowerShell. Server 2016, Windows 10 Pro</b> 



<h2>Project walk-through:</h2>

<p align="center">
This is a copy of the scope and goals for the fictional comany Botium Toys, that I was provided: <br/>
<img src="https://i.imgur.com/gXCPnsq.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
Scope and goals continued:  <br/>
<img src="https://i.imgur.com/vBRW1vZ.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
Controls assessment: <br/>
<img src="https://i.imgur.com/ZCroLst.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
Controls asessment continued:  <br/>
<img src="https://i.imgur.com/xpPvOl0.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />

Controls asessment continued:  <br/>
<img src="https://i.imgur.com/xpPvOl0.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
Controls asessment continued:  <br/>
<img src="https://i.imgur.com/m4GGC2g.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
Controls asessment continued:  <br/>
<img src="https://i.imgur.com/aGAc9Uw.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
Controls asessment continued:  <br/>
<img src="https://i.imgur.com/tfVvQux.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
Controls asessment continued:  <br/>
<img src="https://i.imgur.com/wW8tvb6.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
Admins group:  <br/>
<img src="https://i.imgur.com/gj0YwNz.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
Signing in as a user not admin acc:  <br/>
<img src="https://i.imgur.com/C7Q5Fg5.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
Controls asessment continued:  <br/>
<img src="https://i.imgur.com/lykoglz.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
Controls asessment continued:  <br/>
<img src="https://i.imgur.com/xcIn6RF.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
Controls asessment continued:  <br/>
<img src="https://i.imgur.com/xcIn6RF.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
Controls asessment continued:  <br/>
<img src="https://i.imgur.com/VP5E5xP.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
Controls asessment continued:  <br/>
<img src="https://i.imgur.com/4he5bFV.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
dhcp scope:  <br/>
<img src="https://i.imgur.com/6ErjqYZ.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
dhcp scope 2:  <br/>
<img src="https://i.imgur.com/npibwdd.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
CLI Script 1:  <br/>
<img src="https://i.imgur.com/rByktDM.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
CLI script 2 ls:  <br/>
<img src="https://i.imgur.com/hQrImvm.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
CLI run script:  <br/>
<img src="https://i.imgur.com/1xnblYc.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
AD check script:  <br/>
<img src="https://i.imgur.com/Ru5m5E5.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
CMD check IPconfig:  <br/>
<img src="https://i.imgur.com/QpuZow2.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
CMD check ipfongi2:  <br/>
<img src="https://i.imgur.com/r90cZ2Y.png" height="80%" width="80%" alt="security audit"/>
<br />
<br />
check client AD:  <br/>
<img src="https://i.imgur.com/yAO8BG7.png" height="80%" width="80%" alt="security audit"/>
<br />
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
