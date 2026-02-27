# Week-4 VAPT Tasks

**Overview :-**

This repository documents the work completed during **Week 4 of my VAPT internship**. The focus of this week was on advanced exploitation techniques, API security testing, privilege escalation, network protocol attacks, mobile application penetration testing, and a capstone task demonstrating a complete penetration testing engagement. These activities were conducted in a controlled lab environment to enhance practical security testing and analysis skills.


**Scope of Work :-**

The Week-4 tasks focused on:

- Advanced exploitation techniques and exploit chaining concepts
- Customizing Python-based Proof-of-Concept exploits from Exploit-DB
- API security testing based on **OWASP API Top 10**
- Privilege escalation enumeration and persistence mechanisms
- Network protocol attacks including **SMB relay, ARP spoofing, and DNS spoofing**
- Mobile application security testing using static and dynamic analysis
- Runtime instrumentation and authentication bypass concepts
- Simulating a **full VAPT engagement using PTES methodology**


**Environment & Tools :-**

1) Lab Environment

- Attacker Machine: **Kali Linux**
- Target Machines: **HackTheBox (Meow Lab), VulnHub VM, DVWA API Environment**
- Mobile Application: **Android test APK (test.apk)**

2) Tools Used

- Metasploit Framework
- Burp Suite
- Postman
- sqlmap
- Exploit-DB
- LinPEAS
- Responder
- Ettercap
- Wireshark
- MobSF (Mobile Security Framework)
- Frida (Runtime Instrumentation Toolkit)
- OpenVAS (Vulnerability Scanning)
- Nmap (Network Scanning)


**Work Breakdown :-**

Part 1: Advanced Exploitation Lab

- Studied exploit chaining concepts and simulated multi-stage attacks, analyzed Metasploit exploit modules, customized Python-based Proof-of-Concept exploits from Exploit-DB, and explored defense bypass concepts such as Return-Oriented Programming (ROP).


Part 2: API Security Testing Lab

- Performed API testing using Burp Suite and Postman, identified vulnerabilities related to **Broken Object Level Authorization (BOLA)** and GraphQL query manipulation, intercepted and modified API requests, and documented findings aligned with OWASP API Top 10 risks.


Part 3: Privilege Escalation and Persistence Lab

- Performed privilege escalation enumeration using LinPEAS, analyzed kernel vulnerabilities, writable files, and SUID binaries, obtained elevated privileges, and demonstrated persistence techniques using reverse shell scripts and cron job scheduling.


Part 4: Network Protocol Attacks Lab

- Conducted network protocol attacks including **SMB relay attacks using Responder**, performed Man-in-the-Middle attacks with Ettercap using ARP spoofing, captured authentication hashes, implemented DNS spoofing, and analyzed intercepted network traffic using Wireshark.


Part 5: Mobile Application Testing Lab

- Performed static analysis of an Android application using MobSF, identified insecure data storage and hardcoded secrets, analyzed application security scorecards, and explored dynamic testing concepts using Frida for function hooking and authentication bypass techniques.


Part 6: Capstone Project – Full VAPT Engagement

- Simulated a full penetration testing workflow including reconnaissance using Nmap, exploitation using Metasploit, vulnerability scanning using OpenVAS, and web traffic interception using Burp Suite. Documented findings, remediation recommendations, and prepared structured PTES-style reporting.


**Documentation :-**

- All findings, logs, vulnerability tables, screenshots, and analysis are compiled into a consolidated **Week-4 VAPT report**.

- Supporting artifacts such as screenshots and testing outputs are organized **part-wise in the repository**.

- Reporting follows **PTES methodology**, emphasizing ethical security testing, responsible disclosure, and professional documentation practices.


**Disclaimer :-**

All activities documented in this repository were performed strictly for **educational and internship learning purposes** within authorized lab environments. No testing was conducted on real-world systems without proper permission. This work follows ethical hacking standards and responsible disclosure guidelines.
