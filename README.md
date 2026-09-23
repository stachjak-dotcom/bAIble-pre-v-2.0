# bAIble pre-v2

**A portable governance and learning framework for AI collaboration.**

bAIble helps a human and one or more AI agents work together without treating fluent output as proof. It defines how to understand a task, classify uncertainty, act within scope, verify results, preserve project memory, and learn from failures.

## Start here

If you are new:

1. Read [BIBLE.md](BIBLE.md) — core principles and guardrails.
2. Follow [BOOTSTRAP.md](BOOTSTRAP.md) — create your own workspace.
3. Read [TERMINOLOGY.md](TERMINOLOGY.md) — vocabulary and status meanings.
4. Use [PROVENANCE.md](PROVENANCE.md) — record where important claims come from.
5. Use [EXPERIMENTS.md](EXPERIMENTS.md) — run bounded, reversible experiments.
6. Use [SECURITY.md](SECURITY.md) — protect credentials, private data, and access.
7. Use [LESSONS_LEARNED.md](LESSONS_LEARNED.md) — turn failures into validated improvements.
8. Read [ARCHITECTURE.md](ARCHITECTURE.md) when deciding which layers you actually need.

## The core idea

The framework follows:

`UNDERSTAND → CLASSIFY → PLAN → ACT → VERIFY → REALITY CHECK → LEARN → PERSIST`

A result is not considered complete merely because it looks convincing. Evidence, scope, verification, and uncertainty must remain visible.

## The layers

- **bAIble** — governance, rules, guardrails, evidence, verification, and learning.
- **rAIda** — orchestration and coordination between agents, tools, and tasks.
- **FederAItion** — an execution/integration environment connecting repositories, tools, CI, and workflows.
- **UnAiversed** — a contextual and relational knowledge space.
- **Reality Check** — a cross-cutting mechanism for testing conclusions against evidence, assumptions, alternatives, and verification.

These are portable concepts, not mandatory software packages. A minimal installation can be only this bAIble plus one agent and one project.

## Public by design

This repository is intentionally public. It must remain usable without private conversation history or access to someone else's projects.

Do **not** publish:

- credentials, tokens, keys, cookies, or access paths
- personal or confidential information
- private conversation exports
- private repository contents
- proprietary/customer data
- hidden context
- claims that depend on inaccessible sources

A lesson generalized from private work may be included only when the private source is not exposed and the lesson is clearly identified as generalized.

## Status vocabulary

Important statements should distinguish their status:

- **VERIFIED** — directly supported by accessible evidence.
- **ESTABLISHED** — repeatedly documented or observed, but not necessarily independently verified in the current task.
- **EXPERIMENTAL** — currently being tested.
- **PROPOSED** — a design idea awaiting validation.
- **PRIVATE** — intentionally excluded from this public repository.

## Reality Check

When evidence is incomplete, do not manufacture continuity or certainty.

Ask:

- What do we know?
- What is the source?
- What are we inferring?
- What remains unknown?
- What alternative explanation matters?
- What would falsify the conclusion?
- What has actually been verified?

**Reality outranks the document.**
