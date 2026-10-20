
# 🛡️ Threat Intelligence Capstone Project
## Threat Actor Profiling and Risk Assessment for Novacore Financial Services

![Cyber Threat Intelligence](https://img.shields.io/badge/Cybersecurity-Threat%20Intelligence-0A66C2)
![MITRE ATT&CK](https://img.shields.io/badge/Framework-MITRE%20ATT%26CK-red)
![Risk Assessment](https://img.shields.io/badge/Risk%20Assessment-High%20Risk-orange)
![Project](https://img.shields.io/badge/Project-Capstone-success)
![Sector](https://img.shields.io/badge/Industry-Financial%20Services-blue)
![Status](https://img.shields.io/badge/Status-Research%20Completed-brightgreen)

**Author:** Qhubekani Luphahla  
**Role:** Threat Intelligence Analyst  
**Project Cohort:** April 2026  
**Report Date:** 17 July 2026  
**Case Study Organisation:** Novacore Financial Services  
**Geographical Focus:** United Kingdom / European Economic Area  
**Primary Threat Actor:** Scattered Spider (UNC3944 / 0ktapus)

---

## 📌 Executive Overview

Cyber threats against financial institutions continue to evolve, with financially motivated threat actors increasingly exploiting human vulnerabilities, compromised identities, cloud infrastructure, and weaknesses in authentication processes.

This capstone project presents a structured Cyber Threat Intelligence (CTI) assessment of **Novacore Financial Services**, a fictional mid-sized financial technology organisation operating in the United Kingdom.

The research evaluates five financially motivated cyber threat groups to determine which poses the greatest potential risk to Novacore's payment processing systems, digital wallet infrastructure, customer information, and business operations.

Following comparative threat analysis, **Scattered Spider (UNC3944)** was selected as the priority threat actor because its reported tactics, techniques, and procedures (TTPs) closely align with the organisation's assumed technology environment and security exposure.

The assessment uses the MITRE ATT&CK framework to examine attacker behaviour, evaluate potential business impacts, and recommend preventive, detective, and incident response controls.

### Key Finding

> **Overall Risk Rating: HIGH**
>
> The assessment identifies credential compromise, social engineering, helpdesk manipulation, and unauthorised cloud access as significant threats to Novacore Financial Services.
>
> The highest-priority defensive recommendations are phishing-resistant multi-factor authentication and stronger identity verification procedures for account recovery and access changes.

---

## 🎯 Project Objectives

The primary objective was to conduct an evidence-informed threat intelligence assessment that supports cybersecurity risk management and defensive decision-making.

Specific objectives included:

1. Identify financially motivated cyber threat actors relevant to UK and European financial institutions.
2. Research five threat groups and document their motivations, targets, tools, and TTPs.
3. Compare the threat actors based on sector targeting, regional relevance, and attack methodologies.
4. Select the threat actor presenting the greatest potential risk to Novacore.
5. Map relevant attacker behaviour to the MITRE ATT&CK framework.
6. Examine historical and more recent publicly reported attack campaigns.
7. Evaluate the likelihood and potential impact of a successful cyberattack.
8. Recommend preventive, detective, and incident response measures.
9. Communicate intelligence findings in a format suitable for security teams and organisational leadership.

---

## 🏦 Business Context

### About Novacore Financial Services

Novacore Financial Services is a fictional fintech organisation used as the case study for this assessment.

The organisation is assumed to provide:

- Online payment processing
- Digital wallet services
- Merchant account management
- SME business onboarding
- Customer identity verification
- Financial transaction management

### Critical Information Assets

| Asset | Potential Security Concern |
|---|---|
| Customer personal information | Data theft and privacy breaches |
| Payment card information | Payment fraud and financial exposure |
| Bank account records | Unauthorised financial activity |
| Digital wallet platforms | Account takeover and service disruption |
| Cloud identity systems | Credential compromise and privilege abuse |
| Merchant transaction records | Fraud, manipulation, and information theft |
| Business verification documents | Identity theft and impersonation |

### Problem Statement

Fintech organisations process sensitive financial information and depend heavily on interconnected digital systems.

Their security exposure can increase when attackers exploit:

- Phishing and social engineering
- Weak authentication and account recovery procedures
- Compromised employee credentials
- Misconfigured cloud access controls
- Unmonitored administrative activities
- Third-party security weaknesses
- Insufficient detection and incident response capabilities

**The central research question was:**

> Which financially motivated cyber threat actor presents the greatest potential risk to Novacore Financial Services, and which defensive measures should be prioritised to reduce that risk?

---

## 🔎 Research Methodology

The project followed a structured threat intelligence workflow.

### Phase 1 — Define Intelligence Requirements

Six intelligence questions were developed to guide the research, focusing on attacker motivations, financial sector targeting, regional activity, TTPs, and defensive priorities.

### Phase 2 — Threat Actor Identification

Five financially motivated threat groups were selected for investigation.

### Phase 3 — Threat Actor Profiling

Each group was examined using the following categories:

- Known aliases
- Primary motivations
- Common targets
- Regional relevance
- Tools and malware
- Tactics, techniques, and procedures
- MITRE ATT&CK mappings
- Relevance to Novacore

### Phase 4 — Comparative Threat Analysis

The five threat groups were compared to identify the most relevant adversary for Novacore's operating environment.

### Phase 5 — Threat Actor Deep Dive

Scattered Spider was selected for further analysis, including its attack methods and publicly reported campaigns.

### Phase 6 — Risk Assessment

The assessment considered the likelihood of an attack, potential operational and financial consequences, and exposed business functions.

### Phase 7 — Defensive Recommendations

Preventive, detective, and response measures were developed to address the identified risks.

### Analytical Workflow

```text
Define Intelligence Requirements
              |
              v
Identify Relevant Threat Actors
              |
              v
Research Threat Actor Profiles
              |
              v
Compare Threat Groups
              |
              v
Select Priority Threat Actor
              |
              v
Map TTPs to MITRE ATT&CK
              |
              v
Review Reported Attack Campaigns
              |
              v
Assess Organisational Risk
              |
              v
Recommend Security Controls
              |
              v
Produce Intelligence Report
```

---

## 🕵️ Threat Actor Profiles

Five threat groups were researched and evaluated.

| Threat Group | Primary Threat | Regional Relevance | Project Assessment |
|---|---|---|---|
| Scattered Spider | Social engineering, credential theft, cloud compromise | High | Priority threat |
| BlackCat / ALPHV | Ransomware and data extortion | High | Highly relevant |
| FIN7 | Financial data theft and payment system compromise | Medium | Limited relevance |
| TA551 / Shathak | Phishing and malware distribution | High | Lower direct relevance |
| LockBit 3.0 | Ransomware and operational disruption | High | Highly relevant |

### Three Most Relevant Groups

**1. Scattered Spider**

Selected as the highest-priority threat because of its identity-focused attack methods, social engineering capabilities, and relevance to cloud-dependent financial services.

**2. BlackCat / ALPHV**

Identified as a significant ransomware and data extortion threat, with potentially severe financial and reputational consequences.

**3. LockBit 3.0**

Identified as a significant ransomware threat capable of causing major business disruption.

---

## 🚨 Selected Threat Actor: Scattered Spider

### Threat Actor Overview

**Name:** Scattered Spider  
**Aliases:** UNC3944, 0ktapus, Opal Ring  
**Primary Motivation:** Financial gain  
**Key Attack Methods:** Social engineering, phishing, credential compromise, authentication bypass, and unauthorised access.

Scattered Spider is a financially motivated cybercriminal group known for sophisticated social engineering and identity-focused intrusion techniques.

The group's reported operations include impersonating employees, targeting IT support teams, compromising credentials, and exploiting authentication and account recovery processes.

### Why Scattered Spider?

The assessment selected Scattered Spider because:

- Its methods are relevant to cloud-dependent organisations.
- It uses phishing and impersonation to gain initial access.
- It targets authentication and identity management weaknesses.
- It exploits helpdesk and account recovery procedures.
- Compromised accounts can provide access to sensitive financial systems.
- Its activities can facilitate data theft, extortion, and ransomware-related impacts.

### Potential Attack Chain

```text
Reconnaissance
      |
      v
Employee Information Gathering
      |
      v
SMS / Email Phishing
      |
      v
Credential Theft
      |
      v
Helpdesk Social Engineering
      |
      v
Authentication / Access Abuse
      |
      v
Unauthorised Cloud Access
      |
      v
Internal Discovery and Lateral Movement
      |
      v
Sensitive Data Access / Exfiltration
      |
      v
Potential Ransomware or Extortion
```

This is a conceptual attack sequence based on the TTPs analysed in the report, not a record of an intrusion into Novacore.

---

## 🧩 MITRE ATT&CK Mapping

The project used the MITRE ATT&CK framework to relate documented threat actor behaviour to recognised adversary techniques.

| Technique ID | Technique | Security Relevance |
|---|---|---|
| T1566.001 | Spearphishing Attachment | Initial access through malicious communications |
| T1078 | Valid Accounts | Unauthorised access using compromised credentials |
| T1021.002 | SMB/Windows Admin Shares | Lateral movement through remote services |
| T1486 | Data Encrypted for Impact | Ransomware-related business disruption |

**Important:** The report associates T1566.001 with spearphishing links. MITRE classifies T1566.001 as *Spearphishing Attachment*; spearphishing links are classified as T1566.002. The mapping should be reconciled before publishing a final verified ATT&CK matrix.

The report also discusses authentication bypass, malicious user execution, and data exfiltration as relevant behaviours.

### ATT&CK Framework

[Explore MITRE ATT&CK](https://attack.mitre.org/)

### Value of ATT&CK Mapping

The framework helps defenders:

- Understand adversary behaviour
- Categorise intrusion techniques
- Identify security monitoring opportunities
- Prioritise detection engineering
- Link threat intelligence to defensive controls
- Communicate threats using consistent terminology

---

## 📚 Attack Campaign Analysis

The project examined two campaign scenarios discussed in the capstone report.

### Case Study 1: Global Cloud and SaaS Provider Campaign

**Period:** Mid-2022 to early 2023  
**Threat Actor:** Scattered Spider  
**Sector:** Cloud communications and SaaS

The report describes an intrusion sequence involving:

1. SMS and email phishing.
2. Credential and session token theft.
3. Impersonation of employees.
4. Social engineering of IT helpdesk personnel.
5. Unauthorised access to administrative systems.
6. Potential ransomware-related extortion.

**Key Lesson:**

Technical authentication controls must be supported by robust identity verification and secure helpdesk processes.

### Case Study 2: UK Financial Services Targeting

**Period Discussed:** October 2024 to March 2025  
**Threat Actor:** Scattered Spider  
**Sector:** UK financial services and fintech

The report discusses a campaign involving:

- Targeted phishing
- Fake authentication portals
- Credential compromise
- IT support impersonation
- Attempts to access financial systems
- Potential exposure of merchant information

**Key Lesson:**

Cloud access monitoring, phishing-resistant authentication, and strict support-team identity verification are important defensive priorities.

**Research Note:** These campaign descriptions are drawn from the submitted capstone report. Specific incident attribution and the cited advisory titles should be independently verified against primary publications before being presented as confirmed incidents.

---

## 📊 Risk Assessment

### Overall Assessment

**Final Risk Rating: HIGH**

The project assessed Scattered Spider as a high-priority threat to Novacore based on the organisation's assumed exposure and the group's documented attack methods.

### Likelihood Assessment

**Likelihood: High**

Factors considered:

- Relevance of financial services to the threat actor
- Cloud-dependent business operations
- Exposure to phishing and impersonation
- Dependence on employee credentials
- Potential weaknesses in identity verification

### Potential Business Impact

| Risk Area | Potential Consequence |
|---|---|
| Identity compromise | Unauthorised account access |
| Financial systems | Fraudulent transactions |
| Data security | Customer and merchant data breaches |
| Business continuity | Service interruption |
| Ransomware | System encryption and extortion |
| Compliance | Regulatory investigation and potential penalties |
| Reputation | Loss of customer confidence |

### Most Exposed Business Functions

1. Staff email and cloud accounts
2. IT support and helpdesk teams
3. Customer service and onboarding
4. Payment processing systems
5. Digital wallet infrastructure
6. Cloud identity and access management
7. Customer and transaction databases

The risk assessment is qualitative and based on a fictional organisational environment. It does not represent a measured vulnerability assessment of a live company.

---

## 🛡️ Security Recommendations

The project produced recommendations across three defensive areas.

### 1. Preventive Controls

- Deploy phishing-resistant FIDO2 multi-factor authentication.
- Strengthen helpdesk identity verification.
- Restrict unauthorised email forwarding rules.
- Apply least-privilege access principles.
- Disable legacy authentication protocols.
- Conduct regular phishing awareness training.
- Maintain timely security patching.

### 2. Detection Controls

- Monitor suspicious authentication attempts.
- Detect unusual login locations and devices.
- Alert on unexpected administrator privilege changes.
- Monitor abnormal mailbox forwarding activity.
- Investigate suspicious remote administration activity.
- Monitor unusual data transfers.
- Maintain relevant threat intelligence indicators.

### 3. Incident Response Controls

- Block confirmed malicious infrastructure.
- Remove malicious emails and attachments.
- Revoke compromised sessions and reset affected credentials.
- Isolate affected endpoints and systems.
- Preserve forensic evidence.
- Escalate confirmed incidents to security leadership.
- Involve legal and compliance teams.
- Notify regulators and affected stakeholders when legally required.

### Recommended Priorities

| Priority | Security Control | Intended Outcome |
|---|---|---|
| Critical | Phishing-resistant MFA | Reduce identity compromise risk |
| Critical | Helpdesk identity verification | Prevent fraudulent account recovery |
| High | Cloud identity monitoring | Detect suspicious account activity |
| High | Privileged access restrictions | Limit attacker movement |
| High | Incident response readiness | Improve containment and recovery |
| Medium | Security awareness training | Reduce social engineering exposure |

These are recommended controls, not evidence that the controls have already been implemented.

---

## 🧰 Technologies, Frameworks and Research Resources

This is a research and analytical project rather than a deployable software application.

| Technology / Resource | Project Application |
|---|---|
| MITRE ATT&CK | Adversary TTP research and mapping |
| NCSC Publications | UK cyber threat context |
| Mandiant Threat Intelligence | Threat actor background research |
| Europol Publications | European cybercrime context |
| FCA Publications | Financial sector risk context |
| CrowdStrike Research | Supporting threat intelligence research |
| Sophos Research | Supporting threat intelligence research |
| Web Browser | Accessing publicly available research |
| Oracle VirtualBox | Visible in a supporting research screenshot |

The report includes screenshots of MITRE ATT&CK and external threat intelligence research pages.

No automated threat intelligence platform, custom Python scripts, SIEM implementation, or live exploitation environment is documented as part of this project.

---

## 📁 Project Documentation

The principal deliverable is a 30-page capstone report titled:

**Threat Intelligence Capstone Report — Threat Actor Profiling and Risk Assessment for Novacore Financial Services**

The report contains:

- Executive summary
- Project introduction
- Organisational threat profile
- Intelligence requirements
- Five threat actor profiles
- Comparative threat analysis
- Scattered Spider deep dive
- Historical attack case study
- Recent campaign analysis
- Qualitative risk assessment
- Security recommendations
- References
- Supporting screenshots and appendices

The supporting screenshots include MITRE ATT&CK technique pages and publicly available threat intelligence research material.

---

## ⚙️ Installation and Setup

### Prerequisites

No application installation, programming environment, database, or API credentials are required.

To review this project, you need:

- A PDF reader
- A web browser
- Internet access for consulting external intelligence references

### Accessing the Project

1. Open this GitHub repository.
2. Read the README to understand the project scope.
3. Locate the uploaded capstone report PDF.
4. Open the report to review the full analysis.
5. Examine the supporting screenshots and reference materials.
6. Use the cited intelligence resources for further independent research.

### Optional: Clone the Repository

Once the repository has been published:

```bash
git clone <YOUR-REPOSITORY-URL>
cd <YOUR-REPOSITORY-DIRECTORY>
```

Replace the placeholders with the actual GitHub repository URL and local directory name.

---

## 🚀 How to Use This Project

This repository can be used as:

### 1. A Threat Intelligence Case Study

Understand how financially motivated threat actors can be assessed against an organisation's business and technology profile.

### 2. A Risk Assessment Reference

Review how threat intelligence findings can be translated into business risks and security priorities.

### 3. A MITRE ATT&CK Learning Resource

Explore the relationship between attacker TTPs, intrusion scenarios, and defensive security controls.

### 4. A Cybersecurity Portfolio Project

Review a practical example of structured threat intelligence research, adversary profiling, and risk-based security recommendations.

### 5. A Starting Point for Further Analysis

Extend the work by developing:

- Verified ATT&CK technique matrices
- Detection use cases
- Threat hunting hypotheses
- Intelligence indicator repositories
- Incident response playbooks
- Risk treatment plans

These are possible future enhancements and are not claimed as completed project deliverables.

---

## 📈 Key Findings and Outcomes

The completed research produced the following outcomes:

**Threat Identification**

Five financially motivated cyber threat groups were profiled and compared.

**Threat Prioritisation**

Scattered Spider was identified as the highest-priority threat for the fictional Novacore environment.

**Attack Method Analysis**

The assessment identified social engineering, credential theft, authentication abuse, and cloud access compromise as important attack pathways.

**Risk Evaluation**

The overall assessed threat risk was classified as High.

**Security Recommendations**

Preventive, detective, and incident response measures were proposed to strengthen organisational resilience.

**Business Communication**

The technical findings were translated into practical recommendations relevant to financial services security management.

---

## 🎓 Skills Demonstrated

This capstone project demonstrates practical experience in:

- Cyber Threat Intelligence (CTI)
- Open-Source Intelligence (OSINT) research
- Threat actor profiling
- Adversary TTP analysis
- MITRE ATT&CK mapping
- Threat landscape assessment
- Qualitative cybersecurity risk assessment
- Financial services threat analysis
- Security control recommendation
- Incident response planning concepts
- Technical report writing
- Risk-based communication to stakeholders

### Professional Relevance

These skills are applicable to roles including:

- Threat Intelligence Analyst
- Cybersecurity Analyst
- SOC Analyst
- Junior Threat Hunter
- Cyber Risk Analyst
- Governance, Risk and Compliance (GRC) Analyst

---

## 📚 References and Further Reading

The project draws on publicly available cybersecurity research and threat intelligence resources.

1. [MITRE ATT&CK](https://attack.mitre.org/)
2. [UK National Cyber Security Centre](https://www.ncsc.gov.uk/)
3. [Financial Conduct Authority](https://www.fca.org.uk/)
4. [Google Cloud / Mandiant](https://cloud.google.com/security)
5. [Europol](https://www.europol.europa.eu/)
6. [CrowdStrike](https://www.crowdstrike.com/)
7. [Sophos](https://www.sophos.com/)

For detailed source descriptions, consult the references and appendices of the capstone report.

**Verification Note:** Some source entries in the original report provide organisation-level website links rather than direct publication URLs. Exact advisory titles, publication dates, campaign attribution, and ATT&CK technique IDs should be verified against authoritative sources.

---

## 🤝 Contributions

Suggestions and constructive feedback are welcome, particularly regarding:

- Threat actor research accuracy
- MITRE ATT&CK technique mapping
- Risk assessment methodology
- Defensive control recommendations
- Detection engineering opportunities
- Additional authoritative threat intelligence sources

To propose an improvement:

1. Open a GitHub Issue describing the suggested change.
2. Provide supporting evidence or references.
3. If repository contributions are enabled, fork the repository.
4. Create a feature branch.
5. Submit a pull request explaining the proposed improvement.

All contributions should remain within ethical and authorised cybersecurity research practices.

---

## ⚖️ Ethical and Legal Disclaimer

This project was developed for educational and professional portfolio purposes.

Novacore Financial Services is presented as a fictional case study organisation.

The analysis is based on publicly available threat intelligence and assumed business characteristics.

No unauthorised penetration testing, exploitation, credential collection, or access to real financial systems is claimed or documented.

The findings should not be interpreted as confirmation that any particular organisation has been compromised.

---

## 👨‍💻 About the Author

**Qhubekani Luphahla**

Cybersecurity and Threat Intelligence Enthusiast

This project forms part of my practical cybersecurity learning and professional portfolio, with a focus on understanding real-world adversary behaviour, assessing cyber risk, and developing evidence-informed defensive recommendations.

My areas of professional interest include:

- Cyber Threat Intelligence
- Security Operations
- Vulnerability Assessment
- Risk Management
- Governance, Risk and Compliance
- Incident Detection and Response

**Email:** [pqlups@gmail.com](mailto:pqlups@gmail.com)

**LinkedIn:** www.linkedin.com/in/qhubekani-luphahla



---

## ⭐ Project Summary

> Effective cybersecurity begins with understanding the threat.
>
> This project demonstrates how structured threat intelligence can help an organisation identify relevant adversaries, understand their methods, assess potential business impacts, and prioritise practical security controls.

**Threat Intelligence | MITRE ATT&CK | Financial Services Security | Risk Assessment**

---

*Project completed: July 2026*

*Author: Qhubekani Luphahla*
