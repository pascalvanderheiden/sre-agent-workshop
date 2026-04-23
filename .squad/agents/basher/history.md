# Basher — History

## Core Context

- **Project:** A hands-on workshop introducing Azure SRE Agent capabilities within AKS through guided scenarios and Bicep infrastructure
- **Role:** Tech Writer
- **Joined:** 2026-04-12T08:49:21.228Z
- **Note (2026-04-23):** Container image in GHCR must be public for the workshop to work end-to-end; `publish-image.yml` pushes to ghcr.io but attendees' forks must sync upstream and publish their own images publicly

## Completed Work (Core Summary)

**All workshop modules authored and published:**
- Modules 0–7 complete: Prerequisites, Deploy Infrastructure, Deploy Application, Onboard SRE Agent, Configure Incident Response, Break It (fault injection), Watch SRE Agent, Cleanup
- Architecture: 7 sequential 20–30 min modules guiding attendees through IaC deployment, workload identity setup, incident response automation, and fault injection scenario
- Key design: Workload identity authentication chain emphasized early (Module 1) as foundation for understanding Module 5 fault; `/health` independence from DB highlighted to teach observability
- Narrative tension maintained throughout: clear "before" state (Module 2), deliberate break (Module 5), investigation/remediation (Module 6), cleanup (Module 7)
- All guides use consistent tone (direct, step-by-step) with realistic curl commands, expected outputs, and self-service troubleshooting sections
- Cost transparency emphasized: $1/hr runtime cost in Prerequisites, Module 7 cleanup for budget management
- "What You Accomplished" section in Module 7 celebrates the full incident response workflow and AI-assisted debugging

## Learnings (Archived Sessions)

**Archived detailed session logs from 2026-04-12:** See `docs/00-prerequisites.md` through `docs/07-cleanup.md` for full implementation context. Session notes documented:
- Module structure and key content for each guide (Modules 0–7)
- Design decisions for workshop flow, narrative tension, participant fork model, cost awareness, and observability teaching
- Key file paths and resource references for each module
- Troubleshooting and verification steps embedded in each guide
