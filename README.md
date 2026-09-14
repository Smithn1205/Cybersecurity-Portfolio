# Cybersecurity Portfolio

Hi, I'm Smith 👋

I'm building my cybersecurity portfolio around the kind of work I want to do professionally: **SOC analysis, incident response, cloud security, and identity / Zero Trust**.

This repository is the main entry point to my hands-on security work. Rather than duplicating my GitHub profile, this page focuses on **what I have built, what I have investigated, and the technical areas I am developing**.

`SOC` `Incident Response` `Cloud Security` `Identity` `Zero Trust`

---

## 🧩 Security Skills

My current technical skill set spans security operations, cloud and identity security, web security, systems, automation, and security governance.

### Security Operations

`Microsoft Sentinel` `Microsoft Defender XDR` `Splunk` `KQL` `SPL` `Log Analysis` `Alert Triage` `Event Correlation` `Incident Response` `Threat Hunting` `MITRE ATT&CK`

**Practical focus:** security alert investigation, log correlation, incident reconstruction, detection logic, threat hunting, containment, remediation, and analyst documentation.

### Cloud & Identity Security

`Microsoft Azure` `AWS` `Microsoft Entra ID` `AWS IAM` `RBAC` `Conditional Access` `MFA` `Least Privilege` `Zero Trust` `SASE`

**Practical focus:** identity controls, access policies, cloud security monitoring, authentication security, and architecture-level security decisions.

### Network & Web Security

`DNS` `TCP/IP` `SSL/TLS` `Cloudflare WAF` `HTTP` `Burp Suite` `OWASP Top 10` `Vulnerability Assessment`

**Practical focus:** network and web traffic analysis, WAF controls, request analysis, vulnerability testing, access-control issues, and security hardening.

### Threat Modelling & Security Engineering

`STRIDE` `DREAD` `PASTA` `Secure SDLC` `DevSecOps` `Risk Assessment` `Security Architecture`

**Practical focus:** identifying attack paths, assessing security risks, evaluating controls, and connecting technical findings to practical mitigations.

### Programming & Automation

`Python` `Bash` `PowerShell` `YAML` `REST APIs` `Azure Logic Apps` `Git` `GitHub`

**Practical focus:** security automation, investigation support, scripting, API-based workflows, and repeatable technical processes.

### Systems & Security Foundations

`Windows` `Linux` `Ubuntu` `Kali` `Network Security` `Technical Documentation` `Incident Documentation`

---

## 🚨 SOC & Incident Response Work

### SOC Incident Response Lab

[**Open the SOC Incident Response Lab →**](https://github.com/Smithn1205/SOC-Incident-Response-Lab)

A self-built collection of SOC-style investigations designed around realistic analyst workflows rather than step-by-step tutorials.

| Investigation | Security focus |
|---|---|
| **SSH Brute Force** | Linux authentication analysis, failed-login patterns, source IP investigation and Sentinel/KQL detection |
| **Suspicious PowerShell** | Windows process activity, command-line evidence and suspicious execution analysis |
| **Windows Authentication Anomaly** | Authentication behaviour, account activity and event correlation |
| **Cloudflare WAF Investigation** | HTTP/WAF activity, suspicious traffic and network-security investigation |

The cases are structured to demonstrate practical investigation work including detection, evidence gathering, timeline reconstruction, ATT&CK mapping, and response considerations.

---

## 🔎 Security Investigation Casework

### KC7 Security Investigations

[**Open the KC7 Security Investigations →**](https://github.com/Smithn1205/KC7-Security-Investigations)

Completed **KC7 Security Analyst I** path with documented investigation case studies covering multiple security-data sources and attack scenarios.

| Case | Investigation areas |
|---|---|
| **CloutHaus** | Authentication, users, hosts, IP addresses and network pivots |
| **A Scandal in Valdoria** | Email activity, process execution, persistence, discovery, collection and exfiltration |
| **VirusTotal Fundamentals** | Malware triage, YARA, sandbox behaviour, certificates, passive DNS and indicators |
| **Jojo's Hospital** | Ransomware investigation, Cobalt Strike, discovery, data staging, exfiltration and cleanup |

**Path status:** `1 path completed`

This work complements the self-built SOC lab by showing structured investigation practice across authentication, endpoint, network, DNS, file, malware and threat-intelligence data.

---

## 🛠️ Selected Security Projects

### Microsoft Azure Security

Hands-on Azure security work combining **Microsoft Sentinel, Defender XDR, Entra ID, KQL and Logic Apps**.

- Integrated security log sources into Microsoft Sentinel.
- Developed KQL-based analytics and investigation queries.
- Investigated security incidents across Sentinel and Defender XDR.
- Configured Entra ID RBAC, Conditional Access and MFA.
- Applied least-privilege and Zero Trust principles to identity controls.
- Automated selected response workflows using Azure Logic Apps.

### Splunk SIEM Lab

Hands-on SIEM work using **Linux, Splunk, SPL, dashboards and threshold-based alerts**.

- Installed and configured Splunk in a Linux environment.
- Onboarded multiple log sources and validated searchable events.
- Wrote SPL queries to investigate and correlate security activity.
- Built dashboards and threshold-based detection alerts.

### Cloudflare Network Security

Security controls implemented on a live website using **Cloudflare DNS, SSL/TLS, WAF, geo-based controls and rate limiting**.

The work focused on balancing security controls with availability and performance while monitoring operational impact.

### Web Security & Vulnerability Testing

Completed **54 PortSwigger Web Security Academy labs** using Burp Suite across common web vulnerability classes including SQL injection, XSS, CSRF, SSRF and access-control issues.

The work involved analysing requests, testing attack hypotheses safely, reproducing vulnerabilities, and developing remediation-focused findings.

### Threat Modelling & DevSecOps

Applied **STRIDE, DREAD and PASTA** to identify attack paths, assess risks and recommend mitigations. Also completed secure SDLC and CI/CD security work covering secrets management, dependency integrity, build security and credential hygiene.

### AI Security & Policy Engineering

Built a Python/Streamlit security-policy application using **RAG, ChromaDB and the Google Gemini API**, grounded in 22+ SANS security-policy templates.

The project combines applied AI engineering with security-policy generation, retrieval grounding and security governance.

---

## 🎓 Certifications & Learning

| Status | Certification / Learning | Relevance |
|---|---|---|
| ✅ | **Microsoft SC-900** | Security, compliance and identity fundamentals |
| ✅ | **KC7 Security Analyst I** | Security investigations and KQL-based analysis |
| 🎯 | **TryHackMe SAL1** | SOC analysis and practical defensive security |
| 🎯 | **Microsoft SC-200** | Security operations, Sentinel, Defender XDR and threat hunting |

My approach is to pair certifications with practical work so that the skills represented here are supported by investigations, labs, queries, or projects wherever possible.

---

## 🔬 Academic Security Research

### SASE vs. Traditional Zero Trust

**M.Sc. Computer Science (Cybersecurity) — SRH University of Applied Sciences, Berlin**

My Master's thesis examines **SASE versus traditional Zero Trust approaches for small and medium-sized enterprises**.

The research connects with several areas represented in this portfolio:

- Zero Trust architecture
- Identity and access security
- Cloud security
- Secure network access
- Security architecture and control selection
- Security trade-offs for SME environments

The thesis adds an architectural and research perspective to the portfolio alongside the more operational SOC and investigation work.

---

## 📊 Evidence Across the Portfolio

| Skill area | Where to see it |
|---|---|
| **KQL / SIEM investigation** | SOC lab + KC7 investigations + Azure security work |
| **Incident response** | SOC investigations + KC7 ransomware case |
| **Threat hunting / detection** | Sentinel, Defender XDR and Splunk projects |
| **Authentication analysis** | SSH brute force + Windows authentication + KC7 |
| **Endpoint / process analysis** | PowerShell investigation + Defender XDR work |
| **Network investigation** | Cloudflare WAF + outbound traffic + C2/exfiltration cases |
| **Malware analysis** | VirusTotal Fundamentals investigation |
| **Cloud security** | Azure security work + AWS experience |
| **Identity security** | Entra ID, RBAC, Conditional Access and MFA |
| **Web security** | PortSwigger labs + Cloudflare security work |
| **Threat modelling** | STRIDE, DREAD, PASTA and DevSecOps work |
| **Automation** | Python, Bash, PowerShell, Logic Apps and REST APIs |
| **Security governance** | Zero Trust research, ISO 27001, GDPR and security-policy work |

---

## 📁 Repository Map

```text
Cybersecurity-Portfolio
│
├── 🛡️ SOC-Incident-Response-Lab
│   └── Self-built SOC & incident-response investigations
│
├── 🔎 KC7-Security-Investigations
│   └── Structured security investigation case studies
│
└── 👤 Smithn1205
    └── Personal GitHub profile and broader cybersecurity overview
```

The repositories intentionally have different roles:

- **Cybersecurity-Portfolio** → evidence hub and technical overview
- **SOC-Incident-Response-Lab** → self-built SOC / IR casework
- **KC7-Security-Investigations** → structured investigation case studies
- **Smithn1205** → personal profile and high-level cybersecurity positioning

---

## 🎯 Current Direction

I am currently building toward a security operations role with a longer-term focus on **cloud and identity security**.

My immediate progression is:

**KC7 Security Analyst I → SAL1 → SC-200 → deeper cloud & identity security**

The goal is to keep expanding from individual investigations into stronger detection, response, threat-hunting, cloud-security and identity-security capabilities.

---

## 🌐 Start Here

**Want to see the actual investigation work?** → [SOC Incident Response Lab](https://github.com/Smithn1205/SOC-Incident-Response-Lab)

**Want to see structured security case studies?** → [KC7 Security Investigations](https://github.com/Smithn1205/KC7-Security-Investigations)

**Want the broader personal overview?** → [Smithn1205 GitHub Profile](https://github.com/Smithn1205/Smithn1205)
