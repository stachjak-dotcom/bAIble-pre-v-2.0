# Architecture

bAIble is deliberately layered. Each layer solves a different problem.

## 1. bAIble — governance

Defines rules, scope, guardrails, evidence, verification, provenance, and learning.

**Question it answers:** *How should we work?*

## 2. rAIda — orchestration

Coordinates agents, tasks, tools, handoffs, approvals, and workflow state when a single-agent or manual workflow is no longer sufficient.

**Question it answers:** *Who is doing what, in what state, and what happens next?*

## 3. Basecamp — context and growth

Preserves relationships between observations, ideas, hypotheses, decisions, experiments, projects, evidence, and lessons.

**Question it answers:** *How did we get here, what connects the pieces, and what have we learned?*

Basecamp is a contextual workspace, not a truth engine. It can organize and expose relationships without silently turning an inference into a fact.

The name **Basecamp** is the practical/public name for the contextual layer previously described in design material as **UnAiversed**.

## 4. Integration layer — execution

Connects a project's repositories, tools, CI, environments, applications, and other execution surfaces.

**Question it answers:** *How do the actual systems exchange work and evidence?*

The implementation is project-specific and should remain private when appropriate.

## 5. Watchdog — monitoring

Observes an existing workflow and detects or reports anomalies.

**Question it answers:** *Is the workflow behaving as expected?*

It is not a replacement for governance and should not become an unexplained second orchestrator.

## 6. Reality Check — verification mechanism

Crosses all layers and tests whether a coherent story, shared assumption, or apparent success is actually supported by evidence.

**Question it answers:** *Is this conclusion or apparent success actually supported?*

Reality Check is deliberately not another infrastructure layer.

## Minimal architecture

Start with:

**Human → Agent → bAIble → Project**

Add rAIda when coordination is needed.

Add Basecamp when project context, relationships, history, and learning become difficult to preserve.

Add an integration layer when multiple execution surfaces must be coordinated.

Add Watchdog only after the workflow is observable and understandable.

Use Reality Check wherever verification matters.

## Separation of concerns

- Governance is not orchestration.
- Orchestration is not verification.
- Context is not truth.
- Context is not memory by accident; it should preserve useful relationships deliberately.
- An experiment is not production readiness.
- Agent agreement is not independent evidence.
- UI visibility is not authorization.
- A public framework is not a private runtime.

See [RUNTIME_AND_WATCHDOG.md](RUNTIME_AND_WATCHDOG.md) and [BASECAMP_GUIDE.md](BASECAMP_GUIDE.md).

## Learning loop

**OBSERVATION → EXPERIMENT → RESULT → LESSON → CANDIDATE RULE → VALIDATION → RULE**

A single anecdote is not automatically a permanent rule.
