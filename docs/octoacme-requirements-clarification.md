# OctoAcme — Requirements Clarification Checklist

## Purpose
Provide a structured approach to gathering, clarifying, and validating requirements to reduce ambiguity and rework during project execution.

## When to Use
- During initial requirements gathering
- When refining user stories or features
- Before sprint planning
- When requirements seem unclear or incomplete
- After receiving change requests

---

## Initial Requirements Gathering

### Who Should Be Involved
- Business Analyst (leads)
- Product Manager
- Project Manager
- Key Stakeholders
- Technical Lead/Architect (for feasibility input)
- UX/UI Designer (for user experience considerations)
- Security Lead (for security requirements)

### Core Questions

#### Problem Definition
- [ ] What problem are we trying to solve?
- [ ] Who experiences this problem?
- [ ] How do they currently work around it?
- [ ] What is the impact of not solving this problem?
- [ ] What would success look like?

#### User & Stakeholder Context
- [ ] Who are the primary users?
- [ ] Who are the secondary users or affected parties?
- [ ] What are their roles and responsibilities?
- [ ] What is their technical proficiency level?
- [ ] Are there accessibility requirements?

#### Business Value
- [ ] What business goals does this support?
- [ ] How will success be measured?
- [ ] What are the expected outcomes or KPIs?
- [ ] What is the priority relative to other work?
- [ ] What is the business impact if this is delayed?

---

## Functional Requirements

### Scope & Features
- [ ] What are the core features/capabilities needed?
- [ ] What is in scope vs. out of scope?
- [ ] What are the must-haves vs. nice-to-haves?
- [ ] Are there any dependencies on other features or systems?
- [ ] What integrations are required?

### User Workflows
- [ ] What are the primary user flows?
- [ ] What are the steps in each workflow?
- [ ] Where do users enter the flow?
- [ ] Where do they exit?
- [ ] What decision points exist in the flow?

### Data Requirements
- [ ] What data needs to be captured, stored, or displayed?
- [ ] What are the data types and formats?
- [ ] What are the data validation rules?
- [ ] Where does the data come from?
- [ ] How long should data be retained?
- [ ] Are there data privacy or compliance considerations?

### Business Rules
- [ ] What business rules govern this feature?
- [ ] What validations or constraints must be enforced?
- [ ] What calculations or logic need to be applied?
- [ ] Are there different rules for different user types or contexts?
- [ ] What happens when rules are violated?

---

## Non-Functional Requirements

### Performance
- [ ] What are the expected load/volume levels?
- [ ] What response time is acceptable?
- [ ] How many concurrent users should be supported?
- [ ] Are there specific performance benchmarks?

### Security
- [ ] What level of data sensitivity is involved?
- [ ] What authentication/authorization is required?
- [ ] Are there compliance requirements (GDPR, HIPAA, etc.)?
- [ ] What audit logging is needed?
- [ ] Are there specific security standards to follow?

### Availability & Reliability
- [ ] What uptime is required?
- [ ] What is the acceptable error rate?
- [ ] What are the disaster recovery requirements?
- [ ] Are there backup and restore needs?

### Scalability
- [ ] What is the expected growth trajectory?
- [ ] What are the long-term scaling requirements?
- [ ] Are there seasonal or event-driven spikes?

### Usability & Accessibility
- [ ] What accessibility standards must be met (WCAG 2.1 Level AA)?
- [ ] What devices/browsers must be supported?
- [ ] What are the localization/internationalization needs?
- [ ] Are there specific UX principles or brand guidelines?

---

## Edge Cases & Error Handling

- [ ] What happens when inputs are invalid?
- [ ] How should the system handle missing or incomplete data?
- [ ] What if external services are unavailable?
- [ ] How should timeouts be handled?
- [ ] What happens if a user has insufficient permissions?
- [ ] How should concurrent modifications be handled?
- [ ] What are the maximum limits (file size, record count, etc.)?

---

## Acceptance Criteria Definition

### INVEST Criteria Check
Is the requirement/user story:
- [ ] **Independent**: Can it be developed separately from other stories?
- [ ] **Negotiable**: Can details be discussed and adjusted?
- [ ] **Valuable**: Does it deliver value to users/business?
- [ ] **Estimable**: Can the team estimate the effort?
- [ ] **Small**: Can it be completed in one sprint?
- [ ] **Testable**: Can success be verified?

### Acceptance Criteria Template
For each requirement, define:
- [ ] **Given** (preconditions/context)
- [ ] **When** (action/trigger)
- [ ] **Then** (expected outcome)

### Examples:
```
Given: User is logged in as an admin
When: User navigates to the user management page
Then: System displays list of all active users with edit/delete options
```

---

## Dependencies & Constraints

### Technical Dependencies
- [ ] What systems, APIs, or services does this depend on?
- [ ] Are there infrastructure requirements?
- [ ] What technology stack constraints exist?
- [ ] Are there performance or architectural constraints?

### Team Dependencies
- [ ] What other teams need to be involved?
- [ ] What is their availability?
- [ ] What is the communication plan?
- [ ] Are there shared resources or potential conflicts?

### External Dependencies
- [ ] Are there third-party vendor dependencies?
- [ ] Do we need approvals or sign-offs?
- [ ] Are there legal or compliance reviews needed?
- [ ] What is the timeline for external dependencies?

### Business Constraints
- [ ] What is the deadline or target release date?
- [ ] What is the budget?
- [ ] Are there resource limitations?
- [ ] What are the regulatory constraints?

---

## Validation & Sign-off

### Requirements Review Checklist
- [ ] Requirements are clear, complete, and unambiguous
- [ ] Acceptance criteria are testable
- [ ] Assumptions are documented
- [ ] Risks are identified
- [ ] Dependencies are mapped
- [ ] Technical feasibility confirmed by development team
- [ ] Estimates provided by development team
- [ ] Security requirements reviewed by Security Lead
- [ ] UX considerations reviewed by UX/UI Designer
- [ ] All stakeholders have reviewed and provided feedback

### Sign-off
- [ ] Business Analyst approval
- [ ] Product Manager approval
- [ ] Technical Lead approval
- [ ] Security Lead approval (if security-sensitive)
- [ ] Stakeholder approval (if required)

---

## Requirements Document Template

### 1. Overview
- Requirement ID
- Title
- Description
- Priority (Critical, High, Medium, Low)
- Status (Draft, Under Review, Approved, In Progress, Complete)

### 2. Business Context
- Business objective
- User personas affected
- Success metrics

### 3. Functional Requirements
- User stories with acceptance criteria
- User workflows
- Business rules
- Data requirements

### 4. Non-Functional Requirements
- Performance requirements
- Security requirements
- Accessibility requirements
- Compatibility requirements

### 5. Assumptions & Constraints
- Technical assumptions
- Business assumptions
- Known constraints
- Out of scope items

### 6. Dependencies
- Technical dependencies
- Team dependencies
- External dependencies

### 7. Risks
- Identified risks
- Mitigation strategies

### 8. Acceptance Criteria
- Detailed acceptance criteria in Given/When/Then format
- Test scenarios

### 9. Approvals
- Approval signatures and dates

---

## Common Requirements Clarification Mistakes to Avoid

1. **Assumption Trap**: Don't assume you understand without asking
2. **Solution Focus**: Focus on the problem, not jumping to solutions
3. **Insufficient Stakeholder Input**: Ensure all perspectives are heard
4. **Ignoring Non-Functional Requirements**: Don't overlook performance, security, etc.
5. **Vague Acceptance Criteria**: Make criteria specific and testable
6. **Missing Edge Cases**: Always ask "what if..."
7. **Skipping Validation**: Always validate understanding with stakeholders
8. **No Prioritization**: Ensure requirements are prioritized
9. **Documentation Neglect**: Document everything discussed
10. **One-Time Gathering**: Requirements evolve; plan for iterations

---

## Tips for Effective Requirements Clarification

- **Ask "Why" Five Times**: Get to the root cause and real need
- **Use Visual Aids**: Diagrams, mockups, and flows clarify better than text
- **Provide Examples**: Concrete examples reduce ambiguity
- **Confirm Understanding**: Summarize and play back what you heard
- **Document Decisions**: Record what was decided and why
- **Iterate**: Plan for multiple refinement sessions
- **Involve the Right People**: Get input from all affected roles
- **Stay User-Focused**: Always tie requirements back to user needs
