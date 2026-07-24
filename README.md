# PCD — Portable Context Deck

**Your context. Any AI.**

PCD is your portable context layer — load it into any AI. Connect an MCP-capable
client to one endpoint and it boots with your containers: structured context, live
work state, and accumulated knowledge, composed by you and carried across every
client you use. Use it in whichever AI you're working in — desktop, IDE, chat —
each already briefed, nothing tied to a single client. Your data stays in your
account — we don't sell it or train on it.

- **Home:** https://portablecontext.ai
- **Dashboard:** https://app.portablecontext.ai
- **Docs:** https://docs.portablecontext.ai

## Early access

PCD is in early access. Leave your email at
[portablecontext.ai](https://portablecontext.ai) and we'll get you in soon. Your
invite unlocks the full setup: your MCP endpoint for any client,
a web dashboard with a live view of your containers — skills, knowledge, signals,
and work — plus connection management and export, and the documentation.

## Connect

Once you're in, PCD is a remote MCP server — point any MCP-capable client at the
endpoint and sign in on first connect (no API key):

| | |
|---|---|
| Endpoint  | `https://mcp.portablecontext.ai` |
| Transport | Streamable HTTP |
| Auth      | OAuth 2.0 + PKCE |

```json
{
  "mcpServers": {
    "pcd": {
      "url": "https://mcp.portablecontext.ai",
      "transport": "http"
    }
  }
}
```

Then `load console` to create and manage your containers, or `load <container>` to
enter — or a specialist directly.

## What you get

- **Load** — one call briefs your AI with your whole operating context.
- **Specialists** — specialized contexts scoped to a domain, role, or task.
- **Work state** — a live session that follows you across clients.
- **Knowledge** — your accumulated, structured understanding.
- **Signals** — findings that outlive a session.
- **Skills** — reusable skills, attached to a deck or shared across them.
- **Connections** *(beta)* — your connected external tools through one authenticated surface.

---

Built with PCD, inside PCD.
