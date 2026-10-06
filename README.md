# NIST SP 800-53 Security Assessment Portfolio

A simulated GRC security-control assessment of a Windows Server / Active Directory environment using selected **NIST SP 800-53 Rev. 5** controls.

> **Portfolio disclaimer:** Educational home-lab simulation. This is not an official federal authorization or production client assessment.

## Scenario
I am acting as a Junior GRC / Security Controls Analyst assessing a fictional organization's Active Directory environment.

**In scope:** Windows Server domain controller, Active Directory, user and privileged accounts, Group Policy, Windows endpoints, security logs, and patch configuration.

## Assessment Workflow
1. Define system scope and boundary.
2. Select relevant security controls.
3. Define expected evidence.
4. Use examine, interview, and test concepts.
5. Assess implementation status.
6. Document findings and business risk.
7. Recommend remediation.
8. Track weaknesses in a POA&M-style artifact.

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
- MFA is absent for privileged access in the simulated environment.
- Formal recurring account and privileged-access reviews are incomplete.
- Security logging exists, but formal review/escalation procedures are missing.
- Patch and baseline validation require formal tracking.
- Incident handling procedures need to be documented and exercised.

## Repository Artifacts
- `assessment/security-control-assessment.md` — detailed control tests
- `assessment/findings-and-recommendations.md` — audit-style findings
- `governance/poam.md` — remediation tracking
- `evidence/evidence-guide.md` — evidence collection plan
- `interview/interview-guide.md` — interview questions and talking points

## Skills Demonstrated
NIST SP 800-53 · control assessment · evidence collection · gap analysis · POA&M · Active Directory security · least privilege · audit logging · remediation planning · risk communication

## 30-Second Interview Explanation
“I built a simulated NIST 800-53 assessment around a Windows Server and Active Directory lab. I selected controls relevant to identity, least privilege, logging, configuration management, patching, and incident response. For each control I defined expected evidence, assessed implementation, documented gaps and risk, and created remediation and POA&M items. It helped me connect technical administration with GRC and RMF work.”

**Target roles:** Junior GRC Analyst · ISSO · RMF Analyst · Security Compliance Analyst · Cybersecurity Risk Analyst
