


| 🎥 Watch [SOCURITY](https://www.youtube.com/@Socurity) | 📖 Read [GRC](https://orskoven.github.io/GRC/) | 📖 Read [Software Security](https://github.com/orskoven/Software-Security-by-Socurity/blob/main/README.md) | 📖 Read [Mobile Device Security](https://creators.spotify.com/pod/profile/simon-rskov/episodes/AI--NLP-Event-Stock-Prediction-Data-Cleaning-e2tiptb)  | 🗨️ [Podcast](https://creators.spotify.com/pod/profile/simon-rskov/episodes/AI--NLP-Event-Stock-Prediction-Data-Cleaning-e2tiptb) 




## [Privacy By Design](https://en.wikipedia.org/wiki/Privacy_by_design)

"Privacy by design calls for privacy to be taken into account throughout the whole engineering process. " - [wikipedia ](https://en.wikipedia.org/wiki/Privacy_by_design)

Characterised as value sensitive design, originating from human values. 

Historic challenges (since 1995): 
 - Network Infrastructure scaling
 - Priotorizing coporate interests over consumer's ineterests
 - insufficient emphasis on minmizing data collection (sooner made feasible with
[Privacy-enhancing technologies](https://en.wikipedia.org/wiki/Privacy-enhancing_technologies))

### [Privacy-enhancing technologies](https://en.wikipedia.org/wiki/Privacy-enhancing_technologies)


What:
  - Minimizes personal data use
  - Maximise data security
  - Empower Individuals
  - Enforces right to 
[Informational self-determination](https://en.wikipedia.org/wiki/Informational_self-determination)

How:
  - use pseudonyms or anonymous data credentials to provide anonymity
  - achieve informed consent about giving personal data to online service providers and merchants

### [Soft Privacy Technologies](https://en.wikipedia.org/wiki/Soft_privacy_technologies)

### [Hard privacy technologies](https://en.wikipedia.org/wiki/Hard_privacy_technologies)

  - [Mix Networks](https://en.wikipedia.org/wiki/Mix_network)
  - [Dining Cryptographers Problem](https://en.wikipedia.org/wiki/Dining_cryptographers_problem)
  - [The Integrated Services Digital Network (ISDN)](https://en.wikipedia.org/wiki/ISDN)
  - [Attacks against anonymous communications](https://en.wikipedia.org/wiki/Traffic_analysis)


## Privacy By Design From Lecture 

- Proactive not reactive
- Lead with privacy as the default setting
- Embed Privacy into design
- Retain full functionality (positive-sum, not zero-sum)
- Ensure end-2-end security
- Maintain visibility and transparency
- Respect user privacy (user-centric)

In general, privacy is should be business and user centric, hence it need to be planned. 

### Case Smart Meters 

Smart Devices that measures the household consumption of energy (power / heat ) have following requirements: 

Billing integrity
Aggregate statistics availabiltiy 
Fraudulent actions must be detected

Privacy Risks (Class Exercise): 
Sensitive Household information could be leaked / discloud given billing information is required from system requirements
 - Bahvioral patterns can be analysed from leaked information
   This could invouluntary shared with / bought by sellers of housing equipment to target the household.
 - Financial Status of household could be sampled
 - Consumption patterns could be analysed to derive information regarding household attributes (household size, bedtime, dinner time, equipment numbers, type of equipment, effeciency of equipment, age of equipment): These information are senstive to household and could be exploited for manipultation of the customer.
 - Such information should be carefully protected by security measures.
 - Speculation in home invasions / burglers kidnapping children or stealing from elderly people.

### Case Sugar Beats

Danish sugar beet farmers auction: 

Farmers bit on contracts to produce sugar beets (online).


Privacy Risk: 

[Farmers bit size and patterns reveals farmer economy.](https://csrc.nist.gov/csrc/media/events/meeting-on-privacy-enhancing-cryptography/documents/toft.pdf)

### [OWASP top 10 privacy Risks](https://owasp.org/www-project-top-10-privacy-risks/)

2021  2014  Title 
 P1    1     Web Application Vulnerabilities 
 P2    2     Operator-sided Data Leakage 
 P3    3     Insufficient Data Breach Response 
 P4    New   Consent on Everything 
 P5    5     Non-transparent Policies, Terms and Conditions 
 P6    4     Insufficient Deletion of User Data 
 P7    New   Insufficient Data Quality
 P8    9     Missing or Insufficient Session Expiration 
 P9    13    Inability of Users to Access and Modify Data 
 P10   6     Collection of Data Not Required for the User-Consented Purpose

 ### 3 Pillars of Software Security

- Risk Management ( IT Governance & Threat Ranking)
- Touchpoints ( Code Review, Threat Modeling, Penetration Risk, Risk-based security tests, abuse case, security req., security op.)
- Knowledge (gathering, encapsulating, sharing security knowledge) - Principles - Guidelines - Rules - Vulnerabilities


### Defect, Flaw, Bug

##### Defect
Implementation + Design vuln.
Dormant

##### Flaw
- DESIGN ISSUE
Problem at deeper level usually design

##### Bug
- CODE ISSUE
Implementation level


### Exercise: Think about Flaws

Five Flaws 
- web application vulnerabilities
  3rd party open source dev tools (npm, PyPI)
  This is being heavily exploited by Advanced Persitent Threats
  [Espionage in Open source malware - Lazarous Group](https://www.sonatype.com/blog/sonatype-uncovers-global-espionage-campaign-in-open-source-ecosystems?_gl=1*2ni3d9*_up*MQ..*_ga*ODg1OTA4NjM0LjE3NTgyOTQ1MDc.*_ga_2TMM6KZPXQ*czE3NTgyOTQ1MDYkbzEkZzAkdDE3NTgyOTQ1MDYkajYwJGwwJGgw*_ga_3W70E95Z6Q*czE3NTgyOTQ1MDYkbzEkZzAkdDE3NTgyOTQ1MDYkajYwJGwwJGgw*_ga_08HT33J01V*czE3NTgyOTQ1MDYkbzEkZzAkdDE3NTgyOTQ1MDYkajYwJGwwJGgw)
- No Audit Features
- No Testing
- No Session Management
- No input validation / sanitization
[input injection  The cyber threat actors targeted the /mifs/rs/api/v2/ endpoint with HTTP GET requests and used the ?format= parameter to send malicious remote commands,” [CISA](https://www.cisa.gov/news-events/analysis-reports/ar25-261a) 
- Not correctly implenmented design patterns
- to many dependecies in classes & methodes /functions 
- no layered defence in depth
- no proper exeption handling
- no logs for audit
- no prober privleged process handling
- 

[Supply Chain Breaches 
](https://www.sonatype.com/resources/vulnerability-timeline)

###### Lazarous Group / Hidden Cobra ( NORTH KOREA-backed)

```json
Attack Vector:  Embedding Malware into popular Open Source tools registries[1]
Attack Surface:  NPM (node package manager) & PyPi (python package installer)
```
[1](https://www.sonatype.com/blog/sonatype-uncovers-global-espionage-campaign-in-open-source-ecosystems?_gl=1*gkaze*_up*MQ..*_ga*ODg1OTA4NjM0LjE3NTgyOTQ1MDc.*_ga_2TMM6KZPXQ*czE3NTgyOTQ1MDYkbzEkZzAkdDE3NTgyOTQ1MDYkajYwJGwwJGgw*_ga_3W70E95Z6Q*czE3NTgyOTQ1MDYkbzEkZzAkdDE3NTgyOTQ1MDYkajYwJGwwJGgw*_ga_08HT33J01V*czE3NTgyOTQ1MDYkbzEkZzAkdDE3NTgyOTQ1MDYkajYwJGwwJGgw)


### Flaws VS. Bugs

Security Design Flaws:
- are spotted with threat modelling/ secure architecture reviews.

Security Coding Bugs:
- Following secure coding practices lead to better security.


## [Threat Modelling](https://www.threatmodelingmanifesto.org)

- Continous process
- As early as possible in design process
- #1 Rank by [NIST](https://www.nist.gov/itl/executive-order-improving-nations-cybersecurity/recommended-minimum-standard-vendor-or-developer) in sofware verification process
- Perform threat modelling more than once:
   1. When developing new capabilities
   2. capturing new threats
   3. improve modelling
  
    [Threats] <identify-> [Requirements] compliance--><- [Mitigations]
        |__________________<-->________________|


<img width="614" height="249" alt="Screenshot 2025-09-20 at 07 05 07" src="https://github.com/user-attachments/assets/b4b26ca4-4751-463e-9fd4-cd35d7431cb3" />

## Threat modelling Strategies

1. Brainstorm
2. Focus on assets
3. Focus on attackers
4. Focus on software


### Asset-Focused Threat Modelling

"Providing a sufficient level of security for our assets of interest against certain classes of threats" 

### Data Assets 
 - Secrets - API keys, encryption keys, passwords
 - Restricted - Customer data, Customers PII
 - Confidential, Internal - SW architectural diagrams, emails, production data 
 - Public - app features, press releases, whitepapers

### Persona non Grata (PnG) threat modeling

- Using Personas attacker model to identify potential attackers
- Looking for motivation, skills, background and perspective in attacker personas.

#### Example: 

```json
Lorrin Smith Bates - Insider Threat
Personal Gain : Intense dislike of her employer
Holds BS in computer science
3 years as database admin.

```


## What can "real" attackers do (Knowledge in 3-Pillar)? 

- Identify the likelihood and impact of attacks
- Take effective steps to mitigate attacks
- Describe techniques of attackers
- Similarity to software design patterns
- Applies Problem - Solution paradigm but destructive
- COMMON ATTACK PATTERN ENUMERATION AND CLASSIFICATION ([CAPEC](https://capec.mitre.org))

### Attack Patterns: 

Components : 

```json
{
- Pattern name, classification
- attack prerequisites
- description and chain of actions taken
- related vulnerabilities, weaknesses
- methode of attack ( malicious data, entry, protocol corruption..)
- attack motivation: what is the attacker trying to achieve?
- attacker skill of knowledge required to execute such an attack
- resources required (IP addresses, tools, time..)
- solution and mitigations
- context description (platform, OS, language..)
}
```
###### [CVE](https://www.cve.org)
###### [CWE](https://cwe.mitre.org/data/definitions/89.html)
###### [ATT&CK](https://attack.mitre.org)
###### [D3FEND](https://d3fend.mitre.org)


### Exercise 1: CAPEC Attack Patterns FUZZING ATTACKS

a ) What are they? 
b ) What kind of tools or software are used to conduct these kinds of attacks?
c ) How are they being mitigated? 

[CAPEC-28: Fuzzing](https://capec.mitre.org/data/definitions/28.html)

```json
Adversary/Attacker : Tries to perform Reconasaince and obtain knwoledge about a system to gain insights on system vulnerabilities.
Methode of attack: leverages black box testing techniques and analyse assumption about the systems.
Likelihood: High
Typical severiy: Medium
Mechanisms of Attack : Employ Probabilistic Techniques
Execution Flow: {
 Explpre: Network sniffing ( WIRESHARK ), Monitor API execution (KTRACE, STRACE, APISpy or other debugging tools., Observe inputs using web inspection tools (OWASP's WebScarab, Paros, TamperData, TamperIE, etc.)
Indicators: a lot of invalid data is fed to the system (short period of time from same IP)
Mitigations: Test software for no unintended side effects. Ensure no assumptions about the validity of the data are made.
USE fuzz testing during software QA proces to uncover any surprises, uncover any assumption or unexpected behavior.
Example instance: "A fuzz test reveals that when data length for a particular field exceeds certain length, the input validation filter fails and lets the user data in unfiltered. This provides an attacker with an injection vector to deliver the malicious payload into the system." [CAPEC](https://capec.mitre.org/data/definitions/28.html)
```

### Exercise 2 : [CWE knowledge base](https://cwe.mitre.org/top25/archive/2023/2023_top25_list.html)

a) Look for the weakness referring to path traversal, which ranks number 8, and have a look at the information provided.

[CWE-22: Improper Limitation of a Pathname to a Restricted Directory ('Path Traversal')](https://cwe.mitre.org/data/definitions/22.html)

```json
{
classification: Path Traversal  
attack prerequisites: "Access to web application and input fields
chain of actions: By using special elements such as ".." and "/" separators, attackers can escape outside of the restricted location to access files or directories that are elsewhere on the system. ommon special elements is the "../" sequence"
related vulnerabilities: directory traversal
methode of attack: injection 
attack motivation: altering / stealing information / hijacking / destroctive / espionage / data leak / gaining deeper access 
attacker skill:
resources required:
solution and mitigations:  "Use an "accept known good" input validation strategy, i.e., use a list of acceptable inputs that strictly conform to specifications. Reject any input that does not strictly conform to specifications, or transform it into something that does." -  "However, denylists can be useful for detecting potential attacks or determining which inputs are so malformed that they should be rejected outright." - "If feasible, only allow a single "." character in the filename to avoid weaknesses such as CWE-23, and exclude directory separators such as "/" to avoid CWE-36. Use a list of allowable file extensions, which will help to avoid CWE-434.
" "Do not rely exclusively on a filtering mechanism that removes potentially dangerous characters. This is equivalent to a denylist, which may be incomplete (CWE-184). For example, filtering "/" is insufficient protection if the filesystem also supports the use of "\" as a directory separator. Another possible error could occur when the filtering is applied in a way that still produces dangerous data (CWE-182). For example, if "../" sequences are removed from the ".../...//" string in a sequential fashion, two instances of "../" would be removed from the original string, but the remaining characters would still form the "../" string."
context description:
Detection methodes : Automated Static Analysis, Manual Static Analysis, Automated Static Analysis - Binary or Bytecode,  
}
```

b) List some of the mitigation mechanisms suggested.
c) How can this vulnerability be detected?


### Exercise 3: CVE knowledge base 

Think about your own dependencies in your daily life and look at the software you
depend on. How many vulnerabilities and CVEs are for that? Find flaws or problems on
that, even if they were in older versions of the software and there are none (so far ;) )
in the version you’re currently running.


## Software Focused threat modeling

- Focuses on the system
- Build & Deployment of software is in the scope
- Modeling, architecture, UML diagrams, APIs to find threats

1. Data-Flow Diagram
2. Identify Threats
3. Adress Threats
4. Validation

## [DFDS](https://www.youtube.com/watch?v=lXTwrAWEzGY)

watch my youtube video with +2,2k views about[ Data flow diagrams](https://www.youtube.com/watch?v=lXTwrAWEzGY)
<img width="379" height="249" alt="Screenshot 2025-09-20 at 16 24 30" src="https://github.com/user-attachments/assets/0b627450-bf54-4ac0-bdb3-9dadd106e179" />
<img width="691" height="295" alt="Screenshot 2025-09-20 at 16 24 42" src="https://github.com/user-attachments/assets/17456f67-a05b-482e-8a2e-9a9041610be6" />
<img width="458" height="326" alt="Screenshot 2025-09-20 at 16 25 32" src="https://github.com/user-attachments/assets/ee51b777-d8c7-4320-a181-fa0d579c289b" />
<img width="423" height="184" alt="Screenshot 2025-09-20 at 16 25 38" src="https://github.com/user-attachments/assets/e003c79b-ca16-4918-a923-857613e4f540" />

Circle 


### Verizon Breach Report 2019

Trending 26% stolen records and 40% stolen records. 
Why? 
Small security budget -> poor security. 


Today:
Security is currently being more priotorized. 
Types of initiatives: 
- Network Perimeter (firewalls)
- Enterprise Security (blocking malware and not allowing admin rights for most users)
- physical security(badgning in and out of secure areas)

###### But we still face issues in the software stack. 

BIOS vs. UEFI Boot 

UEFI has been configured to control malware infection by checksum in the boot process.


### [Exploit-Db](https://www.exploit-db.com)

🔺Understand the risk of poorly trained developers in security!

Code is being exploited in many different ways. 

🔺C is fast but not secure compared to other programming language. 

✔️ Java - Secure - Scripting since JVM is a software program that runs the Java code makes it more secure.

Govern is important for software security - NIS2 -.

### Attack Vectors

1. Login username and password combination.

   - Software is build for OSINT combination for input about victim, animals, dates, names, children... to guess passwords

3. Webserver vulnerabilties / not patched
   - [exploitdb](https://www.exploit-db.com)
5. Database vulnerabitlities / not patched
6. OS system vulnerabilities / not patched
7. Third-party components ...
8.  List goes on

- System security only as strong as the weakest link.

### [MOVEit](https://en.wikipedia.org/wiki/2023_MOVEit_data_breach)

[CVE](https://nvd.nist.gov/vuln/detail/CVE-2023-34362)
[CWE-89](https://cwe.mitre.org/data/definitions/89.html): Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') 
MOVEit is a file transfer platform made by Progress Software Corporation. The platform is used by thousands of governments, financial institutions and other public and private sector bodies all around the world to send and receive information.[emisoft](https://www.emsisoft.com/en/blog/44123/unpacking-the-moveit-breach-statistics-and-analysis/)

```json
{
  Type: Zero Day Vulnerability
  CVE : CVE-2023-34362 [4]
  Attack Vectors: SQL injection
  Attacker : Russian-Affiliated Cyber Gang [Cl0p] [1]
  Disclosed by:[Mandiant] [2]
  Exploit methodes: Attacks conducted through Web shell LEMURLOOT, which impersonates legitimate ASP.NET files and can extract Microsoft Azure Storage Blob data. - wikipedia
   Impact: more than 2,773  organizations & 95,788,491 individuals were known to have been impacted as at October 25, 2023, with more than 80 percent of those organizations being US-based. [emisoft] [3]
Impacted individual $:  { Maximus: 11.3 , Welltok 10 million, Delta Dental of California and affiliates 6,9 million  }
Impacted Sectors : { education (39.1 percent), health (20.1 percent), and finance and professional services (13.3 percent) }
COST: $165 USD avarage cost per record | TOTAL $15,805,101,015

}
```
 - [Cl0p](https://en.wikipedia.org/wiki/Clop_(cyber_gang))
 - [Emsisoft](https://www.emsisoft.com/en/blog/44123/unpacking-the-moveit-breach-statistics-and-analysis/)
 - [Mandiant](https://en.wikipedia.org/wiki/Mandiant)
 - [CVE](https://nvd.nist.gov/vuln/detail/CVE-2023-34362)


### Privacy By Design

Schroeder Economy of mechanisms

Auguste Kerckhoff's principle

- "Security of a system should not depend on the secrecy of its protection mechanisms"

#### 1.  Least Common Mechanism / Compartmentalisation

- Limit shared resources to a minimum.
- Isolated groups with limited and controlled means of information exchange.


#### 2. Minimum Exposure 
- Reduce external interfaces to a minimum
- Limit the amount of information given away
- Minimize the window of opportunity for an adversary, e.g. limiting time for availability of attack
    
- Hijack private email is easy
- Session hijacking / Session Copying of credentials stored in the browser ( library browsers are vulnerable )
- Risk Acceptance -> we cannot prevent users from acceptable usage and avoid users from ease of use since this will be tempting to circumvent in an "unsecure" unacceptable way. 


#### 3. Least Privilege

- Singleton connections for Database connection.


#### 4. Minimum Trust 

- Zero Trust


#### 5. Secure, Fail-Safe Defaults

- failing securely


#### 6. Complete Mediation

- Defence in Depth
- Monitored and Controlled Access to resources
- Check Priviledges for every access
- One way paths

Example: 
[Fort Knox
](https://da.wikipedia.org/wiki/Fort_Knox_(gulddepot))

#### [MAC](https://en.wikipedia.org/wiki/Mandatory_access_control) - Mandatory Access Control

#### 7. No Single Point of Failure

- Seperation of Privileges


#### 8. Usability

- Psychological acceptability

#### 9. Promoting Privacy

- Consider all aspects of users' data in context


### 

