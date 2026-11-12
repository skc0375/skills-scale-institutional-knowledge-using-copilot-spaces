# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. A person may hold more than one role on a smaller project, but ownership of each responsibility should remain explicit.

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
- Weekly alignment with project and engineering leads
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

## Additional Project Management Roles

These roles make ownership clearer across business decisions, delivery, requirements, technical design, quality, adoption, and operations. Assign them where project scale and context warrant; on smaller projects, one person may cover multiple roles, while decision authority and accountability remain clear.

### Project Sponsor / Business Owner

#### Role Summary
The Project Sponsor / Business Owner is accountable for the business case, intended outcomes, and high-level project decisions. This role provides organizational support and ensures the project remains aligned with business priorities.

#### Responsibilities
- Confirm the business need, expected benefits, and success measures
- Secure or escalate decisions about funding, scope, and organizational priorities
- Remove organizational blockers and resolve escalations beyond the project team's authority
- Review progress and determine whether the expected outcomes remain valuable

#### Interactions with Existing Roles
- Partners with the Project Manager on governance, priority conflicts, and escalations; the Project Manager continues to manage day-to-day delivery coordination.
- Aligns with the Product Manager on business outcomes and strategic trade-offs.
- Consults the Product Owner and stakeholders on user and operational impacts, and supports the Change Management Lead in securing leadership engagement.

### Product Owner

#### Role Summary
The Product Owner translates product and business priorities into an actionable, ordered set of work and clarifies what constitutes an acceptable outcome. Where a Product Manager already owns product strategy and backlog prioritization, the Product Owner works within that direction rather than duplicating it.

#### Responsibilities
- Refine and prioritize team-level work based on agreed product goals
- Clarify requirements, user needs, and acceptance criteria
- Make or obtain timely decisions on work-scope questions within delegated authority
- Review completed work against acceptance expectations and communicate feedback

#### Interactions with Existing Roles
- Works with the Product Manager to keep team priorities aligned with product strategy, success measures, and roadmap decisions.
- Collaborates with the Business Analyst and stakeholders to clarify needs and acceptance criteria.
- Coordinates with Developers and the QA / Test Lead on scope, acceptance, and defect decisions, and with the Project Manager on dependencies and delivery impacts.

### Delivery Lead / Scrum Master

#### Role Summary
The Delivery Lead / Scrum Master supports the team's delivery practices and flow. This role facilitates team collaboration and helps resolve day-to-day impediments; it does not replace the Project Manager's accountability for overall project coordination, risks, or stakeholder reporting.

#### Responsibilities
- Facilitate team planning, reviews, and regular coordination as appropriate to the delivery approach
- Make workflow, blockers, and delivery risks visible to the team
- Help the team identify and address impediments and improve its working practices
- Coordinate team-level dependencies and raise those requiring broader authority

#### Interactions with Existing Roles
- Coordinates with the Project Manager on schedule, cross-team dependencies, risks, and escalations while maintaining a focus on team-level flow.
- Works with the Product Owner to prepare and clarify prioritized work.
- Supports Developers and the QA / Test Lead in coordinating work and surfacing impediments; does not make product-priority or technical-design decisions on their behalf.

### Business Analyst

#### Role Summary
The Business Analyst elicits, analyzes, and documents business needs, processes, and requirements so that stakeholders and the delivery team share an accurate understanding of the problem and expected outcomes.

#### Responsibilities
- Elicit needs and constraints from users, stakeholders, and subject-matter experts
- Document requirements, process flows, assumptions, and acceptance criteria
- Identify gaps, conflicts, and impacts across business processes
- Validate that requirements remain traceable to intended outcomes as they evolve

#### Interactions with Existing Roles
- Works with the Product Manager and Product Owner to translate desired outcomes into clear, prioritized requirements.
- Partners with the Project Manager to surface scope implications, dependencies, and decisions that affect the plan.
- Collaborates with Developers and the QA / Test Lead to resolve requirement questions and ensure requirements can be implemented and validated.

### Technical Lead / Architect

#### Role Summary
The Technical Lead / Architect guides technical design and integration, helping ensure that solutions meet engineering standards and account for technical constraints and risks.

#### Responsibilities
- Recommend and document technical designs, standards, and integration approaches
- Identify technical dependencies, feasibility concerns, and risks; propose mitigations
- Guide technical decisions and support consistent implementation across components
- Communicate technical impacts of scope or schedule changes

#### Interactions with Existing Roles
- Advises the Project Manager on technical risks, estimates, dependencies, and their delivery impacts.
- Works with Developers on design, implementation, and reviews, and with the Product Manager or Product Owner on technical trade-offs affecting value or scope.
- Coordinates with the QA / Test Lead and Operations / Release Owner on testability, reliability, deployment, and operational constraints.

### QA / Test Lead

#### Role Summary
The QA / Test Lead coordinates the quality strategy and validation needed to provide evidence that the solution meets requirements and is ready for its intended use.

#### Responsibilities
- Define or coordinate test coverage, methods, and quality checkpoints
- Ensure requirements and acceptance criteria have corresponding validation
- Coordinate testing, communicate defects and quality risks, and track their resolution
- Report quality evidence and readiness concerns before release decisions

#### Interactions with Existing Roles
- Partners with the Product Owner and Business Analyst to make acceptance criteria testable and clarify expected behavior.
- Coordinates with Developers and the Technical Lead / Architect on test approach, defect triage, and quality risks.
- Shares readiness evidence and unresolved risks with the Project Manager and Operations / Release Owner; escalates release-blocking concerns through agreed governance.

### Change Management Lead

#### Role Summary
The Change Management Lead prepares affected people and organizations to adopt the project's changes and realize the intended benefits.

#### Responsibilities
- Assess stakeholder groups, change impacts, and adoption risks
- Plan communications, engagement, training, and readiness activities
- Gather feedback and identify barriers to adoption
- Track adoption signals and coordinate follow-up support with the appropriate owners

#### Interactions with Existing Roles
- Works with the Project Sponsor / Business Owner to secure visible leadership support and align change activities with desired outcomes.
- Coordinates with the Project Manager to integrate communications, training, and readiness work into the project plan and risk tracking.
- Collaborates with the Product Manager, Product Owner, and stakeholders to ensure guidance reflects the delivered product and user needs; coordinates operational handover with the Operations / Release Owner.

### Operations / Release Owner

#### Role Summary
The Operations / Release Owner coordinates deployment readiness and the transition to ongoing support, ensuring that operational responsibilities and release risks are addressed before launch.

#### Responsibilities
- Define operational readiness needs, deployment steps, and support ownership
- Confirm monitoring, access, documentation, and incident or rollback plans are prepared
- Coordinate release readiness checks and communicate operational risks
- Ensure knowledge and responsibilities are handed over to support teams

#### Interactions with Existing Roles
- Works with the Technical Lead / Architect and Developers on deployment design, reliability, monitoring, and technical handover.
- Coordinates with the QA / Test Lead on test evidence and quality gates, and with the Project Manager on release dependencies, readiness tracking, and escalation.
- Confirms business timing and support expectations with the Project Sponsor / Business Owner and Product Owner, and partners with the Change Management Lead on user communications and transition support.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Adapt role assignments to the project's size and context, keeping decision authority, accountability, and handoffs explicit when roles are combined.
