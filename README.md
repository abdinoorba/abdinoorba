# Abdinoor Ahmed
### IT Support & SOC Analyst | Help Desk · End-User Support · Microsoft Sentinel · KQL · Threat Detection
**Security+ · Network+ · SC-200 · FortiSIEM**

<p align="center">
  <a href="https://www.linkedin.com/in/abdinoorba/">
    <img src="https://img.shields.io/badge/-LinkedIn-0072b1?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://tryhackme.com/p/abdinoorba">
    <img src="https://img.shields.io/badge/-TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white" />
  </a>
  <a href="https://youtube.com/playlist?list=PLKdr5350ySx1TWttCOM86opPQqrrDOjY6&si=2yjRRrnBYkaW0dI8">
    <img src="https://img.shields.io/badge/-YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" />
  </a>
</p>

---

## About Me

Computer Science graduate (Distinction) who combines hands-on enterprise IT support experience with security operations skills, someone who both **keeps users productive** and **helps keep systems secure**.

On the **IT support** side, I resolve day-to-day hardware, software, network, and access issues for staff, administer accounts and enterprise applications, and work tickets through ServiceNow with clear, reusable documentation. On the **security** side, I investigate with SIEM platforms (Microsoft Sentinel, Splunk), write KQL and SPL to surface authentication anomalies and attacker behaviour, and run SOC-style triage and threat hunting mapped to MITRE ATT&CK.

I hold the **CompTIA Security+, Network+, and Microsoft SC-200** certifications and maintain a publicly documented project portfolio covering both a from-scratch Active Directory identity lab and a full range of detection engineering, threat hunting, phishing triage, and SOAR automation work.

**Currently targeting:** IT Support / Service Desk Analyst **and** SOC / Security Analyst (Tier 1) roles in Canada.

---

## What I Bring

**IT Support & Operations**
- First-contact support across ticketing, email, phone, and in-person channels
- Troubleshooting desktops, laptops, mobile devices, printers, and peripherals
- Windows and Microsoft 365 support; account provisioning and access under RBAC / least-privilege
- Application support and deployment (LearnUpon LMS, SharePoint Online)
- Runbooks, how-to guides, and knowledge-base articles; end-user training

**Security Operations**
- SIEM investigation and detection engineering in Microsoft Sentinel and Splunk (KQL / SPL)
- Alert triage, threat hunting, and IOC analysis mapped to MITRE ATT&CK
- Phishing analysis, brute-force and credential-abuse detection, network forensics
- SOAR playbook design and threat-intelligence enrichment automation
- Governance and risk assessment using NIST CSF and ISO 27001

---

## Experience

**IT Systems Analyst** · Métis Nation within Alberta · *May 2026 to Aug 2026*
Delivered first-contact IT support across ticketing, email, phone, and in-person channels; supported and deployed enterprise applications including the LearnUpon LMS and SharePoint Online; created user accounts and managed access control under least-privilege; and built runbooks, knowledge-base articles, and end-user training.

**Engineering Assistant (Application Support)** · Government of Saskatchewan · *May 2024 to Sep 2025*
Provided technical and application support for internal enterprise systems using log-based troubleshooting and root-cause analysis; resolved device, peripheral, and connectivity issues; administered access under RBAC and least-privilege; configured TLS/SSL; and built Power BI dashboards that improved incident visibility and cut manual reporting by about 6 hours per week.

---

## Certifications

| Certification | Issuer |
|---|---|
| CompTIA Security+ | CompTIA |
| CompTIA Network+ | CompTIA |
| Security Operations Analyst Associate (SC-200) | Microsoft |
| FCP FortiSIEM Analyst | Fortinet |
| Splunk: Zero to Power User | Udemy |
| AI Security & Governance | Securiti AI |
| Deloitte Cyber Simulation | Deloitte |
| Datacom Cyber Simulation | Datacom |
| Cloud Fundamentals | Various |

---

## Featured Projects

### Identity & Infrastructure

#### [Windows AD Domain Lab: Identity & Access Control in Azure](https://github.com/abdinoorba/windows-ad-domain-lab)
Deployed an enterprise-style Active Directory environment in Azure implementing DNS-based domain services, user and OU management, and Group Policy enforcement to simulate centralized identity and access control, the same fundamentals behind everyday IT support and account administration.
**Tools:** Azure, Active Directory, DNS, Group Policy

---

### Security Operations & Detection

#### [Microsoft Sentinel: Brute Force Detection & SIEM Investigation](https://youtu.be/kBQqC0ZjxN8?si=n8e0w_nxlwbHuSkL)
Built end-to-end detection in Microsoft Sentinel for brute-force attacks (MITRE T1110). Wrote KQL queries to correlate sign-in failures, identify suspicious authentication patterns, and triage alerts through a structured SOP-based investigation workflow including evidence gathering, log correlation, and documented findings.
**Tools:** Microsoft Sentinel, KQL, Log Analytics, Azure AD  ·  **MITRE:** T1110 | Brute Force

#### [PowerShell Threat Hunting with Microsoft Defender XDR](https://github.com/abdinoorba/powershell-threat-hunting-defender-xdr)
Threat hunting investigation using Microsoft Defender XDR and KQL to identify suspicious PowerShell activity including encoded commands, execution-policy bypass, in-memory execution, and Defender tampering. Includes attacker tradecraft analysis, detection gaps, and full investigation methodology.
**Tools:** Microsoft Defender XDR, KQL, PowerShell  ·  **MITRE:** T1059.001 | PowerShell, T1562 | Impair Defenses

#### [Azure Tor Activity Detection: Cloud Threat Hunting in Sentinel](https://github.com/abdinoorba/azure-tor-activity-detection)
Threat-hunting detection in Microsoft Sentinel identifying Azure control-plane activity originating from Tor exit nodes, indicating potential credential compromise or anonymized administrative abuse.
**Tools:** Microsoft Sentinel, KQL, Azure  ·  **MITRE:** T1090 | Proxy, T1078 | Valid Accounts

#### [Sentinel Incident IP Enrichment Playbook: SOAR Automation](https://youtu.be/GSrQWSGoYVo?si=jyQ7fzjrmOnt97Jr)
Configured and deployed a Sentinel Logic Apps playbook that iterates over IP entities from incidents and performs automated enrichment, demonstrating SOAR workflow design for operationalizing threat intelligence at scale.
**Tools:** Microsoft Sentinel, Logic Apps, REST APIs, JSON

#### [SOC Alert Prioritization: Threat Intelligence Enrichment Workflow](https://github.com/abdinoorba/soc-alert-prioritization)
Built a threat-intelligence-driven enrichment workflow integrating VirusTotal and AbuseIPDB APIs to auto-score and prioritize SOC alerts by severity, reducing manual triage time and surfacing high-fidelity indicators for analyst review.
**Tools:** Python, VirusTotal API, AbuseIPDB API, JSON

#### [Email Phishing Triage & Analysis](https://github.com/abdinoorba/email-phishing-triage)
SOC-style workflow for analyzing phishing attempts using SPF, DKIM, and DMARC header analysis, URL reputation checks, and social-engineering indicator identification. Produced structured, analyst-ready IOC reports.
**Tools:** Email header analysis, VirusTotal, SPF/DKIM/DMARC  ·  **MITRE:** T1566 | Phishing

#### [Splunk Log Analysis: Windows Security Events](https://youtu.be/puZCX9zwwNI?si=AN4IJqCg1u_xLb3K)
Applied SPL-based investigation to detect authentication anomalies, suspicious process execution, and host-based behavioural indicators across Windows security event logs.
**Tools:** Splunk, SPL, Windows Security Events

#### [Web Traffic Investigation & Network Scan Forensics](https://github.com/abdinoorba/web-traffic-investigation)
Network forensics investigation analyzing HTTP patterns, suspicious behaviour, and reconnaissance indicators; identified and validated Nmap scan activity through packet-level analysis.
**Tools:** Wireshark, Nmap, Packet Capture Analysis  ·  **MITRE:** T1046 | Network Service Discovery, T1595 | Active Scanning

#### [Enterprise Risk Assessment](https://github.com/abdinoorba/enterprise-risk-assessment)
Structured governance project assessing business context, threat exposure, controls, and residual risk using NIST CSF methodology, with documented likelihood, impact, and mitigation priorities.
**Frameworks:** NIST CSF, ISO 27001, CVSS

---

## Technical Skills

**IT Support & Service Desk**
End-user support • Hardware / software / network troubleshooting • Windows • Microsoft 365 • Printers & peripherals • ServiceNow ticketing • SLA-based triage & escalation • Onboarding & account provisioning • Knowledge base & documentation • Remote & in-person support

**Identity, Access & Collaboration**
Active Directory • Azure AD • RBAC / least-privilege • SharePoint Online • Power Platform • Account & access administration

**SIEM & Detection**
Microsoft Sentinel • Splunk • KQL • SPL • Log Analytics Workspaces • Detection Rule Development • Alert Monitoring

**Endpoint & Threat Detection**
Microsoft Defender for Endpoint • Microsoft Defender XDR • Sysmon • Windows Event Viewer • Linux Syslog

**Threat Intelligence & Incident Response**
MITRE ATT&CK • IOC Analysis • Alert Triage • Playbook Execution • SOP-based Investigation • Threat Hunting • Phishing Analysis • Incident Escalation

**Network Analysis**
Wireshark • Nmap • Suricata • Packet Capture Analysis • HTTP Traffic Investigation

**Automation & Scripting**
Python • PowerShell • Bash • REST APIs • SOAR Playbooks (Sentinel Logic Apps) • JSON Enrichment

**Cloud & Platforms**
Azure • Microsoft 365 • Docker • Git

**Governance, Risk & Compliance**
NIST CSF • ISO 27001/27002 • SOC 2 • COBIT • Risk Assessment • Gap Analysis • Security Reporting

**Data & Reporting**
Power BI • SQL • Excel • Dashboard Development • Security Metrics Reporting

---

## Connect

[LinkedIn](https://www.linkedin.com/in/abdinoorba/) · [TryHackMe](https://tryhackme.com/p/abdinoorba) · [YouTube](https://youtube.com/playlist?list=PLKdr5350ySx1TWttCOM86opPQqrrDOjY6&si=2yjRRrnBYkaW0dI8) · abdinoorba@gmail.com
