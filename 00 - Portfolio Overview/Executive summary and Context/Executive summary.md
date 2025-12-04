# 1. Introduction & Context  
**Programme** : FinClear – CyberArk Privileged Access Management (2025–2026)  
**Portfolio focus** : Successful delivery of **Wave 1** (foundational on-prem + Azure)

### 1.1 Organisation & environment
- Brussels-based post-trade financial institution  
- Highly regulated context → ISO 27001 certified, NIS2 & DORA applicable from 2025  
- Hybrid & multi-cloud environment  
  - Identity stack      : Workday → SailPoint IIQ → Entra ID / AD  
  - Authentication     : Okta (IDP) – SAML/OIDC + MFA  
  - Monitoring         : Splunk Enterprise Security  
  - ~4 500 employees, ~1 200 privileged accounts identified (human + non-human)

### 1.2 2024 triggers – Why the programme was launched
| Event                                    | Impact                                          | Regulatory finding          |
|------------------------------------------|--------------------------------------------------|-----------------------------|
| Two privileged-account incidents (Q2/Q3) | €750 k potential exposure + operational outage   | DORA Art. 25 breach risk    |
| Internal audit 2024                      | 18 % orphan/shared accounts, zero session recording | ISO 27001 A.8.3 / A.12.4    |
| External regulator pre-assessment        | “Lack of JIT & dual control” = major finding    | NIS2 Art. 21                |

→ Decision board (CISO + CIO) → launch:**launch a 24-month PAM programme with accelerated Wave 1 in 2025**

### 1.3 Programme governance (high-level)
| Role                  | Name               | Responsibility                              |
|-----------------------|--------------------|---------------------------------------------|
| Sponsor               | CISO               | Budget, risk acceptance, final sign-off     |
| Programme Manager     | Head of Cyber      | Planning, budget, steering committee        |
| Product Owner (proxy) | **Me – IAM Senior BA** | Backlog, priorities, evidence owner         |
| Technical Lead        | CyberArk Architect | Solution design, integration                |

### 1.4 Wave strategy (the reason this portfolio focuses on Wave 1 only)

| Wave | Scope                                      | Go-live   | Risk reduction priority |
|------|--------------------------------------------|-----------|-------------------------|
| **Wave 1** (this portfolio) | Windows, Linux, SQL/Oracle, Azure foundational (~700 high-risk accounts) | **20 Oct 2025** | Highest (critical servers & cloud landing zones) |
| Wave 2 | OT/SCADA, legacy, full GCP, IoT at scale   | Q3 2026   | Medium → Low            |

**Result after Wave 1** → 96.8 % of high-risk accounts under control, zero production incidents, full audit trail → **programme declared “on track” by the regulator in Dec 2025**.

**This portfolio covers the complete end-to-end journey of Wave 1**:  
BRD → Agile delivery → Environment readiness → UAT → Go-live → Hypercare → Handover to BAU.

All following sections are real extracts and evidence from this successful Wave 1 delivery.
