# OctoAcme Project Management Docs — README

Welcome — this folder collects OctoAcme’s project management process documentation and provides a concise summary of how we run projects.

OctoAcme uses an iterative, data‑informed lifecycle with clear gates: Initiation (one‑pager and stakeholder alignment), Planning (kickoff, prioritized backlog, estimates, Definition of Done), Execution (small increments, PRs, CI, reviews), Release (deploy, verify, announce), and Close/Retrospective (capture learnings and actions). The approach emphasizes delivering small, shippable increments, measuring outcomes, and using evidence to guide prioritization and improvement.

Work is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and managed through a disciplined PR process: small PRs linked to issues with acceptance criteria, automated CI (tests, linting, security) before review, and at least one approval policy. Teams follow a regular cadence — daily standups for blockers and progress, weekly delivery syncs and PM/PdM alignment, milestone demos, and monthly stakeholder updates — with templates for status and incident communications to keep messages consistent.

Quality and risk management are built into the pipeline: unit/integration/e2e smoke tests, security scanning, release checklists (pre‑release verification, rollback plan), and an incident playbook. Retrospectives after sprints, releases, or incidents convert learnings into prioritized action items tracked in the backlog. Core roles include Project Manager (delivery coordination), Product Manager (outcomes & prioritization), Developers (implement & test), QA (validation), and Stakeholders (inputs & approvals).

Reference docs in this folder:
- octoacme-project-management-overview.md
- octoacme-project-initiation.md
- octoacme-project-planning.md
- octoacme-execution-and-tracking.md
- octoacme-risks-and-communication.md
- octoacme-release-and-deployment.md
- octoacme-retrospective-and-continuous-improvement.md
- octoacme-roles-and-personas.md

How to use:
- Keep the Project One‑pager and key artifacts in the project repo and link from these docs.
- Use these pages as the canonical process reference and update via the `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` flow when you propose changes.
