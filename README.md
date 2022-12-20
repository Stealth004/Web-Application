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
</p>

<p align="center"><br/>
<img src="https://imgur.com/mO2LGvZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://imgur.com/dyGmPU0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://imgur.com/4VRPevq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://imgur.com/4OsCh36.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://imgur.com/dsEDveA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://imgur.com/hxmPKJO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk2:  <br/>
<img src="https://imgur.com/loMvsl5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://imgur.com/ErCAFVq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

##Day 1 Questions
###General Questions
<p>
1. What option did you select for your domain (Azure free domain,  GoDaddy domain)?
<br>
   [   GoDaddy      ]<br>

2. What is your domain name?
<br>
[   https://brunocyberblogs.xyz/    ]
<br>
<h3>Networking Questions</h3>

1. What is the IP address of your webpage?
<br>
[[    xx.xxx.xx.x   ]
<br>

2. What is the location (city, state, country) of your IP address?
<br>
[    xxxxxxxxxxx, XX, United States ]
<br>

3. Run a DNS lookup on your website. What does the NS record show?

<br>
[    Server:  x.x.x.x
<br>
  	Address: x.x.x.x#53
   <br>
    Server can’t find https://giordanocyber.azurewebsites.net:  NXDOMAIN   ]
<br>

<h3>Web Development Questions</h3>

1. When creating your web app, you selected a runtime stack.  What was it? Does it work on the front end or the back end? 
<br>
[    Runtime stack php 7.4 works on the back end of web app  ]
<br>

2. Inside the /var/www/html directory, there was another directory called assets. Explain what was inside that directory.
<br>
[	Two other directories in the asset’s directory.  One for CSS which is the cascade styling sheet for the HTML, giving the website a colorful visual look and style.  The other is the images, which are images used to show on the website.   ]
<br>

3. Consider your response to the above question. Does this work with the front end or back end?
<br>
[  Those are all front end uses.  CSS gives the website style and good visual look of the website. The images are shown on the website to see.  So they both are front end uses, which anyone would see when visiting the website.   ]
<br>


<h2>Day 2 Questions</h2>

<h3>Cloud Questions</h3>

1. What is a cloud tenant?
<br>
[  A customer who purchases cloud computing resources.  This could be an individual user, a group of users, or an entire department or company.  ]
<br>

2. Why would an access policy be important on a key vault?
<br>
[	Key vault access policy determines whether a given security principal, namely a user, application or user group, can perform different operations on Key Vault secrets, keys and certificates   ]
<br>

3. Within the key vault, what are the differences between keys, secrets, and certificates?
<br>
[  Azure Key Vaults provides two types of resources to store and manage cryptographic keys.  Vaults support software-protected and HSM-protected (Hardware Security Module) keys.
 	Secrets provides secure storage of secrets, such as passwords and database connection strings.
 	Certificates supports certificates which are built on top of keys and secrets and add an automated renewal feature.   ]
<br>

<h3>Cryptography Questions</h3>

1. What are the advantages of a self-signed certificate?
<br>
[  Self-signed certificates are free.  They are suitable for internal network websites and development/testing environments.  Encryption and Decryption of the data is done with the same ciphers used by paid SSL certificates     ]
<br>

2. What are the disadvantages of a self-signed certificate?
<br>
[   Browsers and Operating Systems do not trust self-signed certificates since a publicly trusted CA does not sign them.  Browsers would not show the green lock symbol or other visual indicators of trust
<br>
	Attackers can generate self-signed certificates, which can be used for man in the middle (MITM) attacks, leaving users vulnerable to data thief and other forms of cyber-attacks.    ]
<br>

3. What is a wildcard certificate?
<br>
[   Wildcard certificate is a digital certificate that is applied to a domain and all its subdomains.  Wildcard notation consists of an asterisk and a period before the domain name.  Secure Sockets Layer (SSL) certificates often use wildcards to extend SSL encryption to subdomains.  ]
<br>

4. When binding a certificate to your website, Azure only provides TLS versions 1.0, 1.1, and 1.2.  Explain why SSL 3.0 isn’t provided.
<br>
[   Azure Security SSL 3.0 Update, starting December 1, 2014 in response to an industry wide vulnerability in SSL 3.0, commonly known as POODLE.  SSL 3.0 has been disabled across Azure Websites. 
 	Azure Websites has disabled SSL 3.0 for all sites by default to protect our customers from the vulnerability mentioned before.  Customers no longer need to take any action to disable SSL 3.0 in Azure Websites.  ]
<br>

5. After completing the Day 2 activities, view your SSL certificate and answer the following questions:
<br>
a. Is your browser returning an error for your SSL certificate? Why or why not?
<br>
[   No, the browser has a secure lock.  The connection is secure.   The certificate is issued by a trusted name Microsoft Azure TLS Issuing CA 01. Which is a trusted SSL certificate.   ]
<br>

b. What is the validity of your certificate (date range)?
<br>
[   March 14, 2022 to March 9, 2023]
<br>

c. Do you have an intermediate certificate? If so, what is it?
<br>
[ 	Yes, Microsoft Azure TLS Issuing CA 01  ]
<br>

d. Do you have a root certificate? If so, what is it?
<br>
[   DigiCert Global Root G2  ]
<br>

e. Does your browser have the root certificate in its root store?
<br>
[   Yes    ]
<br>

f. List one other root CA in your browser’s root store.
<br>
[   Actalis Authentication Root CA]
<br>


<h2>Day 3 Questions</h2>

<h3>Cloud Security Questions</h3>

1. What are the similarities and differences between Azure Web Application Gateway and Azure Front Door?
<br>
[   The similarities of both are 1. Both reside in front of your web application in order to protect it.  2.  They work on the Application Layer (7) of the OSI model.  3.  Their primary solution is a load balancer.  4.  They can incorporate a web application firewall (WAF) to protect against web vulnerability attacks.  5.  They have additional features such as URL path-based routing and SSL/TLS termination.
<br> 
Differences are 1.  The Web Application Gateway is more regional, to protect a web application in a single region in your cloud.  2.  The Azure Front Door is more global and is better suited when you have a variety of regions in a cloud environment.  ]
<br>

2. A feature of the Web Application Gateway and Front Door is “SSL Offloading.” What is SSL offloading? What are its benefits?
<br>
[   (Secure Sockets Layer) SSL offloading is the process of removing the SSL based encryption from incoming traffic to relieve a web server of the processing burden of decrypting and /or encrypting traffic sent via SSL.  The benefit of SSL offloading relieves a web server of the processing burden of encrypting and decrypting traffic sent via SSL.]

<br>
3. What OSI layer does a WAF work on?
<br>
[    Web Application firewall (WAF) is a protocol of layer 7 defense (in the OSI model), and is not designed to defend against all types of attacks. This method of attack mitigation is usually part of a suite of tools which together create a holistic defense against a range of attack vectors.  ]
<br>

4. Select one of the WAF managed rules (e.g., directory traversal, SQL injection, etc.), and define it.

[    The WAF managed Default Rule Set (DRS) includes rules against threat categories.  SQL injection is a code injection technique used to attack data driven applications, malicious SQL statements are inserted into an entry field for execution.  Essentially SQLI is a common attack vector that uses malicious SQL code for backend database manipulation to access information that was not intended to be displayed.  ]
<br>

5. Consider the rule that you selected. Could your website (as it is currently designed) be impacted by this vulnerability if Front Door wasn’t enabled? Why or why not?
<br>
[   Yes, because SQL works as a query in the background for example login information being submitted via web.  The WAF has a variety of rules to protect against a wide range of SQL attacks.
<br> 
No, the network doesn’t have a sql database, ]

<br>
6. Hypothetically, say that you create a custom WAF rule to block all traffic from Canada. Does that mean that anyone who resides in Canada would not be able to access your website? Why or why not? 
<br>
[   No, if someone in Canada uses VPN, they would be able to access the website.  ]

<br>
7. Include screenshots below to demonstrate that your web app has the following:
<br>
a. Azure Front Door enabled
<br>
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
