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

## Additional Personas

Add these entries to clarify ownership of cross-functional activities. For each persona below, include Role Summary, Key Responsibilities, and Interactions (formatted to match existing entries).

1) Release Engineer
- Role Summary: Owns release orchestration, deployment pipelines, and rollback plans.
- Key Responsibilities: Maintain CI/CD pipelines, coordinate release windows, validate release readiness (smoke tests), prepare rollback steps, and monitor post-deploy metrics.
- Interactions: Works with PM (scheduling), Developers (deployment readiness), QA (pre/post-release validation), and Support (post-release incident handling).

2) DevOps / Platform Engineer
- Role Summary: Builds and maintains the platform, automation, infrastructure-as-code, and observability.
- Key Responsibilities: Manage infrastructure, automate provisioning, ensure monitoring/alerting, and optimize performance and cost.
- Interactions: Partners with Developers (architecture and deployment), Release Engineer (pipelines), Security (hardening), and PM for capacity/roadmap implications.

3) Security Liaison (Security Engineer)
- Role Summary: Ensures security and compliance considerations are integrated across the project lifecycle.
- Key Responsibilities: Perform threat modeling, security reviews of designs/PRs, coordinate vulnerability scanning, and communicate security risks.
- Interactions: Advises Developers and QA on mitigations, escalates to Product Lead and Security on sensitive issues, and informs PM about schedule impacts.

4) Data Analyst / Measurement Lead
- Role Summary: Defines success metrics, implements instrumentation, and analyzes outcomes.
- Key Responsibilities: Specify telemetry/events, validate data quality, run experiments/analysis, and produce dashboards/reports.
- Interactions: Works with Product Managers (success metrics), Developers (instrumentation), and Stakeholders (reporting results).

5) UX Researcher / Designer
- Role Summary: Represents user needs and validates designs with research and usability testing.
- Key Responsibilities: Conduct user research, craft interaction/specs, run usability tests, and provide design assets and accessibility guidance.
- Interactions: Collaborates with Product Managers (user goals), Developers (implement designs), and QA (acceptance criteria for UX).

6) Technical Writer / Documentation Owner
- Role Summary: Produces and maintains user-facing and runbook documentation.
- Key Responsibilities: Create release notes, runbooks, onboarding docs, API docs, and ensure documentation is versioned with releases.
- Interactions: Works with Developers (technical content), PM (audience/priority), and Support (knowledge transfer).

7) Support / Operations Lead (Customer Ops)
- Role Summary: First-line contact for customer issues and operational feedback.
- Key Responsibilities: Triage incidents, provide reproduction details, track customer-impacting bugs, and feed insights back into backlog.
- Interactions: Communicates with Developers (bug triage), PM (prioritization), and Release/Platform teams for incident resolution.

8) Business Analyst / Product Operations
- Role Summary: Bridges business stakeholders and delivery team for requirements and acceptance criteria.
- Key Responsibilities: Refine requirements, map business processes, validate acceptance criteria, and assist in release readiness.
- Interactions: Works with Product Manager (prioritization), PM (scheduling), and Stakeholders (requirements alignment).

9) Accessibility Lead (when applicable)
- Role Summary: Ensures accessibility requirements and testing are included in definition of done.
- Key Responsibilities: Define accessibility acceptance criteria, run audits, and advise on remediation.
- Interactions: Partners with Developers, QA, and UX to ensure accessible designs and implementations.

Suggested placement and formatting
- Add a section titled "Additional Personas" after the existing persona entries.
- Follow existing persona structure: Role Summary, Responsibilities, Goals (optional), Typical Communication.
- Keep each entry concise and link to relevant runbooks or owners where available.
