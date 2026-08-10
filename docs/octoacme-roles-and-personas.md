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

### Interaction with Other Roles
- **Technical Lead/Architect**: Receive technical direction and design guidance; participate in design reviews
- **QA/Testing Lead**: Collaborate on defining acceptance criteria and test cases; support QA during testing cycles
- **Product Managers**: Clarify requirements and acceptance criteria; discuss implementation trade-offs
- **Project Managers**: Provide estimates and progress updates; report blockers and dependencies

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

### Interaction with Other Roles
- **Developers**: Define acceptance criteria and success metrics; review implementation solutions
- **QA/Testing Lead**: Align on quality standards and success metrics; review test coverage
- **Project Managers**: Align on timeline and milestone prioritization
- **Stakeholders/Sponsors**: Present roadmap and results; gather business requirements

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

### Interaction with Other Roles
- **Technical Lead/Architect**: Collaborate on risk assessment and timeline estimation
- **Release Manager**: Coordinate release schedules and deployment windows
- **Developers**: Track progress and identify blockers; manage dependencies
- **QA/Testing Lead**: Coordinate quality gates and testing schedules
- **Stakeholders/Sponsors**: Provide regular status updates and escalate blockers

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality assurance strategy and test execution for the project. They collaborate with product and engineering to define acceptance criteria and ensure features meet quality standards before release.

### Responsibilities
- Define test strategy and test plan aligned with project scope
- Create and maintain test cases and automated test suites
- Conduct acceptance testing against acceptance criteria
- Identify and triage defects, prioritize rework
- Coordinate manual and automated testing efforts
- Validate release readiness before production deployment

### Goals
- Ensure features meet acceptance criteria and quality standards
- Reduce production incidents through thorough testing
- Identify quality risks early and enable faster delivery

### Typical Communication
- Daily standups and sprint planning
- Test plan reviews with product and engineering
- Defect reports and quality dashboards
- Pre-release sign-off communications

### Interaction with Other Roles
- **Developers**: Collaborate on test case design; report and prioritize defects for rework
- **Product Managers**: Validate acceptance criteria and quality thresholds; align on success metrics
- **Technical Lead/Architect**: Review technical design for testability; escalate technical quality risks
- **Release Manager**: Provide release readiness sign-off; coordinate smoke tests before production deployment
- **Project Managers**: Report quality status and schedule impact of defects

---

## Technical Lead/Architect

### Role Summary
Technical Leads provide technical direction, oversee architecture decisions, and guide the engineering team on implementation approaches. They balance innovation with maintainability and reduce technical risk.

### Responsibilities
- Review and approve technical design and architecture decisions
- Identify and escalate technical risks and dependencies
- Mentor developers and conduct code reviews
- Assess scalability, performance, and security implications
- Recommend technology choices and design patterns
- Participate in planning to estimate technical effort

### Goals
- Deliver maintainable, scalable, and secure solutions
- Reduce technical debt and rework
- Accelerate team velocity through clear technical guidance

### Typical Communication
- Technical design review meetings
- Architecture documentation and ADRs (Architecture Decision Records)
- Code review feedback and mentoring
- Technical risk escalations

### Interaction with Other Roles
- **Developers**: Provide technical guidance; mentor on best practices; review code and architecture
- **QA/Testing Lead**: Advise on testability and quality assurance approaches; escalate technical quality risks
- **Project Managers**: Communicate technical risks and dependencies; participate in effort estimation
- **Product Managers**: Discuss technical feasibility of features and trade-offs
- **Release Manager**: Advise on deployment considerations and potential technical risks during releases

---

## Release Manager

### Role Summary
Release Managers coordinate the delivery of features to production. They own the release schedule, manage deployment procedures, and ensure smooth rollouts with minimal risk and downtime.

### Responsibilities
- Coordinate release planning and scheduling with stakeholders
- Prepare deployment checklists and runbooks
- Manage the deployment process (staging and production)
- Execute rollback procedures if needed
- Document release notes and communicate releases to stakeholders
- Track post-deployment metrics and validate release success

### Goals
- Deliver releases on schedule with zero unplanned downtime
- Minimize deployment risk through process discipline
- Maintain clear communication with all stakeholders during releases

### Typical Communication
- Release planning meetings and deployment windows
- Deployment checklists and runbooks
- Release notes and stakeholder announcements
- Post-deployment verification reports

### Interaction with Other Roles
- **QA/Testing Lead**: Coordinate smoke tests and release readiness validation
- **Developers**: Coordinate deployment support and hotfix procedures
- **Technical Lead/Architect**: Align on deployment strategy and technical risks; coordinate rollback procedures
- **Project Managers**: Coordinate release scheduling and stakeholder communication
- **Stakeholders/Sponsors**: Announce releases and communicate deployment status

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, strategic direction, and approval authority for projects. They ensure alignment between project outcomes and business objectives, and remove organizational obstacles to project success.

### Responsibilities
- Define business objectives and success criteria
- Provide approval and governance for major decisions
- Allocate resources and remove organizational blockers
- Communicate project status to senior leadership
- Validate that project outcomes meet business needs

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment between project delivery and organizational strategy
- Enable teams to execute with clear authority and support

### Typical Communication
- Monthly stakeholder reviews and status briefings
- Approval gates for major scope or timeline changes
- Escalation resolution for organizational blockers
- Post-project validation of business outcomes

### Interaction with Other Roles
- **Project Managers**: Receive escalations and provide decisions on scope/resource trade-offs
- **Product Managers**: Align on business objectives and priorities; approve roadmap direction
- **Release Manager**: Review release announcements and business impact communications
- **All teams**: Provide business context and strategic direction; celebrate delivery milestones

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters/Agile Coaches facilitate team ceremonies, remove impediments, and coach the team on agile practices. They serve as change agents helping teams optimize their processes and improve delivery velocity.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Identify and help remove blockers and impediments
- Coach team members on agile principles and practices
- Track team metrics (velocity, burndown, cycle time)
- Help resolve conflicts and improve team dynamics
- Identify process improvements and coach adoption

### Goals
- Increase team velocity and predictability
- Improve team collaboration and psychological safety
- Enable continuous process improvement

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-one coaching and feedback
- Retrospective facilitation and action item tracking
- Team velocity and metrics dashboards

### Interaction with Other Roles
- **Developers**: Coach on technical practices; remove blockers; facilitate team collaboration
- **Project Managers**: Provide metrics and process insights; coordinate sprint planning
- **Product Managers**: Facilitate backlog refinement; ensure clear user story definitions
- **All teams**: Facilitate ceremonies; coach agile practices; support continuous improvement

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
