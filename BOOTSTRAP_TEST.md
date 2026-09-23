# Bootstrap Acceptance Test

This test checks whether a new user or agent can start from the public bAIble without hidden context.

## Principle

Portability does not mean every implementation must produce identical files or procedures. It means the public contract is clear enough that a fresh participant can implement the same principles without private knowledge.

## Fresh-start test

Give a new participant access only to this public repository and a simple, bounded project.

They should be able to:

1. explain what bAIble is and is not;
2. identify the scope and authority of the current task;
3. create a minimal project workspace;
4. record important claims with provenance/status;
5. distinguish facts, inferences, unknowns, and hypotheses;
6. classify a bounded activity as an experiment when appropriate;
7. perform and record a Reality Check;
8. record verification separately from agent self-report;
9. produce a usable handoff;
10. preserve a lesson without exposing private information;
11. identify when a request is outside scope;
12. avoid adding rAIda, FederAItion, UnAiversed, or a watchdog without a demonstrated need.

## Acceptance criteria

**PASS** if the participant can complete the above using the public documentation without inventing a core governance rule or relying on hidden context.

**PARTIAL** if the participant can complete the work but must invent a non-critical local implementation detail.

**FAIL** if a core decision about authority, evidence, verification, scope, security, or Reality Check must be invented.

Record:
- participant;
- starting material;
- project/task;
- observations;
- invented assumptions, if any;
- result;
- evidence;
- lessons;
- candidate documentation changes.

The test evaluates contract completeness, not identical output.
