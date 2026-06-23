# Abdinoor Ahmed | SOC Analyst | Threat Detection & Security Operations | Microsoft Sentinel | KQL | SC-200 | Security+

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

SOC-focused security analyst with hands-on experience in SIEM investigation, threat detection, and detection engineering using Microsoft Sentinel, Splunk, and KQL. I build detection rules, write KQL queries to surface authentication anomalies and attacker behaviour, and document investigation workflows that mirror real Tier 1 SOC processes.

I hold the SC-200 (Security Operations Analyst Associate), CompTIA Security+, and CompTIA Network+ certifications and maintain a publicly documented security project portfolio covering threat hunting, phishing triage, brute force detection, network forensics, cloud anomaly detection, and automated Sentinel enrichment playbooks.

Backed by real-world enterprise IT experience in government environments including RBAC implementation, TLS/SSL configuration, log-based root cause analysis, and security dashboard development.

**Currently targeting:** SOC Analyst, Triage Analyst, and Threat Analyst Level 1 roles in Canada.

---

## Certifications

| Certification | Issuer |
|---|---|
| Security Operations Analyst Associate (SC-200) | Microsoft |
| CompTIA Security+ | CompTIA |
| CompTIA Network+ | CompTIA |
| FCP FortiSIEM Analyst | Fortinet |
| Splunk: Zero to Power User | Udemy |
| AI Security & Governance | Securiti AI |
| Deloitte Cyber Simulation | Deloitte |
| Datacom Cyber Simulation | Datacom |
| Cloud Fundamentals | Various |

---

## Featured Projects

### [Microsoft Sentinel: Brute Force Detection & SIEM Investigation](https://youtu.be/kBQqC0ZjxN8?si=n8e0w_nxlwbHuSkL)
Built end-to-end detection in Microsoft Sentinel for brute-force attacks (MITRE T1110). Wrote KQL queries to correlate sign-in failures, identify suspicious authentication patterns, and triage alerts through a structured SOP-based investigation workflow including evidence gathering, log correlation, and documented findings.

**Tools:** Microsoft Sentinel, KQL, Log Analytics, Azure AD
**MITRE ATT&CK:** T1110 | Brute Force

---

### [PowerShell Threat Hunting with Microsoft Defender XDR](https://github.com/abdinoorba/powershell-threat-hunting-defender-xdr)
Threat hunting investigation using Microsoft Defender XDR and KQL to identify suspicious PowerShell activity including encoded commands, execution policy bypass, in-memory execution, and Microsoft Defender tampering techniques. Includes attacker tradecraft analysis, detection gaps, and full investigation methodology.

**Tools:** Microsoft Defender XDR, KQL, PowerShell
**MITRE ATT&CK:** T1059.001 | PowerShell, T1562 | Impair Defenses

---

### [Azure Tor Activity Detection: Cloud Threat Hunting in Sentinel](https://github.com/abdinoorba/azure-tor-activity-detection)
Threat-hunting detection in Microsoft Sentinel identifying Azure control-plane activity originating from Tor exit nodes, indicating potential credential compromise or anonymized administrative abuse. Mapped to MITRE ATT&CK for adversary behaviour context.

**Tools:** Microsoft Sentinel, KQL, Azure
**MITRE ATT&CK:** T1090 | Proxy, T1078 | Valid Accounts

---

### [Sentinel Incident IP Enrichment Playbook: SOAR Automation](https://youtu.be/GSrQWSGoYVo?si=jyQ7fzjrmOnt97Jr)
Configured and deployed a Sentinel Logic Apps playbook that iterates over IP entities from incidents and performs automated enrichment, demonstrating SOAR workflow design for operationalizing threat intelligence at scale.

**Tools:** Microsoft Sentinel, Logic Apps, REST APIs, JSON

---

### [SOC Alert Prioritization: Threat Intelligence Enrichment Workflow](https://github.com/abdinoorba/soc-alert-prioritization)
Built a threat-intelligence-driven enrichment workflow integrating VirusTotal and AbuseIPDB APIs to auto-score and prioritize SOC alerts by severity, reducing manual triage time and surfacing high-fidelity indicators for analyst review.

**Tools:** Python, VirusTotal API, AbuseIPDB API, JSON

---

### [Email Phishing Triage & Analysis](https://github.com/abdinoorba/email-phishing-triage)
SOC-style workflow for analyzing phishing attempts using SPF, DKIM, and DMARC authentication header analysis, URL reputation checks, and social engineering indicator identification. Produced structured analyst-ready IOC reports.

**Tools:** Email header analysis, VirusTotal, SPF/DKIM/DMARC
**MITRE ATT&CK:** T1566 | Phishing

---

### [Splunk Log Analysis: Windows Security Events](https://youtu.be/puZCX9zwwNI?si=AN4IJqCg1u_xLb3K)
Applied SPL-based investigation to detect authentication anomalies, suspicious process execution, and host-based behavioural indicators across Windows security event logs.

**Tools:** Splunk, SPL, Windows Security Events

---

### [Windows AD Domain Lab: Identity & Access Control in Azure](https://github.com/abdinoorba/windows-ad-domain-lab)
Deployed an enterprise-style Active Directory environment in Azure implementing DNS-based domain services, user and OU management, and Group Policy enforcement to simulate centralized identity and access control.

**Tools:** Azure, Active Directory, DNS, Group Policy

---

### [Web Traffic Investigation & Network Scan Forensics](https://github.com/abdinoorba/web-traffic-investigation)
Network forensics investigation analyzing HTTP patterns, suspicious behaviour, and indicators of reconnaissance. Identification and validation of Nmap scan activity through packet-level analysis and attacker behaviour interpretation.

**Tools:** Wireshark, Nmap, Packet Capture Analysis
**MITRE ATT&CK:** T1046 | Network Service Discovery, T1595 | Active Scanning

---

### [Enterprise Risk Assessment](https://github.com/abdinoorba/enterprise-risk-assessment)
Structured governance project assessing business context, threat exposure, controls, and residual risk using NIST CSF methodology. Evaluated likelihood and impact of identified risks with documented mitigation priorities.

**Frameworks:** NIST CSF, ISO 27001, CVSS

---

## Technical Skills

### SIEM & Detection
Microsoft Sentinel • Splunk • KQL • SPL • Log Analytics Workspaces • Detection Rule Development • Alert Monitoring

### Endpoint & Identity
Microsoft Defender for Endpoint • Microsoft Defender XDR • Sysmon • Windows Event Viewer • Linux Syslog • Azure AD

### Threat Intelligence & IR
MITRE ATT&CK • IOC Analysis • Alert Triage • Playbook Execution • SOP-based Investigation • Threat Hunting • Phishing Analysis • Incident Escalation

### Network Analysis
Wireshark • Nmap • Suricata • Packet Capture Analysis • HTTP Traffic Investigation

### Automation & Scripting
Python • PowerShell • Bash • REST APIs • SOAR Playbooks (Sentinel Logic Apps) • JSON Enrichment

### Cloud & Platforms
Azure • Microsoft 365 • SharePoint • Power Platform • ServiceNow • Docker • Git

### Governance, Risk & Compliance
NIST CSF • ISO 27001/27002 • SOC 2 • COBIT • Risk Assessment • RBAC • Gap Analysis • Security Reporting

### Data & Reporting
Power BI • SQL • Excel • Dashboard Development • Security Metrics Reporting

---

## Connect

[LinkedIn | Abdinoor Ahmed](https://www.linkedin.com/in/abdinoorba/)
