# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

> **Related:** This document was expanded to address gaps and improve role clarity as part of [issue #4](https://github.com/mariamedp/scale-institutional-knowledge-using-copilot-spaces/issues/4).

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

## QA Engineer/Tester

### Role Summary
QA Engineers/Testers define and execute test strategies to ensure software quality, reliability, and adherence to acceptance criteria. They act as quality advocates throughout the development lifecycle and ensure releases meet defined quality gates.

### Responsibilities
- Develop and maintain test plans, test cases, and automated test suites
- Execute functional, regression, and exploratory testing
- Track, document, and communicate defects and quality feedback
- Define and enforce release criteria and quality gates
- Collaborate with developers to improve test coverage and code quality
- Participate in sprint planning to advocate for quality considerations

### Goals
- Ensure all features meet acceptance criteria and quality standards
- Reduce defect escape rate to production
- Improve test automation coverage and efficiency
- Enable fast, reliable feedback loops for developers

### Typical Communication
- Daily standups and sprint planning
- Defect triage sessions with developers
- Quality gate reviews with Project Managers
- Test coverage and quality metrics reporting

### Interactions with Existing Roles
- **Developers:** Collaborates on defect triage, test coverage improvements, and testability design; provides quality feedback during code reviews
- **Project Managers:** Reports on quality metrics, advises on release readiness, and participates in setting quality gates for milestones
- **Product Managers:** Validates that acceptance criteria are testable and complete; provides insights on quality risks

### Handoffs & Accountability
- **Receives:** Feature specifications and acceptance criteria from Product Manager; code changes from Developers
- **Delivers:** Test results, defect reports, and release readiness assessments to Project Manager and Developers
- **Accountable for:** Ensuring all defined test scenarios are executed and quality gates are met before release

---

## UX Designer

### Role Summary
UX Designers create user-centered designs, including user flows, wireframes, and prototypes. They conduct usability testing and ensure that products are intuitive, accessible, and aligned with user needs.

### Responsibilities
- Research user needs and translate them into design requirements
- Create wireframes, mockups, and interactive prototypes
- Conduct usability testing and gather user feedback
- Collaborate with Product Managers to define user stories and acceptance criteria
- Work with Developers to ensure design fidelity during implementation
- Maintain and evolve design systems and style guides

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Ensure consistency across product interfaces
- Reduce user friction and improve task completion rates
- Advocate for user needs throughout the product lifecycle

### Typical Communication
- Weekly design reviews with Product and Development teams
- Usability testing sessions and findings reports
- Design handoff meetings with Developers
- Design critique sessions with peers

### Interactions with Existing Roles
- **Developers:** Hands off design specifications and assets; collaborates to resolve implementation constraints and ensure design fidelity
- **Product Managers:** Aligns on user goals and product requirements; validates designs against business objectives
- **Project Managers:** Coordinates design milestones and timelines; flags resource or schedule risks

### Handoffs & Accountability
- **Receives:** Product requirements and user research insights from Product Manager; technical constraints from Developers
- **Delivers:** Finalized design specs, prototypes, and assets to Developers; usability findings to Product Manager
- **Accountable for:** Ensuring designs are user-centered, accessible, and feasible within technical constraints

---

## Technical Writer

### Role Summary
Technical Writers produce and maintain clear, accurate documentation for products, APIs, and internal processes. They ensure that users, developers, and stakeholders have the information they need to succeed.

### Responsibilities
- Write, edit, and maintain user guides, API documentation, and release notes
- Collaborate with Developers and Product Managers to gather technical information
- Ensure documentation is accurate, up-to-date, and accessible
- Develop and enforce documentation standards and templates
- Gather feedback on documentation and iterate for clarity and usability

### Goals
- Reduce support burden through self-service documentation
- Improve onboarding time for new users and team members
- Maintain consistent documentation quality across products
- Ensure all releases have accurate, timely documentation

### Typical Communication
- Regular syncs with Developers and Product Managers for technical content
- Review sessions for documentation drafts
- Participation in release planning to ensure documentation readiness
- Feedback loops with Support Engineers on documentation gaps

### Interactions with Existing Roles
- **Developers:** Gathers technical details and reviews documentation for accuracy; collaborates on API docs and inline code comments
- **Product Managers:** Aligns on feature messaging and documentation priorities; ensures consistency with product positioning
- **Project Managers:** Coordinates documentation milestones as part of release planning; reports on documentation status

### Handoffs & Accountability
- **Receives:** Technical specifications from Developers; feature details and messaging from Product Manager
- **Delivers:** Published documentation, release notes, and onboarding guides to users and Support Engineers
- **Accountable for:** Ensuring documentation is accurate, complete, and delivered on schedule for each release

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams. They gather, analyze, and document requirements, ensuring that solutions meet business needs and are clearly understood by all parties.

### Responsibilities
- Elicit and document business requirements and user stories
- Analyze business processes and identify improvement opportunities
- Facilitate requirements workshops and stakeholder interviews
- Create process flows, data models, and business rules documentation
- Validate solutions against requirements and business objectives
- Support acceptance testing and sign-off activities

### Goals
- Ensure requirements are clear, complete, and agreed upon by stakeholders
- Reduce rework by catching requirement gaps early
- Improve alignment between business goals and delivered solutions
- Facilitate transparent communication between business and technical teams

### Typical Communication
- Requirements workshops and stakeholder interviews
- Weekly alignment meetings with Product and Project Managers
- Documentation reviews with Developers and QA
- Sign-off sessions with business stakeholders

### Interactions with Existing Roles
- **Developers:** Clarifies requirements and answers questions during implementation; participates in solution design discussions
- **Product Managers:** Collaborates on defining product requirements and acceptance criteria; provides business context
- **Project Managers:** Reports on requirements status and risks; supports scope and change management

### Handoffs & Accountability
- **Receives:** Business objectives and priorities from stakeholders; feedback from Developers on requirement feasibility
- **Delivers:** Documented requirements, process flows, and acceptance criteria to Developers and QA
- **Accountable for:** Ensuring requirements are complete, unambiguous, and traceable to business objectives

---

## Support Engineer

### Role Summary
Support Engineers address customer incidents, maintain the knowledge base, and provide insights from user feedback to drive product improvements. They serve as the voice of the customer within the organization.

### Responsibilities
- Respond to and resolve customer support tickets and incidents
- Escalate complex issues to Developers or appropriate teams
- Maintain and update the knowledge base and FAQs
- Analyze support trends and provide feedback to Product and Development teams
- Contribute to documentation improvements based on common user issues
- Participate in post-incident reviews and root cause analysis

### Goals
- Resolve customer issues quickly and effectively
- Reduce repeat incidents through knowledge base improvements
- Surface actionable feedback to improve the product
- Maintain high customer satisfaction and trust

### Typical Communication
- Daily triage of support tickets and incident queues
- Regular syncs with Developers for issue escalation and resolution
- Feedback sessions with Product Managers on user pain points
- Participation in incident reviews and retrospectives

### Interactions with Existing Roles
- **Developers:** Escalates bugs and incidents for resolution; provides customer context for defect triage
- **Product Managers:** Shares user feedback and trends to inform product roadmap; advocates for customer needs
- **Project Managers:** Coordinates on incident escalation and communication; contributes to post-incident reviews

### Handoffs & Accountability
- **Receives:** Bug reports and incidents from customers; product updates and release notes from Technical Writers
- **Delivers:** Escalated issues to Developers; customer feedback to Product Managers; knowledge base updates
- **Accountable for:** Ensuring timely resolution of customer issues and maintaining an accurate, helpful knowledge base

---

## Handoffs, Collaboration & Accountability (Cross-Role)

Effective project delivery depends on clear handoffs, transparent collaboration, and shared accountability. This section summarizes how roles work together to ensure nothing falls through the cracks.

### General Handoff Practices
- All handoffs should be documented in the relevant project artifact (e.g., ticket, design spec, release notes)
- Handoffs include explicit acceptance criteria and a named recipient responsible for the next step
- Blockers or delays in handoffs are surfaced during standups or via project communication channels

### Collaboration Norms
- Use shared project boards (e.g., GitHub Projects, Kanban) for visibility into work status
- Hold regular cross-functional syncs (e.g., weekly design/dev/QA review, sprint planning)
- Maintain open channels (Slack, Teams, etc.) for quick clarifications and escalations
- Encourage early and frequent feedback—flag issues as soon as they arise

### Accountability Model
- Each deliverable has a single **owner** (the role responsible for completion) and one or more **contributors**
- Project Managers track accountability through the project board and status updates
- Retrospectives include a review of handoff effectiveness and accountability gaps

### Quality Ownership
- QA Engineers/Testers are accountable for validating quality at each milestone
- Developers are responsible for testability and addressing defects promptly
- Product Managers ensure acceptance criteria are clear and complete

### Documentation Flow
- Technical Writers produce and maintain user-facing and internal documentation
- Developers and Product Managers provide input and review for accuracy
- Documentation is delivered as part of each release, coordinated by the Project Manager

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

