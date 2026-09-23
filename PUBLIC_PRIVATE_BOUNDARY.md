# Public / Private Boundary

This is a hard boundary for publishing bAIble-derived material.

## Public material
Safe public material can include principles, generic workflows, reusable templates, abstract architecture, terminology, generalized lessons, and synthetic examples that contain no private data.

## Keep private
Do not publish:
- passwords, API keys, tokens, cookies, private keys, credentials;
- personal identifiers;
- private conversations or exports;
- private repository contents;
- customer or confidential data;
- proprietary implementation details;
- internal paths, identifiers, access instructions, or private run evidence;
- hidden context;
- unpublished sensitive experiments;
- claims whose supporting evidence is inaccessible to the public reader.

## Generalization procedure
Before moving a private lesson into public bAIble:
1. remove identifying details;
2. remove secrets and access paths;
3. remove unnecessary project-specific implementation details;
4. rewrite the lesson so it stands alone;
5. check that it is understandable without the private source;
6. preserve uncertainty and limitations;
7. perform a final privacy review.

If it still depends on private context, keep it private.

## Public bAIble is not a private-system backup
Do not mirror a private runtime, execution history, data set, internal CI evidence, or project-specific architecture into this repository.

The public framework should teach someone how to construct their own implementation from generic contracts.

## Publication checklist
- [ ] no credentials
- [ ] no personal identifiers
- [ ] no private conversations
- [ ] no private repository data
- [ ] no customer/confidential data
- [ ] no internal paths or access instructions
- [ ] no private run IDs/evidence
- [ ] no hidden dependencies
- [ ] examples are synthetic or safely generalized
- [ ] important claims have public evidence or are clearly labeled proposals
