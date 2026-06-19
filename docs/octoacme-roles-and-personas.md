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

## Delivery Lead

### Role Summary
Delivery Leads oversee day-to-day delivery for a release or major milestone, managing sprint commitments, tracking cross-team dependencies, and maintaining timeline momentum.

### Responsibilities
- Oversee day-to-day delivery for a release or major milestone
- Manage sprint commitments and ensure team velocity
- Track cross-team dependencies and flag integration risks
- Maintain the release milestone timeline and adjust plans as needed
- Facilitate daily standups and remove blockers
- Report delivery status to Project Manager and stakeholders

### Goals
- Maintain predictable delivery cadence
- Reduce dependency-related delays and rework
- Keep the team focused and unblocked

### Typical Communication
- Daily standups and blocking issue calls
- Weekly delivery sync with PM and product stakeholders
- Dependency status updates to connected teams
- Escalations to PM for timeline or scope risks

### Interactions
- Works with **PM** on scheduling, status, and escalation decisions
- Works with **Product Manager** on prioritization during sprint
- Works with **Engineering Managers** on capacity and team constraints
- Works with **QA** on test readiness and acceptance criteria
- Works with **Release Coordinator** on deployment readiness and rollout planning

---

## Release Coordinator

### Role Summary
Release Coordinators manage end-to-end release execution, coordinating build, deployment, testing, and communication across teams.

### Responsibilities
- Coordinate release tasks across teams (build, deploy, smoke tests, rollout plan)
- Maintain release checklist and ensure all pre-release requirements are met
- Communicate deployment windows, rollback plans, and known issues
- Manage release notes and stakeholder announcements
- Facilitate post-release verification and incident triage if needed

### Goals
- Execute predictable, low-risk releases
- Minimize unplanned downtime and rollbacks
- Ensure clear communication across all stakeholders

### Typical Communication
- Release tracking and status updates (daily during release window)
- Release notes and deployment communication
- Incident response coordination
- Post-release retrospective and lessons learned

### Interactions
- Works closely with **Delivery Lead** on release timing and readiness
- Works with **DevOps/Platform** on build pipelines, deployment, and infrastructure
- Works with **Security Representative** for security gating and vulnerability scans
- Works with **Support Liaison** on post-release monitoring and support runbooks
- Works with **QA** on smoke test coordination

---

## Technical Program Manager (TPM)

### Role Summary
Technical Program Managers own cross-team technical dependencies, architecture-related risk tracking, and implementation coordination for complex, multi-team projects.

### Responsibilities
- Map and manage cross-team technical dependencies
- Track architecture-related risks and propose mitigation strategies
- Coordinate implementation across multiple teams and systems
- Facilitate technical design reviews and alignment
- Identify and communicate technical blockers and trade-offs

### Goals
- Reduce technical debt and rework
- Accelerate time to market by unblocking dependencies early
- Ensure architectural alignment and scalability

### Typical Communication
- Technical design review meetings and documentation
- Dependency status updates in weekly syncs
- Architecture decision records and trade-off memos
- Technical risk escalations

### Interactions
- Partners with **Engineering Managers** on team capacity and technical constraints
- Works with **Product Manager** on scope trade-offs and feasibility
- Collaborates with **Developers** on technical design and scheduling
- Coordinates with **Delivery Lead** on milestone dependencies
- Engages **Security Representative** on architectural security implications

---

## Engineering Manager

### Role Summary
Engineering Managers lead teams, focusing on hiring, career development, capacity planning, and ensuring engineering quality and maintainability.

### Responsibilities
- Hire, onboard, and develop team members
- Plan and allocate team capacity across projects
- Ensure code quality, testing standards, and maintainability
- Participate in technical design decisions and architecture discussions
- Foster a culture of learning and psychological safety

### Goals
- Build high-performing, stable teams
- Maintain engineering excellence and code quality
- Support team growth and retention

### Typical Communication
- 1-on-1s with direct reports
- Team retrospectives and planning sessions
- Technical design reviews
- Capacity and resource planning with PM and Delivery Lead

### Interactions
- Works with **PM/Delivery Lead** on resourcing, prioritization, and timeline adjustments
- Collaborates with **Developers** on technical decisions and code standards
- Partners with **QA** on test adoption and quality metrics
- Engages **Technical Program Manager** on cross-team coordination
- Supports **Security Representative** in security practices and code reviews

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers conduct user research, validate designs, and ensure features are accessible, usable, and meet user needs.

### Responsibilities
- Conduct user research to understand needs and pain points
- Create wireframes, prototypes, and design specifications
- Validate designs through user testing and feedback
- Ensure accessibility standards are met (WCAG, etc.)
- Provide design artifacts and acceptance criteria to development team

### Goals
- Maximize user satisfaction and feature adoption
- Reduce post-release usability issues
- Ensure inclusive design practices

### Typical Communication
- Design reviews and critique sessions
- Research findings and recommendations
- Design handoff documents and specification
- Feedback on prototypes and live features

### Interactions
- Collaborates with **Product Manager** on user needs and prioritization
- Works with **Developers** on implementation details and design fidelity
- Partners with **QA** on UI/UX acceptance tests
- Engages **Support Liaison** on user feedback and support pain points
- Coordinates with **Delivery Lead** on design review milestones

---

## Support Liaison

### Role Summary
Support Liaisons act as the bridge between the support team and the delivery team, ensuring customer-impacting issues are prioritized and resolved quickly.

### Responsibilities
- Gather and communicate customer-impacting issues and feedback
- Prioritize and triage post-release bugs reported by support
- Prepare support runbooks and troubleshooting guides
- Coordinate on production incidents and customer communication
- Advocate for customer perspective in prioritization decisions

### Goals
- Reduce mean time to resolution (MTTR) for customer issues
- Prevent recurring bugs through root cause analysis
- Improve customer satisfaction and trust

### Typical Communication
- Daily or weekly support issue triage calls
- Bug prioritization and escalation to Delivery Lead
- Incident response and customer communication
- Support runbook and knowledge base updates

### Interactions
- Works with **PM** on prioritization of incidents and follow-up feature requests
- Coordinates with **Release Coordinator** on planned communications and deployment windows
- Engages **Developers** and **QA** on reproducing and fixing issues
- Partners with **Delivery Lead** on incident response and resolution tracking
- Collaborates with **Engineering Manager** on team availability for urgent issues

---

## Security Representative

### Role Summary
Security Representatives ensure security requirements are integrated into design and release processes, manage vulnerability triage, and coordinate security incident response.

### Responsibilities
- Define security requirements and acceptance criteria for features
- Review high-risk changes and architectural decisions for security implications
- Coordinate security scanning in CI/CD pipelines
- Triage and prioritize security vulnerabilities
- Lead security incident response and post-incident review

### Goals
- Prevent security vulnerabilities and breaches
- Integrate security into development workflow without slowing delivery
- Maintain customer trust through transparent incident communication

### Typical Communication
- Security review meetings and design walkthroughs
- Vulnerability scan results and remediation tracking
- Incident notifications and response coordination
- Security training and awareness updates

### Interactions
- Engages **Developers** on fixes for discovered vulnerabilities
- Works with **Technical Program Manager** on dependency risk related to security
- Coordinates with **Release Coordinator** on release gating and deployment hold decisions
- Partners with **Engineering Manager** on security practices and code review standards
- Collaborates with **PM** and **Delivery Lead** on security-related scope trade-offs

---

## Data Analyst

### Role Summary
Data Analysts define and track metrics for success, validate experiment signals, and produce insights used in post-release evaluation and ongoing optimization.

### Responsibilities
- Define key success metrics aligned with product goals
- Validate telemetry and experiment tracking for accuracy
- Produce dashboards and reports on feature performance
- Analyze user behavior and identify optimization opportunities
- Support data-driven decision-making across teams

### Goals
- Provide clear, actionable insights on product impact
- Reduce decision-making time through accessible dashboards
- Enable evidence-based prioritization and iteration

### Typical Communication
- Weekly metrics and dashboard reviews
- Analysis reports and findings memos
- Experiment results and statistical summaries
- Ad-hoc data requests and deep-dives

### Interactions
- Works with **Product Manager** on success metrics definition and analysis
- Coordinates with **Developers** on instrumentation, logging, and data pipeline
- Partners with **PM/Delivery Lead** on post-release evaluation and reports to stakeholders
- Engages **UX Researcher** on user behavior insights
- Collaborates with **Support Liaison** on customer impact metrics

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference interaction notes when designing workflows to ensure all stakeholders are engaged appropriately.
