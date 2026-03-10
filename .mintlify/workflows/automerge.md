---
name: Update changelog
on:
  cron: "0 9 * * 1"
context:
  - repo: shells-company/shells-code
automerge: true
---

Review all changes since the last changelog update. Draft a new changelog post with any new features, bug fixes, or breaking changes.

Include information about what a change is and how it affects users.

Do not include any internal-only information or minor changes like bumping package versions or updating documentation.

Success criteria: Someone who reads the changelog knows the most up to date information about the product including what changed and whether or not it affects them.
