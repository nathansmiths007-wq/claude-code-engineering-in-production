# Agent SDK / Programmatic Orchestration

The final project can be implemented with `claude -p` for a portable CI baseline or through the current Claude Agent SDK when richer programmatic control is required.

Durable orchestration model:

```text
ORCHESTRATOR
      ↓
BOUNDED AGENT EXECUTION
      ↓
STRUCTURED EVIDENCE
      ↓
POLICY TRANSITION
```

Use the SDK when you need native message objects, callbacks, custom approval logic, structured service integration, explicit interruption, or deeper event processing.

Do not make delivery correctness depend on one SDK method name or model identifier. Track current APIs in `CURRENT_FEATURES.md`.

Production requirements:

- explicit configuration;
- least-privilege tools/credentials;
- bounded cost/time/turns;
- machine-readable results;
- control-plane validation;
- deterministic verification;
- observable failure;
- recovery.
