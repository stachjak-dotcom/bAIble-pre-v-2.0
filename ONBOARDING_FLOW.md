# Beginner Onboarding Flow

## Phase 1 — Meet the user
Ask what the user wants to accomplish, what would count as a useful first result, what is already known, what must remain private, and what tools/repositories already exist.

Do not ask the user to dump project information into the public bAIble repository.

## Phase 2 — Establish the private foundation
Before substantial project work:

1. explain public versus private;
2. check whether a private workspace exists;
3. check whether a private project repository exists or is needed;
4. help create them when necessary;
5. explain what each repository is for;
6. confirm visibility and access;
7. identify the project's implementation source of truth;
8. create the initial private records.

The user should know **where their information will live before they start giving the agent that information**.

## Phase 3 — Explain bAIble
Explain governance, scope, evidence, verification, Reality Check, durable memory, and public/private separation. Do not introduce the entire architecture at once.

## Phase 4 — Define the agent contract
Create an agent profile covering role, purpose, tools, systems/repositories, scope, authority, approval, authoritative sources, verification, handoff, and out-of-scope work.

## Phase 5 — First bounded task
Choose a small reversible task. Define expected result, evidence, scope, approval requirements, and destination for the resulting records.

After execution, inspect the actual result, record verification, run Reality Check, and record a lesson if useful.

## Phase 6 — Durable memory
Move important decisions, evidence, and lessons out of temporary conversation context into the appropriate private project records.

Use the private workspace for coordination and durable project memory. Use the private project repository for implementation/source of truth.

## Phase 7 — Add relational context if needed
If relationships between important context cannot be reliably preserved in ordinary records, introduce UnAiversed concepts. Start with structured records before sophisticated visualization.

## Phase 8 — Add orchestration if needed
If several agents/tools must coordinate, introduce the rAIda role and lifecycle from [RUNTIME_AND_WATCHDOG.md](RUNTIME_AND_WATCHDOG.md). Build the smallest real workflow first.

## Phase 9 — Add integration infrastructure if needed
When multiple repositories, tools, CI systems, or execution environments need coordinated work, introduce the project's own integration layer. Keep implementation-specific details private.

## Phase 10 — Add monitoring
Only after the workflow is observable should a watchdog be added. Begin with detection and reporting. Automated remediation requires explicit authority and adequate evidence.

## Phase 11 — Graduation test
The user should be able to:
- identify the public bAIble repository;
- identify their private workspace;
- identify their private project source of truth;
- explain what belongs in each;
- distinguish facts/interpretations/hypotheses/decisions;
- define agent scope and authority;
- identify evidence;
- perform Reality Check;
- verify independently of self-report;
- preserve a handoff;
- keep private information out of public artifacts;
- explain why each added architectural layer exists.

## Final principle
The goal is not to build the largest AI system.

**Build the smallest system that remains understandable, verifiable, maintainable, and under human control.**
