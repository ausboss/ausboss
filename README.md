# Hey, I'm Austin

I build agent-native tools for real operational systems: MCP integrations, safe JSON CLIs, IBM i automation, and reusable agent workflows.

By day, I run IT for an auto-auction environment where software has to work across IBM i, Windows, Linux, vendor platforms, and production constraints. That shapes how I build: clear interfaces, structured output, read-only and dry-run modes, explicit approval gates, and verification that the thing actually worked.

## What I'm building

- [bluebubbles-relay](https://github.com/ausboss/bluebubbles-relay) — give an AI agent a phone through a safety-gated BlueBubbles CLI.
- [5250ng](https://github.com/ausboss/5250ng) — contributing to a modern TN5250 terminal for IBM i.
- [agent-harness-resources](https://github.com/ausboss/agent-harness-resources) — reusable skills, agents, hooks, and plugins for coding-agent harnesses.
- [dictate-type-situation](https://github.com/ausboss/dictate-type-situation) — push-to-talk Whisper dictation for Linux/Wayland.
- [mcp-ollama-agent](https://github.com/ausboss/mcp-ollama-agent) — a TypeScript example of an Ollama agent using multiple MCP servers.

## Earlier work

I've been building with local models and AI companions since 2023. A few projects people still find useful:

- [Local-LLM-Langchain](https://github.com/ausboss/Local-LLM-Langchain)
- [PygDiscordBot](https://github.com/ausboss/PygDiscordBot)
- [DiscordLangAgent](https://github.com/ausboss/DiscordLangAgent)

## How I ship

I treat agent-facing interfaces as product interfaces: predictable JSON, useful errors, least-privilege defaults, dry runs for risky operations, and tests around real failure modes. For maintained projects, I prefer an issue, a focused branch, tests and a test plan, CI, a self-reviewed diff, and a squash merge.
