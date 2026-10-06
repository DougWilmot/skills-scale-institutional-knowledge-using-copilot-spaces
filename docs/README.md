# OctoAcme Project Management Documentation

## Overview
OctoAcme follows a structured project management approach centered on customer value, iterative delivery, clear ownership, and data-driven decisions. This documentation suite provides guidance for all team members on how we run projects, from initiation through retrospectives.

## Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle
1. **Initiation**: Problem statement, stakeholders, high-level timeline
2. **Planning**: Scope, resources, milestones, dependencies
3. **Execution**: Build, test, review, iterate
4. **Release**: Deploy, verify, announce
5. **Close & Retrospective**: Capture learnings and next steps

## Project Management Processes Summary

### Initiation & Planning
OctoAcme's project management approach starts with clear initiation and ends with continuous improvement. In the initiation phase, teams validate the business need, define success metrics, identify stakeholders, and create a project one-pager with goals, milestones, risks, and roles. Planning then turns that concept into a backlog with acceptance criteria, estimated work, dependencies, and a release timeline. This keeps the team aligned around what is being built, why it matters, and how progress will be measured.

### Roles & Organization
The model emphasizes clear ownership and distinct personas. Developers are responsible for building and testing software, product managers define outcomes and priorities, and project managers coordinate schedule, risk, and communication across the team. Stakeholders provide inputs and approvals, while QA/testing ensures the work meets acceptance criteria and quality expectations. These roles work together in a structured cadence: daily standups, weekly delivery or PM syncs, milestone demos, and stakeholder communications. Responsibilities are clear, cross-team dependencies are visible, and decisions are made with customer value and measurable impact in mind.

### Communication & Risk Management
Communication is a core part of the process. OctoAcme uses a single source of truth for project status, such as a project README or release document, and maintains regular updates through team standups, PM/product alignment, stakeholder briefings, and status reports. Risk and dependency management are integrated into the communication rhythm, with a risk register tracking issues, impact, probability, ownership, and mitigation. When blockers occur, the escalation path moves from the team to the PM, then to the Product Lead or sponsor as needed, especially for business-critical or security-related problems.

### Quality & Continuous Improvement
Quality assurance is treated as part of delivery, not a final checkpoint. The team is expected to write unit tests for new logic, add integration and smoke tests where relevant, and run security scans in CI. PRs are kept small when possible, should include an issue link and acceptance criteria, and require review before merge. Definition of Done is documented up front, and release gates require passing tests, security checks, release notes, rollback planning, and post-deploy verification. After each sprint or milestone, the team conducts a retrospective to capture what went well, what needs improvement, and what action items should be tracked in the backlog. This creates a cycle of learning and continuous improvement that helps the team refine both the product and the process over time.

## Process Documentation

### Getting Started
- [Project Management Overview](octoacme-project-management-overview.md) — Quick introduction to roles, artifacts, and the project lifecycle
- [Roles and Personas](octoacme-roles-and-personas.md) — Detailed descriptions of Project Managers, Product Managers, Developers, and QA roles

### Project Phases
- [Project Initiation](octoacme-project-initiation.md) — Validate business need, align stakeholders, and make a go/no-go decision
- [Project Planning](octoacme-project-planning.md) — Break work into shippable increments, identify dependencies, and create release plans
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Manage day-to-day delivery, testing, and progress tracking
- [Release & Deployment](octoacme-release-and-deployment.md) — Standardize releases and deployments to reduce risk
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and iterate on processes

### Cross-Cutting Concerns
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies

## Key Roles
- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

## How to Use These Docs
- Start with the [Project Management Overview](octoacme-project-management-overview.md) for a high-level introduction
- Follow the project lifecycle phases in order for a new project
- Use specific process docs as reference guides during execution
- Keep the Project Charter updated in your project repository
- Store role-specific context and process enhancements in `.copilot/` for use with Copilot Spaces
