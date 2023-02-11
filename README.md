# Cyber Security Interview Questions and Answer
## Questions:-
	1.Owasp Top 10
	2.Social Engineering
	3.How does work website
	4.What are the 3 types of website
	5.How are website work
	6.10 tips for secure website
	7.What is Metasploit
	8.What is Malware?
		1.Virus
		2.Worms
		3.Trojan
		4.Ransomeware
		5.Adware
		6.Spyware
		7.Rootkit
		8.Banking Trojan
	9.VPN
	10.Proxy
	11.What is 3 way Handshake
	12.What is cryptography
	13.What is different b/w Encryption, Decryption, Hashing
	14.CIA
	15.DOS/DDOS
	
	
	
### What is Cyber Security-> Protect/Secure to every activity on internet.
- Ex. System,Network, Mobile, Device Information, Technology, by the Cyber Attack is called cyber security.
    
### 1. Owasp Top 10:
- The OWASP Top 10 is a standard awareness document for developers and web application security. It represents a broad consensus about the most critical security risks   to web applications.
- 2021
  - Broken Access Control
  - Cryptographic Failures
  - Injection
  - Insecure Design
  - Security Misconfiguration
  - Vulnerable and outdated Components
  - identification and Authentication Failures
  - Security Logging and Monitoring 
  - SSRF

github
  - hello
  - lelo

### 2.Social Engineering:
#### Social engineering is a type of attack that relies on human interaction and involves manipulating individuals into divulging confidential information or performing actions that can compromise a system or network.
##### Types of Social Engineering
   - 1.Phishing: A type of attack that uses fake emails, websites, or text messages to trick individuals into revealing sensitive information, such as login credentials or credit card numbers.
     
   - 2.Baiting: A type of attack that involves leaving a physical device, such as a USB drive, in a public place in the hope that someone will pick it up and use it, infecting their system with malware.

   - 3.Vishing: A type of attack that uses voice calls, such as over the phone or through a voice-over-IP service, to trick individuals into divulging sensitive information.

   - 4.Impersonation: A type of attack that involves posing as a trusted entity, such as a customer service representative or a technical support agent, in order to gain access to sensitive information.

   - 5.Pretexting: A type of attack that involves creating a fake scenario or story to trick individuals into divulging sensitive information.
    
    ----------------------------------------------------------------------------------------

##### How To Indentify  Social Engineering Link:
      
      Typos or grammatical errors: The attacker may not take the time to proofread their emails, text messages, or websites, and may include typos or grammatical errors.
    
    
      Suspicious URLs: The attacker may use a fake website or link that looks similar to a legitimate website, but uses a slightly different URL.
    
      
       Unexpected attachments: The attacker may include an attachment in an email that, when opened, infects your computer with malware.
    
    
    
##### Prevention:
          
          1.Verify the identity of the sender
          2.Use strong passwords and enable two-factor authentication  
          3.Keep software and security systems up-to-date
          4.Educate others
     
	
## 3. How does a website work step by step?
  ### Brief:
    Step 1 - Request.
    Step 2 - Server Response.
    Step 3 - HTML generation.
    Step 4 - CSS and JavaScript.
    Step 5 - Brower Rendering.
    Step 6 - User Interaction.

 ### Explain:
 ##### Request: 
    When a user enters a URL into their web browser, A request is sent to the server where the website is hosted.
     
 ##### Server response: 
      The server receives the request and processes it, typically by using a server-side scripting language, 
      such as PHP or Ruby on Rails, to generate the content for the website.
      
 ##### HTML generation: 
      The server generates the HTML code for the website, which defines the structure and content of the page.
      
##### CSS and JavaScript: 
      The server may also generate and send CSS and JavaScript files that are used to style and add interactivity to the website.     

##### Browser rendering:
    The web browser receives the HTML, CSS, and JavaScript files from the server and uses them to render the website and display it to the user.
  
##### User interaction: 
      The user can interact with the website by clicking links, filling out forms, or performing other actions.
      

   This is a simplified explanation of how a website works, and the actual process can be much more complex, depending on the size
      This overview should give you a general idea of the steps involved in serving a website to a user.
      
      
      
## 4. What are the 3 types of websites?
  - Static website
  - Dynamic website
  - Hybrid website

#### Static website:
  - A static website is a simple type of website that is made up of HTML, CSS, and JavaScript files that are stored on a server. The content of a static website does not change dynamically and is the same for all users. Static websites are often used for personal or small business websites that do not require dynamic content or user interaction. 

#### Dynamic website:
  - A dynamic website is a type of website that generates its content dynamically in response to user actions or other events. Dynamic websites are built using server-side scripting languages, such as PHP or Ruby on Rails, and typically involve a database to store and retrieve data. Dynamic websites are often used for e-commerce, social networking, or other types of websites that require dynamic content and user interaction.
    
#### Hybrid website:
  - A hybrid website is a type of website that combines elements of both static and dynamic websites. A hybrid website may have some static content and some dynamic content, and may use a combination of server-side scripting and client-side scripting (such as JavaScript) to generate its content. Hybrid websites are often used for complex websites that require a mix of static and dynamic content and user interaction.
   These are three of the most common types of websites, but there are many other types of websites as well, including informational websites, portfolio websites, blogs, and forums. The type of website that is best for a particular purpose depends on the requirements of the website and the goals of the website owner.


## 5. How are websites hacked?
- social engineering/ phishing emails, and links, etc.
- Hackers usually use brute-force attacks
- Guessing usernames and passwords, trying generic passwords, 
- using password generator tools, 

## 6. 10 tips for secure a website:
- SSL Configuration
- Encrypt data
- Stop sql Injection
- Remove embeded sql
- Secure credential
- Enforce complex passwod
- Secure API
- Vulnerability patching 
- DDOS Protection
- PCI Compliance
- Check Version 


## 7. What is Metasploit used for?
	It allows testers to scan systems for vulnerabilities,
	conduct network reconnaissance, 
	Exploit modules—allow testers to target a specific, known vulnerability. 
	Metasploit has a large number of exploit modules, 
    including buffer overflow and SQL injection exploits.


## 8. What is malware with example?
#### Ans-: Malware is a type of software that is designed to cause harm to a computer system or network. There are several types of malware, including:
	1.Virus: A program that infects other software and replicates itself.

	2.Worm: A type of virus that spreads itself over a network without the need for a host file.

	3.Trojan: A type of malware that disguises itself as a legitimate program and is used to gain unauthorized access to a system.

	4.Ransomware: Malware that encrypts the victim's files and demands a ransom payment in exchange for the decryption key.

	5.Adware: Software that displays unwanted ads and pop-ups.

	6.Spyware: Software that tracks a user's behavior and activity without their knowledge.

	7.Rootkit: A type of malware that hides itself and its malicious activity from detection.

	8.Banking Trojan: A type of malware that is specifically designed to steal sensitive financial information, such as login credentials and credit card numbers.

	9.RAT: Remote access trojans (RATs) are malware designed to allow an attacker to remotely control an infected computer. Once the RAT is running on a compromised system, the attacker can send commands to it and receive data back in response.
	
	It is important to regularly update your computer's security software and to be cautious when downloading and installing new software to reduce the risk of infection by malware.

	
	

## 9. VPN
   - VPN stands for "virtual private network" — a service that helps you stay private online. 
    A VPN establishes a secure, encrypted connection between your computer and the internet, 
    providing a private tunnel for your data and communications while you use public networks

## 10.Proxy-: A proxy server is a system or router that provides a gateway between users and the internet.


11. what is 3 way handshake
  - SYN
  - SYN-ACK
  - ACK
	A three-way handshake is also known as a TCP handshake or SYN-SYN-ACK, and requires both the client and server to exchange SYN (synchronization) and ACK (acknowledgment) packets before actual data communication begins


12. Secure Sockets Layer (SSL) is a standard security technology for establishing an encrypted link between a server and a client

13. TCP-UDP
	TCP:- Connection-oriented protocol,
		-TCP Slower
		-Retransmission of lost data packets is only possible with TCP
	UDP:- Connectionless protocol. 
		-UDP is much faster
		
		
14. Client-Side Attack:-
	Broken Client-side Access Control.
	DOM-based XSS.
	Sensitive Data Leakage.
	Vulnerable and Outdated Components. 
	Lack of Third-party Origin Control.
	JavaScript Drift.
	Sensitive Data Stored Client-Side.
	Client-side Security Logging and Monitoring Failures.		

15. Server-Side Attacks:-
	DOS attack
	Website Defacement
	Directory Traversal
	Misconfiguration attacks
	Phishing Attack
	Information Gathering
	Vulnerability Scanning
	Password Attacks
