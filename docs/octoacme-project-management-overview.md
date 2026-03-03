# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles

### Role Tier 1 — Always Required
- **Project Manager (PM):** coordinates delivery, schedules, risk, and communications.
- **Product Manager (PdM):** defines outcomes, prioritizes backlog, and measures success.
- **Developers:** implement features, collaborate on design, and ensure testability.

### Role Tier 2 — Usually Required
- **QA Lead:** owns test strategy, coordinates testing efforts, and ensures quality gates are met.
- **Technical Lead:** owns technical direction, ensures code quality, and mentors the development team.
- **Scrum Master:** facilitates agile ceremonies, removes blockers, and fosters team communication.

### Role Tier 3 — As Needed
- **UX Designer:** ensures a user-centric design approach throughout feature planning and delivery.
- **Business Analyst:** bridges business objectives and technical delivery by translating requirements.

> **Stakeholders** (not listed above) provide inputs and approvals across all tiers.

See [Personas](octoacme-roles-and-personas.md) for detailed role definitions and responsibilities.

## Key Artifacts
- Project Charter / One-pager (PM, PdM owned)
- Roadmap and Release Plan (PdM owned)
- Sprint/Iteration Backlog (PM, Scrum Master owned)
- Acceptance Criteria & Definition of Done (PdM, Business Analyst owned)
- Design System / Wireframes (UX Designer owned)
- Test Plan (QA Lead owned)
- Architecture Decision Records (Technical Lead owned)
- Risk Register (PM owned)
- Retrospective notes and action items (Scrum Master owned)

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
