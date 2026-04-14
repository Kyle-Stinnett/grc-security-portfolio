# SOC 2 Audit Simulation

This project simulates a SOC 2 audit for a SaaS organization.

## Objective
Demonstrate how an organization prepares for and responds to a SOC 2 audit.

## Scope
- User access management
- Change management
- Logging and monitoring

## Example Control

### Control: User Access Reviews
Management performs quarterly reviews of user access to ensure appropriate permissions.

### Audit Evidence
- Access review reports
- User access lists
- Approval records

### Testing Approach
- Verify reviews are performed quarterly
- Confirm evidence of management approval
- Ensure inappropriate access is removed

## Outcome
The control is considered effective if all users are reviewed and discrepancies are resolved.
## Auditor Testing Approach

As an auditor, I would:

1. Obtain a list of all system users
2. Review evidence of quarterly access reviews
3. Select a sample of users and verify:
   - Access is appropriate for role
   - Unauthorized access is removed
4. Confirm management approval is documented

## Pass Criteria
- All users reviewed quarterly
- Evidence of approval exists
- No excessive privileges remain
