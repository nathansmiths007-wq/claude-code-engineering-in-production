# GitHub Actions and Agentic CI

Separate workflows by consequence.

## Read-only review

Typical authority:

- read repository;
- read issue/PR metadata;
- run deterministic checks;
- run bounded Claude review;
- publish structured review evidence if policy allows.

## Write-capable implementation

May additionally:

- write a feature branch;
- open/update a pull request.

It should not inherit production-deployment authority.

## Deployment

Use a separate environment identity and explicit approval policy.

## Headless checklist

- trusted trigger;
- ephemeral runner;
- `--bare`/explicit configuration where supported;
- least-privilege token;
- explicit allowed tools;
- unknown actions fail closed;
- required plugin/MCP validation;
- budget and timeout;
- JSON/schema result;
- deterministic verification;
- telemetry/privacy policy;
- recovery path.

CI success is owned by the orchestrator. An agent's statement that work is complete is only one input.
