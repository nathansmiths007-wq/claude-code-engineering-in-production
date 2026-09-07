# Claude Code Engineering in Production

Companion repository for **Claude Code Engineering in Production** by **Dan Blackwood**.

> Build Reliable AI Coding Workflows with Agents, Skills, MCP, Hooks, GitHub, Testing, CI/CD, Security, and Real-World Software Projects.

## Book / Repository Contract

The printed book teaches the durable production-engineering model. This repository carries the runnable-lab structure, templates, configuration examples, failure exercises, and version-sensitive Claude Code notes that can evolve after publication.

- **Book edition:** 1.0
- **Technical baseline:** September 2026
- **Author:** Dan Blackwood
- **Companion URL:** https://github.com/nathansmiths007-wq/claude-code-engineering-in-production
- **Printed release baseline:** `v1.0-book-release` (to be created when publication contents are frozen)
- **Current corrections:** `main`

## Production Reliability Model

```text
GOOD CONTEXT
+ LIMITED AUTHORITY
+ CLEAR SPECIFICATION
+ ISOLATED WORK
+ TESTING
+ INDEPENDENT REVIEW
+ SECURITY
+ OBSERVABILITY
+ RECOVERY
= CONTROLLED AGENTIC ENGINEERING
```

Core rule:

> **Autonomy must never increase faster than verification and control.**

## Repository Map

```text
northstar/              Progressive reference application and architecture notes
chapter-labs/           Chapter-aligned hands-on labs
projects/               Three end-to-end production projects
claude-config/          CLAUDE.md, rules, settings and permission examples
skills/                 Reusable engineering procedures
agents/                 Specialist agent templates
hooks/                  Deterministic guardrail examples
mcp/                    MCP configuration and security examples
plugins/                Team extension-layer examples
agent-sdk/              Programmatic orchestration examples
github-actions/         CI and PR automation examples
failure-labs/           Controlled failure and recovery exercises
security/               Threat models and review checklists
observability/          Telemetry, cost and evidence patterns
troubleshooting/        Recovery-oriented troubleshooting notes
templates/              Specifications, handoffs, PRs and runbooks
checklists/              Production readiness checklists
```

## How to Use This Repository

1. Use the milestone named in the chapter as the starting state.
2. Read the lab README before running commands.
3. Use disposable or staging environments for destructive/failure exercises.
4. Treat examples involving permissions, credentials, MCP, Hooks, CI, and deployment as environment-specific and review them before use.
5. Check `CURRENT_FEATURES.md` when a Claude Code flag, mode, preview feature, UI, or integration differs from the printed book.

## Milestone Sequence

```text
book-start
ch04-context-ready
ch05-skills-ready
ch06-hooks-ready
ch07-mcp-ready
ch08-agents-ready
ch09-plugin-ready
ch12-verification-ready
ch14-parallel-ready
ch16-secure-ready
ch18-ci-ready
project-1-complete
project-2-complete
production-final
```

Not every chapter creates a global tag. The book explains when a lab continues from the previous verified state without publishing another repository milestone.

## Important Safety Note

Do not connect example workflows to real production systems simply to complete a lab. Use least-privilege credentials, disposable branches/worktrees, test data, staging infrastructure, and an explicit recovery path.

## Corrections and Updates

- `CURRENT_FEATURES.md` — fast-moving Claude Code behavior
- `CHANGELOG.md` — repository evolution
- `ERRATA.md` — corrections to printed claims/examples
- `BOOK_VERSION.md` — edition and release baseline

## License

No open-source license has been selected for this companion repository yet. Until a license is added, normal copyright restrictions apply.
