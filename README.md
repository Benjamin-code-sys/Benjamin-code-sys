# Hello, I'm Benjamin Kipsoi
<a href="https://www.linkedin.com/in/benjamin-kibet-red-teamer18?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BSn83sXorQsK6Dd3QzmH47A%3D%3D"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>

Hello i am Benjamin Kibet Kipsoi, an aspiring cybersecurity professional with strong self-taught and hands-on skills in networking,
penetration testing, malware analysis, and red teaming. Passionate about applying knowledge in
real-world environments and eager to gain practical experience through an internship or entry-level
opportunity.

## Objective

My objective and goal is to continuously enhance my offensive cybersecurity skills, uncover system vulnerabilities, and simulate real-world attack scenarios to help organizations strengthen their security posture. Through this blog, I aim to share practical insights, documented projects, and walkthroughs of penetration tests, providing value to both aspiring cybersecurity professionals and industry peers while showcasing my expertise and ongoing commitment to ethical hacking and security research

## Skills

The items listed here represent just a fraction of my custom-coded offensive security portfolio, spanning more than 50 advanced builds.
They demonstrate hands-on expertise across the entire attack chain—from initial access to impact and beyond.
I hope this curated sample helps you understand the dedication and craft behind my projects.

### 1. Initial Compromise (Delivery)
The following projects listed below showcase just five of the many advanced ways attackers can deliver malicious payloads onto a targets system that are fully undetectable by the current AV engines as of today  
Investigate my custom ways and codes i've provided by following the link to my github repos highlighted below

| Skill                                                                   | Proof-Of-Concept &nbsp;Projects                                 |
|-------------------------------------------------------------------------|----------------------------------------------------|
| 1.&nbsp; Delivery using FUD obfuscated meterpreter payload with Early Bird technique (Windows)                  | <a href="https://github.com/Benjamin-code-sys/Bypassing-AV/tree/main/EarlyBird">EarlyBird Technique</a>     |
| 2.&nbsp; Initial compromise using Asynchronous Procudure Call Injection (Windows)              | <a href="https://github.com/Benjamin-code-sys/Bypassing-AV/tree/main/APC-Injection">APC-Injection</a>     |
| 3.&nbsp; Stand-Alone DLLs With FUD Injecting Trojans (Windows)                   | <a href="https://github.com/Benjamin-code-sys/DLL-Injection">Obfuscated DLL Injection</a>                                                   |
| 4.&nbsp; Initial compromise using Map-View Code injection with embeded obfuscated payload  | <a href="https://github.com/Benjamin-code-sys/Bypassing-AV/tree/main/Map-View-Code-Injection">Map-View Code Injection</a>                                                 |
| 5.&nbsp; Initial compromise by leveraging Heavens-Gate technique             | <a href="https://github.com/Benjamin-code-sys/Bypassing-AV/tree/main/Heaven-Gate%20Technique">Heaven-Gate Technique</a>                                                    |

### 2. Post-Compromise Enumeration (Local)  
Upon gaining an initial foothold on our targets system it is imperitive that we perfom some enumeration to understand the enviroment better. This we'll help us get organised and find potential attack vectors and privilege escalation paths.  
Manual enumeration is the recommended way for thorough and accurate information gathering, but since in a red team engagement we are often limited by time constrains we'll have to rely on automated tools. 

| Skill                                                                   | Proof-Of-Concept &nbsp;Projects                                 |
|-------------------------------------------------------------------------|----------------------------------------------------|
| 1.&nbsp; Local Enumeration using undetectable automated tool (Windows)              | <a href="https://github.com/Benjamin-code-sys/Enumeration/tree/main/WinPEAS">Obfuscated WinPEAS</a>     |

| Skill                                                                   | Proof-Of-Concept &nbsp;Projects                                 |
|-------------------------------------------------------------------------|----------------------------------------------------|
| 1.&nbsp; Local non-admin Persistence using Custom methods (Windows)              | <a href="https://github.com/Benjamin-code-sys/Local-Persistence/tree/main/UnPrivileged-Persistence/COM-Hijacking">COM Hijacking</a>     |
                                            

## Tools
Throughout my red teaming and offensive security journey, I’ve worked extensively with a wide range of tools and frameworks that support every stage of an engagement — from reconnaissance and vulnerability assessment to exploitation, post-exploitation, and command & control operations. Below is a categorized overview of some of the core tools I rely on to simulate real-world attack scenarios and assess organizational security postures effectively.

### Network Scanning
<div>
  <a href="https://nmap.org"><img src="https://img.shields.io/badge/-Nmap-4682B4?&style=for-the-badge&logo=nmap&logoColor=white" alt="Nmap" /></a>
  <a href="https://github.com/robertdavidgraham/masscan"><img src="https://img.shields.io/badge/-Masscan-FF6A00?&style=for-the-badge&logo=masscan&logoColor=white" alt="Masscan" /></a>
  <a href="https://zmap.io/"><img src="https://img.shields.io/badge/-ZMap-00ADEF?&style=for-the-badge&logo=zmap&logoColor=white" alt="ZMap" /></a>
  <a href="https://angryip.org/"><img src="https://img.shields.io/badge/-Angry%20IP%20Scanner-1F8ACB?&style=for-the-badge&logo=angryipscanner&logoColor=white" alt="Angry IP Scanner" /></a>
  <a href="https://github.com/netdiscover/netdiscover"><img src="https://img.shields.io/badge/-Netdiscover-2F8F2F?&style=for-the-badge&logo=linux&logoColor=white" alt="Netdiscover" /></a>
  <a href="https://nmap.org/ncat/"><img src="https://img.shields.io/badge/-Netcat-555555?&style=for-the-badge&logo=gnuplot&logoColor=white" alt="Netcat" /></a>
</div>

### Vulnerability Scanning

<div>
  <a href="https://www.tenable.com/products/nessus"><img src="https://img.shields.io/badge/-Nessus-B22222?&style=for-the-badge&logo=tenable&logoColor=white" alt="Nessus" /></a>
  <a href="https://www.rapid7.com/products/nexpose/"><img src="https://img.shields.io/badge/-Nexpose-FF4500?&style=for-the-badge&logo=rapid7&logoColor=white" alt="Nexpose" /></a>
  <a href="https://www.qualys.com/"><img src="https://img.shields.io/badge/-Qualys-1E90FF?&style=for-the-badge&logo=qualys&logoColor=white" alt="Qualys" /></a>
  <a href="https://cirt.net/Nikto2"><img src="https://img.shields.io/badge/-Nikto-8A2BE2?&style=for-the-badge&logo=nikto&logoColor=white" alt="Nikto" /></a>
  <a href="https://www.openvas.org/"><img src="https://img.shields.io/badge/-VulnScan-556B2F?&style=for-the-badge&logo=security&logoColor=white" alt="Vulnerability Scanning" /></a>
</div>

### Exploitation Tools
<div>
  <a href="https://www.metasploit.com"><img src="https://img.shields.io/badge/-Metasploit-B22222?&style=for-the-badge&logo=metasploit&logoColor=white" alt="Metasploit" /></a>
  <a href="https://www.cobaltstrike.com"><img src="https://img.shields.io/badge/-Cobalt%20Strike-1E90FF?&style=for-the-badge&logo=target&logoColor=white" alt="Cobalt Strike" /></a>
  <a href="https://sqlmap.org"><img src="https://img.shields.io/badge/-sqlmap-3CB371?&style=for-the-badge&logo=database&logoColor=white" alt="sqlmap" /></a>
  <a href="https://beefproject.com"><img src="https://img.shields.io/badge/-BeEF-FF8C00?&style=for-the-badge&logo=browser&logoColor=white" alt="BeEF" /></a>
</div>

### C2 Frameworks
<div>
  <a href="https://github.com/BishopFox/sliver"><img src="https://img.shields.io/badge/-Sliver-6A0DAD?&style=for-the-badge&logo=github&logoColor=white" alt="Sliver" /></a>
  <a href="https://github.com/Adaptix-Framework/AdaptixC2"><img src="https://img.shields.io/badge/-AdaptixC2-1F8ACB?&style=for-the-badge&logo=github&logoColor=white" alt="AdaptixC2" /></a>
  <a href="https://www.cobaltstrike.com"><img src="https://img.shields.io/badge/-Cobalt%20Strike-1E90FF?&style=for-the-badge&logo=target&logoColor=white" alt="Cobalt Strike" /></a>
  <a href="https://github.com/cobbr/Covenant"><img src="https://img.shields.io/badge/-Covenant-2F4F4F?&style=for-the-badge&logo=github&logoColor=white" alt="Covenant" /></a>
  <a href="https://github.com/HavocFramework/Havoc"><img src="https://img.shields.io/badge/-Havoc-DC143C?&style=for-the-badge&logo=github&logoColor=white" alt="Havoc" /></a>
</div>


## Certifications

<div>
  <a href="https://www.offsec.com/courses/pen-200/"><img src="https://img.shields.io/badge/-OSCP-0F62FE?&style=for-the-badge&logo=offensive-security&logoColor=white" alt="OSCP" /></a>
  <a href="https://www.offsec.com/courses/pen-300/"><img src="https://img.shields.io/badge/-OSEP-7D3C98?&style=for-the-badge&logo=offensive-security&logoColor=white" alt="OSEP" /></a>
  <a href="https://www.alteredsecurity.com/post/certified-red-team-professional-crtp"><img src="https://img.shields.io/badge/-CRTP-1F8A70?&style=for-the-badge&logo=security&logoColor=white" alt="CRTP" /></a>
  <a href="https://www.zeropointsecurity.co.uk/course/red-team-ops"><img src="https://img.shields.io/badge/-RTO%20(CRTO)-2B6CB0?&style=for-the-badge&logo=zero-point-security&logoColor=white" alt="RTO / CRTO" /></a>
  <a href="https://maldevacademy.com/"><img src="https://img.shields.io/badge/-MalDev-DC143C?&style=for-the-badge&logo=maldevacademy&logoColor=white" alt="MalDev" /></a>
</div>


## Advanced Projects
My work below centers on offensive security engineering—crafting realistic red-team simulations, automation tools, and adversary-emulation frameworks.
These projects reflect relentless commitment, late-night experimentation, and a passion for mastering the offensive side to strengthen the defensive one.
Explore my highlighted project to see the precision, structure, and drive behind my builds.

| **Project**                                                                      | **Project Repo**                                 |
|----------------------------------------------------------------------------------|----------------------------------------------------|
| 1.&nbsp; Fully Undetectable in-Memmory Password sniffer trojan (veracrypt)       | <a href="https://github.com/Benjamin-code-sys/Password-Sniffer">Password Sniffer</a>                                          |
| 2.&nbsp; Compromising Entire Internal Network by Abusing a Web Server (full report)   | <a href="https://github.com/Benjamin-code-sys/Full-Network-Compromise">Penetration Test Report</a>
