# NIST SP 800-53 Security Assessment

A security control assessment of a Windows Server / Active Directory lab environment using selected **NIST SP 800-53 Rev. 5** controls.

> **Scope note:** This repository documents a lab-based assessment and is not an official federal authorization or production assessment.

## Environment in Scope
- Windows Server Domain Controller
- Active Directory Domain Services
- User and privileged accounts
- Group Policy Objects
- Windows endpoints
- Windows Security Event Logs
- Patch and update configuration

## Assessment Workflow
1. Define the system scope and boundary.
2. Select applicable security controls.
3. Identify required assessment evidence.
4. Apply examine, interview, and test assessment methods.
5. Determine implementation status.
6. Document findings and associated risk.
7. Recommend corrective actions.
8. Track remediation through a POA&M.

## Selected Controls
| Control | Area | Result |
|---|---|---|
| AC-2 | Account Management | Partially Implemented |
| AC-6 | Least Privilege | Partially Implemented |
| IA-2 | Identification & Authentication | Not Implemented |
| IA-5 | Authenticator Management | Partially Implemented |
| AU-2 | Event Logging | Partially Implemented |
| AU-6 | Audit Record Review | Not Implemented |
| CM-2 | Baseline Configuration | Partially Implemented |
| CM-6 | Configuration Settings | Partially Implemented |
| SI-2 | Flaw Remediation | Partially Implemented |
| IR-4 | Incident Handling | Not Implemented |

## Key Findings
- MFA is absent for privileged access in the assessed lab environment.
- Recurring account and privileged-access reviews require formal documentation.
- Security logging is enabled, but review and escalation procedures require further definition.
- Patch management and configuration-baseline validation require formal tracking.
- Incident handling procedures require documentation and testing.

## Repository Artifacts
- `assessment/security-control-assessment.md` — detailed control assessment
- `assessment/findings-and-recommendations.md` — findings and corrective actions
- `governance/poam.md` — remediation tracking
- `evidence/evidence-guide.md` — evidence collection and validation guidance

## Assessment Areas
NIST SP 800-53 · security control assessment · evidence collection · gap analysis · POA&M · Active Directory security · least privilege · audit logging · remediation planning · risk analysis
