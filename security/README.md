# Security Reference

Core rule:

> **Untrusted content must never be allowed to inherit trusted authority.**

Review these boundaries whenever agent authority increases:

- repository instructions and cloned configuration;
- issue/PR/web content;
- secrets and environment variables;
- MCP servers and backend credentials;
- plugins and Hooks;
- dependency installation;
- GitHub Actions tokens;
- deployment identities;
- logs and telemetry.

## Security review checklist

```text
Authentication
Authorization
Tenant isolation
Sensitive-data handling
Secret exposure
Prompt injection
External writes
Dependency/supply chain
Logging/telemetry
Recovery/revocation
```

Use short-lived scoped credentials where possible. If a credential may have been exposed, deleting local content is not enough: contain, revoke, rotate, audit, repair, and add a durable prevention control.
