# Architecture

bAIble is deliberately layered. Each layer solves a different problem.

## 1. bAIble — governance
Defines rules, scope, guardrails, evidence, verification, provenance, and learning.

## 2. rAIda — orchestration
Coordinates agents, tasks, tools, handoffs, approvals, and workflow state when a single-agent/manual workflow is no longer sufficient.

## 3. UnAiversed — context
Represents relationships between observations, hypotheses, decisions, experiments, projects, evidence, and lessons.

## 4. Integration layer — execution
Connects a project's repositories, tools, CI, environments, and other execution surfaces. The implementation is project-specific and should remain private when appropriate.

## 5. Watchdog — monitoring
Observes an existing workflow and detects/report anomalies. It is not a replacement for governance or an unexplained second orchestrator.

## 6. Reality Check — verification mechanism
Crosses all layers and tests whether a coherent story, shared assumption, or apparent success is actually supported by evidence.

## Minimal architecture
Start with:
Human → Agent → bAIble → Project

Add rAIda when coordination is needed.
Add UnAiversed when context relationships become difficult to preserve.
Add an integration layer when multiple execution surfaces must be coordinated.
Add Watchdog only after the workflow is observable and understandable.

## Separation of concerns
- Governance is not orchestration.
- Orchestration is not verification.
- Context is not truth.
- An experiment is not production readiness.
- Agent agreement is not independent evidence.
- UI visibility is not authorization.
- A public framework is not a private runtime.

See [RUNTIME_AND_WATCHDOG.md](RUNTIME_AND_WATCHDOG.md) and [UNAIVERSED_GUIDE.md](UNAIVERSED_GUIDE.md).

## Learning loop
OBSERVATION → EXPERIMENT → RESULT → LESSON → CANDIDATE RULE → VALIDATION → RULE

A single anecdote is not automatically a permanent rule.
