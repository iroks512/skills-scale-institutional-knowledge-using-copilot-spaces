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

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate Agile ceremonies, remove team blockers, and coach team members on Agile practices and continuous improvement. They act as a servant-leader, enabling the team to self-organize and deliver value iteratively.

### Responsibilities
- Facilitate daily standups, sprint planning, retrospectives, and reviews
- Identify and help resolve team blockers and impediments
- Coach team members on Agile values and practices
- Protect the team from external distractions and scope creep
- Track team velocity and sprint metrics
- Escalate organizational blockers to the PM or PdM

### Goals
- Enable team self-organization and continuous improvement
- Maximize team velocity and flow
- Build a high-performing, collaborative team culture

### Typical Communication
- Daily standup facilitation
- Sprint planning and retrospective meetings
- One-on-ones with team members for coaching
- Weekly status updates with PM on team health

### Interaction with Existing Roles
- **With Project Manager**: Provides metrics and team health data; escalates schedule risks and resource constraints
- **With Product Manager**: Helps prioritize backlog based on team capacity and dependencies; coordinates sprint goals
- **With Developers**: Removes blockers; coaches on technical practices, collaboration, and Agile principles
- **With QA**: Ensures quality standards are integrated into sprint planning and Definition of Done

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide architectural guidance, mentor developers, and ensure technical excellence. They make key technical decisions and help teams navigate complex design challenges while balancing innovation with maintainability.

### Responsibilities
- Define technical architecture and design patterns
- Review code for architectural alignment and quality
- Mentor developers and conduct technical design reviews
- Identify technical risks and propose mitigations
- Ensure scalability, performance, and maintainability standards
- Collaborate with Security & Compliance on technical security controls
- Evaluate and recommend technology solutions

### Goals
- Maintain technical excellence and code quality
- Enable scalable, maintainable system design
- Reduce technical debt and architectural risks
- Develop team technical capabilities

### Typical Communication
- Technical design reviews and architecture discussions
- Code review comments and architectural guidance
- Technical spikes and proof-of-concept work
- Knowledge sharing sessions and documentation

### Interaction with Existing Roles
- **With Developers**: Provide technical direction; conduct design and code reviews; mentor on best practices
- **With QA**: Define technical test strategies and automation approaches; review test coverage
- **With Project Manager**: Flag technical risks, dependencies, and effort estimates for complex work
- **With Product Manager**: Advise on technical feasibility, trade-offs, and implications of feature requests

---

## Security & Compliance Officer

### Role Summary
Security & Compliance Officers ensure that projects meet security requirements, compliance standards, and risk management policies. They conduct security reviews and help teams embed security throughout the development lifecycle, from planning through deployment.

### Responsibilities
- Conduct security reviews and threat assessments
- Ensure compliance with regulatory requirements and internal policies
- Review code and infrastructure for security vulnerabilities
- Define security acceptance criteria and testing requirements
- Coordinate security scanning and penetration testing
- Provide security training and best practices guidance
- Manage security incidents and postmortems

### Goals
- Prevent security breaches and compliance violations
- Build security awareness and practices across teams
- Maintain compliance with regulatory requirements
- Reduce security-related risks and vulnerabilities

### Typical Communication
- Security design reviews during planning phase
- Code and infrastructure security reviews
- Security incident response meetings
- Compliance and audit reporting

### Interaction with Existing Roles
- **With Developers**: Review code for vulnerabilities; provide security guidance and training; define secure coding standards
- **With QA**: Integrate security testing into test plans; coordinate penetration testing and vulnerability assessments
- **With DevOps/Infrastructure Engineer**: Review infrastructure security and access controls; collaborate on secrets management
- **With Project Manager**: Escalate critical security risks; communicate timeline impact of security work
- **With Technical Lead**: Partner on architectural security decisions and security design patterns

---

## UX/Design Lead

### Role Summary
UX/Design Leads own the user experience strategy, conduct user research, and validate that solutions meet user needs and usability standards. They collaborate with Product and Engineering to deliver delightful, accessible experiences that delight users.

### Responsibilities
- Conduct user research and define user personas
- Create wireframes, prototypes, and design specifications
- Define usability standards and accessibility requirements (WCAG compliance)
- Conduct user testing and gather feedback
- Review implementations against design specifications
- Advocate for user needs within the team
- Iterate on designs based on feedback and metrics

### Goals
- Deliver intuitive, accessible user experiences
- Validate product-market fit through user research
- Reduce support burden through better UX
- Build user satisfaction and loyalty

### Typical Communication
- User research workshops and design reviews
- Prototype and design specification presentations
- User testing sessions and feedback analysis
- Weekly syncs with Product Manager on user insights

### Interaction with Existing Roles
- **With Product Manager**: Partner on defining user needs and success metrics; validate feature priorities based on user research
- **With Developers**: Provide design specs and iterate on implementation; review prototypes and coded experiences
- **With QA**: Define usability acceptance criteria; participate in user testing sessions
- **With Stakeholders**: Present user research insights and design rationale; communicate impact on business goals

---

## DevOps / Infrastructure Engineer

### Role Summary
DevOps/Infrastructure Engineers build and maintain deployment pipelines, infrastructure, monitoring, and observability. They enable teams to deploy confidently and maintain system reliability, performance, and cost efficiency in production environments.

### Responsibilities
- Design and manage CI/CD pipelines and automation
- Provision and manage infrastructure (cloud, on-premises)
- Implement monitoring, logging, and alerting systems
- Manage secrets, access controls, and security policies
- Plan and execute deployments with minimal downtime
- Support incident response and rollback procedures
- Optimize costs and performance
- Maintain infrastructure documentation and runbooks

### Goals
- Enable fast, reliable, safe deployments
- Maintain high system availability and performance
- Minimize mean time to recovery (MTTR) for incidents
- Optimize infrastructure costs and efficiency

### Typical Communication
- Deployment planning and execution meetings
- Incident response and postmortem sessions
- Infrastructure and deployment pipeline reviews
- Performance and cost optimization discussions

### Interaction with Existing Roles
- **With Developers**: Enable fast, safe deployments; provide infrastructure APIs and self-service tools; support local development environments
- **With QA**: Support test environment provisioning and data management; provide staging environment parity
- **With Technical Lead**: Collaborate on reliability and performance architecture; evaluate infrastructure solutions
- **With Security & Compliance Officer**: Implement security controls and access management; support compliance auditing

---

## Stakeholders / Executive Sponsors

### Role Summary
Stakeholders and Executive Sponsors provide strategic direction, organizational support, and resources to ensure project success. They remove organizational blockers, approve budgets and timelines, and represent business and user interests at the executive level.

### Responsibilities
- Provide strategic direction and business context
- Approve budgets, timelines, and resource allocation
- Remove organizational and cross-functional blockers
- Escalate and resolve business-level risks and conflicts
- Communicate project status to leadership
- Validate alignment with business strategy and goals
- Support user communication and change management

### Goals
- Ensure project delivers business value
- Maintain alignment with organizational strategy
- Minimize business risk and disruption
- Enable team success through organizational support

### Typical Communication
- Monthly executive status updates and demos
- Budget and resource approval meetings
- Risk and decision escalation forums
- Strategic planning and roadmap reviews

### Interaction with Existing Roles
- **With Project Manager**: Approve plans and budgets; resolve cross-functional dependencies and organizational blockers
- **With Product Manager**: Validate business priorities and success metrics; provide market and strategic context
- **With Developers**: Communicate project context and business value; support user engagement and feedback
- **With All Roles**: Provide executive air cover and organizational support to enable team success

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When assigning responsibilities and managing dependencies, refer to the interaction patterns defined for each persona to understand communication needs and collaboration points.
- New team members can use this document to understand where their role fits into the OctoAcme project management approach and how they collaborate with other specialized roles.
