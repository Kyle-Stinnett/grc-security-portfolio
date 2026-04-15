# Access Control Evidence (SOC 2 / ISO 27001)

## Control Objective
Ensure that only authorized users have access to systems and data.

## Control
All administrative and user access requires multi-factor authentication (MFA) and is reviewed quarterly.

## Evidence Provided

### 1. MFA Enforcement Evidence
- Screenshot or configuration export showing MFA enabled for all users
- Identity provider settings (e.g., AWS IAM, Okta)

### 2. User Access List
- Exported list of all active users (CSV format)
- Includes roles, permissions, and last login

### 3. Access Review Documentation
- Quarterly access review report
- Manager approvals documented
- Evidence of removed or adjusted access

### 4. Access Request Records
- Ticketing system logs (e.g., Jira, ServiceNow)
- Approval workflows for provisioning access

## Auditor Validation Steps

An auditor would:

1. Verify MFA is enforced across all accounts  
2. Review user access list for completeness  
3. Confirm quarterly access reviews occurred  
4. Validate approvals and removal of inappropriate access  

## Pass Criteria

- MFA is enforced for all users  
- Access reviews are completed and documented  
- No unauthorized or excessive access remains  
