# Next Steps — AI Memory System (Root Level)

> **SCOPE:** This file tracks pending work on the **AI Memory system itself** — its structure, standards, policies, shared resources, and cross-project infrastructure. This is NOT a project-level file. Project-specific next steps live in each project's own `NextSteps.md`.

**Last Updated:** 2026-06-03

---

## Priority Queue

### High Priority

1. **Stage your first project** — Run `staging.md`. The obvious candidate is the CBA clinic transition (insurance-dependent → hybrid cash-based functional wellness). Could also be staged as separate projects (e.g., clinic operations, the non-profit fall-prevention org, a billing/RCM cleanup workstream).
2. **Push setup to git** — Run `git add . && git commit && git push origin main` to persist initialization (Cowork sandbox cannot push automatically).

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

---

*This is a root-level system file. It tracks work on the AI Memory system, NOT individual projects.*
