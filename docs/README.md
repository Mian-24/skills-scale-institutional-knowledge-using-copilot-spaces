# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documents. The goal is to give new contributors and team members a single entry point that summarizes how we plan, execute, release, and improve work across projects.

OctoAcme follows a lightweight, stage-gated process that moves work from idea to production through Initiation, Planning, Execution, Release, and Close. Initiatives start with a Project One-pager that captures the problem, goals, success metrics, stakeholders, and a high-level timeline. Planning turns approved work into a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a release plan that maps key milestones and dependencies.

During execution teams use a project board (Backlog → Ready → In Progress → In Review → QA → Done), small PRs, CI checks, and defined review policies to keep changes small and verifiable. Regular rhythms (daily standups, weekly delivery syncs, sprint demos/reviews) surface progress and blockers. Roles are clear — Product Managers define outcomes, Project Managers coordinate delivery and risks, Developers build and test, QA validates acceptance, and stakeholders receive scheduled updates.

Quality and risk controls are built into the lifecycle: developers provide unit and integration tests, critical flows have end-to-end smoke tests, and CI runs security scans. Releases follow a checklist (pre-release requirements, staging verification, automated deployment where possible, and post-deploy checks) with an incident playbook and rollback plan. Retrospectives after sprints, releases, or incidents produce prioritized action items that get tracked back into the backlog.

Docs in this folder:
- octoacme-project-management-overview.md — Project management overview and key artifacts
- octoacme-project-initiation.md — Project initiation guide and one-pager template
- octoacme-project-planning.md — Planning activities, backlog template, and checklists
- octoacme-execution-and-tracking.md — Team rhythm, workflows, and execution checklist
- octoacme-release-and-deployment.md — Release types, deployment checklist, and rollback playbook
- octoacme-retrospective-and-continuous-improvement.md — Retrospective structure and action tracking
- octoacme-risks-and-communication.md — Risk register and stakeholder communication templates
- octoacme-roles-and-personas.md — Roles, responsibilities, and persona usage
