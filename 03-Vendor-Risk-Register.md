# Vendor Risk Register

## Assessment Information

**Organization:** Midwest Financial Services (MFS)  
**Vendor:** CloudHR Solutions  
**Service:** Cloud-based Human Resources Management System (HRMS)  
**Vendor Criticality:** High  
**Overall Inherent Risk:** High  
**Overall Residual Risk:** Moderate  
**Risk Treatment:** Mitigate  
**Vendor Decision:** Conditionally Approved

## Risk-Scoring Methodology

Likelihood and impact are rated on a three-point scale:

| Rating   | Score | Description                                             |
| -------- | ----: | ------------------------------------------------------- |
| Low      |     1 | Unlikely occurrence or limited organizational impact    |
| Moderate |     2 | Possible occurrence or meaningful organizational impact |
| High     |     3 | Likely occurrence or severe organizational impact       |

Risk scores are calculated as:

**Risk Score = Likelihood × Impact**

| Score | Risk Level |
| ----: | ---------- |
|   1–2 | Low        |
|   3–4 | Moderate   |
|   6–9 | High       |

## Risk Register

| Risk ID | Risk Description                                                                      | Likelihood | Impact | Inherent Risk | Existing Controls                                                          | Control Gaps                                                                                              | Residual Risk | Treatment |
| ------- | ------------------------------------------------------------------------------------- | ---------- | ------ | ------------- | -------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- | ------------- | --------- |
| VR-001  | Unauthorized users may gain excessive access to employee PII and payroll information. | Moderate   | High   | High          | MFA is reportedly enabled; data encryption is implemented.                 | MFA evidence was not provided; role-based access control and periodic access reviews are not implemented. | Moderate      | Mitigate  |
| VR-002  | Sensitive employee and payment information may be exposed during a security incident. | Moderate   | High   | High          | TLS 1.2 or higher protects data in transit; AES-256 protects data at rest. | Access-management weaknesses increase the possibility of unauthorized internal access.                    | Moderate      | Mitigate  |
| VR-003  | CloudHR Solutions may not respond to or notify MFS of a security incident promptly.   | Moderate   | High   | High          | The vendor reports having an incident-response plan.                       | The plan and evidence of testing within the past 12 months were not provided.                             | Moderate      | Mitigate  |
| VR-004  | Employee-related social engineering or phishing could result in unauthorized access.  | Moderate   | High   | High          | Annual security-awareness and phishing training were validated.            | Continued monitoring and recurring training are required.                                                 | Moderate      | Monitor   |

## Required Remediation

| Action ID | Remediation Action                                                                   | Priority | Owner               | Due Date       |
| --------- | ------------------------------------------------------------------------------------ | -------- | ------------------- | -------------- |
| RA-001    | Implement role-based access control based on job responsibilities.                   | High     | CloudHR IT/Security | Within 60 days |
| RA-002    | Establish and document quarterly user-access reviews.                                | High     | CloudHR IT/Security | Within 60 days |
| RA-003    | Provide evidence that MFA is enforced for administrative and remote-access accounts. | High     | CloudHR IT/Security | Within 60 days |
| RA-004    | Provide the current incident-response plan and recent testing results.               | High     | CloudHR Security    | Within 60 days |

## Approval and Monitoring

CloudHR Solutions is conditionally approved for use by MFS. The vendor must complete the required remediation and provide supporting evidence within 60 days. MFS will reassess the vendor every six months and initiate an immediate review following any significant security incident or unresolved high-priority finding.

**Final Residual Risk:** Moderate  
**Final Decision:** Conditionally Approved
