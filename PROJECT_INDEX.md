# Project Master Index — Haddy888

**Purpose:** A single portfolio index for software, business systems, technical research, and supporting documents associated with the Haddy888 GitHub account.

**Status legend**
- **Verified repository** — repository exists and relevant contents have been inspected.
- **Repository known; contents unverified** — repository is known, but its current tree has not been fully inspected.
- **Planning/workstream record** — project is known from project planning or conversation; a matching pushed repository has not yet been verified.
- **Needs reconciliation** — confirm whether work exists in another repository, branch, local workspace, or document export.

**Last inventory note:** Initial hub bootstrap. This is not yet a complete crawl of all repositories, branches, historical commits, releases, or GitHub assets.

## A. Project register

| ID | Project / workstream | Scope | Known repository / entry point | Status |
|---|---|---|---|---|
| BH-001 | Brain Host | AI workforce / virtual company; expert and skill registry; department cells; orchestration; persistence; decision intelligence; auditability; human command center | [brain_host](https://github.com/Haddy888/brain_host) | Repository known; contents/access need verification |
| BH-002 | Brain Host Business Operating System (BH-BOS) | Venture engine, business architecture cell, operate/maintain, sales and marketing AI cell, governed handoffs | [Haddy888 repositories](https://github.com/Haddy888?tab=repositories) — locate canonical repo | Planning/workstream record; needs repository mapping |
| GOV-001 | CTEP / Human Control Gateway | Non-bypassable authenticated human approval before final authorization; evidence sufficiency, contradiction checks, audit trail | [Haddy888 repositories](https://github.com/Haddy888?tab=repositories) | Planning/workstream record; needs repository mapping |
| SEC-001 | Sentinel | Website security/performance auditing, monitoring, browser automation, evidence and reporting | [Haddy888 repositories](https://github.com/Haddy888?tab=repositories) | Planning/workstream record; needs repository mapping |
| CT-001 | Chosen Technology website | Corporate site, interactive landing experience, services, contact/conversion flows, SEO and deployment foundation | [ChosenTech-website-prepublish](https://github.com/Haddy888/ChosenTech-website-prepublish) | Known repository; audit all files and branches |
| CT-002 | Chosen Technology MSP operations | Service delivery, recruiting, field technicians, contractor documentation, onboarding and operational workflows | [Haddy888 repositories](https://github.com/Haddy888?tab=repositories) | Planning/workstream record; needs repository mapping |
| HUB-001 | Business Project Hub | Central project index and inventory | [business-project-hub](https://github.com/Haddy888/business-project-hub) | Verified repository; hub initialized by this index |
| TECH-001 | Hardware data-path research | Transmission, storage, retention, read/write paths, OS constraints and hardware-level capabilities | [Haddy888 repositories](https://github.com/Haddy888?tab=repositories) | Research/workstream record; repository not identified |
| TECH-002 | Psiphon CLI configuration | CLI setup/configuration and troubleshooting notes | [Haddy888 repositories](https://github.com/Haddy888?tab=repositories) | Workstream record; repository not identified |
| OPS-001 | SSDI application packet | Application checklist and supporting documentation workflow | [Haddy888 repositories](https://github.com/Haddy888?tab=repositories) | Document workstream; not assumed to be code |
| OPS-002 | Minnesota GRH / Housing Support research | Independent-apartment research, contact lists and application process | [Haddy888 repositories](https://github.com/Haddy888?tab=repositories) | Research workstream; repository not identified |
| OPS-003 | Business funding plan | $50,000 new-business funding strategy, NDC / Minnesota DEED credit enhancement, project and working-capital narrative | [Haddy888 repositories](https://github.com/Haddy888?tab=repositories) | Business-planning workstream; repository not identified |
| SKILL-001 | Skills/resume/testing workflow | Skill inventory, resume, coding screenings and browser integration exploration | [Haddy888 repositories](https://github.com/Haddy888?tab=repositories) | Workstream record; repository not identified |

## B. Known repositories

| Repository | Visibility / state at initial check | Entry point | Next action |
|---|---|---|---|
| business-project-hub | Public; initially empty; default branch `main`; owner has push/admin permissions | [Repository](https://github.com/Haddy888/business-project-hub) | Use as central index; keep links to canonical source repositories |
| ChosenTech-website-prepublish | Public repository previously identified with website source | [Repository](https://github.com/Haddy888/ChosenTech-website-prepublish) | Inspect complete tree, branches, commit history, assets, dependencies, and build instructions |
| business-project-hub1 | Private repository previously identified; root appeared to have a README | [Repository](https://github.com/Haddy888/business-project-hub1) | Inspect via authenticated access; determine whether it duplicates or contains portfolio material |
| brain_host | Previously identified as a project repository; current access/content not confirmed during initial index setup | [Repository](https://github.com/Haddy888/brain_host) | Verify repository existence, permissions, branches and full tree |

Repository visibility and content can change. Re-check GitHub before treating this initial inventory as current.

## C. Required source-code audit

For every repository accessible to the account, capture:

- Canonical repository URL, description, visibility, default branch, archived status
- All branches and tags/releases
- Latest commit SHA and timestamp per branch
- Recursive file tree, path, extension, byte size, and blob SHA where available
- Source-code entry points and project language/framework
- Build/test/run instructions and dependency manifests
- Documentation, specifications, diagrams, images, fonts, and other assets
- CI/CD workflows, deployment configuration, infrastructure-as-code
- Git submodules and Git LFS references
- Secrets scan status (never copy secret values into the index)
- Files deleted/renamed in history when historical recovery is requested
- Export/backup status and last verification date

## D. Governance and integrity requirements

For Brain Host, CTEP, and connected systems, preserve the established governance hierarchy:

**Constitution → Master Specification → Invariants → Domain Contracts → Subsystems → Work Orders → Tests → Production Release**

Mandatory control: no workflow, component, agent, API, or test may reach final authorization for a consequential action without an explicit, authenticated human approval event. Verification may assess evidence, contradictions, and confidence; it must not replace the required human approval.

## E. Next steps

1. Audit every repository under [Haddy888](https://github.com/Haddy888?tab=repositories), including private repositories accessible to the authorized GitHub connection.
2. Generate a recursive file manifest for every branch and tag.
3. Map project IDs above to canonical repositories and mark duplicates/forks.
4. Identify specifications or code that exist only in local files or conversation drafts.
5. Produce a downloadable archive/export for each repository, where supported, and record checksums.
6. Update this index only after evidence is collected; keep unknowns explicitly marked.

## F. Related files

- [Repository Inventory](REPOSITORY_INVENTORY.md)
- [File Manifest Template](FILE_MANIFEST_TEMPLATE.csv)
