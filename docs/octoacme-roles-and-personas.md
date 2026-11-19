# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Assign these roles according to project needs; one person may hold multiple roles on a small team, but ownership and decision boundaries should remain clear.

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

## Scrum Master / Agile Delivery Facilitator

### Role Summary
Facilitates the team's agreed delivery practices and helps the team improve its flow of work. This role may be combined with the Project Manager role when responsibilities are made explicit.

### Responsibilities
- Facilitate planning, standups, reviews, and retrospectives as agreed by the team
- Help identify and remove impediments, escalating issues the team cannot resolve
- Coach the team on its working agreements and continuous improvement practices
- Surface delivery-flow concerns and dependencies without taking over team ownership

### Goals
- Help the team make predictable progress and resolve blockers early
- Support effective collaboration and sustainable improvement

### Interactions with Existing Roles
- Partners with the Project Manager on delivery visibility, dependencies, and escalations; the Project Manager remains accountable for the overall plan and stakeholder reporting
- Works with the Product Manager to keep planning and review sessions aligned to priorities and outcomes
- Helps Developers and QA/Testing coordinate work and raise impediments
- Invites Stakeholders to reviews when their feedback or decisions are needed

### Typical Communication
- Team ceremonies, working agreements, impediment tracking, and retrospective actions

---

## UX Designer / UX Researcher

### Role Summary
Researches user needs and designs accessible, usable experiences that address the product problem.

### Responsibilities
- Plan and conduct user research and synthesize findings
- Create and validate user flows, prototypes, and design specifications
- Identify usability and accessibility considerations
- Share evidence and design decisions with the delivery team

### Goals
- Ensure solutions address validated user needs and are understandable and usable
- Reduce usability risks through early feedback and iteration

### Interactions with Existing Roles
- Partners with the Product Manager to connect research findings and design choices to customer outcomes and prioritization
- Collaborates with Developers and Technical Leads on feasibility, implementation details, and design trade-offs
- Works with QA/Testing to include usability and accessibility checks in validation
- Shares research insights with the Project Manager for planning and risk tracking and with Stakeholders for feedback at agreed review points

### Typical Communication
- Research plans, findings, design reviews, prototypes, and usability feedback

---

## QA Lead / Test Manager

### Role Summary
Coordinates the test approach and quality signals so the team can assess whether work meets acceptance criteria and is ready for release.

### Responsibilities
- Define and maintain the test strategy and coverage approach
- Coordinate test planning across unit, integration, end-to-end, and manual testing as appropriate
- Identify quality risks, gaps, and defects and track their resolution
- Advise on testability and release-quality evidence

### Goals
- Find important defects early and provide clear evidence of product quality
- Make quality risks visible before release decisions

### Interactions with Existing Roles
- Works with Developers on testability, automated tests, and defect diagnosis
- Partners with the Product Manager to interpret acceptance criteria and with the Project Manager to report quality risks and readiness
- Coordinates with UX Designers on usability and accessibility validation
- Provides Stakeholders with concise test results and known limitations; the release decision remains with the designated decision-makers

### Typical Communication
- Test plans, defect reports, CI results, QA status, and release-readiness assessments

---

## Technical Lead / Architect

### Role Summary
Guides technical design and integration decisions to help the team deliver secure, maintainable solutions.

### Responsibilities
- Establish and communicate technical direction and design constraints
- Identify architectural risks, integration points, and technical dependencies
- Facilitate design reviews and document significant decisions
- Support estimation and decomposition of technical work

### Goals
- Keep the solution maintainable and aligned with technical standards
- Surface technical risks and dependencies early

### Interactions with Existing Roles
- Guides and collaborates with Developers while supporting shared code ownership and review
- Works with the Product Manager to explain technical trade-offs that affect scope or outcomes
- Shares dependencies and risks with the Project Manager for planning and escalation
- Coordinates with QA/Testing, Security Leads, and Release Managers on quality, security, and operational requirements
- Communicates material design decisions and trade-offs to Stakeholders as appropriate

### Typical Communication
- Design documents, architecture decision records, technical estimates, and engineering reviews

---

## Release Manager / DevOps Engineer

### Role Summary
Enables reliable build, deployment, and operation of software through release coordination and delivery automation.

### Responsibilities
- Maintain or coordinate build, deployment, and release automation
- Plan deployment steps, verification, monitoring, and rollback or mitigation procedures
- Confirm operational dependencies and release readiness evidence
- Coordinate release execution and communicate deployment status

### Goals
- Make releases repeatable, observable, and recoverable
- Reduce deployment risk and time to restore service

### Interactions with Existing Roles
- Works with Developers and Technical Leads on pipelines, infrastructure, and deployment changes
- Coordinates with QA/Testing on smoke tests and verification criteria
- Partners with the Project Manager on release timing, dependencies, and status
- Aligns with the Product Manager and Stakeholders on release communications and impact
- Coordinates with Security Leads and Customer/Support Representatives on operational controls and support readiness

### Typical Communication
- Release plans, deployment checklists, monitoring signals, rollback plans, and release announcements

---

## Security Lead

### Role Summary
Advises the team on security requirements and risks and coordinates appropriate security review and mitigation.

### Responsibilities
- Identify security requirements, threats, and relevant controls
- Advise on secure design and review security-sensitive changes
- Coordinate security testing or specialist review as needed
- Track mitigations and escalate security incidents through the established security process

### Goals
- Reduce security risk while enabling delivery
- Make security requirements and residual risks visible and actionable

### Interactions with Existing Roles
- Works with Developers and Technical Leads to incorporate secure design and resolve findings
- Partners with the Product Manager to clarify security requirements and with the Project Manager to track risks and dependencies
- Coordinates with QA/Testing on security test coverage and with Release Managers on release controls
- Escalates incidents through the security incident runbook and informs relevant Stakeholders through approved channels

### Typical Communication
- Security requirements, review findings, risk register updates, and incident communications

---

## Data / Analytics Lead

### Role Summary
Defines how product outcomes will be measured and helps the team use reliable data to evaluate impact.

### Responsibilities
- Translate success metrics into measurement plans and data requirements
- Define event instrumentation and data-quality expectations
- Analyze results and communicate limitations and findings
- Support privacy-conscious collection and appropriate handling of data

### Goals
- Provide trustworthy evidence of product impact
- Help teams learn and make informed product decisions

### Interactions with Existing Roles
- Partners with the Product Manager to define success measures and interpret results
- Works with Developers and Technical Leads on instrumentation and data pipelines
- Coordinates with QA/Testing to validate analytics events and data quality
- Shares measurement dependencies with the Project Manager for planning and communicates insights to Stakeholders

### Typical Communication
- Metric definitions, instrumentation specifications, dashboards, and analysis summaries

---

## Customer / Support Representative

### Role Summary
Brings customer-facing and operational support perspectives into delivery and helps prepare support teams for changes.

### Responsibilities
- Share recurring customer questions, feedback, and operational pain points
- Contribute support scenarios and customer-impact considerations to acceptance discussions
- Prepare support materials and communicate known issues or changes
- Route post-release feedback and incidents to the appropriate owners

### Goals
- Help deliver changes that address customer needs and can be supported effectively
- Enable clear, timely customer support after release

### Interactions with Existing Roles
- Shares customer evidence with the Product Manager to inform priorities and with UX Designers to inform research and usability
- Works with the Project Manager to surface support dependencies and readiness tasks
- Collaborates with Developers, QA/Testing, and Release Managers on support scenarios, known issues, and post-deployment verification
- Provides Stakeholders with customer-impact updates through agreed communication channels

### Typical Communication
- Support readiness reviews, knowledge-base materials, customer feedback summaries, and incident updates

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Assign only the roles needed for a project; if one person holds multiple roles, make ownership and decision boundaries explicit.
