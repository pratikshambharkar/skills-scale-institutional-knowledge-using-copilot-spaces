# OctoAcme Personas

## Overview

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It serves as a comprehensive reference for:

- **Understanding team structure:** Clarifying who does what across project functions
- **Project planning:** Identifying required roles for initiatives and creating RACI matrices
- **Onboarding:** Helping new team members understand the organizational landscape
- **Cross-team collaboration:** Mapping interactions and communication patterns between roles

Each persona includes a role summary, key responsibilities, goals, typical communication patterns, and—for extended personas—explicit RACI-style ownership guidance for common project activities.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Extended Personas

The following personas complement the core roles above to address additional functions commonly needed in project management, release coordination, security, documentation, and stakeholder engagement.

---

## Technical Program Manager (TPM)

### Role Summary
Technical Program Managers drive cross-functional programs and initiatives, coordinating multiple teams and workstreams to deliver complex projects. They bridge technical and business stakeholders, manage dependencies, and ensure alignment on timelines and deliverables.

### Responsibilities
- Lead cross-team coordination for complex programs and initiatives
- Manage program-level schedules, dependencies, and risks
- Facilitate alignment between engineering, product, and business stakeholders
- Drive program reviews and executive reporting
- Identify and resolve blockers across teams
- Ensure consistent process execution across workstreams

### Key Interactions
- **Product Manager:** Align on roadmap priorities and scope trade-offs
- **Engineering Manager:** Coordinate resources and technical dependencies
- **Delivery Lead/Scrum Master:** Sync on team-level execution and blockers
- **Release Engineer:** Coordinate release timing across programs
- **Risk Analyst:** Escalate and track program-level risks

### RACI-Style Ownership

| Activity | Ownership |
|----------|-----------|
| Project Planning | R (Responsible) |
| Release Orchestration | C (Consulted) |
| Incident Response | I (Informed) |
| Documentation Updates | I (Informed) |
| Security Reviews | I (Informed) |
| Onboarding New Hires | C (Consulted) |

---

## Release Engineer / Release Manager

### Role Summary
Release Engineers own the release process, ensuring that software is deployed reliably and efficiently. They manage release pipelines, coordinate deployment windows, and maintain rollback capabilities.

### Responsibilities
- Own and maintain CI/CD pipelines and release automation
- Coordinate release schedules and deployment windows
- Ensure rollback plans are documented and tested
- Monitor release health and post-deployment metrics
- Facilitate release retrospectives and process improvements
- Maintain release documentation and runbooks

### Key Interactions
- **Dev Team:** Coordinate code freeze and release branch management
- **QA Lead:** Ensure testing is complete before release
- **Security Champion:** Verify security scans pass before deployment
- **Support/Operations:** Coordinate production monitoring and on-call
- **TPM:** Align release timing with program milestones

### RACI-Style Ownership

| Activity | Ownership |
|----------|-----------|
| Project Planning | I (Informed) |
| Release Orchestration | R (Responsible) |
| Incident Response | C (Consulted) |
| Documentation Updates | I (Informed) |
| Security Reviews | I (Informed) |
| Onboarding New Hires | I (Informed) |

---

## Security Champion

### Role Summary
Security Champions are the embedded security advocates within development teams. They promote secure coding practices, conduct security reviews, and serve as the bridge between the development team and the central Security Team.

### Responsibilities
- Conduct security reviews and threat modeling for new features
- Promote secure coding practices and security awareness
- Review and triage security vulnerabilities and alerts
- Coordinate with the Security Team on escalations
- Ensure security requirements are met before release
- Maintain security documentation and checklists

### Key Interactions
- **Dev Team:** Advise on secure coding and review code changes
- **QA Lead:** Coordinate security testing efforts
- **Release Engineer:** Verify security gates before deployment
- **Security Team:** Escalate issues and align on policies
- **TPM:** Report on security status for program reviews

### RACI-Style Ownership

| Activity | Ownership |
|----------|-----------|
| Project Planning | I (Informed) |
| Release Orchestration | C (Consulted) |
| Incident Response | C (Consulted) |
| Documentation Updates | I (Informed) |
| Security Reviews | R/A (Responsible & Accountable) |
| Onboarding New Hires | I (Informed) |

---

## Documentation Owner / Documentation Specialist

### Role Summary
Documentation Owners ensure that project and product documentation is accurate, complete, and accessible. They maintain documentation standards and coordinate contributions from subject matter experts.

### Responsibilities
- Own and maintain documentation repositories and structure
- Ensure documentation is up-to-date with product changes
- Define and enforce documentation standards and templates
- Coordinate with developers and SMEs for technical content
- Review and edit documentation for clarity and consistency
- Support onboarding by ensuring documentation is accessible

### Key Interactions
- **Dev Team:** Gather technical details for documentation
- **Product Manager:** Align on user-facing documentation needs
- **Onboarding Coordinator:** Provide documentation for new hires
- **SME Pool:** Leverage expertise for specialized content
- **Communications Lead:** Coordinate on external documentation releases

### RACI-Style Ownership

| Activity | Ownership |
|----------|-----------|
| Project Planning | I (Informed) |
| Release Orchestration | I (Informed) |
| Incident Response | I (Informed) |
| Documentation Updates | R/A (Responsible & Accountable) |
| Security Reviews | I (Informed) |
| Onboarding New Hires | C (Consulted) |

---

## Onboarding Coordinator

### Role Summary
Onboarding Coordinators ensure new team members are set up for success. They manage the onboarding process, coordinate access and training, and track onboarding milestones.

### Responsibilities
- Own and maintain the onboarding checklist and process
- Coordinate access provisioning and environment setup
- Pair new hires with mentors and buddies
- Track onboarding progress and gather feedback
- Continuously improve the onboarding experience
- Liaise with HR and IT for administrative setup

### Key Interactions
- **Engineering Manager:** Coordinate team-specific onboarding
- **Documentation Owner:** Ensure documentation is onboarding-ready
- **Dev Team:** Facilitate introductions and mentorship
- **HR/IT:** Coordinate administrative and access setup
- **TPM:** Include onboarding in program planning for new initiatives

### RACI-Style Ownership

| Activity | Ownership |
|----------|-----------|
| Project Planning | I (Informed) |
| Release Orchestration | I (Informed) |
| Incident Response | I (Informed) |
| Documentation Updates | I (Informed) |
| Security Reviews | I (Informed) |
| Onboarding New Hires | R (Responsible) |

---

## QA Lead / Test Architect

### Role Summary
QA Leads define and oversee testing strategy, ensuring quality standards are met across the development lifecycle. They guide the team on testing best practices and own test infrastructure.

### Responsibilities
- Define and maintain the testing strategy and standards
- Own test infrastructure, frameworks, and automation
- Review and approve test plans and coverage
- Coordinate testing efforts across teams and releases
- Analyze quality metrics and drive improvements
- Mentor team members on testing best practices

### Key Interactions
- **Dev Team:** Collaborate on test design and automation
- **Release Engineer:** Verify test completion before release
- **Security Champion:** Coordinate security testing
- **Product Manager:** Align on acceptance criteria and coverage
- **Support/Operations:** Review production issues for test gaps

### RACI-Style Ownership

| Activity | Ownership |
|----------|-----------|
| Project Planning | C (Consulted) |
| Release Orchestration | C (Consulted) |
| Incident Response | C (Consulted) |
| Documentation Updates | I (Informed) |
| Security Reviews | I (Informed) |
| Onboarding New Hires | I (Informed) |

---

## Change Manager / Change Advisory Liaison

### Role Summary
Change Managers oversee the change management process, ensuring changes are assessed, approved, and communicated appropriately. They facilitate the Change Advisory Board (CAB) and maintain change records.

### Responsibilities
- Own the change management process and policies
- Facilitate Change Advisory Board (CAB) meetings
- Review and approve change requests
- Ensure changes are documented and communicated
- Track change success rates and incidents related to changes
- Coordinate with Release Engineers on deployment windows

### Key Interactions
- **Release Engineer:** Coordinate change approvals for releases
- **Engineering Manager:** Review significant technical changes
- **Support/Operations:** Assess impact and readiness for changes
- **Risk Analyst:** Evaluate change-related risks
- **Communications Lead:** Coordinate change announcements

### RACI-Style Ownership

| Activity | Ownership |
|----------|-----------|
| Project Planning | C (Consulted) |
| Release Orchestration | C (Consulted) |
| Incident Response | I (Informed) |
| Documentation Updates | I (Informed) |
| Security Reviews | I (Informed) |
| Onboarding New Hires | I (Informed) |

---

## Communications Lead

### Role Summary
Communications Leads manage internal and external communications for projects and releases. They ensure stakeholders are informed, coordinate announcements, and maintain communication templates and channels.

### Responsibilities
- Own communication plans for projects and releases
- Draft and distribute announcements and status updates
- Maintain communication templates and channels
- Coordinate with stakeholders on messaging and timing
- Support incident communications and post-mortems
- Ensure consistent messaging across teams and external audiences

### Key Interactions
- **Product Manager:** Align on product announcements and messaging
- **Release Engineer:** Coordinate release announcements
- **Support/Operations:** Support incident communications
- **Business Stakeholder Liaison:** Ensure stakeholder messaging is aligned
- **Change Manager:** Coordinate change announcements

### RACI-Style Ownership

| Activity | Ownership |
|----------|-----------|
| Project Planning | I (Informed) |
| Release Orchestration | C (Consulted) |
| Incident Response | C (Consulted) |
| Documentation Updates | C (Consulted) |
| Security Reviews | I (Informed) |
| Onboarding New Hires | I (Informed) |

---

## Risk Analyst

### Role Summary
Risk Analysts identify, assess, and track risks across projects and programs. They support risk-informed decision-making and maintain the risk register.

### Responsibilities
- Identify and assess project and program risks
- Maintain and update the risk register
- Facilitate risk review sessions
- Recommend mitigations and escalate as needed
- Report on risk status to stakeholders
- Support incident post-mortems and lessons learned

### Key Interactions
- **TPM:** Report on program-level risks
- **Project Manager:** Track project-specific risks
- **Engineering Manager:** Assess technical risks
- **Change Manager:** Evaluate change-related risks
- **Security Champion:** Coordinate on security risks

### RACI-Style Ownership

| Activity | Ownership |
|----------|-----------|
| Project Planning | C (Consulted) |
| Release Orchestration | I (Informed) |
| Incident Response | C (Consulted) |
| Documentation Updates | I (Informed) |
| Security Reviews | C (Consulted) |
| Onboarding New Hires | I (Informed) |

---

## Business Stakeholder Liaison

### Role Summary
Business Stakeholder Liaisons serve as the bridge between project teams and business stakeholders. They gather requirements, communicate progress, and ensure business needs are represented in project decisions.

### Responsibilities
- Gather and communicate business requirements and priorities
- Represent business stakeholder interests in project discussions
- Facilitate stakeholder reviews and approvals
- Communicate project status and decisions to business stakeholders
- Identify and escalate stakeholder concerns
- Support change management communications

### Key Interactions
- **Product Manager:** Align on requirements and priorities
- **TPM:** Provide stakeholder input for program planning
- **Communications Lead:** Coordinate stakeholder messaging
- **Project Manager:** Report on stakeholder engagement
- **Change Manager:** Support change communication to stakeholders

### RACI-Style Ownership

| Activity | Ownership |
|----------|-----------|
| Project Planning | C (Consulted) |
| Release Orchestration | I (Informed) |
| Incident Response | I (Informed) |
| Documentation Updates | I (Informed) |
| Security Reviews | I (Informed) |
| Onboarding New Hires | I (Informed) |

---

## Subject Matter Expert (SME) Pool

### Role Summary
Subject Matter Experts provide deep expertise in specific domains, technologies, or business areas. They are consulted for specialized knowledge and support complex problem-solving.

### Responsibilities
- Provide expert guidance on specialized topics
- Support complex technical or business decisions
- Contribute to documentation and knowledge sharing
- Mentor team members in their area of expertise
- Participate in design reviews and architecture discussions
- Support incident response for issues in their domain

### Key Interactions
- **Dev Team:** Advise on technical implementation
- **Documentation Owner:** Contribute specialized content
- **TPM:** Support complex program decisions
- **Security Champion:** Advise on domain-specific security considerations
- **QA Lead:** Support specialized testing needs

### RACI-Style Ownership

| Activity | Ownership |
|----------|-----------|
| Project Planning | C (Consulted) |
| Release Orchestration | I (Informed) |
| Incident Response | C (Consulted) |
| Documentation Updates | C (Consulted) |
| Security Reviews | C (Consulted) |
| Onboarding New Hires | C (Consulted) |

---

## Sample RACI Matrix for Common Activities

The following matrix provides a comprehensive view of RACI assignments for common project activities across all personas. For detailed guidance on creating and using RACI matrices, see [RACI Guidance](./templates/raci-guidance.md).

| Activity | Product Manager | Engineering Manager | TPM | Delivery Lead/Scrum Master | Dev Team | QA Lead | Release Engineer | Security Champion | Documentation Owner | Support/Ops | Onboarding Coordinator | Change Manager | Communications Lead | Risk Analyst | Business Stakeholder Liaison | SME Pool |
|----------|-----------------|---------------------|-----|----------------------------|----------|---------|-------------------|-------------------|---------------------|-------------|------------------------|----------------|---------------------|--------------|------------------------------|----------|
| **Project Planning** | A | C | R | C | C | C | I | I | I | I | I | C | I | C | C | C |
| **Release Orchestration** | I | A | C | C | I | C | R | C | I | I | I | C | C | I | I | I |
| **Incident Response** | I | A | I | C | R | C | C | C | I | R | I | I | C | C | I | C |
| **Documentation Updates** | C | I | I | I | C | I | I | I | R/A | I | I | I | C | I | I | C |
| **Security Reviews** | I | C | I | I | C | I | I | R/A | I | I | I | I | I | C | I | C |
| **Onboarding New Hires** | I | A | C | C | C | I | I | I | C | I | R | I | I | I | I | C |

**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (ultimate owner)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)

---

## Using Personas for Project Planning

When creating project plans and RACI matrices:

1. **Identify required roles:** Review the personas above and determine which roles are needed for your project
2. **Map activities to owners:** Use the RACI-style ownership tables to assign responsibilities
3. **Create a project-specific RACI:** Customize the sample matrix for your project's unique activities
4. **Validate with stakeholders:** Review assignments with the individuals in each role
5. **Document and share:** Include the RACI in your project charter or planning docs
6. **Review regularly:** Update the RACI as the project evolves

For detailed guidance and a template, see [RACI Guidance](./templates/raci-guidance.md).

---

## Next Steps

Use the following checklists and templates to operationalize these personas:

- [ ] Review the [Release Checklist](./templates/release-checklist.md) for release coordination
- [ ] Use the [Onboarding Checklist](./templates/onboarding-checklist.md) for new team member onboarding
- [ ] Consult the [RACI Guidance](./templates/raci-guidance.md) when creating project-specific RACI matrices
- [ ] Apply the [Security Checklist](./templates/security-checklist.md) for security reviews

---

*See also: [Project Management Overview](./octoacme-project-management-overview.md) | [Release & Deployment Guide](./octoacme-release-and-deployment.md)*

