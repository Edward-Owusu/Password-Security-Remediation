# Password Security & Exposure Remediation – GRC / IT Audit Project

A practical Governance, Risk, and Compliance (GRC) / IT Audit portfolio case study focused on password exposure, password fatigue, physical credential disclosure, and security hygiene.

## Project Overview

This project demonstrates an end-to-end GRC workflow:

**Risk Identification → Risk Assessment → Framework Mapping → Control Design → Audit Testing → Evidence → Metrics → Remediation**

The scenario focuses on employees recording passwords on sticky notes, desks, or other physical locations because of password fatigue. The project evaluates the resulting risk and proposes technical and governance controls to reduce exposure.

## Objectives

- Identify and assess password-security and physical credential exposure risk.
- Calculate inherent and residual risk.
- Map the risk to recognized security and compliance frameworks.
- Design preventive and detective controls.
- Develop practical IT audit testing procedures.
- Define evidence requirements and measurable KPIs.
- Establish a password security and clean-desk policy.
- Demonstrate a complete remediation lifecycle.

## Key Risk

**Risk ID:** RSK-002

Employees may physically record passwords on sticky notes, desks, or underneath keyboards due to password fatigue. This can enable unauthorized physical credential theft, loss of confidentiality, and bypass of logical access controls.

### Risk Scoring

| Measure | Score |
|---|---:|
| Inherent Likelihood | 4/5 |
| Inherent Impact | 3/5 |
| Inherent Risk | 12/25 |
| Residual Likelihood | 1/5 |
| Residual Impact | 3/5 |
| Residual Risk | 3/25 |

The proposed controls reduce the assessed risk from **12/25 to 3/25**.

## Framework References

The workbook maps the risk to:

- **ISO/IEC 27001:2022** – including user endpoint devices and secure working areas.
- **NIST SP 800-53** – including authenticator management and physical access controls.
- **SOC 2** – including logical access and physical security criteria.

> Framework mappings in this portfolio project are presented as practical case-study mappings and should be validated against the applicable organization's control environment and audit scope.

## Proposed Controls

### 1. Enterprise Password Manager

Deploy an Enterprise Password Manager (EPM) with centralized identity/SSO integration to reduce password fatigue and eliminate insecure physical password storage.

### 2. Passwordless Authentication

Transition suitable user populations toward FIDO2 security keys or Windows Hello for Business where organizational architecture and risk requirements support it.

### 3. Clean Desk & Clear Screen Inspections

Perform recurring workplace security inspections to identify exposed credentials and other physical security weaknesses.

### 4. Governance and Accountability

Use security awareness, documented exceptions, retraining, and escalation processes to reinforce compliance.

## IT Audit Testing

The project includes three audit procedures:

| Control ID | Audit Focus | Frequency | Target |
|---|---|---|---|
| AUD-003.1 | Clean Desk inspection for exposed credentials | Monthly | 0 exposed passwords/MFA backup materials |
| AUD-003.2 | Enterprise Password Manager adoption | Monthly | >98% active-user utilization |
| AUD-003.3 | Security hygiene training completion | Quarterly | 100% completion |

## Evidence Examples

Potential audit evidence includes:

- Physical security sweep logs
- Compliance scorecards
- Incident and exception records
- Enterprise Password Manager administration exports
- License allocation reports
- Identity directory reports
- Learning Management System completion records
- Security training escalation records

## Repository Contents

```text
Password-Security-Remediation-GRC-Project/
├── README.md
├── .gitignore
├── data/
│   └── Password_Security_Remediation_Project.xlsx
└── documentation/
    ├── risk-assessment.md
    ├── control-mapping.md
    ├── audit-testing.md
    ├── remediation-plan.md
    └── password-security-policy.md
```

## GRC Lifecycle

**1. Identify** – Identify physical credential exposure and password fatigue.

**2. Assess** – Score likelihood and impact to establish inherent risk.

**3. Map** – Connect the risk and proposed controls to security frameworks.

**4. Treat** – Introduce password-management, passwordless-authentication, and clean-desk controls.

**5. Test** – Define audit procedures, evidence, frequency, and target metrics.

**6. Monitor** – Track adoption, exceptions, training completion, and exposed-credential findings.

**7. Remediate** – Escalate exceptions and validate corrective actions.

## Skills Demonstrated

GRC | IT Audit | IT Risk | Risk Assessment | Control Design | Compliance | ISO 27001 | NIST SP 800-53 | SOC 2 | Audit Testing | Evidence Collection | Security Metrics | Policy Development | Risk Remediation

## Disclaimer

This is a sanitized portfolio case study created for educational and professional demonstration purposes. It does not contain confidential organizational information, credentials, production configurations, or real security event data.
