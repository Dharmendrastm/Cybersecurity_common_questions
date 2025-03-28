# Cybersecurity_VAPT-Interview-questions
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

# **Differnce between TCP and UDP**

| Feature            | TCP (Transmission Control Protocol) | UDP (User Datagram Protocol) |
|--------------------|----------------------------------|----------------------------|
| **Type**          | Connection-oriented             | Connectionless            |
| **Acknowledgment**| Received                        | Not received              |
| **Speed**        | Comparatively slower            | Faster, simpler, and more efficient |
| **Usage**        | Used by HTTP, HTTPS, FTP, SMTP, Telnet | Used by DNS, DHCP, TFTP, SNMP, RIP, VOIP |

**TCP** 
--It stands for Transmission Control Protocol.

--It is a connection oriented protocol.

--Acknowledgement is received.

--TCP is compratively slower than UDP.

--TCP is used by HTTP, HTTPS, FTP, SMTP and telent.

**UDP**

--It stands for user-datagram protocol.

--It is connection less protocol.

--Acknowledgment is not received.

--UDP is faster simpler and more efficient than TCP.

--UDP is used by DNS , DHCP, TFTP,SNMP, RIP,VOIP.

---

# **What is OSI Model?**

--OSI stand for open system interconnections a reference model that descibes how information from a software appliactions in one computer moves through a physical medium to the software application in another computer.

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

--Translate, encrypt, and compress data.

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

# What is pentesting and types of pentesting**
Penetration testing is also knwon as pen testing or ethical hacking. It describe the intentional launching of simulated cyberattacks that seek out exploitable vulnerabilities in computer systems, networks, websites, and applications.

The type of penetraion testing noramlly depends on the scope and the organizational wants and requirements. this can classified into 3 types.

**BLACK BOX PENETRATION TESTING**

In this black box penetration testing, tester has no idea about the systems that he is going to test . He is intrested to gather information about the target network or systems.

**WHITE BOX PENETRATION TESTING**
In this white box penetration testing, it is noramlly considered as a simulationn of an attack by an internal source. It is also known as structural, glass box, and open box testing.

White box Penetration testing examines the code coverage and does data flow testing, path testing, loop testing, etc.

**GREY BOX PENETRATION TEESTING**

In this grey box testing a tester usuallyprovides partial or limited information about the internal details of the program of a system.

---

















