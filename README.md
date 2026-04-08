# ADB.js Project Roadmap

This repository tracks the proposal and RFC process for [ADB.js](https://github.com/adbjs/adb.js). It is the place to suggest new features, follow accepted proposals, and contribute to the direction of the project.

### Overview

- [Proposal Process](#proposal-process)
  - [Stage 1 — Discussion](#stage-1--discussion)
  - [Stage 2 — Accepted Proposal](#stage-2--accepted-proposal)
  - [Stage 3 — RFC](#stage-3--rfc)
- [Templates](#templates)
- [Contributing](#contributing)

## Proposal Process

All significant changes to ADB.js go through a structured three-stage process before implementation. This ensures that ideas are well-defined, discussed openly, and technically sound before any code is written.

### Stage 1 — Discussion

Anyone in the community can propose a new feature or improvement by opening a GitHub Discussion. This is the starting point for all ideas, regardless of size or complexity.

A Stage 1 proposal should describe the problem clearly and define the goals, without committing to a specific solution. Well-scoped goals often lead to better solutions than those that start with an implementation in mind.

[Start a new proposal →](https://github.com/adbjs/roadmap/discussions/new)

### Stage 2 — Accepted Proposal

Once a discussion gains traction and is deemed worth pursuing, a maintainer will open a GitHub Issue using the accepted proposal template. This signals that the problem is acknowledged and that the project is open to a formal solution.

Stage 2 is reserved for ADB.js maintainers. Community members who want to move a discussion forward should advocate for it in the original thread.

### Stage 3 — RFC

An accepted proposal moves to Stage 3 when a champion writes a formal RFC (Request for Comments) and opens a Pull Request. The RFC describes the detailed design, behavior, testing strategy, drawbacks, and adoption plan.

To submit an RFC, create a new file at `proposals/${id}.md` using the Stage 3 template, where `${id}` matches the GitHub Issue number from Stage 2.

[Submit an RFC →](https://github.com/adbjs/roadmap/pulls)

---

## Templates

The following templates are available to guide contributors through each stage of the process.

| Stage | File | Purpose |
|-------|------|---------|
| Stage 1 | `stage-1--discussion-template.md` | Starting point for new proposals |
| Stage 2 | `stage-2--issue-template.md` | Accepted proposal (maintainers only) |
| Stage 3 | `stage-3--rfc-template.md` | Formal RFC for implementation |

---

## Contributing

Community contributions are welcome at Stage 1 and Stage 3. If you have an idea, open a discussion. If a proposal has been accepted and you want to champion it, write the RFC and open a Pull Request.

Please keep proposals focused on problems rather than solutions, especially in the early stages. A clearly defined problem is more valuable than a premature implementation.

For questions about the process, open a discussion rather than an issue.
