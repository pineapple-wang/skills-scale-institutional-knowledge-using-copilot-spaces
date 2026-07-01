# OctoAcme Project Management Docs

Welcome! This directory contains living documentation for OctoAcme project management. The aim is to help all team members understand, use, and evolve our shared processes.

## Summary: OctoAcme Project Management Processes

OctoAcme operates a structured yet iterative project management framework built on five core principles: **customer-first delivery**, **iterative increments**, **clear ownership**, **data-informed decisions**, and **psychological safety**. 

The organization defines clear roles—Project Manager (PM), Product Manager (PdM), Developers, QA/Testing, and Stakeholders—each with distinct responsibilities that work together across a well-defined lifecycle. Projects move through five phases: **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with acceptance criteria), **Execution** (building and testing with daily standups and weekly demos), **Release** (deploying to production with rollback plans), and **Retrospective** (capturing learnings for continuous improvement). This structured approach is anchored by lightweight but comprehensive artifacts like the Project One-pager, Risk Register, and Sprint Backlog.

Communication is woven throughout OctoAcme's process with a deliberate cadence designed to maintain alignment without creating excessive meetings. The team rhythm includes daily 15-minute standups focused on progress and blockers, weekly delivery syncs showing progress and flagged risks, and sprint-end demos or reviews. Beyond internal team communication, stakeholder updates occur monthly or at milestone boundaries, with escalation paths defined at three levels: team-level triage, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues. A single source of truth—typically the project README or release documentation—ensures consistent, transparent status across the organization.

Quality assurance and execution rigor are non-negotiable in OctoAcme's workflow. The team uses GitHub Projects for tracking work through columns (Backlog, Ready, In Progress, In Review, QA, Done), enforces small Pull Requests (≤400 lines when possible), and requires at least one approval before merging. Quality gates include unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance. Pre-release requirements mandate passing CI and security scans, drafted release notes, and documented rollback plans. Metrics tracking—including velocity, burndown, and dashboards for errors and latency—provides visibility into project health and informs mid-course corrections.

Finally, OctoAcme embeds continuous improvement into its culture through structured retrospectives held after each sprint, release, or milestone. Retros follow a consistent format (what went well, what could improve, action items with owners and due dates), are timeboxed to 45–75 minutes, and prioritize 2–3 top improvements to prevent overload. Action items are added to the project backlog with clear success criteria and tracked during weekly PM syncs. This approach transforms tacit team insights into documented, versioned processes—exactly as reflected in the living process documentation stored in this directory.

## Process Docs Index

Navigate to any of these guides to dive deeper into specific project management activities:

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, key artifacts, and lifecycle
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Validate business need, align stakeholders, and make the go/no-go decision to move into planning
- **[Project Planning](./octoacme-project-planning.md)** — Break work into shippable increments, estimate scope, identify dependencies, and create release plans
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day delivery, run sprints, track progress, and escalate blockers
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify and monitor risks, communicate status to stakeholders, and escalate issues
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardize release processes, deployment checklists, rollback procedures, and release notes
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings after sprints/releases and convert them into actionable improvements
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Detailed descriptions of typical roles (Developers, Product Managers, Project Managers) and their responsibilities

## How to Use This Documentation

- **New team members**: Start with the [Project Management Overview](./octoacme-project-management-overview.md) for context, then explore docs relevant to your role
- **Project kickoff**: Reference the [Project Initiation Guide](./octoacme-project-initiation.md) and [Project Planning](./octoacme-project-planning.md)
- **During execution**: Lean on [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Before/during release**: Use [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- **After milestones**: Run a retrospective using [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## Contributing to These Docs

These are **living documents** meant to evolve as the organization learns and improves. To suggest updates or add new content:

1. Open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
2. Describe the gap, rationale, and suggested content
3. Work with stakeholders to validate and refine
4. Update the relevant doc(s) and link back to the issue

---

*Last updated: July 2026*  
*For questions or suggestions, please open an issue or reach out to the Project Management team.*
