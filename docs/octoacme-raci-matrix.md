# OctoAcme — RACI Matrix

## Purpose
Map key project activities to roles so that every team member knows whether they are **Responsible**, **Accountable**, **Consulted**, or **Informed** for each activity.

## RACI Key
| Code | Meaning |
|------|---------|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome; final decision-maker |
| **C** | **Consulted** — provides input before action |
| **I** | **Informed** — kept in the loop after action |

> Each activity should have exactly **one A** (Accountable). Multiple Rs and Cs are fine.

---

## RACI Table

| Activity | Project Sponsor | Project Manager (PM) | Product Manager (PdM) | Business Analyst (BA) | Developers | QA Lead | Change Manager | Release Coordinator |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **INITIATION** | | | | | | | | |
| Approve project charter | **A** | R | C | C | I | I | I | I |
| Define problem statement & success metrics | C | C | **A** | R | C | I | C | I |
| Identify stakeholders & communication plan | C | R | C | C | I | I | **A** | I |
| Confirm team roles & resource plan | **A** | R | C | I | I | I | I | I |
| Initial risk identification | C | **A** | C | R | C | I | C | I |
| **PLANNING** | | | | | | | | |
| Facilitate project kickoff | I | **A** | C | R | C | I | C | I |
| Elicit & document requirements | I | C | C | **A** | C | C | C | I |
| Prioritize backlog | C | C | **A** | R | C | I | I | I |
| Define Definition of Done | I | C | C | C | **A** | R | I | I |
| Create test strategy & test plan | I | I | C | C | C | **A** | I | I |
| Create release plan & milestones | I | **A** | C | I | I | C | C | R |
| Change management plan | C | C | C | C | I | I | **A** | C |
| **EXECUTION** | | | | | | | | |
| Sprint / iteration planning | I | **A** | C | C | R | C | I | I |
| Implement features | I | I | C | C | **A** | C | I | I |
| Code review | I | I | I | I | **A** | C | I | I |
| Track risks & update risk register | C | **A** | C | R | I | C | I | I |
| Defect triage & resolution | I | C | I | C | R | **A** | I | I |
| Weekly status reporting | I | **A** | C | I | I | C | C | C |
| Escalate blockers (business-impacting) | **A** | R | C | I | I | I | C | I |
| **QUALITY & RELEASE** | | | | | | | | |
| Acceptance testing (UAT) | I | I | C | R | C | **A** | I | I |
| QA sign-off | I | C | C | C | C | **A** | I | R |
| Release readiness review | C | C | C | I | C | R | C | **A** |
| Deployment execution | I | I | I | I | R | C | I | **A** |
| Post-deploy verification | I | C | I | I | R | **A** | I | R |
| Release announcement | C | C | C | I | I | I | R | **A** |
| **CLOSE & RETROSPECTIVE** | | | | | | | | |
| Facilitate retrospective | I | **A** | C | I | R | R | C | C |
| Document lessons learned | I | **A** | C | R | C | C | C | C |
| Stakeholder adoption review | C | C | C | C | I | I | **A** | I |
| Project close sign-off | **A** | R | C | I | I | I | C | I |

---

## Role Interaction & Hand-off Checklist

Use this checklist at each phase transition to confirm hand-offs are complete.

### Initiation → Planning
- [ ] Project Sponsor has approved the project charter
- [ ] Project Manager has confirmed team composition and resource availability
- [ ] Business Analyst has begun stakeholder interviews and requirements elicitation
- [ ] Change Manager has been briefed and is drafting stakeholder impact assessment

### Planning → Execution
- [ ] Business Analyst has delivered prioritized, acceptance-criteria-ready user stories to the backlog
- [ ] QA Lead has reviewed acceptance criteria and drafted the test strategy
- [ ] Release Coordinator has been included in release planning and agreed on the deployment window
- [ ] Change Manager has reviewed the communication plan with Product Manager

### Execution → Quality & Release
- [ ] Developers confirm all acceptance criteria are implemented and PRs merged
- [ ] QA Lead has completed test execution and documented results
- [ ] Release Coordinator confirms go-live checklist is complete (see [`octoacme-release-and-deployment.md`](octoacme-release-and-deployment.md))
- [ ] Change Manager confirms stakeholder communications and training are ready for go-live

### Quality & Release → Close & Retrospective
- [ ] Release Coordinator has sent the post-release announcement
- [ ] QA Lead has published the post-release quality summary
- [ ] Change Manager has tracked adoption metrics and flagged any adoption issues
- [ ] Project Manager has scheduled the retrospective and notified all participants
- [ ] Project Sponsor has received the close summary and provided sign-off

---

## Notes
- This matrix is a starting point. Adapt it to the size and complexity of each project.
- For smaller projects, some roles may be combined (e.g., PM and Release Coordinator handled by the same person).
- Keep this table in sync with [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md) when roles change.
