# Next-generation bAIble

> **Bude to první část nové generace bAIble, která už člověka i agenta učí, jak se v celém prostředí zabydlet.**

This document is a public orientation map. It is intentionally generic: it describes how the pieces fit together without exposing any private runtime, repository, execution history, or project-specific implementation.

## The family

The next-generation bAIble is not a single document. It is a family of connected practices.

- **bAIble** — governance, language, rules, guardrails, learning.
- **rAIda** — coordination: THINK / COORDINATE / REMEMBER-TO-CHECK.
- **Basecamp** — context and relationships.
- **Agent** — PREPARE / REASON / EXECUTE / RECORD.
- **Evidence** — the trace left by work.
- **Verification** — checking a result against defined evidence.
- **Reality Check** — the boundary between a plausible story and what the available evidence supports.
- **Watchdog** — CONTINUE / MONITOR / ESCALATE.
- **Human** — intent, material decisions, and intervention gates.
- **Wolf** — ORIENT / TEACH / ONBOARD.

These are roles and responsibilities, not necessarily separate products or agents.

## The map

```
HUMAN
  ↓
bAIble — GOVERN / LANGUAGE / RULES
  ↓
rAIda — THINK / COORDINATE / REMEMBER-TO-CHECK
  ↓
Basecamp — CONTEXT / RELATIONSHIPS
  ↓
Agent — PREPARE / REASON / EXECUTE / RECORD
  ↓
Evidence
  ↓
Verification
  ↓
Reality Check
  ↓
Watchdog — CONTINUE / MONITOR / ESCALATE
  ↓
NEXT AUTHORIZED TASK
  ↺
```

The human remains the source of material intent and the owner of decisions that require human authorization.

## The universal orientation

Before doing work, ask:

1. **WHERE AM I?**
2. **WHAT IS THE INTENT?**
3. **WHAT IS MY ROLE?**
4. **WHAT IS IN SCOPE?**
5. **WHAT MUST I CHECK?**
6. **WHAT DO I KNOW?**
7. **WHAT DO I NOT KNOW?**
8. **WHAT EVIDENCE MUST I PRODUCE?**
9. **WHO OR WHAT VERIFIES IT?**
10. **WHAT HAPPENS NEXT?**

This is deliberately simple. The environment should become easier to navigate, not harder.

## The epistemic discipline

Do not collapse these into one state:

**FOUND ≠ UNDERSTOOD ≠ VERIFIED ≠ CANONICAL**

A useful vocabulary is:

- **UNKNOWN** — we do not have the needed information.
- **UNVERIFIED** — a claim exists, but its support has not been checked.
- **UNCERTAIN** — more than one interpretation remains plausible.
- **CONFLICT** — relevant evidence or interpretations disagree.
- **MISSING_CONTEXT** — the required context is not available.
- **STALE** — the information may no longer represent the current state.
- **VERIFIED** — a defined claim has been checked within a defined scope.

The important habit is not to hide the gap.

## Remember-to-check

The system does not need to remember everything.

It needs to remember **what must be checked**.

Repeated failures should become compact process memory: a known failure pattern, the preventive check, the relevant source, and the evidence needed next time.

That keeps context useful instead of turning every task into an ever-growing prompt.

## Context is not truth

Basecamp can connect observations, claims, interpretations, decisions, experiments, evidence, lessons, and rules.

A relationship in the context space does not automatically prove a fact.

The same discipline applies to maps, graphs, visualizations, agent summaries, and generated explanations:

> **A representation can help us navigate reality without becoming reality itself.**

## Human and agent onboarding

A newcomer does not need the whole system at once.

### Level 0 — Příchozí
What is this environment?

### Level 1 — Pozorovatel
Can I find the relevant workspace, sources, rules, and current state?

### Level 2 — Učeň
Can I prepare work without silently inventing missing requirements?

### Level 3 — Pracovník
Can I execute within scope and leave useful evidence?

### Level 4 — Samostatný agent
Can I continue a defined task without manual steering while respecting gates?

### Level 5 — Spolupracovník prostředí
Can I improve the environment without quietly changing its meaning or authority?

Progression is about demonstrated behaviour, not a badge or a rank.

## Wolf

Wolf is the friendly onboarding persona.

Wolf can:

- show where we are;
- explain terminology;
- point to the next relevant document or step;
- remind us to perform a Reality Check;
- help a newcomer understand the environment.

Wolf does **not**:

- decide;
- verify truth;
- change task state;
- authorize work;
- bypass a human gate;
- become a hidden second orchestrator.

Wolf is the guide at the entrance, not the person who owns the building.

## Public / private boundary

This public document intentionally does not contain:

- private runtime details;
- credentials or access paths;
- private execution evidence;
- private project history;
- internal identifiers;
- hidden context.

Private implementations can use the same principles without exposing their internal machinery.

See [PUBLIC_PRIVATE_BOUNDARY.md](PUBLIC_PRIVATE_BOUNDARY.md).

## The growing loop

The environment grows through:

**OBSERVATION → EXPERIMENT → RESULT → EVIDENCE → LESSON → CANDIDATE RULE → VALIDATION → RULE**

A discovery is not automatically a rule.

A useful rule is earned through evidence.

## Reality outranks the document

The bAIble is a guide for working deliberately.

It is not a substitute for reality, evidence, or human judgment.

When the document and the verified reality disagree, the disagreement becomes something to investigate — not something to hide.
