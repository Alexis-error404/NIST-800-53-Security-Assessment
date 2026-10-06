# Findings & Recommendations

| ID | Finding | Control | Severity | Recommendation |
|---|---|---|---|---|
| F-001 | MFA absent for privileged access | IA-2 | Critical | Implement MFA |
| F-002 | Account reviews not documented | AC-2 | High | Quarterly access reviews |
| F-003 | Privileged certification informal | AC-6 | High | Review and justify privileged access |
| F-004 | Formal log review absent | AU-6 | High | Define monitoring and escalation |
| F-005 | Baseline validation informal | CM-2/CM-6 | Moderate | Document/validate baseline |
| F-006 | Patch tracking informal | SI-2 | High | Establish SLA and exception tracking |
| F-007 | Incident procedure absent | IR-4 | High | Develop and exercise IR process |

## Example Audit-Style Finding — F-001
**Condition:** MFA is not required for privileged access in the simulated environment.  
**Risk/Effect:** Compromised privileged credentials could provide broad administrative access.  
**Cause:** The home lab was originally designed for technical administration rather than production identity governance.  
**Recommendation:** Implement MFA, separate administrative and standard accounts, and monitor privileged authentication.  
**Status:** Open and tracked in the POA&M.
