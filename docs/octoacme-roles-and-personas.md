# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

## QA / Testing (existing entry expanded)

### Role Summary
QA ensures that the product meets quality and acceptance criteria before release.

### Responsibilities
- Define and execute test strategies and test plans
- Maintain automation and manual test coverage
- Provide timely feedback to Developers and PMs
- Sign off on release readiness in coordination with Release Manager

### Typical Communication
- QA standups or sync during sprint
- Test reports and release readiness updates

---

## New/Expanded Personas

### Scrum Master
Role Summary
- Facilitates Agile ceremonies, removes impediments, and helps teams follow agreed processes.

Responsibilities
- Run daily standups, sprint planning, review, and retrospective
- Track and help remove impediments and process blockers
- Coach on agile practices and continuous improvement
- Ensure healthy team cadence and predictable delivery

How they interact
- Works closely with PM and PdM to ensure sprint goals align with project goals.
- Helps Developers and QA optimize flow and remove blockers.
- Coordinates with Project Manager on cross-team dependencies.

---

### UX Designer
Role Summary
- Designs user experiences, validates designs with users, and ensures accessibility and usability.

Responsibilities
- Conduct user research and usability testing
- Produce wireframes, prototypes, and final visual specs
- Collaborate with PM and Developers to iterate on designs
- Validate acceptance criteria related to UX

How they interact
- Partners with Product Manager to refine requirements and acceptance criteria.
- Works with Developers to ensure designs are implemented correctly.
- Provides artifacts for QA to validate UX acceptance.

---

### QA Lead
Role Summary
- Owns the testing strategy for a project or release and coordinates QA activities.

Responsibilities
- Define test strategy, test plans, and coverage targets
- Schedule and coordinate manual and automated testing cycles
- Report test status and risk to PM and Release Manager
- Coordinate release sign-off with Release Manager

How they interact
- Collaborates with Developers to integrate testing earlier in the lifecycle.
- Works with Project Manager and Release Manager to plan QA windows.
- Escalates quality risks to Product and Project leadership.

---

### Release Manager
Role Summary
- Owns release planning, orchestration, and cross-team coordination for deployments.

Responsibilities
- Maintain release calendar and ensure pre-release gating criteria are met
- Coordinate deployment approvals, rollback plans, and communication
- Manage release cutover tasks and stakeholders during deployments
- Ensure post-deploy verification and incident coordination if needed

How they interact
- Works with QA Lead for release readiness sign off.
- Coordinates with Project Manager and Developers for rollouts.
- Communicates status and impact to stakeholders and Support.

---

### Support Lead
Role Summary
- Owns customer support readiness and post-release issue management.

Responsibilities
- Prepare support playbooks and runbooks for new releases
- Coordinate with Release Manager on go-to-support handoffs
- Triage incoming incidents and feed into backlog/incident response

How they interact
- Receives release notes and runbooks from Release Manager and PM
- Escalates customer-impacting issues to Project/ Product leadership

---

### Security Lead
Role Summary
- Ensures security considerations are included across the project lifecycle.

Responsibilities
- Conduct threat modeling and security reviews
- Coordinate security scans and track remediation
- Advise Product and Development on secure-by-design choices

How they interact
- Engages during planning and design phases with PM/PdM.
- Works with Devs/QA to verify fixes and monitor post-release.

---

## Role Interaction & Handoff Guidance (new section)

Purpose
- Reduce confusion by clarifying common handoffs and decision points between roles.

Key handoffs (examples)
- Product discovery -> Product Manager hands validated requirements to Project Manager and Scrum Master.
- Sprint preparation -> Product Manager provides prioritized backlog and acceptance criteria; Scrum Master and PM confirm scope with Developers and QA Lead.
- Release readiness -> QA Lead confirms test coverage; Release Manager coordinates deployment and Support Lead readiness; PM communicates stakeholder status.
- Incident escalation -> Support informs Project Manager and Product Manager; Security Lead engaged if security-related.

Best practices
- Document owners and approvers within the Project One-pager and Release notes.
- Use the Role Responsibility Matrix (see docs/role-responsibility-matrix.md) for RACI-style clarity on common activities.
- Record decisions and exceptions in the decision log to prevent single-person knowledge bottlenecks.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance and to create targeted onboarding artifacts.
