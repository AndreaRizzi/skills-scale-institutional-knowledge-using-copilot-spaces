# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management documentation hub. This directory centralizes OctoAcme's standardized processes and guidance for planning, executing, and delivering projects. Use these docs to onboard, run, and continuously improve projects with a consistent, repeatable approach.

## Overview of our approach

OctoAcme follows a customer-first, iterative delivery model with clear ownership, data-informed decisions, and psychological safety. Projects begin with a concise Project One-pager to validate the business need and success metrics, then move into planning where work is broken into shippable increments with acceptance criteria and a Definition of Done. Execution is organized on a project board with a pull-request-first development flow, CI gating, and explicit QA and release steps. After delivery, retrospectives capture learnings and feed prioritized action items back into the backlog.

## Key workflows and practices

- Initiation → Planning → Execution → Release → Retrospective: the high-level lifecycle used across OctoAcme.
- Project board columns: Backlog, Ready, In Progress, In Review, QA, Done.
- Pull Request workflow: small PRs, include issue link and acceptance criteria, run CI and security checks, require at least one approval before merging.
- Quality assurance: unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA as needed.
- Risk management: maintain a lightweight Risk Register and escalate via the defined path (team → PM → Product Lead → Sponsor).

## Quick navigation by role

- Project Managers
  - Start: docs/octoacme-project-management-overview.md
  - Then: docs/octoacme-project-initiation.md → docs/octoacme-project-planning.md → docs/octoacme-execution-and-tracking.md
- Product Managers
  - Start: docs/octoacme-project-management-overview.md
  - Focus: docs/octoacme-project-initiation.md and docs/octoacme-project-planning.md
- Developers
  - Start: docs/octoacme-execution-and-tracking.md
  - Reference: docs/octoacme-roles-and-personas.md

## Documentation index

| Document | Purpose | When to Use |
|----------|---------|-------------|
| docs/octoacme-project-management-overview.md | Introduction to OctoAcme's framework, roles, artifacts | Onboarding, project setup |
| docs/octoacme-project-initiation.md | Steps to validate and authorize work, align stakeholders | New project ideas or feature proposals |
| docs/octoacme-project-planning.md | Turn approved initiative into a plan and prioritized backlog | After approval, before execution |
| docs/octoacme-execution-and-tracking.md | Day-to-day execution, progress tracking, QA practices | During delivery |
| docs/octoacme-risks-and-communication.md | Risk register, communications templates, escalation | Throughout the lifecycle |
| docs/octoacme-release-and-deployment.md | Release types, pre-release requirements, rollback | Before and during releases |
| docs/octoacme-retrospective-and-continuous-improvement.md | Capture learnings and convert into action | After sprints, releases, incidents |
| docs/octoacme-roles-and-personas.md | Role definitions and responsibilities | Understanding who does what |

## Contributing to process docs

To request updates or add new content, use the repository process doc issue template:
.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml

## Acceptance criteria for this README

- Content aligns with existing process docs
- Improves discoverability and onboarding
- Links to every process doc in docs/
