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
- **With QA/Testing Lead:** Collaborate on test strategy and accept feedback on quality issues during PR review
- **With Technical Architect:** Implement technical designs and raise concerns about architectural decisions
- **With Product Managers:** Clarify acceptance criteria and discuss technical trade-offs
- **With Project Managers:** Provide time estimates and flag blockers in standups

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
- **With Stakeholders/Sponsors:** Align on business priorities and secure approval for roadmap items
- **With Project Managers:** Coordinate timelines and dependencies across work streams
- **With Developers:** Define acceptance criteria and validate feature completeness
- **With QA/Testing Lead:** Define quality expectations and acceptance criteria interpretation

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
- **With Stakeholders/Sponsors:** Provide status updates and escalate blockers
- **With Developers:** Track progress, manage capacity, and facilitate standups
- **With Release Manager:** Coordinate deployment schedules and release readiness
- **With Technical Architect:** Identify and manage technical dependencies and risks

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality assurance strategy and ensure features meet acceptance criteria and quality standards before release. They collaborate with developers and product teams to define test plans and validate user-facing functionality.

### Responsibilities
- Define test strategy and acceptance criteria interpretation
- Create and maintain test plans (unit, integration, E2E, manual QA)
- Coordinate automated testing and CI integration
- Validate features against acceptance criteria before merge
- Report on quality metrics and test coverage
- Participate in release readiness reviews
- Identify and track quality risks

### Goals
- Ensure high-quality releases with minimal production defects
- Enable fast feedback loops with developers
- Maintain high test coverage and observability
- Reduce defect escape rates to production

### Typical Communication
- Sprint planning and review meetings
- Quality metrics in weekly status updates
- Test plan documentation and bug reports
- Release readiness sign-off
- Code review participation on test-related PRs

### Interactions with Other Roles
- **With Developers:** Collaborate on test strategy, review PRs for testability, and discuss failing tests
- **With Product Managers:** Clarify acceptance criteria and validate feature completeness
- **With Release Manager:** Conduct pre-release quality validation and sign off on deployment readiness
- **With Project Managers:** Report on quality metrics and flag quality-related risks

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, secure resources, and give executive visibility to projects. They make key approval decisions and ensure alignment with organizational priorities.

### Responsibilities
- Define business requirements and success metrics
- Approve project initiation and resource allocation
- Attend milestone reviews and stakeholder updates
- Escalate blockers and resource conflicts
- Communicate outcomes to executive leadership
- Provide feedback on releases and impact
- Remove organizational barriers to project success

### Goals
- Ensure project delivers business value
- Maintain organizational alignment and prioritization
- Enable timely decision-making and resource access
- Maximize impact on strategic objectives

### Typical Communication
- Monthly stakeholder updates and milestone reviews
- Ad-hoc escalations and decision requests
- Release announcements and impact reports
- Executive briefings on project status and outcomes

### Interactions with Other Roles
- **With Project Managers:** Receive status updates, approve decisions, and provide escalation support
- **With Product Managers:** Align on business priorities, goals, and success metrics
- **With Release Manager:** Approve release timing and communicate outcomes to business
- **With Technical Architect:** Understand technical dependencies that impact delivery timelines

---

## Technical Architect

### Role Summary
Technical Architects define the technical direction, evaluate system design trade-offs, and ensure solutions are scalable, maintainable, and aligned with organizational standards. They guide technical decisions across projects.

### Responsibilities
- Review and guide technical design decisions
- Evaluate architectural trade-offs and dependencies
- Ensure alignment with platform standards and best practices
- Identify technical risks and propose mitigations
- Participate in design reviews and technical planning
- Mentor developers on technical excellence
- Assess system scalability and performance implications

### Goals
- Enable sustainable, scalable technical solutions
- Reduce rework through strong upfront design
- Share knowledge and build technical consistency
- Minimize technical debt and maintenance burden

### Typical Communication
- Technical design reviews and architecture docs
- Planning sessions for complex features
- Risk registers and dependency mapping
- Architecture decision records (ADRs)

### Interactions with Other Roles
- **With Developers:** Guide design decisions, review technical implementations, and provide mentoring
- **With Project Managers:** Communicate technical risks, dependencies, and timeline impacts
- **With QA/Testing Lead:** Define testability requirements and performance benchmarks
- **With Product Managers:** Evaluate feasibility of features and propose technical trade-offs

---

## Release Manager

### Role Summary
Release Managers coordinate deployment activities, ensure release readiness, and manage go-live execution. They own the release checklist, communication, and rollback procedures.

### Responsibilities
- Coordinate release planning and scheduling
- Verify pre-release requirements are met
- Manage deployment checklists and staging validation
- Coordinate rollback if issues arise
- Manage release notes and stakeholder announcements
- Track post-deployment verification and incidents
- Document release metrics and lessons learned

### Goals
- Execute smooth, low-risk releases
- Minimize deployment incidents and unplanned work
- Ensure clear communication to all stakeholders
- Maintain service reliability and user experience

### Typical Communication
- Release planning meetings and deployment windows
- Stakeholder announcements and release notes
- Post-deployment incident reports
- Release readiness signoffs
- Deployment day coordination and status updates

### Interactions with Other Roles
- **With QA/Testing Lead:** Verify acceptance criteria met and conduct pre-release validation
- **With Developers:** Coordinate final code freeze and address deployment issues
- **With Project Managers:** Report deployment status and manage stakeholder communication
- **With Stakeholders/Sponsors:** Communicate release impact and obtain business approval for deployment
- **With Security/Compliance Lead:** Ensure security requirements and compliance checks are met

---

## Security/Compliance Lead

### Role Summary
Security and Compliance Leads ensure projects meet security standards, implement required scanning, and manage security incidents. They advocate for secure practices and compliance requirements.

### Responsibilities
- Define security requirements and compliance needs
- Configure and monitor security scanning in CI
- Review security findings and recommend fixes
- Manage security incident response and escalation
- Ensure compliance with organizational policies
- Participate in risk assessments
- Conduct security reviews during design and pre-release phases

### Goals
- Prevent security vulnerabilities in production
- Enable fast, secure deployments
- Maintain compliance and organizational trust
- Reduce security-related incidents and rework

### Typical Communication
- Security requirements in planning phase
- CI/CD scanning configuration and reviews
- Incident response escalations
- Compliance audit findings
- Security design review meetings

### Interactions with Other Roles
- **With Developers:** Review code for security issues, provide guidance on secure practices, and support remediation
- **With Technical Architect:** Review system architecture for security implications and compliance considerations
- **With Project Managers:** Communicate security risks and ensure security activities are planned
- **With Release Manager:** Verify security requirements are met before deployment and coordinate security incident response
- **With QA/Testing Lead:** Define security test scenarios and validate security controls

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The "Interactions with Other Roles" section clarifies how each persona collaborates across the project lifecycle and helps teams understand cross-functional dependencies.
