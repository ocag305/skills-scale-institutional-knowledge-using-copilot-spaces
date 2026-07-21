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

---

## QA / Testing

### Role Summary
QA validates quality and acceptance criteria, ensuring delivered work meets the Definition of Done.

### Responsibilities
- Create and execute manual and automated test plans
- Validate acceptance criteria and regression checks
- Triage test failures and coordinate fixes with Developers
- Work with Product/PM to sign off features for release

### Typical Communication
- Test reports and QA sign-off in PRs
- Participation in planning and retrospectives

---

## Additional Personas (proposed additions)

### Delivery Lead
- Responsibilities: Coordinate cross-team delivery, manage sprint commitments and capacity, keep milestone trackers up to date, identify and remove cross-team blockers.
- Interactions: Works closely with the Project Manager and Product Manager to align schedule and scope; coordinates with Technical Leads to resolve implementation constraints; escalates impediments when needed.
- Why it helps: Reduces ambiguity around day-to-day delivery coordination for larger or cross-functional initiatives.

### Technical Lead / Architect
- Responsibilities: Define technical approach and architecture, make design decisions for complex systems, review high-risk PRs, ensure long-term maintainability and scalability.
- Interactions: Collaborates with Developers, QA, and the Product Manager to balance technical trade-offs and delivery timelines; mentors engineers on design patterns.
- Why it helps: Centralizes ownership for technical consistency and speeds engineering decision-making.

### UX Designer
- Responsibilities: Lead user research and design, produce interaction and visual designs, define UX acceptance criteria, and support usability QA.
- Interactions: Works with Product Managers to translate user needs into designs and acceptance criteria; collaborates with Developers on implementation details.
- Why it helps: Ensures delivered features meet usability standards and reduces rework from UX misunderstandings.

### Security / Compliance Owner
- Responsibilities: Identify security and compliance requirements, run threat/risk assessments, define required security checks and approvals before release.
- Interactions: Coordinates with Developers, QA, and Release Engineers; notifies Product/Project leads of security-related blockers and required mitigations.
- Why it helps: Provides clear ownership for security posture and reduces last-minute release blockers.

### Release Engineer / SRE
- Responsibilities: Maintain and own deployment pipelines, manage release automation, run release verifications and rollbacks, and operate observability and incident response.
- Interactions: Works with Developers and PMs during release planning, supports production incidents, and coordinates post-release monitoring.
- Why it helps: Improves deployment reliability and reduces time-to-recovery during incidents.

### Stakeholder Liaison
- Responsibilities: Act as the primary contact for external stakeholders (sales, support, partners), consolidate and surface stakeholder feedback, and coordinate expectations and communications.
- Interactions: Collaborates with PM and Product Manager to prioritize stakeholder requests and ensure communications are timely and consistent.
- Why it helps: Improves stakeholder alignment and reduces miscommunications.

### Data Analyst
- Responsibilities: Define and instrument success metrics, build dashboards, analyze outcomes post-release, and provide evidence for product decisions.
- Interactions: Works with Product Managers and Engineers to ensure metrics are tracked and used for data-informed decisions.
- Why it helps: Strengthens measurement-driven decision making and helps validate feature outcomes.

---

## How to use these personas
- Add a named person for each role on projects where that role is required.
- Document role owners in project README or the project board.
- Use the templates and checklists (see docs/checklists/) to capture onboarding and handoff steps for each role.
