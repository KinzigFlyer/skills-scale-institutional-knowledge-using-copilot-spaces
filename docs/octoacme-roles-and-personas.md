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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, test execution, and acceptance validation. They collaborate with developers and product managers to ensure features meet acceptance criteria and quality standards before release.

### Responsibilities
- Define test strategy and quality acceptance criteria
- Design and execute unit, integration, and end-to-end tests
- Perform manual QA validation against acceptance criteria
- Identify and document defects with reproduction steps
- Coordinate security and performance testing
- Maintain test coverage metrics and reporting

### Goals
- Ensure high-quality releases with minimal defects
- Reduce production incidents through thorough validation
- Enable fast, confident deployments

### Typical Communication
- Sprint planning and backlog refinement
- Quality metrics in weekly status updates
- Test status in pre-release checklists
- Defect reports and regression analysis

### Interaction with Other Roles
- Works with **Developers** during code review to identify testability concerns and collaborate on test strategy
- Partners with **Product Managers** to clarify acceptance criteria and validate feature completeness
- Coordinates with **Project Managers** on test timelines and blockers
- Collaborates with **Release Manager** on smoke tests and pre-deployment verification
- Engages with **Security Lead** on security testing requirements

---

## Security Lead

### Role Summary
Security Leads own security reviews, threat identification, and incident response coordination. They ensure OctoAcme projects comply with security policies and best practices.

### Responsibilities
- Review code and architecture for security risks
- Conduct threat modeling for critical features
- Coordinate security scanning in CI/CD pipeline
- Respond to and triage security incidents
- Maintain security incident runbooks
- Provide security guidance during planning and design

### Goals
- Minimize security risks and vulnerabilities
- Enable rapid response to incidents with clear procedures
- Build secure-by-default practices across projects

### Typical Communication
- Security reviews in code review process
- Security considerations in risk registers
- Incident response coordination
- Security training and best practice sharing

### Interaction with Other Roles
- Advises **Developers** on secure coding practices and conducts security code reviews
- Consults with **Product Managers** on security implications of new features
- Escalates security risks to **Project Managers** for prioritization and mitigation planning
- Coordinates with **QA/Testing Lead** on security test coverage and penetration testing
- Partners with **Release Manager** on security validation before deployments

---

## Technical Lead/Architect

### Role Summary
Technical Leads and Architects guide technical design decisions, ensure system scalability, and identify architectural risks. They mentor developers and ensure technical excellence across the project.

### Responsibilities
- Define technical architecture and design patterns
- Review technical designs for scalability and maintainability
- Identify and mitigate technical risks and dependencies
- Mentor developers and conduct technical code reviews
- Evaluate technology choices and trade-offs
- Document technical decisions and rationale

### Goals
- Enable sustainable, scalable system design
- Reduce technical debt and future rework
- Build knowledge and capability across the team

### Typical Communication
- Technical design reviews and architecture discussions
- Code review comments on design quality
- Technical risk identification in planning meetings
- Design documentation and decision logs

### Interaction with Other Roles
- Collaborates with **Developers** to review and refine technical designs
- Advises **Product Managers** on technical feasibility and trade-offs
- Works with **Project Managers** to identify and manage technical dependencies and risks
- Consults with **Security Lead** on architectural security considerations
- Engages with **QA/Testing Lead** on testability and performance testing strategies

---

## Release Manager

### Role Summary
Release Managers coordinate deployment activities, manage release schedules, and oversee rollback procedures. They ensure smooth, low-risk deployments to production.

### Responsibilities
- Plan and schedule deployment windows
- Coordinate pre-release verification and smoke tests
- Manage deployment checklists and sign-offs
- Oversee production deployments (automated or manual)
- Execute rollback procedures if needed
- Document release notes and communicate to stakeholders

### Goals
- Execute zero-downtime or minimal-impact deployments
- Reduce deployment-related incidents and unplanned downtime
- Ensure clear communication and traceability for all releases

### Typical Communication
- Release schedule planning with PM and engineering
- Pre-release checklists and readiness confirmation
- Deployment status updates during release window
- Post-deployment verification and incident coordination

### Interaction with Other Roles
- Coordinates with **Developers** on deployment readiness and rollback procedures
- Aligns with **Product Managers** on release timing and communication strategy
- Works with **Project Managers** on release scheduling and stakeholder notifications
- Verifies quality with **QA/Testing Lead** through smoke tests and acceptance validation
- Validates security posture with **Security Lead** before production deployment
- Engages with **Technical Lead** on deployment architecture and technical considerations

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interaction with Other Roles" sections to understand cross-functional collaboration and dependencies.
