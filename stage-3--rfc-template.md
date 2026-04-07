<!--
  This template is for RFCs that have been approved and are actively being implemented.
  If you are proposing a new idea, begin with a GitHub Discussion instead.
  See https://github.com/adbjs/roadmap for details on the RFC process.

  To use this template: create a new file at `proposals/${id}.md` where `${id}`
  matches the official proposal ID from the accepted GitHub Issue.
-->

> [!NOTE]
> For feedback on experimental features, comment on the Stage 3 PR. For all other feedback, use the Stage 2 Issue linked below.

- Start Date: <!-- YYYY-MM-DD -->
- Reference Issues: <!-- related issues, if any -->
- Implementation PR: <!-- leave empty until a PR exists -->
- Stage 2 Issue: <!-- required -->
- Stage 3 PR: <!-- leave empty until a PR exists -->

---

# Summary

One or two sentences describing what this RFC proposes and why it matters.

---

# Background & Motivation

Describe the problem this RFC addresses. What is painful or impossible to do in ADB.js today, and why does it need to be solved now? Keep this section focused on the problem, not the solution. A concrete user scenario helps ground the discussion.

# Goals

What this RFC is trying to accomplish, stated independently from the proposed solution:

- Goal one
- Goal two
- Goal three

# Non-Goals

What is intentionally out of scope for this RFC. This helps readers understand the boundaries of the proposal and prevents scope creep during review.

- Non-goal: something that will not be addressed here
- Out-of-scope: something related but deliberately excluded
- Future: something that may be addressed in a follow-up proposal

This section may be left empty if there are no meaningful exclusions to call out.

---

# Detailed Design

This is the core of the RFC. Write at a level of detail that allows someone familiar with ADB.js to understand the proposal fully, and someone familiar with the codebase to implement it. Cover the following as applicable:

**Behavior.** Describe exactly what the feature does, including edge cases and failure modes. If behavior depends on configuration or environment, make that explicit.

**New concepts.** Define any new terminology introduced by this proposal. Do not assume familiarity with concepts that are not already part of ADB.js.

**Interactions with existing features.** Explain how this proposal interacts with other parts of ADB.js, including any constraints or dependencies.

> Replace this block with the actual design. It should be thorough enough that a reviewer can identify gaps and an implementer can begin work without significant ambiguity.

---

# Testing Strategy

Describe how the implementation will be verified. Will this require unit tests, integration tests, end-to-end tests, or some combination? Call out any particularly important test cases, including edge cases that are easy to miss.

---

# Drawbacks

Why should this RFC not be implemented? Consider the implementation cost in terms of code complexity, the risk of confusing new users, the friction of migrating existing applications, and whether the feature could reasonably be built in userspace instead. Identifying real tradeoffs here strengthens the proposal.

---

# Alternatives

What other approaches were considered? What happens if this RFC is not accepted? Describe the alternatives and explain why the proposed design was preferred over them.

---

# Adoption Strategy

Address how this change lands for existing ADB.js users:

- Is this a breaking change? If so, what is the migration path?
- Can a codemod automate the migration?
- Does this affect libraries or integrations in the ADB.js ecosystem?
- What documentation or guides will be needed?

---

# Unresolved Questions

List any open questions that remain at the time of writing. These are items where the design is still uncertain and input from reviewers is particularly welcome.
