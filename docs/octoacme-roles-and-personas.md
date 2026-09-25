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

## Security Champion

### Role Summary
Security Champions embed secure development practices into the team’s day-to-day work and help reduce security risk without slowing delivery.

### Responsibilities
- Review designs and architecture for security risks and compliance considerations
- Facilitate threat modeling and security design discussions
- Help prioritize remediation for vulnerabilities and technical debt
- Partner with developers and project leads on secure implementation patterns
- Support release readiness checks for security-sensitive changes

### Goals
- Reduce security risk across features and services
- Improve security awareness across the delivery team
- Support a secure and compliant release process

### Typical Communication
- Security design reviews and architecture discussions
- Vulnerability triage and remediation planning
- Release readiness checks and risk briefings

### How this role interacts with existing personas
- Works closely with Developers on secure implementation, code review, and remediation planning
- Supports Project Managers by surfacing risks that may impact schedule, scope, or release approval
- Collaborates with Product Managers to assess customer or business impact when security decisions affect roadmap trade-offs
- Provides clear escalation paths for stakeholder awareness when risks require broader action

---

## QA Lead / Test Owner

### Role Summary
QA Leads ensure quality is designed into delivery and that features meet agreed acceptance criteria before release.

### Responsibilities
- Define test strategy, quality gates, and release readiness criteria
- Validate that user stories and requirements are testable and complete
- Coordinate manual and automated test coverage for critical flows
- Partner with developers to reduce defects and improve regression safety
- Provide go/no-go recommendations for milestones and releases

### Goals
- Improve confidence in feature quality and reliability
- Reduce defect leakage into production
- Align validation activities with business and customer expectations

### Typical Communication
- Acceptance criteria review and validation planning
- Defect triage and release readiness updates
- Cross-team quality checkpoints during sprint and release cycles

### How this role interacts with existing personas
- Works with Developers to review testability, identify defects, and confirm fixes
- Aligns with Product Managers on acceptance criteria and stakeholder expectations
- Supports Project Managers with risk and timeline visibility for release quality
- Helps stakeholders understand quality trade-offs and confidence levels before go-live

---

## Release Manager / Delivery Coordinator

### Role Summary
Release Managers coordinate deployment readiness, release timing, and communication so that changes move to production with clear ownership and minimal disruption.

### Responsibilities
- Create and maintain release plans, windows, and deployment checklists
- Coordinate staging, production deployment sequencing, and rollback readiness
- Partner with engineering and QA on release validation and post-deploy checks
- Draft release communications and coordinate stakeholder notifications
- Track issues that may affect deployment success or customer impact

### Goals
- Reduce release risk and operational disruption
- Improve predictability across milestone and production deployments
- Ensure clear communication before, during, and after releases

### Typical Communication
- Release planning and deployment status updates
- Rollback readiness and incident communication
- Stakeholder announcements and support coordination

### How this role interacts with existing personas
- Works with Developers and QA Lead to confirm release readiness and verify deployment success
- Coordinates with Project Managers to align release timing with milestones and dependencies
- Provides Product Managers and stakeholders with updates on release status, risks, and customer impact
- Acts as the handoff point between delivery execution and operational support

---

## Customer / Stakeholder Advocate

### Role Summary
Customer and Stakeholder Advocates ensure project decisions remain grounded in user needs, business context, and stakeholder expectations.

### Responsibilities
- Represent user needs, customer pain points, and business goals in planning discussions
- Validate that roadmap decisions and trade-offs align with expected outcomes
- Surface stakeholder concerns and decision needs early in the delivery lifecycle
- Support prioritization by clarifying value, urgency, and operational impact
- Help confirm whether a feature or release has delivered the intended result

### Goals
- Keep delivery focused on customer and business value
- Reduce misalignment between product decisions and stakeholder expectations
- Improve trust and clarity across governance and delivery discussions

### Typical Communication
- Stakeholder reviews and prioritization discussions
- Customer feedback summaries and validation checkpoints
- Milestone and release outcome reviews

### How this role interacts with existing personas
- Partners with Product Managers to translate business priorities into clear outcomes and trade-offs
- Supports Project Managers by clarifying decision-making needs and stakeholder dependencies
- Helps Developers understand user intent and business context behind requirements
- Provides feedback to leadership on expected value, risks, and readiness for launch

---

## Data / Analytics Lead

### Role Summary
Data and Analytics Leads provide the measurement layer that helps the team understand impact, monitor success signals, and refine decisions with evidence.

### Responsibilities
- Define success metrics, instrumentation plans, and dashboard needs
- Track project performance against agreed goals and operational signals
- Work with teams to validate whether the released change improved business or user outcomes
- Help interpret data and identify when adjustments are needed
- Support retrospective and decision-making with concrete evidence

### Goals
- Make outcomes measurable and visible
- Improve evidence-based decision making
- Help teams learn from release and usage data

### Typical Communication
- KPI reviews and metric definitions
- Dashboard updates and experiment / launch analysis
- Retrospective follow-up tied to measurable impact

### How this role interacts with existing personas
- Works with Product Managers to define and review success metrics and product impact
- Supports Project Managers by surfacing operational risks, trend changes, and delivery health indicators
- Collaborates with Developers on instrumentation, monitoring, and data quality requirements
- Helps stakeholders understand whether the initiative is delivering value and what to do next

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Together, these roles clarify ownership, improve cross-functional handoffs, and support accountability across planning, execution, release, and learning.

