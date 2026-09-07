# Chapter 9 Lab — Plugins and Code Intelligence

**Starting tag:** `ch08-agents-ready`  
**Milestone:** `ch09-plugin-ready`

**Objective:** package reusable team capability and compare lexical search with semantic/code-intelligence navigation.

## Deliverables
- plugin skeleton/reference manifest
- `plugin-trust-review.md`
- `search-vs-lsp.md`

## Workflow
1. Package one reusable Skill/agent/Hook combination as a team extension.
2. Review source, versioning, binaries, network access, credentials, MCP, Hooks, and update mechanism.
3. Use text search to find a symbol/call path, then repeat with LSP/code intelligence.
4. Record where semantic navigation reduces ambiguity or false matches.
5. Keep project `.claude/` configuration authoritative.

## Verification
The plugin should extend the harness without silently redefining project policy, and its supply-chain surface must be documented.
