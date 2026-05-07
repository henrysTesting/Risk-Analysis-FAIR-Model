# Appendix A — MITRE ATT&CK Mappings

---

## Scenario 1 — Service Technician Inside Attack

| Tactic | Technique | MITRE ID | Description |
|--------|-----------|----------|-------------|
| Initial Access | Hardware Additions | T1200 | Attackers use physical devices (e.g., USB or rogue hardware) on a target system |
| Persistence | Valid Accounts | T1078 | Compromised or misused technician credentials provide ongoing access |
| Lateral Movement | External Remote Services | T1133 | Use of VPN, RDP, or remote tools to access internal systems |
| Defense Evasion | Account Manipulation | T1098 | Creation or modification of accounts or privileges for stealth |

---

## Scenario 2 — AE Accelerator Unpatched Vulnerability

| Tactic | Technique | MITRE ID | Description |
|--------|-----------|----------|-------------|
| Execution | Process Injection | T1055 | Code injected into a legitimate AE process |
| Initial Access | Exploitation for Client Execution | T1203 | Malicious input such as SQL injection |
| Defense Evasion | Input Injection | T1190 | Malicious input passed into the application to bypass controls |
| Collection | Data from Info Repositories | T1213 | Extracts partner data or analytics from AE Accelerator |
| Exfiltration | Exfiltration Over Web Service | T1567 | Stolen data transmitted through AE app |

---

## Scenario 3 — Phishing Attack on CFO

| Tactic | Technique | MITRE ID | Description |
|--------|-----------|----------|-------------|
| Initial Access | Phishing | T1566 | Target CFO via email |
| Defense Evasion | Email Spoofing | T1585 | Fake internal domain email address |
| Credential Access | Credential Phishing | T1566 | Harvest CFO login credentials through a fake login portal |
| Persistence | Account Manipulation | T1098 | Admin account altered for continued persistence within the system |

---

*[Back to index](README.md) | [Next: Citations](08-citations.md)*
