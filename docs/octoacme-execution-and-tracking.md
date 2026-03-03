# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Role Responsibilities in Execution

| Role | Execution Responsibility |
|---|---|
| **Scrum Master** | Facilitates daily standups; removes blockers surfaced by the team; tracks action items from retrospectives; shields team from interruptions |
| **QA Lead** | Manages the QA column on the project board; leads defect triage and severity assessment; coordinates manual and automated testing; validates acceptance criteria before items move to Done |
| **Technical Lead** | Participates in code reviews; provides architectural guidance during implementation; escalates technical risks; owns code review quality standards |
| **Developers** | Update ticket status daily; raise blockers in standup; collaborate with QA Lead on defect investigation; follow agreed branching and PR conventions |

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
  - **QA column**: Managed by the QA Lead, who coordinates testing, tracks defects, and validates acceptance criteria before items are marked Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup — Scrum Master facilitates; Developers and QA Lead surface blockers
- Level 2: PM escalates to Product Lead and dependent teams — Technical Lead assesses technical blockers; QA Lead assesses quality-related blockers
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
