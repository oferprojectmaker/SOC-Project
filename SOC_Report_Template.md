# SOC Report Template  
*Version: 1.0*  
*Prepared by: [Your Name / SOC Team]*  
*Date: [DD/MM/YYYY]*

## 1. Executive Summary  
<img width="1855" height="701" alt="image" src="https://github.com/user-attachments/assets/93bba017-888f-4a14-b0a2-7bfda17d70d2" />
Provide a concise overview of the SOC report, high-level findings, detected incidents, and overall security posture.  
**Example placeholders:**  
- Overall risk level: `[Low/Medium/High]`  
- Number of incidents detected: `[X]`  
- Critical findings: `[Summary]`  
- Key recommendations: `[Summary]`

## 2. Scope of the Report  
![Description](Images2/ABC.png)
Define what this report covers, including time range and monitoring boundaries.  
- Reporting period: `[Start Date] – [End Date]`  
- Monitored environments: `[On-prem / Cloud / Hybrid]`  
- SOC service type: `[24/7 | Business Hours | On-Demand]`

## 3. Environment Overview  
Document the monitored infrastructure and organizational context.  
- Number of assets monitored: `[X]`  
- Asset categories: `[Servers, Endpoints, Network Devices, Cloud Resources]`  
- Critical systems overview:  
  - `[System 1]`  
  - `[System 2]`  
  - `[System 3]`

## 4. Data Sources & Log Collection  
Specify all logging and telemetry sources used within the SOC.  
| Source Type | Description | Log Volume | Status |
|------------|-------------|------------|--------|
| `[Firewall]` | `[Vendor/Model]` | `[X GB/day]` | `[Active]` |
| `[EDR]` | `[Vendor]` | `[X Events/day]` | `[Active]` |
| `[Cloud Logs]` | `[AWS/Azure/GCP]` | `[Details]` | `[Active]` |
| `[Application Logs]` | `[System]` | `[Details]` | `[Active]` |

Include ingestion method: `[Syslog / API / Agent / SIEM Collector]`.

## 5. Detection & Monitoring Methodology  
Describe how threats are detected.  
- Detection engines: `[SIEM, SOAR, EDR, IDS/IPS]`  
- Use cases enabled:  
  - `[Use Case 1: Description]`  
  - `[Use Case 2: Description]`  
  - `[Use Case 3: Description]`  
- Alert prioritization approach: `[Risk-based / Triage-based]`  
- False positive management: `[Explain process]`

## 6. Incident Summary Overview  
Provide aggregated information about incidents during the reporting period.  
| Severity | Count | Notes |
|----------|--------|-------|
| Critical | `[X]` | `[Notes]` |
| High | `[X]` | `[Notes]` |
| Medium | `[X]` | `[Notes]` |
| Low | `[X]` | `[Notes]` |

## 7. Detailed Incident Findings  
### 7.1 Incident ID: `[INC-XXXX]`  
- **Detection Timestamp:** `[DD/MM/YYYY HH:MM]`  
- **Severity:** `[Low/Medium/High/Critical]`  
- **Description:** `[Short incident description]`  
- **Affected Assets:** `[List assets]`  
- **Attack Vector:** `[Vector]`  
- **Impact Analysis:** `[Impact]`  
- **Containment Actions:** `[Actions taken]`  
- **Eradication & Recovery:** `[Steps performed]`  
- **Recommendations:** `[Next steps]`

## 8. MITRE ATT&CK Mapping  
| Tactic | Technique ID | Technique Name | Associated Incident IDs |
|--------|--------------|----------------|--------------------------|
| `[TA000X]` | `[TXXXX]` | `[Technique Name]` | `[INC-XXXX]` |

## 9. Recommendations & Remediation Plan  
- Priority 1 (Critical): `[Recommendation]`  
- Priority 2 (High): `[Recommendation]`  
- Priority 3 (Medium): `[Recommendation]`  
- Priority 4 (Low): `[Recommendation]`

## 10. KPIs & SLAs  
| KPI / SLA | Target | Actual | Status |
|-----------|--------|---------|--------|
| Mean Time to Detect (MTTD) | `[X min/h]` | `[Actual]` | `[Status]` |
| Mean Time to Respond (MTTR) | `[X min/h]` | `[Actual]` | `[Status]` |
| Log ingestion uptime | `99%+` | `[Actual]` | `[Status]` |

## 11. Log Coverage Overview  
- Coverage rate: `[X%]`  
- Missing sources: `[Source 1], [Source 2]`  
- Gaps detected: `[Description]`

## 12. Tools & Technologies Used  
- SIEM: `[Splunk / QRadar / Elastic]`  
- SOAR: `[Product]`  
- EDR: `[Vendor]`  
- IDS/IPS: `[Snort / Suricata]`  
- Ticketing system: `[System]`  
- Threat intelligence feeds: `[List]`

## 13. Appendix  
- Network diagram: `[Insert or link]`  
- Glossary: `[Terms]`  
- SOC Contacts: `[Email / Phone]`

