# bAIble v0.1 — Foundation

This document preserves the **public conceptual foundation of bAIble v0.1** inside v2.

It is not a copy of the old repository. It is a bridge: the first bAIble is the root from which the later material grows.

## What the first version established

The original bAIble described itself as a living AI development bible: rules, roles, workflows, guardrails, evaluations, and lessons learned for humans working with AI agents.

Its core principles were:
1. AI is a collaborator, not the final authority.
2. The desired outcome matters more than the implementation.
3. Uncertainty is acceptable; silent guessing is not.
4. Meaningful mistakes can improve the system.

Its concrete rules established a durable working discipline:
- understand before implementing;
- define the desired result;
- make completion testable;
- do not guess material rules;
- respect scope;
- record unrelated problems;
- reuse existing project patterns;
- prefer small, verifiable changes;
- separate implementation from verification;
- preserve project memory;
- distinguish experiments from production;
- use explicit stop conditions.

## lAInguage

The first version also introduced a small shared language for work:
- **Explore** — investigate only; do not change the project.
- **Propose** — provide a solution or design; do not implement.
- **Prepare** — produce an implementation plan or prepared change set.
- **Implement** — make the requested changes within scope.
- **Verify** — inspect or test without changing the implementation unless asked.
- **Review** — look for defects, risks, regressions, and scope violations.

This language tells the receiving person or agent what kind of action is being requested.

## Roles

The first version explicitly named roles:
- Human / Product Owner
- Architect
- Developer
- QA
- Reviewer
- Documentation Agent

Those roles remain part of the foundation. v2 may add coordination roles, but it must not make the original roles disappear into generic agent profiles.

See [AGENT_ROLES.md](AGENT_ROLES.md).

## Handoff

The first version included a dedicated Agent Handoff Protocol. A meaningful handoff records task, goal, scope, current state, changes made, files or areas touched, decisions, not done, known problems, risks, verification, and next step.

The receiving agent should not have to reconstruct hidden context from an old conversation.

See [HANDOFF.md](HANDOFF.md).

## Evaluation

The first version treated agent behaviour itself as something that can be evaluated. Important scenarios include ambiguous requirements, scope expansion, dangerous changes, missing context, existing patterns, conflicting sources, insufficient permissions, unrun tests, visually successful implementations, and unrelated defects.

See [VERIFICATION.md](VERIFICATION.md) and [SELF_AUDIT.md](SELF_AUDIT.md).

## Lessons

The first version treated mistakes as reusable knowledge rather than blame. Examples include early implementation, visual-versus-functional success, scope drift, lost chat context, vague done criteria, UI visibility versus authorization, uncontrolled variables, experimental boundaries, agent self-report, ambiguous short commands, and attractive narratives built from assumptions.

## What v2 adds

v2 extends this foundation with stronger separation between human use, agent use, project context, optional orchestration, verification, and durable learning.

It should not replace the foundation with a new abstraction.

When v2 and this foundation appear to disagree, treat that as a **Reality Check**: determine whether v2 intentionally evolved the rule or accidentally lost it.