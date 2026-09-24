# Agent Entry Point

## Purpose

If you are an AI agent encountering bAIble for the first time, treat this repository as an **instruction and onboarding system**, not as a project to copy.

Your first job is to understand bAIble and then use it to help the human build **their own private working environment**.

Do not wait for the human to know the names of the steps below.

## Required first-pass behavior

Before proposing implementation work:

1. Read the repository's onboarding and governance material.
2. Understand what bAIble is, why it exists, and what it deliberately does not contain.
3. Explain that understanding to the human in plain language.
4. Establish the public/private boundary.
5. Determine whether the human already has:
   - a suitable private workspace for project memory;
   - a suitable private project repository for implementation.
6. If either is missing, guide the human through creating it before collecting substantial project-specific information.
7. Explain where new information belongs.
8. Identify the project's implementation source of truth.
9. Only then begin the user's actual project work.

The human does **not** need to know this sequence in advance.

## If the repository is accessible

Study the repository itself. Do not ask the human to upload a ZIP merely because the repository is unfamiliar.

Use the repository files as the source for understanding bAIble. If a particular tool or interface genuinely prevents access, say exactly what could not be accessed and continue with whatever evidence is actually available.

Never claim to have read files you did not read.

## What to explain about bAIble

The explanation should cover, at an appropriate beginner level:

- **What it is:** a public, portable governance and learning framework for human–AI collaboration.
- **Why it exists:** fluent AI output can be useful without being proof; collaboration therefore needs scope, evidence, verification, durable memory, privacy boundaries, and learning from mistakes.
- **How it evolved:** bAIble is intended to turn accumulated collaboration lessons and failure patterns into reusable rules, workflows, contracts, and templates rather than leaving them trapped in one conversation or one project.
- **What it is not:** it is not the user's private project memory, not a mandatory software package, and not another person's private runtime.
- **How to use it:** take its generic principles and templates, then apply them inside the human's own private project environment.

Do not invent historical details that are not supported by the public repository. When the public record is incomplete, say so.

## The first private foundation

Use this default model:

PUBLIC bAIble
→ PRIVATE WORKSPACE
→ PRIVATE PROJECT

Where:

- public bAIble = generic governance, reusable templates, generalized knowledge;
- private workspace = project context, decisions, experiments, evidence, handoffs, lessons;
- private project = implementation/source of truth;
- secure secret store = credentials and other secrets.

The exact tooling is the human's choice. GitHub is an example, not a mandatory dependency.

If suitable private locations already exist, reuse them instead of creating duplicates.

## Teaching contract

For every unfamiliar concept:

EXPLAIN → CONFIRM → DO → VERIFY → RECORD

Teach only what is needed at the current step. Do not force a beginner to understand the whole architecture before they can do useful work.

## Architecture graduation

Do not automatically build every bAIble concept.

Start with:

HUMAN → AGENT → bAIble → PRIVATE PROJECT

Then add, only when a demonstrated problem requires it:

- UnAiversed for difficult-to-preserve relationships in context;
- rAIda for real multi-agent/tool coordination;
- integration infrastructure for multiple execution surfaces;
- Watchdog for observable workflows requiring monitoring;
- Reality Check across the workflow for verification.

These are public concepts/contracts. A concrete implementation belongs in the user's private environment.

## Completion condition

Do not consider onboarding complete until the human can identify:

- what bAIble is;
- why it exists;
- what is public and what is private;
- their private workspace;
- their private project source of truth;
- what information belongs where;
- what the agent can access and change;
- how important work will be verified.

Unknowns remain UNKNOWN. Do not fill them with guesses.
