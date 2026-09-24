# Start Here

> **Píseň druhá — L(A)Iving together**

Pokud je bAIble nový, začni tady. Nemusíš znát všechny jeho písně, zkratky ani pojmy.

## What is bAIble?

bAIble is a living, public guide for humans and AI working together deliberately.

It began as a practical AI development bible: rules, roles, workflows, guardrails, evaluations, and lessons learned. It grew from real work and mistakes, and it is meant to keep growing through use.

You do **not** need to understand the whole bAIble before using it.

**AI can help you act, but fluent output is not proof.**

## If you are an AI reading bAIble

Read it as a **guide for collaboration**, not as a software package you are expected to copy.

First understand:

- what bAIble is;
- why it exists;
- how it grew from practical experience;
- how it helps a human work with AI;
- where project-specific information belongs.

Then help the human use only the parts that matter to their situation.

Do not invent undocumented history. Do not claim to have read material you could not access.

## If you are a new human

You can simply tell your AI:

> “Read bAIble and help me use it for my work.”

Start with your goal. You do not need to know beforehand which repository, workflow, agent role, or Reality Check you will need.

A useful rhythm is:

**UNDERSTAND → CLASSIFY → PLAN → ACT → VERIFY → REALITY CHECK → LEARN → PERSIST**

This is a rhythm, not bureaucracy. Use more of it when the work is uncertain or important and less when the task is simple.

## The first practical boundary

The public bAIble is a guide. It is **not your private project memory**.

A simple separation is:

- **public bAIble** → reusable principles, safe examples, generalized lessons;
- **private workspace** → project context, decisions, experiments, evidence, lessons, handoffs;
- **private project** → implementation and its source of truth;
- **secure storage** → credentials and other secrets.

If you already have suitable private places, keep using them. The point is clarity, not creating more infrastructure.

## The ideas you may meet later

You do not need these on day one. They exist because different problems need different kinds of help.

- **rAIda** — coordinates several agents, tools, tasks, or handoffs when manual coordination becomes the problem. [Read the construction guide →](RUNTIME_AND_WATCHDOG.md)
- **Basecamp** — preserves the relationships, history, decisions, experiments, evidence, and lessons that help a project grow without losing where things came from. [Read the guide →](UNAIVERSED_GUIDE.md)
- **Integration layer** — connects separate execution environments such as repositories, tools, CI, or applications. [Read the architecture →](ARCHITECTURE.md)
- **Watchdog** — watches an observable workflow for stuck work, invalid states, missing evidence, or unexpected failures. [Read the watchdog guide →](RUNTIME_AND_WATCHDOG.md)
- **Reality Check** — checks conclusions and apparent success against evidence, assumptions, alternatives, and verification. [Read the guide →](REALITY_CHECK.md)

Start with the smallest thing that helps. You can add the rest later.

## What good collaboration looks like

Ask:

- What are we actually trying to do?
- What do we know?
- What are we assuming?
- What does the AI have access to?
- What is it allowed to change?
- What evidence supports the result?
- How can we check it?
- What should be remembered?
- Where should it be stored?
- What decision belongs to the human?

The AI should be willing to say **“I don't know”**, challenge an assumption when evidence warrants it, and make uncertainty visible.

## A note about the public repository

This repository is public.

Do not put credentials, private conversations, personal identifiers, confidential/customer information, private project contents, or private implementation evidence into it.

For the detailed boundary, see [PUBLIC_PRIVATE_BOUNDARY.md](PUBLIC_PRIVATE_BOUNDARY.md).

## Where to go next

- [BIBLE.md](BIBLE.md) — core principles and working discipline.
- [ORIGIN_AND_PURPOSE.md](ORIGIN_AND_PURPOSE.md) — why bAIble exists and how it evolved.
- [ONBOARDING_FLOW.md](ONBOARDING_FLOW.md) — a gradual way to begin.
- [BOOTSTRAP.md](BOOTSTRAP.md) — practical workspace setup.
- [NEW_USER_AGENT.md](NEW_USER_AGENT.md) — guidance for an AI helping a new user.
- [REALITY_CHECK.md](REALITY_CHECK.md) — checking whether something is actually supported.
- [HANDOFF.md](HANDOFF.md) — preserving work between people or agents.
- [LESSONS_LEARNED.md](LESSONS_LEARNED.md) — reusable lessons.

**Start small. Learn as you go. Build only what solves a real problem.**
