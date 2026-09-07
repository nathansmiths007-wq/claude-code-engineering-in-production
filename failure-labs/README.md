# Failure Labs

The failure labs are designed to teach diagnosis and recovery rather than only happy-path implementation.

```text
context-pollution/
hallucinated-api/
modified-tests/
wrong-files/
agent-collision/
excessive-permissions/
destructive-command/
runaway-agent/
```

Use this structure:

```text
SYMPTOM
      ↓
CAUSE
      ↓
DIAGNOSIS
      ↓
FIX
      ↓
VERIFY
      ↓
PREVENT RECURRENCE
```

For operational incidents add:

```text
CONTAIN
PRESERVE EVIDENCE
RECOVER
ROOT CAUSE
GUARDRAIL UPDATE
```

Run destructive examples only in disposable environments.
