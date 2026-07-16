# OctoAcme Project Management Documentation

Welcome to the central hub for OctoAcme's project management processes and guidance.

## What is OctoAcme?

OctoAcme is a structured approach to cross-functional project delivery that prioritizes customer value, iterative delivery, clear ownership, and data-informed decisions. Our processes are designed to be lightweight while maintaining alignment across teams and enabling consistent, repeatable project execution.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Overview of OctoAcme Project Management Processes

OctoAcme follows a **structured lifecycle approach** to project management that spans five key phases: Initiation, Planning, Execution, Release, and Close & Retrospective. The organization prioritizes customer value, iterative delivery, and clear ownership by assigning a named Project Manager and Product Lead to each project.

### Key Workflows and Practices

**Initiation & Planning** begins with validating business needs and creating a lightweight Project One-pager that defines the problem statement, success metrics, and stakeholder alignment. Once approved, the planning phase breaks work into shippable increments with prioritized backlogs, estimated scope, and clearly documented acceptance criteria and Definition of Done (DoD). This foundation ensures the team executes with confidence, knowing what "success" looks like upfront.

**Execution relies on a predictable team rhythm and transparent workflow management.** Teams conduct daily standups (15 minutes) focused on progress and blockers, weekly delivery syncs to showcase progress and surface risks, and sprint reviews or demos at milestone endpoints. Work flows through a project board with standardized columns—Backlog, Ready, In Progress, In Review, QA, and Done—with pull requests kept small (≤400 lines when possible). Quality is baked in through unit and integration tests, automated CI checks for linting and security scanning, and manual QA for feature acceptance when needed.

**Communication and continuous improvement** are embedded throughout the lifecycle. Weekly syncs between PM and Product Manager, twice-weekly standups for delivery teams, and monthly stakeholder updates ensure alignment. A simple Risk Register tracks risks by ID, description, impact, likelihood, owner, and mitigation status, with regular reviews during weekly syncs. After each sprint or milestone, teams conduct retrospectives to capture learnings and convert them into actionable improvements. Finally, releases are managed through a standardized checklist covering pre-release requirements, deployment verification, and rollback procedures to reduce risk and maintain observability.

## Project Lifecycle

Our projects follow five phases:

1. **Initiation** - Problem statement, stakeholders, high-level timeline
2. **Planning** - Scope, resources, milestones, dependencies
3. **Execution** - Build, test, review, iterate
4. **Release** - Deploy, verify, announce
5. **Close & Retrospective** - Capture learnings and next steps

## Documentation by Phase

### Initiation Phase
- [Project Initiation Guide](./octoacme-project-initiation.md) - Steps to validate and authorize work, align stakeholders, and create a lightweight plan

### Planning Phase
- [Project Planning](./octoacme-project-planning.md) - Turn an approved initiative into an actionable plan and backlog

### Execution Phase
- [Execution & Tracking](./octoacme-execution-and-tracking.md) - Manage day-to-day execution and track progress
- [Risks & Communication](./octoacme-risks-and-communication.md) - Identify, manage, and communicate risks and dependencies

### Release Phase
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) - Standardize how to release features to production

### Close Phase
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) - Capture learnings and convert them into actionable improvements

## Essential References

- [Project Management Overview](./octoacme-project-management-overview.md) - Concise introduction to our approach, roles, and key artifacts (start here for new team members)
- [Roles and Personas](./octoacme-roles-and-personas.md) - Definitions of typical roles, responsibilities, and communication patterns

## Quick Reference by Role

### Project Manager
Start with [Project Management Overview](./octoacme-project-management-overview.md), then reference:
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Risks & Communication](./octoacme-risks-and-communication.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)

### Product Manager
Focus on defining outcomes and success metrics:
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)

### Developer
Reference execution workflows and quality standards:
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)

### Stakeholder
Check for context and status updates:
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Risks & Communication](./octoacme-risks-and-communication.md)

## How to Use These Docs

- Keep the Project Charter updated in the project repo
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context
- Link to relevant sections when creating issues or discussing project decisions
- Use these guides as a basis for team-specific adaptations and templates
