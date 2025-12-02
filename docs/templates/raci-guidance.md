# RACI Guidance

## Purpose
Provide guidance on how to create and use RACI matrices for project activities, ensuring clear ownership and accountability across roles and personas.

---

## What is RACI?

RACI is a responsibility assignment matrix that clarifies roles for each activity or deliverable:

| Letter | Role | Description |
|--------|------|-------------|
| **R** | Responsible | The person(s) who do the work to complete the activity |
| **A** | Accountable | The person who is ultimately answerable for the activity (there should be only one A per activity) |
| **C** | Consulted | People who provide input and whose opinions are sought (two-way communication) |
| **I** | Informed | People who are kept up-to-date on progress or decisions (one-way communication) |

---

## When to Use RACI

- **Project kickoff:** Define ownership for key activities early
- **Cross-functional initiatives:** Clarify handoffs between teams
- **Process changes:** Document who is responsible during transitions
- **Incident response:** Ensure clear escalation paths
- **Onboarding:** Help new team members understand their role in processes

---

## How to Build a RACI Matrix

1. **List activities:** Identify key activities, deliverables, or decisions
2. **Identify roles:** List all relevant roles/personas
3. **Assign R, A, C, I:** For each activity, assign responsibility codes
4. **Validate:** Ensure each activity has exactly one A (Accountable)
5. **Review with stakeholders:** Get buy-in from all parties
6. **Document and share:** Keep the matrix accessible and up-to-date

---

## Tips for Effective RACI

- **One Accountable per activity:** Avoid confusion by having a single decision-maker
- **Limit Consulted:** Too many C's can slow decisions
- **Be specific:** Use clear, actionable activity descriptions
- **Review regularly:** Update the RACI as roles or processes change
- **Combine with checklists:** Link RACI to operational checklists for execution

---

## Sample RACI Matrix

The following example maps common project activities to OctoAcme personas:

| Activity | Product Manager | Engineering Manager | TPM | Delivery Lead/Scrum Master | Dev Team | QA Lead | Release Engineer | Security Champion | Documentation Owner | Support/Ops |
|----------|-----------------|---------------------|-----|----------------------------|----------|---------|-------------------|-------------------|---------------------|-------------|
| **Project Planning** | A | C | R | C | C | C | I | I | I | I |
| **Release Orchestration** | I | A | C | C | I | C | R | C | I | I |
| **Incident Response** | I | A | I | C | R | C | C | C | I | R |
| **Documentation Updates** | C | I | I | I | C | I | I | I | R/A | I |
| **Security Reviews** | I | C | I | I | C | I | I | R/A | I | I |
| **Onboarding New Hires** | I | A | C | C | C | I | I | I | C | I |

**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (ultimate owner)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)

---

## Extended RACI with Additional Personas

For larger teams, include additional personas:

| Activity | Product Manager | Engineering Manager | TPM | Dev Team | QA Lead | Release Engineer | Security Champion | Documentation Owner | Onboarding Coordinator | Change Manager | Communications Lead | Risk Analyst | Business Stakeholder Liaison | SME Pool |
|----------|-----------------|---------------------|-----|----------|---------|-------------------|-------------------|---------------------|------------------------|----------------|---------------------|--------------|------------------------------|----------|
| **Project Planning** | A | C | R | C | C | I | I | I | I | C | I | C | C | C |
| **Release Orchestration** | I | A | C | I | C | R | C | I | I | C | C | I | I | I |
| **Incident Response** | I | A | I | R | C | C | C | I | I | I | C | C | I | C |
| **Documentation Updates** | C | I | I | C | I | I | I | R/A | I | I | C | I | I | C |
| **Security Reviews** | I | C | I | C | I | I | R/A | I | I | I | I | C | I | C |
| **Onboarding New Hires** | I | A | C | C | I | I | I | C | R | I | I | I | I | C |

---

## Using RACI with Project Plans

When creating project plans:

1. Reference the [Roles and Personas](../octoacme-roles-and-personas.md) document
2. Create a project-specific RACI for unique activities
3. Link RACI assignments to task owners in your project management tool
4. Review RACI during kickoff and at major milestones
5. Use the RACI to resolve ownership disputes or gaps

---

## Related Resources

- [Roles and Personas](../octoacme-roles-and-personas.md)
- [Release Checklist](./release-checklist.md)
- [Onboarding Checklist](./onboarding-checklist.md)
- [Security Checklist](./security-checklist.md)
