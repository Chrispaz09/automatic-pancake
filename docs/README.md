# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management documentation. This folder contains the process guides, templates, and reference materials that define how OctoAcme plans, executes, and delivers projects.

---

## Overview

OctoAcme follows a structured, lifecycle-based approach to project management grounded in customer value, iterative delivery, and clear accountability. The framework spans five key phases: **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with defined acceptance criteria), **Execution** (daily delivery with standups and progress tracking), **Release** (controlled deployment with quality gates), and **Close & Retrospective** (capturing learnings for continuous improvement). This approach emphasizes psychological safety, data-informed decisions, and small, testable increments delivered regularly to customers.

The organization defines three core delivery roles—**Project Manager** (coordinates schedules, risks, and communications), **Product Manager** (defines outcomes, prioritizes the backlog, and measures success), and **Developers** (implement features, collaborate on design, and maintain quality)—with clear ownership and accountability for each project. Project artifacts anchor the work: a lightweight Project One-pager establishes the problem and success metrics early; a prioritized, estimated backlog with acceptance criteria guides daily work; and a Risk Register tracks dependencies and mitigation strategies. Communication happens through a consistent cadence: weekly PM-to-PdM syncs, twice-weekly delivery standups, monthly stakeholder updates, and ad-hoc escalations via a three-level structure (team → PM → Product Lead → Sponsor).

Quality and testing are embedded throughout the execution phase, with unit tests for new logic, integration and end-to-end smoke tests for critical flows, security scanning in CI, and manual QA when needed. Pull request workflows enforce small PRs (≤400 lines when possible), automated test and lint gates, and at least one approval before merging. Teams use a project board with standard columns (Backlog, Ready, In Progress, In Review, QA, Done) to visualize workflow and maintain transparency. Releases follow a standardized checklist including passing CI, security scans, release notes, and a rollback plan; deployment windows and post-deployment verification ensure production stability.

Finally, OctoAcme institutionalizes learning through regular retrospectives after each sprint, release, or milestone. These sessions follow a structured format—*what went well*, *what could improve*, and *action items with owners and due dates*—and are timeboxed to 45–75 minutes to maintain focus. Action items are tracked in the project backlog with clear success criteria, creating a feedback loop that drives incremental process improvements. This combination of disciplined execution, transparent communication, and continuous improvement ensures consistency across projects while maintaining the flexibility to adapt based on team and customer feedback.

---

## Process Documents

| Document | Description |
|----------|-------------|
| [Project Management Overview](./octoacme-project-management-overview.md) | High-level introduction to OctoAcme's project management principles, roles, key artifacts, and lifecycle. |
| [Project Initiation Guide](./octoacme-project-initiation.md) | Steps to validate and authorize new work, align stakeholders, and produce the Project One-pager. |
| [Project Planning](./octoacme-project-planning.md) | How to turn an approved initiative into an actionable backlog, release plan, and milestone map. |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day delivery guidance covering standups, PR workflows, quality practices, and blocker escalation. |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | How to identify, assess, and mitigate risks, and how to communicate status to stakeholders. |
| [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Standardized release checklist, deployment steps, rollback playbook, and release notes template. |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Running structured retrospectives and converting learnings into tracked action items. |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Detailed responsibilities and communication patterns for Project Managers, Product Managers, and Developers. |

---

## How to Use This Documentation

1. **Starting a new project?** Begin with the [Project Management Overview](./octoacme-project-management-overview.md) to understand the overall framework, then follow the [Project Initiation Guide](./octoacme-project-initiation.md).
2. **Looking for a specific phase?** Jump directly to the relevant process document using the table above.
3. **Using Copilot Spaces?** Copy the process documents you need into your repository's `.copilot/` folder so Copilot can use them as context when answering project-related questions.
4. **Onboarding a new team member?** Share this README as the starting point; it links to everything they need.

---

## Contributing to the Documentation

We welcome improvements to keep these docs accurate and useful.

- **Small fixes** (typos, broken links, clarifications): open a pull request directly with your change.
- **New content or structural changes**: open an issue first to discuss the proposal before writing.
- **Style guidelines**:
  - Use clear, plain language aimed at a mixed technical and non-technical audience.
  - Follow the existing heading hierarchy (`#`, `##`, `###`) in each document.
  - Keep sections concise; link to external references rather than duplicating them.
  - Include a checklist or template wherever a repeatable process is described.
- All pull requests require at least one reviewer approval before merging.
