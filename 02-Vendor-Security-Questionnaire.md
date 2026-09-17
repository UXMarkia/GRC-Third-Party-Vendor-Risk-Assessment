# Vendor Security Questionnaire

## Assessment Information

**Organization:** Midwest Financial Services (MFS)  
**Vendor:** CloudHR Solutions  
**Service:** Cloud-based Human Resources Management System (HRMS)  
**Assessment Type:** Third-Party Security Due Diligence  
**Vendor Criticality:** High

## Questionnaire Results

| ID     | Security Domain                | Assessment Question                                                                     | Vendor Response | Evidence Status       | Assessment Result   |
| ------ | ------------------------------ | --------------------------------------------------------------------------------------- | --------------- | --------------------- | ------------------- |
| VSQ-01 | Identity and Access Management | Is multifactor authentication required for administrative and remote-access accounts?   | Yes             | Not provided          | Partially Effective |
| VSQ-02 | Data Protection                | Is sensitive information encrypted in transit and at rest?                              | Yes             | Provided and reviewed | Effective           |
| VSQ-03 | Access Management              | Are role-based access controls implemented and user-access reviews conducted regularly? | No              | Not applicable        | Ineffective         |
| VSQ-04 | Incident Response              | Does the vendor maintain and test a documented incident-response plan?                  | Yes             | Not provided          | Partially Effective |
| VSQ-05 | Security Awareness             | Are employees required to complete annual security-awareness and phishing training?     | Yes             | Provided and reviewed | Effective           |

## Evidence Reviewed

- Encryption configuration demonstrating TLS 1.2 or higher for data in transit
- Encryption configuration demonstrating AES-256 encryption for data at rest
- Security-awareness training policy
- Annual training-completion report
- Phishing-awareness training records

## Outstanding Evidence Requests

CloudHR Solutions must provide the following documentation:

- MFA policy or configuration evidence
- Screenshot showing MFA enforcement for administrative accounts
- Current incident-response plan
- Incident-response exercise or tabletop-testing results from the past 12 months

## Preliminary Findings

1. MFA could not be fully validated because supporting evidence was not provided.
2. Encryption controls were validated and assessed as effective.
3. Role-based access control and periodic user-access reviews are not implemented.
4. The incident-response program could not be fully validated because documentation and testing records were not provided.
5. Security-awareness training was validated and assessed as effective.

## Overall Control Assessment

CloudHR Solutions has implemented effective encryption and security-awareness controls. However, the absence of role-based access control and periodic access reviews creates a significant security gap. Missing evidence for MFA and incident-response testing further limits assurance that these controls operate effectively.

**Overall Control Effectiveness:** Partially Effective
