<h1>SSH Keys Project -  Authentication, Encryption and Integrity</h1>


<h2>Description</h2>
The objective of this project is to showcase the practical application of SSH keys in enhancing security measures. Focused on utilizing SSH Key Pair in conjunction with OpenSSL, the project aims to illustrate encryption and decryption techniques applied to a text file containing sensitive data. Additionally, to ensure data integrity, the project incorporates a Git commit mechanism. Through this, the project aims to provide a comprehensive demonstration of leveraging SSH keys for improving security protocols. 
<br />

<h2>Utilities Used</h2>

- <b>SSH</b> 
- <b>OpenSSL</b>
- <b>Git</b>

<h2>Environments Used </h2>

- <b>Kali Linux</b>

<h2>Project walk-through:</h2>

<p align="center">
Genrating SSH Key Pair: <br/>
<img src="https://imgur.com/MmXcNnM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Using the rsa type key, we genreate a key pair that will be used later for registering Git signing.
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
Encrypting Text File:  <br/>
<img src="https://imgur.com/VtrIUyb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
The text file is used as our input and we use public key to encrypt. The output will be an encrypted text file.
<br />
<br />
Decrypting Text File:  <br/>
<img src="https://imgur.com/n2DpeVQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Using the generated private key to decrypt. The output will be the decrypted text file.
<br />
<br />
Decrypting Text File:  <br/>
<img src="https://imgur.com/n2DpeVQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Using the generated private key to decrypt. The output will be the decrypted text file.
 
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
