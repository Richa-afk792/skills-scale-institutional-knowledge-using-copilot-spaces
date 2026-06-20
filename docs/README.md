# OctoAcme Project Management — Docs Overview

This folder contains the process documentation for OctoAcme's cross-functional project management approach. The guides here apply to all projects that deliver product features, services, or integrations.
Use this README as the central index for the OctoAcme Project Management Docs.

## Process Overview

OctoAcme's project management lifecycle moves through five phases: **initiation, planning, execution, release, and retrospective**. Initiation validates business need, identifies stakeholders, defines measurable success criteria, and sets a go/no-go decision gate. Planning translates approved goals into a prioritized backlog with acceptance criteria, effort estimates, dependency maps, milestones, and a clear Definition of Done. Execution is iterative — the team builds, tests, reviews, and demos working software in regular increments, guided by a staged project board and PR practices that require linked issues, explicit acceptance criteria, and peer review before merge. Release follows a structured checklist (staging smoke tests, CI and security scan gates, rollback plan, post-deploy verification, and stakeholder announcement), and every sprint, release, or incident closes with a retrospective that converts lessons learned into owned, time-bound action items.

## Roles and Personas

Delivery depends on four core roles working in close collaboration. **Project Managers (PMs)** own coordination, timelines, risk registers, and stakeholder communication. **Product Managers (PdMs)** define outcomes, prioritize the roadmap and backlog, and measure success through data-driven metrics. **Developers** implement and test features, participate in design and code reviews, and surface technical risks early. **QA/Testing contributors** validate acceptance criteria and production readiness before each release. Stakeholders and sponsors provide directional input and approvals throughout. Each project has a named PM and Product Lead to ensure clear ownership and reduce single points of failure.

## Communication and Escalation

OctoAcme uses recurring touchpoints to maintain alignment: twice-weekly standups for the delivery team, a weekly PM–PdM sync, sprint and milestone demos, and monthly stakeholder updates. Status is tracked in a single source of truth (project README or release doc) using a consistent weekly template that covers progress, next steps, risks and blockers, and decisions needed. Escalation paths are explicit — issues are triaged at the team level first, then escalated to the PM, Product Lead, and sponsor as business impact increases. Security incidents follow a dedicated runbook and immediately notify the Security on-call. Incident communications include a triage summary, actions being taken, expected timeline, and a scheduled blameless retrospective.

## Quality Assurance and Release Readiness

Quality is built into every phase rather than added at the end. During execution, all PRs require passing CI checks (linting and automated tests) and linked acceptance criteria before merge. Pre-release requirements include passing CI and security scans, all acceptance criteria met, release notes drafted, smoke tests prepared, and a documented rollback or mitigation plan. Deployment follows a checklist: staging verification, automated production pipeline, post-deploy verification, and a stakeholder announcement. If a deployment causes a critical issue, the team triggers incident response, rolls back to the last known-good release if necessary, and captures root-cause action items. Retrospectives after each sprint or release reinforce continuous improvement by turning observations into concrete, trackable next steps.

## Document Index

| Document | Description |
|---|---|
| [octoacme-project-management-overview.md](octoacme-project-management-overview.md) | High-level principles, roles, artifacts, and lifecycle |
| [octoacme-project-initiation.md](octoacme-project-initiation.md) | Initiation phase — problem statement, stakeholders, go/no-go |
| [octoacme-project-planning.md](octoacme-project-planning.md) | Planning phase — backlog, estimates, milestones, Definition of Done |
| [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md) | Execution — project board, standups, PR practices, iteration demos |
| [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md) | Risk register, escalation paths, communication templates |
| [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md) | Release checklist, deployment pipeline, rollback playbook |
| [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md) | Retrospective format and continuous improvement practices |
| [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) | Detailed persona definitions for PM, PdM, Developers, and QA |
