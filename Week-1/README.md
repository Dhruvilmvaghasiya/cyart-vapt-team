# Week-1 VAPT Tasks

## Overview
This repository documents the work completed during Week 1 of my VAPT internship.  
The focus of this week was to build a strong foundation in Security Assessment, understand the VAPT methodology, set up a safe lab environment, and perform a vulnerability scan using OpenVAS followed by risk assessment and prioritization.

---

## Scope of Work
Week-1 activities covered:

- Understanding Security Assessment and its types (Assessment, VA, PT, Compliance)
- VAPT methodology (Planning → Discovery → Attack → Reporting)
- Security standards and compliance basics (OWASP Top 10, ISO/GDPR/HIPAA concepts)
- Risk assessment using CVSS and severity classification
- Lab environment setup (Kali Linux + Metasploitable 2)
- Connectivity verification and tool validation
- Vulnerability assessment using OpenVAS
- Risk assessment and vulnerability prioritization table

---

## Environment & Tools

### Lab Environment
- **Attacker Machine:** Kali Linux
- **Target Machine:** Metasploitable 2 (intentionally vulnerable VM)
- **Virtualization:** VMware Workstation
- **Network Mode:** NAT / Host-Only (isolated lab network)

### Tools Used
- **Nmap** – service discovery and basic scanning  
- **OpenVAS (Greenbone)** – vulnerability scanning and reporting  
- **Metasploit Framework** – validation reference (tool awareness)  
- **Wireshark** – network traffic capture (basic awareness)  
- **Utilities:** ping, basic Linux commands

---

## Work Summary (Week-1)

### Part 1: Security Assessment & VAPT Fundamentals
- Studied what security assessment means and why it is important.
- Understood the difference between:
  - Vulnerability Assessment vs Penetration Testing  
  - Security assessment vs compliance testing
- Learned a structured VAPT approach:
  - Planning, Discovery, Attack, Reporting
- Reviewed why documentation matters in security testing.

### Part 2: Testing Environment Setup
- Created a controlled lab setup using Kali Linux as attacker and Metasploitable 2 as target.
- Verified network configuration and connectivity using `ping`.
- Confirmed tools were available and ready before scanning.

### Part 3: Vulnerability Assessment Using OpenVAS
- Created scan task in OpenVAS for target:
  - **Target:** Metasploitable 2
  - **Target IP:** 192.168.177.134
  - **Scan Profile:** Full and Fast
  - **Port List:** All TCP and Nmap top 100 UDP
- Executed the scan and reviewed severity distribution (Critical/High/Medium/Low).
- Noted key findings such as default credentials and outdated services.

### Part 4: Risk Assessment & Prioritization
- Used CVSS score + likelihood + impact to prioritize vulnerabilities.
- Prepared a risk table (Critical/High/Medium/Low) to decide what to fix first.
- Documented observations and conclusion based on results.

---

## Documentation
- The complete Week-1 report is included in this repository:
  - **VAPT_Week1_Report.pdf**
- The report contains:
  - Setup screenshots
  - OpenVAS configuration and scan evidence
  - Key vulnerability summary
  - Risk assessment table and prioritization
  - Conclusion, key learnings, and references

---

## Disclaimer
All work documented here was performed in a **legal and authorized lab environment** (Kali + Metasploitable).  
No real-world systems were tested. This repository is maintained strictly for learning and internship documentation.
