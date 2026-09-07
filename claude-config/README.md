# Claude Code Configuration Reference

This directory is the home for project-level examples covering:

```text
claude-md/
rules/
settings/
permissions/
```

## Root instruction principles

Keep repository-wide instructions concise and durable:

- investigate before modifying unfamiliar code;
- prefer existing architecture;
- do not change public behavior without an approved specification;
- do not weaken tests to force a pass;
- keep authorization centralized;
- do not edit generated/vendor files directly;
- do not install dependencies without justification;
- do not push protected branches.

Use package-level `CLAUDE.md` files or path-scoped rules for local conventions instead of expanding the root file indefinitely.

## Permission principles

Use the book's Allow / Ask / Deny model. Persistent approvals should be audited as permission debt. Pair model-level permissions with sandboxing, GitHub/database/IAM controls, and scoped credentials where the real authority lives outside Claude Code.
