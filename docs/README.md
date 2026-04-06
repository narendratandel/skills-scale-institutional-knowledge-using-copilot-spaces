# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation! This README provides an overview of our project management processes and convenient links to each detailed doc below.

## Summary of Project Management Processes

OctoAcme follows a structured, lifecycle-based approach to project management that prioritizes customer value, iterative delivery, and clear ownership. The organization operates through five distinct phases:

1. **Initiation** — Validating business need and stakeholder alignment
2. **Planning** — Breaking work into shippable increments with acceptance criteria
3. **Execution** — Day-to-day delivery with continuous tracking
4. **Release** — Standardized deployment to production
5. **Retrospective** — Capturing learnings for continuous improvement

Each project is anchored by a lightweight Project One-pager that defines the problem statement, success metrics, and key milestones, ensuring all stakeholders maintain alignment from inception through closure.

### Core Roles & Personas

OctoAcme defines clear roles and responsibilities across three core personas:

- **Product Managers** — Define what should be built and prioritize based on customer and business value
- **Project Managers** — Coordinate delivery, manage schedules, risks, and stakeholder communications
- **Developers** — Design, build, test, and deliver components while maintaining high code quality and test coverage

This separation of concerns—combined with defined stakeholder groups and escalation paths—ensures transparent decision-making authority and regular cross-functional alignment.

### Communication & Collaboration

Communication follows a consistent rhythm to maintain transparency and alignment:

- **Daily standups** (15 minutes) — Team-level progress and blockers
- **Weekly delivery syncs** — Show progress, updates, and flagged risks
- **Weekly PM-PdM alignment** — Prioritization and strategic alignment
- **Monthly stakeholder updates** — High-level progress and outcomes
- **Ad-hoc escalations** — Critical issues and blockers

### Quality Assurance & Risk Management

Quality assurance and risk management are embedded throughout the OctoAcme lifecycle rather than treated as downstream activities. During execution, teams employ:

- Small pull requests (≤400 lines)
- Automated CI testing and linting
- Manual QA for feature acceptance
- Security scanning before release
- Formal Risk Register tracking (ID, description, impact, likelihood, mitigation, owner)
- Weekly risk reviews at syncs and escalation meetings

The release process includes pre-release checklists (acceptance criteria met, CI passing, smoke tests prepared, rollback plans documented) and post-deployment verification to reduce production incidents. Structured retrospectives after each sprint, release, or milestone—combined with tracked action items and continuous measurement of improvements—institutionalize learning and prevent gaps or risks from recurring across future projects.

## Process Documentation

Detailed guidance for each phase and function:

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to roles, principles, artifacts, and communication cadence
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate business need, align stakeholders, and create the Project One-pager
- **[Project Planning](./octoacme-project-planning.md)** — Breaking work into shippable increments with prioritization, estimation, and dependency management
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Day-to-day delivery, team rhythm, PR workflows, quality practices, and blocker escalation
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Risk register lifecycle, stakeholder communication templates, and escalation paths
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Pre-release requirements, deployment checklists, rollback procedures, and release notes
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Running retrospectives, tracking action items, and measuring improvement impact
- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Detailed descriptions of Developer, Product Manager, and Project Manager responsibilities and communication patterns

## Getting Started

- **For new projects:** Start with [Project Initiation Guide](./octoacme-project-initiation.md) to create your Project One-pager
- **For ongoing delivery:** Refer to [Execution & Tracking](./octoacme-execution-and-tracking.md) for team rhythm and workflows
- **For releases:** Follow the [Release & Deployment Guide](./octoacme-release-and-deployment.md) to standardize your go-live process
- **For process improvements:** Use [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to capture and act on learnings

## How to Use This Documentation

- Keep the Project Charter / One-pager updated in your project repository
- Reference the relevant process doc at each phase of your project lifecycle
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context
- Suggest improvements via issues using the "Add Content to Project Management Process Docs" issue template
