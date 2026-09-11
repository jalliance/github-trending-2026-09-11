# GitHub Trending — 11 September 2026

Snapshot of [github.com/trending](https://github.com/trending) captured around **11:19 BST** on Friday, 11 September 2026.

Filters on the source page: **Repositories · Spoken language: Any · Language: Any · Date range: Today**. GitHub listed **16** repositories. Independently confirmed against same-day archives and the GitHub API (`ayghri/i-have-adhd` API-confirmed at 39,718★; `obra/superpowers` API-confirmed at 285,024★).

This repo is a frozen briefing you can reopen later. Trending itself rotates every day. It is **not** a deployment of the 16 projects.

| Live source | This snapshot |
|---|---|
| [github.com/trending](https://github.com/trending) | Open `index.html` in a browser, or enable Pages |
| Rolling Pages (older stub) | [jalliance.github.io/github-trending-dashboard](https://jalliance.github.io/github-trending-dashboard/) |
| Yesterday | [github-trending-2026-09-10](https://github.com/jalliance/github-trending-2026-09-10) |

## How to test this later

1. Clone or download this repository and open `index.html` locally. No server required.
2. Or enable **Settings → Pages → Deploy from a branch → `main` / root** to get  
   `https://jalliance.github.io/github-trending-2026-09-11/`.
3. You already have three Grok automations for this exact job. Do not create a fourth. Keep one daily briefing; pause the rest.

The dashboard is static. No backend, no API keys, no tracking.

## What today actually is

This is not a general software leaderboard. Most of the 16 entries are agent skills, harnesses, local inference engines, or prompt packs. Stars measure viral agent-plugin installs, not production quality. If you wanted 16 things to deploy and click, you asked the wrong question.

Items that behave like real tools you can run locally: **llmfit**, **colibri**, **armorpaint**, **PI-Desktop**, **OpenMAIC**, **llm_wiki**, **gods-eye-view** (localhost globe), **OmniRoute** (local proxy only). Do **not** run **CloddsBot** against live funds.

## Trending table

Star and fork counts are from the official trending page and GitHub API around capture time. **Stars today** comes from the public trending page (momentum, not lifetime quality). Totals drift by hundreds while the page is open.

| # | Repository | Lang | Stars | Forks | Stars today | What it is | Good for |
|---|---|---|---:|---:|---:|---|---|
| 1 | [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd) | Python | 39,718 | 2,275 | 3,882 | Claude/Codex skill that forces action-first, numbered, no-preamble replies. 10 rules in `SKILL.md`. MIT. Created 2026-05-13. Biggest mover today. | Cutting agent waffle. Not a medical tool. Install only if your agent buries the answer. |
| 2 | [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view) | JavaScript | 25,673 | 5,258 | 1,762 | CesiumJS browser globe fusing public feeds (OpenSky, AIS, CelesTrak, USGS, NASA FIRMS, traffic, public cameras). Voice via OpenAI Realtime. `npm run dev` → localhost:4173. Site: [maptheworld.ai](https://maptheworld.ai/). | Local OSINT / geospatial demo. Not a spy satellite. Do not publish with API keys in env. |
| 3 | [obra/superpowers](https://github.com/obra/superpowers) | Shell | 285,024 | 25,492 | 732 | Jesse Vincent / Prime Radiant agentic SDLC: brainstorm → signed-off design → TDD plan → subagent execution. Plugin for Claude, Codex, Cursor, Gemini, Copilot, Grok Build, Pi, Hermes. MIT. Created 2025-10-09. Star count is real. | Disciplined multi-step coding with tests. Methodology, not a model. Optional logo telemetry (`SUPERPOWERS_DISABLE_TELEMETRY`). |
| 4 | [alsk1992/CloddsBot](https://github.com/alsk1992/CloddsBot) | TypeScript | 1,910 | 270 | 277 | Self-hosted Claude trading agent: Polymarket, Kalshi, Binance, Hyperliquid, Solana DEXs, EVM. Wants `ANTHROPIC_API_KEY` + exchange keys + wallet private keys. 12-day hackathon build. Site: [cloddsbot.com](https://www.cloddsbot.com). MIT. | Studying agent-trading architecture. **UNSAFE TO RUN LIVE.** Unaudited. Real-money autonomy + keys in `.env` is how you lose funds. |
| 5 | [Tencent/teamai-cli](https://github.com/Tencent/teamai-cli) | TypeScript | 4,095 | 262 | 841 | npm CLI that syncs team skills, rules, MCP, hooks, and knowledge across Claude Code, Codex, Cursor, OpenCode, CodeBuddy via a shared git repo. Context/improvement layers are beta. Created 2026-04-27. | Teams that want one harness instead of each person hoarding `CLAUDE.md`. You still host the git repo. |
| 6 | [AlexsJones/llmfit](https://github.com/AlexsJones/llmfit) | Rust | 35,953 | 2,273 | 258 | Detects CPU/RAM/GPU/VRAM and scores models for fit/speed/quality/context. TUI + `llmfit serve` + Docker `ghcr.io/alexsjones/llmfit`. MIT. | Deciding what local model will actually run before you download 70GB of weights. Not an inference server. |
| 7 | [liquidslr/system-design-notes](https://github.com/liquidslr/system-design-notes) | Markdown | 19,156 | 3,518 | 900 | Chapter notes for Alex Xu, *System Design Interview* Vol 1+2 (rate limiter, KV store, news feed, YouTube, payments, stock exchange). No license file. | Interview prep outlines. Notes of a copyrighted book, not original systems. Nothing to run. |
| 8 | [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | HTML | 38,200 | 2,420 | 1,294 | 38 editorial HTML+SVG diagram types for Claude Code / Codex / Pi / Copilot. No Mermaid. Self-contained files. MIT. | Architecture and flow diagrams that look designed. Needs an agent that loads skills. |
| 9 | [freestylefly/awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2) | JavaScript | 31,207 | 3,020 | 962 | Prompt-as-code library for GPT Image 2 / 2.5: 530+ cases, 20+ industrial templates, agent skill. Docs CN/EN/JA. MIT. | Repeatable image-gen workflows if you already pay for GPT Image. Prompt pack, not a model. |
| 10 | [armory3d/armorpaint](https://github.com/armory3d/armorpaint) | C | 4,564 | 522 | 72 | The actual ArmorPaint 3D PBR texture painter ([armorpaint.org](https://armorpaint.org)). Source in-repo; official binaries are paid to fund development. | Painting PBR maps on 3D meshes. Desktop app, not an AI project that wandered onto the list. |
| 11 | [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) | TypeScript | 64,590 | 9,028 | 626 | Local OpenAI-compatible gateway. Claims 352 providers / 150+ free / 1200+ models, quota fallback, token compression. npm/Docker. Homepage [omniroute.online](https://omniroute.online). MIT. 687 open issues. | One endpoint in Cursor/Claude Code when you juggle many keys. Review credential storage. Catalog numbers rot. Localhost only. |
| 12 | [JustVugg/colibri](https://github.com/JustVugg/colibri) | C | 27,632 | 3,018 | 98 | Pure-C MoE inference. Streams experts from disk across VRAM/RAM/SSD. GLM-5.2-class models need ~372GB disk / 16GB RAM; GPU optional. `./coli chat\|serve\|web`. Apache-2.0. | Running huge MoE models on a machine that cannot hold them in VRAM. Disk I/O bound. Not faster than llama.cpp for dense models that already fit. |
| 13 | [THU-MAIC/OpenMAIC](https://github.com/THU-MAIC/OpenMAIC) | TypeScript | 35,685 | 5,670 | 837 | Tsinghua MAIC multi-agent classroom: topic/docs → AI teacher + peers + whiteboard + quizzes. `pnpm dev` :3000 or Docker/Vercel. MIT. v1.0.0 ~2026-08-27. | Education/research demos of agent tutoring. You host it and pay the model bill. Not a finished LMS. |
| 14 | [nashsu/llm_wiki](https://github.com/nashsu/llm_wiki) | TypeScript | 18,404 | 2,114 | 142 | Tauri desktop app: ingest docs → persistent interlinked wiki + graph, not retrieve-from-scratch RAG. macOS/Win/Linux binaries. Local API + MCP. GPL-3.0. | Building a maintained personal knowledge base from files. GPL-3 if you plan to ship a derivative. |
| 15 | [vercel-labs/skills](https://github.com/vercel-labs/skills) | TypeScript | 31,358 | 2,672 | 122 | `npx skills add <repo>` installer for the [agentskills.io](https://agentskills.io) `SKILL.md` ecosystem. 75+ agents. MIT. | Installing/managing skills across Claude Code, Codex, Cursor, OpenCode. Plumbing, not a skill pack itself. |
| 16 | [vastsa/PI-Desktop](https://github.com/vastsa/PI-Desktop) | TypeScript | 2,555 | 204 | 624 | Local-first Electron + Rust desktop workspace for coding agents. BYO OpenAI-compatible model. Agent/Plan/Goal modes, plugins, permission layer. Early preview 0.14.x. LGPL-3.0. | An agent workspace that is not locked to one IDE. Verify release binaries. Preview software. |

## What the list is saying

Three currents dominate:

1. **Agent skills and harnesses as a product category.** i-have-adhd, Superpowers, TeamAI, Vercel skills, diagram-design, and PI-Desktop are all "change how my coding agent behaves." Stars here measure plugin virality.
2. **Local inference and routing.** llmfit (what fits), colibri (stream MoE from disk), OmniRoute (one proxy, many providers).
3. **Study / media material.** system-design-notes, GPT Image prompts, OpenMAIC classroom, ArmorPaint (the one non-AI tool that snuck in).

**CloddsBot is the outlier to avoid.** It is the only entry that wants wallet private keys and live market access.

## Existing automations

Do not create a fourth copy of this job.

| Name | Task ID | Schedule | Status |
|---|---|---|---|
| github-trending-briefing | `2d49e2ee-aa12-4206-b738-afbcd3c5dd3b` | Daily 09:00 Europe/London | Active |
| github-trending-daily | `35d4408d-90b2-4f55-87f8-9c0162878231` | Daily 09:00 Europe/London | Paused |
| GitHub trending | `bd336ad4-9df6-4b51-b4da-34d77cf3cbcb` | Daily 11:05 Europe/London | Active (this run) |

Say "run github-trending-briefing now" to regenerate on demand.
