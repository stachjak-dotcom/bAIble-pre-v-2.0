# Repository Bootstrap

The public bAIble repository is the manual. It is **not** the user's project memory.

## A simple separation

**PUBLIC bAIble → PRIVATE WORKSPACE → PRIVATE PROJECT**

These are concepts, not mandatory numbers of repositories.

### Public bAIble

Contains reusable principles, generic contracts, safe examples, terminology, and deliberately generalized lessons.

### Private workspace

Contains project context, decisions, working notes, handoffs, experiments, evidence, lessons, and other information that should not be public.

### Private project repository

Contains the actual implementation and its project-specific source of truth.

If the user already has suitable private places, use them. Do not create infrastructure for its own sake.

## What the new-user agent should do

When a new user arrives with only the public bAIble link:

1. explain the public/private boundary;
2. ask what private workspace or project repository already exists;
3. identify where implementation is authoritative;
4. help create or organize a suitable private place only if needed;
5. explain where each kind of information will live before asking for substantial project context;
6. confirm visibility and access;
7. begin with a small, bounded task.

Do not require the user to understand Git internals before getting started. Explain each concept when it becomes relevant.

## Information routing

Before storing important information, classify it:

- **Public governance** → public bAIble only when safely generalized.
- **Project fact/context** → private workspace or private project.
- **Decision** → private decision record.
- **Experiment** → private experiment record.
- **Evidence** → appropriate private evidence record.
- **Implementation** → private project source of truth.
- **Personal/confidential/secret information** → private system with appropriate access controls; never public bAIble.

If the correct destination is unclear, resolve that before publishing or committing.

## Keep secrets out

Never place passwords, tokens, private keys, session cookies, or similar credentials in source files, commits, examples, screenshots, or logs. Use secure secret storage where available.

## Add layers only when needed

Add **rAIda** when there is a real coordination problem.

Add **UnAiversed** when relationships between important context become difficult to preserve.

Add an integration layer when multiple execution surfaces need coordination.

Add **Watchdog** only when the workflow is observable enough to assess meaningfully.

## First useful milestone

The setup is sufficient when the user can answer:

- What is my project?
- Where is its implementation source of truth?
- Where does durable project memory live?
- What can each agent access?
- What may each agent change?
- Who approves material actions?
- How is a result verified?
- What is public and what is private?

Unknown answers should be recorded as UNKNOWN, not invented.
