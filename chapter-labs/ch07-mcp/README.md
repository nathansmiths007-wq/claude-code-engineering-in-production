# Chapter 7 Lab — MCP

**Starting tag:** `ch06-hooks-ready`  
**Milestone:** `ch07-mcp-ready`

**Objective:** connect one external capability while preserving least privilege.

## Deliverables
- MCP configuration example
- `mcp-trust-review.md`
- `mcp-tool-matrix.md`

## Workflow
1. Identify the smallest external data/action surface the task requires.
2. Review publisher/owner, transport, authentication, tool list, backend credential privilege, data sensitivity, network reach, and revocation.
3. Separate read and write tools where possible.
4. Exercise one benign tool call and record the exact external effect.
5. Test untrusted content that tries to expand authority.

## Verification
Tool labels must match real authority, write access must be explicitly justified, and the task should still fail safely when the integration is unavailable.
