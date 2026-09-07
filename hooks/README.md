# Hooks as Deterministic Guardrails

Use Hooks where a lifecycle event should trigger a deterministic check, transformation, audit, or completion gate.

Examples:

```text
formatting/
testing/
security/
completion-gates/
```

A production Hook needs an explicit design record:

```text
Event
Matcher
Purpose
Input
Validation
Action
Blocking behavior
Timeout behavior
Failure behavior
Logging
Security
Tests
```

Do not assume an ordinary nonzero shell exit always blocks the Claude Code action. Hook semantics differ by event and can evolve. Verify the exact current event behavior before relying on a Hook as an enforcement boundary.

Required tests should cover success, prohibited input, malformed input, missing dependencies, timeouts, and malformed Hook output.
