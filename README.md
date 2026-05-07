# Accel Entertainment Cybersecurity Risk Assessment

A quantitative and qualitative cybersecurity risk assessment of Accel Entertainment, Inc. (NYSE: ACEL), the largest distributed gaming terminal operator in the United States. This project was completed as an academic exercise applying industry-standard frameworks to a real-world publicly traded company.

## Disclaimer

This report is an independent academic exercise conducted entirely using publicly available information, including SEC 10-K filings, Shodan, LinkedIn, and published cybersecurity industry research. No internal systems were accessed, no unauthorized testing was performed, and no proprietary data was obtained. Any named individuals or IP addresses referenced are drawn from public records. This assessment does not represent a real engagement with Accel Entertainment and was not commissioned by or affiliated with the company in any way.

---

## Skills Demonstrated

- **FAIR Model (Factor Analysis of Information Risk)** — quantitative pre/post-mitigation loss modeling with Loss Exceedance Curves (LECs)
- **OSINT** — company reconnaissance using SEC 10-K filings, Shodan, LinkedIn job postings, and public financial data
- **MITRE ATT&CK Framework** — mapped attack techniques to each threat scenario
- **Qualitative Risk Analysis** — asset identification, threat vector/actor mapping, heat map
- **Technical Writing** — executive summary, company overview, recommendations, and appendices

---

## Project Structure

| File | Description |
|------|-------------|
| `Research.docx` | Original preliminary document |
| [`Research.md`](Research.md) | Preliminary research document — initial asset/threat/actor mapping that informed the final report |
| `RiskAssessment.docx` | Original formatted report (download for full layout with figures) |
| [`RiskAssessment.md`](RiskAssessment.md) | Full final report — qualitative + quantitative FAIR analysis, MITRE ATT&CK mappings, recommendations |

---

## Key Findings

Three threat scenarios were modeled using the FAIR framework against Accel Entertainment's infrastructure:

| Scenario | Pre-Mitigation Expected Loss | Post-Mitigation Expected Loss |
|----------|------------------------------|-------------------------------|
| Insider attack via field service technician | ~$54.5M | ~$1.2M |
| AE Accelerator app unpatched vulnerability | ~$88M | ~$8.55M |
| Spear phishing of CFO/cybersecurity lead | ~$113M | ~$7.5M |

Mitigation strategies include technician activity logging, zero trust architecture, patch management cadence, phishing simulation campaigns, and appointing a dedicated CISO.

---

## Frameworks & Tools Referenced

- FAIR (Factor Analysis of Information Risk)
- MITRE ATT&CK
- Shodan
- IBM 2024 Cost of a Data Breach Report
- Illinois Gaming Board (IGB) regulatory guidelines
- SEC Form 10-K filings

---

*Author: Henry Nguyen | Academic project — April 2025*
