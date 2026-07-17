# Hi, I'm Asyraf 👋

> CTF Player | Cybersecurity Enthusiast | Computer Networks Graduate

I enjoy solving security challenges, investigating attacks, developing security tools, and documenting the complete technical process.

My main interests include:

- Web Application Security
- Digital Forensics
- Incident Response
- Active Directory Security
- Network Security
- Malware Analysis
- Capture The Flag competitions

---

## 🧭 My General Workflow

```text
Understand the Target
        ↓
Reconnaissance
        ↓
Enumeration
        ↓
Vulnerability Identification
        ↓
Exploitation or Investigation
        ↓
Evidence Collection
        ↓
Impact Analysis
        ↓
Remediation
        ↓
Documentation
```

For every project or challenge, I try to document:

```text
Problem → Methodology → Tools → Findings → Evidence → Solution → Lessons Learned
```

---

## 🛠️ Technical Skills

| Area | Technologies and Tools |
|---|---|
| Web Security | Burp Suite, FFUF, SQLmap, OWASP ZAP, Caido |
| Network Security | Nmap, Wireshark, Netcat, Masscan |
| Active Directory | Impacket, BloodHound, Certipy, BloodyAD, Responder |
| Digital Forensics | Volatility, Autopsy, FTK Imager, ExifTool, CyberChef |
| Incident Response | Splunk, Sysmon, Windows Event Logs, MISP |
| Malware Analysis | VirusTotal, FLOSS, Ghidra, Procmon, Wireshark |
| Reverse Engineering | Ghidra, GDB, Radare2, Strings |
| Exploitation | Metasploit, Pwntools, Python |
| Infrastructure | Linux, Kali Linux, Windows Server, Docker |
| Programming | Python, Bash, PHP, HTML, JavaScript |

---

# 📂 Work and Project Index

| Project | Category | Workflow Summary | Tools | Tags | Status |
|---|---|---|---|---|---|
| [CTF Writeups](https://github.com/elgolemite/CTF-Writeups) | CTF | Enumeration → Exploitation → Flag → Remediation → Write-up | Burp Suite, Nmap, Python, Ghidra | `#CTF` `#Web` `#Forensics` `#Reverse` | Active |
| [Web Security Challenges](https://github.com/elgolemite/Web-challenge) | Security Lab | Design → Develop → Test → Exploit → Document | Python, Flask, PHP, Burp Suite | `#WebSecurity` `#ChallengeDevelopment` | Active |
| [Penetration Testing Web Crawler](https://github.com/elgolemite/fyp-project-degree) | Final-Year Project | Crawl → Extract → Analyse → Prioritise → Report | Python, Web Crawling, Automation | `#Python` `#Automation` `#Pentesting` | Completed |
| [SOC Honeypot Investigation](PROJECT-LINK) | Defensive Security | Collect Logs → Detect → Investigate → Correlate → Respond | Splunk, Sysmon, Windows Logs | `#SOC` `#Honeypot` `#IncidentResponse` | Completed |
| [Active Directory Labs](PROJECT-LINK) | Offensive Security | Enumerate → Map Relationships → Exploit → Privilege Escalation | Impacket, BloodHound, Certipy | `#ActiveDirectory` `#Windows` | Ongoing |
| [Digital Forensics Labs](PROJECT-LINK) | Forensics | Preserve → Extract → Analyse → Correlate → Report | Volatility, Autopsy, CyberChef | `#Forensics` `#MemoryForensics` | Ongoing |
| [Portfolio Website](https://elgolemite.github.io) | Portfolio | Design → Build → Publish → Maintain | HTML, CSS, JavaScript | `#Portfolio` `#GitHubPages` | Active |

---

## 🏷️ Tag Directory

Use these tags consistently so visitors can quickly identify your work.

| Tag | Description |
|---|---|
| `#CTF` | Capture The Flag challenges and competitions |
| `#Web` | Web application exploitation |
| `#Forensics` | File, disk, memory, or network forensics |
| `#Reverse` | Reverse engineering and binary analysis |
| `#Pwn` | Binary exploitation |
| `#Crypto` | Cryptography challenges |
| `#OSINT` | Open-source intelligence |
| `#SOC` | Security operations and alert investigation |
| `#IncidentResponse` | Incident investigation and response |
| `#ThreatHunting` | Searching for suspicious activity |
| `#MalwareAnalysis` | Static or dynamic malware analysis |
| `#ActiveDirectory` | Windows domain security |
| `#NetworkSecurity` | Network analysis and security |
| `#Python` | Python-based projects or automation |
| `#Automation` | Tools that automate security tasks |
| `#Research` | Security research and experiments |
| `#ChallengeDevelopment` | CTF or vulnerable-lab development |

---

# 🔎 Detailed Work Template

Duplicate this section whenever you add a major project.

<details>
<summary><strong>Project Name — Click to expand</strong></summary>

## Project Overview

| Field | Details |
|---|---|
| Project | `PROJECT_NAME` |
| Category | `Web Security / Forensics / SOC / Active Directory` |
| Date | `Month Year` |
| Status | `Completed / Ongoing / Archived` |
| Repository | `[View repository](REPOSITORY_LINK)` |
| Documentation | `[Read documentation](DOCUMENTATION_LINK)` |
| Tags | `#Web` `#Python` `#Automation` |

### Objective

Briefly explain the purpose of the project.

Example:

> The objective was to investigate suspicious activity on a Windows server and identify the attack source, affected accounts, malicious processes, and network indicators.

### Workflow

```text
Data Collection
      ↓
Initial Triage
      ↓
Log Analysis
      ↓
Timeline Creation
      ↓
Indicator Extraction
      ↓
Impact Assessment
      ↓
Remediation
```

### Tools Used

| Tool | Purpose |
|---|---|
| Splunk | Searching and correlating logs |
| Sysmon | Process and network telemetry |
| Wireshark | Network traffic analysis |
| VirusTotal | Threat-intelligence lookup |

### Key Findings

- Finding one
- Finding two
- Finding three

### Evidence

Add screenshots, commands, diagrams, or log excerpts here.

```bash
# Example investigation command
vol -f memory.mem windows.pslist
```

### Lessons Learned

- Technical lesson
- Investigation lesson
- Tool-related lesson
- Improvement for future work

### Remediation

- Apply the required security update.
- Remove or isolate malicious files.
- Reset compromised credentials.
- Improve logging and monitoring rules.

</details>

---

# 🚩 CTF Writeup Format

Use this table inside your CTF writeup repository.

| Challenge | Event | Category | Main Technique | Tools | Difficulty | Tags | Writeup |
|---|---|---|---|---|---|---|---|
| Challenge Name | Competition Name | Web | JWT secret disclosure and token forgery | Burp Suite, Python | Medium | `#Web` `#JWT` | [Read](LINK) |
| Challenge Name | Competition Name | Forensics | Windows memory analysis | Volatility | Medium | `#Forensics` `#Memory` | [Read](LINK) |
| Challenge Name | Competition Name | Reverse | Static binary analysis | Ghidra, Strings | Easy | `#Reverse` | [Read](LINK) |
| Challenge Name | Competition Name | Pwn | Information leak and buffer overflow | GDB, Pwntools | Hard | `#Pwn` `#BinaryExploitation` | [Read](LINK) |

### Standard CTF Workflow

```text
Challenge Description
        ↓
File or Service Identification
        ↓
Initial Enumeration
        ↓
Hypothesis Development
        ↓
Exploit Development
        ↓
Flag Extraction
        ↓
Root Cause Analysis
        ↓
Remediation
```

---

# 🛡️ SOC and Forensics Case Study Format

| Case | Data Source | Investigation | Findings | Tools | Tags | Report |
|---|---|---|---|---|---|---|
| Suspicious RDP Activity | Windows Security Logs | Authentication timeline and source-IP analysis | Multiple failed logins followed by a successful session | Splunk, Sysmon | `#SOC` `#RDP` `#ThreatHunting` | [Read](LINK) |
| Malicious Process Investigation | Memory Dump | Process, network, and parent-child analysis | Suspicious executable communicating with a C2 server | Volatility, VirusTotal | `#Forensics` `#MalwareAnalysis` | [Read](LINK) |
| Honeypot Investigation | IIS and Windows Logs | Attack reconstruction and IOC extraction | Scanning, brute force, and malicious tool execution | Splunk, Wireshark | `#Honeypot` `#IncidentResponse` | [Read](LINK) |

### Investigation Workflow

```text
Alert
  ↓
Validation
  ↓
Scoping
  ↓
Evidence Collection
  ↓
Timeline Analysis
  ↓
IOC Extraction
  ↓
Containment Recommendation
  ↓
Incident Report
```

---

# 🏆 Achievements

| Achievement | Event or Organisation | Year | Evidence |
|---|---|---:|---|
| Champion | UiTM UCC Cyberheroes Internal CTF | 2026 | [View achievement](LINK) |
| Completed Security Lab | Platform Name | 2026 | [View profile](LINK) |
| Project Presentation | Organisation or University | 2026 | [View project](LINK) |

---

# 📊 GitHub Activity

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=elgolemite&show_icons=true&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=elgolemite&layout=compact&hide_border=true)

---

# 📚 Currently Learning

- Active Directory attack-path analysis
- Windows memory forensics
- Malware analysis
- Detection engineering
- Security automation with Python

---

# 📫 Connect With Me

| Platform | Link |
|---|---|
| GitHub | [github.com/elgolemite](https://github.com/elgolemite) |
| Portfolio | [elgolemite.github.io](https://elgolemite.github.io) |
| LinkedIn | [LinkedIn Profile](YOUR_LINKEDIN_LINK) |
| Email | `YOUR_EMAIL` |

---

> **Learn → Test → Break → Investigate → Document → Improve**
