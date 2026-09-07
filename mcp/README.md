# MCP Integration and Security

MCP connects Claude Code to systems outside the repository. Treat each server as a trust and authority boundary.

Review before enabling:

- purpose and publisher/owner;
- transport and scope;
- authentication and credential privilege;
- exact tool list;
- read/write classification;
- data sensitivity;
- prompt-injection exposure;
- network reach;
- human approval requirements;
- revocation path;
- verification.

Core rule:

> A tool's displayed name is not its security boundary. Review what the implementation and backend credential can actually do.

Prefer separate read and write domains, least-privilege credentials, and explicit approval for consequential external mutations.
