# IV. Qualitative Risk Analysis

## Overview

Three primary cybersecurity concerns were identified within AE's ecosystem:

1. **Insider threat via field service technicians** — identified through active LinkedIn job postings for new technician hires
2. **Application exploits via unpatched vulnerabilities** — primarily targeting the AE Accelerator application
3. **Phishing attacks on key executives** — specifically the CFO and head of cybersecurity, Matthew Ellis

---

## Assets

**Gaming Machines & Terminals**
Deployed across thousands of locations, these devices contain proprietary software and embedded systems controlling game logic, payout calculations, and performance metrics. They are revenue-generating assets subject to strict regulatory compliance managed by state Gaming Control Boards.

**AE Accelerator Application**
A proprietary customer portal providing location partners with gaming performance analytics, compliance tracking (including gaming licenses and renewal dates), and business intelligence. As a centralized hub for sensitive business and regulatory data widely distributed to partners, it is a high-value digital asset and a high-value target.

**Field Service Technicians**
Responsible for installing, maintaining, and troubleshooting gaming machines across partner venues. These individuals have direct access to both hardware and software components, proprietary configuration data, and potentially sensitive customer information. Their privileged access makes them a high-value asset — and a high-value attack surface.

**Network Infrastructure & Third-Party Vendors**
Cloud connectivity (Azure), maintenance contractors, and consultants all carry varying levels of system access, expanding the attack surface if not carefully managed.

**Executive Leadership (CFO/CISO)**
The individuals overseeing cybersecurity have the highest level of IT infrastructure privileges within the company. A compromise here represents the single most impactful risk scenario.

---

## Threat Vectors

**Field Service Technician Compromise**
Technicians are prime targets for social engineering or insider attacks (intentional or unintentional). Direct, privileged physical access to machines combined with inconsistent oversight creates meaningful risk. As a real-world example: during personal work experience in a similar field, an employee was observed plugging their personal laptop into a contracted company's server system — an incident that went unreported.

**AE Accelerator Unpatched Vulnerabilities**
The AE Accelerator app stores and transmits highly sensitive business data. Unpatched vulnerabilities — such as improper authentication, weak encryption, or exposed APIs — could be exploited for unauthorized access. Notably, the application does not follow a uniform update schedule (updates have ranged from a few weeks to several months apart), increasing this risk surface.

**CFO as High-Value Phishing Target**
Accel Entertainment's 10-K filing lists the CFO, Matthew Ellis, as one of two individuals responsible for cybersecurity oversight. He does not appear to have a formal background in information technology or cybersecurity. This gap introduces significant vulnerability to social engineering. Given his high-level access to financial systems and security infrastructure, he represents a prime target for spear phishing.

---

## Threat Actors

| Actor | Description |
|-------|-------------|
| Cybercriminal Groups | Organized hackers motivated by financial gain |
| Insider Threats | Employees or contractors with malicious or negligent intent |
| Hacktivists | Politically motivated actors seeking disruption |
| Competitor/Rivaling Companies | Entities seeking proprietary intelligence or competitive advantage |
| Script Kiddies | Low-skill actors using pre-built tools |

---

## Losses

### Scenario 1 — Field Service Technician Compromise

| Loss Type | Estimated Range |
|-----------|----------------|
| Operational disruption / machine downtime | $100,000–$500,000 |
| IGB regulatory fines (per machine / systemic) | $5,000–$50,000 per machine / $100,000+ systemic |
| Reputational damage and lost partner trust | $170,000–$2,000,000 |
| **Total estimated range** | **$370,000–$2,850,000+** |

### Scenario 2 — AE Accelerator Exploitation

| Loss Type | Estimated Range |
|-----------|----------------|
| Breach response costs (IBM 2024 benchmark) | $500,000–$3,000,000 |
| Regulatory penalties from gaming boards | up to $500,000 |
| Lost partner relationships (5–10% engagement drop) | $250,000–$1,500,000 |
| **Total estimated range** | **$800,000–$10,000,000** |

### Scenario 3 — CFO Phishing Attack

| Loss Type | Estimated Range |
|-----------|----------------|
| Legal settlements (MGM 2019 precedent) | ~$45,000,000 |
| Forensic investigation | $500,000–$1,000,000 |
| IGB regulatory fines | $500,000–$1,000,000 |
| Reputational / revenue loss | $2,000,000–$5,000,000 |
| **Total estimated losses** | **$50,000,000+** |

---

## Scenarios Summary Table

| Asset | Threat Methods | Threat Actors | Loss Types | Loss Scale |
|-------|---------------|---------------|------------|------------|
| Field Service Technicians | Social engineering, insider attack | Malicious insiders, social engineers, competitors | Operational disruption, regulatory fines, reputational damage, legal costs | $370,000–$2,850,000+ |
| AE Accelerator Application | Unpatched vulnerability exploitation, credential stuffing | Cybercriminals, hacktivists, APTs | Data breach, reputational damage, system downtime, compliance penalties | $800,000–$10,000,000 |
| CFO / CISO | Spear phishing, email compromise, malware injection | Cybercriminal organizations, phishing groups | Massive data breach, regulatory fines, lawsuit settlements, financial fraud, reputational damage | $50,000,000+ |

---

## Heat Map

| Severity | Improbable | Insignificant | Minor | Moderate | Major | Critical |
|----------|:----------:|:-------------:|:-----:|:--------:|:-----:|:--------:|
| **Severe** | | | | | | CFO Phishing (Scenario 3) |
| **High** | | | | | AE Accelerator Exploit (Scenario 2) | |
| **Medium** | | | | Field Tech Insider (Scenario 1) | | |
| **Low** | | | | | | |

*Green = generally safe, Yellow = caution, Orange = high risk, Red = immediate danger*

---

*[Back to index](README.md) | [Next: Quantitative Risk Analysis](05-quantitative-analysis.md)*
