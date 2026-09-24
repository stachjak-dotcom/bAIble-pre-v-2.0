# v0.1 → v2 Audit

This is a migration audit, not a replacement for the foundation.

## Result

The current v2 contains the major public concepts from v0.1:

| v0.1 concept | v2 location | Status |
|---|---|---|
| AI as collaborator, not authority | BIBLE.md / FOUNDATION_V0_1.md | preserved |
| Outcome over implementation | FOUNDATION_V0_1.md / BIBLE.md | preserved |
| Uncertainty / no silent guessing | BIBLE.md / REALITY_CHECK.md | preserved |
| Rules 001–012 | BIBLE.md / FOUNDATION_V0_1.md | preserved and extended |
| lAInguage: Explore / Propose / Prepare / Implement / Verify / Review | FOUNDATION_V0_1.md | restored explicitly |
| Human / Product Owner | AGENT_ROLES.md | restored explicitly |
| Architect | AGENT_ROLES.md | restored explicitly |
| Developer | AGENT_ROLES.md | restored explicitly |
| QA | AGENT_ROLES.md | restored explicitly |
| Reviewer | AGENT_ROLES.md | restored explicitly |
| Documentation Agent | AGENT_ROLES.md | restored explicitly |
| Agent profile | AGENT_PROFILE.md | preserved as concrete-agent contract |
| Agent handoff | HANDOFF.md | preserved and made role-aware |
| Agent evaluation | VERIFICATION.md / SELF_AUDIT.md | preserved in generalized form |
| Lessons learned | LESSONS_LEARNED.md | preserved and generalized |
| Scope control | BIBLE.md / HANDOFF.md | preserved |
| Least privilege | BIBLE.md / SECURITY.md | preserved |
| Approval gates | BIBLE.md / SECURITY.md | preserved |
| Decision records | WORKSPACE_TEMPLATE/DECISIONS.md | preserved |
| Versioning / learning from mistakes | ORIGIN_AND_PURPOSE.md / FOUNDATION_V0_1.md | preserved |
| Original identity / voice | SONG_TWO.md / START_HERE.md | partially restored; historical source checked below |

## Important findings

### 1. Roles were lost as definitions

v0.1 explicitly defined roles. v2 originally retained a profile template but not the role definitions. This was a real migration loss.

**Fixed:** AGENT_ROLES.md.

### 2. Handoff survived, but the responsibility chain was weakened

The v2 handoff kept the information fields but did not make sender/receiver roles explicit.

**Fixed:** role-aware handoff fields were added.

### 3. lAInguage was easy to lose

The action vocabulary was part of v0.1's practical interface between human and agent. It is now preserved in FOUNDATION_V0_1.md.

### 4. Evaluation survived conceptually

The original evaluation scenarios are still represented by the current verification/self-audit material. They should not be confused with application tests.

### 5. Public/private separation is mostly new v2 material

This is an evolution, not something that should be falsely presented as part of v0.1. It belongs to v2's expansion.

### 6. rAIda, Basecamp and Watchdog are v2 extensions

These are not required to understand the v0.1 foundation. They remain optional layers.

### 7. Historical voice has now been checked

The two quotations used in SONG_TWO.md were checked against the original v0.1 README.md and BIBLE.md:

- “bAIble is not a manual for making AI obey. It is a framework for working well with AI.”
- “The goal is not perfect instructions. The goal is a system that becomes more reliable through use.”

Both are supported by the original v0.1 repository.

The **Wolf/paw reference is not being presented as v0.1 history**. It belongs to the later identity/context of the project and is intentionally kept as a subtle Easter egg rather than explained as part of the original foundation.

## Migration rule

When adding to v2, ask:

> Is this a preserved foundation, an intentional evolution, or a new optional layer?

If it is none of those, the change needs another Reality Check.
