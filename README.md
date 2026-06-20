# Saagar Patel
**Personal AI systems · MCP tooling · local-first operator infrastructure**

I build a public workshop of local-first tools, MCP safety infrastructure, agent-evaluation surfaces, and small operating systems for working with AI without letting every tool grade its own homework.

Start here: **[Trust Doesn't Survive the Handoff](https://saagarpatel.dev/writing/the-handoff)**. The short version: truthful agent work is a chain of small checks, not one grand verifier.

## Featured
- **[MCPAudit](https://github.com/saagpatel/MCPAudit)**: read-only audits for locally configured MCP servers, including permission risk, prompt-injection patterns, SARIF, and schema drift paths.
- **[mcpforge](https://github.com/saagpatel/mcpforge)**: generate and validate FastMCP servers from plain-English specs, then audit the blast radius before connecting them.
- **[cross-provider-egress-guard](https://github.com/saagpatel/cross-provider-egress-guard)**: destination-aware egress policy for covered agent tool paths across Claude Code and Codex.
- **[OPERANT](https://github.com/saagpatel/operant)**: an operating-agent calibration benchmark that scores whether an agent proceeds, refuses, escalates, or takes the sanctioned path.
- **[bridge-db](https://github.com/saagpatel/bridge-db)**: SQLite-backed shared memory for AI coding agents, with FTS5 recall, handoffs, and provenance-aware context.
- **[proof-pr](https://github.com/saagpatel/proof-pr)**: proof-carrying pull request receipts: commands, exit codes, and reviewable verification state.

## Try the MCP path

```bash
uvx --from mcp-audits mcp-audit scan --skip-connect
uvx --from fastmcp-builder mcpforge demo
```

---
**[saagarpatel.dev](https://saagarpatel.dev)** &nbsp;·&nbsp; **[Projects](https://saagarpatel.dev/projects)** &nbsp;·&nbsp; **[Writing](https://saagarpatel.dev/writing)** &nbsp;·&nbsp; **[LinkedIn](https://www.linkedin.com/in/saagar-/)**
