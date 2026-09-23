# bAIble v2

**A public, portable governance and learning framework for AI collaboration.**

bAIble helps a human and one or more AI agents work together without treating fluent output as proof. It defines how to understand a task, classify uncertainty, act within scope, verify results, preserve project memory, and learn from failures.

## Start here

New to this? Start with [START_HERE.md](START_HERE.md), then [ONBOARDING_FLOW.md](ONBOARDING_FLOW.md).

Core references:
- [BIBLE.md](BIBLE.md) — principles and guardrails.
- [BOOTSTRAP.md](BOOTSTRAP.md) — create a workspace.
- [NEW_USER_AGENT.md](NEW_USER_AGENT.md) — beginner-agent contract.
- [PUBLIC_PRIVATE_BOUNDARY.md](PUBLIC_PRIVATE_BOUNDARY.md) — publication boundary.
- [REALITY_CHECK.md](REALITY_CHECK.md) — evidence checkpoint.
- [VERIFICATION_RECORD.md](VERIFICATION_RECORD.md) — verification record.
- [HANDOFF.md](HANDOFF.md) — transfer work safely.
- [WORKSPACE_TEMPLATE/](WORKSPACE_TEMPLATE/) — reusable project records.

## Core cycle
UNDERSTAND → CLASSIFY → PLAN → ACT → VERIFY → REALITY CHECK → LEARN → PERSIST

A result is not complete merely because it looks convincing. Evidence, scope, verification, and uncertainty remain visible.

## Optional layers
- **bAIble** — governance, evidence, verification, learning.
- **rAIda** — orchestration and coordination.
- **UnAiversed** — relational context.
- **Integration layer** — project-specific execution/integration infrastructure.
- **Watchdog** — monitoring/detection.
- **Reality Check** — cross-cutting verification.

These are portable concepts, not mandatory packages. Start with Human → Agent → bAIble → Project and add layers only when a demonstrated problem requires them.

See [RUNTIME_AND_WATCHDOG.md](RUNTIME_AND_WATCHDOG.md) for the public construction contract. The repository deliberately does **not** contain a private runtime implementation.

## Public by design
This repository is public and must remain usable without private conversation history or access to another person's projects.

Do not publish credentials, personal identifiers, private conversations, private repository contents, confidential/customer data, hidden context, internal access paths, private run evidence, or claims that depend on inaccessible sources.

See [PUBLIC_PRIVATE_BOUNDARY.md](PUBLIC_PRIVATE_BOUNDARY.md).

## Status vocabulary
- **VERIFIED** — directly supported by accessible evidence.
- **ESTABLISHED** — repeatedly documented or observed with relevant limitations.
- **EXPERIMENTAL** — currently being tested.
- **PROPOSED** — design idea awaiting validation.
- **PRIVATE** — intentionally excluded from this public repository.

See [STATUS_TRANSITIONS.md](STATUS_TRANSITIONS.md).

## Reality Check
Ask:
- What do we know?
- What is the source?
- What are we inferring?
- What remains unknown?
- What alternative explanation matters?
- What would falsify the conclusion?
- What has actually been verified?

**Reality outranks the document.**
