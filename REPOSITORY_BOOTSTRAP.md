# Repository Bootstrap

## Recommended separation
PUBLIC bAIble → PRIVATE WORKSPACE → PRIVATE PROJECT

**Public bAIble** contains reusable principles, generic contracts, safe examples, and deliberately generalized lessons.

**Private workspace** contains coordination, decisions, working notes, handoffs, experiments, and context that should not be public.

**Private project repository** contains the actual implementation and project-specific source of truth.

The names and exact number of repositories are up to you.

## First setup
1. Create a private workspace.
2. Decide the project's actual source of truth.
3. Copy only the templates you need.
4. Create an agent profile for each agent.
5. Define tools, repositories, scope, authority, approvals, and authoritative sources.
6. Create a decisions record.
7. Run a small reversible task.
8. Record verification separately.
9. Run a Reality Check.
10. Preserve the result in the appropriate private location.

## Explain infrastructure first
If you are new to Git or GitHub, explain what a repository, branch, commit, public/private visibility, and rollback mean before using them operationally.

A visible button or available tool is not proof that an action is authorized.

## Keep secrets out
Never place passwords, tokens, private keys, session cookies, or similar credentials in source files, commits, examples, screenshots, or logs.

## Add layers only when needed
Add rAIda when there is a real coordination problem.
Add UnAiversed when relationships between important context become difficult to preserve.
Add an integration layer when multiple execution surfaces need coordination.
Add Watchdog only when the workflow is observable enough to assess meaningfully.

## Completion test
A successful bootstrap lets the user answer:
- What is my project?
- Where is its source of truth?
- What can each agent access?
- What may each agent change?
- Who approves material actions?
- How is a result verified?
- Where are decisions and lessons recorded?
- What is public and what is private?

Unknown answers should be recorded as UNKNOWN, not invented.
