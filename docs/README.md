# OctoAcme — Project Management Processes

OctoAcme runs projects using a lightweight, iterative lifecycle that moves work from initiation through planning, execution, release, and continuous improvement. New efforts begin with a Project One-pager to capture the problem, measurable goals, stakeholders, and success metrics. Approved initiatives are broken into prioritized backlogs, estimated, and planned into shippable increments; teams hold a kickoff to align scope, dependencies, and a release plan.

Roles and responsibilities are clearly defined to ensure accountability: Product Managers (PdM) own outcomes and prioritization, Project Managers (PM) coordinate delivery and communication, Developers implement and test, and QA validates acceptance criteria and release readiness. Key artifacts include the Project One-pager, release plan and roadmap, backlog with acceptance criteria, risk register, and retrospective notes. Every project should name a PM and Product Lead and surface action items in the backlog with owners and due dates.

Communication is structured and frequent: daily standups to surface progress and blockers, weekly delivery syncs for progress and risks, demo/review sessions at the end of sprints or milestones, and regular stakeholder updates. Use a single source of truth (project README or release doc) for status; adopt the provided weekly status template and follow established escalation paths (Team → PM → Product Lead → Sponsor). Security incidents follow the security incident runbook and notify Security on-call.

Quality assurance and release practices emphasize CI, observability, and low-risk deployments. Pull requests should be small, CI-verified, and include acceptance criteria before review. Automated unit, integration, and security scans run in CI; end-to-end smoke tests and manual QA are used as needed. Releases follow a checklist (staging verification, rollback plan, release notes) and use the incident playbook to rollback and capture post-incident action items. Retrospectives capture learnings and convert them into backlog action items for continuous improvement.

Quick links
- Project initiation: octoacme-project-initiation.md
- Planning: octoacme-project-planning.md
- Execution & tracking: octoacme-execution-and-tracking.md
- Roles & personas: octoacme-roles-and-personas.md
- Onboarding checklist: octoacme-onboarding-checklist.md
- Risk & communication: octoacme-risks-and-communication.md
- Release & deployment: octoacme-release-and-deployment.md
- Retrospectives: octoacme-retrospective-and-continuous-improvement.md
