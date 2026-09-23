# Status Transitions

Status belongs to a claim, decision, artifact, or lesson. It is not a permanent label for an entire project.

## Statuses

- **PROPOSED** — design idea or hypothesis awaiting validation.
- **EXPERIMENTAL** — currently being tested in a bounded context.
- **ESTABLISHED** — repeatedly documented or observed with relevant limitations known.
- **VERIFIED** — directly supported by accessible evidence in the current verification context.
- **PRIVATE** — intentionally excluded from the public repository.

## Promotion gates

### PROPOSED → EXPERIMENTAL
Define a bounded question, hypothesis, setup, expected result, and stopping condition.

### EXPERIMENTAL → ESTABLISHED
Require evidence from repeated or sufficiently informative observations, with alternative explanations and limitations considered.

### ESTABLISHED → VERIFIED
Require direct accessible evidence and a verification record appropriate to the claim.

Not every claim needs to reach VERIFIED.

## Regression

A status may move backward when new evidence contradicts an earlier conclusion, when its scope changes, or when a previous verification no longer applies.

Do not promote status merely because time has passed, agents agree, or the result looks convincing.
