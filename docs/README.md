# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management documentation hub. This README serves as the central entry point for understanding how OctoAcme runs projects, onboarding new team members, and navigating our process documentation.

## Project Management Process Overview

OctoAcme follows a customer-first, iterative approach to project management that emphasizes delivering value in small, testable increments. Our process is built on five core principles:

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Named Project Managers and Product Leads for each initiative
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and continuous learning

Our project lifecycle consists of five key phases that guide work from concept to completion:

- **Initiation**: Validate the business need, align stakeholders, and create a lightweight project one-pager that defines the problem, objectives, and success metrics
- **Planning**: Transform approved initiatives into actionable plans by breaking work into shippable increments, identifying dependencies and risks, and creating release timelines
- **Execution**: Follow a consistent rhythm of daily standups, weekly syncs, and regular demos while tracking progress through project boards and maintaining quality through comprehensive testing
- **Release**: Follow standardized deployment procedures with pre-release checklists, smoke tests, and rollback plans to minimize risk
- **Retrospective**: Capture learnings after each sprint or milestone and convert them into actionable improvements

Communication and collaboration are central to how we work. Teams maintain a regular cadence with weekly syncs between Project and Product Managers, twice-weekly standups for delivery teams, and monthly stakeholder updates. We use GitHub Projects for tracking work through clearly defined columns (Backlog, Ready, In Progress, In Review, QA, Done), and we maintain key artifacts including project charters, roadmaps, sprint backlogs, risk registers, and retrospective notes to ensure transparency and alignment.

Quality is built into every stage through comprehensive practices including unit, integration, and end-to-end testing, security scanning in CI/CD pipelines, code reviews requiring at least one approval, and documented Definition of Done criteria. We manage risks proactively by maintaining risk registers, conducting weekly reviews, and following clear escalation paths from team-level to PM to Product Lead to Sponsor level when needed.

## Team Structure & Roles

OctoAcme projects involve three primary personas working together to deliver customer value:

### Product Managers
Product Managers own the **"what"** — defining what should be built to deliver customer and business value. They own the product vision, prioritize the backlog based on customer needs and business impact, collaborate with stakeholders on trade-offs, and validate solutions through user research and metrics. Their goal is to maximize customer value through clear, data-driven prioritization decisions and ensure product-market fit.

### Project Managers
Project Managers coordinate the **"how"** — managing delivery activities, schedules, risks, and communications. They create and maintain project plans and timelines, manage risks and dependencies, facilitate meetings (kickoffs, planning sessions, retrospectives), ensure consistent documentation and status reporting, and coordinate cross-team communication. Their goal is to deliver projects on time and within scope while maintaining transparency and alignment across all stakeholders.

### Developers
Developers execute the **"build"** — designing, building, testing, and delivering software components. They implement features that meet acceptance criteria, write and maintain tests and documentation, participate in design and code reviews, assist in estimating and planning work, and help identify technical risks. Their goal is to deliver reliable, maintainable code while reducing cycle time from idea to production.

## Documentation Index

Our process documentation is organized to guide you through the complete project lifecycle:

### Core Process Documents

- **[Project Management Overview](octoacme-project-management-overview.md)** - A concise introduction to how OctoAcme runs projects, including our principles, core roles, key artifacts, lifecycle phases, and communication cadence. Start here for a high-level understanding.

- **[Roles and Personas](octoacme-roles-and-personas.md)** - Detailed definitions of the three key roles (Developers, Product Managers, Project Managers) including responsibilities, goals, and typical communication patterns.

### Project Lifecycle Guides

- **[Project Initiation Guide](octoacme-project-initiation.md)** - How to validate and authorize new work, including creating project one-pagers, aligning stakeholders, defining success criteria, and deciding whether to proceed to planning.

- **[Project Planning](octoacme-project-planning.md)** - Turning approved initiatives into actionable plans by creating prioritized backlogs, estimating scope, defining Definition of Done, identifying dependencies, and creating release plans.

- **[Execution & Tracking](octoacme-execution-and-tracking.md)** - Day-to-day execution guidance including team rhythm, workflows, pull request conventions, quality and testing practices, reporting metrics, and blocker escalation procedures.

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** - How to identify, assess, mitigate, and monitor risks using our risk register. Includes stakeholder communication templates and escalation paths.

- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** - Standardized release procedures covering release types (patch/minor/major), pre-release requirements, deployment checklists, rollback procedures, and release notes templates.

- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** - How to capture learnings and convert them into actionable improvements through structured retrospectives after sprints, releases, or incidents.

## How to Use This Documentation

- **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our approach, then explore [Roles and Personas](octoacme-roles-and-personas.md) to understand your role.

- **Starting a new project?** Follow the lifecycle guides in order: [Initiation](octoacme-project-initiation.md) → [Planning](octoacme-project-planning.md) → [Execution](octoacme-execution-and-tracking.md) → [Release](octoacme-release-and-deployment.md) → [Retrospective](octoacme-retrospective-and-continuous-improvement.md).

- **Need specific guidance?** Jump directly to the relevant guide, such as [Risk Management](octoacme-risks-and-communication.md) for handling project risks or [Release Guide](octoacme-release-and-deployment.md) for deployment procedures.

- **Using Copilot Spaces?** Keep the Project Charter and relevant process docs in `.copilot/` directory to provide context to Copilot Spaces for your specific project.

## Contributing to These Docs

These process documents are living artifacts that should evolve with our practices. If you identify gaps, outdated information, or opportunities for improvement:

1. Create an issue describing the documentation need
2. Propose changes through a pull request
3. Ensure changes are reviewed by both a PM and Product Manager
4. Update this README if you add new documents to maintain the index

## Questions?

If you have questions about OctoAcme's project management processes that aren't answered in these docs, reach out to your Project Manager or Product Manager for guidance.
