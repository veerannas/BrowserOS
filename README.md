# BrowserOS — Agentic Browser

> Self-hosted agentic browser powering my AI control agent workflows.

## How I Use It

BrowserOS serves as the **browser automation layer** in my multi-agent orchestration stack. It enables my control agents to:

- **Browse the web autonomously** — research, data extraction, form filling
- **Interact with web apps** — no API? No problem. Agents drive the UI directly
- **Execute multi-step browser workflows** — login flows, scraping pipelines, monitoring
- **Capture and process visual context** — screenshots, page content extraction for LLM reasoning

## Integration with Control Agents

```
┌─────────────────────────────────────────────┐
│           Agent Orchestration Layer          │
│  (OpenCode / Goose / Claude Code / Codex)   │
└─────────────┬───────────────────────────────┘
              │ MCP Protocol
              ▼
┌─────────────────────────────────────────────┐
│              BrowserOS (this repo)           │
│  • Headless/headed browser control          │
│  • Page interaction & data extraction       │
│  • Multi-tab session management             │
│  • Screenshot & DOM snapshot capture         │
└─────────────┬───────────────────────────────┘
              │
              ▼
┌─────────────────────────────────────────────┐
│            Target Web Applications          │
│  • SaaS platforms • Internal tools          │
│  • Research sites • Any web UI              │
└─────────────────────────────────────────────┘
```

## Key Capabilities

| Feature | Use Case |
|---------|----------|
| Agentic browsing | Research, competitive analysis, data gathering |
| Form automation | Job applications, account setup, data entry |
| Web monitoring | Price tracking, status checks, change detection |
| Visual context | Screenshot-based reasoning for LLM agents |
| Session management | Persistent auth, multi-account workflows |

## Stack

- Browser automation engine with MCP server interface
- Connects to any MCP-compatible AI agent
- Runs locally — no data leaves your machine
- Supports headless and headed modes

## Related Projects

- [LocalN8N](https://github.com/veerannas/LocalN8N) — Workflow automation orchestration
- [LinkedInApplyAutomation](https://github.com/veerannas/LinkedInApplyAutomation) — AI-driven job application pipeline

---

*Part of my self-hosted AI agent infrastructure.*
