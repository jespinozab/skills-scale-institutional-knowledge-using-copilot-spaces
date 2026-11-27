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

## QA/Quality Leads

### Role Summary
QA/Quality Leads own quality strategy and acceptance evidence across the project. They help the team prevent defects and confirm that delivered work meets functional, non-functional, and release requirements.

### Responsibilities
- Define test strategy, coverage plans, and quality gates
- Coordinate test planning and acceptance evidence
- Facilitate defect triage and track quality risks
- Review testability and support risk-based testing

### Goals
- Prevent defects and maintain consistent quality standards
- Provide clear evidence that acceptance criteria are met
- Improve feedback time for quality issues

### Interactions with Existing Roles
- Collaborate with **Developers** on testability, test coverage, defect reproduction, and fixes.
- Work with **Product Managers** to clarify acceptance criteria and validate that quality measures reflect customer needs.
- Partner with **Project Managers** to report quality risks and support release-readiness decisions.

---

## Release/DevOps Leads

### Role Summary
Release/DevOps Leads own deployment planning and execution. They ensure environments, automation, approvals, and rollback processes are ready for reliable releases.

### Responsibilities
- Plan release steps, environment readiness, and deployment automation
- Coordinate approvals and validate operational readiness
- Manage rollback procedures and release communications
- Identify deployment dependencies and recovery risks

### Goals
- Deliver safe, repeatable, and observable releases
- Reduce deployment lead time and failed-change risk
- Ensure the team can recover quickly when a release fails

### Interactions with Existing Roles
- Work with **Developers** to confirm deployable artifacts, configuration, runbooks, and observability.
- Collaborate with **QA/Quality Leads** on release validation and quality gates.
- Coordinate with **Product Managers** on release scope and customer impact, and with **Project Managers** on timing, dependencies, approvals, and status.

---

## Security/Compliance Leads

### Role Summary
Security/Compliance Leads establish security and regulatory requirements and ensure project decisions account for applicable controls and risks.

### Responsibilities
- Define security and compliance requirements and acceptance evidence
- Review designs for threats, controls, and exceptions
- Coordinate assessments, approvals, and remediation
- Maintain traceability for controls and unresolved risks

### Goals
- Reduce security and compliance exposure
- Embed practical controls into delivery workflows
- Maintain clear evidence for required decisions and approvals

### Interactions with Existing Roles
- Advise **Developers** on secure implementation and remediation priorities.
- Help **Product Managers** balance customer value with security, privacy, and compliance constraints.
- Work with **Project Managers** to plan reviews, approvals, exceptions, and schedule impacts.

---

## Data/Analytics Leads

### Role Summary
Data/Analytics Leads ensure data requirements, instrumentation, quality, and outcome measurement support informed project decisions.

### Responsibilities
- Define data sources, requirements, quality checks, and ownership
- Establish instrumentation and analytics for outcomes
- Analyze delivery and product metrics
- Identify data gaps and risks that affect decisions

### Goals
- Make decisions based on reliable, timely data
- Measure customer and business outcomes consistently
- Improve observability across delivery and adoption

### Interactions with Existing Roles
- Work with **Product Managers** to define success metrics and interpret outcomes.
- Partner with **Developers** on instrumentation, data contracts, pipelines, and quality controls.
- Support **Project Managers** with delivery metrics, dependencies, and data-related risks.

---

## UX/Design Leads

### Role Summary
UX/Design Leads represent users through research, interaction design, and usability validation. They ensure the solution is understandable, accessible, and useful.

### Responsibilities
- Conduct or coordinate user research and usability testing
- Create and maintain interaction and experience specifications
- Validate accessibility and design standards
- Incorporate evidence into design decisions

### Goals
- Improve usability and product-market fit
- Resolve usability risks before they become implementation constraints
- Deliver accessible, consistent experiences

### Interactions with Existing Roles
- Collaborate with **Product Managers** to translate customer needs into prioritized experience requirements.
- Work with **Developers** to clarify feasibility, implementation details, and design constraints.
- Coordinate with **QA/Quality Leads** on usability, accessibility, and experience acceptance criteria.

---

## Change/Adoption Leads

### Role Summary
Change/Adoption Leads plan stakeholder engagement and readiness activities so users can successfully adopt delivered changes.

### Responsibilities
- Assess stakeholder impact and adoption risks
- Plan communications, training, and enablement
- Coordinate pilots, feedback, and rollout support
- Measure adoption and support follow-up actions

### Goals
- Increase user readiness and adoption
- Reduce disruption and resistance to change
- Ensure stakeholder feedback reaches delivery teams

### Interactions with Existing Roles
- Work with **Product Managers** to communicate the product value proposition and adoption priorities.
- Partner with **Project Managers** on rollout plans, communications, and stakeholder dependencies.
- Collaborate with **Developers**, **UX/Design Leads**, and **Operations/Support Leads** to prepare materials and address readiness issues.

---

## Operations/Support Leads

### Role Summary
Operations/Support Leads ensure the delivered solution is supportable and ready for live use. They coordinate handoffs, incident response, and post-launch feedback.

### Responsibilities
- Plan operational readiness and support coverage
- Maintain runbooks, escalation paths, and known-issue processes
- Coordinate incidents and service recovery
- Feed operational data and user feedback into improvements

### Goals
- Maintain reliable service after launch
- Reduce resolution time and support burden
- Create effective operational and support handoffs

### Interactions with Existing Roles
- Coordinate with **Release/DevOps Leads** on monitoring, runbooks, rollback, and operational readiness.
- Work with **Developers** on known issues, fixes, root-cause analysis, and service improvements.
- Alert **Project Managers** to service-impact risks and communicate priorities to **Product Managers**.

---

## Customer/Stakeholder Representatives

### Role Summary
Customer/Stakeholder Representatives provide domain knowledge and validate that proposed outcomes meet real needs. They offer an accountable route for input and decisions from affected stakeholders.

### Responsibilities
- Represent user or stakeholder needs and constraints
- Review proposals, prototypes, and acceptance evidence
- Provide timely decisions and feedback
- Surface organizational or customer risks and dependencies

### Goals
- Keep project decisions aligned with real needs
- Improve confidence in acceptance and adoption outcomes
- Reduce late changes caused by missing stakeholder input

### Interactions with Existing Roles
- Work with **Product Managers** to clarify requirements, priorities, and success measures.
- Provide decisions and feedback to **Project Managers** on scope, dependencies, and readiness.
- Collaborate with **UX/Design Leads**, **QA/Quality Leads**, and **Change/Adoption Leads** to validate experiences, acceptance, and rollout plans.

---

## Persona Interaction Summary

The personas share ownership where work overlaps, while retaining explicit handoffs:
- Product Managers define desired outcomes and priorities.
- Project Managers coordinate delivery, schedules, risks, and stakeholder communication.
- Developers, QA/Quality Leads, and Release/DevOps Leads establish and deliver technical quality and release readiness.
- Security/Compliance, Data/Analytics, UX/Design, Change/Adoption, Operations/Support, and Customer/Stakeholder representatives provide specialized decision, evidence, and adoption inputs.
- Project Managers escalate cross-persona risks and unresolved decisions to the appropriate role; Product Managers retain product priority decisions, subject to documented security, compliance, safety, or other constraints.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
