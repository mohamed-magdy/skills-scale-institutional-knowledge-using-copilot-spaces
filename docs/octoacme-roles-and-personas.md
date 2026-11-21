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

## Engineering Leads / Technical Architects

### Role Summary
Engineering Leads and Technical Architects provide technical direction and ensure that implementation choices support maintainability, reliability, security, and delivery goals.

### Responsibilities
- Recommend architectural approaches and resolve significant technical trade-offs
- Review feasibility, integration points, and technical dependencies during planning
- Establish engineering standards and guide design and code reviews
- Help identify, estimate, and mitigate technical risks
- Coordinate technical decisions across teams

### Goals
- Maintain a coherent, scalable technical design
- Reduce delivery risk from unresolved dependencies or architectural issues
- Enable Developers to deliver consistently and safely

### Typical Communication
- Architecture and technical design reviews
- Sprint planning and dependency discussions
- Engineering risk escalations and implementation guidance

### Interactions with Existing Roles
The Engineering Lead works with the Product Manager to translate outcomes into technically viable options and with the Project Manager to identify milestones, dependencies, and risks. Developers own implementation and consult the Engineering Lead on design decisions. QA and Security roles validate quality and control requirements, while Project and Product stakeholders receive clear technical trade-offs and decisions.

---

## UX / Product Designers

### Role Summary
UX and Product Designers turn customer and business needs into clear, usable experiences. They represent users throughout discovery, delivery, and validation.

### Responsibilities
- Conduct or synthesize user research and usability findings
- Create interaction flows, wireframes, prototypes, and visual specifications
- Define usability and accessibility expectations
- Validate designs with users and delivery teams
- Maintain consistency across product experiences

### Goals
- Improve usability and customer value
- Reduce ambiguity by making intended behavior visible before implementation
- Ensure accessibility and consistent experience

### Typical Communication
- Discovery and design reviews
- Acceptance criteria and design handoffs
- Usability testing and feedback sessions

### Interactions with Existing Roles
The Designer partners with the Product Manager to connect user needs and product outcomes, and with Developers to ensure implementations match approved designs. The Project Manager tracks design dependencies and review decisions. QA includes usability and accessibility criteria in validation, and stakeholders provide domain and policy context.

---

## Security Leads

### Role Summary
Security Leads define security requirements and help teams identify, prioritize, and mitigate threats and compliance risks across the project lifecycle.

### Responsibilities
- Define security and compliance requirements
- Review architecture and implementation for security risks
- Coordinate threat modeling and security testing
- Recommend mitigations and document residual risks
- Support incident response and security readiness

### Goals
- Prevent avoidable security and compliance exposure
- Make security requirements visible during planning and review
- Enable safe, auditable releases

### Typical Communication
- Security and threat-model reviews
- Risk register updates and control exceptions
- Release readiness and incident coordination

### Interactions with Existing Roles
The Security Lead advises the Engineering Lead and Developers on controls and threat mitigations, while the QA Lead coordinates security test coverage. The Project Manager records unresolved risks and escalations, and the Product Manager weighs security constraints against outcomes. Release and Operations roles ensure controls are enforced in deployment and operations.

---

## QA Leads

### Role Summary
QA Leads own the test strategy and quality evidence needed to determine whether work meets acceptance criteria and is ready for release.

### Responsibilities
- Define test scope, strategy, environments, and quality metrics
- Review acceptance criteria for completeness and testability
- Coordinate unit, integration, end-to-end, accessibility, and exploratory testing
- Track defects, test coverage, and release-quality risks
- Provide a go/no-go quality recommendation

### Goals
- Improve confidence that delivered behavior meets customer and technical requirements
- Surface defects and quality gaps early
- Maintain repeatable and observable release evidence

### Typical Communication
- Test planning and backlog refinement
- QA reviews and defect triage
- Release readiness checks

### Interactions with Existing Roles
The QA Lead works with the Product Manager and Product Designer to make acceptance criteria observable and with Developers to plan test coverage and resolve defects. The Project Manager coordinates QA dependencies and release timing, while the Engineering and Security Leads address technical or security gaps. QA provides quality evidence to the Release Manager and stakeholders.

---

## Release Managers / DevOps Leads

### Role Summary
Release Managers and DevOps Leads own dependable, repeatable delivery paths and coordinate deployment, rollback readiness, and operational handoff.

### Responsibilities
- Plan and coordinate deployment windows and release communications
- Maintain automated build, deployment, verification, and rollback processes
- Confirm backup, migration, and smoke-test readiness
- Coordinate release evidence and post-deployment checks
- Handoff operational responsibilities to Support and Operations

### Goals
- Reduce release risk and manual effort
- Improve recovery time when deployments fail
- Make production readiness explicit and repeatable

### Typical Communication
- Release planning and go/no-go reviews
- Deployment coordination and incident updates
- Post-release verification and handoff

### Interactions with Existing Roles
The Release/DevOps Lead works with Developers and the Engineering Lead on deployment compatibility, with QA on release evidence, and with the Project Manager on schedule and communications. Security requirements are confirmed with the Security Lead, while runbooks and support readiness are coordinated with Support/Operations and the Change Manager.

---

## Support / Operations Leads

### Role Summary
Support and Operations Leads represent production readiness and the needs of customers and support teams after launch.

### Responsibilities
- Define operational readiness and support requirements
- Create or review runbooks, monitoring expectations, and escalation routes
- Prepare support teams for known changes, incidents, and support volume
- Provide production feedback and recurring customer issues
- Coordinate incident communication and recovery actions

### Goals
- Improve customer supportability and incident response
- Reduce operational surprises after release
- Feed production evidence back into product decisions

### Typical Communication
- Operational readiness reviews
- Incident triage and status updates
- Product and engineering feedback sessions

### Interactions with Existing Roles
Support/Operations partners with the Release/DevOps Lead on deployment handoff and the Engineering Lead on observability and recovery. The Product Manager uses production and customer feedback to prioritize improvements, while the Project Manager tracks operational dependencies and Communications. QA and Security roles coordinate test and control evidence for support readiness.

---

## Data / Analytics Leads

### Role Summary
Data and Analytics Leads ensure that project outcomes are measurable and that teams have reliable evidence for prioritizing and validating decisions.

### Responsibilities
- Define metrics, instrumentation, and reporting requirements
- Validate data quality and measurement methodology
- Design dashboards, experiments, and evaluation plans
- Interpret results and communicate evidence and limitations
- Identify gaps in the success-measurement approach

### Goals
- Improve the reliability and usefulness of outcome data
- Reduce decisions based on incomplete or ambiguous measurements
- Shorten feedback loops for product and delivery improvements

### Typical Communication
- Success-metrics definition and review
- Experiment and dashboard planning
- Outcome readouts and retrospectives

### Interactions with Existing Roles
The Data/Analytics Lead collaborates with the Product Manager to turn success metrics into measurable indicators and with the Engineering Lead and Developers on instrumentation. The QA Lead validates data and reporting where needed, and the Project Manager includes measurement milestones in the delivery plan. Results inform stakeholder updates and project retrospectives.

---

## Change Managers / Training Leads

### Role Summary
Change Managers and Training Leads prepare people and organizations to adopt significant process or product changes.

### Responsibilities
- Assess stakeholder impact and adoption needs
- Plan stakeholder communications and training
- Create or coordinate documentation and learning materials
- Track adoption readiness and change feedback
- Coordinate launch support and reinforcement

### Goals
- Improve adoption and reduce change friction
- Ensure users and teams understand and can use new capabilities
- Surface stakeholder risks before launch

### Typical Communication
- Change and stakeholder impact planning
- Training and enablement sessions
- Adoption updates and launch communications

### Interactions with Existing Roles
The Change/Training Lead works with the Product Manager on customer value and stakeholder impacts, the Project Manager on timing and communications, and Support/Operations on launch readiness and issue escalation. The UX/Product Designer ensures guidance matches the user experience, while Developers and the Release/DevOps Lead coordinate feature and documentation availability.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

