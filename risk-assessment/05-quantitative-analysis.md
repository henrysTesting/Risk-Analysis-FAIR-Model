# V. Quantitative Risk Analysis (FAIR Model)

Loss Exceedance Curves (LECs) were constructed for each scenario using the FAIR (Factor Analysis of Information Risk) model. Values are estimates grounded in industry benchmarks and publicly reported data.

---

## Pre-Mitigation

### Scenario 1 — Service Technician Inside Attack

| Percentile | Estimated Loss |
|------------|----------------|
| Minimum | $13,000,000 |
| 10th percentile | $32,000,000 |
| Average (50th percentile) | $54,500,000 |
| 90th percentile | $80,300,000 |
| Maximum | $163,000,000 |

**Expected value:** ~$22.25M (50% probability)

Loss Event Frequency (LEF) derived from Insider Threat Statistics (2025) — maximum of 89 reported cases within the relevant industry, scaled downward by percentile.

---

### Scenario 2 — AE Accelerator Unpatched Vulnerability

| Percentile | Estimated Loss |
|------------|----------------|
| Minimum | $23,600,000 |
| Average | $88,000,000 |
| Maximum | $468,500,000 |

**Expected value:** ~$4.6M

Minimum losses represent mandatory regulatory fines and legal costs regardless of breach scope. LEF derived from *Vulnerability Exploitation (2024-25)* (Dark Reading) — 33 attackers targeting enterprise-focused technologies, adjusted downward to account for AE's lower public profile.

---

### Scenario 3 — Phishing Attack on CFO

| Percentile | Estimated Loss |
|------------|----------------|
| Minimum | $31,000,000 |
| Average | $226,000,000 |
| Maximum | $736,360,000 |

**Expected value:** ~$113M

Proportionally higher than MGM's losses due to the target's higher privilege level across AE's infrastructure. Base frequency sourced from social engineering attacks targeting Las Vegas casinos, expanded to reflect AE's wider operational footprint.

---

## Post-Mitigation

### Scenario 1 — Service Technician Inside Attack

| Percentile | Estimated Loss |
|------------|----------------|
| 10th percentile | $922,000 |
| Average | $2,300,000 |
| Maximum | $9,300,000 |

**Expected value:** ~$1.22M

Reduction driven by improved incident response capability, enhanced technician vetting, and reduced subcontractor usage — significantly shrinking the attack surface.

---

### Scenario 2 — AE Accelerator Unpatched Vulnerability

| Percentile | Estimated Loss |
|------------|----------------|
| Minimum | $1,900,000 |
| Moderate breach | $17,200,000 |
| Maximum | $49,600,000 |

**Expected value:** ~$8.55M

Minimum costs represent forensic and legal expenses. Regular patching reduces known exploitable vulnerabilities, though cannot eliminate all risk.

---

### Scenario 3 — Phishing Attack on CFO

| Percentile | Estimated Loss |
|------------|----------------|
| Minimum | $3,900,000 |
| Maximum | $99,600,000 |

**Expected value:** ~$7.5M

Nearly a 90% drop from pre-mitigation minimum, driven by cybersecurity awareness training and phishing simulation campaigns.

---

## Pre vs. Post-Mitigation Summary

| Scenario | Pre-Mitigation Expected Value | Post-Mitigation Expected Value | Reduction |
|----------|------------------------------|-------------------------------|-----------|
| Insider Technician Attack | ~$54.5M | ~$1.22M | ~97.8% |
| AE Accelerator Exploit | ~$88M | ~$8.55M | ~90.3% |
| CFO Phishing Attack | ~$113M | ~$7.5M | ~93.4% |

---

*[Back to index](README.md) | [Next: Recommendations](06-recommendations.md)*
