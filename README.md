# GitHub Trending — 11 September 2026

Snapshot of [github.com/trending](https://github.com/trending) captured around **11:19 BST** on Friday, 11 September 2026.

Filters on the source page: **Repositories · Spoken language: Any · Language: Any · Date range: Today**. GitHub listed **16** repositories. Independently confirmed against same-day archives and the GitHub API (`obra/superpowers` API-confirmed at ~285k★ — the number is real, not a scrape error).

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

Items that behave like real tools you can run today: **llmfit**, **colibri**, **teamai-cli**, **vercel-labs/skills**, **PI-Desktop**, **armorpaint** (source; official binaries historically paid). **CloddsBot is not one of them.** OmniRoute and gods-eye-view can be tried locally; do not expose them with keys on a public host.

## Trending table

Star and fork counts are from the official trending page and GitHub API around capture time. **Stars today** comes from the public trending page (momentum, not lifetime quality). Totals drift by hundreds while the page is open.

| # | Repository | Lang | Stars | Forks | Stars today | What it is | Good for |
|---|---|---|---:|---:|---:|---|---|
| 1 | [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd) | Python | 39,695 | 2,273 | 3,882 | Claude/Codex skill that forces action-first, numbered, no-preamble replies. 10 rules in `SKILL.md`. MIT. Created 2026-05-13. Biggest mover today. | Cutting agent waffle. Not a medical tool. Install only if your agent buries the answer. |
| 2 | [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view) | JavaScript | 25,643 | 5,253 | 1,762 | Browser CesiumJS globe fusing public feeds (OpenSky flights, AIS ships, CelesTrak sats, USGS quakes, NASA FIRMS fires, traffic, public cameras). Optional OpenAI voice. MIT. | Local OSINT / situational-awareness playground. Not a spy satellite. Keep API keys local; do not publish as a public service. |
| 3 | [obra/superpowers](https://github.com/obra/superpowers) | Shell | 285,016 | 25,491 | 732 | Jesse Vincent / Prime Radiant agentic SDLC: brainstorm → signed-off design → TDD plan → subagent execution. Plugin for Claude, Codex, Cursor, Gemini, Copilot, Grok, Pi. MIT. Created 2025-10-09. | Disciplined multi-step coding with tests. Methodology, not a model. Do not stack on every other harness at once. |
| 4 | [alsk1992/CloddsBot](https://github.com/alsk1992/CloddsBot) | TypeScript | 1,906 | 269 | 277 | Self-hosted Claude trading agent across Polymarket, Kalshi, Binance, Hyperliquid, Solana DEXs, EVM. Wants `ANTHROPIC_API_KEY` + exchange keys + wallet private keys. Claims 118+ strategies. 12-day hackathon build. MIT claimed. | Studying agent-trading architecture only. **UNSAFE TO RUN LIVE.** Unaudited. Real-money autonomy + private keys in `.env` is how you lose funds. |
| 5 | [Tencent/teamai-cli](https://github.com/Tencent/teamai-cli) | TypeScript | 4,089 | 262 | 841 | npm CLI that syncs team skills, rules, MCP, hooks, and knowledge across Claude Code, Codex, Cursor, OpenCode, and others via a shared git repo. README says MIT. | Teams that want one harness instead of each person hoarding `CLAUDE.md`. Context/improvement layers are beta. |
| 6 | [AlexsJones/llmfit](https://github.com/AlexsJones/llmfit) | Rust | 35,957 | 2,273 | 258 | Detects CPU/RAM/GPU/VRAM and ranks hundreds of models for fit/speed/quality. TUI + `llmfit serve` web/API + Docker. MIT. | Answering “what local model will actually run on this machine” before you download 70GB of GGUF. Not an inference server. |
| 7 | [liquidslr/system-design-notes](https://github.com/liquidslr/system-design-notes) | Markdown | 19,158 | 3,518 | 900 | Chapter notes for Alex Xu, *System Design Interview* Vol 1+2 (rate limiter, KV store, news feed, YouTube, payments, etc.). No license file. | Interview prep and a map of classic designs. Notes, not original systems. Copyright-adjacent study aid. |
| 8 | [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | HTML | 38,203 | 2,420 | 1,294 | 38 editorial HTML+SVG diagram types for Claude Code / Codex / Pi. No Mermaid. Brand-onboards from a URL. MIT. | Architecture and flow diagrams that look designed. Needs an agent that loads skills. |
| 9 | [freestylefly/awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2) | JavaScript | 31,207 | 3,020 | 962 | Prompt-as-code library for GPT Image 2 / 2.5: 530+ cases, 20+ industrial templates, agent skill. Docs CN/EN/JA. MIT. | Repeatable image-gen workflows if you already pay for GPT Image. Prompt pack, not a model. |
| 10 | [armory3d/armorpaint](https://github.com/armory3d/armorpaint) | C | 4,564 | 522 | 72 | The actual ArmorPaint 3D PBR texture painter ([armorpaint.org](https://armorpaint.org)). Source in-repo; official binaries historically paid to fund development. | Painting PBR maps on 3D meshes (desktop / mobile). Not an AI project that wandered onto the list. |
| 11 | [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) | TypeScript | 64,580 | 9,027 | 626 | Local OpenAI-compatible gateway. Claims 352 providers / 150+ free / 1200+ models, quota fallback, token compression. npm/Docker. Keys live in the gateway. MIT. Site: [omniroute.online](https://omniroute.online). | One endpoint in Cursor/Claude Code when you juggle many provider keys. Review credential storage. “150+ free” is catalog marketing. Keep it on localhost. |
| 12 | [JustVugg/colibri](https://github.com/JustVugg/colibri) | C | 27,633 | 3,018 | 98 | Pure-C MoE inference. Streams experts from disk across VRAM/RAM/SSD. GLM-5.2-class models need ~372GB disk / 16–24GB RAM; GPU optional. Apache-2.0. | Running huge MoE models on a machine that cannot hold them in VRAM. Disk I/O bound. Not faster than llama.cpp for dense models that already fit. |
| 13 | [THU-MAIC/OpenMAIC](https://github.com/THU-MAIC/OpenMAIC) | TypeScript | 35,685 | 5,670 | 837 | Tsinghua MAIC multi-agent classroom: topic/docs → AI teacher + peers + whiteboard + quizzes. `pnpm dev` or Docker/Vercel. Needs an LLM API key. MIT. | Demo/research of agent-taught lessons. Not a finished LMS. You host it and pay the model bill. |
| 14 | [nashsu/llm_wiki](https://github.com/nashsu/llm_wiki) | TypeScript | 18,406 | 2,114 | 142 | Desktop app: ingest docs → persistent interlinked wiki + graph, not retrieve-from-scratch RAG. macOS/Win/Linux. Local API + MCP. GPL-3.0. | Building a maintained personal/team knowledge base from files. Not drop-in RAG for a production chatbot. GPL-3 if you ship a derivative. |
| 15 | [vercel-labs/skills](https://github.com/vercel-labs/skills) | TypeScript | 31,360 | 2,672 | 122 | `npx skills add <repo>` installer for the agentskills.io `SKILL.md` ecosystem. 75+ agents. MIT. | Installing/managing skills across Claude Code, Codex, Cursor, OpenCode. Plumbing, not a collection of skills itself. |
| 16 | [vastsa/PI-Desktop](https://github.com/vastsa/PI-Desktop) | TypeScript | 2,556 | 204 | 624 | Local-first Electron + Rust desktop workspace for coding agents. BYO OpenAI-compatible model. Agent/Plan/Goal modes, plugins, MCP. Early preview. LGPL-3.0. | An agent workspace that is not locked to one IDE. Verify release binaries. Preview software. |

## What the list is saying

Three currents dominate:

1. **Agent skills and harnesses as a product category.** i-have-adhd, Superpowers, TeamAI, Vercel skills, diagram-design, and PI-Desktop are all “change how my coding agent behaves.” Stars here measure plugin virality.
2. **Local inference and routing.** llmfit (what fits), colibri (run huge MoE from disk), OmniRoute (one endpoint, many providers). The market is still trying to make frontier models cheap and local.
3. **Study / catalog / specialty tools.** system-design-notes, GPT Image prompt library, ArmorPaint, OpenMAIC classroom, llm_wiki. Plus one thing you should not run: CloddsBot.

Pick **one** harness (Superpowers *or* TeamAI *or* PI-Desktop), not all three.

## Existing automations

Do not create a fourth copy of this job.

| Name | Task ID | Schedule | Status |
|---|---|---|---|
| github-trending-briefing | `2d49e2ee-aa12-4206-b738-afbcd3c5dd3b` | Daily 09:00 Europe/London | Active |
| github-trending-daily | `35d4408d-90b2-4f55-87f8-9c0162878231` | Daily 09:00 Europe/London | Paused |
| GitHub trending | `bd336ad4-9df6-4b51-b4da-34d77cf3cbcb` | Daily 11:05 Europe/London | Active (this run) |

Say “run github-trending-briefing now” to regenerate on demand.
