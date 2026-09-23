# Repository Bootstrap

The public bAIble repository is the manual. It is **not** the user's project memory.

## Recommended separation
PUBLIC bAIble → PRIVATE WORKSPACE → PRIVATE PROJECT

### Public bAIble
Contains reusable principles, generic contracts, safe examples, and deliberately generalized lessons.

### Private workspace
Contains coordination, project context, decisions, working notes, handoffs, experiments, evidence, lessons, and other information that should not be public.

### Private project repository
Contains the actual implementation and project-specific source of truth.

The names and exact number of repositories are up to the user, but a beginner should normally be guided to create these two private places before accumulating meaningful project data.

## What the new-user agent should do

When a new user arrives with only the public bAIble link:

1. Explain the public/private boundary.
2. Ask whether they already have a suitable private workspace and project repository.
3. If not, guide them through creating them.
4. Explain **where each kind of information will live before asking the user to provide it**.
5. Confirm repository visibility.
6. Confirm the project's source of truth.
7. Help create the initial workspace records.
8. Only then begin accumulating project-specific context.

A useful default is:

- private workspace = memory, decisions, handoffs, experiments, evidence, lessons;
- private project repository = implementation/source of truth;
- public bAIble = reusable governance and generalized knowledge.

Do not require the user to understand Git internals before getting started. Explain each concept immediately before it becomes relevant.

## First setup
1. Create a private workspace.
2. Create or identify the private project repository.
3. Decide which repository is authoritative for implementation.
4. Copy only the bAIble templates needed into the appropriate private location.
5. Create an agent profile.
6. Define tools, repositories, scope, authority, approvals, and authoritative sources.
7. Create initial project context and decision records.
8. Run a small reversible task.
9. Record verification separately.
10. Run a Reality Check.
11. Preserve the result in the appropriate private location.

## Information routing rule

Before storing anything, classify it:

- **Public governance** → public bAIble only if safely generalized.
- **Project fact/context** → private workspace or private project.
- **Decision** → private decision record.
- **Experiment** → private experiment record.
- **Evidence** → appropriate private evidence record.
- **Implementation** → private project source of truth.
- **Personal/confidential/secret information** → private system with appropriate access controls; never public bAIble.

If the correct destination is unclear, stop and resolve it before publishing or committing.

## Keep secrets out
Never place passwords, tokens, private keys, session cookies, or similar credentials in source files, commits, examples, screenshots, or logs. Use secure secret storage where available.

## Add layers only when needed
Add rAIda when there is a real coordination problem.
Add UnAiversed when relationships between important context become difficult to preserve.
Add an integration layer when multiple execution surfaces need coordination.
Add Watchdog only when the workflow is observable enough to assess meaningfully.

## Completion test
A successful bootstrap lets the user answer:
- What is my project?
- Where is its implementation source of truth?
- Where does durable project memory live?
- What can each agent access?
- What may each agent change?
- Who approves material actions?
- How is a result verified?
- What is public and what is private?
- Where should a new piece of information be stored?

Unknown answers should be recorded as UNKNOWN, not invented.
