# Hello, I'm Peter 
<a href="https://linkedin.com/in/peter-w90"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>

I am a Cybersecurity graduate with strong interest in all things blue team.

## Objective
I would really like to help companies protect themselves from attacks.

My studies have led me to develop a passion for cybersecurity, and I am now eager to transition into this field, specifically aiming to join a Security Operations Center (SOC) as a Tier 1 Analyst.

## Projects
**Detection and Monitoring Lab**

* 	Designed and implemented a virtualized home lab network for vulnerability testing and threat detection.
* Configured Windows Server, Splunk (SIEM), Kali Linux, and Windows 10 in the lab environment.
* Performed brute-force attacks using Kali Linux’s Crowbar and analyzed logs in Splunk to detect and respond to failed and successful login attempts.

**Incident response lab(WGUD483)**

* In this lab an engineer put in a ticket that the application server used for processing CAD images began to run slow and had high CPU and GPU usage. As the Security professional at this oraganization i was tasked with investigating this incident.
* After speaking with the engineer it was was found that this occured after updating the application however the email from the vendor was spoofed.
* After logging into the affected server and taking a look into task manager it was found that a cryptominer was causing the high CPU usage. the attackers were using this server to mine cryptocurrency on their behalf.
* Logged into the SIEM(Wazuh) and found the IP address and port number of the malicious traffic
* On the affected server the attackers disabled defender reason why the application wasnt detected. I went into group policy and renabled defender and turned on virus scanning and protection.
* I ran a scan which picked up the XMRig miner and removed the application
* I then went into the firewall and blocked traffic to and from the port the attackers were using to communicate
* After remidiating the incident i suggested that a EDR solution be implemented  and more user training to spot phishing emails to prevent this from reoccuring 


**Network Merger and Implementation Plan (WGU-D82)**
*	Executed a comprehensive merger of two company networks, incorporating zero trust architecture and migrating infrastructure to Azure.
*	Analyzed vulnerability scans and recommended security enhancements.
*	Deprecated unsupported hardware and implemented defense-in-depth strategies.


**Home Lab**
* Purchased dell optiplex 
* installed proxmox hypervisor
* installed windows 10 machine
* installed windows server 
* installed PFSense and configured firewall rules to block unwanted conections
* installed PiHole for ad blocking
* created domain and used cloudflare for ssl certificate when accessing server
* configured active directory by adding users and the windows 10 machine to the domain and configured group policies

**Cyberdefenders Boss of the SOC v1**
  * utilized splunk for threat hunting to analyze the MITRE ATTACK framework steps including intial access, exceution,persistence, priviledge escalation,defense evasion and so forth.
 
**Python Calculator**
* designed a basic calculator in python to accept user input and out answer 




## Skills

* Cybersecurity Tools: SIEM (Splunk), IPS, EDR
* Network Analysis: Wireshark, Packet Capture Analysis
* Email Analysis 
* Vulnerability Scanning: Nessus
* Security Frameworks: RMF, NIST, Zero Trust Architecture
* Operating Systems: Windows, Linux
* Scripting & Automation: PowerShell, Python


## Certifications
•	CompTIA Network+

•	CompTIA Security+

•	Security Blue Team Level 1

•	CompTIA CySA+

