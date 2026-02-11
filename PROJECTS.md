# OpenClaw Projects

Standalone systems in the workspace.

## Active Projects

### polymarket-bot

**Status:** Active
**Location:** [projects/polymarket-bot/](./projects/polymarket-bot/)

AI-powered prediction market trading system targeting high-volume autonomous execution.

**Capabilities:**
- Arbitrage detection (pure and combinatorial) across 1500+ markets
- LLM-based event probability estimation with chain-of-thought reasoning
- Sub-100ms latency execution with parallel order processing
- Portfolio-level risk controls, correlation tracking, drawdown limits

**Target Metrics:**
| Metric | Target |
|--------|--------|
| Monthly Volume | $40M+ |
| Win Rate | 60%+ |
| Sharpe Ratio | 2.0+ |
| Max Drawdown | <15% |

**Architecture:** Scanner → Forecaster → Executor → Risk Manager

---

### honcho

**Status:** Submodule (upstream: Plastic Labs)
**Location:** [projects/honcho/](./projects/honcho/)

Open source memory library for building stateful agents. Enables agents to build and maintain state about entities (users, agents, groups, ideas) that change over time.

**Key Features:**
- Continual learning system for entity understanding
- Works with any model, framework, or architecture
- Managed service available at app.honcho.dev
- Python and JavaScript SDKs

**Version:** 3.0.2

---

### agent-dashboard

**Status:** Active
**Location:** [projects/agent-dashboard/](./projects/agent-dashboard/)

Web-based monitoring interface for OpenClaw agents.

**Stack:** React + TypeScript + Vite

---

## Project vs Skill

| Aspect | Projects | Skills |
|--------|----------|--------|
| Scope | Standalone systems | Modular capabilities |
| Independence | Run independently | Invoked by agents |
| State | Own databases/state | Minimal or shared state |
| Deployment | Separate processes | Loaded into agent context |

## Adding Projects

Projects live in `projects/` and should include:
- `README.md` with setup and usage
- Clear dependency documentation
- Integration points with OpenClaw (if applicable)
