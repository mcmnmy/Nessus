<h1>Vulnerability Management with Nessus</h1>



<h2>Description</h2>
This project covers vulnerability scanning and remediation through Nessus Essentials. I used Nessus to scan a Virtual Machine (VMWare) and ran credentialed scans to detect vulnerabilities and take action toward remediation. I rescanned to compare before and after to verify remediation. I then downloaded a deprecated version of Firefox on the VM and ran the same credentialed vulnerability scan on the machine. As expected, there was a much greater magnitude of vulnerabilities with the outdated version of Firefox. Remediation was made: uninstall of Firefox and requested all Windows updates. Vulnerabilities were greatly reduced on the next scan once these actions were complete. This was a great visual of how Windows and third-party software can raise vulnerabilities on a machine. 

<br />


<h2>Languages and Utilities Used</h2>

- <b>VMWare</b>
- <b>Nessus Essentials</b> 


<h2>Environments Used </h2>

- <b>Windows 10</b> 
<b/>
<h2>Comparing Each Vulnerability Scan</h2>
<b/>
Base VM, no credentials: <br/> <br/>
<img src="https://imgur.com/iHDiSR2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Scan with credentials: <br/> <br/>
<img src="https://imgur.com/HpZKOXH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Scan with deprecated Firefox: <br/> <br/>
<img src="https://imgur.com/WnEA9gG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Scan afer remediation: <br/> <br/>
<img src="https://imgur.com/8uIFWO6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
