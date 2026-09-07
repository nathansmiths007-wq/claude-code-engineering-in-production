# Plugins and Team Extension Layers

Plugins package reusable team capability such as Skills, agents, Hooks, MCP configuration, code intelligence/LSP integration, and other extension components.

Review plugins as software dependencies:

- source and maintainer;
- version/update mechanism;
- included Skills/agents/Hooks/MCP;
- binaries and network access;
- credential reach;
- supply-chain trust;
- security review and approval.

Project `.claude/` configuration remains the authoritative project truth; a plugin should extend the harness, not silently replace repository policy.
