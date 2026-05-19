# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation. This folder is the central reference for how OctoAcme plans, executes, ships, and continuously improves its work. Whether you are a new contributor, a stakeholder, or a team member, start here to understand our processes and find the guide you need.

## Overview

OctoAcme follows a lightweight but structured lifecycle that moves from **initiation** through **planning**, **execution**, **release**, and **retrospective improvement**. Work begins by validating the business need, defining success metrics, identifying stakeholders, and producing a one-pager with goals, risks, rough milestones, and resource needs. Once approved, the team shifts into planning by holding a kickoff, building a prioritized backlog, defining acceptance criteria and a Definition of Done, estimating work, and mapping dependencies and release plans.

The documentation defines clear roles across cross-functional delivery. **Project Managers** coordinate schedules, risks, dependencies, meetings, status reporting, and stakeholder communication. **Product Managers** own the problem statement, success metrics, roadmap priorities, and trade-off decisions. **Developers** implement features, contribute to estimation and design, maintain tests and documentation, and surface technical risks. Across all roles, OctoAcme emphasizes customer value, iterative delivery, data-informed decisions, clear ownership, and psychological safety.

Communication and tracking are built into the operating rhythm through recurring cadences—daily or twice-weekly standups, weekly PM/Product alignment, weekly delivery syncs, milestone demos, and monthly stakeholder updates. Project boards (Backlog → Ready → In Progress → In Review → QA → Done) serve as the operational source of truth. Risks and dependencies are maintained in a risk register with owners, likelihood, impact, mitigations, and status, with clear escalation paths when business impact increases.

Quality assurance is treated as part of delivery rather than a final checkpoint. OctoAcme expects unit tests for new logic, integration tests where relevant, smoke tests for critical flows, and security scanning in CI. PR practices reinforce quality through small pull requests, linked issues and acceptance criteria, CI checks before review, and required approvals before merge. After each sprint, release, or major milestone, retrospectives capture what worked, what did not, and which improvement actions to track going forward.

## Process Guides

| Guide | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level lifecycle, principles, roles, key artifacts, and communication cadence |
| [Project Initiation](octoacme-project-initiation.md) | Business validation, stakeholders, one-pager, risk list, and go/no-go gating |
| [Project Planning](octoacme-project-planning.md) | Kickoff, backlog, acceptance criteria, estimation, dependencies, DoD, and release planning |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | Project board workflow, PR expectations, team rhythm, blocker escalation, metrics, and quality/testing practices |
| [Risks and Communication](octoacme-risks-and-communication.md) | Risk register structure, stakeholder communication, templates, and escalation paths |
| [Release and Deployment](octoacme-release-and-deployment.md) | Pre-release checks, deployment checklist, rollback, incident handling, and release notes |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospectives, action items, and continuous improvement |
| [Roles and Personas](octoacme-roles-and-personas.md) | Definitions for Developers, Product Managers, and Project Managers |
