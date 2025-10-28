```markdown
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
QA ensures that delivered work meets acceptance criteria and quality standards through testing and verification.

### Responsibilities
- Define testing approaches for features and releases
- Execute manual tests when necessary and verify automated test coverage
- Collaborate with developers to reproduce and triage issues
- Validate release readiness and sign-off on acceptance criteria

### Typical Communication
- QA reports during weekly delivery syncs
- Test status in PRs and release docs

---

## Stakeholders

Represent business groups, customers, or partners who provide inputs, priorities, and approvals for project work.

---

## Additional Personas (Proposed additions)

These roles are commonly involved in cross-functional delivery but were previously underspecified. Adding them clarifies accountability and improves handoffs.

### UX / UI Designer

- Role Summary:
  Design usable, accessible experiences that meet product goals and stakeholder needs.
- Responsibilities:
  - Create user flows, wireframes, high-fidelity mockups, and interactive prototypes.
  - Conduct usability reviews and accessibility checks.
  - Provide design acceptance criteria and QA guidance for visual/UX behavior.
  - Participate in product discovery and user research.
- Interaction:
  - Works with Product Managers to translate requirements into designs.
  - Handoffs assets and specifications to Developers; reviews implementations in PRs.
  - Contributes to acceptance criteria and demo materials.

### DevOps / Platform Engineer

- Role Summary:
  Build and maintain automated delivery pipelines, environments, observability, and platform security.
- Responsibilities:
  - Design and operate CI/CD pipelines and infrastructure-as-code.
  - Configure monitoring, alerts, and runbooks for production systems.
  - Automate staging and deployment processes; manage secrets and access controls.
  - Support incident response and post-incident remediation.
- Interaction:
  - Works with Developers to enable safe, repeatable deployments.
  - Coordinates with QA to provide test environments and automation resources.
  - Escalates production-level risks to PM/Project stakeholders.

### Data Analyst / Analytics Engineer

- Role Summary:
  Provide data-driven insights to measure product outcomes and validate success metrics.
- Responsibilities:
  - Define and instrument metrics and events required to validate hypotheses.
  - Build dashboards and reports for stakeholders and PMs.
  - Analyze experiments and feature performance; surface actionable insights.
  - Validate data quality and collaborate on migration/ETL considerations.
- Interaction:
  - Works with Product Managers to define success metrics.
  - Partners with Developers and DevOps to ensure correct data pipelines.
  - Shares findings in weekly delivery syncs and retrospectives.

### Customer Support Lead (or Support Engineer)

- Role Summary:
  Act as the front line for user-reported issues, escalate incidents, and feed user insights back to product and engineering.
- Responsibilities:
  - Triage incoming support tickets and create reproducible issues.
  - Maintain knowledge base and FAQs relevant to releases.
  - Own communication with affected users during incidents and planned changes.
  - Provide user-impact data and trends to the product team.
- Interaction:
  - Communicates major incidents and recurring user pain points to PMs and Project Managers.
  - Works with Developers for reproductions and fixes; with QA for post-fix verification.
  - Participates in post-incident reviews and retrospectives.

---

## How these personas interact (high-level)

- Product Manager defines the why and success metrics; UX designs the how; Developers and QA implement and verify; Project Manager coordinates schedules and communication; DevOps ensures the path to production is safe and observable; Data Analyst validates outcomes; Support keeps the team grounded in user-reported realities.
- Suggested RACI examples:
  - Acceptance criteria: Responsible (PdM), Accountable (PdM), Consulted (UX, Dev), Informed (PM, Stakeholders)
  - Release readiness: Responsible (Dev/QA), Accountable (PM), Consulted (DevOps, PdM), Informed (Support, Stakeholders)
  - Incident communications: Responsible (Support), Accountable (PM), Consulted (DevOps, Dev), Informed (PdM, Sponsor)

---

## Using these persona definitions

- Keep role descriptions short and action-oriented.
- When starting a project, list named individuals for each applicable role on the Project One-pager.
- Use these definitions to create clear handoffs and reduce ambiguity about ownership.
```
