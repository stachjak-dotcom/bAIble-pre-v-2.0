# Bootstrap a new workspace

A new user should be able to start without hidden context.

1. Read `README.md`, `BIBLE.md`, and `TERMINOLOGY.md`.
2. Create your own workspace/repository. Names are your choice.
3. Decide visibility deliberately.
4. Copy the files you need from [WORKSPACE_TEMPLATE](WORKSPACE_TEMPLATE/).
5. Create an [AGENT_PROFILE](AGENT_PROFILE.md) for each agent.
6. Define each agent's role, tools, scope, authority/approval level, authoritative sources, verification responsibility, and handoff format.
7. Run a first Reality Check using [REALITY_CHECK.md](REALITY_CHECK.md): what can the agent access, what can it not access, which source is authoritative, what is assumed, and what needs verification?
8. Run one small, reversible experiment using [EXPERIMENTS.md](EXPERIMENTS.md).
9. Record verification separately from the agent's report using [VERIFICATION_RECORD.md](VERIFICATION_RECORD.md).
10. Transfer work using [HANDOFF.md](HANDOFF.md) when another human, agent, tool, or session takes over.
11. Run [BOOTSTRAP_TEST.md](BOOTSTRAP_TEST.md) to check whether the public contract is sufficient without hidden context.
12. Add orchestration only when coordination becomes useful.
13. Add contextual/relational knowledge only when it solves a real problem.
14. Add integration infrastructure when multiple tools, repositories, CI systems, or workflows need coordination.
15. Add a watchdog last. It should detect and report before it autonomously repairs.
16. Promote lessons into permanent rules only after validation. Use [STATUS_TRANSITIONS.md](STATUS_TRANSITIONS.md).

## Authority rule

bAIble requires authority and approval to be explicit, but it does not invent project-specific authority.

If authority for a material action is unknown:
- record it as UNKNOWN;
- do not infer authorization from tool availability or UI visibility;
- stop or escalate when the action requires authority that has not been established.

## First milestone

A new human can understand the framework, create a workspace, give a bounded task, define agent boundaries, observe a Reality Check, verify the result, hand off the work, and preserve a lesson without hidden context.

## Bootstrap failure is useful

If the fresh-start test forces the participant to invent a core rule about authority, evidence, verification, scope, security, or Reality Check, record that as a documentation gap rather than silently inventing the rule. Update the public contract only after the gap has been understood and validated.
