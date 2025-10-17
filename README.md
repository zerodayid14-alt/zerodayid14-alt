<div align="center">

# 🔐 ZeroDay Indonesia

### Bug Bounty Hunter & Cloud Security Expert

[![GitHub followers](https://img.shields.io/github/followers/zerodayid?style=social)](https://github.com/zerodayid)
[![YouTube](https://img.shields.io/badge/YouTube-@ZeroDayId-red?style=flat&logo=youtube)](https://youtube.com/@ZeroDayId)
[![TikTok](https://img.shields.io/badge/TikTok-@zeroday__id-black?style=flat&logo=tiktok)](https://tiktok.com/@zerodayid)
[![Email](https://img.shields.io/badge/Email-contact-blue?style=flat&logo=gmail)](mailto:contact@zerodayid.com)

**Journey from Zero to Expert | Roadmap 2025-2027**

---

</div>

## 🎯 About This Repository

Repository ini berisi dokumentasi lengkap perjalanan learning saya dari **pemula total** menjadi **Bug Bounty Hunter & Cloud Security Expert** dalam 36 bulan (2025-2027). Semua materi, tools, scripts, dan writeups akan saya share di sini sebagai referensi bagi komunitas.

**📺 Follow konten saya:**
- 🎥 **YouTube**: [@ZeroDayId](https://youtube.com/@ZeroDayId) - Tutorial, Tips & Tricks
- 🎵 **TikTok**: [@zeroday_id](https://tiktok.com/@zerodayid) - Short Security Tips
- 📧 **Email**: contact@zerodayid.com

---

## 🗺️ Learning Roadmap Overview

```
┌─────────────────────────────────────────────────────────────────┐
│  PRE-FUNDAMENTAL (Month 1-4)                                    │
│  ├─ Linux Command Line & System Basics                          │
│  └─ Python for Security                                         │
├─────────────────────────────────────────────────────────────────┤
│  BUG BOUNTY FUNDAMENTAL (Month 5-10)                            │
│  └─ HTTP Basics, OWASP Top 10, XSS, CSRF, Auth                 │
├─────────────────────────────────────────────────────────────────┤
│  BUG BOUNTY INTERMEDIATE (Month 11-16)                          │
│  └─ Advanced XSS, SQLi, SSTI, XXE, SSRF, JWT                   │
├─────────────────────────────────────────────────────────────────┤
│  BUG BOUNTY ADVANCED (Month 17-22)                              │
│  └─ OAuth, WebSockets, HTTP Smuggling, API Security            │
├─────────────────────────────────────────────────────────────────┤
│  CLOUD SECURITY FUNDAMENTAL (Month 11-16)                       │
│  └─ AWS/GCP/Azure Basics, IAM, S3, Container Security          │
├─────────────────────────────────────────────────────────────────┤
│  CLOUD SECURITY ADVANCED (Month 23-28)                          │
│  └─ Multi-Cloud, Zero Trust, CSPM, Compliance                  │
├─────────────────────────────────────────────────────────────────┤
│  CLOUD SECURITY EXPERT (Month 29-34)                            │
│  └─ Architecture, Custom Tools, Enterprise Consulting          │
└─────────────────────────────────────────────────────────────────┘
```

---

## 📚 Phase 1: PRE-FUNDAMENTAL (Month 1-4)

<details>
<summary><b>🐧 Linux Command Line & System Basics</b></summary>

### 🎓 Learning Platforms
- **OverTheWire** - Bandit (Level 0-34), Leviathan (0-8), Natas (0-10)
- **LinuxJourney.com** - Structured curriculum
- **CmdChallenge.com** - Command practice

### 🛠️ Tools & Setup
```bash
# Terminal & Shell
- zsh + oh-my-zsh
- tmux
- WezTerm / Alacritty

# Modern Command Alternatives
- bat (replacement for cat)
- exa/eza (replacement for ls)
- ripgrep (replacement for grep)
- fd (replacement for find)
- tldr (replacement for man)

# File Manager & Editor
- ranger / nnn
- neovim + LazyVim
- VSCode / Cursor
```

### 📖 Books & Resources
- The Linux Command Line - William Shotts
- Linux Basics for Hackers - OccupyTheWeb

### ✅ Practice Output
- [ ] Complete Bandit Level 0-34
- [ ] Complete Leviathan Level 0-8
- [ ] Complete Natas Level 0-10
- [ ] Create personal command cheat sheet
- [ ] Build 3 bash scripts (file organizer, log parser, backup automation)

</details>

<details>
<summary><b>🐍 Python for Security</b></summary>

### 🎓 Learning Platforms
- **Exercism.org** - Python Track (mentored exercises)
- **Codewars** - Python kata (8-6 kyu)
- **Real Python** - Articles & tutorials
- **Automate the Boring Stuff** - Automation focus

### 🛠️ Tools & Libraries
```python
# Python Version & Package Manager
Python 3.12+
uv / rye (modern package managers)

# Essential Libraries
typer, rich          # CLI tools
httpx, requests      # HTTP clients
beautifulsoup4, lxml # Web scraping
pandas               # Data processing
asyncio              # Async programming

# Code Quality
ruff                 # Linting & formatting
black                # Code formatter
```

### 📖 Books & Resources
- Python Crash Course 3rd Edition - Eric Matthes
- Automate the Boring Stuff with Python - Al Sweigart
- Black Hat Python 2nd Edition - Justin Seitz

### ✅ Practice Output
- [ ] Complete 50+ Exercism exercises
- [ ] Complete 30+ Codewars kata (6-7 kyu)
- [ ] Build 5 security tools:
  - Subdomain enumerator
  - HTTP header analyzer
  - Log file parser
  - Port scanner
  - Password strength checker

</details>

---

## 🔐 Phase 2: BUG BOUNTY FUNDAMENTAL (Month 5-10)

<details>
<summary><b>🌐 Web Security Basics</b></summary>

### 🎓 Learning Platforms
| Platform | Focus | Free? |
|----------|-------|-------|
| **PortSwigger Web Security Academy** | HTTP, Auth, XSS, CSRF | ✅ |
| **OWASP Juice Shop** | OWASP Top 10 Hands-on | ✅ |
| **TryHackMe** | Guided Learning Paths | 🟡 Freemium |
| **HackTheBox Academy** | Web Attacks Module | 🟡 Freemium |
| **PentesterLab** | Introduction Badge | ❌ Paid |

### 🛠️ Essential Tools
```bash
# Web Proxy
Burp Suite Community
Caido (free tier)

# Browser Setup
Firefox + FoxyProxy
Wappalyzer (tech detection)
Cookie-Editor
User-Agent Switcher

# Documentation
Obsidian / Notion
Flameshot (Linux screenshots)
ShareX (Windows screenshots)
```

### 📖 Books & Resources
- Bug Bounty Bootcamp (Ch 1-8) - Vickie Li
- OWASP Web Security Testing Guide (WSTG)

### ✅ Practice Output
- [ ] Solve 20+ PortSwigger apprentice labs
- [ ] Complete OWASP Juice Shop 1-2 star (20+ challenges)
- [ ] Complete TryHackMe OWASP Top 10 room
- [ ] Document 10 findings (English writeups)
- [ ] Create personal vulnerability notes

</details>

---

## 🔐 Phase 3: BUG BOUNTY INTERMEDIATE (Month 11-16)

<details>
<summary><b>⚡ Advanced Vulnerabilities</b></summary>

### 🎓 Learning Platforms
- **PortSwigger Academy** - Advanced modules (XSS, SQLi, SSTI, XXE, SSRF)
- **Hack The Box** - Web challenges (easy-medium)
- **PentesterLab** - XSS, SQLi, GraphQL badges
- **Intigriti Labs** - Modern web challenges
- **Root-Me** - Web Server & Client challenges
- **DVWA** - Local practice environment

### 🛠️ Advanced Tools
```bash
# Web Proxies
Burp Suite Pro ($449/year)
Caido Pro

# Exploitation Tools
sqlmap, ghauri           # SQL injection
ffuf, feroxbuster       # Fuzzing/discovery
dalfox, XSStrike        # XSS testing
jwt_tool, jwt-hack      # JWT attacks

# GraphQL Testing
graphw00f
clairvoyance
InQL (Burp extension)

# Reconnaissance
subfinder, assetfinder, amass
```

### 📖 Books & Resources
- Bug Bounty Bootcamp (Ch 9-18) - Vickie Li
- Real-World Bug Hunting - Peter Yaworski
- PortSwigger Research Papers

### ✅ Practice Output
- [ ] Solve 50+ PortSwigger practitioner labs
- [ ] Complete 10+ HTB easy-medium web boxes
- [ ] Start public bug bounty (VDP programs)
- [ ] Submit 20+ valid bugs (any severity)
- [ ] Earn first bounty ($50-500)
- [ ] Publish 5+ writeups (Medium/blog)

</details>

---

## 🔐 Phase 4: BUG BOUNTY ADVANCED (Month 17-22)

<details>
<summary><b>🚀 Cutting-Edge Techniques</b></summary>

### 🎓 Learning Platforms
- **PortSwigger Academy** - Expert modules (OAuth, WebSockets, HTTP/2 Smuggling)
- **Hack The Box Pro Labs** - API-heavy challenges
- **API Security University** (APIsec.ai) - OWASP API Top 10 2023
- **Kontra Application Security** - Modern API challenges
- **Pentester Academy** - Advanced Web Attacks

### 🛠️ Full Recon Stack
```bash
# Subdomain Discovery
subfinder, assetfinder, amass

# HTTP Probing & Crawling
httpx
katana, gospider

# JavaScript Analysis
nuclei, gau, waybackurls, getJS

# Parameter Discovery
arjun, x8, ParamSpider

# API Testing
Postman, Insomnia          # GUI
httpie, curlie             # CLI
graphw00f, clairvoyance    # GraphQL
grpcurl, grpcui            # gRPC

# Fuzzing & Automation
ffuf, wfuzz
nuclei (custom templates)
SecLists, assetnote wordlists
```

### 📖 Books & Resources
- API Security in Action - Neil Madden
- OWASP API Security Top 10 (2023)
- Bug Bounty Playbook v3 - Jason Haddix
- PortSwigger Research: "Browser-Powered Desync", "HTTP/2 Smuggling"

### ✅ Practice Output
- [ ] Complete 30+ PortSwigger expert labs
- [ ] Complete API Security University course
- [ ] Access private programs (build reputation)
- [ ] Submit 50+ bugs (focus medium-high severity)
- [ ] Build automation pipeline (recon → scan → report)
- [ ] Publish 10+ advanced writeups
- [ ] Create 5+ custom nuclei templates

</details>

---

## ☁️ Phase 5: CLOUD SECURITY FUNDAMENTAL (Month 11-16)

<details>
<summary><b>☁️ Cloud Basics & Security</b></summary>

### 🎓 Learning Platforms
| Platform | Focus | Provider |
|----------|-------|----------|
| **AWS Skill Builder** | Cloud Practitioner, IAM, S3 | AWS |
| **GCP Skills Boost** | Cloud Basics, IAM & Security | Google |
| **Azure Learn** | Fundamentals, Security Basics | Microsoft |
| **CloudGoat** | AWS Pentesting Scenarios | Rhino Security |
| **CloudFoxable** | Modern AWS Pentesting | Community |
| **TryHackMe** | AWS Fundamentals, Cloud Intro | Platform |
| **Kubernetes Goat** | Container Security | OWASP |

### 🛠️ Cloud Security Tools
```bash
# CLI Tools
aws-cli v2               # AWS management
gcloud                   # GCP management
az                       # Azure management

# Security Auditing
Prowler v4               # AWS/GCP/Azure audit
ScoutSuite               # Multi-cloud security audit
Steampipe                # Query cloud resources

# Container Security
Trivy                    # Image scanning
Docker Bench             # Docker security audit

# Secrets Detection
Trufflehog v3
Gitleaks
ggshield

# Credential Management
aws-vault                # AWS credentials management
```

### 📖 Books & Resources
- AWS Security - Manning (2022)
- Hacking Kubernetes - O'Reilly (2021)
- CIS Benchmarks: AWS, GCP, Azure (free)

### ✅ Practice Output
- [ ] Setup AWS/GCP/Azure free tier accounts
- [ ] Complete CloudGoat scenarios 1-5
- [ ] Run Prowler/ScoutSuite on test accounts
- [ ] Fix 20+ findings (hands-on hardening)
- [ ] Document S3 bucket security checklist
- [ ] Deploy secure EC2/GCE instance

</details>

---

## ☁️ Phase 6: CLOUD SECURITY INTERMEDIATE (Month 17-22)

<details>
<summary><b>⚡ Advanced Cloud Exploitation</b></summary>

### 🎓 Learning Platforms
- **CloudGoat** - All scenarios (IAM escalation, Lambda abuse)
- **Flaws.cloud & Flaws2.cloud** - AWS pentesting challenges
- **Sadcloud** - Terraform misconfigurations
- **Qwiklabs** - AWS/GCP advanced security labs
- **Azure Defender** - Cloud security workshops
- **Kubernetes Goat** - Advanced K8s challenges

### 🛠️ Advanced Cloud Tools
```bash
# Advanced Auditing
Prowler v4
Steampipe + compliance mods
CloudQuery

# IAM Analysis
PMapper                  # Privilege escalation paths
Cloudsplaining          # IAM risk analysis
IAM Vulnerable          # Testing framework
Pacu                    # AWS exploitation framework

# IaC Security Scanning
Checkov                 # Multi-platform IaC scanner
Terrascan               # Policy as code
tfsec                   # Terraform specific
Snyk IaC                # Commercial option

# Container Security
Trivy                   # Comprehensive scanner
Grype                   # Vulnerability scanner
Syft                    # SBOM generation
Docker Scout            # Docker security

# Kubernetes Security
kube-bench              # CIS benchmark
kube-hunter             # Security assessment
kubescape               # Security platform

# Secrets Detection
Trufflehog, Gitleaks, detect-secrets
```

### 📖 Books & Resources
- Practical Cloud Security - O'Reilly
- Kubernetes Security - O'Reilly (2023)
- Container Security - Liz Rice

### ✅ Practice Output
- [ ] Complete all CloudGoat scenarios
- [ ] Complete Flaws.cloud & Flaws2.cloud
- [ ] Build IaC (Terraform) for secure AWS environment
- [ ] Implement least-privilege IAM policies (5+ examples)
- [ ] Setup secure CI/CD pipeline with scanning
- [ ] Harden Kubernetes cluster (CIS benchmark)
- [ ] First cloud consulting gigs ($500-2k total)

</details>

---

## ☁️ Phase 7: CLOUD SECURITY ADVANCED & EXPERT (Month 23-34)

<details>
<summary><b>🏆 Enterprise-Grade Cloud Security</b></summary>

### 🎓 Learning Platforms
- **AWS Workshops** - Security Logging, Organizations & SCP
- **GCP Security Command Center** - Threat detection
- **Azure Defender for Cloud** - CSPM, threat protection
- **CNCF Projects** - Falco, OPA, Istio tutorials

### 🛠️ Enterprise Tools
```bash
# Policy Enforcement
Open Policy Agent (OPA) + Gatekeeper
Kyverno (K8s native)
HashiCorp Sentinel
Cloud Custodian (AWS)

# Runtime Security
Falco (CNCF)
Cilium (eBPF)

# CSPM Stack (Custom)
CloudQuery               # Data collection
Steampipe                # SQL queries
PostgreSQL               # Storage
Grafana                  # Visualization

# Service Mesh
Istio
Linkerd

# Zero Trust
SPIFFE/SPIRE
Pomerium
Cloudflare Access

# Multi-Cloud Architecture
AWS Control Tower
GCP Resource Manager
Azure Landing Zones
Terraform + OPA
```

### 📖 Books & Resources
- Cloud Native Security - O'Reilly (2023)
- AWS Well-Architected Framework
- Container Security - Liz Rice
- AWS Security Reference Architecture
- Google Cloud Security Foundations
- NIST SP 800-53 Rev 5
- CNCF Security Whitepaper (2024)

### ✅ Practice Output
- [ ] Build compliance dashboard (CIS mapping)
- [ ] Implement SCP/Azure Policy guardrails
- [ ] Setup Falco + Grafana (runtime monitoring)
- [ ] DevSecOps pipeline (Gitleaks → Checkov → Trivy → Prowler)
- [ ] Design multi-account architecture
- [ ] Implement Zero Trust networking
- [ ] Build open-source CSPM alternative
- [ ] Consulting: enterprise clients ($5k-15k projects)
- [ ] Speaking: AWS re:Invent, KubeCon (CFP submissions)

</details>

---

## 🌍 ENGLISH PROFICIENCY (Parallel Track)

<details>
<summary><b>📚 English Learning Roadmap</b></summary>

### 🎯 Target Progression
```
Month 1-6   → TOEFL 60-70  / IELTS 5.0-5.5  (Basic)
Month 7-12  → TOEFL 75-85  / IELTS 6.0-6.5  (Intermediate)
Month 13-18 → TOEFL 90-100 / IELTS 7.0-7.5  (Advanced)
Month 19-24 → Professional Fluency           (Expert)
```

### 🎓 Learning Resources
```bash
# Daily Practice (30min-2h)
Duolingo / Babbel
Anki (spaced repetition)
ELSA Speak (pronunciation)

# Structured Learning
BBC Learning English
English Grammar in Use (Cambridge)
4000 Essential English Words

# Test Preparation
TOEFL Official Guide (ETS)
IELTS Cambridge Practice Tests
Preply / iTalki (1-on-1 tutors)

# Immersion
Security Now podcast
Darknet Diaries
TED Talks (cybersecurity)
Conference talks (Black Hat, DEF CON)
```

### ✅ Practice Output
- [ ] Write all bug reports in English
- [ ] Publish blog posts in English
- [ ] Record YouTube tutorials in English
- [ ] Take TOEFL/IELTS (Month 18)
- [ ] Network with international community

</details>

---

## 🛠️ Complete Tools Arsenal

<table>
<tr>
<td width="50%">

### 🔍 Reconnaissance
```bash
subfinder
assetfinder
amass
httpx
katana
gospider
nuclei
gau
waybackurls
```

</td>
<td width="50%">

### 💥 Exploitation
```bash
Burp Suite Pro
Caido
sqlmap
ffuf
dalfox
jwt_tool
graphw00f
grpcurl
```

</td>
</tr>
<tr>
<td>

### ☁️ Cloud Security
```bash
aws-cli
gcloud
az
Prowler v4
ScoutSuite
Trivy
Steampipe
CloudQuery
Falco
```

</td>
<td>

### 🐍 Python Security
```bash
Python 3.12+
uv / rye
typer, rich
httpx, requests
beautifulsoup4
asyncio
ruff, black
```

</td>
</tr>
</table>

---

## 📊 Learning Progress Tracker

### 🎯 Current Phase
```
[████████░░░░░░░░░░░░] Month 4/36 - Pre-Fundamental
```

### ✅ Completed Milestones
- [ ] Bandit 0-34 ✅
- [ ] 50+ Exercism exercises ⏳
- [ ] First bug bounty ❌
- [ ] TOEFL 95+ ❌
- [ ] First cloud consulting ❌

### 📈 Stats (Updated Weekly)
| Metric | Target | Current |
|--------|--------|---------|
| Bugs Submitted | 100+ | 0 |
| Bounties Earned | $10k+ | $0 |
| Writeups Published | 20+ | 0 |
| GitHub Stars | 500+ | 0 |
| YouTube Subscribers | 1k+ | 0 |

---

## 💰 Support My Journey

<div align="center">

### ☕ Dukung Pembelajaran Saya

Jika konten dan materi yang saya bagikan bermanfaat, dukungan kecil Anda sangat berarti!  
Setiap kontribusi akan digunakan untuk biaya tools, platform, dan sumber belajar.

[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/zerodayid)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/zerodayid)
[![GitHub Sponsors](https://img.shields.io/badge/GitHub_Sponsors-EA4AAA?style=for-the-badge&logo=github-sponsors&logoColor=white)](https://github.com/sponsors/zerodayid)
[![Buy Me A Coffee](https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/zerodayid)

**💝 Terima kasih kepada semua supporter yang telah membantu perjalanan learning saya!**

</div>

---

## 📞 Connect With Me

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-@zerodayid-181717?style=for-the-badge&logo=github)](https://github.com/zerodayid)
[![YouTube](https://img.shields.io/badge/YouTube-@ZeroDayId-FF0000?style=for-the-badge&logo=youtube)](https://youtube.com/@ZeroDayId)
[![TikTok](https://img.shields.io/badge/TikTok-@zeroday__id-000000?style=for-the-badge&logo=tiktok)](https://tiktok.com/@zerodayid)
[![Email](https://img.shields.io/badge/Email-contact@zerodayid.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@zerodayid.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ZeroDay_Indonesia-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/zerodayid)
[![Twitter](https://img.shields.io/badge/Twitter-@zerodayid-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/zerodayid)

</div>

---

<div align="center">

### 📚 Repository Structure (Coming Soon)

```
zerodayid/
├── learning/           # Materi pembelajaran & catatan
├── scripts/            # Security tools & automation scripts
├── writeups/           # Bug bounty writeups
├── labs/              # Lab exercises & solutions
├── cheatsheets/       # Command & technique references
└── resources/         # Curated learning resources
```

**⭐ Star repo ini untuk mengikuti progress pembelajaran saya!**

---

*Last Updated: January 2025 | Roadmap v3.0*  
*© 2025 ZeroDay Indonesia | Journey from Zero to Expert*

</div>
