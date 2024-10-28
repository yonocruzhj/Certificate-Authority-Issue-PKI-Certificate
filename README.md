
<h1>Issue PKI Certificate</h1>


<h2>Description</h2>
The objective of this repository is to provide a comprehensive guide and tools to enable users to set up and manage a Public Key Infrastructure (PKI) for generating, signing, and managing certificates on Linux systems. This repository leverages open-source tools like OpenSSL to help users create their own Certificate Authority (CA) and issue self-signed certificates.
<br />

<h2>Goals</h2>


- Set up and configure a Certificate Authority.
- Generate private keys and issue self-signed certificates.

<h2>Languages and Tools </h2>


- <b>OpenSSL</b>

<h2>Environments Used </h2>

- <b>Kali Linux</b> 

<h2>Walk-through:</h2>

Install OpenSSL: <br/>
<img src="https://imgur.com/YUFByR5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Generate private key for CA <br/>
<img src="https://imgur.com/eQoJGTC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create self signed certificate<br/>
<img src="https://imgur.com/AfL6iWU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Generate private key for new certificate <br/>
<img src="https://imgur.com/RigQR6q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a certificate signing request (CSR) <br/>
<img src="https://imgur.com/yqCXJ4c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sign CSR with CA to produce new certificate  <br/>
<img src="https://imgur.com/zdNliYi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Verify certificate  <br/>
<img src="https://imgur.com/gW7gD4w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h1>Summary</h1>
This repository provides a complete guide and tools for setting up and managing a Public Key Infrastructure (PKI) on Linux. Using open-source tools like OpenSSL, users can create a Certificate Authority (CA), generate, and issue self-signed certificates to secure their applications and infrastructure. Ideal for administrators, developers, and teams aiming to enhance security with reliable certificate management.
