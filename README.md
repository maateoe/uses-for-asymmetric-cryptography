<h1>Asymmestric Keys with Commits Project </h1>


<h2>Description</h2>
The objective of this project is to showcase the practical application of asymmetric cryptography to demonstrate its uses for authentication, encryption, and integrity. This is to demonstrate real world uses of public and private keys. This project utilizes SSH Key pair and OpenSSL key pair, to encrypt and decrypt a text file containing sensitive data. Lastly, I utilized SSH key pair to configure a Git commit signing feature to ensure data integrity. These measures provide a comprehensive demonstration of using asymmetric encryption for improving different areas of security. 
<br />

<h2>Utilities Used</h2>

- <b>SSH</b> 
- <b>OpenSSL</b>
- <b>Git</b>

<h2>Environments Used </h2>

- <b>Kali Linux</b>

<h2>Project walk-through:</h2>

<p align="center">
Genrating SSH Key Pair:<br/>
<br/>
<img src="https://imgur.com/MmXcNnM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Using the rsa type key, I genreate a key pair that will be used later for registering Git signing.
<br />
<br />
<br />
<br />
Generating OpenSSL Key Pair:  <br/>
<img src="https://imgur.com/7CNeLx9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Utilizing OpenSSL to generate a key pair that will be used encrypt
<br />and decrypt a text file with a password.
<br />
<br />
<br />
Encrypting Text File:  <br/>
<img src="https://imgur.com/VtrIUyb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Using public key to encrypt file. The output will be an encrypted text file.
<br />
<br />
<br />
Decrypting Text File:  <br/>
<img src="https://imgur.com/n2DpeVQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Using the generated private key to decrypt file. The output will be the decrypted text file.
<br />
<br />
<br />
Configuring Global User Credentials and Changing Signing Key Format:  <br/>
<img src="https://imgur.com/ModrBu0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Configuring global email and name for Git repository. 
<br />Enabling Git to sign commit with existing SSH key pair insted of GPG keys.
<br />
<br />
<br />
Adding SSH Key Pair:  <br/>
<img src="https://imgur.com/LS0x56t.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Loading private key to the agent. Then, retreiving public key to be used in next step. 
<br />
<br />
<br />
Add Signers:  <br/>
<img src="https://imgur.com/GxRkmzO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Setting the public key to be recognized to be as a valid key. Adds the key to a new file called 
<br />'allowed signer' and will configure GPG signing for allowed SSH signer.
<br />
<br />
<br />
Commit Sign Test:  <br/>
<img src="https://imgur.com/TmNCHQI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Testing SSH singing by outputting a message to display. Name and Email are also displayed. 
<br />
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
