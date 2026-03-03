# OctoAcme — Role Interaction Matrix

## Purpose
This document maps how the eight OctoAcme roles collaborate with one another. Use it to understand who is a primary partner for a given role, who plays a supporting or advisory part, and which handoffs are most critical to smooth delivery.

---

## Interaction Matrix

The table below shows the nature of each role-to-role relationship. Read across a row to see how that role interacts with each column role.

| Role | PM | PdM | Developer | QA Lead | Technical Lead | UX Designer | Scrum Master | Business Analyst |
|---|---|---|---|---|---|---|---|---|
| **Project Manager (PM)** | — | Primary | Primary | Supporting | Supporting | Supporting | Primary | Supporting |
| **Product Manager (PdM)** | Primary | — | Supporting | Supporting | Advises | Primary | Supporting | Primary |
| **Developer** | Supporting | Supporting | — | Primary | Primary | Supporting | Supporting | Supporting |
| **QA Lead** | Supporting | Reviews | Primary | — | Primary | Supporting | Supporting | Supporting |
| **Technical Lead** | Supporting | Advises | Primary | Primary | — | Supporting | Supporting | Advises |
| **UX Designer** | Supporting | Primary | Supporting | Supporting | Supporting | — | Supporting | Supporting |
| **Scrum Master** | Primary | Supporting | Supporting | Supporting | Supporting | Supporting | — | Supporting |
| **Business Analyst** | Supporting | Primary | Supporting | Supporting | Advises | Supporting | Supporting | — |

**Interaction types:**
- **Primary** – frequent, direct collaboration; key dependency
- **Supporting** – regular touchpoints; provides input or assistance
- **Advises** – consulted for expertise; less frequent but high-value
- **Reviews** – provides feedback at defined checkpoints

---

## Key Handoff Points

Critical transitions where clear communication and shared artifacts prevent gaps:

1. **Requirements → Design**
   - Business Analyst hands off documented requirements and acceptance criteria to Product Manager and UX Designer.
   - UX Designer reviews requirements for user impact before designing.

2. **Design → Development**
   - UX Designer delivers finalized wireframes, design specs, and component guidance to Developers.
   - Product Manager confirms acceptance criteria are reflected in the design before development begins.

3. **Development → QA**
   - Developers hand off completed features via pull requests with linked acceptance criteria.
   - QA Lead confirms test cases are ready and the feature meets the Definition of Done before QA begins.

4. **QA → Release**
   - QA Lead signs off on test results and acceptance criteria validation.
   - Project Manager coordinates release activities and stakeholder communication.

---

## Collaboration Examples

### Example 1: New Feature from Concept to Delivery
1. **Business Analyst** gathers stakeholder requirements and produces user stories with acceptance criteria.
2. **Product Manager** prioritizes the feature and aligns with **UX Designer** on user research needs.
3. **UX Designer** creates wireframes and iterates with **Developers** on feasibility.
4. **Technical Lead** reviews the approach, flags architectural considerations, and aligns with the **QA Lead** on the testing strategy.
5. **Scrum Master** facilitates sprint planning to pull the work in and monitors blockers.
6. **Developers** implement the feature; **QA Lead** validates acceptance criteria before the **Project Manager** schedules release.

### Example 2: Critical Bug in Production
1. **QA Lead** triages the defect, assesses severity, and notifies the **Project Manager**.
2. **Project Manager** escalates to **Technical Lead** and **Product Manager** for impact assessment.
3. **Technical Lead** assigns a **Developer** and reviews the fix for quality and safety.
4. **QA Lead** re-validates the fix and confirms the defect is resolved.
5. **Project Manager** coordinates the release and communicates to stakeholders.

### Example 3: Sprint Retrospective into Process Improvement
1. **Scrum Master** facilitates the retrospective and captures action items.
2. Action items are assigned to owners — e.g., **QA Lead** owns improving test automation coverage; **Technical Lead** owns updating code review guidelines.
3. **Project Manager** tracks action items in the project board and follows up in the next retrospective.

### Example 4: Requirements Clarification Mid-Sprint
1. **Developer** encounters ambiguous acceptance criteria during implementation.
2. **Developer** raises the question in the daily standup; **Scrum Master** surfaces it to the right people.
3. **Business Analyst** and **Product Manager** clarify requirements and update the user story.
4. **QA Lead** updates test cases accordingly before the feature reaches QA.

---

## Communication Patterns

| Role Pair | Sync Cadence | Primary Communication Channel |
|---|---|---|
| PM ↔ PdM | Weekly | Weekly sync meeting, shared project board |
| PM ↔ Scrum Master | Daily | Standup, async updates |
| PdM ↔ UX Designer | Weekly or per-sprint | Design reviews, shared design tool |
| PdM ↔ Business Analyst | As needed (requirements phases) | Requirements workshops, user story reviews |
| Technical Lead ↔ Developer | Daily | Code reviews, architecture discussions |
| Technical Lead ↔ QA Lead | Weekly or per-sprint | Testing strategy sessions |
| QA Lead ↔ Developer | Daily (during QA) | Defect triage, PR reviews |
| Scrum Master ↔ Team | Daily | Standup, retrospectives, sprint ceremonies |
| Business Analyst ↔ Stakeholders | As needed | Requirements workshops, review sign-offs |
