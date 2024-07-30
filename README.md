<h1>Active Directory Home Lab</h1>

<h2>Description</h2>
Project guides you through creating an Active Directory Home Lab environment using Oracle Virtual Box and creating users via PowerShell. It's designed to help you understand the fundamentals of Active Directory and Windows networking.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle Virtual Box</b>

<h2>Environments Used </h2>

- <b>Windows 11</b> (23H2)
- <b>Server 2022</b>

<h2>Downloads:</h2>

<p align="left">
Oracle Virtual Box: <br/>
<img src="https://imgur.com/Sb8p938.png" height="40%" width="40%" alt="Downloads"/>
<br />

<p align="left">
Windows 11 (23H2): <br/>
<img src="https://imgur.com/t27PujP.png" height="40%" width="40%" alt="Downloads"/>
<br />

<p align="left">
Server 2022: <br/>
<img src="https://imgur.com/REN9tTk.png" height="40%" width="40%" alt="Downloads"/>
<br />

<h2>Logical Diagram:<h2/>
<p align="center">
Network Diagram <b>
  <img src="https://imgur.com/qlsMQkR.png" height="60%" width="60%" alt="Downloads"/>
</b>
  
<h2>Program walk-through:</h2>

<p align="center">
Create our Virtual Machines: <br/>
<img src="https://imgur.com/zGJeHIV.png" height="60%" width="60%" alt="AD home lab"/>
<br />
Insert Guest Additions Cd Image:  <br/>
<img src="https://imgur.com/9kHHx4i.png" height="60%" width="60%" alt="AD home lab"/>
  <br/>
Setting up IP addressing: <br/>
<img src="https://imgur.com/ffqTK9g.png" height="60%" width="60%" alt="AD home lab"/>
  <br />
Renaming the Pc: <br/>
<img src="https://imgur.com/RUvel2z.png" height="60%" width="60%" alt="AD home lab"/>
<br />
Installing Active Directory Domain Services onto Domain Controller(DC): <br/>
<img src="https://imgur.com/l6E7kBA.png" height="60%" width="60%" alt="AD home lab"/>
<br />
Post Deployment configuration: <br/>
<img src="https://imgur.com/cEEU11u.png" height="60%" width="60%" alt="AD home lab"/>
<br />
Creating a Domain Admin: <br/>
<img src="https://imgur.com/bbxPYTT.png" height="60%" width="60%" alt="AD home lab"/>
<br />
Installing and configuring RAS / NAT: <br/>
<img src="https://imgur.com/3RvURJZ.png" height="60%" width="60%" alt="AD home lab"/>
<img src="https://imgur.com/ofhnTxK.png" height="60%" width="60%" alt="AD home lab"/>
<br />
Setting up / configuring DHCP Scope: <br/>
<img src="https://imgur.com/ZPibCyR.png" height="60%" width="60%" alt="AD home lab"/>
<br />
Creating +1K users: <br/>
<img src="https://imgur.com/yUXSsuo.png" height="60%" width="60%" alt="AD home lab"/>
<img src="https://imgur.com/SZSHCCD.png" height="60%" width="60%" alt="AD home lab"/>
<br />
Creating a new VM called CLIENT1(The User): <br/>
<img src="https://imgur.com/WEQkBb3.png" height="60%" width="60%" alt="AD home lab"/>
<br />
CLIENT1 is pinging to the internet: <br/>
<img src="https://imgur.com/lKq1oc2.png" height="60%" width="60%" alt="AD home lab"/>
<br />
Join CLIENT1 to DC: <br/>
<img src="https://imgur.com/9JWczQk.png" height="60%" width="60%" alt="AD home lab"/>
<br />
Client computer requested an address in which the DHCP server gave: <br/>
<img src="https://imgur.com/tQI0r9n.png" height="60%" width="60%" alt="AD home lab"/>
<br />
Shows that CLIENT1 is a member of the domain: <br/>
<img src="https://imgur.com/oYWfxOu.png" height="60%" width="60%" alt="AD home lab"/>
<br />
Logging in with a random user that was genearted: <br/>
<img src="https://imgur.com/hSYKQix.png" height="60%" width="60%" alt="AD home lab"/>
<img src="https://imgur.com/sQFVwBg.png" height="60%" width="60%" alt="AD home lab"/>
<img src="https://imgur.com/ppqQ8HA.png" height="60%" width="60%" alt="AD home lab"/>
<br />
