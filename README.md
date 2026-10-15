### Hi, I'm Dheeraj 👋

I'm a computer science master's student (M.Sc. Software Engineering and Intelligent Systems) at RPTU Kaiserslautern, Germany. I build backend and AI systems with Python, FastAPI, PostgreSQL, React and TypeScript. My main project is **Spanlight**.

Open to working student roles (up to 20 hours a week). [LinkedIn](https://www.linkedin.com/in/dkarwasra)

## Skills

| Area | Tools |
|---|---|
| **Languages** | Python · TypeScript · JavaScript · SQL · C++ |
| **Backend** | FastAPI · SQLAlchemy · Alembic · REST · NestJS · Node.js · Express · GraphQL |
| **Frontend** | React · TanStack Query · Redux · Vite · Tailwind CSS |
| **Data** | PostgreSQL (row-level security) · MySQL · MongoDB · Redis · ChromaDB |
| **Cloud & DevOps** | Docker · GitHub Actions · Railway · AWS · Linux |
| **Testing** | pytest · Vitest · Playwright |
| **AI & LLMs** | LangChain · LangGraph · CrewAI · MCP · RAG · OpenAI and Anthropic APIs · LLM observability · scikit-learn · pandas · NumPy |

## Spanlight

**Open-source LLM observability.** See every prompt, completion, token, cost, latency and error as traces and sessions, then act on them:

- **Tracing** with a Python SDK (`pip install spanlight`) or any OpenTelemetry exporter (`gen_ai.*`)
- **The Doctor**: fifteen deterministic detectors that find retry storms, ignored `Retry-After` and other costly patterns, each with evidence, a fix and a check
- **Gateway**: one base URL for OpenAI and Anthropic clients, with retries, fallbacks, caching and budgets that block
- **Prompts and evals**: versioned prompts, datasets, LLM judges on a budget, experiments, and a GitHub Action that fails a pull request when quality drops
- **Self-hosted on one Postgres**, MIT licensed

**How it's built:** tenant isolation enforced by Postgres row-level security on every project table, idempotent ingestion, and 2,000+ backend tests, including failure injection (killed connections, interrupted streams, concurrent budget checks) against a real database. Live at [spanlight.dev](https://spanlight.dev).

[Live demo](https://spanlight.dev) · [Docs](https://spanlight.dev/docs/) · [Repository](https://github.com/dheerajkarwasra/spanlight) · [PyPI](https://pypi.org/project/spanlight/)

## Other projects

- [Nexus](https://github.com/dheerajkarwasra/Nexus-Agentic-Document-Intelligence): privacy-first local RAG with hybrid search, HyDE, re-ranking, agentic routing and faithfulness checks
- [Gatekeeper](https://github.com/dheerajkarwasra/Gatekeeper): a reverse proxy gateway between the internet and internal services
- [ESN Events](https://github.com/dheerajkarwasra/esn): event management for ESN chapters on NestJS GraphQL, Postgres, Redis and Auth0
- [ByteSphere](https://github.com/dheerajkarwasra/ByteSphere): a blog platform
- [LocalMart](https://github.com/dheerajkarwasra/LocalMart): a local marketplace with a lost and found section (React, Firebase)
