# Orchestration and Watchdog — Public Construction Guide

bAIble does not contain a mandatory runtime implementation. This document defines roles and contracts for building one when a project actually needs it.

## When to add orchestration
Use orchestration when several agents/tools must collaborate, work must move through explicit states, handoffs need to be durable, approval gates matter, or the human should not manually relay every bounded task.

Do not add it merely because multiple agents exist.

## Generic lifecycle
INTENT → PLAN → APPROVAL → DISPATCH → EXECUTION → EVIDENCE → VERIFICATION → REALITY CHECK → DONE / STOP / HUMAN

The names may differ. The important properties are explicit scope, explicit material approval, execution evidence, distinct verification, stoppable failure paths, and human escalation for unresolved consequential uncertainty.

## Essential contract
An orchestration component should answer:
- What task is running?
- What is its scope?
- What state is it in?
- Who or what is executing it?
- What evidence exists?
- What verification occurred?
- What remains uncertain?
- Why did it continue or stop?
- What requires human intervention?

A simulated callback is not the same as real dispatch.

## Three distinct claims
UNIT TEST ≠ REAL DISPATCH ≠ VERIFIED END-TO-END WORKFLOW

A unit test can show that code behaves as coded. Real dispatch shows an actual participant or execution surface received work. End-to-end verification shows the intended result was actually produced and checked.

Do not promote one claim into another.

## Watchdog role
A watchdog observes an existing workflow and reports health or anomalies. It should not become an unexplained second orchestrator.

DETECT → REPORT → DECIDE → ACT

Typical conditions:
- inactivity or stuck work;
- invalid state transitions;
- missing context;
- conflicting participant views;
- failed execution;
- unexpected terminal states;
- missing evidence.

## Watchdog safety
Do not autonomously repair a condition you cannot explain. For consequential remediation: detect, preserve evidence, report, establish authority, obtain approval when required, act, and verify.

## Build recipe
1. Define task states.
2. Define legal transitions.
3. Define task and evidence records.
4. Define approval gates.
5. Implement one bounded execution path.
6. Verify it independently.
7. Add real integrations only where required.
8. Add observability.
9. Build the watchdog around observable facts.
10. Test failure paths.
11. Run Reality Check before treating the system as ready for consequential use.

The implementation is yours. bAIble supplies construction principles, not somebody else's runtime.
