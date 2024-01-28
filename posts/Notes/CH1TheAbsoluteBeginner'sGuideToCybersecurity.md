# Chapter 1: Introduction to Cybersecurity
<br>
  1.1 Understanding Cybersecurity
  
_What is Cybersecurity?_:
Cybersecurity is the practice of _protecting systems, networks, and digital assets from malicious attacks¹, unauthorized access, and data breaches_.

(_CISCO Introduction to Cybersecurity - What Is Cybersecurity? Definition_
Cybersecurity is the ongoing effort to protect individuals, organizations and governments from digital attacks by protecting networked systems and data from unauthorized use or harm.)

¹ _What Malicious attacks are we referring to?:_
Intrusion: Imagine your computer system is a fortress - with high walls, a moat, and a secure gate. Inside the Fortress, there's valuable treasure (sensitive data, personal information, and more). An "Intrusion" is like an unwanted visitor attempting to breach the fortress walls and gain access to your treasure. 

_How can an "intruder" get past the cameras, guards, and walls of my castle?_:

> _What is Malware?_: Malware, or malicious software, is code that can be used to steal data, bypass access controls, or cause harm to compromise a system. 
## The top 3 _Most_ common Intrusion Malware:

Virus: The _sneaky_ infiltrator → The _Virus_ is a _Spy_ who infiltrates the castle _disguised as a trusted messenger_

> **_A Computer Virus_** is a piece of code that attaches itself to a legitimate program/file. When you run the _infected_ program, the virus activates and spreads, like a disguised messenger spreading chaos within the castle.
> The virus replicates itself and attaches to other executable files.  Most viruses require end-user interaction, can modify or delete data, and avoid detection. Most viruses are spread via emails, network sharing, optical disks or USB drives.

Trojan Horse: The _Deceptive_ Gift → The _Trojan Horse_ is a _Seemingly innocent gift_ left at the castle gates by an _unknown source._

>**_A Trojan Horse_** is Malware disguised as a legitimate file or program. Like the legendary wooden horse to infitrate Troy, it tricks the user into installing it, giving unauthorized access to the attacker. The Deceptive package carries a hidden threat.
> Trojans are most often found in image files, audio files, or games. They exploit your user priveleges to sneak malware onto a user's system.

Worm: The Secret _Tunnel_ Digger → The _Worm_ is a _sneaky_ creature that _digs_ secret tunnels _connecting different parts of the castle._

>**_A Computer Worm_** is a _standalone_ program that replicates itself to spread accross the network. It _doesn't need a host file_ to attach to - Just like secret tunnel systems don't rely on existing structures. Worms can _rapidly spread through interconnected systems_, like tunnels weaving through the castle's different sections.
> Worms do not require user participation after the initial infection, and they spread very quickly over the network. All Worms contain malicious code to cause damage to computer systems or networks.
> ★ Worms are responsible for some of the most devastating attacks on the internet. For example, in 2001, the Code Red Worm infected 3000,000+ servers in 19 hours.

## _Additional_ Types of Malware
**More types of malware are:**
- **Spyware**: Monitors online activity, logging your typing, clicking, and data. It does this by _modifying_ the _security settings on your devices_, often buldling with a legitimate software or a Trojan Horse.
- **Adware**: Automatically delivers ads to a user, mostly on a web browser. It commonly comes with spyware, and is often installed with some versions of (vulnerable) software.
- **Scareware**: Scaring you through OS- style window warnings that tell you that your system is at risk. When the program is executed, you get infected with malware.
- **Rootkit**: Malware that modifies the OS and creates a backdoor (or a means for the attacker to gain remote access to your computer system that is hard to detect). Most rootkits take advantage of software vulnerabilities to gain access ("privelege escalation") and modify system files. They can also modify system forensics and monitoring tools, making it hard to detect.
- **Ransomeware**: Encrypts your data so that you can't access it until you make a payment. Often spreads through phishing email attachments or through a software vulnerability.

**Cybersecurity encompasses a wide range of technologies, Processes, and practices designed to safegaurd our digital world.**

# When a system becomes Infected with Malware
_What are some common indicators that a system has become infected?_
- an increase in central processing unit (CPU) usage, which slows down your device
- your computer freezing or crashing often
- a decrease in your web browsing speed
- unexplainable problems with your network connections
- modified or deleted files
- the presence of unknown files, programs or desktop icons
- unknown processes running
- programs turning off or reconfiguring themselves
- emails being sent without your knowledge or consent.

---
## The Threat Landscape in Cybersecurity
_The field of cybersecurity has witnessed significant changes in the nature of threats over the years. Understanding this evolution helps us develop effective strategies to protect against current and future cyberthreats._

A Historical Perspective:
1. A Background on Viruses and Worms (1980's - 1990's):
- Early viruses were primarily transmitted via infected floppy disks, which were commonly used for software distribution.
  
**Morris Worm: A Pioneering Incident (1988)**:
  The Morris worm, created by Robert Tappan Morris, was unleashed on the internet on November 2, 1988, intended to gauge the size of the internet.
  
  Significance:
  
  _↳Exploited vulnerabilities in Unix-Based systems, primarily "Sendmail" (an older "email"), "Finger" (a sort of online yellow pages with public personal information), and weak passwork mechanisms._
  
  _↳Implemented a self-replicating mechanism, allowing it to propagate accross connected systems._
  
★ The Worm spread _faster_ than anticipated, causing system shutdowns and, in some cases, complete unavailability (a total of ~6,000 systems.)

★ Morris' experiment highlighted the unpredictability of malware behaviour and the potential for unintended consequences. 

★ The Incident underscored the need for ethical handling of security research and responsible disclosure of vulnerabilities.

★ In 1989, Morris became the _first person to be tried and convicted unter the Computer Fraud and Abuse Act (CFAA)_ in the United States.

★ The Incident raised awareness about the vulnerability of connected systems and the potential for rapid, self-propagating malware. It also prompted the development + enhancement of security practices.

>**_Another Significant case convicted Under the Computer Fraud & Abuse Act (CFAA)_**
> Kevin Mitnick (1999)
> - In 1979, at 16, Kevin Broke into the Digital Equipment Corporations (DEC) computer network and copied the company's software → he was sentenced to 12 months of prison + 3 years of supervised release.
> - Near the end of his supervised release, he hacked into Pacific Bell voicemail computers → he fled, becoming a fugitive for 2 1/2 years.
> - Kevin Had allegedly gained unauthorized access to dozens of computer networks as a fugitive. He _intercepted and stole computer passwords, altered computer networks, and broke into and read private emails.
> - Mitnick was finally arrested on February 15, 1996
> - Case Significance: The case became a landmark in the legal landscape of computer crimes, bringing attention to the need for legislation to address computer crimes. It also demonstrated that hacking and unauthorized access to computer networks could be treated as serious criminal offenses.
> - 
> - In 2001, Kevin Mitnick wrote a book, **"The Art of Deception: Controlling the Human Element of Security"** (my favorite book to read of his):

>**_Key Takeaway:_**
> - Social Engineering: The art of Manipulating, Influencing, or decieving people in order to gain unauthorized access to information or systems (targeting the _human element._)
> - Mitnick emphasized the ease of gaining access to private services both physically and online by tricking people into willingly or unknowingly give the nescessary information away. Tricks include exploiting the human curiousity through phishing or spamming, exploiting Authority and Compliance to pose as someone you should give information to, and taking advantage of company privacy blunders, such as picking up sensitive information unproperly discarded outside large company facilities ("Dumpster Diving").

<br>

### From CISCO Introduction to Cybersecurity Course

_What do cybercrmiinals want from me?_
Cybercriminals can use your sensitive personal information to identify and impersonate you, infringing on your privacy and potentially causing serious damage to your reputation.

- Every time we collect or share personal data, we should consider our security.

★ When we analyze the cybersecurity measures for a larger organization as specialists: 

In Organizations, the two main types of (organizational) data are:

_Traditional Data_ (Including transactional data such as sales and purchases, and basic operations; Intellectual Property, such as patents and trademarks; and Financial data such as income statements and balance sheets) and _Internet of Things (IoT) and Big Data_ (the large network of physical object such as sensors, software, and relevant equipment that collects and shares data).

## The McCumber Cube

>**_The Cube_**
> is a framework created in 1991 by John McCumber to help organizations evaluate information security initiatives. The security model has 3 Dimensions:
> 1. The foundational principles of protecting Information systems:
>    - _Confidentiality_: Methods to ensure confidentiality like **data encryption,** **Identity proofing,** and **two factor authentication** prevent sensitive information from being disclosed in an unauthorized manner.
>    - _Integrity_: One method to ensure integrity is a **Hash Function/Checksum,** which prevents information from being accidently or intentionally modified.
>    - _Availability_: **Maintaining equipment,** **performing harware repairs,** **keeping operating systems and software up to date**, and **creating backups** can ensure authorized users the ability to access systems and data when needed.
> 2. The Protection of Data in each of its possible states:
>    - _Processing_: data being **used** to **perform an operation** (_Data In Process_ - data updating a database record)
>    - _Storage_: Data **stored** on a **permanent storage device** (_Data At Rest_ - stored in a hard drive, solid-state drive, or USB Drive ([Recall Mitnick in "Dumpster Diving"])
>    - _Transmission_: Data **traveling between Information systems** (_Data In Transit_)
> 3. The Security measures used to protect data:
>    - _Awareness, training, and education_: Organizations ensure that **users are knowledgeable** about **potential security threats** and actions they can take to protect information systems.
>    - _Technology_: **Software** and **Hardware**- based solutions built to protect data systems (Such as **Firewalls**).
>    - _Policy and Procedure_: Administrative control such as **incident response** and **best practice guidelines**.
> ★ Phishing emails sent to customers will often have crappy grammar, strange URL's, strange email addresses, and bad graphics.

>**_Some notable (recent) data breaches:_**
> 1. **Equifax - Consumer Credit Card Reporting Agency (2017):**
>   - Impact: Personal information of approximately 147 million consumers, including names, Social Security numbers, birth dates, addresses, and in some cases, driver's license numbers.
>   - Cause: Exploitation of a vulnerability in the company's website.
>
> 2. **Yahoo (2013-2014, disclosed in 2016):**
>   - Impact: Over 3 billion user accounts compromised, including email addresses, hashed passwords, and personal information.
>   - Cause: State-sponsored hackers were involved in the cyberattack.
>
> 3. **Marriott International (2018):**
>   - Impact: Personal details of around 500 million guests exposed, including names, addresses, passport numbers, and payment card information.
>   - Cause: Unauthorized access to the Starwood guest reservation database.
>
> 4. **Capital One (2019):**
>   - Impact: Data of around 100 million customers exposed, including names, addresses, credit scores, and social security numbers.
>   - Cause: A former employee exploited a vulnerability in the bank's system.
>
> 5. **Facebook-Cambridge Analytica (2018):**
>   - Impact: Improper access to personal data of up to 87 million Facebook users.
>   - Cause: An app developer collected and shared user data for political profiling without proper consent.
>
> 6. **Target (2013):**
>   - Impact: Payment card data and personal information of about 110 million customers compromised.
>   - Cause: Malware introduced through a third-party vendor's credentials.
>
> 7. **Sony PlayStation Network (2011):**
>   - Impact: Personal information and credit card details of approximately 77 million users exposed.
>   - Cause: A cyberattack on Sony's online gaming network.
>
> 8. **Uber (2016, disclosed in 2017):**
>   - Impact: Data of 57 million users and drivers exposed, including names, email addresses, and driver's license numbers.
>  - Cause: Hackers gained access to Uber's cloud storage.
> 8. **Persirai botnet (2017):**
>    - Impact: 1000+ models of IP cameras were injected with a command to install malware on them, used to carry out DDoS attacks.
>    - Cause: Hackers used the vulnerability of this common unprotected IoT device to their favor
> These incidents highlight the significance of cybersecurity and the need for companies to implement robust measures to protect user data. Keep in mind that the cybersecurity landscape is dynamic, and new breaches may have occurred since my last update.

If a Company/Organization has experienced a Security Breach, they can experience: 

**Reputational Damage**: Customers must be notified and may seek compensation and/or switch provider, and employees may leave. 

**Online Vandalism**: Hackers may post false information on your website, such as editing your phone number, which shows unprofessionalism and loses your credibility.

**Theft**: Sensetive personal data may be stolen, and made public for identity theft, ransom, or simply stealing your customers' money.

**Loss Of Revenue**: A Hacker taking down a website or infrastructure can impede growth and expansion, damnding further investment from the organizatino and possible fines or penalties for not protecting personal data.

**Damaged Intellectual Property**: Hackers may get their hands on Confidential documents, trade secrets, and/or intellectual property, devastating the organization's competitiveness.

⭐ As a **Cybersecurity Specialist**, your job is _not_ to protect organizations from **every** cyberattack - because **this is not possible**. **Your Job** is to **_respond quickly_** and **_Minimize the attack's Impact_**.
<br>

Companies who have had their data breached within the database could have instead:
- invested in cybersecurity training for all staff so that they are aware of and able to spot a cyber attack
- enforced two factor authentication for employees accessing files and applications that contain sensitive data
- maintained log files and ongoing monitoring to identify anomalous behavior that might indicate a data breach
- stored the passwords of customers using a combination of salting and robust hashing algorithms
- separated cloud-based resources from the public Internet into an isolated private network segment
- granted employee access to personal data and internal systems _only_ via a secure VPN connection.

<br>

## _The Types of Cyber Attackers_

1. **"Script Kiddies"** - **amateur**/**inexperienced** hackers using existing tools/instructions found on the internet in order to launch attacks (whether it be out of curiousity or to cause real harm)
2. **"Hackers"** - Fall into three Categories:
   - **White Hat** - break into networks/computer systems **with permission** in order to identify and resolve weaknesses in systems.
   - **Gray Hat** - Break into networks **with or without permission**, usually only reponrting for financial gain (or other times, publishing the vulnerability on line so that others can explout it.
   - **Black Hat** - Take advantage of vulnerabilities for personal, financial, or political gain
3. **"Organized Hackers** - Organizations of **cybercriminals**, **hactivists**, **terrorists**, and **state-sponsored hackers**. They usually are highly sophisticated and organized, and may even _provide_ cybercrime as a _service_ to _other criminals_
4. **Internal Threats** - Employees, staff, or partners either _intentionally_ or _unintentionally_:
   - Mishandling confidential data, connecting infected USB media into an organization's computer system, and/or clicking on malicious links on the organization's network.
5. **External Threats** - Amateur or skilled attackers outside the organizations:
   - Exploiting vulnerablities in the network, gaining unauthorized access to computing devices, and/or Using social engineering to gain unauthorized access to organizational data.

<br>

>**_ ## Another topic to consider: Cyberwarfare_**
>_Cyberwarfare_ is the use of technology to penetrate and attack another nation's computer systems and networks in an effort to cause damage or disrupt services, such as shutting down a power grid, or to obtain snesitive information. 
>
> _Why Do other nations want other's informations?:_ 
>
> - To gather information and/or defense secrets (whether it be for **blackmail** or to gain **military advantage**
> - To disrupt Infrastructure/ Services (causing chaos and closing down systems)
>  ★ Check out the Stutnex Virus: Distributed prmarily via USB, Using 0-day exploits, being a sophisticated program, and targeting important infrastructure. [Stutnex virus Documentary]()

>**_Methods of Infiltration/ How A company's online assets are crashed_**
> - **Social Engineering**
> - **Denial of Service (DoS)** - Simple to carry out, and results in the interruption of the network service to the users, devices, or applications. There are 2 types:
>     A. _An overwhelming quantity of traffice sent to a network, host or application._ This causes a slowdown or crash.
>     B. _Maliciously formatted Packets_. These disable a reciever's computer or application from handling data from a requested source. This causes a slowdown or crash.
>   **DoS** attacks are considered a _Major_ risk because they can easily interrupt communication and cause significant time and money loss.
>   
> - **Distributed Denial of Service (DDoS)** - Similar to a DoS attack, but origniating from multiple, coordinated sources. How does an attacker do this?
>    A. The attacker builds a network (botnet) of infected hosts called "Zombies," which are controlled by a handler system.
>    B. The zombie computers constantly scan & infect more hosts, creating more zombies.
>    C. The attacker will instruct the handler system to make the botnet of zombies to carry out a DDoS attack, sending an overloading amount of requests to a system. This causes it to ultimately crash.

>**What is a Botnet?** - A "Bot" computer is infected by visiting an unsafe website or opening an infected document. A botnet is a _group_ of Bots connected through the internet and controlled by an attacker/malicious group, usually through a command and control server.
>- _Bots can distribute malware, launch DDoS attacks, send spam emails, or execute brute-force password attacks._
>- _Cybercriminals often rent out botnets to 3rd parties._ )

> - **On - Path Attacks / Man In the Middle / Man In the Mobile Attack** - Intercepts or modifies communications between two devices, either to collect information or impersonate one of the devices. 
>
>    A. Man-in-the-Middle (_MitM_) attack: A cybercriminal takes control or intercepts a device without the user's knowledge. The attacker than then intercept and capture user information before it is sent to it's intended destination. This attack is often used to steal financial infromation. Many types of malware  posessing MitM atack capablities exist today.
>   
>   B. Man-in-the-Mobile (_MitMO_) attack: A Variation of MitM, where the infected _mobile device_ is instructed to send user-sensitive inforamtion to the attackers. Malware packages such as "ZeuS" have MitMO capabilities. This type of attack allows attackers to capture 2-step verification SMS messages that are sent to users.
>   
> - **SEO - Poisoning** - Attackers take advantage of popular search terms and use Search Engine Optimization (SEO) to push malicious sites higher in the ranks of search results, increasing traffic to malicious sites that host malware or attempt social engineering.
> 
> - **Password Attacks** - Password Attacks allow cybercriminals to impersonate you and gain access to your valuable information. The following are ways in which attackers can get access to your password:
>
>    _Password Spraying_: An Attacker "Sprays" a few commonly used passwords accross a large number of accounts on a system. This allows the attacker to avoid frequent account lockouts, remaining undetected.
>
>    _Dictionary attack_: The Hacker tries every word in a dictionary or a commonly used words as a password list to attempt breaking into an account
>
>    _Brute-force Attack_: An attacker uses all possible combinations of letters, numbers, and symbols until the attacker gets it right.
>
>    _Rainbow attacks_: A faster brute-force attack which skips the process of having to calculate each hash in real-time. _Passwords in a computer systems are stored as hashed values (numerical values that uniquely identify data)._ Using a rainbow table (a dictionary of pre-computed hashes and the passwords from which they were calculated), a rainbow attack compares the hash of a password with those stored in the table to match and identify the correct one.
>
>    _Traffic Interception_: Intercepted communications allow bots/a hacker to read your passwords in plain text and unencrypted.
>
> - **Advanced Persistent Threats (APTs)** - a multi-phase, long-term stealthy operation carried out by well-funded and organized groups carried out against organizations or nations for business or political reasons. The main purpose of APTs is to deploy customized malware on one or more of the target's systems and remain there, undetected.


