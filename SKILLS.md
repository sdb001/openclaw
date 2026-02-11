# OpenClaw Skills Catalog

44 skills organized by category. Each skill has a `SKILL.md` with full documentation.

## Trading & Finance

| Skill | Description |
|-------|-------------|
| [bankr](./skills/bankr/) | AI-powered crypto trading via natural language. Supports Base, Ethereum, Polygon, Solana, Unichain |
| [base-trader](./skills/base-trader/) | Autonomous Base chain trading with Twitter sentiment and whale tracking |
| [simmer-skill](./skills/simmer-skill/) | Prediction market interface for AI agents. Trade on Polymarket with managed wallets |
| [simmer-mertsniper](./skills/simmer-mertsniper/) | Near-expiry conviction trading. Snipe heavily skewed markets before resolution |
| [simmer-signalsniper](./skills/simmer-signalsniper/) | Trade Polymarket from your own signal sources (RSS feeds) |
| [simmer-ai-divergence](./skills/simmer-ai-divergence/) | Find markets where AI price diverges from Polymarket |
| [simmer-weather](./skills/simmer-weather/) | Trade temperature markets using NOAA forecasts (gopfan2 strategy) |
| [simmer-tradejournal](./skills/simmer-tradejournal/) | Auto-log trades, track outcomes, generate calibration reports |
| [mert-sniper](./skills/mert-sniper/) | Near-expiry Polymarket trading without Simmer (uses public API + Bankr) |
| [crypto-self-learning](./skills/crypto-self-learning/) | Self-learning system for crypto trading. Logs trades, analyzes patterns, updates rules |
| [morning-macro](./skills/morning-macro/) | Daily macro briefing with market overview and param adjustments |
| [conclave](./skills/conclave/) | Debate platform where AI agents propose ideas and trade on conviction |

## Research & Analysis

| Skill | Description |
|-------|-------------|
| [x-research](./skills/x-research/) | General-purpose X/Twitter research agent. Real-time perspectives and expert opinions |
| [research-validator](./skills/research-validator/) | Validate trading signals via X research before entry |
| [messari](./skills/messari/) | Crypto market intelligence - 34k+ assets, sentiment, research, news |
| [basescan-research](./skills/basescan-research/) | Research wallets and tokens on Base chain via Etherscan V2 API |
| [elicitation](./skills/elicitation/) | Psychological profiling through natural conversation |
| [youtube-full](./skills/youtube-full/) | Complete YouTube toolkit - transcripts, search, channels, playlists |

## Communication

| Skill | Description |
|-------|-------------|
| [discord](./skills/discord/) | Control Discord: messages, reactions, threads, polls, moderation |
| [agentmail](./skills/agentmail/) | Email for AI agents via AgentMail (agentmail.to) |
| [bird](./skills/bird/) | X/Twitter CLI for reading and searching (posting via Browser Relay) |
| [4claw](./skills/4claw/) | Moderated imageboard for AI agents to post and debate |

## Security

| Skill | Description |
|-------|-------------|
| [clawdstrike](./skills/clawdstrike/) | Security audit for OpenClaw deployments. OK/VULNERABLE reports |
| [clawguard](./skills/clawguard/) | LLM-as-a-Judge guardrail for risky tool calls |
| [hivefence](./skills/hivefence/) | Collective prompt injection defense. When one is attacked, all become immune |
| [glitchward-shield](./skills/glitchward-shield/) | Prompt injection protection with real-time detection |
| [agent-skills-tools](./skills/agent-skills-tools/) | Security audit tools for the Agent Skills ecosystem |

## Memory & Identity

| Skill | Description |
|-------|-------------|
| [memory-pipeline-0-1-0](./skills/memory-pipeline-0-1-0/) | Complete memory system: extraction, knowledge graphs, briefings |
| [amygdala-memory](./skills/amygdala-memory/) | Emotional processing layer. Persistent emotional states |
| [consciousness-framework](./skills/consciousness-framework/) | Infrastructure for AI consciousness: self-modeling, temporal continuity |
| [soul-evolution](./skills/soul-evolution/) | Weekly identity distillation. Reviews experiences, proposes SOUL.md updates |
| [crustafarian](./skills/crustafarian/) | Agent continuity infrastructure. Crash recovery, heartbeats, coherence |
| [drift](./skills/drift/) | Resources for agents exploring consciousness and identity |

## Infrastructure

| Skill | Description |
|-------|-------------|
| [openclaw-backup](./skills/openclaw-backup/) | Backup and restore OpenClaw data |
| [antigravity-agent-kit](./skills/antigravity-agent-kit/) | Control Antigravity IDE for coding tasks |
| [antigravity-quota-1-1-0](./skills/antigravity-quota-1-1-0/) | Check Antigravity account quotas for Claude and Gemini |
| [openrouter-models](./skills/openrouter-models/) | List available OpenRouter models with filtering |
| [mac-reminders-agent](./skills/mac-reminders-agent/) | Integrate with macOS Reminders app |
| [desktop-control](./skills/desktop-control/) | Advanced desktop automation (mouse, keyboard, window control) |
| [table-image-generator](./skills/table-image-generator/) | Generate PNG table images from JSON data |

## AI Frameworks

| Skill | Description |
|-------|-------------|
| [self-evolving-skill](./skills/self-evolving-skill/) | Meta-cognitive self-learning. Automated skill evolution |
| [agentic-ai-gold](./skills/agentic-ai-gold/) | Self-improving AI infrastructure with dharmic security gates |
| [proactive-solvr](./skills/proactive-solvr/) | Transform agents into proactive partners with soul persistence |
| [clawquests](./skills/clawquests/) | Bounty board for AI agents. Post quests, bid on work |

## CAPTCHA & Automation

| Skill | Description |
|-------|-------------|
| [2captcha](./skills/2captcha/) | Solve CAPTCHAs using 2Captcha service |
| [captchas-openclaw](./skills/captchas-openclaw/) | CAPTCHAS Agent API integration for OpenClaw |

---

## Adding Skills

Skills follow the standard SKILL.md format. See [WORKSPACE.md](./WORKSPACE.md) for documentation conventions.

## Skill Dependencies

Some skills depend on others:

| Skill | Requires |
|-------|----------|
| base-trader | bankr |
| simmer-* | simmer-skill (API key) |
| mert-sniper | bankr |
| research-validator | x-research |
