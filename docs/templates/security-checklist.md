# Security Checklist

## Purpose
Checklist for security reviews, threat modeling, dependency vulnerability checks, and escalation paths. Ensures security considerations are addressed throughout the development lifecycle.

**Owner:** Security Champion

---

## Pre-Development Security Review

### Threat Modeling
- [ ] Assets and data flows identified
- [ ] Trust boundaries defined
- [ ] Potential threat actors and motivations documented
- [ ] STRIDE analysis completed (Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, Elevation of Privilege)
- [ ] Attack surface documented
- [ ] Risk ratings assigned to identified threats

### Security Requirements
- [ ] Authentication requirements defined
- [ ] Authorization and access control requirements defined
- [ ] Data protection requirements identified (encryption at rest/in transit)
- [ ] Audit logging requirements documented
- [ ] Compliance requirements reviewed (GDPR, SOC2, HIPAA, etc.)
- [ ] Input validation requirements specified

---

## Development Security Review

### Secure Coding Practices
- [ ] Input validation implemented for all user inputs
- [ ] Output encoding applied to prevent injection attacks
- [ ] Parameterized queries used for database access
- [ ] Sensitive data not logged or exposed in error messages
- [ ] Secrets managed securely (not hardcoded)
- [ ] Security headers configured appropriately

### Dependency Management
- [ ] Dependency vulnerability scan completed (Dependabot, Snyk, etc.)
- [ ] No critical or high severity vulnerabilities in dependencies
- [ ] Dependencies are up-to-date or update plan documented
- [ ] License compliance verified
- [ ] Software Bill of Materials (SBOM) generated (if required)

### Code Review Security Focus
- [ ] Security-focused code review completed
- [ ] Common vulnerability patterns checked (OWASP Top 10)
- [ ] Authentication/authorization logic reviewed
- [ ] Cryptographic implementations reviewed
- [ ] Error handling reviewed for information leakage

---

## Pre-Release Security Review

### Security Testing
- [ ] Static Application Security Testing (SAST) completed
- [ ] Dynamic Application Security Testing (DAST) completed (if applicable)
- [ ] Penetration testing completed (for significant releases)
- [ ] Security regression tests passing
- [ ] API security testing completed (if applicable)

### Infrastructure Security
- [ ] Network security configuration reviewed
- [ ] Firewall rules verified
- [ ] Access controls audited
- [ ] Secrets rotation plan in place
- [ ] Backup and recovery procedures verified

### Compliance & Documentation
- [ ] Security documentation updated
- [ ] Compliance checklist completed
- [ ] Risk acceptance documented (for known issues)
- [ ] Security release notes prepared (if applicable)

---

## Incident Response Readiness

### Preparation
- [ ] Incident response plan documented and accessible
- [ ] Security team escalation contacts current
- [ ] On-call rotation confirmed
- [ ] Communication templates prepared
- [ ] Forensic tools and access verified

### Detection & Monitoring
- [ ] Security monitoring enabled
- [ ] Alerting thresholds configured
- [ ] Log aggregation and retention verified
- [ ] Anomaly detection in place (if applicable)

---

## Escalation Path

### When to Escalate
- Critical or high severity vulnerability discovered
- Potential data breach or security incident
- Compliance violation identified
- Security blocking release

### Escalation Contacts

| Level | Role | When to Contact |
|-------|------|-----------------|
| 1 | Security Champion | First point of contact for security questions |
| 2 | Security Team Lead | Unresolved issues, critical vulnerabilities |
| 3 | CISO / Security Director | Incidents, breaches, executive decisions |
| 4 | Legal / Compliance | Regulatory issues, breach notifications |

### Escalation Process
1. Document the issue with severity assessment
2. Notify Security Champion immediately
3. Security Champion triages and escalates if needed
4. Follow incident response procedures for confirmed incidents
5. Document resolution and lessons learned

---

## Sign-off

| Role | Name | Date | Signature |
|------|------|------|-----------|
| Security Champion | | | |
| Engineering Manager | | | |
| Security Team Lead (if escalated) | | | |

---

## Notes
_Add any security-specific notes, exceptions, or follow-up items here._

---

*Related: [Roles and Personas](../octoacme-roles-and-personas.md) | [RACI Guidance](./raci-guidance.md) | [Release Checklist](./release-checklist.md)*
