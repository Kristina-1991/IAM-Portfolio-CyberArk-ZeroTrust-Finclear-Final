# Executive Summary – CyberArk PAM Programme (Wave 1)

**Organisation** : FinClear – Brussels-based post-trade financial institution  
**Context 2024** : Internal audit + two privileged-account incidents → critical gaps identified  
• Manual onboarding (3+ days, 20 % errors)  
• Shared & orphan accounts (~18 %)  
• No session recording or approval workflow  
• Compliance findings (ISO 27001, NIS2, DORA)

**Programme objective**  
Deliver foundational Privileged Access Management under Zero Trust principles: eliminate standing privileges, enforce JIT + dual approval, achieve full session auditability.

**Delivery approach – two phases**  
**Phase 0** – Discovery & reconciliation (BR-00) → reliable inventory + owner assignment  
**Phase 1** – Core controls rollout (Oct 2025)  
 • BR-01 Semi-automated onboarding (Discovery → Pending → Safe/Platform)  
 • BR-02 Just-In-Time elevation with mandatory dual approval & auto-revocation  
 • BR-03 100 % session isolation & recording (PSM) + Splunk ingestion

**Wave strategy**  
**Wave 1 (focus of this portfolio)** – Go-live 20 October 2025  
 700+ high-risk accounts (Windows, Linux, SQL/Oracle DB, Azure foundational)  
**Wave 2 (2026)** – OT/SCADA, full cloud, legacy systems

**Key results – Wave 1 (Dec 2025)**  
| KPI                                    | Target 2025 | Actual Dec 2025 | Target 2026 |
|----------------------------------------|-------------|-----------------|-------------|
| % privileged accounts in CyberArk      | ≥ 95 %      | 96.8 %          | 100 %       |
| % sessions via JIT (no standing rights)| ≥ 90 %      | 93 %            | 100 %       |
| % sessions recorded & searchable       | 100 %       | 100 %           | 100 %       |
| Orphan accounts                        | ≤ 5 %       | 1.8 %           | 0 %         |
| Avg JIT approval time                  | ≤ 15 min    | 11 min          | ≤ 5 min     |

**Delivery highlights**  
• 6-week Scrum delivery (3 sprints)  
• 8/8 environment readiness checks passed  
• 12 UAT scenarios – 100 % pass – CISO sign-off  
• 6-week hypercare with 24/7 rota → zero severity-1 incidents  
• Full handover to BAU – 1 December 2025

**Compliance & standards**  
Full audit trail and controls aligned with ISO 27001 (A.8/A.9/A.12), NIS2, DORA, GDPR.

**Scope Wave 1 – In**  
• Windows, Linux, Oracle/SQL DB, Azure (foundational)  
• Human + service accounts, break-glass  
• Integrations: SailPoint ↔ CyberArk, Entra ID, Splunk, SAML/OIDC PVWA

**Scope Wave 1 – Out / Deferred**  
• Full IoT/SCADA fleet (pilot only)  
• GCP & legacy platforms  
• Enterprise-wide recertification campaigns

**My role** : IAM Senior Business Analyst – Proxy Product Owner, Scrum Master, UAT Coordinator, Change Lead, Hypercare Lead

**This portfolio demonstrates end-to-end delivery of a regulated, high-impact PAM Wave 1 – from requirements to run – with zero production incidents and full CISO sign-off.**
