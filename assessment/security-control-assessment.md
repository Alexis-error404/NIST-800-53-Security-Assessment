# Security Control Assessment

## Method
For each control I considered **Examine, Interview, and Test** procedures and recorded an implementation conclusion.

### AC-2 — Account Management
**Evidence:** AD account inventory, enabled/disabled status, group memberships, last-logon information, lifecycle procedure.  
**Interview:** Who approves accounts? How quickly are terminated accounts disabled? How often are accounts reviewed?  
**Test:** Sample accounts and validate status, membership, and continued need.  
**Assessment:** Partially Implemented.  
**Finding:** Formal periodic access review is not documented.  
**Risk:** Dormant or unnecessary accounts may retain access.  
**Recommendation:** Quarterly access reviews, defined disablement timelines, and retained evidence.

### AC-6 — Least Privilege
**Evidence:** Domain Admins/Enterprise Admins membership, local admin assignments, dedicated admin accounts.  
**Assessment:** Partially Implemented.  
**Finding:** Formal privileged-access certification is not documented.  
**Recommendation:** Minimize privileged membership, use dedicated admin accounts, and periodically certify access.

### IA-2 — Identification and Authentication
**Evidence:** Authentication and MFA configuration.  
**Assessment:** Not Implemented for MFA in this scenario.  
**Finding:** Privileged accounts rely on password-based authentication.  
**Risk:** Stolen credentials could enable administrative access.  
**Recommendation:** Require MFA for privileged and remote administrative access.

### IA-5 — Authenticator Management
**Evidence:** Domain password and account lockout policy.  
**Assessment:** Partially Implemented.  
**Recommendation:** Define approved authentication requirements and validate GPO enforcement.

### AU-2 — Event Logging
**Evidence:** Advanced Audit Policy, Security Event Log, retention configuration.  
**Assessment:** Partially Implemented.  
**Recommendation:** Define required security events, retention, and centralized collection where appropriate.

### AU-6 — Audit Record Review
**Assessment:** Not Implemented.  
**Finding:** No formal recurring log-review process.  
**Risk:** Suspicious activity may remain undetected.  
**Recommendation:** Establish review cadence, alert thresholds, escalation, and review evidence.

### CM-2 / CM-6 — Baseline and Configuration Settings
**Assessment:** Partially Implemented.  
**Finding:** Secure baseline and validation process are not formally documented.  
**Recommendation:** Document approved settings, manage exceptions, and validate periodically.

### SI-2 — Flaw Remediation
**Assessment:** Partially Implemented.  
**Finding:** Patch compliance and exceptions require formal tracking.  
**Recommendation:** Define remediation timelines, track deployment/exceptions, and validate closure.

### IR-4 — Incident Handling
**Assessment:** Not Implemented.  
**Recommendation:** Establish preparation, detection/analysis, containment, eradication, recovery, and lessons-learned procedures.

## Conclusion
Technical settings alone do not demonstrate a mature control environment. Governance requires repeatable processes, ownership, evidence, review, exception handling, and remediation tracking.
