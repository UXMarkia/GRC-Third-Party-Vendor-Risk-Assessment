# Remediation and Vendor Approval

## Assessment Summary

**Organization:** Midwest Financial Services (MFS)  
**Vendor:** CloudHR Solutions  
**Service:** Cloud-based Human Resources Management System (HRMS)  
**Assessment Date:** September 17, 2026  
**Vendor Criticality:** High  
**Inherent Risk:** High  
**Residual Risk:** Moderate  
**Risk Treatment:** Mitigate  
**Approval Status:** Conditionally Approved

## Approval Recommendation

CloudHR Solutions is recommended for conditional approval. The vendor provides essential payroll, employee-record, benefits, and onboarding services and processes highly sensitive employee and payment information.

Validated encryption and security-awareness controls reduce portions of the vendor’s risk. However, access-management weaknesses and missing evidence for MFA and incident-response testing prevent full approval at this time.

The vendor may continue through the onboarding process provided that all high-priority remediation requirements are completed and validated within 60 days.

## Remediation Plan

| Action ID | Finding                                                           | Required Action                                                                                                                     | Priority | Responsible Owner   | Target Date    | Status |
| --------- | ----------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- | -------- | ------------------- | -------------- | ------ |
| RA-001    | Role-based access control is not implemented.                     | Implement role-based access control based on job responsibilities and least-privilege principles.                                   | High     | CloudHR IT/Security | Within 60 days | Open   |
| RA-002    | Periodic user-access reviews are not performed.                   | Establish and document quarterly access reviews for privileged and standard user accounts.                                          | High     | CloudHR IT/Security | Within 60 days | Open   |
| RA-003    | MFA was reported but not validated.                               | Provide MFA policy, configuration evidence, or screenshots demonstrating enforcement for administrative and remote-access accounts. | High     | CloudHR IT/Security | Within 60 days | Open   |
| RA-004    | The incident-response plan and testing records were not provided. | Submit the current incident-response plan and results from an exercise completed within the past 12 months.                         | High     | CloudHR Security    | Within 60 days | Open   |

## Validation Requirements

MFS will validate remediation by reviewing:

- Role and permission configuration documentation
- Results from the initial user-access review
- Evidence of MFA enforcement
- The current incident-response plan
- Incident-response exercise or tabletop-testing records

A remediation item will remain open until acceptable evidence has been reviewed and approved by MFS Security or the designated third-party risk owner.

## Monitoring Requirements

- Review remediation evidence at the end of the 60-day period.
- Reassess CloudHR Solutions every six months.
- Require immediate notification of any actual or suspected security incident affecting MFS information.
- Escalate overdue high-priority remediation to MFS management.
- Reconsider vendor approval if remediation is not completed or validated.

## Approval Conditions

Conditional approval is based on the following requirements:

1. CloudHR Solutions must complete all high-priority remediation within 60 days.
2. The vendor must provide sufficient evidence for MFS to validate each remediation item.
3. CloudHR Solutions must notify MFS promptly of material security incidents.
4. Continued use of the vendor is subject to six-month reassessments.
5. Unresolved findings may result in restricted access, suspension, or termination of the vendor relationship.

## Final Decision

**Decision:** Conditionally Approved  
**Residual Risk:** Moderate  
**Reassessment Frequency:** Every six months  
**Remediation Period:** 60 days

CloudHR Solutions may be approved for use while remediation is in progress. Full approval should be granted only after MFS validates that the identified access-management and evidence gaps have been addressed.

## Approval Record

| Role                         | Decision                       | Name            | Date               |
| ---------------------------- | ------------------------------ | --------------- | ------------------ |
| Third-Party Risk Analyst     | Recommend Conditional Approval | Project Analyst | September 17, 2026 |
| Information Security Manager | Pending Review                 |                 |                    |
| Business Owner               | Pending Review                 |                 |                    |
