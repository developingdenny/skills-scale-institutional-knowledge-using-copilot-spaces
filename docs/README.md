# OctoAcme Project Management Docs

Welcome to the documentation hub for OctoAcme's project management processes. This README serves as the central navigation point for all process documentation, giving you a quick overview of how OctoAcme runs projects and helping you find the right document for your needs.

## Project Management Processes Overview

OctoAcme follows an iterative, customer-first delivery methodology structured around a clear project lifecycle: **Initiation → Planning → Execution → Release → Close & Retrospective**. Each phase has defined artifacts and owners. During Initiation, a project charter and problem statement are established along with stakeholder alignment. Planning translates that vision into scope, milestones, and a prioritized backlog. Execution drives the build-test-review cycle in short iterations, tracked on a shared project board with pull requests as the primary delivery mechanism. Release standardizes how features reach production—gated by CI checks, security scans, and smoke tests—and Close & Retrospective captures learnings to feed continuous improvement.

Roles and personas are clearly defined to avoid ambiguity and foster accountability. The **Project Manager (PM)** coordinates schedules, risks, and communications. The **Product Manager (PdM)** owns the product vision, prioritizes the backlog, and measures outcomes. **Developers** implement and test features, participate in design and code reviews, and flag technical risks. **QA/Testing** validates acceptance criteria and release readiness. **Stakeholders** provide inputs, approvals, and receive regular status updates to stay aligned.

Communication is intentional and structured. OctoAcme uses a regular cadence of twice-weekly delivery standups, weekly PM–PdM syncs, and monthly stakeholder updates, with ad-hoc escalations routed through a clear path: Team → PM → Product Lead → Sponsor. A single source of truth (the project README or release doc) is maintained for project status, supported by a weekly status template covering progress, next steps, risks, and decisions needed. Incident communication follows a dedicated template that includes triage summaries and timelines.

Quality assurance is baked into every phase. Developers write and maintain tests alongside their code, and every change flows through CI pipelines that enforce automated testing and security scanning before merge. Code reviews and PR descriptions provide traceability and knowledge sharing. Pre-release gates require all acceptance criteria to be met, passing CI and security checks, and a documented rollback plan. After each release, the team holds a blameless retrospective to surface improvement actions and refine the process.

---

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, roles, key artifacts, and the high-level lifecycle |
| [Project Initiation](octoacme-project-initiation.md) | How to kick off a project: charters, stakeholders, and problem statements |
| [Project Planning](octoacme-project-planning.md) | Scope, milestones, backlog structure, and dependency management |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | Sprint workflow, project board usage, PR process, and Definition of Done |
| [Risks and Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, status templates, and stakeholder comms |
| [Release and Deployment](octoacme-release-and-deployment.md) | Release types, pre-release checklist, deployment steps, and rollback playbook |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | How to run retrospectives and turn insights into improvement actions |
| [Roles and Personas](octoacme-roles-and-personas.md) | Detailed responsibilities, goals, and communication patterns for each role |

---

## Where to Start / Which Doc to Use

| I want to… | Start here |
|---|---|
| Get a quick end-to-end picture of how OctoAcme runs projects | [Project Management Overview](octoacme-project-management-overview.md) |
| Kick off a new project | [Project Initiation](octoacme-project-initiation.md) |
| Build a project plan or sprint backlog | [Project Planning](octoacme-project-planning.md) |
| Understand day-to-day workflow and the PR/board process | [Execution and Tracking](octoacme-execution-and-tracking.md) |
| Manage risks or set up stakeholder communication | [Risks and Communication](octoacme-risks-and-communication.md) |
| Prepare or execute a production release | [Release and Deployment](octoacme-release-and-deployment.md) |
| Run a retrospective after a release or incident | [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) |
| Understand who does what on a project | [Roles and Personas](octoacme-roles-and-personas.md) |
