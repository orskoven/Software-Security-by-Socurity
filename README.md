# Software Security by Socurity


##### 🎥 Watch [SOCURITY](https://www.youtube.com/@Socurity)
##### 📖 Read [GRC](https://orskoven.github.io/GRC/)
##### 📖 Read [Software Security](https://github.com/orskoven/Software-Security-by-Socurity/blob/main/README.md)
##### 📖 Read [Mobile Device Security](https://creators.spotify.com/pod/profile/simon-rskov/episodes/AI--NLP-Event-Stock-Prediction-Data-Cleaning-e2tiptb) 
##### 🗨️ [Podcast](https://creators.spotify.com/pod/profile/simon-rskov/episodes/AI--NLP-Event-Stock-Prediction-Data-Cleaning-e2tiptb) 



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

MOVEit is a file transfer platform made by Progress Software Corporation. The platform is used by thousands of governments, financial institutions and other public and private sector bodies all around the world to send and receive information.[emisoft](https://www.emsisoft.com/en/blog/44123/unpacking-the-moveit-breach-statistics-and-analysis/)

```json
{
  Type: Zero Day Vulnerability
  Attack Vectors: SQL injection
  Attacker : Russian-Affiliated Cyber Gang [Cl0p] [1]
  Disclosed by:[Mandiant] [2]
  Exploit methodes: Attacks conducted through Web shell LEMURLOOT, which impersonates legitimate ASP.NET files and can extract Microsoft Azure Storage Blob data. - wikipedia
   Impact: more than 2,773  organizations & 95,788,491 individuals were known to have been impacted as at October 25, 2023, with more than 80 percent of those organizations being US-based. [emisoft] [3]
Impacted individual:  { Maximus: 11.3 , Welltok 10 million, Delta Dental of California and affiliates } 

}
```
 - [1][Cl0p](https://en.wikipedia.org/wiki/Clop_(cyber_gang))
 - [2][emisoft](https://www.emsisoft.com/en/blog/44123/unpacking-the-moveit-breach-statistics-and-analysis/)
 - [3][mandiant](https://en.wikipedia.org/wiki/Mandiant)


