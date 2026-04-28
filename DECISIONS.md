# Decision Log

---

## Parallel sub-agents

**Date:** 2026-04-28
**Question:** Should the wizard or the work sessions use parallel sub-agents?
**Decision:** No — for now.

**Reasoning:**

- Wizard flow is approval-gated. STEP_3 (skill file generation) is the only candidate for parallelism, but only pays off at 8+ skill files. Not a proven pain point yet.
- Work sessions are one-task-per-session by design. Single task = usually single domain = no parallelism needed.

**When to revisit:**
If a "project health scan" or similar multi-domain feature is added — that's the natural first use case for parallel agents.

**Action:** None until there's a real problem to solve.
