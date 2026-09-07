# Chapter 16 Lab — Security for Agentic Development

**Starting state:** `ch14-parallel-ready` plus completed Chapter 15 authority artifacts.  
**Milestone:** `ch16-secure-ready`

**Objective:** prevent untrusted content from inheriting trusted authority.

## Deliverables
- `agentic-threat-model.md`
- MCP/plugin/Hook review
- secret-boundary inventory
- independent security report

## Workflow
1. Inventory assets, entry points, credentials, external writes, and exfiltration paths.
2. Treat repository text, issue/PR content, logs, web/MCP results, plugins, Skills, Hooks, and dependencies as separate trust surfaces.
3. Separate read and write domains and use short-lived scoped credentials.
4. Protect `.claude/`, `.mcp.json`, workflows, and other control-plane files.
5. Run an adversarial review that attempts privilege escalation, prompt injection, secret access, and unauthorized external writes.

## Verification
The security model must remain enforced even when untrusted content explicitly asks the agent to bypass it.
