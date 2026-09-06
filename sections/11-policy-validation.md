# 11. POLICY VALIDATION

Since Week 3 focuses on security policy review rather than technical implementation, validation was conducted through policy walkthroughs and hypothetical security scenarios. The scenarios were used to determine whether the recommended policy controls provide clear and appropriate responses to common security situations. No live production systems or organizational security infrastructure were tested.

### 11.1 Validation Method

| Test ID | Scenario/Test | Expected Policy Response | Review Result | Status |
| --- | --- | --- | --- | --- |
| T-01 | Employee reports a phishing email. | Employee uses approved reporting channel; security team records and assesses the event. | The improved policy defines reporting, escalation and documentation actions. | Meets  Requirement |
| T-02 | Administrator account login occurs without MFA. | High-risk account should require MFA; exception should be documented if applicable. | MFA requirement is explicitly defined for administrator accounts. | Meets  Requirement |
| T-03 | Former employee account remains active. | Offboarding process should disable the account promptly. | Improved checklist includes account-status verification for each exit. | Meets  Requirement |
| T-04 | Critical vulnerability is discovered. | Vulnerability should be assigned, prioritized and remediated within defined SLA. | Improved policy requires severity-based remediation and tracking. | Meets  Requirement |
| T-05 | Critical backup needs restoration. | Organization should restore from a trusted backup and record the test result. | Improved policy requires documented restoration testing. | Meets  Requirement |
| T-06 | Vendor requests system access. | Access should be approved, limited and periodically reviewed. | Improved policy defines vendor assessment, minimum access and periodic review. | Meets  Requirement |
| T-07 | Sensitive file is shared externally. | Classification should determine whether external sharing is permitted and how it must be protected. | Data classification and handling rules are included in the recommendation. | Meets  Requirement |
| T-08 | Major security incident occurs. | Incident should be classified, escalated and communicated through authorized channels. | Improved policy defines severity, escalation and communication responsibilities. | Meets  Requirement |
| T-09 | Employee connects to organizational resources remotely. | Remote access should use approved methods, MFA and appropriate security controls. | Improved policy defines approved remote-access methods, MFA and device/security requirements. | Meets  Requirement |

### 11.2 Checklist Validation Result

The revised checklist was validated against the characteristics required for a practical security policy review. Each control includes a specific verification action, evidence to be checked, a frequency or trigger, and a status field. The validation confirms that the checklist can support a future internal audit or policy compliance review.

| Validation Criterion | Result |
| --- | --- |
| Specific action included | Pass |
| Evidence identified | Pass |
| Frequency/trigger included | Pass |
| Responsible control area identifiable | Pass |
| Risk linked to control gaps | Pass |
| Recommendation linked to gap | Pass |
| Scenario-based validation included | Pass |
| Future review/update mechanism included | Pass |
