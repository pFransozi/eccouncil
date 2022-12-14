# Information Security Fundamentals

## Main Topics

1. Why security is needed?
2. Which are the elements of information security?
3. Security, functionality and usability triangle, what is that?
4. Why exist information security attacks? What are the motives, the goals, and objectives of thouse?
5. What are the attacks?
6. What are the information security attack vectors?
7. What are the information security laws and regulations?

## Our motivation

Sun Tzu, Art of War, “If you know yourself but not the enemy, for every victory gained, you will also suffer a defeat.”
Security professionals must guard their infrastructure against exploits by knowing the enemy— the malicious hacker(s)— **who seek(s) to use the same infrastructure for illegal activities**.

## 1. Why security is needed?

First of all, what is security information? Into security information, we are thinking about information and infrastructure, by which information flows, in a way that theft, tampering, disruption of information or services is kept low or tolerable. **Information security** is about protection or safeguarding of **information and information systems** that use, store, and transmit information **from unauthorized access, disclosure, alteration, and destruction**.

Information security is needed even more because information systems and business become one thing, the well operation of the companies is supported by information systems. Likely, our lifes even more become supported by information systems. For that, some concepts emerge such as: systems that are focus on ease to use, security of the assets, computers were designed to facilitate research, **and that did not place much emphasis on security as these resources, being scarce, were meant for sharing**.

The permeation of computers into both the routine workspace and daily life has led to more control being transferred to computers and a higher dependency on them for facilitating important routine tasks. This has further increased the usage of networked environments and network-based applications. Any network disruptions mean a loss of time, money, and, sometimes, even loss of life. Additionally, the increasing complexity of computer infrastructure administration and management is creating a direct impact of security breaches on the corporate asset base and goodwill.

### Basic core concepts of Information Security

* Confidentiality: it is **the assurance** that the **information is accessible only to authorized**. Confidentiality breaches may occur due to improper data handling or a hacking attempt. **Confidentiality controls include data classification, data encryption, and proper disposal of equipment (such as DVDs, USB drives, etc.)**.

* Integrity: it is the **trustworthiness** of data or resources in the **prevention of improper and unauthorized changes** — **the assurance that information is sufficiently accurate for its purpose**. Measures to maintain data integrity may include **a checksum and access control** **(which ensures that only authorized people can update, add, or delete data)**.

* Availability: it is the **assurance** that the **systems responsible for delivering, storing, and processing information are accessible when required by authorized users**. Measures to maintain data availability can include **disk arrays for redundant systems and clustered machines**, **antivirus software to combat malware**, and **distributed denial-of-service (DDoS) prevention systems**.

* Authenticity: Authenticity refers to the **characteristic of communication, documents, or any data that ensures the quality of being genuine or uncorrupted**. The major role of authentication **is to confirm that a user is genuine**. Controls such as **biometrics**, **smart cards**, and **digital certificates ensure the authenticity of data**, **transactions**, **communications**, **and documents**.

* Non-Repudiation: it is **a way to guarantee that the sender of a message cannot later deny having sent the message** and that **the recipient cannot deny having received the message**. Individuals and organizations use digital signatures to ensure non-repudiation.

### Security, Functionality, and Usability Triangle

Generally, information systems must have to dealing with security, functionality and usability. The problem is that every time the weight of one of those aspects is increased, the importance of the other two are reduced.

The ideia of the triangle is this: more security means less functionality and usability. Generally, the information systems weight more functionality and usability than security. Furthermore, each every year it increases the number of routine activities that are done through an information system and then each every year become more difficult for security professionals to allocate resources exclusively for securing systems.

In the context of information security, **hacking is** defined as the exploitation of vulnerabilities of computer systems and networks and requires great proficiency, even though more and more automated tools and codes are available on the Internet. That phenomenon facilitates the way systems can be exploited, making it easier, and the knowledge curve required to perform such exploits has decreased.

Increasingly networked environment makes it critical for security professionals to take countermeasures to prevent exploits that can result in data loss.

Returning to triangle: 

* functionality: the set of features provided by the system
* usability: the gui components used to design the system for ease of use
* security: restrictions imposed on accessing the components of the system.

There's a strong relationship between those components.

### Security Challenges

* **Compliance to laws and regulations**;
* **Lack of qualified and skilled cybersecurity professionals**;
* **Distributed computing environment makes harder a centralizing security**;
* **Complex IT infrastructure makes harder overseeing end-to-end processes**;
* **Fragmented and complex privacy and data protection regulations**;
* **Use of a serverless architecture and applications that rely on third-party cloud providers**;
* Compliance issues and issues with data removal and retrieval due to the implementation of Bring Your Own Device (BYOD) policies in companies;
* Relocation of sensitive data from legacy data centers to the cloud without proper configuration;
* Weak links in supply-chain management;
* Increase in cybersecurity risks such as data loss and unpatched vulnerabilities and errors due to the usage of shadow IT;
* Shortage of research visibility and training for IT employees;

### Motives, Goals, and Objectives of Information Security Attacks

Information security attacks are motivates by the notion that a target system stores or processses something valuable, which leads to the threat of an attack on the system.

Attacks = Motives (Goal) + Method + Vulnerability

Motives behind information secuirty attacks:

* disrupt business continuity
* perform informatin theft
* manipulating data
* create fear and chaos by disrupting critical infrastructures
* bring financial loss to the target
* propagate religious or polical beliefs
* achieve a state's military objectives
* damage the reputation of the target
* take revenge
* demand ransom

## Attacks

**Passive Attacks** **do not tamper** with the data and **involve intercepting and monitoring network traffic** and **data flow on the target network**. **Reconnaissance is a kind of this type of attacks, using sniffers to detect the activity on the network**. It is difficult to detect when has no active interaction with the target system or network. Passive attacks allow attackers to capture the data or files being transmitted in the network without the consent of the user. For example, an attacker can obtain information such as unencrypted data in transit, clear-text credentials, or other sensitive information that is useful in performing active attacks. Examples: **sniffing, eavesdropping, footprinting, sniffing and eavesdropping, netowork traffic analysis, decryption of weakly encrypted traffic**.

**Active attacks** tamper with data in transit or disrupt the communication or services between the systems to bypass or break into secured systems. Attackers launch attacks on the target system or network **by sending traffic actively that can be detected**. These attacks are performed on the target network to exploit the information in transit. **They penetrate or infect the target’s internal network and gain access to a remote system to compromise the internal network**. Examples: DoS, Bypassing protection mechanisms, Malware attacks (viruses, worms, ransomware), Modification of information, spoofing attacks, replay attacks, password-based attacks, MitM, session hijacking, DNS and ARP poisoning, compromised-key attack, Firewall and IDS attack, Profiling, arbritary code execution, privilege escalation, backdoor access, cryptography attacks, SQLi, xss attacks, directory traversal attacks, exploitation of application and OS software.

**Close-in attacks** are performed when the attacker **is in close physical proximity with the target system or network in order to gather, modify, or disrupt access to information**. The main goal of performing this type of attack is to gather or modify information or disrupt its access. Examples: include social engineering: eavesdropping, shoulder surfing, dumpster diving.

**Insider attacks** involve using privileged access to violate rules or intentionally cause a threat to the organization's information or information systems. An insider attack involves using **privileged access to violate rules** or **intentionally cause a threat to the organization’s information or information systems**. Insiders can easily bypass security rules, corrupt valuable resources, and access sensitive information. They misuse the organization’s assets to directly affect the confidentiality, integrity, and  availability of information systems. These attacks impact the
organization’s business operations, reputation, and profit. It is difficult to figure out an insider attack. Examples: eavesdroping and wiretapping, theft of physical devices, social engineering, data theft and spoliation, pod slurping, planting keyloggers, backdoors, malware, theft of physical devices and planting keyloggers, backdoors, and malware.

**Distribution attacks** occur when attackers tamper with hardware or software prior to instalation. Attackers tamper with the hardware or software at its source or in transit.

## Information Security Attack Vectors

An vector is a way through an attacker can gain access to a computer or network server to deliver a payload or seek a malicious outocme.

* **cloud computing theats**: cloud computing is a on-demand delivery of IT capabilities in which IT infrastructure and applications are provided to subscribers as a service **over a network**. Clientes can store sensitive information on the cloud.

* **advanced persistent threats (APTs)**: it is an attack that focuses on stealing information from the victim machine without its user being aware of it. These attacks are generally targeted at large companies and government networks. Because **APT attacks are slow in nature**, **their effect on computer performance and Internet connections is
negligible**. **APTs exploit vulnerabilities in the applications running on computers, operating systems, and embedded systems**.

* **viruses and worms**: they are the most prevalent networking threats. A virus is a self-replicating program that produces a copy of itself by attaching to another computer program, boot sector, or document.  A worm is a malicious program that replicates, executes, and spreads across network connections.

* **ransomware**: it is a type of a malware that restricts access to the computer system's files and folders and demands an online ransom payment spread via malicious attachments to email messagens, infected software applications, infected disks, or compromised websites.

* **mobile threats**: mobiles has became a target for attackers due to the increased adoption of smartphones for business and personal use, and their comparatively fewer security controls.

* botnet: it is a huge network of compromised sustems used by attackers to perform DoS attacks. In a botnet, bots perform tasks such as uploading viruses, sending mails with botnets attached to them, stealing data. Antivirus programs might fail to find spyware or botnets. Hence, it is essential to deploy programs specifically designed to find and eliminate such threats.

* **insider attack**: it is an attack by someone **from within an organization who has authorized access to its network and is aware of the network architecture**.

* **phishing**: it refers to the practice of sending an illegitimate email falsely claiming to be from a legitimate site in an attempt to acquire a user's personal or account information. Attackers perform phishing attacks by distributing malicious links via some communication channel or mails to obtain private information such as account numbers, credit card numbers, mobile numbers, etc. from the victim. Attackers design emails to lure victims in such a way that they appear to be from some legitimate source or at times
they send malicious links that resemble a legitimate website.

* **Web application threats**: Attacks such as **SQL injection and cross-site scripting** has made web applications a favorable target for attackers to steal credentials, set up phishing site, or acquire private information. Most of these attacks are the result of flawed coding and improper sanitization of input and output data from the web application. Web application attacks can threaten the performance of the website and hamper its security.

* **IoT threats**: IoT devices connected to the Internet **have little or no security**, which makes them **vulnerable to various types of attacks**. These devices include many software applications that are *used to access the device remotely*. Due to hardware constraints such as memory, battery, etc. these **IoT applications do not include complex security mechanisms to protect the devices from attacks**. These drawbacks make IoT devices more vulnerable and allow attackers to access the device remotely and perform various attacks.

## Information Security Laws and Regulations

### PCI DSS

Source: https://www.pcisecuritystandards.org

For organizations that handle cardholder information. It offers standards and supporting materials to enhance payment card data security. PCI DSS applies to all entities involved in payment card processing, including merchants, processors, acquirers, issuers, and service providers, as well as all other entities that store, process, or transmit cardholder data.

* High Level Overwiew
    * Build and Maintain a Secure Network
        * Install and maintain a firewall configuration to protect cardholder data
        * Do not use vendor-supplied defaults for system passwords and other security parameters
    * Protect Cardholder Data
        * Protect stored cardholder data
        * Encrypt transmission of cardholder data across open, public networks
    * Maintain a Vulnerability Management Program
        * Use and regularly update anti-virus software or programs
        * Develop and maintain secure systems and applications.
    * Implement Strong Access Control Measures
        * Restrict access to cardholder data by business need to know
        * Assign a unique ID to each person with computer access
        * Restrict physical access to cardholder data
    * Regularly Monitor and Test Networks
        * Track and monitor all access to network resources and cardholder data
        * Regularly test security systems and process
    * Maintain an Information Security Policy
        * Maintain a policy that addresses information security for all personnel.

### ISO/IEC 27001:2013

Source: https://www.iso.org

It specifies the requirements for establishing, implementing, maintaining, and continually improving an information security management system within the context of an organization.

It is intended to be suitable for several different uses, including:
* Use within organizations to formulate security requirements and objectives
* Use within organizations as a way to ensure that security risks are cost-effectively managed
* Use within organizations to ensure compliance with laws and regulations
* Defining new information security management processes
* Identifying and clarifying existing information security management processes
* Use by the management of organizations to determine the status of information security management activities
* Implementing business-enabling information security
* Use by organizations to provide relevant information about information security to customers

### HIPAA Health Insurance Portability and Accountability Act

Source: https://www.hhs.gov

It protects the individually identifiable health information. The Security Rule specifies a series of **administrative**, **physical**, and **technical safeguards for covered entities and their business associates to use to ensure the confidentiality**, **integrity**, and **availability** of electronically protected health information.

HIPAA’s Administrative Simplification Statute and Rules:
* Electronic Transactions and Code Set Standards: it designated certain types of organization as covered entities: health plans, health care claringhouses, health care providers. There are certain standard transactions for the Eletronic Data Interchange (EDI) of health care data. Under HIPAA, a covered entity must use the adopted standard: ASC, X12N, NCPDP.
* Privacy Rule: standards to protect people’s medical
records and other personal health information and applies to health plans, health care clearinghouses, and health care providers that conduct certain health care transactions
electronically. **The rule requires appropriate safeguards to protect the privacy of personal health information.** It sets limits and conditions on the uses and disclosures
that may be made of such information without patient authorization. The rule also gives patients’ rights over their health information, including the right to examine and obtain a copy of their health records and to request corrections.
* Security Rule: to protect individuals’ electronic personal health information that is **created**, **received**, **used**, or maintained by a covered entity. The Security Rule requires appropriate administrative, physical, and technical safeguards to ensure the confidentiality, integrity, and security of electronically protected health information.
* Employer Identifier Standard: The HIPAA requires that each employer has a standard national number that identifies
them on standard transactions.
* National Provider Identifier Standard (NPI): The National Provider Identifier (NPI) is a HIPAA Administrative Simplification Standard. The NPI is a unique identification number assigned to covered health care providers. Covered health care providers and all health plans and health care clearinghouses must use the NPIs in the administrative and financial transactions adopted under HIPAA. The NPI is a 10-position, intelligence-free numeric identifier (10-digit number). This means that the numbers do not carry other information about healthcare providers, such as the state in which they live or their medical specialty.
* Enforcement Rule: The HIPAA Enforcement Rule contains provisions relating to compliance and investigation, as well as the imposition of civil monetary penalties for violations of the HIPAA Administrative Simplification Rules and procedures for hearings.

### Sarbanes Oxley Act

Source: https://www.sec.gov

to protect the public and investors by increasing the accuracy and reliability of corporate disclosures. This act does not explain how an organization must store records but describes the records that organizations must store and
the duration of their storage.

The key requirements and provisions of SOX are organized into 11 titles:

1. Public Company Accounting Oversight Board (PCAOB)
2. Auditor Independence
3. Corporate Responsibility
4. Enhanced Financial Disclosures
5. Analyst Conflicts of Interest
6. Commission Resources and Authority
7. Studies and Reports
8. Corporate and Criminal Fraud Accountability
9. White-Collar-Crime Penalty Enhancement
10. Corporate Tax Returns
11. Corporate Fraud Accountability

### The Digital Millennium Copyright Act (DMCA)

the DMCA defines legal prohibitions against circumvention of the technological protection measures employed by copyright owners to protect their works, and against the removal or alteration of copyright management information. The DMCA contains five titles:

### The Federal Information Security Management Act (FISMA)

Source: https://csrc.nist.gov

### General Data Protection Regulation (GDPR)

Source: https://gdpr.eu

### Data Protection Act 2018 (DPA)

Source: https://www.legislation.gov.uk