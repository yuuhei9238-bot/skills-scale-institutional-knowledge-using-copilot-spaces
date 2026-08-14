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
- **With Technical Lead**: Receive architectural guidance and design reviews; escalate technical risks and complex decisions
- **With QA/Testing Lead**: Collaborate on test strategy and acceptance criteria validation
- **With Project Manager**: Receive work assignments and timeline expectations; report blockers and progress
- **With Product Manager**: Clarify requirements and acceptance criteria; validate solutions meet user needs

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
- **With Product Lead**: Report on backlog priorities and success metrics; escalate strategic trade-offs for decision-making
- **With Project Manager**: Coordinate delivery timelines and resource needs; align on release plans
- **With Developers**: Define acceptance criteria and feature specifications; review implemented solutions
- **With QA/Testing Lead**: Collaborate on quality standards and release readiness validation

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
- **With Product Manager**: Align on priorities and scope; coordinate delivery schedules
- **With Product Lead**: Escalate risks and blockers; provide project status updates
- **With Developers**: Manage work assignments and timeline tracking; facilitate sprint planning
- **With Release Manager**: Coordinate deployment schedules and readiness verification
- **With Scrum Master**: Collaborate on ceremony facilitation and team blockers (in agile environments)

---

## Product Lead

### Role Summary
Product Lead provides strategic direction, owns the product vision across multiple initiatives, and serves as the primary decision-maker for product prioritization and trade-offs. This role is critical for strategic alignment and enabling fast decision-making on roadmap conflicts and major architectural decisions.

### Responsibilities
- Define and communicate product vision and strategy across multiple initiatives
- Make final prioritization decisions on roadmap conflicts
- Approve major product and architectural decisions
- Serve as escalation point for cross-team dependencies and strategic blockers
- Review and validate business metrics and success criteria
- Align product strategy with organizational goals and stakeholder needs

### Goals
- Ensure product strategy delivers maximum customer and business value
- Maintain strategic alignment across multiple concurrent projects
- Enable fast decision-making by being the clear, empowered decision owner
- Reduce escalation times and rework through clear strategic direction

### Typical Communication
- Weekly alignment with Product Manager and engineering leadership
- Monthly stakeholder briefings and executive updates
- Ad-hoc decisions on prioritization conflicts and strategic trade-offs
- Architecture review board participation (when applicable)

### Interactions with Other Roles
- **With Product Manager**: Review metrics and provide strategic guidance; make final prioritization decisions
- **With Project Manager**: Escalation point for business-impacting risks; approval authority on scope trade-offs
- **With Technical Lead**: Collaborate on technical strategy alignment with product roadmap; approve major architectural decisions
- **With Developers**: Provide context on product vision; review key implementation decisions
- **With Stakeholder/Sponsor**: Communicate product strategy and business outcomes; align on priorities

---

## Technical Lead/Architect

### Role Summary
Technical Lead provides architectural guidance, identifies technical risks, and ensures design decisions align with system goals and long-term technical strategy. This role bridges technology and product delivery, ensuring scalability and maintainability of solutions.

### Responsibilities
- Review technical designs for scalability, maintainability, and alignment with system architecture
- Identify and mitigate technical risks; escalate blocking issues
- Guide technology choices and integration decisions
- Mentor developers on technical best practices and design patterns
- Participate in planning to estimate technical effort and identify technical dependencies
- Collaborate with Product Lead on major architectural decisions

### Goals
- Maintain system reliability, scalability, and security
- Reduce technical debt and rework through sound design decisions
- Enable efficient code reviews and faster developer velocity
- Ensure long-term architectural coherence across projects

### Typical Communication
- Design review sessions and architecture decision logs
- Technical risk discussions in planning and retrospectives
- Code review collaboration and mentoring
- Technical dependencies and integration planning meetings

### Interactions with Other Roles
- **With Developers**: Review designs and code; mentor on best practices; help resolve technical blockers
- **With Product Lead**: Collaborate on major architectural decisions; review technical feasibility of strategic initiatives
- **With Project Manager**: Identify technical risks and dependencies during planning; provide technical estimates
- **With QA/Testing Lead**: Define test strategy for complex technical components; validate technical quality gates
- **With Security Officer**: Integrate security requirements into architectural decisions

---

## QA/Testing Lead

### Role Summary
QA/Testing Lead owns quality assurance strategy, test planning, and validation that features meet acceptance criteria and quality standards before release. This role ensures consistent quality gates across the development lifecycle.

### Responsibilities
- Define QA strategy and test approach for projects
- Plan and execute unit, integration, and end-to-end testing
- Validate acceptance criteria are met before sign-off
- Identify, document, and track defects
- Coordinate security and performance testing
- Define and enforce quality standards and Definition of Done

### Goals
- Ensure consistent quality before release
- Reduce production defects and rework
- Build confidence in release readiness
- Enable rapid iteration through efficient test automation

### Typical Communication
- QA planning in sprint planning and kickoff meetings
- Defect reports and test results in sprints
- Sign-off on acceptance criteria completion
- Release readiness verification and go/no-go recommendations

### Interactions with Other Roles
- **With Developers**: Collaborate on test strategy; define testable acceptance criteria; review test coverage
- **With Product Manager**: Validate feature acceptance criteria; coordinate on quality standards
- **With Technical Lead**: Plan testing approach for complex technical components; coordinate performance testing
- **With Release Manager**: Verify release readiness; coordinate final testing and sign-off
- **With Project Manager**: Report quality metrics and test progress; escalate quality risks

---

## Release Manager

### Role Summary
Release Manager coordinates deployment activities, manages release schedules, and ensures pre-release and post-release requirements are met. This role is central to managing deployment risk and maintaining release cadence.

### Responsibilities
- Coordinate and schedule deployment activities
- Ensure pre-release requirements are met (testing, approvals, documentation)
- Execute deployment to production (or oversee automated pipelines)
- Manage rollback procedures if needed
- Verify post-deployment health and performance
- Communicate release status to stakeholders and support teams
- Maintain release notes and deployment documentation

### Goals
- Reduce deployment risk and enable confident releases
- Maintain consistent, predictable release schedules
- Minimize deployment-related incidents and rollbacks
- Enable quick communication and support for deployed features

### Typical Communication
- Pre-release readiness reviews
- Deployment window coordination and notifications
- Post-deployment verification and stakeholder announcements
- Incident communication and rollback coordination

### Interactions with Other Roles
- **With Project Manager**: Coordinate release schedules and readiness verification
- **With QA/Testing Lead**: Verify testing completion and release readiness sign-off
- **With Developers**: Coordinate code freeze and deployment instructions; support incident response
- **With Security Officer**: Ensure security sign-off before release; coordinate security patches
- **With Stakeholder/Sponsor**: Communicate release timing and business impact

---

## Stakeholder/Sponsor

### Role Summary
Stakeholder/Sponsor is a business owner or executive sponsor who provides approval, resources, and escalation authority. This role ensures projects align with business goals and removes organizational blockers.

### Responsibilities
- Provide business approval and strategic direction for projects
- Allocate resources and support (budget, team capacity, cross-functional help)
- Serve as escalation point for business-impacting blockers
- Review and validate business success metrics
- Remove organizational and political blockers
- Communicate project status to broader business leadership

### Goals
- Ensure projects deliver business value and ROI
- Provide resources and support to enable team success
- Remove obstacles preventing project delivery
- Maintain alignment between project outcomes and business strategy

### Typical Communication
- Project initiation and approval meetings
- Monthly stakeholder updates and business reviews
- Escalation and decision-making on strategic trade-offs
- Post-release business impact reviews

### Interactions with Other Roles
- **With Product Lead**: Strategic alignment on priorities and business outcomes
- **With Project Manager**: Escalation point for blocker resolution; resource allocation decisions
- **With Product Manager**: Review business metrics and success criteria
- **With Release Manager**: Notification of release timing and business impact

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Master (in Scrum teams) or Agile Coach facilitates ceremonies, removes blockers, and guides the team through iterative delivery. This role ensures the team adheres to processes and continuously improves.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Remove team blockers and impediments to progress
- Coach team on Agile practices and continuous improvement
- Maintain sprint boards and tracking artifacts
- Shield the team from external distractions during sprints
- Guide retrospective action items and process improvements

### Goals
- Enable team velocity and consistent delivery cadence
- Foster psychological safety and continuous improvement culture
- Remove organizational and process barriers to delivery
- Improve team collaboration and communication

### Typical Communication
- Daily standup facilitation
- Sprint planning and retrospective meetings
- One-on-one coaching with team members
- Escalation of blockers to Project Manager or Product Lead

### Interactions with Other Roles
- **With Project Manager**: Escalate team blockers; coordinate resource needs
- **With Developers**: Remove blockers; facilitate collaboration; coach on Agile practices
- **With Product Manager**: Protect team focus; facilitate backlog refinement
- **With Team Members (All Roles)**: Facilitate ceremonies and coach on process adherence

---

## Security/Compliance Officer

### Role Summary
Security/Compliance Officer owns security reviews, incident response protocols, and compliance requirements. This role ensures products meet security and regulatory standards before release and throughout operation.

### Responsibilities
- Review security requirements and threat models
- Conduct or coordinate security assessments and code reviews
- Ensure compliance with regulatory requirements (GDPR, SOC 2, etc.)
- Define and enforce security policies and controls
- Respond to security incidents and manage remediation
- Participate in incident retrospectives and post-mortems

### Goals
- Ensure products meet security and compliance standards before release
- Reduce security vulnerabilities and compliance violations
- Enable fast incident response and remediation
- Maintain organizational security posture and regulatory standing

### Typical Communication
- Security requirements definition in planning
- Security review gates in development and release processes
- Incident response and escalation
- Compliance audit and certification support

### Interactions with Other Roles
- **With Technical Lead**: Collaborate on architectural security decisions; review design for security risks
- **With Developers**: Define secure coding practices; review code for vulnerabilities
- **With Product Manager**: Advise on security and privacy features; coordinate compliance requirements
- **With Release Manager**: Security sign-off gate before release; coordinate security patches
- **With Project Manager**: Escalate security risks; coordinate incident response

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When managing multi-functional projects, ensure all relevant personas are involved in appropriate decision gates and ceremonies.
- Refer to the "Interactions with Other Roles" sections to understand cross-functional collaboration and escalation paths.
