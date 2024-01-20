# Chapter 1: Introduction to Cybersecurity
<br>
  1.1 Understanding Cybersecurity
  
_What is Cybersecurity?_ :
Cybersecurity is the practice of _protecting systems, networks, and digital assets from malicious attacks¹, unauthorized access, and data breaches_. 

(_CISCO Introduction to Cybersecurity - What Is Cybersecurity?_
Cybersecurity is the ongoing effort to protect individuals, organizations and governments from digital attacks by protecting networked systems and data from unauthorized use or harm.)

¹ _What Malicious attacks are we referring to?:_
Intrusion: Imagine your computer system is a fortress - with high walls, a moat, and a secure gate. Inside the Fortress, there's valuable treasure (sensitive data, personal information, and more). An "Intrusion" is like an unwanted visitor attempting to breach the fortress walls and gain access to your treasure. 

_How can an "intruder" get past the gameras, guards, and walls of my castle?_:

Virus: The _sneaky_ infiltrator → The _Virus_ is a _Spy_ who infiltrates the castle _disguised as a trusted messenger_

> **_A Computer Virus_** is a piece of code that attaches itself to a legitimate program/file. When you run the _infected_ program, the virus activates and spreads, like a disguised messenger spreading chaos within the castle.

Trojan Horse: The _Deceptive_ Gift → The _Trojan Horse_ is a _Seemingly innocent gift_ left at the castle gates by an _unknown source._

>**_A Trojan Horse_** is Malware disguised as a legitimate file or program. Like the legendary wooden horse to infitrate Troy, it tricks the user into installing it, giving unauthorized access to the attacker. The Deceptive package carries a hidden threat.

Worm: The Secret _Tunnel_ Digger → The _Worm_ is a _sneaky_ creature that _digs_ secret tunnels _connecting different parts of the castle._

>**_A Computer Worm_** is a _standalone_ program that replicates itself to spread accross the network. It _doesn't need a host file_ to attach to - Just like secret tunnel systems don't rely on existing structures. Works can _rapidly spread through interconnected systems_, like tunnels weaving through the castle's different sections.

**Cybersecurity encompasses a wide range of technologies, Processes, and practices designed to safegaurd our digital world.**

---
## The Threat Landscape in Cybersecurity
_The field of cybersecurity has witnessed significant changes in the nature of threats over the years. Understanding this evolution helps us develop effective strategies to protect agains current and future cyberthreats._

A Historical Perspective:
1. A Background on Viruses and Worms (1980's - 1990's):
- Early viruses were primarily transmitted via infected floppy disks, which were commonly used for software distribution.
  
**Morris Worm: A Pioneering Incident (1988)**:
  The Morris worm, created by Robert Tappan Morris, was unleashed on the internet on November 2, 1988, intended to gauge the size of the internet.
  
  Significance:
  
  _↳Exploited vulnerabilities in Unix-Based systems, primarily "Sendmail" (an older "email,") "Finger (a sort of online yellow pages with public personal information), and weak passwork mechanisms._
  
  _↳Implemented a self-replicating mechanism, allowing it to propagate accross connected systems._
  
★ The Worm spread _faster_ than anticipated, causing system shutdowns and, in some cases, complete unavailability (a total of ~6,000 systems.)

★ Morris' experiment highlighted the unpredictability of malware behaviour and the potential for unintended consequences. 

★ The Incident underscored the need for ethical handling of security research and responsible disclosure of vulnerabilities.

★ In 1989, Morris became the _first person to be tried and convicted unter the Computer Fraud and Abuse Act (CFAA)_ in the United States.

★ The Incident raised awareness about the vulnerability of connected systems and the potential for rapid, self-propagating malware. It also prompted the development + enhancement of security practices.

>**_Another Significant case convicted Under the Computer Fraud & Abuse Act (CFAA)_**
> Kevin Mitnick (1999)
> - In 1979, at 16, Kevin Broke into the Digital Equipment Corporations (DEC) computer network and copid the company's software → he was sentenced to 12 months of prison + 3 years of supervised release.
> - Near the end of his supervised release, he hacked into Pacific Bell voicemail computers → he fled, becoming a fugitive for 2 1/2 years.
> - Kevin Had allegedly gained unauthorized access to dozens of computer networks as a fugitive. He _intercepted and stole computer passwords, altered computer networks, and broke and read private emails.
> - Mitnick was finnaly arrested on February 15, 1996
> - Case Significance: The case became a landmark in the legal landscape of computer crimes, bringing attention to the need for legislation to address computer crimes. It also demonstrated that hacking and unauthorized access to computer networks could be treated as serious criminal offenses.
> - In 2001, Kevin Mitnick wrote a book, **"The Art of Deception: Controlling the Human Element of Security"** (my favorite book to read of his:

>**_Key Takeaway:_**
> - Social Engineering: The art of Manipulating, Influencing, or decieving people in order to gain unauthorized access to information or systems (targeting the _human element._)
> - Mitnick emphasized the ease of gaining access to private services both physically and online by tricking people into willingly or unknowingly give the nescessary information away. Tricks include exploiting the human curiousity for phishing or spamming, exploiting Authority and Compliance to pose as someone with a high respect due, and taking advantage of company privacy blunders, such as picking up sensitive information unproperly discarded outside large company facilities.

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
> The Cube is a framework created in 1991 by John McCumber to help organizations evaluate information security initiatives. The security model has 3 Dimensions:
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


