# Third-Party Vendor Risk Assessment

## Project Overview

This project demonstrates a third-party vendor risk assessment performed for Midwest Financial Services (MFS), a fictional financial-services organization. The assessment evaluates CloudHR Solutions, a high-criticality SaaS vendor that processes sensitive employee, payroll, banking, and authentication information.

The project covers vendor scoping, security due diligence, control evaluation, inherent and residual risk analysis, remediation planning, and a conditional approval decision.

## Business Scenario

MFS is considering CloudHR Solutions for payroll, employee-record management, benefits administration, and onboarding. Because the platform processes employee PII and payment-related information, a security assessment is required before full vendor approval.

## Assessment Results

| Category                      | Result                 |
| ----------------------------- | ---------------------- |
| Vendor Criticality            | High                   |
| Inherent Risk                 | High                   |
| Overall Control Effectiveness | Partially Effective    |
| Residual Risk                 | Moderate               |
| Risk Treatment                | Mitigate               |
| Final Decision                | Conditionally Approved |
| Remediation Period            | 60 days                |
| Reassessment Frequency        | Every six months       |

## Key Findings

- Encryption controls were validated and assessed as effective.
- Security-awareness and phishing training were validated.
- MFA was reported, but supporting evidence was not provided.
- Role-based access control and periodic access reviews were not implemented.
- The incident-response plan and recent testing results were not provided.

## Required Remediation

CloudHR Solutions must:

1. Implement role-based access control.
2. Establish quarterly user-access reviews.
3. Provide evidence of MFA enforcement.
4. Provide the current incident-response plan and recent testing results.

All high-priority remediation must be completed and validated within 60 days.

## Project Files

- [Vendor Profile and Scope](01-Vendor-Profile-and-Scope.md)
- [Vendor Security Questionnaire](02-Vendor-Security-Questionnaire.md)
- [Vendor Risk Register](03-Vendor-Risk-Register.md)
- [Remediation and Approval](04-Remediation-and-Approval.md)

## Skills Demonstrated

- Third-party risk management
- Vendor security due diligence
- Security-control assessment
- Evidence review and gap identification
- Inherent and residual risk scoring
- Risk-register development
- Remediation planning
- Vendor approval recommendations
- GRC documentation
- Risk-based decision-making

## Disclaimer

This project uses fictional organizations, systems, evidence, and assessment results for educational and portfolio purposes.
