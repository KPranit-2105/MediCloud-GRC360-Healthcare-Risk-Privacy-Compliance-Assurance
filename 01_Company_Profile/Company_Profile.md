# MediCloud Health Systems — Company Profile & Tech Stack

## 1. Overview
- **Company Name:** MediCloud Health Systems Inc.
- **Industry:** Healthcare Technology / Software-as-a-Service (SaaS)
- **Employees:** 1,200 across US headquarters and remote engineering teams
- **Customer Base:** 350+ Hospital Networks, Regional Health Systems, and Urgent Care Clinics
- **Headquarters:** Austin, Texas
- **Compliance Scope:** HIPAA Security & Privacy Rules, HITECH, ISO/IEC 27001:2022, NIST CSF v2.0, SOC 2 Type II (TSC: Security, Confidentiality, Privacy, Availability, Processing Integrity)

## 2. Business Services Provided
1. **Core Electronic Health Records (EHR) Platform (`APP-001`):** Central cloud database storing patient clinical encounters, diagnoses, lab orders, and treatment notes.
2. **Patient Portal Mobile & Web App (`APP-002`):** Direct-to-patient access for scheduling, lab results, prescription refill requests, and secure provider messaging.
3. **Provider Dashboard & Clinical Workflow (`APP-003`):** Physician interface for reviewing charts, ordering e-prescriptions, and documenting patient consultations.
4. **Telemedicine Video Service (`APP-004`):** WebRTC-based encrypted video consultation platform connecting remote patients with clinicians.
5. **Medical Report & Imaging Service (`APP-005`):** Cloud-hosted repository for DICOM imaging, radiology reports, and pathology results.
6. **E-Prescription & Pharmacy Integration Gateway (`APP-006`):** Integration bus linking clinicians with national pharmacy networks (Surescripts).
7. **Patient Billing & Revenue Cycle Management (`APP-007`):** Claims processing, insurance eligibility verification, and payment gateway integration.

## 3. Technology & Cloud Infrastructure
- **Cloud Service Provider:** Amazon Web Services (AWS multi-region deployment - `us-east-1` primary, `us-west-2` DR).
- **Container Orchestration:** AWS Elastic Kubernetes Service (EKS) managing 50+ microservice pods.
- **Databases:** Managed AWS Aurora PostgreSQL (encrypted via AWS KMS with customer-managed keys), Redis for caching, S3 for DICOM image storage.
- **API Architecture:** AWS API Gateway routing HTTPS/TLS 1.3 REST API traffic with OAuth 2.0 / OIDC authentication tokens.
- **Identity & Access Management:** Okta enterprise SSO for employee access; Auth0 for patient/provider identity with mandatory WebAuthn/TOTP MFA for staff.
- **CI/CD Pipeline:** GitHub Enterprise, HashiCorp Terraform for Infrastructure-as-Code (IaC), ArgoCD for Kubernetes deployments, Snyk & SonarQube for vulnerability scanning.
- **Logging & Security Monitoring:** AWS CloudTrail, Amazon GuardDuty, Datadog Application Performance Monitoring, Splunk Cloud SIEM with 365-day log retention.

## 4. Protected Health Information (PHI) Environment
MediCloud creates, receives, maintains, and transmits Business Associate and Covered Entity data including:
- Patient Demographic Information (Name, SSN, DOB, Address, Phone)
- Clinical Encounters, Diagnoses (ICD-10), Procedures (CPT), Clinical Progress Notes
- Diagnostic Lab Results & Radiology Imaging Files (DICOM)
- Electronic Prescription History & Controlled Substance Records
- Health Insurance Subscriber IDs, Claims Data, Billing History
- Telemedicine Session Metadata and Transcripts

---

## 5. Current GRC Challenges (Problem Statement)
MediCloud grew rapidly from 200 to 1,200 employees, causing GRC operations to lag behind engineering velocity:
- **Spreadsheet Fragmentation:** 500+ controls, 100+ vendor relationships, and thousands of evidence files maintained across disconnected Excel sheets and Google Drive folders.
- **Inconsistent Control Ownership:** Unclear accountability between DevOps, Application Security, IT Ops, and Compliance teams.
- **Vendor Risk Blind Spots:** Over 100 third-party SaaS vendors operating without standardized Business Associate Agreements (BAAs) or recent SOC 2 reviews.
- **Audit Fatigue:** Repeat requests for evidence during annual SOC 2, HIPAA, and ISO audits due to lack of a centralized evidence repository.
- **Lack of Incident-to-Risk Integration:** Inability to dynamically link third-party security events to risk scoring, legal breach assessments, and executive reporting.
