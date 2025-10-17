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

## UX Designer

### Role Summary
UX Designers research user needs, design intuitive interfaces, and validate solutions through testing. They ensure product experiences are usable, accessible, and aligned with user goals.

### Responsibilities
- Conduct user research and synthesize insights
- Create wireframes, prototypes, and design specifications
- Collaborate with Product Managers and Developers on design feasibility
- Validate designs through usability testing and feedback
- Maintain design systems and UI consistency

### Goals
- Deliver experiences that meet user needs and reduce friction
- Ensure accessibility and inclusive design practices
- Contribute to measurable improvements in user satisfaction and engagement

### Typical Communication
- Design reviews and critique sessions
- User research readouts and insight sharing
- Collaboration in planning and refinement meetings
- Handoff documentation and design specs

### Collaboration Touchpoints
- **Initiation**: Identify user research needs and scope UX activities
- **Planning**: Synthesize research insights, define design deliverables
- **Execution**: Review implemented flows, provide design feedback
- **Release**: Conduct UI/UX acceptance review for user-facing changes

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain CI/CD pipelines, infrastructure, and deployment automation. They ensure reliable, efficient, and secure release processes.

### Responsibilities
- Design and maintain deployment pipelines and infrastructure
- Monitor system health, performance, and reliability
- Implement automation for builds, tests, and deployments
- Manage environment configuration and secrets
- Support incident response and rollback procedures

### Goals
- Reduce deployment friction and increase release frequency
- Ensure system reliability and minimize downtime
- Provide observability and proactive issue detection

### Typical Communication
- Infrastructure and pipeline design reviews
- Incident response and post-mortems
- Release planning and deployment coordination
- Monitoring and alerting discussions

### Collaboration Touchpoints
- **Initiation**: Assess infrastructure constraints and deployment requirements
- **Planning**: Review environment and pipeline readiness
- **Execution**: Monitor pipeline health and resolve build/deploy issues
- **Release**: Validate monitoring, rollback plans, and deployment execution

---

## Technical Writer

### Role Summary
Technical Writers create and maintain documentation that enables users and team members to understand and use products effectively. They ensure documentation accuracy, clarity, and completeness.

### Responsibilities
- Write and maintain user guides, API docs, and internal documentation
- Collaborate with Product, Engineering, and Support on content needs
- Ensure documentation aligns with product changes
- Establish and maintain documentation standards
- Gather feedback to improve documentation quality

### Goals
- Enable self-service through clear, accurate documentation
- Reduce support burden via comprehensive knowledge base
- Maintain documentation that evolves with the product

### Typical Communication
- Documentation reviews and content planning
- Collaboration with Engineering on technical accuracy
- Coordination with Support on common user questions
- Release note drafting and publication

### Collaboration Touchpoints
- **Initiation**: Outline documentation scope and requirements
- **Planning**: Draft documentation plan and timeline
- **Execution**: Update documentation as features develop
- **Release**: Finalize release notes and update knowledge base

---

## Support Lead

### Role Summary
Support Leads ensure teams are prepared to handle customer inquiries and incidents. They bridge product development and customer-facing support operations.

### Responsibilities
- Assess support impact of new features and changes
- Create support enablement materials and training
- Coordinate incident response and escalation paths
- Gather and communicate customer feedback to Product teams
- Maintain support knowledge base and playbooks

### Goals
- Minimize customer impact through proactive support readiness
- Reduce resolution time via clear escalation and documentation
- Surface product improvement opportunities from support trends

### Typical Communication
- Support readiness reviews and training sessions
- Incident escalation and coordination
- Customer feedback summaries and trend reports
- Collaboration on release impact assessments

### Collaboration Touchpoints
- **Initiation**: Assess support impact and resource needs
- **Planning**: Outline support readiness activities and training needs
- **Execution**: Capture support feedback and escalate blocking issues
- **Release**: Enable support team and monitor post-release incidents

---

## Role Interaction Matrix

This table shows primary (**P**) and supporting (**S**) role participation across project lifecycle phases:

| Lifecycle Phase | PM | PdM | Dev | UX | DevOps | Writer | Support | QA |
|-----------------|----|----|-----|-------|--------|--------|---------|-----|
| Initiation | **P** | **P** | S | S | S | S | S | - |
| Planning | **P** | **P** | **P** | S | S | S | S | S |
| Execution | **P** | S | **P** | S | S | S | S | **P** |
| Release | **P** | S | S | S | **P** | **P** | **P** | S |
| Retrospective | **P** | **P** | **P** | S | S | S | S | S |

**Legend:**
- **P** = Primary participant (leads activities or decisions in this phase)
- **S** = Supporting participant (provides input, reviews, or assists)
- **-** = Typically not involved

**Note:** QA/Testing is included in the matrix as it is referenced throughout the documentation as a core role, though a full persona definition is not provided in this document.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

