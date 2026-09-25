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

## How to scale the core team

Every OctoAcme project should identify a Product Manager, Project Manager, and Developers. QA/Testing and Stakeholders are also expected collaborators, even when they are not dedicated full-time roles on the project.

Add the personas below based on project scope:

- **Business Sponsor / Executive Sponsor** when funding, priority, or cross-org escalation needs executive support.
- **UX / Product Designer** when user research, workflows, or design quality materially affect outcomes.
- **Technical Lead / Architect** when the team needs clear technical direction, architecture decisions, or complex dependency management.
- **DevOps / Site Reliability Engineer** when environments, observability, reliability, or deployment automation are significant delivery risks.
- **Security, Privacy, or Compliance Partner** when the work handles sensitive data, regulated workflows, or elevated risk.
- **Data / Analytics Partner** when the team needs instrumentation, reporting, experimentation, or success-metric validation.
- **Customer Support / Operations Representative** when release readiness depends on support workflows, operational runbooks, or customer-impact planning.
- **Release Manager** when delivery requires coordinated go/no-go checkpoints across multiple teams or systems.

These additional personas should clarify ownership and handoffs without adding unnecessary ceremony. A single person may cover more than one role on smaller projects.

### Decision rights and typical artifacts

| Persona | Primary decision rights | Typical artifacts |
| --- | --- | --- |
| Business Sponsor / Executive Sponsor | Funding approval, major priority shifts, escalation outcomes | Business case, milestone approvals, executive status decisions |
| UX / Product Designer | User-flow and interaction decisions within agreed scope | Journey maps, wireframes, prototypes, design acceptance notes |
| Technical Lead / Architect | Architecture direction, technical trade-offs, exception handling | Technical designs, architecture decisions, dependency plans |
| DevOps / Site Reliability Engineer | Deployment guardrails, observability standards, operational readiness criteria | Pipeline changes, runbooks, monitors, rollback procedures |
| Security, Privacy, or Compliance Partner | Control requirements, risk acceptance recommendations, compliance checkpoints | Risk assessments, control checklists, approval evidence |
| Data / Analytics Partner | Measurement design, telemetry quality expectations, reporting definitions | Tracking plans, dashboard definitions, experiment or metric readouts |
| Customer Support / Operations Representative | Support-readiness requirements, customer-communication inputs, operational escalation needs | Support guides, readiness checklists, escalation notes |
| Release Manager | Release sequencing, go/no-go coordination, rollback readiness confirmation | Release checklist, launch communications, rollback plan |

### Lifecycle participation at a glance

- **Initiation:** Sponsor sets direction, Product Manager defines outcomes, Project Manager frames delivery approach, and Technical, Design, Security, Data, and Operations partners identify early risks and constraints.
- **Planning:** Core and supporting roles agree on scope, milestones, architecture, test approach, dependencies, metrics, and release criteria.
- **Execution:** Developers, QA/Testing, and specialist partners collaborate on delivery, unblock issues, and manage changes through the backlog and risk register.
- **Release:** Release, DevOps/SRE, Support/Operations, Security, and project leads confirm readiness, communications, rollback plans, and approvals.
- **Retrospective:** All roles contribute lessons learned in proportion to their involvement and convert them into concrete follow-up actions.

---

## Business Sponsor / Executive Sponsor

### Role Summary
The Business Sponsor provides strategic direction, funding support, and escalation coverage so the team can make timely decisions and stay aligned to business outcomes.

### Responsibilities
- Confirm the business problem, expected value, and success criteria during initiation
- Approve major scope, funding, or priority changes that exceed the working team's authority
- Resolve escalations that require cross-functional alignment or executive support
- Hold Product Managers and Project Managers accountable for outcome visibility

### Key Interactions
- Partners with the Product Manager on strategic goals, trade-offs, and success measures
- Supports the Project Manager when risks, dependencies, or timelines need executive decisions
- Reviews milestone progress with Stakeholders and helps remove organizational blockers

### Lifecycle Participation
- **Initiation:** validates the investment and outcome
- **Planning:** approves major milestones and decision boundaries
- **Execution:** joins escalations and milestone reviews as needed
- **Release:** confirms readiness for high-visibility launches when appropriate
- **Retrospective:** reviews outcome performance and follow-up investments

---

## UX / Product Designer

### Role Summary
The UX or Product Designer ensures the solution is usable, coherent, and grounded in customer needs.

### Responsibilities
- Lead discovery for workflows, pain points, and user expectations
- Produce design artifacts such as flows, wireframes, or prototypes
- Define interaction details that Developers and QA/Testing can validate
- Help assess usability risks before release

### Key Interactions
- Works with the Product Manager to translate customer problems into user journeys and acceptance criteria
- Collaborates with Developers on feasibility, edge cases, and implementation details
- Partners with QA/Testing to validate usability and design acceptance during execution

### Lifecycle Participation
- **Initiation:** contributes research findings and user context
- **Planning:** defines experience scope and design deliverables
- **Execution:** reviews implementation, clarifies interactions, and supports acceptance
- **Release:** confirms user-facing changes are communicated and production-ready
- **Retrospective:** shares customer-experience learnings

---

## Technical Lead / Architect

### Role Summary
The Technical Lead or Architect guides architecture, engineering trade-offs, and technical risk management across the project lifecycle.

### Responsibilities
- Set technical direction, guardrails, and design review expectations
- Make or facilitate architecture decisions with clear trade-offs
- Identify technical dependencies, scalability concerns, and delivery risks
- Support estimation and sequencing for technically complex work

### Key Interactions
- Works closely with Developers on implementation approach and quality standards
- Helps the Product Manager and Project Manager understand technical constraints and options
- Coordinates with DevOps/SRE, Security, and QA/Testing on non-functional requirements

### Lifecycle Participation
- **Initiation:** assesses feasibility and major dependencies
- **Planning:** shapes architecture, milestones, and technical risk mitigation
- **Execution:** reviews design changes, resolves blockers, and steers trade-offs
- **Release:** validates operational and technical readiness
- **Retrospective:** identifies engineering improvements and debt follow-up

---

## DevOps / Site Reliability Engineer

### Role Summary
The DevOps or Site Reliability Engineer owns environment readiness, deployment automation, observability, and service reliability expectations.

### Responsibilities
- Prepare environments, pipelines, and operational checks needed for delivery
- Define monitoring, alerting, and incident-readiness requirements
- Improve deployment safety, rollback paths, and recovery procedures
- Surface reliability risks that affect scope or launch decisions

### Key Interactions
- Partners with Developers on build, deployment, and observability implementation
- Works with the Project Manager and Release Manager on release readiness and rollback planning
- Coordinates with Security and QA/Testing on environment controls and verification

### Lifecycle Participation
- **Initiation:** identifies infrastructure or reliability constraints
- **Planning:** defines environment, automation, and support requirements
- **Execution:** enables deployments, telemetry, and operational testing
- **Release:** leads operational readiness and production verification steps
- **Retrospective:** contributes incident, reliability, and automation lessons

---

## Security, Privacy, or Compliance Partner

### Role Summary
The Security, Privacy, or Compliance Partner helps the team identify control requirements early and validate that mitigations are built into delivery plans.

### Responsibilities
- Identify security, privacy, and compliance requirements relevant to the work
- Review risks, controls, and exceptions before they become release blockers
- Validate that testing and release plans cover required protections
- Support auditability and evidence needs when applicable

### Key Interactions
- Works with the Project Manager to track risk, approvals, and required checkpoints
- Partners with Developers and Technical Leads on secure design and mitigation choices
- Aligns with QA/Testing and DevOps/SRE on verification, logging, and operational controls

### Lifecycle Participation
- **Initiation:** highlights sensitive data flows and policy needs
- **Planning:** defines controls, review points, and approval criteria
- **Execution:** reviews implementation and test evidence for key risks
- **Release:** confirms required controls and approvals are in place
- **Retrospective:** captures risk, incident, or control improvement actions

---

## Data / Analytics Partner

### Role Summary
The Data or Analytics Partner ensures the project can measure adoption, quality, and business outcomes with trustworthy instrumentation.

### Responsibilities
- Define measurement plans, event taxonomy, and reporting expectations
- Help the Product Manager translate goals into measurable success signals
- Validate data quality, dashboards, and experiment-readiness where needed
- Highlight reporting gaps that could limit decision-making after launch

### Key Interactions
- Partners with the Product Manager on success metrics and learning plans
- Works with Developers on telemetry implementation and data quality checks
- Supports Stakeholders and Sponsors with outcome reporting after release

### Lifecycle Participation
- **Initiation:** advises on measurable outcomes and baseline data
- **Planning:** documents instrumentation and reporting requirements
- **Execution:** validates telemetry, dashboards, and experiment support
- **Release:** confirms monitoring for adoption and outcome tracking
- **Retrospective:** shares performance insights and recommendations

---

## Customer Support / Operations Representative

### Role Summary
The Customer Support or Operations Representative brings customer-impact awareness, support readiness, and operational practicality into delivery decisions.

### Responsibilities
- Provide frontline context on recurring issues, operational constraints, and support needs
- Prepare support materials, runbooks, and readiness checklists for launch
- Flag customer communication, training, or staffing requirements
- Surface post-release issues and feedback for triage

### Key Interactions
- Works with the Product Manager on customer-impact scenarios and messaging
- Partners with the Project Manager and Release Manager on readiness planning
- Coordinates with QA/Testing and Developers on support workflows, troubleshooting, and defect trends

### Lifecycle Participation
- **Initiation:** shares operational pain points and customer context
- **Planning:** defines readiness tasks and support dependencies
- **Execution:** reviews support impacts and validates operational workflows
- **Release:** confirms support coverage, communications, and escalation paths
- **Retrospective:** contributes customer and operations feedback

---

## Release Manager

### Role Summary
The Release Manager coordinates release readiness across teams and drives clear go/no-go decisions for launches with elevated coordination needs.

### Responsibilities
- Maintain the release checklist, schedule, and stakeholder communication plan
- Confirm dependencies, approvals, rollback plans, and ownership before launch
- Coordinate final readiness reviews and production change windows
- Track release outcomes, incidents, and follow-up actions

### Key Interactions
- Works with the Project Manager on timeline management and escalation
- Partners with Developers, QA/Testing, DevOps/SRE, and Security on release criteria
- Keeps Stakeholders, Support/Operations, and Sponsors informed on launch timing and risk

### Lifecycle Participation
- **Initiation:** optional unless release coordination is already known to be complex
- **Planning:** defines release milestones, checkpoints, and entry/exit criteria
- **Execution:** monitors readiness, dependencies, and approval status
- **Release:** leads go/no-go coordination, communications, and rollback preparedness
- **Retrospective:** documents launch lessons and release process improvements

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
