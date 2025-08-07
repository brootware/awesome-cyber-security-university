# Awesome Cyber Security University
> A curated list of awesome and free educational resources that focuses on learning by doing. This project aims to be a comprehensive, guided pathway for anyone looking to enter or advance in the field of cybersecurity.

<div align="center">
<a href="https://brootware.github.io/awesome-cyber-security-university/"><img src="assets/purpleteam.png" width="250"/></a>
<br/>
<i>Because education should be free.</i>
<br/>

<a href="https://brootware.github.io/awesome-cyber-security-university/"><img src="https://visitor-badge.glitch.me/badge?page_id=brootware.cyber-security-university&right_color=blue" /></a>
</div>

## Contents

* [About This University](#about-this-university)
* [Your Cyber Journey Blueprint: Getting Started](#your-cyber-journey-blueprint-getting-started)
* [Core Learning Paths](#core-learning-paths)
    * [Free Beginner Red Team Path](#free-beginner-red-team-path)
    * [Free Beginner Blue Team Path](#free-beginner-blue-team-path)
    * [Free Beginner Purple Team Path](#free-beginner-purple-team-path)
* [Specialized Domains](#specialized-domains)
    * [Cloud Security](#cloud-security)
    * [Mobile Security](#mobile-security)
* [Advanced Practice & CTFs](#advanced-practice--ctfs)
* [Career & Beyond](#career--beyond)
* [Contributing and Community](#contributing-and-community)

---

## About This University

This "Awesome Cyber Security University" is more than just a list of links; it is a structured curriculum designed to take you from a curious beginner to a capable cybersecurity professional. Our philosophy is simple: the best way to learn is by doing. Every resource here is free and emphasizes hands-on practice.

We understand that the world of cybersecurity can seem vast and intimidating. This guide is built to provide a clear, progressive path, ensuring you build a strong foundation before diving into specialized areas. Think of it as your personal roadmap through the digital security landscape.

---

## Your Cyber Journey Blueprint: Getting Started

For every aspiring cybersecurity professional, the journey begins with understanding the landscape and setting up a safe environment for practice. This section is your "Level 0" - the essential foundation before you dive into the core learning paths.

### 1. Understanding the Landscape: Roles in Cybersecurity

Before you pick a path, it helps to know where you are going. Cybersecurity has many roles, but they often fall into three main categories:

*   **Red Team | The Attackers:** These are the ethical hackers. Their job is to simulate real-world attacks to test an organization's defenses. They think like adversaries to find weaknesses before malicious actors do.
    *   _Analogy:_ Imagine a team hired to find all the hidden entrances and weak spots in a castle's walls by trying to break in.
*   **Blue Team | The Defenders:** These are the guardians. They build, maintain, and monitor security systems to protect against attacks. They are the first line of defense, detecting and responding to threats.
    *   _Analogy:_ This team designs the castle's defenses, patrols the walls, and watches for any signs of an attempted breach.
*   **Purple Team | The Trainers & Optimizers:** This team acts as a bridge between Red and Blue. They ensure that the insights gained from Red Team exercises are effectively used by the Blue Team to improve defenses. They optimize the overall security posture.
    *   _Analogy:_ This team helps the attackers and defenders work together, sharing knowledge to make the castle's defenses stronger and the guards more effective.

### 2. Setting Up Your Cyber Lab: Your Safe Practice Environment

You wouldn't learn to drive a car by immediately jumping onto a busy highway. Similarly, in cybersecurity, you need a safe, isolated space to practice. This is where Virtual Machines (VMs) come in.

*   **What is a Virtual Machine (VM)?**
    A VM is like having a separate, independent computer running inside your current computer. It allows you to install different operating systems (like Linux) and experiment with tools without affecting your main system. If you break something in the VM, you can simply reset it!

*   **Recommended Tools for Your Lab:**
    *   **Virtualization Software:**
        *   [VirtualBox](https://www.virtualbox.org/wiki/Downloads) - Free and open-source. Excellent for beginners.
        *   [VMware Workstation Player](https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html) - Free for personal use. Another robust option.
    *   **Operating System for Practice:**
        *   [Kali Linux](https://www.kali.org/get-kali/#kali-virtual-machines) - A Linux distribution specifically designed for penetration testing and digital forensics, pre-loaded with hundreds of tools. Download the pre-built VM image for VirtualBox or VMware for the easiest setup.

*   **Your First Steps (Conceptual):**
    1.  Download and install your chosen virtualization software (VirtualBox or VMware Player).
    2.  Download the Kali Linux VM image compatible with your virtualization software.
    3.  Import the Kali Linux image into your virtualization software.
    4.  Start your Kali Linux VM. You now have a safe, dedicated environment for all your hands-on learning!

### 3. Essential Foundational Concepts

Before diving deep into specialized tools, a solid grasp of these basics will make your learning journey much smoother:

*   **Networking Fundamentals:** Understand how computers communicate. Concepts like IP addresses, ports, protocols (TCP/IP, HTTP), and basic network devices (routers, switches).
*   **Command-Line Interface (CLI):** Proficiency in using the terminal (especially Linux command line) is non-negotiable. Many powerful cybersecurity tools are command-line based.
*   **Operating System Basics:** A general understanding of how operating systems (Linux, Windows) manage files, processes, and users.

---

## Core Learning Paths

Once you have your lab set up and a grasp of the fundamentals, you can embark on these structured learning paths. Each path is designed to build your skills progressively.

### Free Beginner Red Team Path

This path focuses on offensive security - learning to think like an attacker to identify and exploit vulnerabilities.

#### Level 1 - Intro & Foundational Tools

*   [OpenVPN](<https://tryhackme.com/room/openvpn>) - Learn how to connect to a virtual private network using OpenVPN.
*   [Welcome](<https://tryhackme.com/jr/welcome>) - Learn how to use a TryHackMe room to start your upskilling in cyber security.
*   [Intro to Researching](<https://tryhackme.com/room/introtoresearch>) - A brief introduction to research skills for pentesting.
*   [Linux Fundamentals 1](<https://tryhackme.com/room/linuxfundamentalspart1>) - Embark on the journey of learning the fundamentals of Linux. Learn to run some of the first essential commands on an interactive terminal.
*   [Linux Fundamentals 2](<https://tryhackme.com/room/linuxfundamentalspart2>) - Continue your journey with Linux fundamentals.
*   [Linux Fundamentals 3](<https://tryhackme.com/room/linuxfundamentalspart3>) - Conclude your Linux fundamentals journey.
*   [Pentesting fundamentals](<https://tryhackme.com/room/pentestingfundamentals>) - Fundamentals of penetration testing.
*   [Principles of security](<https://tryhackme.com/room/principlesofsecurity>) - Core principles guiding secure systems.
*   [Red Team Engagements](<https://tryhackme.com/room/redteamengagements>) - Introduction to red team engagements.
*   [Hip Flask](https://tryhackme.com/room/hipflask) - An in-depth walkthrough covering pentest methodology against a vulnerable server.
*   [Practice Linux Commands](https://labex.io/courses/linux-basic-commands-practice-online) - A free course with 41 hands-on labs to practice and master the most commonly used Linux commands.

**Introductory CTFs to get your feet wet**

*   [Google Dorking](<https://tryhackme.com/room/googledorking>) - Explaining how Search Engines work and leveraging them into finding hidden content!
*   [Osint](<https://tryhackme.com/room/ohsint>) - Introduction to Open Source Intelligence.
*   [Shodan.io](<https://tryhackme.com/room/shodan>) - Learn about Shodan.io and how to use it for device enumeration.

#### Level 2 - Tooling & Reconnaissance

*   [Tmux](<https://tryhackme.com/room/rptmux>) - Learn to use tmux, one of the most powerful multi-tasking tools on linux.
*   [Nmap, Curl and Netcat](<https://echoctf.red/challenge/1>) - Gain experience with Nmap, Curl and Netcat for network communications.
*   [Web Scanning](<https://tryhackme.com/room/rustscan>) - Learn the basics of automated web scanning.
*   [Subdomain Enumeration](<https://tryhackme.com/room/subdomainenumeration>) - Learn how to find subdomains with different techniques.
*   [Metasploit](<https://tryhackme.com/room/metasploitintro>) - An introduction to the main components of the Metasploit Framework.
*   [Hydra](<https://tryhackme.com/room/hydra>) - Learn about and use Hydra, a fast network logon cracker, to bruteforce and obtain a website's credentials.
*   [Linux Privesc](<https://tryhackme.com/room/linuxprivesc>) - Practice your Linux Privilege Escalation skills on an intentionally misconfigured Debian VM with multiple ways to get root! SSH is available.
*   [Red Team Fundamentals](<https://tryhackme.com/room/redteamfundamentals>) - Learn about the basics of a red engagement, the main components and stakeholders involved, and how red teaming differs from other cyber security engagements.
*   [Red Team Recon](<https://tryhackme.com/room/redteamrecon>) - Learn how to use DNS, advanced searching, Recon-ng, and Maltego to collect information about your target.
*   [Nmap Tutorials](https://labex.io/tutorials/quick-start-with-nmap-free-tutorials-400132) - Learn and practice the basics of network scanning using Nmap.

**Red Team Intro CTFs**

*   [Vulnversity](<https://tryhackme.com/room/vulnversity>) - Learn about active recon, web app attacks and privilege escalation.
*   [Blue](<https://tryhackme.com/room/blue>) - Deploy & hack into a Windows machine, leveraging common misconfigurations issues.
*   [Simple CTF](<https://tryhackme.com/room/easyctf>) - Beginner level CTF.
*   [Bounty Hacker](<https://tryhackme.com/room/cowboyhacker>) - A space cowboy-themed boot to root machine.

#### Level 3 - Cryptography & Hashes

*   [Crack the hash](<https://tryhackme.com/room/crackthehash>) - Cracking hash challenges.
*   [Agent Sudo](<https://tryhackme.com/room/agentsudoctf>) - You found a secret server located under the deep sea. Your task is to hack inside the server and reveal the truth.
*   [The Cod Caper](<https://tryhackme.com/room/thecodcaper>) - A guided room taking you through infiltrating and exploiting a Linux system.
*   [Ice](<https://tryhackme.com/room/ice>) - Deploy & hack into a Windows machine, exploiting a very poorly secured media server.
*   [Lazy Admin](<https://tryhackme.com/room/lazyadmin>) - Easy linux machine to practice your skills.
*   [Basic Pentesting](<https://tryhackme.com/room/basicpentestingjt>) - This is a machine that allows you to practice web app hacking and privilege escalation.
*   [Bypassing UAC](https://tryhackme.com/room/bypassinguac) - Learn common ways to bypass User Account Control (UAC) in Windows hosts.

#### Level 4 - Web Application Security

*   [OWASP top 10](<https://tryhackme.com/room/owasptop10>) - Learn about and exploit each of the OWASP Top 10 vulnerabilities; the 10 most critical web security risks.
*   [Inclusion](<https://tryhackme.com/room/inclusion>) - A beginner-level Local File Inclusion (LFI) challenge.
*   [Injection](<https://tryhackme.com/room/injection>) - Walkthrough of OS Command Injection. Demonstrate OS Command Injection and explain how to prevent it on your servers.
*   [Juiceshop](<https://tryhackme.com/room/owaspjuiceshop>) - This room uses the OWASP juice shop vulnerable web application to learn how to identify and exploit common web application vulnerabilities.
*   [Overpass](<https://tryhackme.com/room/overpass>) - What happens when some broke CompSci students make a password manager.
*   [Year of the Rabbit](<https://tryhackme.com/room/yearoftherabbit>) - Can you hack into the Year of the Rabbit box without falling down a hole.
*   [DevelPy](<https://tryhackme.com/room/bsidesgtdevelpy>) - Boot2root machine for FIT and bsides Guatemala CTF.
*   [Jack of all trades](<https://tryhackme.com/room/jackofalltrades>) - Boot-to-root originally designed for Securi-Tay 2020.
*   [Bolt](https://tryhackme.com/room/bolt) - Bolt themed machine to root into.

#### Level 5 - Reverse Engineering & Pwn

*   [Windows x64 Assembly](<https://tryhackme.com/r/room/win64assembly>) - Introduction to x64 Assembly on Windows.
*   [CC Ghidra](<https://tryhackme.com/room/ccghidra>) - This room teaches the basics of Ghidra.
*   [CC Radare2](<https://tryhackme.com/room/ccradare2>) - This room teaches the basics of Radare2.
*   [Reverse Engineering](<https://tryhackme.com/room/reverseengineering>) - This room focuses on teaching the basics of assembly through reverse engineering.
*   [Reversing ELF](<https://tryhackme.com/room/reverselfiles>) - Room for beginner Reverse Engineering CTF players.
*   [Dumping Router Firmware](<https://tryhackme.com/room/rfirmware>) - Reverse engineering router firmware.
*   [Intro to pwntools](<https://tryhackme.com/room/introtopwntools>) - Introduction to popular pwn tools framework.
*   [Pwnkit: CVE-2021-4034](<https://tryhackme.com/room/pwnkit>) - Interactive lab for exploiting and remediating Pwnkit (CVE-2021-4034) in the Polkit package.

#### Level 6 - Privilege Escalation

*   [Sudo Security Bypass](<https://tryhackme.com/room/sudovulnsbypass>) - A tutorial room exploring CVE-2019-14287 in the Unix Sudo Program. Room One in the SudoVulns Series.
*   [Sudo Buffer Overflow](<https://tryhackme.com/room/sudovulnsbof>) - A tutorial room exploring CVE-2019-18634 in the Unix Sudo Program. Room Two in the SudoVulns Series.
*   [Windows Privesc Arena](<https://tryhackme.com/room/windowsprivescarena>) - Students will learn how to escalate privileges using a very vulnerable Windows 7 VM.
*   [Linux Privesc Arena](<https://tryhackme.com/room/linuxprivescarena>) - Students will learn how to escalate privileges using a very vulnerable Linux VM.
*   [Windows Privesc](<https://tryhackme.com/room/windows10privesc>) - Students will learn how to escalate privileges using a very vulnerable Windows 7 VM.
*   [Blaster](<https://tryhackme.com/room/blaster>) - Metasploit Framework to get a foothold.
*   [Ignite](<https://tryhackme.com/room/ignite>) - A new start-up has a few security issues with its web server.
*   [Kenobi](<https://tryhackme.com/room/kenobi>) - Walkthrough on exploiting a Linux machine. Enumerate Samba for shares, manipulate a vulnerable version of proftpd and escalate your privileges with path variable manipulation.
*   [Capture the flag](<https://tryhackme.com/room/c4ptur3th3fl4g>) - Another beginner-level CTF challenge.
*   [Pickle Rick](<https://tryhackme.com/room/picklerick>) - Rick and Morty themed LFI challenge.

> Congratulations! If you have finished until here. You deserve a badge! Put this in your writeups or git profile.

<details>
  <summary>Click here to get your red team badge!</summary>

<https://gist.github.com/brootware/e30a10dbccf334eb95da7ea59d6f87fe>

</details>

### Free Beginner Blue Team Path

This path focuses on defensive security - protecting systems, detecting threats, and responding to incidents.

#### Level 1 - Tools & Fundamentals

*   [Introduction to digital forensics](https://tryhackme.com/room/introdigitalforensics) - Introduction to Digital Forensics.
*   [Windows Fundamentals](<https://tryhackme.com/room/windowsfundamentals1xbx>) - Introduction to Windows Operating System.
*   [Nessus](<https://tryhackme.com/room/rpnessusredux>) - Introduction to Nessus vulnerability scanner.
*   [Mitre](<https://tryhackme.com/room/mitre>) - Introduction to the MITRE ATT&CK framework.
*   [IntroSIEM](https://tryhackme.com/room/introtosiem) - Introduction to Security Information and Event Management (SIEM).
*   [Yara](<https://tryhackme.com/room/yara>) - Introduction to Yara for malware analysis.
*   [OpenVAS](<https://tryhackme.com/room/openvas>) - Introduction to OpenVAS vulnerability scanner.
*   [Intro to Honeypots](<https://tryhackme.com/room/introductiontohoneypots>) - Introduction to Honeypots.
*   [Volatility](<https://cyberdefenders.org/blueteam-ctf-challenges/redline/>) - Introduction to memory analysis with Volatility.
*   [Red Line](<https://tryhackme.com/room/btredlinejoxr3d>) - Learn how to use Redline to perform memory analysis and scan for IOCs on an endpoint.
*   [Autopsy](<https://tryhackme.com/room/autopsy2ze0>) - Use Autopsy to investigate artifacts from a disk image.

#### Level 2 - Security Operations, Incident Response & Threat Hunting

*   [Investigating Windows](<https://tryhackme.com/room/investigatingwindows>) - Investigating Windows systems for security incidents.
*   [Juicy Details](<https://tryhackme.com/room/juicydetails>) - Analyze logs to investigate a simulated breach.
*   [Carnage](<https://tryhackme.com/room/c2carnage>) - Apply your analytical skills to analyze malicious network traffic using Wireshark.
*   [Squid Game](<https://tryhackme.com/room/squidgameroom>) - Squid game-themed CTF for defensive skills.
*   [Splunk Boss of the SOC V1](<https://tryhackme.com/room/bpsplunk>) - Learn how to use Splunk to search through massive amounts of information.
*   [Splunk Boss of the SOC V2](<https://cyberdefenders.org/blueteam-ctf-challenges/16>) - Splunk analysis volume 2.
*   [Splunk Boss of the SOC V3](<https://cyberdefenders.org/blueteam-ctf-challenges/8>) - Splunk analysis volume 3.
*   [Hunt Conti with Splunk](https://tryhackme.com/room/contiransomwarehgh) - Investigate a ransomware compromise using Splunk.
*   [Hunting for Execution Tactic](https://info.cyborgsecurity.com/en-us/threat-hunting-workshop-3) - Dive into the MITRE ATT&CK Tactic of Execution (TA0002).
*   [Hunting for Credential Access](https://info.cyborgsecurity.com/en-us/threat-hunting-workshop-5) - Dive into the MITRE ATT&CK Tactic of Credential Access (TA0006).
*   [Hunting for Persistence Access](https://info.cyborgsecurity.com/en-us/threat-hunting-workshop-2) - Explore adversarial persistence (TA0003).
*   [Hunting for Defense Evation](https://info.cyborgsecurity.com/en-us/threat-hunting-workshop-4) - Explore the MITRE ATT&CK Tactic of Defense Evasion (TA0005).

#### Level 3 - Forensics, Threat Intelligence & Cryptography

*   [Threat Intelligence 101](<https://tryhackme.com/room/cyberthreatintel>) - Introduction to Cyber Threat Intelligence.
*   [Threat Intelligence Tools](<https://tryhackme.com/room/threatinteltools>) - Explore OSINT tools for security assessments.
*   [Martryohka doll](<https://play.picoctf.org/practice/challenge/129?category=4&page=1&solved=0>) - Beginner file analysis challenge.
*   [The Glory of the Garden](<https://play.picoctf.org/practice/challenge/44?category=4&page=1&solved=0>) - Beginner image analysis challenge.
*   [Packets Primer](<https://play.picoctf.org/practice/challenge/286?category=4&page=2&solved=0>) - Beginner packet analysis challenge.
*   [Wireshark doo doo doo](<https://play.picoctf.org/practice/challenge/115?category=4&page=1&solved=0>) - Beginner packet analysis challenge.
*   [Wireshark two two two](<https://play.picoctf.org/practice/challenge/110?category=4&page=1&solved=0>) - Beginner packet analysis challenge.
*   [Trivial flag transfer protocol](<https://play.picoctf.org/practice/challenge/103?category=4&page=1&solved=0>) - Beginner packet analysis challenge.
*   [What Lies within](<https://play.picoctf.org/practice/challenge/74?category=4&page=2&solved=0>) - Beginner decoding analysis challenge.
*   [Illumination](<https://app.hackthebox.com/challenges/illumination>) - Medium level forensics challenge.
*   [Emo](<https://app.hackthebox.com/challenges/emo>) - Medium level forensics challenge.
*   [Obsecure](<https://app.hackthebox.com/challenges/obscure>) - Medium level forensics challenge.
*   [Intel101 Challenge](<https://cyberdefenders.org/blueteam-ctf-challenges/38>) - Medium level Threat Intel challenge.
*   [Introduction to Cryptohack](<https://cryptohack.org/courses/intro/course_details/>) - Medium level cryptography challenge.

#### Level 4 - Memory & Disk Forensics

*   [Sleuthkit Intro](<https://play.picoctf.org/practice/challenge/301?category=4&page=2&solved=0>) - Medium level disk forensics challenge.
*   [Reminiscent](<https://app.hackthebox.com/challenges/reminiscent>) - Medium level disk forensics challenge.
*   [Hunter - Windows Disk Image Forensics](<https://cyberdefenders.org/blueteam-ctf-challenges/32>) - Medium level disk forensics challenge.
*   [Spotlight - Mac Disk Image Forensics](<https://cyberdefenders.org/blueteam-ctf-challenges/34>) - Medium level disk forensics challenge.
*   [Ulysses - Linux Disk Image Forensics](<https://cyberdefenders.org/blueteam-ctf-challenges/41>) - Medium level disk forensics challenge.
*   [Banking Troubles - Windows Memory Image Forensics](<https://cyberdefenders.org/blueteam-ctf-challenges/43>) - Medium level memory forensics challenge.
*   [Detect Log4J](<https://cyberdefenders.org/blueteam-ctf-challenges/86>) - Medium level disk forensics challenge.

#### Level 5 - Malware Analysis and Reverse Engineering

*   [History of Malware](<https://tryhackme.com/room/historyofmalware>) - Introduction to malware history.
*   [Malware Introduction](<https://tryhackme.com/room/malmalintroductory>) - Introduction to malware.
*   [Basic Malware Reverse Engineering](<https://tryhackme.com/room/basicmalwarere>) - Introduction to malware reverse engineering.
*   [Intro Windows Reversing](<https://tryhackme.com/room/windowsreversingintro>) - Introduction to Windows reverse engineering.
*   [Windows x64 Assembly](<https://tryhackme.com/room/win64assembly>) - Introduction to x64 Assembly on Windows.
*   [JVM reverse engineering](<https://tryhackme.com/room/jvmreverseengineering>) - Learn Reverse Engineering for Java Virtual Machine bytecode.
*   [Get PDF (Malicious Document)](<https://cyberdefenders.org/blueteam-ctf-challenges/47>) - Reversing PDF malware.

> Congratulations! If you have finished until here. You deserve a badge! Put this in your writeups or git profile.

<details>
 <summary>Click here to get your blue team badge!</summary>

<https://gist.github.com/brootware/62b76a84aaa8d6f55c82f6f329ad6d2d>

</details>

### Free Beginner Purple Team Path

This path focuses on integrating offensive and defensive security practices to build more resilient systems.

#### Level 1 - Foundations

*   [Introduction to Purple Teaming](<https://tryhackme.com/room/introductiontopurpleteaming>) - Learn the fundamentals of purple teaming.
*   [Threat-Informed Defense](<https://academy.attackiq.com/courses/threat-informed-defense>) - A free course on threat-informed defense from AttackIQ Academy.
*   [MITRE ATT&CK for Defenders](<https://attack.mitre.org/>) - Understanding the ATT&CK framework from a defender's perspective.

#### Level 2 - Emulation and Detection

*   [Atomic Red Team](<https://github.com/redcanaryco/atomic-red-team>) - A library of simple tests that every security team can use to test their controls.
*   [Caldera](<https://github.com/mitre/caldera>) - An automated adversary emulation system.
*   [Sigma](<https://github.com/SigmaHQ/sigma>) - Generic signatures for SIEM systems.

---

## Specialized Domains

Once you have a strong foundation in Red, Blue, or Purple Teaming, you might want to explore these specialized areas that are critical in today's cybersecurity landscape.

### Cloud Security

Understanding security in cloud environments (AWS, Azure, GCP) is essential as more infrastructure moves off-premise.

#### Level 1 - Cloud Fundamentals

*   [Introduction to Cloud Computing](<https://tryhackme.com/room/introductiontocloudcomputing>) - Learn the fundamentals of cloud computing.
*   [AWS Certified Cloud Practitioner](<https://aws.amazon.com/certification/certified-cloud-practitioner/>) - Foundational knowledge of AWS Cloud.
*   [Azure Fundamentals](<https://docs.microsoft.com/en-us/learn/certifications/azure-fundamentals/>) - Foundational knowledge of Azure.
*   [Google Cloud Digital Leader](<https://cloud.google.com/certification/cloud-digital-leader>) - Foundational knowledge of Google Cloud.

#### Level 2 - Cloud Security Fundamentals

*   [AWS Security Fundamentals](<https://aws.amazon.com/training/digital/aws-security-fundamentals/>) - A free, self-paced digital course on AWS security fundamentals.
*   [Microsoft Azure Security Technologies](<https://docs.microsoft.com/en-us/learn/certifications/azure-security-engineer/>) - Learn how to implement security controls and threat protection in Azure.
*   [Google Cloud Security Best Practices](<https://cloud.google.com/security/best-practices>) - A guide to security best practices on Google Cloud.

#### Level 3 - Hands-On Cloud Security

*   [CloudGoat](<https://github.com/RhinoSecurityLabs/cloudgoat>) - Rhino Security Labs' "Vulnerable by Design" AWS deployment tool.
*   [SADCloud](<https://github.com/nccgroup/sadcloud>) - A tool for spinning up vulnerable-by-design AWS infrastructure.
*   [GCPGoat](<https://github.com/ine-labs/GCPGoat>) - A vulnerable GCP infrastructure.

### Mobile Security

Securing mobile applications and devices is a growing and critical field.

#### Level 1 - Mobile Security Fundamentals

*   [OWASP Mobile Top 10](<https://owasp.org/www-project-mobile-top-10/>) - The top 10 most critical mobile security risks.
*   [Introduction to Mobile Security](<https://www.cybrary.it/course/intro-to-mobile-security/>) - A free course on mobile security from Cybrary.

#### Level 2 - Android Security

*   [Android Security for Beginners](<https://www.udacity.com/course/android-security-for-beginners--ud996>) - A free course from Udacity.
*   [InsecureBankv2](<https://github.com/dineshshetty/Android-InsecureBankv2>) - A vulnerable Android application.

#### Level 3 - iOS Security

*   [iOS Security for Beginners](<https://www.hacker101.com/videos/ios-basics>) - A free course from Hacker101.
*   [Damn Vulnerable iOS App (DVIA)](<https://github.com/prateek147/DVIA-v2>) - A vulnerable iOS application.

---

## Advanced Practice & CTFs

This section is for those who want to sharpen their skills, test their knowledge, and dive into more complex challenges. Capture The Flag (CTF) competitions are an excellent way to apply what you've learned in a practical, competitive environment.

*   [Bandit](<https://overthewire.org/wargames/bandit/>) - Aimed at absolute beginners and teaches the basics of remote server access.
*   [Natas](<https://overthewire.org/wargames/natas/>) - Teaches the basics of serverside web-security.
*   [Post Exploitation Basics](<https://tryhackme.com/room/postexploit>) - Learn the basics of post-exploitation and maintaining access with mimikatz, bloodhound, powerview and msfvenom.
*   [Smag Grotto](<https://tryhackme.com/room/smaggrotto>) - An obscure boot to root machine.
*   [Dogcat](<https://tryhackme.com/room/dogcat>) - Exploit a PHP application via LFI and break out of a docker container.
*   [Buffer Overflow Prep](<https://tryhackme.com/room/bufferoverflowprep>) - Practice stack-based buffer overflows.
*   [Break out the cage](<https://tryhackme.com/room/breakoutthecage1>) - Help Cage bring back his acting career and investigate the nefarious going on of his agent.
*   [Lian Yu](<https://tryhackme.com/room/lianyu>) - A beginner-level security challenge.
*   [Insecure Kubernetes](<https://tryhackme.com/room/insekube>) - Exploiting Kubernetes by leveraging a Grafana LFI vulnerability.
*   [The Great Escape (docker)](<https://tryhackme.com/room/thegreatescape>) - Escaping docker container.
*   [Solr Exploiting Log4j](<https://tryhackme.com/room/solar>) - Explore CVE-2021-44228, a vulnerability in log4j affecting almost all software under the sun.
*   [Spring4Shell](<https://tryhackme.com/room/spring4shell>) - Interactive lab for exploiting Spring4Shell (CVE-2022-22965) in the Java Spring Framework.
*   [Most Recent threats](<https://tryhackme.com/module/recent-threats>) - Learn about the latest industry threats. Get hands-on experience identifying, exploiting, and mitigating critical vulnerabilities.

### Extremely Hard Rooms to do

These challenges are for those seeking to push their limits and tackle complex, multi-stage scenarios.

*   [Ra](<https://tryhackme.com/room/ra>) - You have found WindCorp's internal network and their Domain Controller. Pwn the network.
*   [CCT2019](<https://tryhackme.com/room/cct2019>) - Legacy challenges from the US Navy Cyber Competition Team 2019 Assessment sponsored by US TENTH Fleet.
*   [Theseus](<https://tryhackme.com/room/theseus>) - The first installment of the SuitGuy series of very hard challenges.
*   [IronCorp](<https://tryhackme.com/room/ironcorp>) - Get access to Iron Corp's system.
*   [Carpe Diem 1](<https://tryhackme.com/room/carpediem1>) - Recover your client's encrypted files before the ransomware timer runs out.
*   [Borderlands](<https://tryhackme.com/room/borderlands>) - Compromise a perimeter host and pivot through this network.
*   [Jeff](<https://tryhackme.com/room/jeff>) - Hack into Jeff's web server.
*   [Year of the Owl](https://tryhackme.com/room/yearoftheowl) - Owl-themed boot to root machine.
*   [Anonymous Playground](<https://tryhackme.com/room/anonymousplayground>) - Want to become part of Anonymous? They have a challenge for you.
*   [EnterPrize](<https://tryhackme.com/room/enterprize>) - Enterprise-themed network to hack into.
*   [Racetrack Bank](<https://tryhackme.com/room/racetrackbank>) - It's time for another heist.
*   [Python Playground](<https://tryhackme.com/room/pythonplayground>) - Use python to pwn this room.

---

## Career & Beyond

Learning is just the first step. This section helps you translate your newfound knowledge into tangible career opportunities and guides you on the path of continuous professional growth.

### 1. Building Your Professional Identity

*   **CTF Write-ups: Your Portfolio in Action:**
    Solving a CTF is great, but documenting *how* you solved it is invaluable. Write-ups demonstrate your problem-solving skills, technical understanding, and ability to communicate complex ideas. Host them on a blog, GitHub Pages, or a personal website. This is your practical portfolio.
*   **Crafting Your Online Presence:**
    *   **GitHub:** Showcase your CTF write-ups, any small scripts you develop, or contributions to open-source projects. A well-maintained GitHub profile is a strong asset.
    *   **LinkedIn:** Build a professional network. Connect with cybersecurity professionals, follow companies, and share your learning journey.
    *   **Personal Website/Blog:** A central hub for your write-ups, projects, and thoughts on cybersecurity.

### 2. Navigating the Job Market

*   **Understanding Entry-Level Roles:** Research common entry-level positions like Security Analyst, SOC Analyst, Junior Penetration Tester, or Cybersecurity Intern. Understand their typical responsibilities and required skills.
*   **Resume & Interview Tips:** Tailor your resume to highlight the hands-on experience gained from this curriculum. Practice explaining technical concepts clearly and concisely.
*   **Networking:** Attend local cybersecurity meetups, conferences (even virtual ones), and join online communities. Connections can open doors to opportunities.

### 3. Continuous Learning: The Cybersecurity Imperative

The cybersecurity landscape is constantly evolving. Lifelong learning is not an option; it's a necessity.

*   **Stay Current:** Follow cybersecurity news, blogs, and reputable researchers.
*   **Certifications:** While not strictly necessary for entry, certifications like CompTIA Security+, CySA+, or vendor-specific certs (AWS, Azure security) can validate your skills and open up more opportunities.
*   **Specialization:** As you gain experience, you may find a niche you are passionate about (e.g., cloud security, incident response, reverse engineering). Continue to deepen your expertise in those areas.

---

## Contributing and Community

This project thrives on community contributions. If you find a broken link, a new free resource, or an idea for improvement, your input is highly valued.

### How to Contribute:

We welcome contributions that align with the project's mission of providing free, hands-on cybersecurity education. Here are some guidelines:

*   **Resource Quality:** All suggested resources must be free and emphasize a "learn by doing" approach.
*   **Formatting:**
    *   Use title-casing for resource titles.
    *   Ensure links are correct and active.
    *   Maintain consistent indentation and bullet point style.
*   **Submission Process:**
    *   Make individual pull requests for each suggestion or logical group of changes. This makes reviews easier.
    *   Provide a clear description of your changes in the pull request.
    *   Read the full [contribution guide in the wiki](https://github.com/brootware/Cyber-Security-University/wiki) for more detailed instructions and best practices.

### Footnotes:

Inspired by <https://skerritt.blog/free-rooms/>

### Contributors & Stargazers

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

Special thanks to everyone who forked or starred the repository. Your support fuels this project!

[![Stargazers repo roster for @brootware/awesome-cyber-security-university](https://reporoster.com/stars/dark/brootware/awesome-cyber-security-university)](https://github.com/brootware/awesome-cyber-security-university/stargazers)

[![Forkers repo roster for @brootware/awesome-cyber-security-university](https://reporoster.com/forks/dark/brootware/awesome-cyber-security-university)](https://github.com/brootware/awesome-cyber-security-university/network/members)

Thanks goes to these wonderful people:

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://brootware.github.io"><img src="https://avatars.githubusercontent.com/u/7734956?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Oaker Min</b></sub></a><br /><a href="#infra-brootware" title="Infrastructure (Hosting, Build-Tools, etc)">&#9981;</a> <a href="#maintenance-brootware" title="Maintenance">&#9876;</a> <a href="https://github.com/brootware/cyber-security-university/commits?author=brootware" title="Documentation">&#128218;</a> <a href="https://github.com/brootware/cyber-security-university/commits?author=brootware" title="Code">&#128187;</a></td>
    <td align="center"><a href="https://lucidcode.com"><img src="https://avatars.githubusercontent.com/u/1631870?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Michael Paul Coder</b></sub></a><br /><a href="https://github.com/brootware/cyber-security-university/commits?author=IAmCoder" title="Documentation">&#128218;</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind are welcome!

<!--lint disable double-link-->
[↑](#contents)<!--lint enable double-link-->
