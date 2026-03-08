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

### Interactions with Other Roles
- Work with **Business Analyst** to clarify requirements and acceptance criteria
- Collaborate with **QA Lead** on test strategy and defect resolution
- Coordinate with **Release Coordinator** on deployment readiness and go-live steps

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

### Interactions with Other Roles
- Partner with **Project Sponsor** to align roadmap with organizational strategy
- Work with **Business Analyst** to translate business needs into backlog items
- Collaborate with **Change Manager** to plan adoption for new product capabilities

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

### Interactions with Other Roles
- Escalate blockers to the **Project Sponsor** for executive decisions
- Rely on the **Business Analyst** for requirements documentation and gap analysis
- Align release scheduling with the **Release Coordinator**
- Loop in the **Change Manager** early when a release introduces process or workflow changes

---

## Project Sponsor

### Role Summary
The Project Sponsor provides executive oversight, secures resources, and ensures the project aligns with organizational strategy and priorities. They serve as the ultimate decision-maker for scope, budget, and strategic direction.

### Responsibilities
- Champion the project at the executive level and secure funding/resources
- Approve the project charter, major scope changes, and key milestones
- Remove organizational blockers that the Project Manager cannot resolve
- Ensure alignment between project goals and organizational strategy
- Provide final go/no-go decisions at key decision gates

### Goals
- Ensure the project delivers measurable business value
- Keep the project aligned with evolving organizational priorities
- Enable the delivery team by removing systemic obstacles

### Typical Communication
- Milestone-based briefings from the Project Manager
- Executive status summaries (written, concise)
- Escalation notifications for business-impacting risks

### Interactions with Other Roles
- Delegates day-to-day coordination to the **Project Manager**
- Aligns strategic outcomes with the **Product Manager**
- Receives escalation from the **Change Manager** when adoption risk is high

---

## Business Analyst

### Role Summary
The Business Analyst elicits requirements, documents business needs, and bridges communication between business stakeholders and the delivery team. They ensure that what is built solves the right problem.

### Responsibilities
- Conduct stakeholder interviews and workshops to elicit requirements
- Document functional and non-functional requirements with clear acceptance criteria
- Analyze current-state processes and identify gaps or improvement opportunities
- Translate business needs into backlog-ready user stories
- Validate that delivered functionality meets business requirements

### Goals
- Ensure requirements are complete, unambiguous, and traceable
- Reduce rework caused by misunderstood or missing requirements
- Improve alignment between business and technical teams

### Typical Communication
- Requirements documents and user story write-ups
- Regular sync with Product Manager and Project Manager
- Sign-off workshops or reviews with business stakeholders

### Interactions with Other Roles
- Works closely with **Product Manager** to refine and prioritize requirements
- Provides **Developers** with well-defined stories and acceptance criteria
- Partners with **QA Lead** to validate that test cases cover the business requirements
- Supports the **Change Manager** with process-change impact analysis

---

## Quality Assurance (QA) Lead

### Role Summary
The QA Lead defines the overall testing strategy, ensures that deliverables meet acceptance criteria and quality standards, and coordinates quality checkpoints across the project lifecycle.

### Responsibilities
- Define and maintain the test strategy, test plans, and entry/exit criteria
- Coordinate functional, regression, integration, and user acceptance testing (UAT)
- Track and report defects; triage with developers to prioritize resolution
- Validate acceptance criteria are met before milestone sign-off
- Champion quality best practices and shift-left testing approaches

### Goals
- Prevent defects from reaching production
- Maintain high confidence in each release through systematic testing
- Keep the cost of quality visible and improving sprint over sprint

### Typical Communication
- Test summary reports at end of each sprint or milestone
- Defect triage meetings with Developers and Project Manager
- QA sign-off statements included in release notes

### Interactions with Other Roles
- Works with **Developers** to define testability requirements and resolve defects
- Reviews acceptance criteria with the **Business Analyst** and **Product Manager**
- Provides quality gate status to the **Release Coordinator** before deployment
- Reports quality metrics and risks to the **Project Manager**

---

## Change Manager

### Role Summary
The Change Manager plans and manages the people-side of change — stakeholder buy-in, communications, training, and adoption — to ensure that new processes, tools, or releases are successfully adopted by the organization.

### Responsibilities
- Develop and execute a change management plan for each significant release or process change
- Identify impacted stakeholder groups and assess readiness
- Create and deliver change communications, training materials, and adoption guides
- Monitor adoption metrics and address resistance or confusion
- Coordinate with teams to ensure support structures are in place post-release

### Goals
- Maximize user adoption and minimize disruption to business operations
- Ensure stakeholders understand and embrace changes
- Reduce change-related incidents or rollbacks caused by adoption failure

### Typical Communication
- Change impact assessments shared with the Project Manager and Project Sponsor
- Stakeholder communication plans reviewed with the Product Manager
- Adoption dashboards and readiness reports at key milestones

### Interactions with Other Roles
- Aligns with **Product Manager** on messaging and release timing
- Collaborates with **Business Analyst** to understand process impacts
- Coordinates with **Release Coordinator** on go-live communications and training schedules
- Escalates unresolved adoption risks to the **Project Sponsor**

---

## Release Coordinator

### Role Summary
The Release Coordinator oversees the release schedule, manages go-live checklists, and ensures each deployment is executed according to established procedures. They act as the hub connecting QA, development, operations, and communications for each release.

### Responsibilities
- Maintain the release calendar and coordinate deployment windows
- Own and execute the go-live checklist (pre-deployment, deployment, post-deployment)
- Confirm that QA sign-off, rollback plan, and release notes are ready before deployment
- Coordinate with operations and infrastructure teams on deployment logistics
- Announce releases to stakeholders and ensure support teams are briefed

### Goals
- Execute predictable, low-risk releases
- Ensure all release readiness criteria are met before go-live
- Provide a clear audit trail for each release event

### Typical Communication
- Release readiness status updates to the Project Manager
- Deployment window notifications to all relevant teams
- Post-release announcements to stakeholders

### Interactions with Other Roles
- Receives QA sign-off from the **QA Lead** before approving deployment
- Coordinates release timing with the **Project Manager** and **Change Manager**
- Works with **Developers** to confirm build artifacts and deployment scripts are ready
- Briefs the **Project Sponsor** and key stakeholders via the **Change Manager** on go-live status

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [`octoacme-raci-matrix.md`](octoacme-raci-matrix.md) for a summary of how all roles participate across the project lifecycle.

