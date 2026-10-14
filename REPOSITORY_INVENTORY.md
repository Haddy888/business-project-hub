# GitHub Repository Inventory — Haddy888

This is the initial known-repository list, not yet a complete account-wide enumeration.

| Repository | URL | Initial state | Audit status |
|---|---|---|---|
| business-project-hub | https://github.com/Haddy888/business-project-hub | Public, default branch main, size 0 before hub bootstrap | Index initialized; full tree audit pending |
| ChosenTech-website-prepublish | https://github.com/Haddy888/ChosenTech-website-prepublish | Public; website source previously identified | Full recursive audit pending |
| business-project-hub1 | https://github.com/Haddy888/business-project-hub1 | Private; README observed at root in a prior check | Authenticated full audit pending |
| brain_host | https://github.com/Haddy888/brain_host | Previously identified; current content/access unconfirmed | Verify access, repository identity, branches and files |

## Audit procedure

For each accessible repository:

1. Read repository metadata.
2. Enumerate all branches and tags.
3. Fetch recursive Git tree for each branch.
4. Record paths, blob SHAs, sizes, and file types.
5. Identify source entry points and build/test commands.
6. Review commit history and releases.
7. Export/archive repository contents and calculate a checksum.
8. Update this inventory and the Project Master Index with the audit date and latest commit SHA.

Do not record credentials or secret values. Use links to canonical repositories rather than copying code into this hub unless a deliberate migration is approved.
