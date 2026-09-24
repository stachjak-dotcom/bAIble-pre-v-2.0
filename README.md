# 📖 bAIble v2

**A living guide for humans and AI working together deliberately.**

> *Píseň první — Vznik jAIzyka.*  
> *Píseň druhá — L(A)Iving together.*

bAIble is not here to make AI obey. It is here to help humans and AI learn how to work well together.

It began as a practical AI development bible: rules, roles, workflows, guardrails, evaluations, and lessons learned. It has grown into a broader, portable guide for working with AI without confusing fluent output with truth.

You do not need to understand the whole system before using it.

## Start here

New here? Read [START_HERE.md](START_HERE.md).

Then use only the parts that are useful to you:

- [WHEEAILS.md](WHEEAILS.md) — the beginner path when the full bAIble feels like too much.
- [AGENT_QUICK_START.md](AGENT_QUICK_START.md) — compact practical agent discipline.
- [AGENT_EVALS.md](AGENT_EVALS.md) — practical agent-behaviour scenarios.
- [BIBLE.md](BIBLE.md) — the core principles and working discipline.
- [ONBOARDING_FLOW.md](ONBOARDING_FLOW.md) — a gradual path for getting started.
- [BOOTSTRAP.md](BOOTSTRAP.md) — practical workspace setup.
- [NEW_USER_AGENT.md](NEW_USER_AGENT.md) — guidance for an AI helping a new user.
- [REALITY_CHECK.md](REALITY_CHECK.md) — a way to test whether something is actually supported.
- [VERIFICATION.md](VERIFICATION.md) — verification practice.
- [AGENT_ROLES.md](AGENT_ROLES.md) — the core collaboration roles.
- [HANDOFF.md](HANDOFF.md) — preserving work when it moves between people or agents.
- [FOUNDATION_V0_1.md](FOUNDATION_V0_1.md) — the foundation v2 grows from.
- [LESSONS_LEARNED.md](LESSONS_LEARNED.md) — reusable lessons.
- [WORKSPACE_TEMPLATE/](WORKSPACE_TEMPLATE/) — optional templates for a private workspace.

## The basic idea

Work with AI as a collaboration, not as an oracle.

A useful rhythm is:

**UNDERSTAND → CLASSIFY → PLAN → ACT → VERIFY → REALITY CHECK → LEARN → PERSIST**

You do not have to perform every step formally every time. The point is to notice when a step matters.

Ask:

- What are we actually trying to do?
- What do we know?
- What are we assuming?
- What is the AI allowed to do?
- What evidence do we have?
- How will we know the result is real?
- Where should the important information live?

## The layers

These names describe **different jobs**, not a stack you are expected to install.

### [rAIda](RUNTIME_AND_WATCHDOG.md) — coordination

rAIda is the coordination layer. It becomes useful when several agents, tools, tasks, or handoffs need to work together without a human manually relaying every step.

It helps answer: **What is happening, who is doing it, what state is it in, and what happens next?**

### [Basecamp](BASECAMP_GUIDE.md) — context and growth

Basecamp is the project's contextual workspace: a place to preserve relationships between observations, ideas, decisions, experiments, evidence, lessons, and the history of how the project grew.

It helps answer: **Why are we here, how did we get here, what connects these things, and what have we learned along the way?**

Basecamp is not the source of truth by itself. It is the context around the work.

This layer is important because a project does not only accumulate files. It accumulates **relationships, decisions, discoveries, and learning**. Basecamp gives those relationships somewhere to live.

### Integration layer — execution

An integration layer connects separate execution environments: repositories, tools, CI systems, applications, or other services.

It helps answer: **How do the actual systems exchange work and evidence?**

The concrete implementation is project-specific and should remain private when appropriate.

### Watchdog — monitoring

A Watchdog observes an existing workflow and detects or reports anomalies such as stuck work, invalid state transitions, missing evidence, or unexpected failures.

It helps answer: **Is the workflow behaving as expected?**

It is not a second unexplained orchestrator.

### [Reality Check](REALITY_CHECK.md) — verification across the layers

Reality Check is not another infrastructure layer. It is a verification mechanism that can be used anywhere.

It asks: **Do the conclusion, assumption, or apparent success actually hold up against the evidence?**

## Start small

The smallest useful setup is simply:

**HUMAN → AI → bAIble → YOUR PROJECT**

Add another layer only when a real problem calls for it.

See [ARCHITECTURE.md](ARCHITECTURE.md) for the relationships between these concepts.

## Your private work

The public bAIble is the guide. It is not your private project memory.

For a real project, keep project-specific information in an appropriate private place:

- project context and decisions;
- experiments and evidence;
- lessons and handoffs;
- implementation/source of truth;
- secrets in appropriate secure storage.

If you already have suitable places, use them. Do not build a complicated system just because bAIble mentions one.

See [PUBLIC_PRIVATE_BOUNDARY.md](PUBLIC_PRIVATE_BOUNDARY.md).

## A central idea

**AI can help you act, but fluent output is not proof.**

Good collaboration keeps uncertainty visible, checks important results, preserves useful knowledge, and leaves decisions that belong to the human with the human.

**Reality outranks the document.**
