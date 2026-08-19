# MediCloud Health Systems — Comprehensive Enterprise GRC & Privacy Portfolio Case Study

> **Notice:** This project represents a simulated portfolio case study designed for demonstration and interview purposes. All company names, incidents, metrics, and scenario details are fictionalized models of Healthcare SaaS Governance, Risk, and Compliance (GRC) operations.

---

## Executive Overview
**MediCloud Health Systems** is a cloud-native Healthcare SaaS provider with 1,200 employees serving over 350 hospital networks and healthcare clinics across the United States. The platform processes millions of Protected Health Information (PHI) records across 52 microservices hosted in Amazon Web Services (AWS) using Kubernetes (EKS), PostgreSQL, REST APIs, and native mobile applications.

This repository contains a **complete, auditable, evidence-backed Enterprise GRC Operating Model** designed to transition MediCloud from fragmented spreadsheet-based risk management to an enterprise-grade, ServiceNow-ready GRC framework.

---

## Key Program Achievements & Metrics
- **Enterprise Risk Register:** 32 fully quantified risks across Privacy, Cybersecurity, Cloud, Application Security, Data Security, Third-Party Risk, and Business Continuity.
- **Application & Data Inventory:** 52 categorized SaaS microservices & 26 classified data elements (PHI, PII, Financial, System Logs).
- **Control Framework & Testing:** 78 standardized controls mapped across **HIPAA Security & Privacy Rules, HITECH, ISO/IEC 27001:2022, NIST CSF 2.0, and SOC 2 Trust Services Criteria (Security, Confidentiality, Privacy, Availability, Processing Integrity)**. 42 controls rigorously tested with empirical pass/fail workpapers.
- **Vendor Risk & Central Case Study:** 26 critical vendors evaluated with a 30-question due diligence questionnaire. Includes a complete **End-to-End Vendor Incident Lifecycle (`VINC-2026-001`)** mapping an administrative compromise at a medical report vendor to risk assessment, HIPAA breach evaluation, control gap analysis, audit findings, and remediation.
- **Executive Dashboard & KRIs:** Data-driven executive dashboard, 5x5 Risk Heatmap, 26 Key Performance & Risk Indicators (KPIs/KRIs), 14-domain GRC Maturity Model, and a 30/60/90-Day Strategic Improvement Roadmap.

---

## Directory Architecture
```text
MediCloud-GRC-Project/
├── README.md                                  # Repository Master Guide
├── 01_Company_Profile/
│   └── Company_Profile.md                     # Business, Tech & PHI Profile
├── 02_Risk_Management/                        # Risk Registers & Assessments (.xlsx)
├── 03_Application_Risk/                       # Microservice Inventory & Risk Tiering (.xlsx)
├── 04_Data_Governance/                        # Data Inventory & PHI Classification (.xlsx)
├── 05_Control_Management/                     # Control Library, Testing & Effectiveness (.xlsx)
├── 06_Compliance/                             # Framework Mappings & Calculated Posture (.xlsx)
├── 07_Privacy/                                # Privacy Impact Assessments & Risk Scores (.xlsx)
├── 08_Vendor_Risk/                            # Vendor Inventory, Assessment & Questionnaire (.xlsx)
├── 09_Incident_Risk/                          # Central Incident Workflow & Legal Impact (.xlsx)
├── 10_Remediation/                            # Issue & Remediation SLA Tracker (.xlsx)
├── 11_Audit/                                  # Internal Audit Workpapers & Findings (.xlsx)
├── 12_Evidence/                               # Central Evidence & Expiration Tracker (.xlsx)
├── 13_Policies/                               # Policy Governance Register (.xlsx)
├── 14_Dashboard/                              # Executive Dashboard, Heatmap & KRIs (.xlsx)
├── 15_Documentation/                          # Methodologies, ServiceNow Mapping & Reports (.md)
└── 16_Interview_Preparation/                  # Elevator Pitches, 100+ Q&As & STAR Stories (.md)
```

---

## The Central GRC Operating Thread
This project demonstrates the core GRC lifecycle connecting all entities through explicit relational IDs:

$$\text{Application (APP-004)} \longrightarrow \text{Data Element (DATA-005)} \longrightarrow \text{Vendor (VEND-001)} \longrightarrow \text{Vendor Incident (VINC-2026-001)} \longrightarrow \text{Enterprise Risk (RISK-015)} \longrightarrow \text{Control (CTRL-001/056)} \longrightarrow \text{Control Test (TEST-015)} \longrightarrow \text{Audit Finding (FIND-008)} \longrightarrow \text{Remediation (REM-012)} \longrightarrow \text{Evidence (EVID-015)} \longrightarrow \text{Executive Dashboard}$$

---

## ServiceNow GRC / IRM Architecture Alignment
The entire data model maps directly to ServiceNow Integrated Risk Management (IRM):
- **Risk Management Module:** `sn_risk_risk` & `sn_risk_definition`
- **Policy and Compliance:** `sn_compliance_control` & `sn_compliance_policy`
- **Third-Party Risk Management (TPRM):** `sn_vdr_risk_asmt_vendor`
- **Audit Management:** `sn_audit_engagement` & `sn_audit_finding`
- **Issue Management:** `sn_grc_issue` & `sn_grc_task`

---

## Author & Contact
Designed and authored as an auditable healthcare technology GRC case study.
