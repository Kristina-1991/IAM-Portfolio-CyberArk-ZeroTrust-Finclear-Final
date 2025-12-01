# IAM-Portfolio-CyberArk-ZeroTrust-Finclear-Final

# CyberArk PAM Implementation – Zero Trust Financial Services
FinClear – Brussels-based post-trade organisation (hybrid & multi-cloud)

**Objective**  
Close the three highest privileged-access risks in an already mature IAM ecosystem (Workday + SailPoint + Entra ID) by implementing CyberArk PAM.

**Key business risks addressed**
1. Shared & orphan privileged accounts + 3-day manual onboarding
2. Permanent elevated privileges – no approval workflow
3. No session recording or audit trail → compliance findings

**Target state (after this programme)**
- >95 % of privileged accounts onboarded & rotated
- 100 % Just-In-Time elevation with dual approval
- 100 % of privileged sessions recorded and exported to Splunk

### Repository structure
0. Context & Executive Summary → Business case, scope, KPIs  
1. Discovery & Clean-up (BR-00)  
2. Foundational PAM Controls (BR-01/02/03) – semi-automated onboarding, JIT, session recording  
3. Onboarding Waves & Scale – phased rollout (servers → DB → cloud → SaaS → OT pilot)  
4. Run – Operating Model, RACI, KPIs, hypercare

Key visuals ↓
[![Executive Summary](Diagrams_Overview/00_Executive_Summary_Preview.png)](0_Context_&_Executive_Summary/Executive_Summary.pdf)
[![Target Architecture](Diagrams_Overview/01_Target_Architecture.png)](Diagrams_Overview/01_Target_Architecture.png)
