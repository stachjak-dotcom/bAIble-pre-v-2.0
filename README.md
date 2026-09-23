# bAIble pre-v2

**A portable governance and learning framework for AI collaboration.**

bAIble helps a human and one or more AI agents work together without treating fluent output as proof. It defines how to understand a task, classify uncertainty, act within scope, verify results, preserve project memory, and learn from failures.

## Start here

If you are new:

1. Read [BIBLE.md](BIBLE.md) — core principles and guardrails.
2. Follow [BOOTSTRAP.md](BOOTSTRAP.md) — create your own workspace.
3. Read [TERMINOLOGY.md](TERMINOLOGY.md) — vocabulary and status meanings.
4. Use [AGENT_PROFILE.md](AGENT_PROFILE.md) — define an agent's local operating contract.
5. Use [PROVENANCE.md](PROVENANCE.md) — record where important claims come from.
6. Use [REALITY_CHECK.md](REALITY_CHECK.md) — perform an explicit evidence checkpoint.
7. Use [VERIFICATION_RECORD.md](VERIFICATION_RECORD.md) — record what was actually checked.
8. Use [HANDOFF.md](HANDOFF.md) — transfer work without losing scope or uncertainty.
9. Use [EXPERIMENTS.md](EXPERIMENTS.md) and [BOOTSTRAP_TEST.md](BOOTSTRAP_TEST.md) — run bounded experiments and test fresh-start portability.
10. Use [SECURITY.md](SECURITY.md) — protect credentials, private data, and access.
11. Use [LESSONS_LEARNED.md](LESSONS_LEARNED.md) and [SELF_AUDIT.md](SELF_AUDIT.md) — preserve learning and audit the public contract.

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

See [STATUS_TRANSITIONS.md](STATUS_TRANSITIONS.md) for promotion and regression rules.

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

For the operational record and outcomes, use [REALITY_CHECK.md](REALITY_CHECK.md).

The first blind bootstrap RC is recorded in [BLIND_BOOTSTRAP_RC.md](BLIND_BOOTSTRAP_RC.md). Its result is **PASS-WITH-UNCERTAINTY** because the documentation gaps were addressed, but a second independent blind bootstrap has not yet been run.

**Reality outranks the document.**
