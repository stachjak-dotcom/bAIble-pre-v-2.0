# Agent Roles

Roles describe **why an agent exists in a workflow**. A role is not the same thing as an agent profile.

A **role** defines responsibility. A **profile** defines how a particular agent is allowed to perform that responsibility.

## Core roles

### Human / Product Owner
Owns intent, priorities, business meaning, material trade-offs, and final approval of high-impact decisions.

### Architect
Owns or proposes system structure and technical trade-offs.

### Developer / Implementer
Turns an agreed task into an implementation within the defined scope.

### QA / Verifier
Attempts to falsify the result. Checks happy paths, negative paths, edge cases, permissions, regressions, and acceptance criteria.

### Reviewer
Independently examines correctness, maintainability, security, scope, and architectural consistency.

### Documentation Agent
Keeps durable project knowledge aligned with what actually happened: decisions, current state, evidence, lessons, and handoff information.

### Coordinator / Orchestrator
Coordinates work between agents, roles, tools, or stages. Coordination does not automatically grant authority over the work being coordinated.

## Why roles matter

Roles become especially important when work moves between agents. A receiving agent should be able to answer:
- Who did this work?
- What responsibility did that agent have?
- What was it allowed to decide?
- What was actually completed?
- What was verified?
- What remains open?
- What should the receiving role do next?

This is why a handoff records role, scope, authority, evidence, verification, and next action.

## Role vs profile

Use AGENT_PROFILE.md for a concrete agent: Role, Purpose, Allowed tools, Allowed systems, Task scope, Authority, Approval level, Verification responsibility, and Handoff format.

Do not treat an empty profile template as a definition of the role itself.

## Combining roles

One agent may hold several roles for a small task. For higher-risk work, keep implementation and verification separate where practical. An agent should not manufacture independence merely by giving itself a second title.

## Adding a new role

A new role should solve a real coordination or responsibility problem. Define its responsibility, authority, boundaries, expected outputs, verification responsibility, and handoff expectations.

Do not create roles only because the architecture looks cleaner with more boxes.