# Observability, Cost, and Context

A production agentic workflow should expose four signal families:

```text
QUALITY
verification, review, delivery outcome

BEHAVIOR
tools, MCP, Hooks, Skills, plugins, subagents

RESOURCE
tokens, estimated cost, duration, context pressure

SECURITY
permission decisions, denials, mode/config changes, authentication/integration anomalies
```

Useful operating measures include cost per accepted PR, time to verified change, blocking defects found, rollback rate, CI/deployment failure rate, and human-review effort.

Do not log sensitive content merely because telemetry supports it. Start with redacted/minimal signals, control retention/access, and keep the telemetry pipeline itself inside the security model.
