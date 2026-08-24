# OctoAcme Project Management Process Documentation

Welcome to the OctoAcme project management process library. This documentation centralizes how we run projects, align stakeholders, deliver value, and continuously improve.

## Our Approach

OctoAcme follows a structured yet flexible project management approach built on these core principles:

- **Customer-first**: We prioritize customer value and usability in every decision
- **Iterative delivery**: We deliver small, testable increments to gather feedback early
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: We measure impact and iterate based on evidence
- **Psychological safety**: We encourage feedback, learning, and blameless retrospectives

## Project Lifecycle

All OctoAcme projects follow these stages:

1. **Initiation** - Validate the business need, align stakeholders, and gain approval
2. **Planning** - Define scope, create a prioritized backlog, and establish success metrics
3. **Execution** - Build, test, and deliver iteratively with regular demos and feedback
4. **Release** - Deploy to production with proper verification and communication
5. **Close & Retrospective** - Capture learnings and feed improvements back into our processes

## Core Roles

- **Project Manager (PM)** - Coordinates delivery, schedules, risk, and communications
- **Product Manager (PdM)** - Defines outcomes, prioritizes the backlog, and measures success
- **Developers** - Implement features, collaborate on design, and maintain quality standards
- **QA/Testing** - Validates quality and acceptance criteria
- **Stakeholders** - Provide inputs, approvals, and strategic guidance

## OctoAcme Project Management Process Summary

### Project Lifecycle & Core Workflow

OctoAcme follows a structured five-phase project lifecycle: **Initiation, Planning, Execution, Release, and Close & Retrospective**. The **Initiation phase** focuses on validating business need and stakeholder alignment through a lightweight One-pager that captures the problem statement, objectives, success metrics, and initial resource needs. Once approved, the **Planning phase** breaks work into shippable increments with clear acceptance criteria, estimated scope using T-shirt sizing or story points, and a documented Definition of Done. During **Execution**, teams work in sprints using a GitHub Projects board with columns (Backlog, Ready, In Progress, In Review, QA, Done), supported by daily standups, pull request workflows with automated CI/CD checks, and at least one peer approval before merging. The **Release phase** enforces pre-release checklists including passing security scans, smoke tests, and prepared rollback plans, followed by post-deploy verification and stakeholder announcements. Finally, **Retrospectives** capture learnings and convert them into actionable improvements tracked through the project backlog.

### Roles, Responsibilities & Communication

OctoAcme defines four primary personas: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define what to build and prioritize the backlog based on customer value; **Developers** implement features and maintain quality through testing and code reviews; and **QA/Testing teams** validate acceptance criteria and quality standards. Clear ownership is enforced with each project having a named PM and Product Lead. Communication occurs through a regular cadence: **daily standups** (15 min) focused on progress and blockers, **weekly PM syncs** between PM and Product Manager, **twice-weekly delivery standups**, **monthly stakeholder updates**, and **demo/review sessions** at sprint or milestone ends. All decisions, risks, and status updates are centralized in a single source of truth (project README or release documentation) to ensure transparency across stakeholders.

### Risk Management & Quality Assurance

OctoAcme maintains a **Risk Register** that tracks identification, assessment, mitigation, and ongoing monitoring of risks using a simple matrix of ID, Description, Impact, Likelihood, Owner, Mitigation, and Status. Risks are reviewed at weekly syncs and escalated through a three-level path: team-level triage → PM escalation to Product Lead → sponsor-level escalation for business-impacting issues. Quality is embedded throughout execution: **unit tests** for new logic, **integration tests** where applicable, **end-to-end smoke tests** for critical flows, and **security scanning in CI**. Pull requests must be small (≤400 lines when possible), include issue links and acceptance criteria, pass automated tests and linting, and require at least one approval before merging. Success is measured through **velocity and burndown tracking**, **dashboard monitoring** of key signals (errors, latency, usage), and adherence to acceptance criteria tied to the Project One-pager's success metrics.

### Continuous Improvement & Learning Culture

OctoAcme emphasizes a **psychological safety** culture where feedback and learning are encouraged. **Retrospectives** are held after each sprint, release, or milestone (typically 45–75 minutes) using anonymous idea boards to surface candor. Teams prioritize 2–3 top action items with clear owners and due dates, then track their impact in subsequent weekly syncs. **Incident retrospectives** follow a blameless approach to capture root causes and prevent recurrence. This commitment to continuous improvement is reinforced through the project documentation itself: teams add learnings and validated improvements back into living docs in `.copilot/` and `docs/` folders, ensuring that tacit knowledge becomes searchable, versioned artifacts available to all team members. This practice accelerates onboarding, reduces single-person dependency risk, and enables consistent, repeatable project execution across the organization.

## Process Documentation

### Getting Started
- [**Project Management Overview**](octoacme-project-management-overview.md) - Start here for a high-level introduction to OctoAcme's approach, roles, and key artifacts
- [**Personas & Roles**](octoacme-roles-and-personas.md) - Understand the typical roles and responsibilities in OctoAcme projects

### By Project Stage
- [**Project Initiation Guide**](octoacme-project-initiation.md) - Validate needs, align stakeholders, and gain approval to move to planning
- [**Project Planning**](octoacme-project-planning.md) - Turn an approved initiative into an actionable plan and backlog
- [**Execution & Tracking**](octoacme-execution-and-tracking.md) - Manage day-to-day delivery, track progress, and handle blockers
- [**Release & Deployment**](octoacme-release-and-deployment.md) - Standardize how we release features to production
- [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) - Capture learnings and convert them into improvements

### Cross-Cutting Guides
- [**Risk Management & Communication**](octoacme-risks-and-communication.md) - Identify, manage, and communicate risks and dependencies

## Quick Links by Role

**Product Managers**: Start with [Project Initiation](octoacme-project-initiation.md) and [Project Management Overview](octoacme-project-management-overview.md)

**Project Managers**: Review [Execution & Tracking](octoacme-execution-and-tracking.md), [Risk Management & Communication](octoacme-risks-and-communication.md), and [Project Planning](octoacme-project-planning.md)

**Developers**: Focus on [Execution & Tracking](octoacme-execution-and-tracking.md) and [Release & Deployment](octoacme-release-and-deployment.md)

**New Team Members**: Begin with [Project Management Overview](octoacme-project-management-overview.md) and [Personas & Roles](octoacme-roles-and-personas.md)
