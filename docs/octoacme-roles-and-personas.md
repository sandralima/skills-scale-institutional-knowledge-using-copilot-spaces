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
QA/Testing Leads design and execute testing strategies to ensure product quality meets acceptance criteria and standards. They own the testing approach, validate release readiness, and manage quality metrics.

### Responsibilities
- Define testing strategy and test plans for each release
- Design and maintain automated test suites
- Execute manual QA and acceptance testing
- Identify and triage defects
- Validate release readiness via smoke tests and sign-off
- Track and report quality metrics

### Goals
- Catch defects early and reduce production issues
- Ensure user-facing features meet acceptance criteria
- Maintain high test coverage and observability

### Typical Communication
- Sprint planning to discuss test strategy
- Daily standups for blocker escalation
- Release coordination with PM and deployment teams

### Interaction with Existing Roles
- **Developers**: Partner on test automation design and review test coverage during code reviews
- **Product Managers**: Validate acceptance criteria and ensure test plans align with feature expectations
- **Project Managers**: Report quality metrics and flag release blockers or test delays

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters or Agile Coaches facilitate team processes, remove impediments, and coach teams on continuous improvement. They enable predictable, sustainable delivery.

### Responsibilities
- Facilitate sprint planning, standups, and retrospectives
- Identify and help resolve team blockers
- Coach team on Agile practices and continuous improvement
- Maintain team velocity and health metrics
- Support process improvements from retrospective actions

### Goals
- Enable fast, predictable delivery
- Build a high-performing, self-organizing team
- Sustain psychological safety and blameless culture

### Typical Communication
- Daily standups to surface and triage blockers
- Retrospectives to capture and act on learnings
- Weekly metrics reviews with PM/Project Lead

### Interaction with Existing Roles
- **Project Managers**: Work together to maintain schedules and escalation paths; Scrum Master focuses on team health, PM focuses on scope/timeline
- **Developers**: Remove impediments and coach on Agile best practices and team dynamics
- **Product Managers**: Support backlog refinement meetings and ensure prioritization is clear to the team

---

## Security Engineer

### Role Summary
Security Engineers ensure that product design, implementation, and deployment follow security standards and best practices. They own the security posture of the project.

### Responsibilities
- Review architectural and design decisions for security implications
- Conduct security code reviews and threat modeling
- Implement and maintain security scanning in CI/CD
- Define security testing and penetration test scope
- Manage and communicate security incidents
- Ensure compliance with data protection and regulatory requirements

### Goals
- Prevent security breaches and protect customer data
- Embed security into development from day one
- Reduce time-to-remediation for vulnerabilities

### Typical Communication
- Design reviews during planning phase
- Security incident response and escalation
- Release readiness reviews
- Quarterly security and compliance updates

### Interaction with Existing Roles
- **Developers**: Review code for security vulnerabilities and mentor on secure coding practices
- **Technical Architects**: Partner on architectural security decisions and threat modeling
- **Project Managers**: Escalate critical security issues and coordinate incident response; include security sign-off in release gates
- **QA/Testing Lead**: Define security testing scenarios and penetration test scope

---

## Technical Architect

### Role Summary
Technical Architects define the overall system design, technology choices, and technical strategy. They ensure scalability, maintainability, and alignment with organizational technical direction.

### Responsibilities
- Define system architecture and design patterns
- Evaluate and recommend technology and tools
- Review technical designs and implementation approaches
- Identify scalability, performance, and maintainability risks
- Guide technical trade-offs and refactoring priorities
- Ensure consistency across systems and services

### Goals
- Build scalable, maintainable, and resilient systems
- Minimize technical debt and rework
- Align projects with organizational technical strategy

### Typical Communication
- Design reviews during planning and implementation
- Technical decision logs and ADRs (Architecture Decision Records)
- Architecture reviews at key milestones
- Guidance on cross-cutting technical concerns

### Interaction with Existing Roles
- **Developers**: Guide on design patterns and technical decisions; review implementation approaches
- **Security Engineer**: Partner on architectural security and compliance requirements
- **Project Managers**: Advise on technical risks and trade-offs that impact timeline or scope
- **Product Managers**: Explain technical constraints and opportunities that influence product feasibility

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Project Sponsors provide business context, secure resources, and make go/no-go decisions. They are the voice of business priorities and hold ultimate accountability for project outcomes.

### Responsibilities
- Define business objectives and success metrics
- Approve project charter and scope
- Allocate budget and resources
- Make trade-off and priority decisions
- Provide executive visibility and remove organizational blockers
- Serve as escalation point for critical issues

### Goals
- Ensure projects deliver measurable business value
- Align project outcomes with organizational strategy
- Enable timely decision-making and resource allocation

### Typical Communication
- Initiation and kickoff meetings
- Monthly or milestone-based status updates
- Executive summaries and business metrics reviews
- Escalation and decision forums

### Interaction with Existing Roles
- **Project Managers**: Receive regular status updates, escalations, and decision requests; approve scope changes
- **Product Managers**: Align on business objectives, success metrics, and prioritization
- **Developers**: Occasional interaction via project kickoff and demos; understand business context for the work

---

## Support / Operations Lead

### Role Summary
Support and Operations teams manage production environments, monitor system health, and support end users. They are the bridge between development and customers.

### Responsibilities
- Monitor production systems and alert on issues
- Triage and escalate incidents and support requests
- Provide post-release support and troubleshooting
- Gather customer feedback and usage insights
- Document runbooks and operational procedures
- Communicate with customers during incidents

### Goals
- Maintain high system availability and performance
- Rapidly detect and resolve production issues
- Deliver excellent customer support and experience

### Typical Communication
- Pre-release coordination to prepare runbooks and support docs
- Incident response and post-incident retrospectives
- Weekly operational metrics and health reviews
- Customer feedback loops to product and engineering teams

### Interaction with Existing Roles
- **Developers**: Coordinate on troubleshooting production issues; provide customer feedback on usability and bugs
- **Project Managers**: Report operational metrics and incidents that impact release success or require escalation
- **Product Managers**: Share customer insights and feature requests gathered from support interactions
- **QA/Testing Lead**: Participate in smoke testing before release to validate deployment readiness

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction sections to understand cross-functional collaboration and communication patterns.
