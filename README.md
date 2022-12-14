```diff
- *Excuse a few spelling errors, some sections compiled with voice to text software*
```


CompTia Security Plus

1. [ Attack Vectors ](#vectors)
2. [ Threat Actors ](#actors)
3. [ Research and Cyber Threat Intelligence ](#research)
4. [ Vulnerabilities by Type and Impact ](#vulnerabilities)
5. [ Attacks by Type ](#attacks)
6. [ Social Engineering ](#social)
7. [ Security Operations ](#operations)


<a name="vectors"></a>
## 1. Attack Vectors  
In computer security, an attack vector is a specific path, method, or scenario that can be exploited to break into an IT system, thus compromising its security. An attack vector may be exploited manually, automatically, or through a combination of manual and automatic activity. 
Often, this is a multi-step process. For instance, malicious code, I E code that the user did not consent to being run and that performs actions the user would not consent to, often operates by being added to a harmless seeming document made available to an end user. When the unsuspecting end user opens the document, the malicious code in question, known as the payload, is executed and performs the abusive tasks it was programmed to execute. These tasks may include things such as spreading itself further, opening up unauthorized access to the IT system, stealing or encrypting the user's documents, and more. In order to limit the chance of discovery once installed, the code in question is often obfuscated by layers of seemingly harmless code. 
   
    Some real world examples of common attack vectors include: 
      
    1. exploiting buffer overflows; this is how the Blaster worm was able to propagate. 
   
    2. exploiting webpages and email to support loading and subsequent execution of JavaScript, or other types of scripts without properly limiting their powers. 
   
    3. exploiting networking protocol flaws to perform unauthorized actions at the other end of a network connection. 
   
    4. phishing: sending deceptive messages to end users to entice them to reveal confidential information, such as passwords. 
   
    5. The attack vectors that the comp teaya 20 22 security + exam wants you to be familiar with include direct access, wireless, e mail, removable media, social media, cloud systems, and supply chains. 
   
   
    1.1   Direct Access 
    Direct access encomposes attack methods where the hacker gains physical access to facilities, hardware, and infrastructure. When the attacker has direct access it can be trivial to infect devices and systems. Common attacks inlude keylogger equipment and malware, malicious flash drive payloads, and well-hidden network or data capture software and systems. The lead countermeasure that your exam will ask you to identify is, physical security. 
   
    1.2   Wireless 
    The comp teaya exam focuses on three wireless attack vectors. These are: rogue access points, unsecure access points, and the evil twin attack. These attacks are covered in depth during the attacks by type, network level sub-set, wireless attacks sub-section of this course. The wireless attacks sub-section of this course covers a total of 9 attack types along this vector. The lead countermeasure that your exam will ask you to identify is, secure Wi-Fi networks. 
   
    1.3   Email 
    Email is the vector used for attacks such as spam, the many varieties of fishing, invoice scams, and ransomware. There are 13 unique attacks of this vector type covered later in domain 1 of this course, most of them in the social engineering sub-section. Your exam wants you to identify user training as the key countermeasure of this vector. Your exam might obscure the phrase user training by showing you examples, or sub-sects, like fishing simulations or security awareness programs.   
   
    1.4   Removable Media 
    Removable media, while tied closely to the direct access vector, is unique in that it is so portable. A very good pop-culture example of this attack vector is the Mr. Robot scene from season 1, episode 6, where the malware author working with Elliot casually drops infected U S B drives in the parking lot of a prison. We soon see the attack find success, when a prison guard gleefully picks up the free u s b drive and satisfies his natural curiosity by plugging it straight into an internally networked device. While this vector may or may not be independent of the direct access vector in your exam, the countermeasure remains physical security and external device port security. Although in our colorful example, user training would have also stopped this attack. 
   
    1.5   Social Media 
    Social media is the predominant vector in hybrid warfare and influence campaigns. We are seeing this vector become a hot zone of hybrid warfare on a nation state level throughout the Russian invasion of Ukraine. The battle for our minds is on full display in this vector as both Russia and the Ukranian Western Alliance fight for likes, sympathy, and the re-writing of history. Your exam wants you to identify acceptable use policies as the primary countermeasure of this vector. 
   
    1.6   Cloud Systems 
    The cloud vector involves unsecure applications, sometimes hosted in secure marketplaces, misconfigured infrastructure, and shadow I T. All of these attacks and more are covered in the domain one, attacks by type subsection of this course. Your security + exam wants you to identify cloud configuration management and C A S B as the primary counter-measures. 
   
      1.6.1   CASB 
      What is C A S B? A cloud access security broker, sometimes pronounced cas-bee, is on-premises or cloud based software that sits between cloud service users and cloud applications, and monitors all activity and enforces security policies. A cas-bee can offer services such as monitoring user activity, warning administrators about potentially hazardous actions, enforcing security policy compliance, and automatically preventing malware. 
   
    1.7   Supply Chain 
    The supply chain vector refers to attacks on vendors in an organizations supply chain, sometimes as a precursor to direct attack. While supply chain attacks are covered in great depth later in this course, for now it is sufficient to know that the lead countermeasure of this vector will be vendor screening. 
    ```
   
  <a name="actors"></a>
## 2   Threat Actors  
    A threat actor or malicious actor is either a person or a group of people that take part in an action that is intended to cause harm to the cyber realm. This realm includes; computers, devices, systems, or networks. The term is typically used to describe individuals or groups that perform malicious acts against a person or an organization of any type or size. Threat actors engage in cyber related offenses to exploit open vulnerabilities and disrupt operations. Threat actors have different educational backgrounds, skills, and resources. The frequency and classification of cyber attacks changes rapidly. The background of threat actors helps dictate who they target, how they attack, and what information they seek. There are a number of threat actors including: cyber criminals, nation-state actors, ideologues, often referred to as hacktivists, thrill seekers and trolls, insiders, and competitors. These threat actors all have distinct motivations, techniques, targets, and uses of stolen data. To prepare you for your security + exam, these threat actors are broken up into nine categories commonly used by comp teaya; Hackers, A P tees, insider threats, state actors, hacktivists, criminal organizations, shadow I T, business competitors, and everyones favorite; script kiddies. Each threat actor can have a set of main pulling factors, or attributes. The four common to the security + exam are; internal and external, sophistication and capability, resources and funding, and intent and motivation. 
   
    2.2   Hackers 
      If you are taking this course, it is likely that you can be categorized as a hacker. Unlike the other threat actors covered for your exam, a general hacker is not bad, or criminal, by definition alone. The hacker threat actor has three sub-categories according to your exam. The authorized hacker, the unauthorized hacker, and the semi-authorized hacker. 
      2.2.1   Authorized 
        The authorized hacker is a skilled actor who is employed, either internally, as a contractor, or through a service provider agreement, to help defend the organizations cyber-security. Often through red team activities, which we will cover in depth during our security operations sub-section of domain 1. 
      2.2.2   Unauthorized 
        The unauthorized hacker is the infamous black hat, wielding a high skill level for malicious activities against the target or organization. 
      2.2.3   Semi-authorized 
        The semi-authorized hacker, sometimes referred to as a gray hat hacker. Here at Nomad Security, the most recognizable example would be the bug-bounty hunter. Abiding by the scope of a specific program and operating under a safe-harbour contract, the bounty hunter uses this semi-authorized infrastructure to find and report bugs, often for a cash payout per severity level of each bug. Your exam will refer to this as the, finding but not exploiting, threat actor. 
   
    2.3   Advanced persistent threat (APT) 
      An advanced persistent threat (APT) is a stealthy threat actor, typically a nation state or state-sponsored group, which gains unauthorized access to a computer network and remains undetected for an extended period.[1][2] In recent times, the term may also refer to non-state-sponsored groups conducting large-scale targeted intrusions for specific goals.Such threat actors' motivations are typically political or economic. Every major business sector has recorded instances of cyberattacks by advanced actors with specific goals, whether to steal, spy, or disrupt. These targeted sectors include government, defense, financial services, legal services, industrial, telecoms, consumer goods and many more. Some groups utilize traditional espionage vectors, including social engineering, human intelligence and infiltration to gain access to a physical location to enable network attacks. The purpose of these attacks is to install custom malware (malicious software). The median "dwell-time", or the time an APT attack goes undetected, differs widely between regions. FireEye reported the mean dwell-time for 2018 in the Americas as 71 days, EMEA as 177 days, and APAC as 204 days.[5] Such a long dwell-time allows attackers a significant amount of time to go through the attack cycle, propagate, and achieve their objective. 
   
    2.4   Insider threats 
      Insiders are a type of threat actor that can either be an insider who sells network information to other adversaries, or it can be a disgruntled employee who feels like they need to retaliate because they feel like they have been treated unfairly. Insider attacks can be challenging to prevent; however, with a structured logging and analysis plan in place, insider threat actors can be detected after a successful attack. 
   
    2.5   State actors 
      Nation-state threat actors aim to gain intelligence of national interest. Nation-state actors can be interested in a number of sectors, including nuclear, financial, and technology information.[2] There are two ways nations use nation-state actors. First, some nations make use of their own governmental intelligence agencies. Second, some nations work with organizations that specialize in cyber crime. States that use outside groups can be tracked; however, states might not necessarily take accountability for the act conducted by the outside group. Nation-state actors can attack both other nations or other outside organizations, including private companies and non-governmental organizations. They typically aim to bolster their nation-state's counterintelligence strategy.[2] Nation-state attacks can include: strategic sabotage or critical infrastructure attacks. Nation states considered an incredibly large group of threat actors in the cyber realm. 
   
    2.6   Hacktivists 
      Hacktivism is a term that was coined in the early days of the World Wide Web. It is derived from a combination of two words: hacking and activism.[2] Hacktivists typically are individuals or entities that are ready to commit cyber crimes to further their own beliefs and ideologues.[3] Many hactivists include anti-capitalists or anti-corporate idealists and their attacks are inspired by similar political and social issues. 
   
    2.7   Criminal syndicates 
      Cyber criminals have two main objectives. First, they want to take infiltrate a system to access valuable data or items. Second, they want to ensure that they avoid legal consequence after infiltrating a system. Cyber criminal can be broken down into three sub-groups: mass scammers/automated hackers, criminal infrastructure providers, and big game hunters.Mass scammers and automated hackers include cyber criminals who attacks a system to gain monetary success. These threat actors use tools to infect organization computer systems. They then seek to gain financial compensation for victims to retrieve their data.[2] Criminal infrastructure providers are a group of threat actors that aim to use tools to infect a computer system of an organization. Criminal infrastructure providers then sell the organization's infrastructure to an outside organization so they can exploit the system. Typically, victims of criminal infrastructure providers are unaware that their system has been infected.[2] Big game hunters are another sub-group of cyber criminals that aim to attack one single, but high-value target. Big game hunters spend extra time learning about their target, including system architecture and other technologies used by their target. Victims can be targeted by email, phone attacks or by social engineering skills. 
   
    2.8   Shadow IT 
      In big organizations, shadow IT refers to information technology (IT) systems deployed by departments other than the central IT department, to work around[1] the perceived or actual shortcomings of the central information systems.[2] Shadow IT often introduces security and compliance concerns. 
   
    2.9   Competitors 
      Competitors can gain access to organization secrets that are typically secure. Organizations can try to gain a stronger knowledge of business intelligence to protect themselves against a competition threat actor. 
   
    2.10  Script kiddies 
      Script kiddies are often broken into two categeories; thrill seekers and trolls. And while the language and premise may sound silly, these threat actors can do serious damage and are highly unpredictable. A thrill seeker is a type of threat actor that attacks a system for the sole purpose of experimentation.[3] Thrill seekers are interested in learning more about how computer systems and networks operate and want to see how much data they can infiltrate within a computer system. While they do not aim to cause major damage, they can cause problems to an organization's system. As time has gone on, thrill seekers have evolved into modern trolls. Similar to thrill seekers, a troll is a type of person or group that attacks a system for recreation. However, unlike thrill seekers, trolls aim to cause malice.[2] Modern day trolls can cause both misinformation and direct harm. 
   
  <a name="research"></a>
## 3.  Research and Cyber Threat Intelligence 
        Cyber threat intelligence (CTI) is knowledge, skills and experience-based information concerning the occurrence and assessment of both cyber and physical threats and threat actors that is intended to help mitigate potential attacks and harmful events occurring in cyberspace.[1] Cyber threat intelligence sources include open source intelligence, social media intelligence, human Intelligence, technical intelligence, device log files, forensically acquired data or intelligence from the internet traffic and data derived for the deep and dark web. 
   
        In recent years, threat intelligence has become a crucial part of companies cyber security strategy since it allows companies to be more proactive in their approach and determine which threats represent the greatest risks to a business. This puts companies on a more proactive front - actively trying to find their vulnerabilities and prevents hacks before they happen.[2] This method is gaining importance in recent years since, as IBM estimates, the most common method companies are hack is via threat exploitation (47% of all attacks)[3] 
   
        Threat vulnerabilities have risen in recent years also do to the COVID-19 pandemic and more people working from home - which makes companies' data more vulnerable. Due to the growing threats on one hand, and the growing sophistication needed for threat intelligence, many companies have opted in recent years to outsource their threat intelligence activities to a managed security provider (MSSP). 
   
    3.1   Threat Intelligence Sources 
      3.1.1   OSINT 
        Open-source intelligence (OSINT) is the collection and analysis of data gathered from open sources (overt and publicly available sources) to produce actionable intelligence. OSINT is primarily used in national security, law enforcement, and business intelligence functions and is of value to analysts who use non-sensitive intelligence in answering classified, unclassified, or proprietary intelligence requirements across the previous intelligence disciplines. 
   
        OSINT is distinguished from research in that it applies the process of intelligence to create tailored knowledge supportive of a specific decision by a specific individual or group. 
   
        OSINT sources can be divided up into six different categories of information flow: 
   
        3.1.1.1   Media 
          Print newspapers, magazines, radio, and television from across and between countries. 
        3.1.1.2   Internet 
          Online publications, blogs, discussion groups, citizen media (i.e. – cell phone videos, and user created content), YouTube, and other social media websites (i.e. – Facebook, Twitter, Instagram, etc.). This source also outpaces a variety of other sources due to its timeliness and ease of access. 
        3.1.1.3   Public Government Data 
          Public government reports, budgets, hearings, telephone directories, press conferences, websites, and speeches. Although this source comes from an official source they are publicly accessible and may be used openly and freely. 
        3.1.1.4   Professional and Academic Publications  
          Information acquired from journals, conferences, symposia, academic papers, dissertations, and theses.  
        3.1.1.5   Commercial Data  
          Commercial imagery, financial and industrial assessments, and databases.  
        3.1.1.6   Grey Literature  
          Technical reports, preprints, patents, working papers, business documents, unpublished works, and newsletters.  
    
      3.1.2   Dark Web  
        The dark web is the World Wide Web content that exists on darknets: overlay networks that use the Internet but require specific software, configurations, or authorization to access. Through the dark web, private computer networks can communicate and conduct business anonymously without divulging identifying information, such as a user's location.[5][6] The dark web forms a small part of the deep web, the part of the Web not indexed by web search engines, although sometimes the term deep web is mistakenly used to refer specifically to the dark web.[7][2][8]  
    
        The darknets which constitute the dark web include small, friend-to-friend peer-to-peer networks, as well as large, popular networks such as Tor, Freenet, I2P, and Riffle operated by public organizations and individuals.[6] Users of the dark web refer to the regular web as Clearnet due to its unencrypted nature.[9] The Tor dark web or onionland[10] uses the traffic anonymization technique of onion routing under the network's top-level domain suffix .onion.  
    
      3.1.3   Vulnerability Databases  
        A vulnerability database (VDB) is a platform aimed at collecting, maintaining, and disseminating information about discovered computer security vulnerabilities. The database will customarily describe the identified vulnerability, assess the potential impact on affected systems, and any workarounds or updates to mitigate the issue. A VDB will assign a unique identifier to each vulnerability cataloged such as a number (e.g. 123456) or alphanumeric designation (e.g. VDB-2020-12345). Information in the database can be made available via web pages, exports, or API. A VDB can provide the information for free, for pay, or a combination thereof.  
      3.1.4   Indicators of Compromise  
        sometimes called “threat indicators” are “pieces of forensic data, such as data found in system log entries or files, that identify potentially malicious activity on a system or network.”  
      3.1.5   STIX and TAXII  
        3.1.5.1   Structured Threat Information eXpression (STIX)  
          Structured threat information expression, or sticks, is a machine-to-machine cyber threat information-sharing language. It creates a uniform standard for using APIs to structure data transport.  
        3.1.5.2   Trusted Automated eXchange of Intelligence Information (TAXII)  
          This program facilitates information sharing between industry, critical infrastructure operators and governments by providing participants a way to share data via the Trusted Automated eXchange of Indicator Information (TAXII). The structured threat information expression, or sticks, language covered before is designed to completely comply with TAXII data transport norms.  
      3.1.6   Closed or Proprietary Sources  
        These vendor-specific threat intelligence feeds limited to paying customers, which are intended to keep customers informed and secure, while not tipping off threat actors  
      3.1.7   Public and Private Sources  
        Public sources of threat intelligence include threatcrowd.org and similar alternatives. These provide threat-hunting and intelligence gathering free of charge for companies and organizations.  
    
    3.2 Research  
      Research is the other end of threat intelligence. Staying on the cutting edge of research allows cyber-security professionals the upper hand when identifying or responding to emerging and creative threats.  
      3.2.1   Conferences  
        Conferences are not just great events to network, listen to cutting edge talks based off peer reviewed white papers, and participate in capture the flag tournaments for prize and prestige. They are also one of the most fun ways to dive into the hacker and maker mindset. From lockpicking to biohacking, being in the know is more important in cybersecurity than any other I T field out there.  
      3.2.2   Threat and Vulnerability Feeds  
        Vulnerability feeds differ from vulnerability databases in that they are often direct over time logs from individual organizations. All of these vulnerability feeds can be compiled in what your security + exam will refer to as a central vulnerability management system.  
      3.2.3   Social Media  
        InfoSec social media can at times be a dumpster fire. Not unlike every other niche community out there. But you will also find recent vulnerabilities, techniques, emerging threats, and peer mentoring opportunities on platforms such as Twitter and YouTube. Additionally, a large amount of learning content is freely available on both.  
      3.2.4   Academic Journals  
        Academic journals are unique in that they are often peer reviewed. Your security + exam will consider these results of a higher quality than other like sources if asked in context within a question.  
      3.2.5   Vendor Websites  
        Individual vendors will often create a specific location, usually accessible from their front-facing website, to keep track of all known vulnerabilities. This is usually in an effort to help maintain proper patching guidelines.  
      3.2.6   Requests for Comments (RFC)  
        Your exam will almost solely be referring to the Internet Engineering Task Force, the I E T F, when speaking in context of requests for comments. Requests for comments are a way for a governing body, like the I E T F, to ask for open source comments on standards or technologies that are sometimes experimental or otherwise emerging.  
      3.2.8   Adversary tactics, techniques, and procedures (TTP)  
        TTPs are how we describe the behaviors, methods, tools, and strategies that cyber threat actors and hackers use to plan and execute cyber attacks. Often referred to as the why and how of cyber attacks.  
    
  <a name="vulnerabilities"></a>
## 4.  Vulnerabilities by Type and Impact  
    Vulnerabilities are flaws in a computer system that weaken the overall security of the device/system. Vulnerabilities can be weaknesses in either the hardware itself, or the software that runs on the hardware. Vulnerabilities can be exploited by a threat actor, such as an attacker, to cross privilege boundaries (i.e. perform unauthorized actions) within a computer system. To exploit a vulnerability, an attacker must have at least one applicable tool or technique that can connect to a system weakness. In this frame, vulnerabilities are also known as the attack surface.  
    
    Vulnerability management is a cyclical practice that varies in theory but contains common processes which include: discover all assets, prioritize assets, assess or perform a complete vulnerability scan, report on results, remediate vulnerabilities, verify remediation - repeat. This practice generally refers to software vulnerabilities in computing systems.[1] Agile vulnerability management refers preventing attacks by identifying all vulnerabilities as quickly as possible.[2]  
    
    A security risk is often incorrectly classified as a vulnerability. The use of vulnerability with the same meaning of risk can lead to confusion. The risk is the potential of a significant impact resulting from the exploit of a vulnerability. Then there are vulnerabilities without risk: for example when the affected asset has no value. A vulnerability with one or more known instances of working and fully implemented attacks is classified as an exploitable vulnerability—a vulnerability for which an exploit exists. The window of vulnerability is the time from when the security hole was introduced or manifested in deployed software, to when access was removed, a security fix was available/deployed, or the attacker was disabled—see zero-day attack.  
    
    4.1   Improper or Weak Patch Management  
      4.1.1   Application Patching  
        In many environments, non-Microsoft applications (commonly called third-party apps) get overlooked for patching. Due in part because many management tools (and software vendors) do not offer the same level of automation.  
      4.1.2   OS Patching  
        Windows has historically been (and continues to be) the biggest target. In the age of the smartphone, mobile systems are a common target of threat actors.  
      4.1.3   Firmware Patching  
        Commonly overlooked in IoT devices and other embedded systems, like VoIP phones.  
    4.2   Security Misconfigurations  
      4.2.1   Open Permissions  
        Permissions are a key concept in information security. System, network, and application configurations that give the user more permissions than necessary fail to implement the least privelege paradigm.    
      4.2.2   Open Ports/Services  
        Services and open ports that are not actively being used serve no purpose other than to widen the attack surface presented to threat actors.  
      4.2.3   Default Settings  
        Yet another process issue that poses a serious security risk to an organization or individual. Every device that you put on your network to manage has a default username and password. Think admin admin. Leaving the defaults in place make it trivial for your device to be compromised. Compromised devices can become part of a larger botnet or an immediate pivot point to other networked devices.  
      4.2.4   Unsecure Root Accounts  
        Root accounts with weak passwords allow for simple privelege escalation once the perimeter of the network or device is compromised. Some devices may not even have a root (sudo) password in place. This is more common in I O T devices than workstations.  
      4.2.5   Errors  
        This encompasses the human element in the cybersecurity chain. As we know, humans are the weakest link in this chain and researchers from Stanford University have found that around 88% of all data breaches are caused by an employee mistake.  
      4.2.6   Weak Encryption  
        Simply put, some encryption methods are easier to crack than other. Using deprecated cryptographic algorithms after the recommended lifespan lead to major security issues. An encryption algorithm from just ten years ago might have required hundreds or thousands of hours of non rate limited computing process to crack. Where as todays hacker can spin up cheap, powerful cloud instances to work simultaneously to crack the same algorithm in an hour.  
    4.3   Zero Days  
      The security + exam describes the top zero-day countermeasure as, following security best practices. Additionally, antivirus solutions created on artifical intelligence, machine learning, and U E B A, or user and entity behavior analytics, are considered countermeasures to zero-days. SIEM, IDPS, and EDR/XDR solutions also offer a smaller amount of defense.  
    4.4   Legacy Platforms  
      Legacy applications that might require an outdated version of an operating system. May run aging business-critical applications for which staff to manage is difficult to find.  
    4.5   Third-Party Risks  
      4.5.1   Data Storage  
        Sensitive data stored in vendor repositories, such as cloud services, needs to be secured, access managed, and usage monitored.  
      4.5.2   Lack of Vendor Support  
        Vendor may end support for legacy application versions before an organization is ready to support dependent business processes on another platform. For apps beyond mainstream support, security patches may be expensive or unavailable entirely.  
      4.5.3   System Integration  
        System integration partners working on systems often have privileged remote or physical access, necessitating security measures and process controls. System integration vulnerabilities have an increased risk of insider attack associated with it.  
      4.5.4   Vendor Management  
        Many orgs are reducing the number of vendors they work with and requiring stricter onboarding procedures. Vendors may be required to submit to an external audit and agree to strict communication and reporting requirements in event of potential breach.  
      4.5.5   Supply Chain  
        Supply chain security has become a significant concern for organizations. Includes, suppliers, manufacturers, distributors, and customers. A breach at any link in the supply chain can result in business impact.  
      4.5.6   Outsourced Code Development  
        Source code storage and access control will be important. Development workstations and environments must be secured to the organization’s standards  
    4.6   Cloud based vs On-Premise Vulnerabilities  
      The 20 22 security + exam will ask you to identify which vulnerabilities are cloud based, versus which vulnerabilities are considered on-premises. These can be contentious questions as there remains some ambiguity in certain attacks. For example, misconfigurations will be, according to comp teaya, a significant vulnerability in both the cloud based and on premises models. There are also disruptive attacks such as D dos attacks which often interact, whether in collusion or to bypass, cloud based infrastructure. D dos attacks however can be far more disruptive at scale when carried out on premises. The shared responsibility model illustrates some of the common areas of ownership in cloud based vs on premise computing security.  
    4.7   Impacts of Vulnerabilities  
      4.7.1   Data Loss  
        Data loss is an error condition in information systems in which information is destroyed by failures (like failed spindle motors or head crashes on hard drives) or neglect (like mishandling, careless handling or storage under unsuitable conditions) in storage, transmission, or processing. Information systems implement backup and disaster recovery equipment and processes to prevent data loss or restore lost data.[1] Data loss can also occur if the physical medium containing the data is lost or stolen.  
    
        Data loss is distinguished from data unavailability, which may arise from a network outage. Although the two have substantially similar consequences for users, data unavailability is temporary, while data loss may be permanent. Data loss is also distinct from data breach, an incident where data falls into the wrong hands, although the term data loss has been used in those incidents.  
      4.7.2   Data Exfiltration  
        Data exfiltration occurs when malware and/or a malicious actor carries out an unauthorized data transfer from a computer. It is also commonly called data extrusion or data exportation. Data exfiltration is also considered a form of data theft. Since the year 2000, a number of data exfiltration efforts severely damaged the consumer confidence, corporate valuation, and intellectual property of businesses and national security of governments across the world.  
      4.7.3   Data Breaches  
        A data breach is a security violation, in which sensitive, protected or confidential data is copied, transmitted, viewed, stolen or used by an individual unauthorized to do so.[1] Other terms are unintentional information disclosure, data leak, information leakage, and data spill. Incidents range from concerted attacks by individuals who hack for personal gain or malice (black hats), organized crime, political activists or national governments, to poorly configured system security or careless disposal of used computer equipment or data storage media. Leaked information can range from matters compromising national security, to information on actions which a government or official considers embarrassing and wants to conceal. A deliberate data breach by a person privy to the information, typically for political purposes, is more often described as a "leak".  
      4.7.4   Identity Theft  
        Identity theft occurs when someone uses another person's personal identifying information, like their name, identifying number, or credit card number, without their permission, to commit fraud or other crimes. The term identity theft was coined in 1964.[1] Since that time, the definition of identity theft has been statutorily defined throughout both the U.K. and the United States as the theft of personally identifiable information. Identity theft deliberately uses someone else's identity as a method to gain financial advantages or obtain credit and other benefits,[2][3] and perhaps to cause other person's disadvantages or loss. The person whose identity has been stolen may suffer adverse consequences,[4] especially if they are falsely held responsible for the perpetrator's actions. Personally identifiable information generally includes a person's name, date of birth, social security number, driver's license number, bank account or credit card numbers, PINs, electronic signatures, fingerprints, passwords, or any other information that can be used to access a person's financial resources.[5  
      4.7.5   Reputation Loss  
        Reputational damage is the loss to financial capital, social capital and/or market share resulting from damage to a firm's reputation. This is often measured in lost revenue, increased operating, capital or regulatory costs, or destruction of shareholder value.  
      4.7.6   Financial Loss  
        And of course, all of these vulnerabilities can result in general financial loss to the company or organization.  
    
  <a name="attacks"></a>
## 5.  Attacks by Type  
  ```
    5.1   Malware  
      Malware (a portmanteau for malicious software) is any software intentionally designed to cause disruption to a computer, server, client, or computer network, leak private information, gain unauthorized access to information or systems, deprive users access to information or which unknowingly interferes with the user's computer security and privacy.[1][2][3][4] By contrast, software that causes harm due to some deficiency is typically described as a software bug.[5] Malware poses serious problems to individuals and businesses on the Internet.[6][7] According to Symantec’s 2018 Internet Security Threat Report (ISTR), malware variants number has increased to 669,947,865 in 2017, which is twice as many malware variants as in 2016.[8] Cybercrime, which includes malware attacks as well as other crimes committed by computer, was predicted to cost the world economy 6 trillion dollars in 2021, and is increasing at a rate of 15% per year.[9]  
    
      Many types of malware exist, including computer viruses, worms, Trojan horses, ransomware, spyware, adware, rogue software, wiper, and scareware. The defense strategies against malware differs according to the type of malware but most can be thwarted by installing antivirus software, firewalls, applying regular patches to reduce zero-day attacks, securing networks from intrusion, having regular backups and isolating infected systems. Malware is now being designed to evade antivirus software detection algorithms.  
    
      5.1.1   Ransomware  
        Sometimes called crypto-malware, ransomware is a type of malware from crypto virology that threatens to publish the victim's personal data or perpetually block access to it unless a ransom is paid. While some simple ransomware may lock the system without damaging any files, more advanced malware uses a technique called cryptoviral extortion. It encrypts the victim's files, making them inaccessible, and demands a ransom payment to decrypt them.[1][2][3][4] In a properly implemented cryptoviral extortion attack, recovering the files without the decryption key is an intractable problem – and difficult to trace digital currencies such as paysafecard or Bitcoin and other cryptocurrencies are used for the ransoms, making tracing and prosecuting the perpetrators difficult.  
        5.1.1.1   Screen Locking Ransomware  
          Lock-screens, or screen lockers is a type of “cyber police” ransomware that blocks screens on Windows or Android devices with a false accusation in harvesting illegal content, trying to scare the victims into paying up a fee.[54] Jisut and SLocker impact Android devices more than other lock-screens, with Jisut making up nearly 60 percent of all Android ransomware detections.  
        5.1.1.2   Encryption Based Ransomware  
          Encryption-based ransomware, like the name suggests, is a type of ransomware that encrypts all files on an infected machine. These types of malware then display a pop-up informing the user that their files have been encrypted and that they must pay (usually in Bitcoin) to recover them. Some examples of encryption-based ransomware are CryptoLocker and WannaCry.  
      5.1.2   Bots  
        A botnet is a logical collection of Internet-connected devices, such as computers, smartphones or Internet of things (IoT) devices whose security have been breached and control ceded to a third party. Each compromised device, known as a "bot," is created when a device is penetrated by software from a malware (malicious software) distribution. The controller of a botnet is able to direct the activities of these compromised computers through communication channels formed by standards-based network protocols, such as IRC and Hypertext Transfer Protocol (HTTP).[3][4]  
    
        Botnets are increasingly rented out by cyber criminals as commodities for a variety of purposes.  
      5.1.3   Rootkit  
        A rootkit is a collection of computer software, typically malicious, designed to enable access to a computer or an area of its software that is not otherwise allowed (for example, to an unauthorized user) and often masks its existence or the existence of other software.[1] The term rootkit is a compound of "root" (the traditional name of the privileged account on Unix-like operating systems) and the word "kit" (which refers to the software components that implement the tool).[2] The term "rootkit" has negative connotations through its association with malware  
      5.1.4   Backdoor  
        A backdoor is a method of bypassing normal authentication procedures, usually over a connection to a network such as the Internet. Once a system has been compromised, one or more backdoors may be installed in order to allow access in the future,[47] invisibly to the user.  
      5.1.6   Logic bombs  
        A logic bomb is a piece of code intentionally inserted into a software system that will set off a malicious function when specified conditions are met. For example, a programmer may hide a piece of code that starts deleting files (such as a salary database trigger), should they ever be terminated from the company.  
    
        Software that is inherently malicious, such as viruses and worms, often contain logic bombs that execute a certain payload at a pre-defined time or when some other condition is met. This technique can be used by a virus or worm to gain momentum and spread before being noticed. Some viruses attack their host systems on specific dates, such as Friday the 13th or April Fools' Day. Trojans and other computer viruses that activate on certain dates are often called "time bombs".  
      5.1.7   Spyware  
        Spyware (a portmanteau for spying software) is software with malicious behavior that aims to gather information about a person or organization and send it to another entity in a way that harms the user—for example, by violating their privacy or endangering their device's security. This behavior may be present in malware as well as in legitimate software. Websites may engage in spyware behaviors like web tracking. Hardware devices may also be affected.[1] Spyware is frequently associated with advertising and involves many of the same issues. Because these behaviors are so common, and can have non-harmful uses, providing a precise definition of spyware is a difficult task.  
      5.1.8   Trojans  
        In computing, a Trojan horse is any malware that misleads users of its true intent. The term is derived from the Ancient Greek story of the deceptive Trojan Horse that led to the fall of the city of Troy.[1][2][3][4][5]  
    
        Trojans generally spread by some form of social engineering; for example, where a user is duped into executing an email attachment disguised to appear innocuous (e.g., a routine form to be filled in), or by clicking on some fake advertisement on social media or anywhere else. Although their payload can be anything, many modern forms act as a backdoor, contacting a controller who can then have unauthorized access to the affected computer.[6] Ransomware attacks are often carried out using a trojan.  
    
        Unlike computer viruses, worms, and rogue security software, trojans generally do not attempt to inject themselves into other files or otherwise propagate themselves.  
      5.1.9   Remote access Trojan (RAT)  
        A remote access trojan (RAT, sometimes called creepware)[5] is a type of malware that controls a system through a remote network connection. While desktop sharing and remote administration have many legal uses, "RAT" connotes criminal or malicious activity. A RAT is typically installed without the victim's knowledge, often as payload of a Trojan horse, and will try to hide its operation from the victim and from computer security software and other anti-virus software.  
      5.1.10  Worms  
        A computer worm is a standalone malware computer program that replicates itself in order to spread to other computers.[1] It often uses a computer network to spread itself, relying on security failures on the target computer to access it. It will use this machine as a host to scan and infect other computers. When these new worm-invaded computers are controlled, the worm will continue to scan and infect other computers using these computers as hosts, and this behavior will continue.[2] Computer worms use recursive methods to copy themselves without host programs and distribute themselves based on the law of exponential growth, thus controlling and infecting more and more computers in a short time.[3] Worms almost always cause at least some harm to the network, even if only by consuming bandwidth, whereas viruses almost always corrupt or modify files on a targeted computer.  
    
        Many worms are designed only to spread, and do not attempt to change the systems they pass through. However, as the Morris worm and Mydoom showed, even these "payload-free" worms can cause major disruption by increasing network traffic and other unintended effects.  
      5.1.11  Potentially unwanted programs (PUPs)  
        potentially unwanted program (PUP) or potentially unwanted application (PUA) is software that a user may perceive as unwanted or unnecessary. It is used as a subjective tagging criterion by security and parental control products. Such software may use an implementation that can compromise privacy or weaken the computer's security. Companies often bundle a wanted program download with a wrapper application and may offer to install an unwanted application, and in some cases without providing a clear opt-out method. Antivirus companies define the software bundled as potentially unwanted programs[1][2] which can include software that displays intrusive advertising (adware), or tracks the user's Internet usage to sell information to advertisers (spyware), injects its own advertising into web pages that a user looks at, or uses premium SMS services to rack up charges for the user.[3][4] A growing number of open-source software projects have expressed dismay at third-party websites wrapping their downloads with unwanted bundles, without the project's knowledge or consent. Nearly every third-party free download site bundles their downloads with potentially unwanted software.[5] The practice is widely considered unethical because it violates the security interests of users without their informed consent. Some unwanted software bundles install a root certificate on a user's device, which allows hackers to intercept private data such as banking details, without a browser giving security warnings. The United States Department of Homeland Security has advised removing an insecure root certificate, because they make computers vulnerable to serious cyberattacks.[6] Software developers and security experts recommend that people always download the latest version from the official project website, or a trusted package manager or app store.  
      5.1.12  Fileless virus  
        Fileless malware is a variant of computer related malicious software that exists exclusively as a computer memory-based artifact i.e. in RAM.  
    
        It does not write any part of its activity to the computer's hard drive meaning that it's very resistant to existing Anti-computer forensic strategies that incorporate file-based whitelisting, signature detection, hardware verification, pattern-analysis, time-stamping, etc., and leaves very little by way of evidence that could be used by digital forensic investigators to identify illegitimate activity.  
    
        As malware of this type is designed to work in-memory, its longevity on the system exists only until the system is rebooted  
      5.1.13  Keyloggers  
        Keystroke logging, often referred to as keylogging or keyboard capturing, is the action of recording (logging) the keys struck on a keyboard,[1][2] typically covertly, so that a person using the keyboard is unaware that their actions are being monitored. Data can then be retrieved by the person operating the logging program. A keystroke recorder or keylogger can be either software or hardware.  
    
        While the programs themselves are legal,[3] with many designed to allow employers to oversee the use of their computers, keyloggers are most often used for stealing passwords and other confidential information.[4][5]  
    
        Keylogging can also be used to study keystroke dynamics[6] or human-computer interaction. Numerous keylogging methods exist, ranging from hardware and software-based approaches to acoustic cryptanalysis.  
      5.1.14  Command and control  
        a computer controlled by an attacker or cybercriminal which is used to send commands to systems compromised by malware and receive stolen data from a target network.  
    5.2   Physical Attacks  
      5.2.1   Skimming  
        Skimming is the theft of personal information which has been used in an otherwise normal transaction. The thief can procure a victim's card number using basic methods such as photocopying receipts or more advanced methods such as using a small electronic device (skimmer) to swipe and store hundreds of victims' card numbers. Common scenarios for skimming are taxis, restaurants or bars where the skimmer has possession of the victim's payment card out of their immediate view.[20] The thief may also use a small keypad to unobtrusively transcribe the three or four-digit card security code, which is not present on the magnetic strip.  
      5.2.2   Malicious Device  
        5.2.2.1   USB cable  
          USB cable attacks compromise devices like phones and tablets which use the same cable for charging and data transfer, typically a USB cable. The goal of the attack is to either install malware on the device, or to surreptitiously copy potentially sensitive data.  
        5.2.2.2   Flash Drive  
          The top examples of malware spread by USB flash drives are Stuxnet, Flame Modular Malware, and the Duqu collection. Often taking advantages of quality of life features like the windows autorun feature, USB drives can quickly drop a malicious payload on an unsuspecting system without any user input.  
      5.2.3   Carding (Cloning)  
        Carding is a term describing the trafficking and unauthorized use of credit cards.[1] The stolen credit cards or credit card numbers are then used to buy prepaid gift cards to cover up the tracks.[2] Activities also encompass exploitation of personal data,[3] and money laundering techniques.[4] Modern carding sites have been described as full-service commercial entities.  
    5.3   A.I. Poisoning and Cryptographic Attacks  
      5.3.1 Tainted training data for machine learning  
        Data poisoning that supplies AI and ML algorithms with adversarial data that serves the attackers purposes, or attacks against privacy.  
      5.3.2 Security of machine learning algorithms  
        Validate quality and security of the data sources. Secure infrastructure and environment where AI and ML is hosted. Review, test, and document changes to AI and ML algorithms.  
      5.3.3 Cryptographic Collision  
        In computer science, a hash collision or clash[citation needed] is when two pieces of data in a hash table share the same hash value. The hash value in this case is derived from a hash function which takes a data input and returns a fixed length of bits.[1]  
    
        Although hash algorithms have been created with the intent of being collision resistant, they can still sometimes map different data to the same hash (by virtue of the pigeonhole principle). Malicious users can take advantage of this to mimic, access, or alter data.[2]  
    
        Due to the possible negative applications of hash collisions in data management and computer security (in particular, cryptographic hash functions), collision avoidance has become an important topic in computer security.  
      5.3.4 Cryptographic Downgrade  
        A downgrade attack, also called a bidding-down attack[1] or version rollback attack, is a form of cryptographic attack on a computer system or communications protocol that makes it abandon a high-quality mode of operation (e.g. an encrypted connection) in favor of an older, lower-quality mode of operation (e.g. cleartext) that is typically provided for backward compatibility with older systems.[2] An example of such a flaw was found in OpenSSL that allowed the attacker to negotiate the use of a lower version of TLS between the client and server.[3] This is one of the most common types of downgrade attacks. Opportunistic encryption protocols such as STARTTLS are generally vulnerable to downgrade attacks, as they, by design, fall back to unencrypted communication. Websites which rely on redirects from unencrypted HTTP to encrypted HTTPS can also be vulnerable to downgrade attacks (e.g., sslstrip), as the initial redirect is not protected by encryption.  
      5.3.5 Birthday Attack  
        This is an extremely high level mathmatical attack. A birthday attack is a type of cryptographic attack that exploits the mathematics behind the birthday problem in probability theory. This attack can be used to abuse communication between two or more parties. The attack depends on the higher likelihood of collisions found between random attack attempts and a fixed degree of permutations  
    5.4   Application Level Attacks  
      5.4.1   Injection Vulnerabilities  
        Code injection is the exploitation of a computer bug that is caused by processing invalid data. The injection is used by an attacker to introduce (or "inject") code into a vulnerable computer program and change the course of execution. The result of successful code injection can be disastrous, for example, by allowing computer viruses or computer worms to propagate.  
    
        Code injection vulnerabilities occur when an application sends untrusted data to an interpreter. Injection flaws are most often found in SQL, LDAP, XPath, NoSQL queries, OS commands, XML parsers, SMTP headers, program arguments, etc. Injection flaws tend to be easier to discover when examining source code than via testing.[1] Scanners and fuzzers can help find injection flaws.[2]  
    
        Injection can result in data loss or corruption, lack of accountability, or denial of access. Injection can sometimes lead to complete host takeover.  
    
        5.4.1.1   SQL Injection [Structured Query Language]  
          SQL injection is a code injection technique used to attack data-driven applications, in which malicious SQL statements are inserted into an entry field for execution (e.g. to dump the database contents to the attacker).[1][2] SQL injection must exploit a security vulnerability in an application's software, for example, when user input is either incorrectly filtered for string literal escape characters embedded in SQL statements or user input is not strongly typed and unexpectedly executed. SQL injection is mostly known as an attack vector for websites but can be used to attack any type of SQL database.  
    
          SQL injection attacks allow attackers to spoof identity, tamper with existing data, cause repudiation issues such as voiding transactions or changing balances, allow the complete disclosure of all data on the system, destroy the data or make it otherwise unavailable, and become administrators of the database server  
        5.4.1.2   LDAP Injection [Lightweight Directory Access Protocol]  
          LDAP injection is a code injection technique used to exploit web applications which could reveal sensitive user information or modify information represented in the LDAP (Lightweight Directory Access Protocol) data stores.[1][2][3] LDAP injection exploits a security vulnerability in an application by manipulating input parameters passed to internal search, add or modify functions. When an application fails to properly sanitize user input, it is possible for an attacker to modify an LDAP statement.  
        5.4.1.3   DLL Injection [Dynamic Link Library]  
          DLL injection is a technique used for running code within the address space of another process by forcing it to load a dynamic-link library.[1] DLL injection is often used by external programs to influence the behavior of another program in a way its authors did not anticipate or intend.[1][2][3] For example, the injected code could hook system function calls,[4][5] or read the contents of password textboxes, which cannot be done the usual way.[6] A program used to inject arbitrary code into arbitrary processes is called a DLL injector.  
        5.4.1.4   XML Injection [Extended Markup Language]  
          XML Injection is a type of attack against an application that parses XML input. This attack occurs when XML input containing a reference to an external entity is processed by a weakly configured XML parser. This attack may lead to the disclosure of confidential data, denial of service (DoS), server side request forgery, port scanning from the perspective of the machine where the parser is located, and other system impacts.  
      5.4.2   API Hacking  
        Attempts to manipulate the application programming interface (API) Include DDoS, Man in the Middle, and injection attacks focused on an API Goals are to gain additional resource or data access, or interrupt service  
      5.4.3   SSL Stripping  
        Also known as SSL downgrading, SSL stripping is a technique to downgrade a website from https to http. To execute an SSL strip attack, there must be three entities – victim’s system, secure web server, and attacker’s system. In order to “strip” the TLS/SSL, an attacker intervenes in the redirection from HTTP to HTTPS and intercepts a request from the user to the server. On your security + exam you might see TLS, which is the technology that has replaced SSL. The attack method affects TLS as well.  
      5.4.4   Race Conditions  
        A condition where the system's behavior is dependent on the sequence or timing of other uncontrollable events. A Time-of-Check-to-Time-of-Use (TICTOU) a timing vulnerability that occurs when a program checks access permissions too far in advance of a resource request.  
      5.4.5   Cross-site scripting  
        Cross-site scripting (XSS) is a type of security vulnerability that can be found in some web applications. XSS attacks enable attackers to inject client-side scripts into web pages viewed by other users. A cross-site scripting vulnerability may be used by attackers to bypass access controls such as the same-origin policy. Cross-site scripting carried out on websites accounted for roughly 84% of all security vulnerabilities documented by Symantec up until 2007.[1] XSS effects vary in range from petty nuisance to significant security risk, depending on the sensitivity of the data handled by the vulnerable site and the nature of any security mitigation implemented by the site's owner network.  
      5.4.6   Privilege Escalation  
        Privilege escalation is the act of exploiting a bug, a design flaw, or a configuration oversight in an operating system or software application to gain elevated access to resources that are normally protected from an application or user. The result is that an application with more privileges than intended by the application developer or system administrator can perform unauthorized actions.  
      5.4.7   Pointer/Object Dereference  
        An attack that consists of finding null references in a target program and dereferencing them, causing an exception to be generated. Dereferencing means taking away the reference and giving you what it was actually referring to. The vulnerability in memory that usually causes the applications to crash or a denial of service is a NULL Pointer dereference. In this case, there is nothing at that memory address to dereference (it is empty, or NULL) and the application crashes.  
      5.4.8   Directory Traversal  
        Directory traversal is the act of gaining access to restricted directories. If an attacker is able to gain access to restricted directories through HTTP, it is known as a directory traversal attack. One of the simplest ways to perform directory traversal is by using a command injection attack that carries out the action. Most vulnerability scanners will check for weaknesses with directory traversal/command injection and inform you of their presence. The largest risk is the attacker gaining access to the site's root directory.  
      5.4.9   Server-Side Request Forgery  
      5.4.10  Cross-Site Request Forgery  
        Cross-site request forgery (XSRF or CSRF) similar to cross-site scripting attacks but exploit a different trust relationship. This attack exploits trust that a user has in a website to execute code on the user’s computer. Countermeasures include to create web apps that use secure tokens, and sites that check the referring URL in requests to ensure it came from local site.  
      5.4.11  Replay Attack and Session Replays  
        A replay attack is an attempt to reuse authentication requests. According to your security + exam, this often targets Kerberos authentication.  
      5.4.13  Buffer Overflow Attack  
        A buffer overflow attack is used to exploit poorly written software. Buffer Overflow exist when a developer does not validate user input to ensure that it is of an appropriate size (allows Input that is too large can “overflow” memory buffer).  
      5.4.14  Pass the Hash  
        Pass the Hash is a technique whereby an attacker captures a password hash (as opposed to the password characters) and then passes it through for authentication and lateral access. Your exam will ask you to differentiate pass the hash attacks from pass the ticket attacks. The main difference is pass the hash usually targets NTLM while pass the ticket targets Kerberos. Another primary difference between pass-the-hash and pass-the-ticket, is ticket expiration. Kerberos TGT tickets expire (10 hours by default) whereas NTLM hashes only change when the user changes their password. A TGT ticket must be used within its lifetime, or it can be renewed for a longer period (7 days). For the purposes of your exam, preventing pass the hash attacks requires you to enforce least privilege access, analyze applications to determine which require admin privileges, use flexible policies that allow only trusted applications to run and in specific context.  
      5.4.15  Resource Exhaustion  
        Intentional resource exhaustion is a form of denial of service, or dos, attack. CompTia defines this is When an application continuously allocates additional resources, exhausting machine resources, leading the system to hang or crash. When exploited, resource exhaustion vulnerabilities in apps, software, or system security that hang, crash, or interfere with external programs perform designated tasks properly. Memory leaks can lead to resource exhaustion (see “memory leaks” in this session). However, these attacks can be executed by exhausting other resource subsystems, such as CPU, disk, or network. Countermeasures include Good software development practices (e.g. preventing memory leaks) and limiting what files and apps can be executed on endpoints.  
      5.4.16  Memory Leak  
        A memory leak is the most common issue in memory management. Many modern programming languages (such as C# and Java) don’t allow the programmer to directly allocate or deallocate memory. Therefore, those programming languages are not prone to memory leaks. However, certain older languages, most notably C and C++, give the programmer a great deal of control over memory management. Memory leaks are usually caused by failure to deallocate memory that has been allocated. Countermeasures include A static code analyzer can check to see if all memory allocation commands (malloc, alloc, and others) have a matching deallocation command.  
    5.5  Network Level Attacks  
      5.5.1   Domain Name System (DNS) Attacks  
        The Domain Name System (DNS) is the hierarchical and decentralized naming system used to identify computers reachable through the Internet or other Internet Protocol (IP) networks. The resource records contained in the DNS associate domain names with other forms of information. These are most commonly used to map human-friendly domain names to the numerical IP addresses computers need to locate services and devices using the underlying network protocols, but have been extended over time to perform many other functions as well  
        5.5.1.1   DNS Poisoning  
          DNS spoofing, also referred to as DNS cache poisoning, is a form of computer security hacking in which corrupt Domain Name System data is introduced into the DNS resolver's cache, causing the name server to return an incorrect result record, e.g. an IP address. This results in traffic being diverted to the attacker's computer (or any other computer).  
        5.5.1.2   URL Redirection  
          URL redirection can be abused by attackers for phishing attacks, such as open redirect and covert redirect. "An open redirect is an application that takes a parameter and redirects a user to the parameter value without any validation."[25] "Covert redirect is an application that takes a parameter and redirects a user to the parameter value WITHOUT SUFFICIENT validation."  
        5.5.1.3   Domain Hijacking  
          Domain hijacking or domain theft is the act of changing the registration of a domain name without the permission of its original registrant, or by abuse of privileges on domain hosting and registrar software systems.[1]  
    
          This can be devastating to the original domain name holder, not only financially as they may have derived commercial income from a website hosted at the domain or conducted business through that domain's e-mail accounts,[2] but also in terms of readership and/or audience for non-profit or artistic web addresses. After a successful hijacking, the hijacker can use the domain name to facilitate other illegal activity such as phishing, where a website is replaced by an identical website that records private information such as log-in passwords, spam, or may distribute malware from the perceived "trusted" domain  
      5.5.2   Malicious Code Execution  
        Malicious code, or scripts, don't always have to be traditionally packaged malware. Malicious code can also come in the form of bash, powershell, macros, vba, and even interpreted languages like python running on the victims device.  
      5.5.3   Distributed Denial-of-Service (DDoS)  
        A distributed denial-of-service (DDoS) attack occurs when multiple systems flood the bandwidth or resources of a targeted system, usually one or more web servers.[16] A DDoS attack uses more than one unique IP address or machines, often from thousands of hosts infected with malware.[17][18] A distributed denial of service attack typically involves more than around 3–5 nodes on different networks; fewer nodes may qualify as a DoS attack but is not a DDoS attack.[19][20]  
    
        Multiple machines can generate more attack traffic than one machine, multiple attack machines are harder to turn off than one attack machine, and the behavior of each attack machine can be stealthier, making it harder to track and shut down. Since the incoming traffic flooding the victim originates from different sources, it may be impossible to stop the attack simply by using ingress filtering. It also makes it difficult to distinguish legitimate user traffic from attack traffic when spread across multiple points of origin. As an alternative or augmentation of a DDoS, attacks may involve forging of IP sender addresses (IP address spoofing) further complicating identifying and defeating the attack. These attacker advantages cause challenges for defense mechanisms. For example, merely purchasing more incoming bandwidth than the current volume of the attack might not help, because the attacker might be able to simply add more attack machines. COUNTERMEASURES include IDS, IPS, rate-limiting, firewall ingress/egress filters  
        5.5.3.1   Network Level  
          volume-based attacks targeting flaws in network protocols, often using botnets, using techniques such as UDP, ICMP flooding, or SYN flooding (TCP-based).  
        5.5.3.2   Application Level  
          exploit weaknesses in the application layer (Layer 7) by opening connections and initiating process and transaction requests that consume finite resources like disk space and available memory.  
        5.5.3.3   Operating Technology (OT)  
          Targets the weaknesses of software and hardware devices that control systems in factories, power plants, and other industries, such as IoT devices. Often target weaknesses using the network and application techniques described above.  
      5.5.4   Layer 2 Attacks  
        The data link layer, or layer 2, is the second layer of the seven-layer OSI model of computer networking. This layer is the protocol layer that transfers data between nodes on a network segment across the physical layer.[2] The data link layer provides the functional and procedural means to transfer data between network entities and may also provide the means to detect and possibly correct errors that can occur in the physical layer.  
        5.5.4.1   ARP Poisoning  
          ARP spoofing, ARP cache poisoning, or ARP poison routing, is a technique by which an attacker sends (spoofed) Address Resolution Protocol (ARP) messages onto a local area network. Generally, the aim is to associate the attacker's MAC address with the IP address of another host, such as the default gateway, causing any traffic meant for that IP address to be sent to the attacker instead.  
    
          ARP spoofing may allow an attacker to intercept data frames on a network, modify the traffic, or stop all traffic. Often the attack is used as an opening for other attacks, such as denial of service, man in the middle, or session hijacking attacks.[1]  
    
          The attack can only be used on networks that use ARP, and requires attacker have direct access to the local network segment to be attacked.  
        5.5.4.2   MAC Cloning  
          MAC Cloning can be difficult to detect without additional information about the devices in question. This attack Duplicates the MAC address (hardware address) of a device, allowing attacker to appear as a trusted device.  
        5.5.4.3   MAC Flooding  
          a media access control attack or MAC flooding is a technique employed to compromise the security of network switches. The attack works by forcing legitimate MAC table contents out of the switch and forcing a unicast flooding behavior potentially sending sensitive information to portions of the network where it is not normally intended to go.  
      5.5.5   On-Path Attack (Formerly MitM)  
          The 2022 CompTia Security + exam uses the terminology On-Path Attack to replace what has up to this point been known as man-in-the-middle. This is a cyberattack where the attacker secretly relays and possibly alters the communications between two parties who believe that they are directly communicating with each other, as the attacker has inserted themselves between the two parties.[7] One example of a MITM attack is active eavesdropping, in which the attacker makes independent connections with the victims and relays messages between them to make them believe they are talking directly to each other over a private connection, when in fact the entire conversation is controlled by the attacker.[8] The attacker must be able to intercept all relevant messages passing between the two victims and inject new ones. This is straightforward in many circumstances; for example, an attacker within the reception range of an unencrypted Wi-Fi access point could insert themselves as a man-in-the-middle.[9][10][11] As it aims to circumvent mutual authentication, a MITM attack can succeed only when the attacker impersonates each endpoint sufficiently well to satisfy their expectations. Most cryptographic protocols include some form of endpoint authentication specifically to prevent MITM attacks. For example, TLS can authenticate one or both parties using a mutually trusted certificate authority  
      5.5.6   Wireless Attacks  
        A common countermeasure to wireless and mobile attacks is to disable discovery mode, use a long pin, and use two factor authentication  
        5.5.6.1   Rogue Access Point  
          A rogue access point is a wireless access point that has been installed on a secure network without explicit authorization from a local network administrator,[1] whether added by a well-meaning employee or by a malicious attacker.  
    
          Although it is technically easy for a well-meaning employee to install a "soft access point" or an inexpensive wireless router—perhaps to make access from mobile devices easier—it is likely that they will configure this as "open", or with poor security, and potentially allow access to unauthorized parties.  
    
          If an attacker installs an access point they are able to run various types of vulnerability scanners, and rather than having to be physically inside the organization, can attack remotely—perhaps from a reception area, adjacent building, car park, or with a high gain antenna, even from several miles away.  
        5.5.6.2   RFID Attacks  
          Commonly used in access badge attacks, Vulnerable to several classes of attack, like sniffing (or eavesdropping), spoofing, cloning, replay, relay, and DoS attacks  
        5.5.6.3   NFC Attacks  
          Built on RFID, often used with payment systems. Subject to many of the same vulnerabilities as RFID. This is the touch pay system at bars and grocery store PIN terminals  
        5.5.6.4   Disassociation  
          A type of DoS attack in which the attacker breaks the wireless connection between the victim device and the access point. This can be used to provide a reconnection window to install, or inject, an evil twin.  
        5.5.6.5   Jamming  
          This attack can often be unintentional and is difficult to detect. A DoS attack that prevents other nodes from using the channel to communicate by occupying the channel that they are communicating on.  
        5.5.6.6   Bluesnarfing  
          Bluesnarfing is data theft using Bluetooth. Vulnerable devices are those using bluetooth in public places with device in discoverable mode.  
        5.5.6.7   Bluejacking  
          Bluejacking is used to push unsolicited messages to engage or annoy other nearby Bluetooth through a loophole in Bluetooth messaging options. Bluejacking can also lead to a new technique called bluebugging. Developed a year after bluejacking, creates a backdoor attack before returning control of the phone to its owner.  
        5.5.6.8   Evil Twin  
          The Evil Twin attack involves a malicious fake wireless access point set up to appear as a legitimate, trusted network. These are often found in common areas where a users accepted risk is lowered for a variety of reasons. For example, an airport or cafe.  
```
  

  <a name="social"></a>
## 6. Social Engineering  
    Social engineering is the psychological manipulation of people into performing actions or divulging confidential information. This differs from social engineering within the social sciences, which does not concern the divulging of confidential information. A type of confidence trick for the purpose of information gathering, fraud, or system access, it differs from a traditional "con" in that it is often one of many steps in a more complex fraud scheme.[1]  
    
    It has also been defined as "any act that influences a person to take an action that may or may not be in their best interests."[2]  
    
    An example of social engineering is the use of the "forgot password" function on most websites which require login. An improperly-secured password-recovery system can be used to grant a malicious attacker full access to a user's account, while the original user will lose access to the account.  
    6.1   Social Engineering Principles  
      All social engineering techniques are based on specific attributes of human decision-making known as cognitive biases.[6][7] These biases, sometimes called "bugs in the human hardware,” are exploited in various combinations to create attack techniques, some of which are listed below. The attacks used in social engineering can be used to steal employees' confidential information. The most common type of social engineering happens over the phone. Other examples of social engineering attacks are criminals posing as exterminators, fire marshals and technicians to go unnoticed as they steal company secrets.  
      6.1.1   Authority  
        In social engineering, the attacker may pose as authority to increase the likelihood of adherence from the victim.  
      6.1.2   Intimidation  
        Attacker (potentially disguised) informs or implies that there will be negative consequences if certain actions are not performed. Consequences could include subtle intimidation phrases such as "I'll tell your manager" to much worse.  
      6.1.3   Consensus  
        People will do things that they see other people are doing. For example, in one experiment[which?], one or more confederates would look up into the sky; bystanders would then look up into the sky to see what they were missing. At one point this experiment was aborted, as so many people were looking up that they stopped traffic  
      6.1.4   Scarcity  
        Perceived scarcity will generate demand. The common advertising phrase "while supplies last" capitalizes on a sense of scarcity.  
      6.1.5   Familiarity  
        People are easily persuaded by other people whom they like. Cialdini cites the marketing of Tupperware in what might now be called viral marketing. People were more likely to buy if they liked the person selling it to them. Some of the many biases favoring more attractive people are discussed. See physical attractiveness stereotype.  
      6.1.6   Urgency  
        Linked to scarcity, attackers use urgency as a time-based psychological principle of social engineering. For example, saying offers are available for a "limited time only" encourages sales through a sense of urgency.  
    6.2   Social Engineering Attacks  
      At a high level, two categories of social engineering attacks; physical and virtual.  
      6.2.1   Physical Attacks  
        6.2.1.1   Tailgating  
          Tailgaiting is when an unauthorized individual might follow you in through that open door without badging in themselves. Often times, tailgating is not an accident.  
        6.2.1.2   Dumpster diving  
          Dumpster diving is the act of gathering important details (intelligence) from things that people have thrown out in their trash.Dumpster diving is often legal.  
        6.2.1.3   Shoulder surfing  
          Shoulder surfing is a criminal practice where thieves steal your personal data by spying over your shoulder  
        6.2.1.4   Eliciting information  
          Elicitation is a strategic use of casual conversation to extract information without the arousing suspicion of the target. This form of social engineering can involve complex cover stories and co-conspirators.  
      6.2.2   Virtual Attacks  
        6.2.2.1   Phishing  
          Phishing is a type of social engineering where an attacker sends a fraudulent (e.g., spoofed, fake, or otherwise deceptive) message designed to trick a person into revealing sensitive information to the attacker[1] or to deploy malicious software on the victim's infrastructure like ransomware. Phishing attacks have become increasingly sophisticated and often transparently mirror the site being targeted, allowing the attacker to observe everything while the victim is navigating the site, and transverse any additional security boundaries with the victim.[2] As of 2020, phishing is by far the most common attack performed by cybercriminals, the FBI's Internet Crime Complaint Centre recording over twice as many incidents of phishing than any other type of computer crime.  
        6.2.2.2   Smishing  
          SMS phishing[31] or smishing[32] is conceptually similar to email phishing, except attackers use cell phone text messages to deliver the "bait".[33] Smishing attacks typically invite the user to click a link, call a phone number, or contact an email address provided by the attacker via SMS message. The victim is then invited to provide their private data; often, credentials to other websites or services. Furthermore, due to the nature of mobile browsers, URLs may not be fully displayed; this may make it more difficult to identify an illegitimate logon page.[34] As the mobile phone market is now saturated with smartphones which all have fast internet connectivity, a malicious link sent via SMS can yield the same result as it would if sent via email. Smishing messages may come from telephone numbers that are in a strange or unexpected format.  
        6.2.2.3   Vishing  
          Voice phishing, or vishing,[29] is the use of telephony (often Voice over IP telephony) to conduct phishing attacks. Attackers will dial a large quantity of telephone numbers and play automated recordings - often made using text-to-speech synthesizers - that make false claims of fraudulent activity on the victim's bank accounts or credit cards. The calling phone number will be spoofed to show the real number of the bank or institution impersonated. The victim is then directed to call a number controlled by the attackers, which will either automatically prompt them to enter sensitive information in order to "resolve" the supposed fraud, or connect them to a live person who will attempt to use social engineering to obtain information.[29] Voice phishing capitalizes on the lower awareness among the general public of techniques such as caller ID spoofing and automated dialing, compared to the equivalents for email phishing, and thereby the inherent trust that many people have in voice telephony.  
        6.2.2.4   Spam  
          Spamming is the use of messaging systems to send multiple unsolicited messages (spam) to large numbers of recipients for the purpose of commercial advertising, for the purpose of non-commercial proselytizing, for any prohibited purpose (especially the fraudulent purpose of phishing), or simply repeatedly sending the same message to the same user.  
        6.2.2.5   Spam over instant messaging (SPIM)  
          Messaging spam, sometimes called SPIM,[1][2][3] is a type of spam targeting users of instant messaging (IM) services, SMS, or private messages within websites.  
        6.2.2.6   Spear phishing  
          Spear phishing involves an attacker directly targeting a specific organization or person with tailored phishing communications.[14] This is essentially the creation and sending of emails to a particular person to make the person think the email is legitimate. In contrast to bulk phishing, spear phishing attackers often gather and use personal information about their target to increase their probability of success of the attack.[15][16][17][18] Spear phishing typically targets executives or those that work in financial departments that have access to the organization's sensitive financial data and services. A 2019 study showed that accountancy and audit firms are frequent targets for spear phishing owing to their employees' access to information that could be valuable to criminals.  
        6.2.2.7   Pharming  
          Pharming[a] is a cyberattack intended to redirect a website's traffic to another, fake site by installing a malicious program on the computer.[citation needed] Pharming can be conducted either by changing the hosts file on a victim's computer or by exploitation of a vulnerability in DNS server software. DNS servers are computers responsible for resolving Internet names into their real IP addresses. Compromised DNS servers are sometimes referred to as "poisoned". Pharming requires unprotected access to target a computer, such as altering a customer's home computer, rather than a corporate business server.  
        6.2.2.8   Whaling  
          Whaling refers to spear phishing attacks directed specifically at senior executives and other high-profile targets.[23] The content will be likely crafted to be of interest to the person or role targeted - such as a subpoena or customer complaint.[24]  
    
          CEO fraud is effectively the opposite of whaling; it involves the crafting of spoofed emails purportedly from senior executives with the intention of getting other employees at an organization to perform a specific action, usually the wiring of money to an offshore account.[25] While CEO fraud has a reasonably low success rate, criminals can gain very large sums of money from the few attempts that do succeed. There have been multiple instances of organizations losing tens of millions of dollars to such attacks.  
        6.2.2.9   Prepending  
          Prepending is adding words or phrases like “SAFE” to a malicious file or suggesting topics via social engineering to uncover information of interest.  
        6.2.2.10  Identity fraud  
          Identity fraud is the use of another person's personal information, without authorization, to commit a crime or to deceive or defraud that person or other 3rd party  
        6.2.2.11  Invoice scams  
          Invoice scams involve fake invoices with a goal of receiving money or by prompting a victim to put their credentials into a fake login screen.  
    6.3   Social Engineering Techniques  
      6.3.1   Credential harvesting  
        Credential harvesting is when attackers trying to gain access to your usernames and passwords that might be stored on your local computer. This is often the goal of phishing attempts. Countermeasure include email defense, anti-malware, EDR/XDR solutions that will check URLs and block the scripts often used to execute the attack  
      6.3.2   Hoax  
        A hoax is an Intentional falsehoods coming in a variety of forms ranging from virus hoaxes to fake news. Social media plays a prominent role in hoaxes today  
      6.3.3   Impersonation  
        Impersonation is a form of fraud in which attackers pose as a known or trusted person to dupe the user into sharing sensitive info, transferring money, etc.  
      6.3.4   Watering hole attack  
        A watering hole attack is an attack strategy in which an attacker guesses or observes which websites an organization often uses and infects one or more of them with malware  
      6.3.5   Typosquatting  
        Typosquatting, also known as URL hijacking, is a form of cybersquatting (sitting on sites under someone else’s brand or copyright) targeting users who type an incorrect website address. Typosquatting can often employ a drive-by-download that can infect a device without any user input.  
      6.3.6   Pretexting  
        Pretexting (adj. pretextual) is the act of creating and using an invented scenario (the pretext) to engage a targeted victim in a manner that increases the chance the victim will divulge information or perform actions that would be unlikely in ordinary circumstances.[11] An elaborate lie, it most often involves some prior research or setup and the use of this information for impersonation (e.g., date of birth, Social Security number, last bill amount) to establish legitimacy in the mind of the target.[12] As a background, pretexting can be interpreted as the first evolution of social engineering, and continued to develop as social engineering incorporated current-day technologies. Current and past examples of pretexting demonstrate this development.  
    
        This technique can be used to fool a business into disclosing customer information as well as by private investigators to obtain telephone records, utility records, banking records and other information directly from company service representatives.[13] The information can then be used to establish even greater legitimacy under tougher questioning with a manager, e.g., to make account changes, get specific balances, etc.  
    
        Pretexting can also be used to impersonate co-workers, police, bank, tax authorities, clergy, insurance investigators—or any other individual who could have perceived authority or right-to-know in the mind of the targeted victim. The pretexter must simply prepare answers to questions that might be asked by the victim. In some cases, all that is needed is a voice that sounds authoritative, an earnest tone, and an ability to think on one's feet to create a pretextual scenario.  
    6.4   Influence campaigns  
      An influence campaign is A social engineering attack intended to manipulate the thoughts and minds of large groups of people. These attacks might even include, sometimes as a primary goal, paid advertising.  
      6.4.1   Hybrid warfare  
        Attack using a mixture of conventional and unconventional methods and resources to carry out the campaign  
      6.4.2   Social media  
        May use multiple social platforms leveraging multiple/many individuals to amplify the message, influencing credibility. May involve creating multiple fake accounts to post content and seed the spread.  
    
  <a name="operations"></a>
## 7.  Security Operations  
  ```
    7.1   Red Team  
      Red team members are the offensive arm of security operations. They are internal or external entities dedicated to testing the effectiveness of a security program by emulating the tools and techniques of likely attackers in the most realistic way possible.  
    7.2   Blue Team  
      Blue team members are the defensive backbone of security operations. They are the internal security team that defends against both real attackers and Red Teams.  
    7.3   Purple Team  
      Your security + exam defines purple team members as the process improvement team for security operations. They exist to ensure and maximize the effectiveness of the red and blue teams.  
    7.4   White Team  
      White team members are the judge or referee component to security operations. They are responsible for overseeing an engagement between a red team and blue team.  
    7.5   Security Assessment Techniques  
      7.5.1   Vulnerability Scans  
        A vulnerability scan assesses possible security vulnerabilities in computers, networks, and equipment that can be exploited.  
        7.5.1.1   Intrusive vs. Non-Intrusive  
          Non-intrusive scans are passive and merely report vulnerabilities. They do not cause damage to your system. On the other hand, intrusive scans can cause damage as they try to exploit the vulnerability and should be used in a sandbox and not on your live production system.  
        7.5.1.2   Credentialed vs. Non-Credentialed  
          A credentialed scan is a much more powerful version of the vulnerability scanner. It has higher privileges than a non-credentialed scan. Credentialed scans can help spot vulnerabilities that require privelege, like non-expiring passwords. A non-credentialed scan has lower privileges than a credentialed scan. It will identify vulnerabilities that an attacker would easily find. Non-credentialed scans can find missing patches and protocol vulnerabilities.  
        7.5.1.3   Network Assessment  
          These scans look at computers and devices on your network and help identify weaknesses in their security.  
        7.5.1.4   Application Assessment  
          Before applications are released, coding experts perform regression testing that will check code for deficiencies.  
        7.5.1.5   Web Application Assessment  
          Crawl through a website as if they are a search engine looking for vulnerabilities. Perform and automated check for site/app vulnerabilities, such as cross-site scripting and SQL injection.  
        7.5.1.6   False Positives  
          A false positive is where the scan believes that there is a vulnerability but when physically checked, it is not there. Likewise, a true positive is where the results of the system scan agree with the manual inspection.  
        7.5.1.7   False Negatives  
          A false negative is when there is a vulnerability, but the scanner does not detect it.  
        7.5.1.8   Log Reviews  
          Log review is the process following a vulnerability scan. It is an important step to review the log files/reports that list any potential vulnerabilities.  
        7.5.1.9   CVE/CVSS  
          Common vulnerability scoring system, or CVSS, is the overall score assigned to a vulnerability. It indicates severity and is used by many vulnerability scanning tools. Common vulnerabilities and exposures, or CVE, is simply a list of all publicly disclosed vulnerabilities that includes the CVE ID, a description, dates, and comments. The CVSS score is not reported in the CVE listing – you must use the National Vulnerability Database (NVD) to find assigned CVSS scores. The CVE list, however, feeds into the NVD.  
        7.5.1.10  Configuration Review  
          Configuration compliance scanners and desired state configuration in PowerShell ensure that no deviations are made to the security configuration of a system.  
        7.5.1.11  SAST vs DAST  
          Static application security testing and dynamic application security testing are two different methodologies. You will need to know the difference as this is certain to be on your security + exam. The main difference between DAST and SAST lies in how each performs the security testing. SAST scans the application code at rest to discover faulty code posing a security threat, while DAST tests the running application and has no access to its source code.  
      7.5.2   Security Orchestration, Automation, and Response (SOAR)  
        SOAR provides centralized alert and response automation with threat-specific playbooks. Response may be fully automated or single-click. Often provided in conjunction with SIEM solutions. Further, SOAR Integrates your security processes and tooling in a central location. Response automation, using machine learning and artificial intelligence These make it faster than humans in identifying and responding to true incidents. Reduces MTTD and accelerates response Uses playbooks that define an incident and the action taken. Over time, should produce faster alerting and response for the SOC team.  
      7.5.3   Threat Hunting  
        A dynamic process of seeking out cybersecurity threats inside your network from attackers and malware threats. For the exam, Know the difference between UEBA, machine learning, AI, and deep learning  
        7.5.3.1   Advisories and Bulletins  
          Advisories and security bulletins provide good advice on how to keep your company safe. The advisories tend to be released government-funded agencies. Bulletins tend to be released by vendors or private companies.  
        7.5.3.2   Intelligence Fusion  
          A combination of industry and government. Fusion centers in the US and abroad play an important role in countering cyber threats, attacks, and crime through gathering, analyzing, and sharing threat information.  
        7.5.3.3   Threat Feeds  
          Also known as threat intelligence feeds, these enable organizations to stay informed about indicators of compromise (IoCs) related to various threats that could adversely affect the network.  
        7.5.3.4   Maneuver  
           A cybersecurity maneuver refers to a company's efforts to defend itself by disguising its systems, thereby making it difficult for an attacker to successfully infiltrate.  
      7.5.4   Syslog/SIEM (Security Information Event Management)  
        7.5.4.1   Security Monitoring  
          Real-time protection and event monitoring system that correlates the security events from multiple resources, identifies a breach, and helps the security team to prevent the breach. UEBA, AI, ML, and threat intel feeds all factor in to security monitoring.  
        7.5.4.2   Data Inputs  
          The SIEM system collects a massive amount of data from various sources. This may include network devices, IDM, MDM, CASB, XDR, and more.  
        7.5.4.3   Packet Capture  
          Can capture packets and analyze them to identify threats as soon as they reach your network, providing immediate alert to security team if desired.  
        7.5.4.4   Event Reporting  
          A SIEM typically includes dashboard and collects reports that can be reviewed regularly to ensure that the policies have been enforced and that the environment is compliant. Also highlight whether the SIEM system is effective and working properly. False positives may arise because the wrong input filters are being used or the wrong hosts monitored.  
        7.5.4.5   User Entity Behavior Analysis (UEBA)  
          This is based on the interaction of a user that focuses on their identity and the data that they would normally access on a normal day. It tracks the devices that the user normally uses and the servers that they normally visit.  
        7.5.4.6   Log Aggregation  
          Can correlate and aggregate events so that duplicates are filtered and a better understanding network events is achieved to help identify potential attacks.  
        7.5.4.7   Log Collectors  
          SIEM has built-in log collector tooling that can collect information from both the syslog server and multiple other servers. An agent is placed on the device that can collect log information, parse and restructure data, and pass to SIEM for aggregation. Ingestion may be via an egent, syslog, or API.  
        7.5.4.8   Sentiment Analysis  
          Artificial intelligence and machine learning to identify attacks. Cybersecurity sentiment analysis can monitor articles on social media, look at the text and analyze the sentiment behind the articles. Over time, can identify a users' attitudes to different aspects of cybersecurity.  
    7.6   Penetration Testing Techniques  
      7.6.1   Recon  
        Generally refers to one of the pre-attack phases; tasks performed before doing the actual attack. Often the collection of information leading to an expansion of the attack surface and therefor a higher success rate of finding vulnerabilities to exploit.  
        7.6.1.1   Passive vs Active  
          Passive reconnaissance one is not interacting directly with the target and as such, the target has no way of knowing, recording, or logging activity. On the other hand, Active reconnaissance interacts directly with the target in some way and as such, the target may discover, record, or log these activities.  
        7.6.1.2   Drones  
          Can be leveraged in multiple ways for passive reconnaissance, from assessing physical security to gathering wireless network information.  
        7.6.1.3   Footprinting  
          Footprinting is an ethical hacking technique used to gather as much data as possible about a specific targeted computer system, infrastructure and networks to identify opportunities to penetrate them. Unlike some other recon techniques, footprinting can be both active and passive. Active footprinting includes; nmap, extracting DNS info, tracert analysis, and pinging. Passive footprinting includes; browsing target website, google hacking, WHOIS lookups, and viewing social media profiles.  
        7.6.1.4   OSINT  
          Much of this information in the open source can be categorized as open-source intelligence or OSINT. The data that you can gather through these open sources is extensive. OSINT  
        7.6.1.5   War Driving  
          Gathering wireless network information while driving around the streets of the city.  
        7.6.1.6   War Flying  
          Combines war driving with a drone and simply float above all of these organizations to gather wireless details. Enables accumulation of information like SSID or wireless network names, and encryption status of these networks.  
      7.6.2   Known Environment (White Box)  
        penetration tester is given a map of target systems and networks. They go into the test with substantial/full information of the target systems and networks.  
      7.6.3   Unknown Environment (Black Box)  
        penetration tester knows nothing about target systems and networks. They go into the test completely blind and build out the database of everything they find as they go.  
      7.6.4   Partially Known Environment (Gray Box)  
        limited information is shared with the tester, sometimes in the form of login credentials. Simulate the level of knowledge that a hacker with long-term access to a system would achieve through research and system footprinting.  
      7.6.5   Rules of Engagement  
        Rules of engagement define the purpose of the test, and what the scope will be for the people who are performing this test on the network. They ensure everyone will be aware of what systems will be considered, date and time, and any constraints all should be aware of.  
      7.6.6   Lateral Movement  
        Gaining access to an initial system, then moving to other devices on the inside of the network.  
      7.6.7   Privelege Escelation  
        A security hole created when code is executed with higher privileges than those of the user running it. Generally, a higher-level account, but in some cases, it is a horizontal privilege escalation where a user gains access to another users' resources.  
      7.6.8   Persistence  
        in the context of penetration testing refers to the testers ability to achieve a persistent presence in the exploited system— long enough for a bad actor to gain in-depth access. Enabling the ability to reconnect to the compromised host and use it as a remote access tool.  
      7.6.9   Pivoting  
        Also known as island hopping, a compromised system is used to attack another system on the same network following the initial exploitation. If the compromise is introduced at a different time than the attack, then it is said to involve persistence.  
      7.6.10  Cleanup  
        The final stage of a penetration test, in which all work done during the testing process is cleaned up / removed.  
      7.6.11  Bug Bounties  
        A monetary reward given to ethical hackers for successfully discovering and reporting a vulnerability or bug to the application's developer. Bug bounty programs allow companies to leverage the hacker community to improve their systems’ security posture over time continuously 
        ```
