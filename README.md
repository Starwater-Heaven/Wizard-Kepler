# Wizard Kepler — Quick Start Guide
**Version 1.0 (May 2026) · Qatom Agent Creator**

Wizard Kepler is a setup agent that walks you through a 10–15 minute conversation and produces a ready-to-use Qatom-powered agent at the end. No coding required.

---

## Step 1 — Pick your file

| Platform | File to use | How to activate |
|---|---|---|
| **Claude.ai / Cowork** | `CLAUDE.md` | Copy full contents → New Project → Project Instructions → Paste → Save |
| **Claude Code** | `CLAUDE.md` | Drop into your project directory. The CLI picks it up automatically. |
| **OpenAI Codex CLI** | `AGENTS.md` | Drop into your working directory. The CLI picks it up automatically. |
| **Hermes / MiniMax / Ollama** | `AGENTS.md` | Drop into your working directory or `.hermes/` directory. |
| **Gemini CLI** | `GEMINI.md` | Drop into your working directory. The CLI picks it up automatically. |
| **Manus** | `manus-system-prompt.md` | Copy full contents → New agent → System Prompt → Paste → Save. |

---

## Step 2 — Start a new chat

Open a new chat in the project or session where you pasted / dropped the file. The wizard starts automatically. It will ask you a small number of plain-English questions in grouped steps — no developer knowledge needed.

**What the wizard collects:**
- Your name and Qatom email
- Your agent's name and what it does
- Its personality and tone
- Spending limits for its wallet

**What the wizard produces:**
- A complete agent instruction block — paste it into a new project to activate your agent
- A `qatom-agent-community-card.md` — a short shareable card about your new agent

---

## Step 3 — Connect Qatom

Before your agent can transact, add the Qatom MCP server to your AI platform's settings:

- **URL:** `https://mcp.m.todaq.net/mcp`
- **Authorization server:** `https://pay.m.todaq.net`
- **Scopes:** `openid`, `profile`, `email`, `twin`

Sign in with your Qatom credentials. Then open your new agent project and say **"set up Qatom"** — it walks you through the rest.

---

## Step 4 — Share your story

Once your agent is live, share your experience with the Qatom builder community:

- **Telegram:** [t.me/qatomagentstories](https://t.me/qatomagentstories)
- **X / Twitter:** Post to [@todaq](https://x.com/todaq)

Your `qatom-agent-community-card.md` file has everything you need — just copy and post.

---

## Something not working?

Email **support@todaq.net** with:
1. A description of what went wrong
2. Your hardware and AI model (e.g. "MacBook M2, Claude Sonnet 4.5 on Claude.ai")
3. A screenshot and/or copy-paste of any relevant error or status messages

If you improved these files and want to contribute, send them the same way.

---

## File inventory

| File | Purpose |
|---|---|
| `WIZARD_KEPLER.md` | Master source file — all platform files derive from this |
| `CLAUDE.md` | Claude Code + Claude.ai / Cowork |
| `AGENTS.md` | OpenAI Codex CLI + Hermes / MiniMax / Ollama |
| `GEMINI.md` | Gemini CLI |
| `manus-system-prompt.md` | Manus |
| `README.md` | This file |

---

*Wizard Kepler is part of the Kepler agent family — built by Starwater Heaven and the Qatom team.*
*May you be strong, prosperous, and fair in trade.*
