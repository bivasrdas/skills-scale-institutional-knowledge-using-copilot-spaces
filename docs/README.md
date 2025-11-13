# OctoAcme Project Management Documentation

## Overview

This docs folder serves as the central repository for OctoAcme's project management processes, workflows, and team knowledge. The goal of maintaining these docs in a Copilot Space is to centralize our process documentation, streamline onboarding for new team members, and maintain versioned team knowledge that evolves with our practices. By keeping these documents accessible and up-to-date, we enable anyone on the team to quickly understand our approach to running projects, from initiation through retrospectives.

## Project Management at OctoAcme

OctoAcme follows an iterative, customer-first approach to project delivery. We use a project board (e.g., GitHub Projects) to manage work through columns like Backlog, Ready, In Progress, In Review, QA, and Done. Our PR workflow emphasizes small, reviewable changes (<= 400 lines when possible) with clear issue links, automated CI checks, and at least one approval before merging. Sprint planning operates within agreed timeboxes, pulling items with clear acceptance criteria and respecting team capacity. Each project has defined roles—Project Manager (PM) coordinates delivery and risk, Product Manager (PdM) defines outcomes and prioritizes the backlog, Developers implement features, QA validates quality, and Stakeholders provide input and approvals.

Communication happens through multiple cadences: daily standups (15 minutes) focus on progress and blockers, weekly syncs between PM and PdM track delivery and risks, and monthly stakeholder updates maintain alignment. For escalations, we follow a tiered approach—team-level triage in standups, PM escalation to Product Lead for cross-team dependencies, and sponsor-level escalation for business-impacting issues. Security incidents follow a dedicated runbook with on-call notification.

Quality assurance is built into every stage of delivery. We require unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before release. CI gates include automated tests, linting, and security scans before code can merge. Releases follow a checklist that includes passing CI, drafted release notes, documented rollback plans, and smoke tests. If a deployment fails or causes a critical issue, we trigger incident response, rollback to the last known-good release if necessary, and conduct a blameless retrospective to capture learnings and action items.

## Docs Directory

- [octoacme-project-management-overview.md](octoacme-project-management-overview.md) — High-level introduction to OctoAcme's project management principles, roles, and lifecycle
- [octoacme-project-initiation.md](octoacme-project-initiation.md) — Guidance for validating project ideas and creating initial project one-pagers
- [octoacme-project-planning.md](octoacme-project-planning.md) — How to turn approved initiatives into actionable plans with backlogs, estimates, and timelines
- [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md) — Day-to-day execution guidance including team rhythm, workflows, and quality practices
- [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md) — Risk management, stakeholder communication, and escalation paths
- [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md) — Release standards, deployment checklists, and rollback procedures
- [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md) — How to run retrospectives and track improvement action items
- [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) — Detailed role definitions and responsibilities for team personas

## How to Contribute

We welcome improvements and updates to these process docs. To propose changes:

1. Use the [Add Content to Project Management Process Docs](./../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to submit your proposal
2. Describe what you'd like to add or update, why it's needed, and provide suggested content when possible
3. Submit small, focused PRs that are easy to review and discuss
4. Ensure your updates align with existing process docs and improve clarity

All changes to process documentation should be reviewed to maintain consistency and quality across our knowledge base.
