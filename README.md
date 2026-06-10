<div align="center">

```
██████╗  ██████╗  ██████╗ ████████╗@  ██╗  ██╗ █████╗  ██████╗██╗  ██╗███████╗██████╗ ███████╗
██╔══██╗██╔═══██╗██╔═══██╗╚══██╔══╝   ██║  ██║██╔══██╗██╔════╝██║ ██╔╝██╔════╝██╔══██╗██╔════╝
██████╔╝██║   ██║██║   ██║   ██║      ███████║███████║██║     █████╔╝ █████╗  ██████╔╝███████╗
██╔══██╗██║   ██║██║   ██║   ██║      ██╔══██║██╔══██║██║     ██╔═██╗ ██╔══╝  ██╔══██╗╚════██║
██║  ██║╚██████╔╝╚██████╔╝   ██║      ██║  ██║██║  ██║╚██████╗██║  ██╗███████╗██║  ██║███████║
╚═╝  ╚═╝ ╚═════╝  ╚═════╝    ╚═╝      ╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚══════╝
```

<img src="https://readme-typing-svg.herokuapp.com?font=VT323&size=24&duration=2500&pause=800&color=00FF41&center=true&vCenter=true&width=800&lines=root%40arun%3A~%24+whoami;%5B+SOC+Analyst+%26+Threat+Hunter+%5D;%5B+Web+%26+API+Pentester+%5D;%5B+Python+Security+Automation+%5D;%5B+OWASP+Top+10+%7C+API+Top+10+%5D;%5B+Breaking+Things+to+Secure+Them+%5D" />

</div>

---

## `$ cat /etc/profile.d/arun.conf`

```bash
root@arun:~$ id
uid=1337(arun) gid=1337(security) groups=1337(security),0(root),31337(offensive)

root@arun:~$ cat about.txt
┌─────────────────────────────────────────────────────┐
│  NAME    : Arun Chavan                              │
│  ROLE    : SOC Analyst | Offensive Security         │
│  BASE    : India                                    │
│  FOCUS   : Threat Hunting • Web/API Pentesting      │
│  TOOLS   : Burp Suite • Python • Wireshark • Nmap   │
│  STATUS  : [ HUNTING THREATS & BUGS ]               │
└─────────────────────────────────────────────────────┘
```

---

## `$ cat /var/log/soc/skills.log`

```diff
+ [ACTIVE]   SOC Alert Triage & Incident Investigation
+ [ACTIVE]   Threat Hunting & IOC Correlation
+ [ACTIVE]   Phishing Email Analysis & Infrastructure Takedown
+ [ACTIVE]   Log Analysis & SIEM Correlation
+ [ACTIVE]   Network Traffic Forensics & PCAP Analysis
+ [ACTIVE]   Web Application Pentesting
+ [ACTIVE]   API Security Testing (JWT, OAuth, IDOR)
+ [ACTIVE]   Python Security Tool Development
+ [LEARNING] Advanced Red Team Operations
+ [LEARNING] Cloud Security (AWS)
```

---

## `$ cat targets.txt`

```yaml
attack_surface:
  web_security:
    - XSS • SQLi • SSRF • XXE • IDOR • CSRF
    - Authentication & Authorization Bypass
    - Business Logic Vulnerabilities
  api_security:
    - JWT / OAuth Exploitation
    - Mass Assignment • BOLA • BFLA
    - API Recon & Enumeration
  soc_operations:
    - Threat Hunting & Behavioral Analytics
    - Phishing Investigation & OSINT
    - Network Traffic Analysis
    - Log Analysis & Incident Response
    - IOC Enrichment & Threat Intelligence
  automation:
    - Python Security Tooling
    - Bash Scripting & Workflows
    - Node.js SOC Applications
```

---

## `$ ls -la /opt/tools/`

### Pentesting & Recon
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6300?style=for-the-badge&logo=burpsuite&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-00457C?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP-000000?style=for-the-badge&logo=owasp&logoColor=white)

### Languages & Automation
![Python](https://img.shields.io/badge/Python-00FF41?style=for-the-badge&logo=python&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-1a1a1a?style=for-the-badge&logo=gnu-bash&logoColor=00FF41)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![JavaScript](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)

### Platforms
![Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

---

## `$ ls /projects/ --color=always`

### [PhishShield](https://github.com/arunchavan143/phishshield) — Phishing Investigation Dashboard

```
drwxr-xr-x  arun  security  PhishShield/
```

> SOC-style phishing forensics tool. Analyzes suspicious URLs using risk scoring, redirect chain mapping, entropy analysis, and domain intelligence.

```python
TECH_STACK = ["Python", "Streamlit", "Plotly", "NetworkX", "DNS/WHOIS"]
FEATURES   = ["Risk Score Engine", "Redirect Graph", "Entropy Analysis", "GeoIP Intel"]
STATUS     = "[ACTIVE] — SOC Ready"
```

[![View Repo](https://img.shields.io/badge/View_Repo-00FF41?style=for-the-badge&logo=github&logoColor=black)](https://github.com/arunchavan143/phishshield)

---

### [ThreatIntelWorkbench](https://github.com/arunchavan143/ThreatIntelWorkbench) — SOC IOC Investigation Platform

```
drwxr-xr-x  arun  security  ThreatIntelWorkbench/
```

> Multi-source threat intelligence aggregator for IPs, domains, and file hashes. Integrates VirusTotal, AbuseIPDB, Shodan, OTX, URLScan with weighted risk scoring.

```javascript
TECH_STACK = ["Node.js", "Express", "Jest", "Docker"]
INTEL_FEEDS = ["VirusTotal", "AbuseIPDB", "Shodan", "OTX", "URLScan", "MalwareBazaar"]
FEATURES   = ["Risk Scoring", "Audit Logging", "Caching", "Rate Limiting", "Docker"]
STATUS     = "[ACTIVE] — SOC Ready"
```

[![View Repo](https://img.shields.io/badge/View_Repo-00FF41?style=for-the-badge&logo=github&logoColor=black)](https://github.com/arunchavan143/ThreatIntelWorkbench)

---

## `$ cat training_grounds.txt`

| Platform | Mission |
|---|---|
| PortSwigger Academy | Web Application Exploitation |
| OWASP Juice Shop | Realistic VAPT Practice |
| TryHackMe | Networking & SOC Fundamentals |
| Hack The Box | Offensive Security Challenges |

---

## 📊 Operational Metrics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=arunchavan143&show_icons=true&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00FF41&icon_color=00FF41&text_color=c9d1d9&border_radius=10" height="180"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=arunchavan143&theme=chartreuse-dark&hide_border=true&background=0d1117&ring=00FF41&fire=00FF41&currStreakLabel=00FF41&sideNums=00FF41&sideLabels=c9d1d9&dates=c9d1d9&border_radius=10" height="180"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=arunchavan143&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00FF41&text_color=c9d1d9&border_radius=10"/>
</p>

---

<p align="center">
  <img width="100%" src="https://raw.githubusercontent.com/arunchavan143/arunchavan143/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />
</p>

---

## 🌐 3D Contribution Calendar

<p align="center">
  <img src="https://raw.githubusercontent.com/arunchavan143/arunchavan143/main/profile-3d-contrib/profile-green-animate.svg" alt="3D Contribution Calendar" />
</p>

---

## `$ cat /proc/goals/objectives.yml`

```yaml
objectives:
  short_term:
    - Ship TLS Security Scanner tool
    - Publish PortSwigger lab writeups
    - Complete eJPT certification
  long_term:
    - Specialize in Web & API Security
    - Contribute to open-source security tooling
    - Land a role in Offensive Security / Red Team
    - Work remotely on real-world VAPT & SOC ops
```

---

## `$ ping -c1 arun`

<p align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arun-chawan-4a3356362/)
[![GitHub](https://img.shields.io/badge/GitHub-00FF41?style=for-the-badge&logo=github&logoColor=black)](https://github.com/arunchavan143)

</p>

---

<div align="center">

![](https://visitcount.itsvg.in/api?id=arunchavan143&icon=5&color=6)

```
┌──────────────────────────────────────────────────┐
│                                                  │
│   Hack • Learn • Analyze • Exploit • Secure      │
│         [ REPEAT UNTIL HIRED ]                   │
│                                                  │
└──────────────────────────────────────────────────┘
```

</div>
