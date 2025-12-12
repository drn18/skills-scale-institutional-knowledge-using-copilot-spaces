# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management documentation hub! This guide serves as your entry point to understanding how we plan, execute, and deliver projects at OctoAcme.

## Overview

OctoAcme employs a structured project management framework emphasizing iterative delivery, stakeholder alignment, and continuous improvement, as outlined in its comprehensive documentation.

### Project Lifecycle

**Initiation:** The process begins with project initiation, where a Project One-pager validates business needs, defines SMART goals, success metrics, and initial risks, ensuring stakeholder buy-in before proceeding to planning.

**Planning:** Planning involves breaking work into prioritized backlogs with acceptance criteria, T-shirt sizing estimates, and a Definition of Done, followed by sprint planning to align on timelines and dependencies.

**Execution:** Execution leverages daily standups, weekly delivery syncs, and a GitHub Projects board with columns for Backlog to Done, incorporating pull request workflows with automated CI testing, linting, and security scans.

### Key Roles

Key personas include:
- **Project Managers (PMs)** who coordinate delivery and risks
- **Product Managers (PdMs)** who prioritize outcomes and measure success
- **Developers** who implement and test features
- **QA roles** focused on validation

All roles foster clear ownership and psychological safety.

### Communication & Risk Management

Communication strategies are integral, with weekly PM-PdM syncs, twice-weekly standups, and monthly stakeholder updates using templates for status reports and incident triage to maintain transparency. Escalation paths start at the team level for blockers and rise to sponsors for business-impacting issues, supported by a single source of truth like project READMEs. 

Risk management uses a register reviewed weekly, identifying impacts, probabilities, and mitigations, while retrospectives after sprints or milestones prioritize 2-3 action items for iterative enhancements.

### Quality Assurance & Releases

Quality assurance practices integrate throughout, requiring unit, integration, and end-to-end tests, manual QA for features, and CI-driven security scanning, with metrics tracking velocity, burndown, and success indicators. 

Releases are categorized as patches, minors, or majors, with checklists for pre-release requirements, smoke tests, rollback plans, and post-deploy verifications to minimize risks. Deployment involves staging verification and automated pipelines where possible, followed by announcements, ensuring repeatable, observable rollouts that align with customer-first principles and data-informed decisions. 

This holistic approach reduces single-person dependencies, accelerates onboarding, and standardizes workflows for consistent project execution.

## Docs Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

## Contributing

Have suggestions for improving our process documentation? We welcome your feedback! Please use our [process doc update template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to submit your ideas and help us continuously improve our project management practices.
