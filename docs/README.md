# OctoAcme Project Management Documentation

## Welcome to OctoAcme

This repository contains the processes, templates, and guidance used to plan, execute, and deliver successful projects at OctoAcme. Our approach is built on five core principles:

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments that enable early feedback
- **Clear ownership**: Each project has named Project Manager and Product Lead roles
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

## OctoAcme Project Management Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The organization operates across five distinct phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. Each phase is supported by lightweight but comprehensive documentation and defined decision gates.

Projects begin with a **One-pager** that validates business need and stakeholder alignment, move into detailed **planning** with prioritized backlogs and risk registers, proceed through **incremental delivery** with daily standups and weekly syncs, and conclude with disciplined **releases** backed by smoke tests and rollback plans. This structured progression ensures that projects are well-scoped before development begins and that learnings are captured systematically after completion.

Responsibility is distributed across three core roles—**Project Managers** (who coordinate schedules, risks, and communications), **Product Managers** (who define outcomes, prioritize work, and measure success), and **Developers** (who implement features, write tests, and collaborate on design)—supported by QA/Testing and stakeholder input. Communication happens through a regular cadence: daily standups focused on progress and blockers, weekly PM-PdM syncs, twice-weekly team standups, and monthly stakeholder updates. Risks and dependencies are managed through a centralized Risk Register, with escalation paths flowing from team-level triage through PM, Product Lead, and ultimately to Sponsor for business-critical issues.

Quality and reliability are woven into every stage of delivery. OctoAcme requires unit and integration tests for new logic, end-to-end smoke tests before release, and security scanning in CI before PRs are approved. Pull requests are kept small (≤400 lines when possible) and require at least one approval before merging. Releases are governed by pre-deployment checklists that verify acceptance criteria, passing tests, and prepared rollback plans. Retrospectives held after sprints and releases capture what went well and what can improve, converting insights into prioritized action items that feed back into the project backlog—reinforcing a culture of continuous, evidence-informed improvement.

## Quick Start

New to OctoAcme? Start here:

1. **[Project Management Overview](octoacme-project-management-overview.md)** — Understand our principles, core roles, and project lifecycle
2. **[Roles and Personas](octoacme-roles-and-personas.md)** — Identify your role and responsibilities
3. **Navigate to the relevant phase document** — Find guidance for your current project stage

## Process Documentation

### Project Lifecycle

Follow these documents as your project progresses through each phase:

1. **[Project Initiation](octoacme-project-initiation.md)**
   - Validate business need and measurable outcomes
   - Identify stakeholders and champions
   - Define success criteria and initial timeline
   - Decision gate: Approve to move into planning

2. **[Project Planning](octoacme-project-planning.md)**
   - Break work into shippable increments
   - Create prioritized backlog with acceptance criteria
   - Identify dependencies and risks
   - Define Definition of Done and release plan

3. **[Execution & Tracking](octoacme-execution-and-tracking.md)**
   - Manage day-to-day execution and progress tracking
   - Use project board with standard columns (Backlog, Ready, In Progress, In Review, QA, Done)
   - Conduct daily standups and weekly delivery syncs
   - Track velocity, burndown, and success metrics

4. **[Release & Deployment](octoacme-release-and-deployment.md)**
   - Standardize how we release features to production
   - Pre-release requirements and deployment checklist
   - Rollback and incident playbook
   - Release notes and post-deploy verification

5. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)**
   - Capture learnings after sprints, releases, or milestones
   - Convert insights into actionable improvements
   - Track action items with clear owners and due dates

### Cross-Cutting Guidance

Refer to these documents throughout the project lifecycle:

- **[Risk Management & Communication](octoacme-risks-and-communication.md)**
  - Maintain and monitor risk registers
  - Manage stakeholder communication and escalation paths
  - Communication templates for status updates and incidents

- **[Roles and Personas](octoacme-roles-and-personas.md)**
  - Project Manager responsibilities and communication patterns
  - Product Manager responsibilities and communication patterns
  - Developer responsibilities and communication patterns

## Using These Docs with Copilot Spaces

To use these process documents as context for Copilot Spaces interactions:

1. Add the relevant docs to a `.copilot/` folder in your project repository
2. Reference them in your project's Copilot Space configuration
3. Copilot will use these docs to provide context-specific guidance aligned with OctoAcme processes

This enables Copilot to give you role-specific advice, template suggestions, and process reminders tailored to your project's phase and your team's context.

## Key Artifacts Reference

Throughout your project, you'll create and maintain these key artifacts:

- **Project Charter / One-pager** — Problem, goal, success metrics, stakeholders, timeline, risks
- **Roadmap and Release Plan** — Milestones, dependencies, delivery schedule
- **Sprint/Iteration Backlog** — Prioritized items with acceptance criteria and estimates
- **Risk Register** — ID, description, impact, likelihood, owner, mitigation plan, status
- **Definition of Done** — Acceptance criteria for what "done" means for your project
- **Retrospective Notes and Action Items** — Learnings, improvements, and owners

## Communication Cadence

Stay aligned with this communication rhythm:

- **Daily**: Team standups (15 min) — progress, blockers, dependencies
- **Twice-weekly**: Delivery team standups (or as agreed)
- **Weekly**: PM-PdM sync and delivery team sync
- **Monthly**: Stakeholder updates
- **As needed**: Ad-hoc escalations and incident communication

## Contributing

To request updates or add new content to these process documents:

1. Use the [**"Add Content to Project Management Process Docs"**](https://github.com/SriniDixit/skills-scale-institutional-knowledge-using-copilot-spaces/issues/new?template=add-update-content-to-process-docs.yml) issue template
2. Describe what you want to add and why it's needed
3. The team will review and merge improvements back into the docs

## Purpose of This Documentation

These process documents serve a critical role in OctoAcme's knowledge management:

- **Centralize** scattered project management knowledge in one location
- **Convert** tacit team insights into searchable, versioned artifacts
- **Give** all team members equal access to processes, decisions, and rationale
- **Accelerate** onboarding and reduce single-person dependency risk
- **Enable** consistent, repeatable project execution across teams
- **Feed** validated improvements back into living documentation

By keeping these docs up-to-date and leveraging them in your projects, you help build organizational muscle memory and ensure that best practices are accessible to everyone.

---

**Last Updated:** 2026
**Maintained by:** OctoAcme Project Management Team
