# Bootstrap a new workspace

A new user should be able to start without hidden context.

1. Read `README.md`, `BIBLE.md`, and `TERMINOLOGY.md`.
2. Create your own workspace/repository. Names are your choice.
3. Decide visibility deliberately.
4. Copy the files you need from [WORKSPACE_TEMPLATE](WORKSPACE_TEMPLATE/).
5. Define each agent's role, tools, scope, authority/approval level, authoritative sources, verification responsibility, and handoff format.
6. Run a first Reality Check using [REALITY_CHECK.md](REALITY_CHECK.md): what can the agent access, what can it not access, which source is authoritative, what is assumed, and what needs verification?
7. Run one small, reversible experiment using [EXPERIMENTS.md](EXPERIMENTS.md).
8. Record verification separately from the agent's report using [VERIFICATION.md](VERIFICATION.md).
9. Transfer work using [HANDOFF.md](HANDOFF.md) when another human, agent, tool, or session takes over.
10. Run [BOOTSTRAP_TEST.md](BOOTSTRAP_TEST.md) to check whether the public contract is sufficient without hidden context.
11. Add orchestration only when coordination becomes useful.
12. Add contextual/relational knowledge only when it solves a real problem.
13. Add integration infrastructure when multiple tools, repositories, CI systems, or workflows need coordination.
14. Add a watchdog last. It should detect and report before it autonomously repairs.
15. Promote lessons into permanent rules only after validation. Use [STATUS_TRANSITIONS.md](STATUS_TRANSITIONS.md).

## First milestone

A new human can understand the framework, create a workspace, give a bounded task, observe a Reality Check, verify the result, hand off the work, and preserve a lesson without hidden context.

## Bootstrap failure is useful

If the fresh-start test forces the participant to invent a core rule about authority, evidence, verification, scope, security, or Reality Check, record that as a documentation gap rather than silently inventing the rule. Update the public contract only after the gap has been understood and validated.
