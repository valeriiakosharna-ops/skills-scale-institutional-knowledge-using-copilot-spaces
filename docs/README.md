# OctoAcme Project Management Docs

This README provides an at-a-glance overview of OctoAcme's project management processes and quick links to all detailed documentation.

## Project Management Processes Overview

OctoAcme employs a structured, lifecycle-based approach to project management that emphasizes **clear ownership**, **iterative delivery**, and **data-informed decision-making**. Every project moves through five key phases with defined decision gates and consistent transparency.

### Core Lifecycle Phases

1. **Initiation**: New ideas are validated through a lightweight one-pager that confirms business need, identifies stakeholders, establishes success criteria, and gates go/no-go decisions.

2. **Planning**: Approved work is broken into shippable increments with prioritized backlogs, defined acceptance criteria, estimated scope, and identified dependencies and risks.

3. **Execution**: Teams deliver incrementally through sprint cycles, daily standups, weekly delivery syncs, demos, quality checks, and proactive blocker management.

4. **Release**: Features are deployed to production with comprehensive pre-release validation, automated testing, smoke tests, rollback plans, and stakeholder announcements.

5. **Close & Retrospective**: Learnings are captured in structured retrospectives and converted into actionable improvements tracked back into the project backlog.

### Key Principles

- **Customer-first**: Prioritize customer value and usability in all decisions.
- **Iterative delivery**: Deliver small, testable increments rather than big-bang releases.
- **Clear ownership**: Each project has a named Project Manager and Product Manager with defined responsibilities.
- **Data-informed decisions**: Measure impact and iterate based on evidence and metrics.
- **Psychological safety**: Encourage feedback, learning, and continuous improvement.

### Roles & Accountability

OctoAcme establishes clear accountability through well-defined roles:

- **Project Managers**: Coordinate schedules, manage risks and dependencies, facilitate meetings, and ensure consistent documentation and stakeholder communication.
- **Product Managers**: Define problem statements, prioritize the roadmap and backlog, establish success metrics, and validate solutions through data and user research.
- **Developers**: Design, build, test, and deliver features that meet acceptance criteria; write and maintain tests; participate in reviews and estimating.
- **QA/Testing**: Validate acceptance criteria, ensure quality standards, and conduct smoke tests and end-to-end verification.
- **Stakeholders**: Provide inputs, approvals, and strategic direction.

### Communication & Collaboration

OctoAcme maintains alignment through a consistent communication cadence:

- **Daily standups** (15 min): Focus on progress, blockers, and dependencies.
- **Weekly PM + Product Manager sync**: Alignment on priorities, risks, and decisions.
- **Twice-weekly delivery team standups**: Progress updates and coordination.
- **Weekly stakeholder updates**: Status reports using standardized templates.
- **Monthly stakeholder briefings**: High-level progress and strategic updates.

Ad-hoc escalations follow a three-tier model: team-level triage → PM/Product Lead → Sponsor involvement for business-critical issues.

### Quality & Risk Management

Quality and risk management are embedded throughout execution:

- **Quality practices**: Small pull requests (≤400 lines), automated CI testing, linting, security scanning, unit tests, integration tests, and end-to-end smoke tests.
- **Risk management**: Simple Risk Register tracking description, impact, likelihood, owner, and mitigation plan; reviewed weekly.
- **Escalation path**: Level 1 (daily standup) → Level 2 (PM to Product Lead) → Level 3 (Sponsor involvement).

### Continuous Improvement

Retrospectives are held after each sprint, release, or significant milestone. These structured sessions (45–75 minutes) capture what went well, identify improvements, and distill insights into 2–3 prioritized action items with clear owners and due dates. Improvements are tracked as backlog items and measured for impact, creating an iterative refinement cycle.

---

## Process Documentation Directory

Each of the documents below provides detailed guidance, checklists, and templates for its respective phase or function:

- **[Project Management Overview](./octoacme-project-management-overview.md)**  
  Concise introduction to OctoAcme's approach, core roles, key artifacts, and high-level lifecycle.

- **[Project Initiation Guide](./octoacme-project-initiation.md)**  
  Steps to validate and authorize work, align stakeholders, and create a lightweight plan. Includes the one-pager template and decision gate criteria.

- **[Project Planning](./octoacme-project-planning.md)**  
  Turn an approved initiative into an actionable plan and backlog. Covers kickoff, backlog creation, estimation, Definition of Done, and risk identification.

- **[Execution & Tracking](./octoacme-execution-and-tracking.md)**  
  Guidance for managing day-to-day execution and tracking progress. Includes team rhythm, PR workflow, quality standards, reporting, and blocker escalation.

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)**  
  How to identify, manage, and communicate risks and dependencies. Covers the Risk Register, stakeholder communication templates, and escalation paths.

- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)**  
  Standardize how OctoAcme releases features to production. Includes release types, pre-release requirements, deployment checklist, rollback playbooks, and release notes template.

- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)**  
  Capture learnings and convert them into actionable improvements. Covers retrospective structure, tracking improvements, and building a continuous improvement culture.

- **[Roles & Personas](./octoacme-roles-and-personas.md)**  
  Definitions of typical roles (Developers, Product Managers, Project Managers) used across OctoAcme projects, including responsibilities, goals, and communication patterns.

---

## How to Use These Docs

- **New team members**: Start with the [Project Management Overview](./octoacme-project-management-overview.md), then read the phase-specific guides as you engage with projects.
- **Project kickoff**: Reference the [Initiation Guide](./octoacme-project-initiation.md) and [Planning guide](./octoacme-project-planning.md) to set up a new project.
- **During execution**: Use the [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management](./octoacme-risks-and-communication.md) docs as your daily reference.
- **Before release**: Review the [Release & Deployment Guide](./octoacme-release-and-deployment.md) pre-release checklist.
- **Post-milestone**: Structure retrospectives using the [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) guide.

Keep the Project Charter updated in your project repo, and add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context for role-specific guidance.
