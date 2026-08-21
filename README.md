<div align="center">

# 🏥 MediCloud Health Systems — Enterprise GRC & Privacy Portfolio

**Healthcare SaaS Governance, Risk & Compliance — Full Operating Model**

![Company](https://img.shields.io/badge/Company-MediCloud%20Health%20Systems-1B2A4A.svg)
![Industry](https://img.shields.io/badge/Industry-Healthcare%20SaaS%20%2F%20PHI-2E7D32.svg)
![Frameworks](https://img.shields.io/badge/Compliance-HIPAA%20%7C%20HITECH%20%7C%20ISO%2027001%20%7C%20NIST%20CSF%20%7C%20SOC%202-FF9900.svg)
![Status](https://img.shields.io/badge/Type-Simulated%20Portfolio%20Case%20Study-6A1B9A.svg)

> **Notice:** This is a simulated portfolio case study for demonstration and interview purposes. All company names, incidents, metrics, and scenarios are fictionalized models of Healthcare SaaS GRC operations.

</div>

---

## Executive Overview

**MediCloud Health Systems** is a cloud-native Healthcare SaaS provider with **1,200 employees** serving **350+ hospital networks and clinics** across the United States. The platform processes millions of Protected Health Information (PHI) records across **52 microservices** hosted on AWS (EKS, PostgreSQL, REST APIs, native mobile).

This repository contains a **complete, auditable, evidence-backed Enterprise GRC Operating Model** — designed to move MediCloud from fragmented spreadsheet-based risk management to an enterprise-grade, **ServiceNow-ready GRC framework.**

---

## 📊 Program Scale at a Glance

<p align="center">
  <img src="assets_medicloud/program_scale.svg" alt="MediCloud GRC Program Scale Overview" width="850">
</p>

| Metric | Detail |
|---|---|
| **Enterprise Risk Register** | 32 fully quantified risks across Privacy, Cybersecurity, Cloud, Application Security, Data Security, Third-Party Risk, and Business Continuity |
| **Application & Data Inventory** | 52 categorized SaaS microservices · 26 classified data elements (PHI, PII, Financial, System Logs) |
| **Control Framework & Testing** | 78 standardized controls mapped across **HIPAA Security & Privacy Rules, HITECH, ISO/IEC 27001:2022, NIST CSF 2.0, SOC 2 TSC** (Security, Confidentiality, Privacy, Availability, Processing Integrity) — **42 controls tested** with empirical pass/fail workpapers |
| **Vendor Risk** | 26 critical vendors evaluated via a 30-question due diligence questionnaire, including a complete end-to-end **Vendor Incident Lifecycle** case study (`VINC-2026-001`) |
| **Executive Reporting** | Data-driven dashboard, 5×5 Risk Heatmap, 26 KPIs/KRIs, 14-domain GRC Maturity Model, 30/60/90-Day Strategic Roadmap |

---

## 🔗 The Central GRC Operating Thread

Every entity in this program connects through explicit relational IDs — nothing lives in isolation. A single vendor incident traces cleanly from the application it touched all the way through to the executive dashboard:

<p align="center">
  <img src="assets_medicloud/operating_thread.svg" alt="Central GRC Operating Thread Diagram" width="1000">
</p>

This traceability is the difference between a GRC program that *looks* organized and one that actually **survives an audit** — any finding can be walked backward to the exact control, risk, and application that produced it.

---

## 📁 Directory Architecture

```text
MediCloud-GRC-Project/
├── README.md                                  # Repository Master Guide
├── 01_Company_Profile/
│   └── Company_Profile.md                     # Business, Tech & PHI Profile
├── 02_Risk_Management/                        # Risk Registers & Assessments (.xlsx)
├── 03_Application_Risk/                       # Microservice Inventory & Risk Tiering (.xlsx)
├── 04_Data_Governance/                        # Data Inventory & PHI Classification (.xlsx)
├── 05_Control_Management/                     # Control Library, Testing & Effectiveness (.xlsx)
├── 06_Compliance/                              # Framework Mappings & Calculated Posture (.xlsx)
├── 07_Privacy/                                 # Privacy Impact Assessments & Risk Scores (.xlsx)
├── 08_Vendor_Risk/                             # Vendor Inventory, Assessment & Questionnaire (.xlsx)
├── 09_Incident_Risk/                           # Central Incident Workflow & Legal Impact (.xlsx)
├── 10_Remediation/                             # Issue & Remediation SLA Tracker (.xlsx)
├── 11_Audit/                                   # Internal Audit Workpapers & Findings (.xlsx)
├── 12_Evidence/                                # Central Evidence & Expiration Tracker (.xlsx)
├── 13_Policies/                                # Policy Governance Register (.xlsx)
├── 14_Dashboard/                               # Executive Dashboard, Heatmap & KRIs (.xlsx)
├── 15_Documentation/                           # Methodologies, ServiceNow Mapping & Reports (.md)
└── 16_Interview_Preparation/                   # Elevator Pitches, 100+ Q&As & STAR Stories (.md)
```

---

## 🔌 ServiceNow IRM Architecture Alignment

The entire data model was designed to map directly onto ServiceNow Integrated Risk Management (IRM) — this isn't a spreadsheet exercise pretending to be enterprise-ready, it's structured to migrate into a real IRM platform with minimal rework.

<p align="center">
  <img src="assets_medicloud/servicenow_mapping.svg" alt="ServiceNow IRM Architecture Alignment Diagram" width="700">
</p>

| GRC Program Module | ServiceNow IRM Table |
|---|---|
| Risk Management | `sn_risk_risk`, `sn_risk_definition` |
| Policy and Compliance | `sn_compliance_control`, `sn_compliance_policy` |
| Third-Party Risk Management (TPRM) | `sn_vdr_risk_asmt_vendor` |
| Audit Management | `sn_audit_engagement`, `sn_audit_finding` |
| Issue Management | `sn_grc_issue`, `sn_grc_task` |

---

## Author & Contact

Designed and authored as an auditable healthcare technology GRC case study.

---

<div align="center">

**Every number in this program traces to an ID, every ID traces to a record, and every record is built to move into a real IRM system.** That's the standard this repository was built to meet.

</div>
