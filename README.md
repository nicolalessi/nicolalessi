# Hi, I'm Nicola 👋

📍 **Milan, Italy** · 🦀 **Rust + TypeScript** · 🏗️ **Building the context layer for AI coding agents**

![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Tree-sitter](https://img.shields.io/badge/-Tree--sitter-6EBF8B?style=flat-square&logo=data:image/svg+xml;base64,&logoColor=white)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![MCP](https://img.shields.io/badge/-MCP_Protocol-000000?style=flat-square&logo=anthropic&logoColor=white)
![VS Code](https://img.shields.io/badge/-VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)

> AI coding agents are powerful but blind — they waste tokens reading irrelevant code and forget everything between sessions. I'm building the infrastructure that fixes both.

## What I'm building

### 🔬 [vexp](https://vexp.dev) — Local-first context engine for AI coding agents

Combines tree-sitter AST parsing, dependency graph traversal, hybrid search (FTS5 + TF-IDF + graph centrality), intent detection, and AST-level skeletonization into a single pipeline → 74% fewer tokens, session memory, zero cloud.

Solo-built the full stack: Rust core (tree-sitter, petgraph, SQLite, blake3), TypeScript MCP server (11 tools), VS Code extension with LSP bridge, passive observation pipeline.

| Metric | Value |
|--------|-------|
| **Agents supported** | 12 (Claude Code, Cursor, Copilot, Windsurf, Zed, Codex...) |
| **Languages parsed** | 11 (more to come)|
| **Architecture** | Single Rust binary, 100% local, zero network calls |

**→** [vexp.dev](https://vexp.dev) · [VS Code Extension](https://marketplace.visualstudio.com/items?itemName=Vexp.vexp-vscode) · [npm CLI](https://www.npmjs.com/package/vexp-cli)

---

### 🎬 [Lumigo](https://lumigo.it) — AI-powered entertainment discovery

NLP mood-based content recommendations. **500K+ page views, 30K users, €0 marketing.**

Owned product strategy, technical architecture, and go-to-market end to end.

---

## Builder track record

I build things, ship them, and get users — consistently, without budgets.

| Year | Project | What happened |
|------|---------|---------------|
| 2026 | **[Vexp](https://vexp.dev)** | Context engine for AI agents. 30 paying users in 15 days, $0 CAC |
| 2025 | **[Lumigo](https://lumigo.tv)** | AI entertainment platform. 500K page views, 30K users, €0 marketing |
| 2022 | **Fantagoverno** | Political engagement game. MVP in 4 weeks, 6K users in 3 months |
| 2021 | **Clicmon** | Gen Z sustainable marketplace. 9-person team, 42% waitlist conversion, €1.32 CAC ||

## Day job (6+ years)

**Team Leader → Software Analyst** at **Intesa Sanpaolo** (via Exprivia S.p.A.)

Mission-critical financial markets IT. Trading systems, front-office integrations, core banking. IBM MQ, WebSphere, SQL, Python, Unix. Led a hybrid team of 6 — finance and IT — on mission-critical trading systems. 99.9% uptime. 30% faster incident resolution. ECB/ECMS compliance. 40% reduction in deployment time via CI/CD.

## Current focus

- 🦀 Shipping vexp v2: multi-repo workspaces, expanded language support, team features
- 🔍 Looking for a cofounder — deep in developer GTM, growth, or product strategy
- 📖 Writing about AI agent infrastructure at [vexp.dev/blog](https://vexp.dev/blog)

## Connect

[![Website](https://img.shields.io/badge/-vexp.dev-000000?style=flat-square&logo=safari&logoColor=white)](https://vexp.dev)
[![LinkedIn](https://img.shields.io/badge/-Nicola_Alessi-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nicolalessi)
[![Email](https://img.shields.io/badge/-nicola@vexp.dev-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:nicola@vexp.dev)

---

*Solo founder. Serial builder. If you're working on AI agents and tired of context thrashing, [try vexp](https://vexp.dev). If you're investing in developer infrastructure, let's talk.*
