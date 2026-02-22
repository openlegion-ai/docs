# OpenLegion Docs

Documentation site for [OpenLegion](https://github.com/openlegion-ai/openlegion) — the open-source, container-isolated AI agent framework.

**Live:** [docs.openlegion.ai](https://docs.openlegion.ai)
**Landing:** [openlegion.ai](https://openlegion.ai)
**Engine:** [github.com/openlegion-ai/openlegion](https://github.com/openlegion-ai/openlegion)

Powered by [Mintlify](https://mintlify.com).

## Contents

- **Getting Started** — Overview, quickstart guide
- **Concepts** — Architecture, security model
- **Features** — Agents, workflows, memory, triggering, channels, dashboard, MCP, cost tracking
- **Reference** — CLI commands, configuration, all 37 built-in agent tools

## Development

Install the Mintlify CLI to preview docs locally:

```bash
npm i -g mint
mint dev             # http://localhost:3000
```

## Structure

```
├── docs.json                — Mintlify configuration and navigation
├── index.mdx                — Landing page
├── quickstart.mdx           — Installation and setup guide
├── concepts/
│   ├── architecture.mdx     — Trust zones, mesh host, containers
│   └── security.mdx         — 5-layer defense model
├── features/
│   ├── agents.mdx           — Agent containers, task/chat modes
│   ├── workflows.mdx        — Deterministic DAG orchestration
│   ├── memory.mdx           — 5-layer memory system
│   ├── triggering.mdx       — Cron, heartbeats, webhooks, watchers
│   ├── channels.mdx         — Telegram, Discord, Slack, WhatsApp
│   ├── dashboard.mdx        — Real-time web monitoring UI
│   ├── mcp.mdx              — Model Context Protocol integration
│   └── cost-tracking.mdx    — Per-agent budget enforcement
└── reference/
    ├── cli.mdx              — CLI and REPL command reference
    ├── configuration.mdx    — Config files and environment variables
    └── agent-tools.mdx      — All 37 built-in tools
```

## Contributing

Found an error or something missing? Issues and pull requests welcome.

## License

MIT
