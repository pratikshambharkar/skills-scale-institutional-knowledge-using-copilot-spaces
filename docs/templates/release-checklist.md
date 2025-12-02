# Release Checklist

## Purpose
A practical pre-release checklist to ensure releases are well-coordinated, risks are mitigated, and stakeholders are informed.

**Owner:** Release Engineer / Release Manager

---

## Pre-Release Checklist

### Pipeline Health
- [ ] All CI pipelines passing on release branch
- [ ] No critical/blocker issues open in the release scope
- [ ] Security scans completed and no high/critical vulnerabilities outstanding
- [ ] Code coverage meets minimum threshold

### Documentation & Runbooks
- [ ] Deployment runbook reviewed and up to date
- [ ] Release notes drafted and reviewed
- [ ] Migration steps documented (if applicable)
- [ ] User-facing documentation updated

### Rollback Plan
- [ ] Rollback procedure documented and tested
- [ ] Previous stable version identified for rollback
- [ ] Database rollback/migration reversal plan in place (if applicable)
- [ ] Feature flags configured for quick disable (if applicable)

### Stakeholder Approvals
- [ ] Product Manager sign-off obtained
- [ ] Engineering Manager sign-off obtained
- [ ] Security Champion review completed (if security-relevant changes)
- [ ] QA Lead sign-off on test results

### Release Window
- [ ] Release window scheduled and communicated
- [ ] On-call support confirmed for release window
- [ ] Change Advisory Board (CAB) approval obtained (if required)
- [ ] Communications Lead notified for announcements

### Deployment Steps
- [ ] Staging deployment completed successfully
- [ ] Smoke tests passed on staging
- [ ] Production deployment executed
- [ ] Post-deployment verification completed

### Monitoring & Validation
- [ ] Monitoring dashboards reviewed pre-release
- [ ] Alerting thresholds confirmed
- [ ] Post-release monitoring period defined
- [ ] Key metrics baseline captured for comparison

---

## Post-Release Validation

- [ ] All critical user flows verified in production
- [ ] No unexpected errors in logs or monitoring
- [ ] Performance metrics within expected range
- [ ] Stakeholders notified of successful release
- [ ] Release retrospective scheduled (if needed)

---

## Sign-off

| Role | Name | Date | Signature |
|------|------|------|-----------|
| Release Engineer | | | |
| Product Manager | | | |
| Engineering Manager | | | |
| QA Lead | | | |

---

## Notes
_Add any release-specific notes, known issues, or follow-up items here._

---

*Related: [Roles and Personas](../octoacme-roles-and-personas.md) | [RACI Guidance](./raci-guidance.md)*
