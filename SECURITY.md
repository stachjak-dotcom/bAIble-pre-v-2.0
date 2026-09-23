# Security

## Never publish

- passwords, API keys, tokens, SSH keys, cookies
- personal identifiers
- private conversation exports
- private repository contents
- confidential customer or proprietary data
- hidden context or inaccessible references
- secrets in logs

## Before sharing

Ask: Does this contain private/personal information? Does it reveal an access path? Does it depend on hidden context? Can another person reproduce the claim? Is the specificity necessary?

## Access

Use least privilege. Prefer read-only inspection when writing is unnecessary. Keep credentials outside source control. Separate environments where practical. Require explicit approval for destructive or irreversible actions.

Security must be enforced by the real access layer. Hiding a control in a UI is not authorization.
