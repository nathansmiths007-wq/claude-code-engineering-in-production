# Northstar Reference Application

Northstar is the progressive application used throughout the book. It represents a realistic multi-tenant SaaS codebase rather than a toy prompt demo.

## Reference architecture

```text
northstar/
├── backend/
│   ├── app/
│   │   ├── api/
│   │   ├── auth/
│   │   ├── models/
│   │   ├── services/
│   │   └── main.py
│   └── tests/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── tests/
│   └── package.json
├── database/
│   └── migrations/
├── docs/
│   ├── architecture/
│   ├── decisions/
│   └── specifications/
├── scripts/
├── .github/workflows/
└── .claude/
```

Reference stack: Python API, React/TypeScript, PostgreSQL, automated tests, GitHub Actions, and containerized staging.

The repository may evolve toward a package-style monorepo as the later chapters introduce worktrees, shared contracts, agents, audit, and delivery automation. Preserve behavior and milestones over cosmetic directory identity.
