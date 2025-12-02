# OctoAcme Project Management Docs

A central index and summary of project management best practices, workflows, templates, and roles for OctoAcme. This directory serves as the landing page for onboarding new team members and discovering process documentation quickly.

## Project Management Processes Summary

OctoAcme uses repeatable, documented processes for project management that span the entire project lifecycle. The framework covers **Initiation** (establishing clear project goals, stakeholder alignment, and decision gates), **Planning** (building an actionable backlog, risk management, milestone definition, and capacity alignment), **Execution & Tracking** (agile cadence with standups and demos, quality standards, and metrics-driven delivery), and **Release & Deployment** (standardized release checklists, rollback/incident response procedures, and stakeholder announcements).

Communication is central to OctoAcme's approach. The organization maintains a structured **Risks & Communication** process that includes a risk register lifecycle, regular stakeholder updates, and clear escalation paths. Teams follow a weekly sync cadence between Project Managers and Product Managers, twice-weekly standups for delivery teams, and monthly stakeholder updates. This ensures transparency and rapid issue resolution across all project phases.

Quality assurance is embedded throughout the delivery process. Teams are expected to maintain unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI. The **Retrospective & Continuous Improvement** process captures learnings at the end of each sprint, release, or milestone, converting them into actionable improvements tracked in the backlog.

Key roles include **Project Manager** (coordinates delivery, schedules, risk, and communications), **Product Manager** (defines outcomes, prioritizes backlog, and measures success), **Developers** (implement features and collaborate on design and testability), **QA/Testing** (validate quality and acceptance criteria), and **Stakeholders** (provide inputs and approvals). Key artifacts include one-pagers, project plans, checklists, templates, risk registers, and retrospective notes.

## Links to Process Documents

- [Project Management Overview](octoacme-project-management-overview.md) — Introduction to how OctoAcme runs projects, including principles and lifecycle overview
- [Project Initiation Guide](octoacme-project-initiation.md) — Initial steps to validate and authorize work, align stakeholders, and create a lightweight plan
- [Project Planning](octoacme-project-planning.md) — Turning an approved initiative into an actionable plan and backlog for delivery
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day execution guidance and tracking progress toward milestones
- [Risks & Communication](octoacme-risks-and-communication.md) — Identifying, managing, and communicating risks and dependencies
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardizing how OctoAcme releases features to production
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and converting them into actionable improvements
- [Roles & Personas](octoacme-roles-and-personas.md) — Typical roles and responsibilities used in OctoAcme projects

## How to Use These Docs

- **Keep the Project Charter updated** in the project repo for each active project.
- **Add process-specific docs into `.copilot/`** if you want Copilot Spaces to use them as context for AI-assisted project management.
- **Reference these docs** during project kickoffs, planning sessions, and retrospectives to ensure alignment with OctoAcme standards.

### Submitting Process Updates

To propose additions or updates to any process document, use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template. This ensures proper review and alignment with existing documentation.

## Acceptance Checklist

- [x] Content aligns with existing process docs
- [x] Update improves clarity or closes a documented gap
- [x] Proposed content has been reviewed with stakeholders (if needed)
