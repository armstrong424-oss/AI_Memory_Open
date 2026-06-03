# Next Steps — AI Memory System (Root Level)

> **SCOPE:** This file tracks pending work on the **AI Memory system itself** — its structure, standards, policies, shared resources, and cross-project infrastructure. This is NOT a project-level file. Project-specific next steps live in each project's own `NextSteps.md`.

**Last Updated:** 2026-06-03

---

## Priority Queue

### High Priority

1. **Advance FunctionalWellnessHybrid staging** — Owner-review the three drafts in `projects/staging/FunctionalWellnessHybrid/Master-Context.md`, validate assumptions (RCM baseline, APCM/RPM-eligible count, willingness-to-pay, device terms), then promote via `PROJECT_MEMORY_INIT.md`.
2. **Push to git** — Run `git add . && git commit && git push origin main` to persist setup + the staged project (Cowork sandbox cannot push automatically).

### Medium Priority

1. **Configure enterprise OS** — Deferred during setup. Decide CRM/PM/finance platform (Zoho One has a pre-built connector at `zoho-mcp-server/`) and add credentials to `SammyKeys.txt`.
2. **Add API keys** — Populate `SammyKeys.txt` with GitHub and Claude/Anthropic keys; add other platforms as adopted.
3. **Create contact profiles** — Add key people to `contacts/` (e.g., Dr. Chandra Armstrong MD, NP Tanisha Williams, Citizens Trust Bank contact, billing vendor, LCSW) using `_PROFILE-TEMPLATE.md`.

### Low Priority

*(populated during sessions)*

---

## Recently Completed

| Item | Date | Notes |
|------|------|-------|
| Ran `setup-AI-Memory.md` (first-time initialization) | 2026-06-03 | Owner=SammyD, Org=Chandra Britt Armstrong MD LLC, repo=armstrong424-oss/AI_Memory_Open, primary AI=Claude, standards=as-is, enterprise OS=deferred. |
| Staged FunctionalWellnessHybrid (`staging.md`) | 2026-06-03 | Whole-practice hybrid transformation; $1M anchor; 18 advisors activated (36 files); Documents 1–3 drafted; 9 epics, 6 milestones, risk register. |

---

*This is a root-level system file. It tracks work on the AI Memory system, NOT individual projects.*
