# OctoAcme Project Management Docs

This README provides an at-a-glance overview of OctoAcme's project management processes and quick links to all detailed documentation.

## Project Management Processes Summary

OctoAcme operates on a structured yet iterative project management approach centered around clear ownership, customer-first principles, and data-informed decision-making. The process flows through five key phases:

- **Initiation**: Validating business need, stakeholder alignment, and success criteria
- **Planning**: Breaking work into shippable increments, identifying dependencies and risks, defining scope and timelines
- **Execution**: Sprint/iteration cycles with daily standups, regular demos, quality checks, and blocker management
- **Release**: Pre-release QA, standardized deployment practices, rollback planning, and release notes
- **Close & Retrospective**: Capturing learnings and converting them into actionable improvements

Each project has a named **Project Manager (PM)** who coordinates delivery and timelines, and a **Product Manager (PdM)** who defines outcomes and measures success. These roles work together in weekly syncs to keep initiatives aligned and on track.

### Key Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Named PM and Product Lead for each project
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Team Rhythm
- **Daily standups** (15 min): Focus on progress, blockers, and dependencies
- **Weekly delivery syncs**: Show progress, updates, and flagged risks
- **Sprint/milestone-based demos**: Review and celebrate deliverables
- **Weekly PM + PdM sync**: Strategic alignment and issue resolution

### Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI pipelines
- Manual QA for feature acceptance when needed

### Risk Management & Communication
- Risks identified during planning and monitored weekly
- Escalation path: Team-level triage → PM → Product Lead → Sponsor
- Stakeholder updates on weekly or milestone basis
- Single source of truth for project status

## Process Documentation Directory

- [**Project Management Overview**](./octoacme-project-management-overview.md) — Introduction to OctoAcme's approach, roles, key artifacts, and lifecycle
- [**Project Initiation Guide**](./octoacme-project-initiation.md) — Initial steps to validate and authorize work, align stakeholders, and create a lightweight plan
- [**Project Planning**](./octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and backlog for delivery
- [**Execution & Tracking**](./octoacme-execution-and-tracking.md) — Guidance for managing day-to-day execution and tracking progress toward milestones
- [**Risk Management & Communication**](./octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks and dependencies
- [**Release & Deployment Guide**](./octoacme-release-and-deployment.md) — Standardize how OctoAcme releases features to production
- [**Retrospective & Continuous Improvement**](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements
- [**Roles & Personas**](./octoacme-roles-and-personas.md) — Definitions of typical roles and responsibilities in OctoAcme projects

## Quick Navigation

**Getting Started with a New Project?**
1. Start with [Project Initiation Guide](./octoacme-project-initiation.md)
2. Move to [Project Planning](./octoacme-project-planning.md)
3. Reference [Roles & Personas](./octoacme-roles-and-personas.md) to understand team structure

**Executing an Active Project?**
1. Use [Execution & Tracking](./octoacme-execution-and-tracking.md) for daily management
2. Consult [Risk Management & Communication](./octoacme-risks-and-communication.md) for escalations
3. Prepare for release with [Release & Deployment Guide](./octoacme-release-and-deployment.md)

**After a Milestone or Release?**
1. Run a retrospective using [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
2. Convert action items into improvements to your process

## Contributing to Process Docs

To propose updates or new content to these process documents, use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
