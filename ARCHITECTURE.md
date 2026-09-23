# Architecture

bAIble pre-v2 is deliberately layered. The layers solve different problems and should not be confused.

## 1. bAIble — governance

Purpose: define rules, scope, guardrails, evidence handling, verification, provenance, and learning.

bAIble answers: **How should the collaboration behave?**

It does not have to be an application. Markdown files are enough to start.

## 2. rAIda — orchestration

Purpose: coordinate agents, tasks, tools, handoffs, retries, and workflow state.

rAIda answers: **Who does what, when, and with which tools?**

Orchestration is useful when one agent or one manual workflow becomes insufficient.

## 3. FederAItion — execution/integration

Purpose: connect repositories, CI, tools, environments, and execution workflows.

FederAItion answers: **Where does coordinated work actually run and integrate?**

This is an implementation concept, not a dependency of the public bAIble.

## 4. UnAiversed — context

Purpose: represent relationships between knowledge, decisions, observations, projects, experiments, and other context.

UnAiversed answers: **How are pieces of context related?**

It may be implemented as files, databases, graphs, maps, or another representation.

## 5. Reality Check — verification mechanism

Reality Check crosses all layers.

It answers: **Are we mistaking a coherent story, shared assumption, or apparent success for verified reality?**

It should be invoked before consequential decisions, after surprising results, when evidence conflicts, and when confidence is high but evidence is weak.

## 6. Learning Loop

The system should evolve through:

OBSERVATION → EXPERIMENT → RESULT → LESSON → CANDIDATE RULE → VALIDATION → RULE

A single anecdote is not automatically a permanent rule.

## Minimal architecture

Start with:

Human → Agent → bAIble → Project

Add rAIda when coordination is needed.

Add UnAiversed when context relationships become difficult to manage.

Add FederAItion when multiple execution/integration surfaces must be coordinated.

Add Watchdog only after the underlying workflow is observable and understandable.

## Watchdog

A watchdog is a monitoring/detection layer, not a replacement for governance.

Preferred sequence:

DETECT → REPORT → DECIDE → ACT

An immature watchdog should not autonomously repair situations it cannot explain.

## Separation of concerns

- Governance is not orchestration.
- Orchestration is not verification.
- Context is not truth.
- An experiment is not production readiness.
- Agent agreement is not independent evidence.
- A UI state is not authorization.

The layers cooperate, but each keeps a distinct responsibility.
