<h1>Network Firewall Hardening and Traffic Control Implementation</h1>

 

<h2>Description</h2>
This project simulates an enterprise firewall hardening scenario where insecure services were identified and restricted to reduce attack surface while maintaining required functionality.
<br />


<h2>Tools Used </h2>

- <b>Windows Defender Firewall (Advanced Security)</b>
- <b>Windows Server / Windows OS</b>
- <b>Microsoft Management Console</b>

<h2>Inbound Traffic Hardening:</h2>
Phase 1: Allow HTTPS (Port 443)
<p align="center">
Secure web traffic using encryption (TLS)
<br/>
<img src="https://i.imgur.com/6luSwHK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="left">
 Phase 2: Allow SSH (Port 22) <br/>
<p align="center">
Replaces insecure remote access protocols like Telnet
<br/>
<img src="https://i.imgur.com/tV9KQIw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="left">
 Phase 3: Block Telnet (Port 23) <br/>
<p align="center">
Prevents plaintext credential exposure
<br/>
<img src="https://i.imgur.com/CqbdhEn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="left">
 Phase 4: Block SMB (Port 445) <br/>
<p align="center">
Estimated the operating system using TCP/IP fingerprinting based on network response behavior.
<br/>
<img src="https://i.imgur.com/BkUlKHD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br />
<p align="left">
 Phase 4: Block TFTP (Port 69)
<br/>
<p align="center">
Prevents unauthorized file transfers (no authentication/encryption)
<br/>
<img src="https://i.imgur.com/0i12zQ7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br />
<p align="center">
SMTP Configuration Restricted unencrypted SMTP and enforced secure email transmission
<br/>
<img src="https://i.imgur.com/fQK14Av.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h2> Security Improvements </h2>

- <b>Reduced attack surface</b>
- <b>Replaced insecure protocols with secure alternatives</b>
- <b>Implemented outbound filtering</b>
- <b>Maintained required services</b>

<h2> Skills Demonstrated </h2>

- <b>Firewall configuration</b>
- <b>Traffic filtering (inbound/outbound)</b>
- <b>Service enumeration</b>
- <b>Port-based security</b>
- <b>Risk-based decision making</b>


<h2>Ethical Statement</h2>
All activities were conducted in an isolated lab environment on authorized systems for educational and defensive security purposes only.
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
