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

## UX / Design Lead

### Role Summary
The UX/Design Lead owns the user experience and visual design of product features. They bridge customer needs and technical implementation by producing design artifacts that guide development.

### Responsibilities
- Conduct user research and translate insights into design requirements
- Produce wireframes, prototypes, and high-fidelity design specs
- Collaborate with Product Managers to refine acceptance criteria from a usability perspective
- Review implementations for design fidelity before QA sign-off
- Contribute to retrospectives with UX-focused learnings

### Goals
- Deliver intuitive, accessible, and consistent user experiences
- Reduce design-to-development rework through early collaboration
- Champion user needs in trade-off decisions

### Typical Communication
- Sprint planning and review sessions
- Design critique sessions with developers
- Usability testing summaries shared with PdM and stakeholders

### Interacts With
- Product Manager (PdM): aligns on requirements, success metrics, and acceptance criteria
- Developers: delivers design specs and reviews implementations for fidelity
- QA/Testing: coordinates design acceptance before sign-off

---

## Tech Lead / Engineering Lead

### Role Summary
The Tech Lead provides technical direction, ensures architectural integrity, and supports the delivery team in making sound engineering decisions.

### Responsibilities
- Define and communicate technical standards and architecture decisions
- Lead design reviews for complex features or cross-service integrations
- Approve pull requests with significant architectural impact
- Identify and escalate technical risks to the Project Manager
- Support developers through mentoring and pair programming

### Goals
- Maintain a scalable, maintainable, and observable codebase
- Reduce technical debt while enabling fast delivery
- Ensure alignment between technical decisions and product goals

### Typical Communication
- Technical design docs and Architecture Decision Records (ADRs)
- Code review comments and PR approvals
- Engineering sync with PM on blockers and risks

### Interacts With
- Developers: mentors, reviews code, and sets technical standards
- Project Manager (PM): escalates technical risks and dependencies
- Product Manager (PdM): advises on technical feasibility and trade-offs

---

## Security / Compliance Officer

### Role Summary
The Security/Compliance Officer ensures that all deliverables comply with security policies and regulatory requirements, and leads the team's response to security incidents.

### Responsibilities
- Review architecture and code changes for security vulnerabilities
- Define and maintain the security incident runbook
- Provide security sign-off as part of the pre-release checklist
- Track compliance requirements and ensure they are reflected in acceptance criteria
- Participate in post-incident retrospectives to drive security improvements

### Goals
- Protect customer data and system integrity across all releases
- Embed security practices into the development lifecycle (shift-left)
- Ensure regulatory compliance without blocking delivery velocity

### Typical Communication
- Security review checkpoints in the PR and release process
- Incident response coordination with on-call and Tech Lead
- Compliance status updates to PM and stakeholders

### Interacts With
- Tech Lead: collaborates on architecture reviews and vulnerability remediation
- Project Manager (PM): flags security risks and provides pre-release sign-off
- DevOps / Infrastructure Engineer: coordinates secure pipeline and infrastructure configurations

---

## DevOps / Infrastructure Engineer

### Role Summary
The DevOps/Infrastructure Engineer owns the reliability and automation of the delivery pipeline, environments, and production infrastructure.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Manage environment configurations (dev, staging, production)
- Own rollback procedures and deployment runbooks
- Monitor system health and respond to infrastructure incidents
- Collaborate with developers on testability and observability instrumentation

### Goals
- Maximize deployment frequency and reliability
- Minimize mean time to recovery (MTTR) for incidents
- Ensure infrastructure supports scalability and security requirements

### Typical Communication
- Deployment coordination with PM and Tech Lead during release windows
- On-call handoff notes and incident reports
- CI/CD and monitoring documentation in the repo

### Interacts With
- Developers: supports build tooling, environment setup, and observability
- Tech Lead: aligns on infrastructure decisions and architecture
- Security/Compliance Officer: ensures pipeline and infrastructure meet security standards
- Project Manager (PM): coordinates deployment windows and communicates release status

---

## Customer Success / Support Representative

### Role Summary
The Customer Success/Support Representative brings the voice of the customer into the product lifecycle, ensuring that releases are customer-ready and that feedback loops are closed.

### Responsibilities
- Surface customer feedback and bug reports to PdM and PM
- Validate that acceptance criteria meet real customer needs
- Coordinate support readiness for upcoming releases (documentation, FAQs, training)
- Participate in release announcements and stakeholder communications
- Contribute customer impact context to risk and retrospective discussions

### Goals
- Ensure customers experience smooth, well-communicated releases
- Reduce support ticket volume through proactive readiness and clear release notes
- Close the feedback loop between customers and the product team

### Typical Communication
- Release readiness reviews with PM and PdM
- Customer feedback summaries shared in retrospectives
- Support documentation and FAQs updated before each release

### Interacts With
- Product Manager (PdM): provides customer feedback to inform backlog prioritization
- Project Manager (PM): coordinates release communications and support readiness
- Stakeholders: contributes to external announcements and customer-facing updates

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
