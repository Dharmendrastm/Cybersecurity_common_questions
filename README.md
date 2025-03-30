# Cybersecurity_common_questions

Father of Cybersecurity :- BOB Thomas.

Father of Networking :- Dr Ivan misner.

Linux Invented by :- Linus trovald.

---

 # **What is Cyber security?**

Cybersecurity protects computer sytem network and data from theft damage and unauthorised access. It Important to safeguard sensitive information , maintain privacy and prevent financial losses and protect critical infrastructure from cyber threats.

# **What is Information security?**

Information security is the process of employed to safeguard inforamtion in any form (Physical or electronic) from unauthorised accessed, discloure and destruction.

---
# **What is CIA traids?**

The CIA traids is foundational model in cybersecurity, standing for Confidentiality, Intergrity and Availability. It outlines the three essential principle that ensure the protection of data.

**Confidentiality**:- Refers to protecting sensitive infromation from unauthorised access or disclousre.

**Integrity**:-Refers to maintain acuuracy and consistency of the data. that is not tempered with or modified in unauthorised manner.

**Availability**:- Refers to ensuring that system data and resources are avialable and accessible to authorised user when needed.

---

# **Explain Vulnerability, Threats, Exploit and Risk?**

**Vulnerability**:-A Vulnerability is a flaw, loopholes, oversight and error that can be exploited by violate system security policy.

**Threats**:-A threat is an event, natural or man-made able to cause the negative impact of an organisation.

**Exploit**:-An Exploit is defined as way to  breach the security of an IT System through a Vulnerability.

**Risk**:-It is situation involving exposure to danger.

---
# **What is AAA?**

It is stand for Authenticaton, Authorization and Accounting. It is framework for controlling access to resources and proper identify verification and tracking the use of system resources.

**Authentication**:- Authentication is the process of verifying the identify a user, device or system attempting a access a network or resources.

**Authorization**:- Authorization is the process of granting access to resources or infromation based on user's identify role or  privileges.

**Accounting**:- Accounting is refers to tracking and record the action performed by a user or system. It helps monitor activities,create logs and maintain audit trails for future analysis and complinace purposes.

---

# **Define Identification**

Identification is the process of reognizing and uniquely identifying user within system or application. It establishe who the user.

---

# **What is 3-way Hanshake?**

A three way handshake is a method of TCP/IP network to create a connection  between a local host/ client and server.

**SYN(SYNCHRONIZE)**:- The client send a SYN message to the server to initiates connection.

**SYN-ACK**:- The server sends (SYN-ACK) packets to the client . if it has open ports.

**ACK(Acknowledgement)**:- The client sends an (ACk) packet to confirm the connection is establish.

----

# **What is SSL/TLS handshake?**
--SSL Stand for  Secure Scoket layer.

--Netscape was developed the first version of SSL in 1995.

--SSL is a cryptographic protocol that uses explicit connections to establish secure communication between webserver and client.

--Three version of SSL have been released SSL 1.0,2.0 and 3.0 .

**TLS**

--TLS Stand for Transport Layer Security.

-- the first version of TLS was developed by the internet engineering taskforce (IETF) in 1999.

-- TLS is also a cryptographic protocol that provides secure communication between webserver and client via implicit connections.

-- Four version of TLS have been released TLS 1.0, 1.1, 1.2 and 1.3.


---

# **Accounting and Auditing**
**Accounting**

Accounting is refers to tracking and recording to the action performed by a user or system. It helps monitor activities, create logs, and maintain audits trails for future analysis and compliance purposes.

**Auditing**

The portion of accouting requires security professionals to examine logs of what was recorded.

---

# **Encryption , Encoding  and Hashing**

**Encryption**:-Protect data confidentiality by transforming plaintext into cipher text.

**Decryption**:- Reversible with the correct decryption key.

EX:- AES, RSA

**Encoding**:- Transform data into a different format for proper interpretion by systems.

**Decoding**:- Reversible using a decoding scheme.

EX:- Base64, ASCII ,URL ,encoding

**Hashing**:-  Ensure data integrity by transforming data into a fixed-size string.


Ex:- MD5, SHA-1 , SHA-256

---

# Difference between TCP and UDP


| Feature            |It stands for TCP (Transmission Control Protocol) |It stands for UDP (User Datagram Protocol) |
|--------------------|----------------------------------|----------------------------|
| **Type**          | It is a connection-oriented  protocol           |It is a  connectionless protocol      |
| **Acknowledgment**| Acknowledgment is received                        |Acknowledgment is not received              |
| **Speed**        | TCP is omparatively slower than UDP          | UDP is Faster, simpler, and more efficient than TCP |
| **Usage**        | Used by HTTP, HTTPS, FTP, SMTP, Telnet | Used by DNS, DHCP, TFTP, SNMP, RIP, VOIP |

---
# What is Firewall and Why it is used?
The Firewall is a network Security system  set on boundaries of the system/network that monitors and controls network traffic.
Firewall is mainly used  to protect the system/network from viruses, worms, malware, etc. Firewalls can also be to prevent remote access and content filtering.

# What is web Application Firewall?
The Web application firewall helps to protect web applications by filtering and monitoring the HTTP traffic between a web application and the internet.

---
# IDS and IPS

IDS (Intrusion Detection System): Monitors network traffic and generate suspicious activity is detected.

IPS(Intrusion Preventation System): Not Only Detects but also actively block orprevent suspicious network activity.

---
# What is VPN?
A VPN (Virtual Private Network) is a technology that creates a secure and encrypted connection between your device and the internet, protecting your online privacy and data. It hides your IP address and encrypts your internet traffic, making it difficult for hackers, governments, and ISPs (Internet Service Providers) to track your online activities.

**How VPN Works?**

Encryption – A VPN encrypts your internet connection, preventing third parties from intercepting your data.

Tunneling – It creates a secure tunnel between your device and a VPN server, ensuring data travels safely.

IP Masking – Your real IP address is replaced with the VPN server’s IP, making your location and identity anonymous.

---
# **What is OSI Model?**

--OSI stand for open system interconnections a reference model that descibes how information from a software appliactions in one computer moves through a physical medium to the software application in another computer.

The OSI model is developed by International Organisation for standardization (ISO) in 1984.

-- OSI model consist of seven layers and each layer performs particular network function.

--Upper layer of the OSI model mainly deals with the application related issues and they are implemented only in the software.

--Lower layer of the OSI model deals with the data transport issues. the data link layer and the  physical layer are implemented in hardware and software.

----

**Application Layer**

--Application layer interface directly interacts with the application and provides common web application services.

**Protocol**:- HTTP, FTP, SMTP, POP, SNMP, DHCP.

**Attack**:- Exploit.

---

**Persentation Layer**

--Responsible for Translate, encrypt, and compress data.

**Protocol**:-SSL, TLS, ASCII, JPEG, MPEG.

**Attack**:- Phishing.

---

**Session Layer**

--To establish, manage, and terminate sessions.

**Protocol**:- NetBios, PPTP, RPC, SIP, SSH.

**Attack**:- Hijacking.

---

**Transport Layer**

--Provide reliable end to end communication solution.

--From Segments

**Protocol**:- TCP, UDP, SCTP, DCCP, SPX.

**Attack**:- Reconnaissance.

---

**Network Layer**

--Move packets from source to destination.

--Internetworking, Addressing

--From Packets.

**Protocol**:- IP, ICMP, ARP,OSPF, BGP, RIP.

**Attack**:- MITM(Man in the middle Attack).

---

**Data Link Layer**

--Framing error detection and correction acknowledgment, flow controls, ensuring well-defined relaiable service interface to the  network layer encapsulating packets from netwok layer to frames,etc.

--From Frames.

**Protocol**:- Bridge, Switch, Ethernet, PPP, HDLL.

**Attack**:- Spoofing.

---

**Physical layer**

-- Controls the way unstrucutred, raw,bit-stream data is sent and received over a physical medium.

-- Composed of the electrical, optical and physical components of the netwrok.

--From Bits

**Protocol**:- COax, Fiber, wireless, RJ45, Bluetooth.

**Attack**:- Sniffing.

---

# **What is TCP/IP MOdel?**

--TCP/IP Model , it was desgined and devloped by department of defense (DOD) in 1960s and is based on standard protocol.It stand for transmission control protocol/Internet protocol. The TCP/IP model is a concise version of the model.

**It Contains four layer**

1. Process/Application layer-Application+Presenation+Session Layer
2. HOst-to-Host/-Transport layer -transport layer
3. Internet layer- Network layer
4. Network access/link layer- DataLink Layer+Physical Layer

---

# **What is OWASP**

--OWASP Top10 is an online document on OWASP's website that provides ranking of and remediations guidance for the top 10 most critical web application security risks.

--The owasp top 10 is a list of the most critical web application security risks, compiled by the Open Web application Security project. IT Provides guidance to devlopers, security teams, and organisations on addressing the most common and impactful vulnerabilities.

1. **BROKEN ACCESS CONTROL**

   --Flaws that allow users to act outside their intended permissions, such as gaining unauthorised access to restricted resources.

  **EX**:- A normal user modifying a URL to access an admin page.

2. **Cryptographic Failures**

   --Weak or improperly implemented cryptographic mechanisms that expose sensitive data.

**EX**:- Storing passwords in plaintext or using  weak encryption algorithms like MD5.

3. **Injection**

   --Inserting malicious code into a program often through user inputs, to execute unintended  commands or queries.

**EX**:- SQL injection, where an attacker can manipulate a database query by injecting SQL code.

4. **Insecure Desgin**

   -- Flaws resulting froms the absence of secuirty in the desgin of applications, often due to lack  of security controls in the desgin phase.

**EX**:-No proper Validation on inputs allowing for attacks like XSS.

5. **Security Misconfiguration**

   -- Improper configuration of security setting in applications, servers, or database, exposing system to attacks.

**EX**:- Leaving default account active, unnecessary fatures enabled or error mssages revealing too much inforamtion.

6. **Vulnerable and outdated components**

   --Using libraries, framework, or other components with known vulnerbilities can introduce security risks.

**EX**:- Running  an onoutdated version of a software libarary that is vulnerable to known attacks.

7. **Identification and authentication Failures**

   --Weak authentications mechanisms or improper session handling, which allow attackers compromise user indentities.

**EX**:- Allowing weak passwords or session hijacking due to insecure token handling.

8. **Software and Data Integrity failures**

   --Failures related to software updates, critical data, or CI/CD pipelines not being preoperly verified for intergrity.

**EX**:-Allowing unsigned or untrusted software updates, which could lead to compromise.

9. **Security logging and monitoring failures**
    --Lack of sufficient logging, monitoring or response mechanism , leading to undetected attack and delayed incident response.

**EX**:-Not logging failed login attempt or ignoring alerts for  suspicious activity.

10. **Server-side request frogery (SSRF)**
    -- An attacker tricks a server into making unintended requests to other resources. potentially exposing sensitive internal systems.

**EX**:- Exploiting an API to make the server fetch unauthorised data from internal netwoks.

---

# What is pentesting and types of pentesting
Penetration testing is also knwon as pen testing or ethical hacking. It describe the intentional launching of simulated cyberattacks that seek out exploitable vulnerabilities in computer systems, networks, websites, and applications.

The type of penetraion testing noramlly depends on the scope and the organizational wants and requirements. 

# This can classified into 3 types.

**BLACK BOX PENETRATION TESTING**

In this black box penetration testing, tester has no idea about the systems that he is going to test . He is intrested to gather information about the target network or systems.

**WHITE BOX PENETRATION TESTING**

In this white box penetration testing, it is noramlly considered as a simulationn of an attack by an internal source. It is also known as structural, glass box, and open box testing.

White box Penetration testing examines the code coverage and does data flow testing, path testing, loop testing, etc.

**GREY BOX PENETRATION TEESTING**

In this grey box testing a tester usually provides partial or limited information about the internal details of the program of a system.

---

# What is ports and most common network ports and services.

Protocol is set of rule by defnition in computer networking, protocol is standard way for computer to exchange information each protocol has a port number assigned to it.

There are 65,535 ports in total

| Service | Port Number | Function |
|---------|-------------|----------|
| FTP | 20,21 | Filw transfer Protocol use:- Transfer files uploading and Download |
| SSH | 22 | Secure Shell Use:- Encrypts the connection fro remote login |
| Telnet | 23 | Establish a connection to remote login Note:- Does not encrypt data linke SSH |
| RDP | 3389 | Remote Desktop protocol | Use :- Connects a remote windows computers |
| DNS | 53 | Domian Name System | Maps URL to IPs addresses |
| SMTP | 25 | Simple mail transfer protocol  use: Sending mails |
| POP3 | 110 | Post Office Protocol v3 |
| MYSQL | 3306 | MySQL Databases Use: Connects to mysql databases |
| PostgreSQL |5432 | PostgreSQL databse Use :- Connects to postgreSQL databases |
| Oracle | 1521 | Oracle Databse Use: Connects to Oracle Database |
| LDPA | 389 | Lightweight Directoray Access Protocol Use: Access Directory services |
| SMB | 445 | Server Message Block Use: File sharing and Network Communication |
| NetBIOS | 137, 138, 139 | Network Basic Input Output system Use: Receiving Emails |
| MSSQL | 1433 | Microsoft SQL server Use: Connects to Microsoft SQl server Databses |
| IMPA4 |  143 | Internet Message Access Control Protocol V4 USe: Receving emails (new version) |
| HTTP | 80 | Hypertext transfer protocol Use: Connects to web pages on the internet |
| HTTPS | 443 | Hypertext transfer protocol use: Secure protocl using SSL/ TLS certificates |
| ARP | NA | Address Resoultion protocol Use : Maps IP addresses to MAC addressing for routing in IP subnets |
| VNC | 5900 | Virtual Machine Computing  use: Remote Desktop Access |
|Syslog | 161 | Simple Network Management Protocol Use: Network device  management and monitoring |


---

# DNS Working 
| Step | Description |
|------|-------------|
| 1. Initial Query | When searching for www.example.com the browser and OS first check their local cache for the  corresponding IP address |
| 2. Cache miss | If no record is found, the OS queries the "Resolving Name  server " (RNS) For the IP addres. The RNS checks its own cache |
| 3. Root Name Servers | If the RNS does not have the record, it queries the Root name server, which provide addresses of the TLD Name Server for .com |
| 4. TLD Nmae Server | The RNS queries the .com TLD name server, which provide the address of the Authoritative Nmae Server for example.com |
| 5. Authorative Name Server | The Authorative Nmae Server for example.com provide the IP address of www.example.com. The RNS cahches this result and returns it to the OS |


---
# SSH handshake Process

| Step | Description |
|-----|-------------|
| 1. Clients initiates | The SSH clients initiates a connectiosn to the SSH server by sending a connection request |
| 2. Server  respond | The SSH server responds with its public key and a set of supported algorithm |
| 3. Key Exchange | The client and server exchange cryptographic keys to agree on ashared secret for encryption |
| 4. Authentication | the clients sends an authentication request (username and password, or key-based authentication) |
| 5. server verifies | the server verifies the clients credentials. if valid, it send an acknowledgement |
| 6. Secure Connection | Once authentication is sucessful, both the clients and server establish an encrypted session |

---
# What is Burpsuite?
Burpsuite is a set of tools for penetration testing of webappliactions. It was developed by the company named by Portswigger.which is the also alias of its founder dafydd struff.

| Tool | Desription | Key features |
|-----|------------|--------------|
| Proxy | Allows users to view and modify the contents of requests and responses while they transit. | -view modify request and response. - Forward to other tools -Configurable proxy setting |
| Intruder | Automates customized attakcs against web applications | -Brute Force - Dictionary attacks - Rate limiting tests |
| Repeter | Manually manipulates and issues individual HTTP requests analyze responses | -send modify, and reisues requests - Detailed response analysis |
| Decoder | Decodes and encodes data using common methos like URL,HTML,BASE64, and Hex | -common encoding decoding methods - analyzes data in parameters or headers |
| Scanner | Automatically scans web applications for Vulnerability | - automated Vulnerability scaning - deatiled reports - Customizable scan setting |
| Comparer | Compares two sets of data to identify diffrences, useful for analyzing responses or request variations | -comparer request and responses  - Highlights diiferences |
| Sequencer | Analyzes the radomness of tokens and session identifiers to assess their strenght and predictablity |-token randomness analysis - session identifieer analysis -statistical reports |
| Extender | Allow users to add custom funtionality to Burpsuite through extensions and plugins |  -Add and manage extensions - Customize burpsuite capabilites -Support for third-party plugins |

---
# What is wireshark?
Wireshark is an open-source tool very widely used to traffic in a network in real time. It helps us to analyse the data packets flowing in the network thus providing valuable information about the network behaviour and its performance as well as security. 
Network Traffic Analysis,Intrusion Detection and Prevention,Malware Analysis,Network Forensics,Vulnerability Analysis,Security Monitoring and Incident Response.

---
# What is Nmap?
Nmap (Network Mapper) is an open-source tool used for network discovery and security auditing. It scans networks to detect live hosts, open ports, running services, and operating system details.

| Nmap | Command Examples |
|-----|------------------|
| Ping Scan | nmap -sn <target ip> |
| Host Scan | nmap -sn <target ip> |
| OS Scaning | nmap -O <target ip> |
| Most Popular ports | nmap --top-ports 20 <target ip> |
| Output to a file | nmap -oN output.txt |
| Service version dectection | nmp -sV <target ip> |
| Script Sacning | nmap --script=<script_nmae> <target> |
| TCP SYN Scan | nmap -sS <target> |
| UDP Scan | nmap -sU <target> |
| Aggressive Scan | nmap -A <target> |
| Traceroute Scan | nmap --tracerote <target> |
| Full TCP Connect scan | nmap -sT <target> |
| Version Detection Scan | nmap -sV --version-all <target> |
| Idle Scan | nmap -sI <target> |
| OS and Version Detection | nmap -O -sV <target> |
| TCP ACK scan | nmap -sA <target> |
| IP protocol scan | nmap -sO <target> |



---
# What is SQLMap?
SQLmap is an open-source tool that automates the detection and exploitation of SQL injection vulnerabilities in web applications.

