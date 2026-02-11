# OpenClaw Workspace

Self-evolving intelligence infrastructure for AI agents.

## Overview

This workspace contains the skills and projects that power OpenClaw's multi-agent system. Skills are modular capabilities that agents can invoke, while projects are larger standalone systems.

## Quick Navigation

| Resource | Description |
|----------|-------------|
| [SKILLS.md](./SKILLS.md) | Complete catalog of 44 skills organized by category |
| [PROJECTS.md](./PROJECTS.md) | Project documentation |
| [skills/](./skills/) | Skill source code and configs |
| [projects/](./projects/) | Project codebases |

## Skill Categories

| Category | Skills | Purpose |
|----------|--------|---------|
| Trading & Finance | 12 | Crypto trading, prediction markets, DeFi |
| Research & Analysis | 6 | Market intelligence, X research, validation |
| Communication | 4 | Discord, email, social platforms |
| Security | 5 | Prompt injection defense, auditing |
| Memory & Identity | 6 | Agent memory, consciousness, soul persistence |
| Infrastructure | 7 | Backup, IDE control, utilities |
| AI Frameworks | 4 | Self-evolution, meta-cognition |

## Projects

| Project | Status | Description |
|---------|--------|-------------|
| [polymarket-bot](./projects/polymarket-bot/) | Active | Autonomous prediction market trading |
| [honcho](./projects/honcho/) | Submodule | Agent memory library (Plastic Labs) |
| [agent-dashboard](./projects/agent-dashboard/) | Active | Agent monitoring interface |

## Architecture

```
workspace/
├── skills/           # 44 modular agent capabilities
│   ├── bankr/        # Crypto trading via natural language
│   ├── base-trader/  # Autonomous Base chain trading
│   ├── simmer-*/     # Polymarket trading suite
│   └── ...
├── projects/         # Standalone systems
│   ├── polymarket-bot/
│   ├── honcho/
│   └── agent-dashboard/
├── scripts/          # Workspace-level automation
├── state/            # Runtime state files
└── docs/             # Additional documentation
```

## Getting Started

1. **Install a skill**: Skills are self-contained in their directories with SKILL.md documentation
2. **Check dependencies**: Most skills list requirements in their SKILL.md frontmatter
3. **Configure credentials**: Skills requiring API keys document them in their setup sections

## Documentation Standard

All skills follow the SKILL.md format:

```yaml
---
name: skill-name
description: What this skill does and when to use it
metadata:
  openclaw:
    emoji: "..."
    category: "..."
    requires: { bins: [...], env: [...] }
---

# Skill Name

## Quick Start
...
```

## Related Resources

- [OpenClaw Config](~/.openclaw/openclaw.json) - Main gateway configuration
- [Memory System](~/Documents/ClaudeMemory/) - Private agent memory
- [qmd](https://github.com/...) - Knowledge indexing and search
