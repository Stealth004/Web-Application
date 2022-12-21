<h1>Securing a Cloud Application</h1>

<h2>Description</h2>
<p>Build, host, and design web application that incorporates topics from the Networking, Cloud, and Web Development. Will secure the web application with SSL certificates incorporating topics from the Cryptography and Terminal lessons. Protect the web application with Azure’s security features incorporating topics from the Network Security lesson.</p>

<h2>Languages and Utilities Used</h2>
<ul>
  <li>PowerShell</li>
  <li>Diskpart</li>
</ul>

<h2>Environments Used</h2>
<ul>
  <li>Windows 10 (21H2)</li>
</ul>

<h2>Web Application</h2>
<h3>Enter the URL for the web application that you created:</h3>
<ul>
  <li>https://brunocyberblogs.xyz/</li>
  <li>https://giordanocyber.azurewebsites.net</li>
</ul>
<p>Websites have discontinue due to expiration!!</p>

<h3>Paste screenshots of your website created (Be sure to include your blog posts):</h3>
<!-- Insert images here -->


<!--
<!--- BREAK --><!--
<h1>Securing a Cloud Application</h1>



<h2>Description</h2>
Build, host, and design web application that incorporates topics from the Networking, Cloud, and Web Development.  Will secure the web application with SSL certificates incorporating topics from the Cryptography and Terminal lessons.  Protect the web application with Azure’s security features incorporating topics from the Network Security lesson.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2 align="center">Web Application</h2>
<p>Enter the URL for the web application that you created:
<br>
[   https://brunocyberblogs.xyz/

<br>
   https://giordanocyber.azurewebsites.net        ]
<br>
 Websites have discontinue due to expiration!!
 <br>

Paste screenshots of your website created (Be sure to include your blog posts):
</p>   --> 

<p align="center"><br/>
<img src="https://imgur.com/mO2LGvZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://imgur.com/dyGmPU0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://imgur.com/4VRPevq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://imgur.com/4OsCh36.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://imgur.com/dsEDveA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://imgur.com/hxmPKJO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://imgur.com/loMvsl5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://imgur.com/ErCAFVq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h2>Day 1 Questions</h2>

<h3>General Questions</h3>
<ol>
  <li>
    <p>What option did you select for your domain (Azure free domain, GoDaddy domain)?</p>
    <ul>
      <li>GoDaddy</li>
    </ul>
  </li>
  <li>
    <p>What is your domain name?</p>
    <ul>
      <li>https://brunocyberblogs.xyz/</li>
    </ul>
  </li>
</ol>

<h3>Networking Questions</h3>
<ol>
  <li>
    <p>What is the IP address of your webpage?</p>
    <ul>
      <li>xx.xxx.xx.x</li>
    </ul>
  </li>
  <li>
    <p>What is the location (city, state, country) of your IP address?</p>
    <ul>
      <li>xxxxxxxxxxx, XX, United States</li>
    </ul>
  </li>
  <li>
    <p>Run a DNS lookup on your website. What does the NS record show?</p>
    <ul>
      <li>Server: x.x.x.x</li>
      <li>Address: x.x.x.x#53</li>
      <li>Server can’t find https://giordanocyber.azurewebsites.net: NXDOMAIN</li>
    </ul>
  </li>
</ol>


<!--BREAK of PAGE -->



<h3>Web Development Questions</h3>
<ol>
  <li>
    <p>When creating your web app, you selected a runtime stack.  What was it? Does it work on the front end or the back end?</p>
    <ul>
      <li>Runtime stack php 7.4 works on the back end of web app</li>
    </ul>
  </li>
  <li>
    <p>Inside the /var/www/html directory, there was another directory called assets. Explain what was inside that directory.</p>
    <ul>
      <li>Two other directories in the asset’s directory.  One for CSS which is the cascade styling sheet for the HTML, giving the website a colorful visual look and style.  The other is the images, which are images used to show on the website.</li>
    </ul>
  </li>
  <li>
    <p>Consider your response to the above question. Does this work with the front end or back end?</p>
    <ul>
      <li>Those are all front end uses.  CSS gives the website style and good visual look of the website. The images are shown on the website to see.  So they both are front end uses, which anyone would see when visiting the website.</li>
    </ul>
  </li>
</ol>

<h2>Day 2 Questions</h2>

<h3>Cloud Questions</h3>
<!-- Add questions and answers here -->

<!--Break  -->
<ol>
  <li>
    <p>What is a cloud tenant?</p>
    <ul>
      <li>A customer who purchases cloud computing resources. This could be an individual user, a group of users, or an entire department or company.</li>
    </ul>
  </li>
  <li>
    <p>Why would an access policy be important on a key vault?</p>
    <ul>
      <li>Key vault access policy determines whether a given security principal, namely a user, application or user group, can perform different operations on Key Vault secrets, keys and certificates</li>
    </ul>
  </li>
  <li>
    <p>Within the key vault, what are the differences between keys, secrets, and certificates?</p>
    <ul>
      <li>Azure Key Vaults provides two types of resources to store and manage cryptographic keys. Vaults support software-protected and HSM-protected (Hardware Security Module) keys.</li>
      <li>Secrets provides secure storage of secrets, such as passwords and database connection strings.</li>
      <li>Certificates supports certificates which are built on top of keys and secrets and add an automated renewal feature.</li>
    </ul>
  </li>
</ol>

<!--BREAK of this -->

<h3>Cryptography Questions</h3>
<ol>
<li>
<p>What are the advantages of a self-signed certificate?</p>
<ul>
  <li>Self-signed certificates are free.</li>
  <li>They are suitable for internal network websites and development/testing environments.</li>
  <li>Encryption and Decryption of the data is done with the same ciphers used by paid SSL certificates.</li>
</ul>
  </li>
  <li>
<p>What are the disadvantages of a self-signed certificate?</p>
<ul>
  <li>Browsers and Operating Systems do not trust self-signed certificates since a publicly trusted CA does not sign them. Browsers would not show the green lock symbol or other visual indicators of trust</li>
  <li>Attackers can generate self-signed certificates, which can be used for man in the middle (MITM) attacks, leaving users vulnerable to data thief and other forms of cyber-attacks.</li>
</ul>
  </li>
  <li>
<p>What is a wildcard certificate?</p>
<ul>
  <li>Wildcard certificate is a digital certificate that is applied to a domain and all its subdomains. Wildcard notation consists of an asterisk and a period before the domain name. Secure Sockets Layer (SSL) certificates often use wildcards to extend SSL encryption to subdomains.</li>
</ul>
  </li>
  <li>
<p>When binding a certificate to your website, Azure only provides TLS versions 1.0, 1.1, and 1.2. Explain why SSL 3.0 isn’t provided.</p>
<ul>
  <li>Azure Security SSL 3.0 Update, starting December 1, 2014 in response to an industry wide vulnerability in SSL 3.0, commonly known as POODLE. SSL 3.0 has been disabled across Azure Websites.</li>
  <li>Azure Websites has disabled SSL 3.0 for all sites by default to protect our customers from the vulnerability mentioned before. Customers no longer need to take any action to disable SSL 3.0 in Azure Websites.</li>
</ul>
  </li>
  <li>
<!-- <p>After completing the Day 2 activities, view your SSL certificate and answer the following questions:</p> -->
<p>Is your browser returning an error for your SSL certificate? Why or why not?</p>
<ul>
  <li>No, the browser has a secure lock. The connection is secure. The certificate is issued by a trusted name Microsoft Azure TLS Issuing CA 01. Which is a trusted SSL certificate.</li>
</ul>
  </li>
  <li>
<p>What is the validity of your certificate (date range)?</p>
<ul>
  <li>March 14, 2022 to March 9, 2023</li>
</ul>
  </li>
  <li>
<p>Do you have an intermediate certificate? If so, what is it?</p>
<ul>
  <li>Yes, Microsoft Azure TLS Issuing CA 01</li>
</ul>
  </li>
  <li>
<p>Do you have a root certificate? If so, what is it?</p>
<ul>
  <li>DigiCert Global Root G2</li>
</ul>
  </li>
  <li>
<p>Does your browser have the root certificate in its root store?</p>
<ul>
  <li>Yes</li>
</ul>
  </li>
  </ol>
<p>List one other root CA in your browser’s root store.</
<!--BREAKing -->
  
<h2>Day 3 Questions</h2>

<h3>Cloud Security Questions</h3>

<p>
1. What are the similarities and differences between Azure Web Application Gateway and Azure Front Door?
<br>
[   The similarities of both are 
<ul>
  <li>Both reside in front of your web application in order to protect it.</li>
  <li>They work on the Application Layer (7) of the OSI model.</li>
  <li>Their primary solution is a load balancer.</li>
  <li>They can incorporate a web application firewall (WAF) to protect against web vulnerability attacks.</li>
  <li>They have additional features such as URL path-based routing and SSL/TLS termination.</li>
</ul> 
Differences are 
<ul>
  <li>The Web Application Gateway is more regional, to protect a web application in a single region in your cloud.</li>
  <li>The Azure Front Door is more global and is better suited when you have a variety of regions in a cloud environment.</li>
</ul>
]
</p>

<p>
2. A feature of the Web Application Gateway and Front Door is “SSL Offloading.” What is SSL offloading? What are its benefits?
<br>
[   (Secure Sockets Layer) SSL offloading is the process of removing the SSL based encryption from incoming traffic to relieve a web server of the processing burden of decrypting and /or encrypting traffic sent via SSL. The benefit of SSL offloading relieves a web server of the processing burden of encrypting and decrypting traffic sent via SSL.]
</p>

<!-- BREAKING -->
<h2>Day 3 Questions</h2>

<h3>Cloud Security Questions</h3>

<strong>1. What are the similarities and differences between Azure Web Application Gateway and Azure Front Door?</strong>
<br>
[   The similarities of both are 1. Both reside in front of your web application in order to protect it.  2.  They work on the Application Layer (7) of the OSI model.  3.  Their primary solution is a load balancer.  4.  They can incorporate a web application firewall (WAF) to protect against web vulnerability attacks.  5.  They have additional features such as URL path-based routing and SSL/TLS termination.
<br> 
Differences are 1.  The Web Application Gateway is more regional, to protect a web application in a single region in your cloud.  2.  The Azure Front Door is more global and is better suited when you have a variety of regions in a cloud environment.  ]
<br>

<strong>2. A feature of the Web Application Gateway and Front Door is “SSL Offloading.” What is SSL offloading? What are its benefits?</strong>
<br>
[   (Secure Sockets Layer) SSL offloading is the process of removing the SSL based encryption from incoming traffic to relieve a web server of the processing burden of decrypting and /or encrypting traffic sent via SSL.  The benefit of SSL offloading relieves a web server of the processing burden of encrypting and decrypting traffic sent via SSL.]







<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
