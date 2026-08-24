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
- **Technical Lead/Architect**: Receives guidance on technical design and architecture decisions; participates in design reviews
- **QA/Testing Lead**: Collaborates on testability requirements and provides code for validation
- **Project Manager**: Receives task assignments and provides status updates
- **Product Manager**: Clarifies acceptance criteria and feature requirements

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
- **Stakeholder/Sponsor**: Receives business context and approval for major decisions
- **Project Manager**: Collaborates on roadmap planning and release coordination
- **Developers**: Defines acceptance criteria and validates solutions
- **QA/Testing Lead**: Aligns on quality expectations and acceptance criteria

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
- **Scrum Master/Agile Coach**: Coordinates sprint planning and ceremony facilitation
- **Stakeholder/Sponsor**: Provides executive updates and escalates business-critical issues
- **Release Manager**: Coordinates release timelines and deployment schedules
- **All team members**: Facilitates communication and removes impediments

---

## QA/Testing Lead

### Role Summary
QA and Testing Leads own quality assurance strategy, test planning, and acceptance validation. They ensure deliverables meet acceptance criteria and quality standards before release.

### Responsibilities
- Define test strategy and QA approach for each project
- Create and maintain test plans and test cases
- Validate acceptance criteria and feature functionality
- Execute manual QA testing when needed
- Report quality metrics and defect trends
- Coordinate with developers on testability and reproducibility

### Goals
- Prevent defects from reaching production
- Build confidence in release quality
- Enable fast feedback loops on quality

### Typical Communication
- Participation in sprint planning and kickoff
- Daily standup updates on test progress
- Quality reports and defect metrics

### Interactions with Other Roles
- **Developers**: Reviews code for testability; validates implementations against acceptance criteria
- **Product Manager**: Aligns on quality expectations and acceptance criteria
- **Release Manager**: Provides quality metrics and smoke test results for release readiness
- **Project Manager**: Reports on testing progress and quality risks

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, approve major decisions, allocate resources, and serve as the escalation authority for business-impacting issues.

### Responsibilities
- Provide business requirements and context
- Approve project charter and major scope changes
- Allocate budget and resources
- Escalate business-critical blockers
- Review and approve releases
- Communicate outcomes to broader organization

### Goals
- Ensure project aligns with business objectives
- Enable quick decision-making on trade-offs
- Maintain executive visibility into project health

### Typical Communication
- Monthly stakeholder briefings
- Milestone reviews and approvals
- Ad-hoc escalation for critical decisions

### Interactions with Other Roles
- **Project Manager**: Receives escalations and provides strategic guidance
- **Product Manager**: Aligns on priorities and business outcomes
- **Release Manager**: Reviews and approves releases
- **Security/Compliance Officer**: Ensures compliance and security sign-off

---

## Technical Lead/Architect

### Role Summary
Technical Leads and Architects guide technical direction, design decisions, and ensure systems are built for scalability, maintainability, and reliability.

### Responsibilities
- Lead technical design and architecture reviews
- Identify technical risks and propose mitigations
- Mentor developers and support skill development
- Ensure adherence to coding standards and best practices
- Collaborate on technology choices and trade-offs
- Champion refactoring and technical debt management

### Goals
- Build systems that are maintainable and scalable
- Reduce technical risk and technical debt
- Foster engineering excellence and continuous learning

### Typical Communication
- Technical design reviews with development team
- Architecture decision records (ADRs)
- Code review feedback and mentoring

### Interactions with Other Roles
- **Developers**: Provides technical guidance and mentoring; reviews architecture and design decisions
- **QA/Testing Lead**: Collaborates on testability and quality strategies
- **Project Manager**: Identifies and escalates technical risks
- **Release Manager**: Ensures architectural readiness for deployments

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate agile ceremonies, remove impediments, and drive continuous improvement of processes and team dynamics.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Help remove blockers and impediments
- Coach team on agile practices and iterative delivery
- Maintain sprint health and predictability
- Drive action items from retrospectives
- Track and improve team velocity and predictability

### Goals
- Enable self-organizing teams
- Improve predictability and cycle time
- Build a culture of continuous improvement

### Typical Communication
- Facilitation of all sprint ceremonies
- Blocker escalation and resolution
- Retrospective notes and action tracking

### Interactions with Other Roles
- **Project Manager**: Coordinates sprint planning and facilitates team ceremonies
- **Developers**: Removes impediments and coaches on agile practices
- **All team members**: Facilitates retrospectives and drives process improvements
- **Product Manager**: Ensures backlog is ready and prioritized for sprints

---

## Release Manager

### Role Summary
Release Managers coordinate the release process, manage deployment schedules, and own the rollback and incident response procedures to ensure smooth, low-risk releases.

### Responsibilities
- Coordinate release planning and timelines
- Manage deployment schedules and communication
- Prepare release notes and deployment checklists
- Oversee smoke testing and post-deploy verification
- Own rollback procedures and incident response
- Track deployment metrics and health

### Goals
- Execute low-risk, predictable releases
- Minimize downtime and customer impact
- Enable rapid recovery from incidents

### Typical Communication
- Release coordination meetings and deployment windows
- Pre-release readiness reviews
- Post-incident retrospectives and follow-up

### Interactions with Other Roles
- **Project Manager**: Coordinates release timelines and milestones
- **QA/Testing Lead**: Reviews quality metrics and runs smoke tests
- **Developers**: Provides deployment support and troubleshooting
- **Stakeholder/Sponsor**: Reports release status and seeks approval
- **Technical Lead/Architect**: Coordinates technical deployment concerns

---

## Security/Compliance Officer

### Role Summary
Security and Compliance Officers ensure that projects meet security and regulatory requirements, coordinate security reviews, and lead incident response for security events.

### Responsibilities
- Define security requirements and acceptance criteria
- Review and approve security scanning and testing
- Conduct or coordinate security code reviews
- Lead security incident response and investigation
- Ensure compliance with data protection and regulatory requirements
- Report security metrics and audit findings

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure regulatory and compliance adherence
- Enable rapid, coordinated response to security incidents

### Typical Communication
- Security review participation during planning and testing
- Incident response coordination
- Regular security and compliance reporting

### Interactions with Other Roles
- **Developers**: Reviews code for security vulnerabilities; defines secure coding standards
- **QA/Testing Lead**: Collaborates on security testing and penetration testing
- **Release Manager**: Approves deployments from a security perspective; leads incident response
- **Stakeholder/Sponsor**: Reports on security posture and compliance status
- **Project Manager**: Escalates security risks and compliance issues

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interactions with Other Roles" sections to understand cross-functional dependencies and communication patterns.
