# Beginner Onboarding Flow

## Phase 1 — Meet the project
Ask what the user wants to accomplish, what would count as a useful first result, what is already known, what must remain private, and what tools/repositories exist. Summarize the answers and mark assumptions.

## Phase 2 — Explain bAIble
Explain governance, scope, evidence, verification, Reality Check, durable memory, and public/private separation. Do not introduce the entire architecture at once.

## Phase 3 — Establish a private workspace
Help create an appropriate private workspace and identify the project's source of truth. Explain repository visibility and basic version-control concepts before using them operationally.

## Phase 4 — Define the agent contract
Create an agent profile covering role, purpose, tools, systems/repositories, scope, authority, approval, authoritative sources, verification, handoff, and out-of-scope work.

## Phase 5 — First bounded task
Choose a small reversible task. Define the expected result, evidence, scope, and approval requirements. After execution, inspect the actual result, record verification, run Reality Check, and record a lesson if useful.

## Phase 6 — Durable memory
Move important decisions, evidence, and lessons out of temporary conversation context into the appropriate private project records. Never copy private material into public bAIble.

## Phase 7 — Add relational context if needed
If relationships between important context cannot be reliably preserved in ordinary records, introduce UnAiversed concepts. Start with structured records before sophisticated visualization.

## Phase 8 — Add orchestration if needed
If several agents/tools must coordinate, introduce the rAIda role and lifecycle from [RUNTIME_AND_WATCHDOG.md](RUNTIME_AND_WATCHDOG.md). Build the smallest real workflow first.

## Phase 9 — Add integration infrastructure if needed
When multiple repositories, tools, CI systems, or execution environments need coordinated work, introduce the project's own integration layer. Keep implementation-specific details private.

## Phase 10 — Add monitoring
Only after the workflow is observable should a watchdog be added. Begin with detection and reporting. Automated remediation requires explicit authority and adequate evidence.

## Phase 11 — Graduation test
The user should be able to describe the project and source of truth, distinguish facts/interpretations/hypotheses/decisions, define agent scope and authority, identify evidence, perform Reality Check, verify independently of self-report, preserve a handoff, keep private information out of public artifacts, and explain why each added architectural layer exists.

## Final principle
The goal is not to build the largest AI system.

**Build the smallest system that remains understandable, verifiable, maintainable, and under human control.**
