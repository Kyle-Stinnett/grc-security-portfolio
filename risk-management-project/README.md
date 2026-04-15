# Risk Management Project
This project demonstrates a practical approach to identifying, assessing, and mitigating cybersecurity risks in a mid-sized enterprise environment.

## Business Context

This scenario represents a SaaS organization responsible for protecting sensitive customer data, where inadequate access controls could result in regulatory, financial, and reputational impact.

## Scenario
A fictional SaaS company handling customer data lacks formalized security controls, increasing the risk of unauthorized access and data exposure.

## Methodology
Risks are evaluated using:
- Likelihood (1–5)
- Impact (1–5)
- Risk Score = Likelihood × Impact

## Sample Risk Analysis

### Risk: Unauthorized System Access
- Likelihood: 4 (High due to lack of MFA)
- Impact: 5 (Critical systems exposed)
- Risk Score: 20 (High)

### Root Cause
- No multi-factor authentication (MFA)
- Weak access control policies

### Mitigation Plan
- Implement MFA across all systems
- Conduct quarterly access reviews
- Enforce least privilege access

## Evidence Request List (Audit Support)

As part of audit preparation, the following evidence would be requested to validate control effectiveness:

### Access Control
- User access list (including roles and permissions)
- Evidence of MFA enforcement (screenshots or configuration export)
- Access review documentation (quarterly reviews, approvals)

### Change Management
- Change request tickets
- Approval records for system changes
- Deployment logs or release documentation

### Logging & Monitoring
- Sample system logs
- Evidence of log review processes
- Alerts or incident tickets generated from monitoring tools

### Backup & Recovery
- Backup configuration documentation
- Evidence of recent backup tests
- Recovery test results

## Purpose

This evidence ensures that implemented controls are functioning as intended and can be validated during an audit.

Regular follow-ups would be conducted to ensure remediation timelines are met.

## Stakeholder Coordination
To remediate this risk, I would work with:
- Engineering teams to implement MFA  
- IT administrators to enforce access controls  
- Management to review and approve access changes  

Regular follow-ups would be conducted to ensure remediation timelines are met.

## Potential Challenges

- Engineering teams may have competing priorities delaying MFA implementation  
- Incomplete user inventories may impact access review accuracy  
- Resistance to access changes from business users  

These challenges would be addressed through prioritization, escalation, and clear communication of risk impact.
## Framework Alignment
- ISO 27001: A.9 (Access Control)
- SOC 2: CC6 (Logical Access)
- NIST CSF: PR.AC (Access Control)

## Outcome
This risk was prioritized as high and requires immediate remediation to reduce exposure.

## Success Metrics

- 87% of systems with MFA enabled  
- Number of access violations identified and remediated  
- Time to remediate identified risks  

## Key Takeaway

Effective risk management requires not only identifying and mitigating risks, but also coordinating across teams, managing real-world challenges, and ensuring sustained control effectiveness.
