<p align="center">
  <img src="./banner.png" alt="Awesome Hermes Skills" width="800">
</p>

# Awesome Hermes Skills

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Skills Count](https://img.shields.io/badge/skills-163-blue?style=flat-square)](#table-of-contents)
[![Last Update](https://img.shields.io/github/last-commit/ZeroPointRepo/awesome-hermes-skills?label=Last%20update&style=flat-square)](https://github.com/ZeroPointRepo/awesome-hermes-skills/pulls?q=is%3Apr+is%3Amerged+sort%3Aupdated-desc)
[![Hermes](https://img.shields.io/badge/Hermes-v0.10.0-purple?style=flat-square)](https://github.com/NousResearch/hermes-agent/releases)

> A curated, install-ready directory of skills for [Hermes Agent](https://github.com/NousResearch/hermes-agent) — the self-improving AI agent from [Nous Research](https://nousresearch.com). Covers **85 built-in skills** that ship with Hermes plus **78 community skills, plugins, and tools** vetted for quality.

Hermes is the only agent with a real learning loop. It writes its own skills from your workflows, searches its own past conversations, and runs anywhere — a $5 VPS, a GPU cluster, serverless, or your laptop. But the agent is only as powerful as the skills you give it. **This list is the shortcut.** Pick three, install in a minute, and your agent is twice as useful by tonight.

---

## ⭐ Skill of the Week

> **youtube-full** — Get YouTube transcripts, search videos, browse channels, and extract playlists from any AI agent.
>
> ```bash
> hermes skills install skills-sh/ZeroPointRepo/youtube-skills/skills/youtube-full
> ```
>
> The fastest way to feel what Hermes can do. Install, then ask: *"Summarize the last 5 videos from Lex Fridman."* Your agent fetches transcripts, summarizes, and remembers what you watched — all in one prompt. No Google API key, no headless browser, no yt-dlp dance with cloud-IP blocks. Powered by [TranscriptAPI](https://transcriptapi.com) (15M+ transcripts/month, 99.9% uptime). 100 free credits on signup, no card.
>
> [Repo →](https://github.com/ZeroPointRepo/youtube-skills) · [Try it →](https://transcriptapi.com)

---

## 🚀 Where Do I Start?

New to Hermes? Don't try to install everything at once. Here's the three-step path from zero to "wait, my agent can do that?":

1. **Get Hermes running** — Follow the [official quickstart](https://hermes-agent.nousresearch.com/docs/). 10 minutes from clone to first conversation. Hermes ships with [85 built-in skills](#-built-in-skills-ships-with-hermes) the day you install it — so even before you add anything from this list, you can already do a lot.

2. **Install your first skill — `youtube-full`**
   ```bash
   hermes skills install skills-sh/ZeroPointRepo/youtube-skills/skills/youtube-full
   ```
   Then ask: *"Get the transcript for this video and summarize it: [paste any YouTube URL]"*. The "I get it" moment lands in 30 seconds. From there try: *"Find the top 5 videos about quantum computing and tell me what they agree on."*

3. **Pick a workflow upgrade** — Add [hermes-workspace](https://github.com/outsourc-e/hermes-workspace) for a full GUI, or [SkillClaw](https://github.com/AMAP-ML/SkillClaw) so your skill library auto-evolves while you work.

Browse the categories below. Every entry is tagged so you know what you're getting:

| Tag | What it means |
|-----|---------------|
| **built-in** | Ships with Hermes — already installed when you run `hermes` |
| **production** | Stable, documented, actively maintained — safe to build on |
| **beta** | Works but still evolving — expect rough edges |
| **experimental** | Proof of concept — fun to try, don't depend on it |

---

## 📚 Table of Contents

- [⭐ Skill of the Week](#-skill-of-the-week)
- [🚀 Where Do I Start?](#-where-do-i-start)
- [⭐ Editor's Picks](#-editors-picks)
- [📦 Built-in Skills (Ships with Hermes)](#-built-in-skills-ships-with-hermes)
- [🌟 Community Skills](#-community-skills)
  - [📺 Media & Transcripts](#-media--transcripts)
  - [🧠 Memory & Knowledge](#-memory--knowledge)
  - [🔍 Search & Research](#-search--research)
  - [💻 Dev & Skill Authoring](#-dev--skill-authoring)
  - [🌐 Browser & Web](#-browser--web)
  - [✉️ Communication & Social](#%EF%B8%8F-communication--social)
  - [📊 Productivity & Tasks](#-productivity--tasks)
  - [🎨 Creative & Media Generation](#-creative--media-generation)
  - [🔧 DevOps & Deployment](#-devops--deployment)
  - [💰 Finance, Payments & Crypto](#-finance-payments--crypto)
  - [🤖 Multi-Agent & Swarms](#-multi-agent--swarms)
  - [🏠 Smart Home, IoT & Embodied](#-smart-home-iot--embodied)
  - [🔐 Security & Detection](#-security--detection)
  - [🎯 Domain & Novelty](#-domain--novelty)
- [🛠️ Tools, Workspaces & GUIs](#%EF%B8%8F-tools-workspaces--guis)
- [📚 Skill Registries & Discovery](#-skill-registries--discovery)
- [📖 Guides & Documentation](#-guides--documentation)
- [🛡️ Security Notice](#%EF%B8%8F-security-notice)
- [🤝 Contributing](#-contributing)
- [📰 Stay in the Loop](#-stay-in-the-loop)
- [License](#license)

---

## ⭐ Editor's Picks

A short hand-picked list to get you started. If you install nothing else from this page, install these.

### 🎬 youtube-full
**production** · [@therohitdas](https://github.com/therohitdas) · [Repo](https://github.com/ZeroPointRepo/youtube-skills)

```bash
hermes skills install skills-sh/ZeroPointRepo/youtube-skills/skills/youtube-full
```

If your agent can't read YouTube, half the internet is invisible to it. This skill gives Hermes transcript extraction, channel browsing, search, and playlist parsing — no Google API key, no yt-dlp, no cloud-IP blocks. Powered by [TranscriptAPI](https://transcriptapi.com), which serves 15M+ transcripts/month. 100 free credits on signup, no card. Works in Hermes, Claude Code, OpenClaw, Cursor, Windsurf, Cline, and Codex.

### 🛠️ mattpocock/skills — Skills For Real Engineers
**production** · [Matt Pocock](https://github.com/mattpocock) · [Repo](https://github.com/mattpocock/skills) · 🔥 trending

```bash
npx skills@latest add mattpocock/skills
```

Fifteen battle-tested skills from the Total TypeScript creator (60k+ newsletter readers). The `grill-me` and `grill-with-docs` skills force the agent to interview you before writing code — the single best fix for "the agent didn't do what I wanted." `tdd` enforces red-green-refactor. `improve-codebase-architecture` rescues codebases that have become balls of mud. `caveman` cuts ~75% of token usage on long sessions. Built for real engineering work, not vibe coding. Pick the ones you want with the installer's interactive picker.

### 🔬 SkillClaw
**production** · [AMAP-ML](https://github.com/AMAP-ML) · [Repo](https://github.com/AMAP-ML/SkillClaw) · 705★

Open-source companion that auto-evolves, deduplicates, and improves your skill library from real session data. Sits on top of Hermes's built-in skill creation and adds a post-task evolution loop. Native Hermes integration via `~/.hermes/skills`, with safety flows (`skillclaw doctor hermes` / `skillclaw restore hermes`).

### 🛡️ resemble-ai/detect-skill
**beta** · [Resemble AI](https://github.com/resemble-ai) · [Repo](https://github.com/resemble-ai/detect-skill)

Deepfake detection for agents that ingest user-submitted media. Detects AI-generated audio, image, video, and text. Traces audio source (ElevenLabs, Resemble, etc.), applies invisible watermarks for provenance, and verifies speaker identity. The first thing to install if your agent reads the public internet.

### 🖥️ hermes-workspace
**production** · [outsourc-e](https://github.com/outsourc-e) · [Repo](https://github.com/outsourc-e/hermes-workspace) · 500★

Web-based workspace with chat, terminal, memory browser, skills manager, and inspector. The most complete GUI for Hermes. Built during Nous Hackathon 2026. Pairs well with everything else on this list.

---

## 📦 Built-in Skills (Ships with Hermes)

> Hermes is unique — it ships with **85 built-in skills** out of the box, organized into 22 categories. You don't install these. Run `hermes` and they're already there.
>
> This section exists so you know what you already have before you start adding more. Most "I need a skill for X" questions are answered here first.

<details open>
<summary><h3 style="display:inline">🍎 Apple (4)</h3></summary>

- **apple-notes** — Manage Apple Notes via memo CLI: create, search, edit.
- **apple-reminders** — Apple Reminders via remindctl: add, list, complete.
- **findmy** — Track Apple devices/AirTags via FindMy.app on macOS.
- **imessage** — Send and receive iMessages/SMS via the imsg CLI on macOS.
</details>

<details open>
<summary><h3 style="display:inline">🤖 Autonomous AI Agents (4)</h3></summary>

- **claude-code** — Delegate coding to Claude Code CLI (features, PRs).
- **codex** — Delegate coding to OpenAI Codex CLI (features, PRs).
- **hermes-agent** — Configure, extend, or contribute to Hermes Agent.
- **opencode** — Delegate coding to OpenCode CLI (features, PR review).
</details>

<details open>
<summary><h3 style="display:inline">🎨 Creative (16)</h3></summary>

- **architecture-diagram** — Dark-themed SVG architecture/cloud/infra diagrams as HTML.
- **ascii-art** — ASCII art: pyfiglet, cowsay, boxes, image-to-ascii.
- **ascii-video** — Convert video/audio to colored ASCII MP4/GIF.
- **baoyu-comic** — Knowledge comics (知识漫画): educational, biography, tutorial.
- **baoyu-infographic** — Infographics: 21 layouts × 21 styles (信息图, 可视化).
- **claude-design** — Design one-off HTML artifacts (landing, deck, prototype).
- **creative-ideation** — Generate project ideas via creative constraints.
- **design-md** — Author/validate/export Google's DESIGN.md token spec files.
- **excalidraw** — Hand-drawn Excalidraw JSON diagrams (arch, flow, seq).
- **humanizer** — Humanize text: strip AI-isms and add real voice.
- **manim-video** — Manim CE animations: 3Blue1Brown-style math/algo videos.
- **p5js** — p5.js sketches: gen art, shaders, interactive, 3D.
- **pixel-art** — Pixel art with era palettes (NES, Game Boy, PICO-8).
- **popular-web-designs** — 54 real design systems (Stripe, Linear, Vercel) as HTML/CSS.
- **songwriting-and-ai-music** — Songwriting craft and Suno AI music prompts.
- **touchdesigner-mcp** — Control TouchDesigner via twozero MCP — operators, parameters, Python, real-time visuals.
</details>

<details>
<summary><h3 style="display:inline">📊 Data Science (1)</h3></summary>

- **jupyter-live-kernel** — Iterative Python via live Jupyter kernel (hamelnb).
</details>

<details>
<summary><h3 style="display:inline">⚙️ DevOps (1)</h3></summary>

- **webhook-subscriptions** — Webhook subscriptions for event-driven agent runs.
</details>

<details>
<summary><h3 style="display:inline">🐶 Dogfood (1)</h3></summary>

- **dogfood** — Exploratory QA of web apps: find bugs, evidence, reports.
</details>

<details>
<summary><h3 style="display:inline">🌐 Domain Intel (1)</h3></summary>

- **domain-intel** — Passive domain reconnaissance via Python stdlib: subdomain discovery, SSL inspection, WHOIS, DNS, availability checks. No API keys required.
</details>

<details>
<summary><h3 style="display:inline">✉️ Email (1)</h3></summary>

- **himalaya** — Himalaya CLI: IMAP/SMTP email from terminal.
</details>

<details>
<summary><h3 style="display:inline">🎮 Gaming (2)</h3></summary>

- **minecraft-modpack-server** — Host modded Minecraft servers (CurseForge, Modrinth).
- **pokemon-player** — Play Pokemon via headless emulator + RAM reads.
</details>

<details>
<summary><h3 style="display:inline">🐙 GitHub (6)</h3></summary>

- **codebase-inspection** — Inspect codebases with pygount: LOC, languages, ratios.
- **github-auth** — GitHub auth setup: HTTPS tokens, SSH keys, gh CLI login.
- **github-code-review** — Review PRs: diffs, inline comments via gh or REST.
- **github-issues** — Create, triage, label, assign GitHub issues.
- **github-pr-workflow** — GitHub PR lifecycle: branch, commit, open, CI, merge.
- **github-repo-management** — Clone/create/fork repos; manage remotes, releases.
</details>

<details>
<summary><h3 style="display:inline">☁️ Inference.sh (1)</h3></summary>

- **inference-sh** — Run 150+ AI applications in the cloud (image gen, video, LLMs, search, 3D) with one API key, accessed through the `infsh` CLI.
</details>

<details>
<summary><h3 style="display:inline">🔌 MCP (1)</h3></summary>

- **native-mcp** — MCP client: connect servers, register tools (stdio/HTTP).
</details>

<details>
<summary><h3 style="display:inline">📺 Media (5)</h3></summary>

- **gif-search** — Search/download GIFs from Tenor via curl + jq.
- **heartmula** — HeartMuLa: Suno-like song generation from lyrics + tags.
- **songsee** — Audio spectrograms/features (mel, chroma, MFCC) via CLI.
- **spotify** — Spotify: play, search, queue, manage playlists and devices.
- **youtube-content** — YouTube transcripts to summaries, threads, blogs.

> ⚠️ **Heads up on built-in `youtube-content`:** it scrapes YouTube directly. That means **it won't work on a VPS or any cloud host** — YouTube blocks cloud IPs across all major providers. Even on a personal device it gets rate-limited and stops returning transcripts after a while; YouTube actively prevents automated transcript fetching.
>
> 💡 **The fix is [`youtube-full`](#-skill-of-the-week)** — it uses [TranscriptAPI.com](https://transcriptapi.com), the same backend powering [YouTubeToTranscript.com](https://youtubetotranscript.com) (15M+ transcripts/month). Works from anywhere — VPS, laptop, serverless. Install it and your agent gains **YouTube as a first-class capability**: search videos, browse channels, and pull transcripts the same way it uses web search. No blocks, no rate limits, no Google API key.
>
> ```bash
> hermes skills install skills-sh/ZeroPointRepo/youtube-skills/skills/youtube-full
> ```
</details>

<details>
<summary><h3 style="display:inline">🤖 MLOps (13)</h3></summary>

- **lm-evaluation-harness** — lm-eval-harness: benchmark LLMs (MMLU, GSM8K, etc.).
- **weights-and-biases** — W&B: log ML experiments, sweeps, model registry, dashboards.
- **huggingface-hub** — HuggingFace `hf` CLI: search/download/upload models, datasets.
- **llama-cpp** — llama.cpp local GGUF inference + HF Hub model discovery.
- **obliteratus** — OBLITERATUS: abliterate LLM refusals (diff-in-means).
- **outlines** — Outlines: structured JSON/regex/Pydantic LLM generation.
- **vllm** — vLLM: high-throughput LLM serving, OpenAI API, quantization.
- **audiocraft** — AudioCraft: MusicGen text-to-music, AudioGen text-to-sound.
- **segment-anything** — SAM: zero-shot image segmentation via points, boxes, masks.
- **dspy** — DSPy: declarative LM programs, auto-optimize prompts, RAG.
- **axolotl** — Axolotl: YAML LLM fine-tuning (LoRA, DPO, GRPO).
- **trl-fine-tuning** — TRL: SFT, DPO, PPO, GRPO, reward modeling for LLM RLHF.
- **unsloth** — Unsloth: 2-5× faster LoRA/QLoRA fine-tuning, less VRAM.
</details>

<details>
<summary><h3 style="display:inline">📝 Note-Taking (1)</h3></summary>

- **obsidian** — Read, search, and create notes in the Obsidian vault.
</details>

<details>
<summary><h3 style="display:inline">📊 Productivity (8)</h3></summary>

- **airtable** — Airtable REST API via curl. Records CRUD, filters, upserts.
- **google-workspace** — Gmail, Calendar, Drive, Docs, Sheets via gws CLI or Python.
- **linear** — Linear: manage issues, projects, teams via GraphQL + curl.
- **maps** — Geocode, POIs, routes, timezones via OpenStreetMap/OSRM.
- **nano-pdf** — Edit PDF text/typos/titles via nano-pdf CLI (NL prompts).
- **notion** — Notion API via curl: pages, databases, blocks, search.
- **ocr-and-documents** — Extract text from PDFs/scans (pymupdf, marker-pdf).
- **powerpoint** — Create, read, edit .pptx decks, slides, notes, templates.
</details>

<details>
<summary><h3 style="display:inline">🔓 Red-Teaming (1)</h3></summary>

- **godmode** — Jailbreak LLMs: Parseltongue, GODMODE, ULTRAPLINIAN.
</details>

<details>
<summary><h3 style="display:inline">🔬 Research (5)</h3></summary>

- **arxiv** — Search arXiv papers by keyword, author, category, or ID.
- **blogwatcher** — Monitor blogs and RSS/Atom feeds via blogwatcher-cli.
- **llm-wiki** — Karpathy's LLM Wiki: build/query interlinked markdown KB.
- **polymarket** — Query Polymarket: markets, prices, orderbooks, history.
- **research-paper-writing** — Write ML papers for NeurIPS/ICML/ICLR: design → submit.
</details>

<details>
<summary><h3 style="display:inline">🏠 Smart Home (1)</h3></summary>

- **openhue** — Control Philips Hue lights, scenes, rooms via OpenHue CLI.
</details>

<details>
<summary><h3 style="display:inline">🐦 Social Media (1)</h3></summary>

- **xurl** — X/Twitter via xurl CLI: post, search, DM, media, v2 API.
</details>

<details>
<summary><h3 style="display:inline">💻 Software Development (10)</h3></summary>

- **debugging-hermes-tui-commands** — Debug Hermes TUI slash commands: Python, gateway, Ink UI.
- **hermes-agent-skill-authoring** — Author in-repo SKILL.md: frontmatter, validator, structure.
- **node-inspect-debugger** — Debug Node.js via `--inspect` + Chrome DevTools Protocol CLI.
- **plan** — Plan mode: write markdown plan to `.hermes/plans/`, no exec.
- **python-debugpy** — Debug Python: pdb REPL + debugpy remote (DAP).
- **requesting-code-review** — Pre-commit review: security scan, quality gates, auto-fix.
- **subagent-driven-development** — Execute plans via `delegate_task` subagents (2-stage review).
- **systematic-debugging** — 4-phase root cause debugging: understand bugs before fixing.
- **test-driven-development** — TDD: enforce RED-GREEN-REFACTOR, tests before code.
- **writing-plans** — Write implementation plans: bite-sized tasks, paths, code.
</details>

<details>
<summary><h3 style="display:inline">💬 Yuanbao (1)</h3></summary>

- **yuanbao** — Yuanbao (元宝) groups: @mention users, query info/members.
</details>

---

## 🌟 Community Skills

> Skills, plugins, and integrations built by the Hermes community. Tagged for maturity. Click through for install instructions per project.

### 📺 Media & Transcripts

- [youtube-skills](https://github.com/ZeroPointRepo/youtube-skills) by [therohitdas](https://github.com/therohitdas) — Transcripts, search, channels, playlists. Cross-agent: Hermes / Claude Code / OpenClaw / Cursor / Windsurf. Powered by [TranscriptAPI](https://transcriptapi.com). **[production]**
- [hermes-spotify-skill](https://github.com/Alexeyisme/hermes-spotify-skill) by [Alexeyisme](https://github.com/Alexeyisme) — Spotify control for headless Linux and Raspberry Pi. The only Linux-native Spotify skill in the ecosystem. **[beta]**

### 🧠 Memory & Knowledge

- [hindsight](https://github.com/vectorize-io/hindsight) by [Vectorize](https://github.com/vectorize-io) — Long-term memory layer with retain/recall/reflect workflows. Semantic + graph + temporal retrieval. Plugin or MCP. **[production]**
- [honcho-self-hosted](https://github.com/elkimek/honcho-self-hosted) by [elkimek](https://github.com/elkimek) — Self-hosted Honcho memory backend setup for Hermes. Stronger cross-session memory with local control. **[beta]**
- [yantrikdb-hermes-plugin](https://github.com/yantrikos/yantrikdb-hermes-plugin) by [yantrikos](https://github.com/yantrikos) — Hermes-native memory provider for YantrikDB. `think()` canonicalizes duplicates, `conflicts()` surfaces contradictions, every `recall()` carries `why_retrieved` reasons. **[beta]**
- [plur](https://github.com/plur-ai/plur) by [plur-ai](https://github.com/plur-ai) — Shared memory layer for AI agents with open engram format (YAML). Persistent learning patterns. **[beta]**
- [flowstate-qmd](https://github.com/amanning3390/flowstate-qmd) by [amanning3390](https://github.com/amanning3390) — Anticipatory memory with RAG and vector search. Pre-fetches relevant context before queries hit the agent. **[beta]**
- [personal-api](https://github.com/beiyuii/personal-api-skill) by [beiyuii](https://github.com/beiyuii) — Turn your Obsidian vault into an identity layer any AI agent can read in under 30 seconds. **[experimental]**
- [Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) by [mukul975](https://github.com/mukul975) — 753+ structured cybersecurity skills mapped to MITRE ATT&CK. 4k+ stars. **[production]**

### 🔍 Search & Research

- [hermes-web-search-plus](https://github.com/robbyczgw-cla/hermes-web-search-plus) by [robbyczgw-cla](https://github.com/robbyczgw-cla) — Multi-provider web search with intelligent routing across Serper, Tavily, Exa, and more. Replaces built-in search with better quality + source diversity. **[beta]**
- [Not Human Search](https://github.com/unitedideas/nothumansearch-mcp) by [unitedideas](https://github.com/unitedideas) — MCP server for discovering other MCP servers. Indexes 8,600+ agent-friendly sites with agentic scoring. Lets Hermes find new tools on its own. **[production]**

### 💻 Dev & Skill Authoring

#### 🔥 mattpocock/skills — Engineering bundle
> Install all at once: `npx skills@latest add mattpocock/skills` — pick which skills you want at install time.

- [diagnose](https://github.com/mattpocock/skills/blob/main/skills/engineering/diagnose/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Disciplined diagnosis loop for hard bugs and perf regressions: reproduce → minimise → hypothesise → instrument → fix → regression-test. **[production]**
- [grill-with-docs](https://github.com/mattpocock/skills/blob/main/skills/engineering/grill-with-docs/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Grilling session that challenges your plan against the existing domain model, sharpens terminology, updates `CONTEXT.md` and ADRs inline. The most popular skill in the pack. **[production]**
- [tdd](https://github.com/mattpocock/skills/blob/main/skills/engineering/tdd/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Test-driven development with red-green-refactor loop. Builds features or fixes bugs one vertical slice at a time. **[production]**
- [improve-codebase-architecture](https://github.com/mattpocock/skills/blob/main/skills/engineering/improve-codebase-architecture/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Find deepening opportunities in a codebase, informed by domain language in `CONTEXT.md` and decisions in `docs/adr/`. Run it every few days. **[production]**
- [zoom-out](https://github.com/mattpocock/skills/blob/main/skills/engineering/zoom-out/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Tell the agent to zoom out and give broader context or higher-level perspective on unfamiliar code. **[production]**
- [to-prd](https://github.com/mattpocock/skills/blob/main/skills/engineering/to-prd/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Turn the current conversation into a PRD and submit it as a GitHub issue. No interview — synthesizes what you've discussed. **[production]**
- [to-issues](https://github.com/mattpocock/skills/blob/main/skills/engineering/to-issues/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Break any plan, spec, or PRD into independently-grabbable GitHub issues using vertical slices. **[production]**
- [github-triage](https://github.com/mattpocock/skills/blob/main/skills/engineering/github-triage/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Triage GitHub issues through a label-based state machine. **[production]**
- [git-guardrails-claude-code](https://github.com/mattpocock/skills/blob/main/skills/misc/git-guardrails-claude-code/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Block dangerous git commands (push, reset --hard, clean) before they execute. Hooks-based. **[production]**
- [setup-pre-commit](https://github.com/mattpocock/skills/blob/main/skills/misc/setup-pre-commit/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Set up Husky pre-commit hooks with lint-staged, Prettier, type checking, and tests. **[production]**
- [migrate-to-shoehorn](https://github.com/mattpocock/skills/blob/main/skills/misc/migrate-to-shoehorn/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Migrate test files from `as` type assertions to @total-typescript/shoehorn. **[production]**
- [scaffold-exercises](https://github.com/mattpocock/skills/blob/main/skills/misc/scaffold-exercises/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Create exercise directory structures with sections, problems, solutions, explainers. **[production]**
- [write-a-skill](https://github.com/mattpocock/skills/blob/main/skills/productivity/write-a-skill/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Create new skills with proper structure, progressive disclosure, and bundled resources. **[production]**

#### Hermes-native skill builders

- [hermes-skill-factory](https://github.com/Romanescu11/hermes-skill-factory) by [Romanescu11](https://github.com/Romanescu11) — Meta-skill that auto-generates reusable skills from your workflows. Point it at a repeated task and it creates a skill for it. **[beta]**
- [bmad-module-skill-forge](https://github.com/armelhbobdad/bmad-module-skill-forge) by [armelhbobdad](https://github.com/armelhbobdad) — Transforms repos and docs into agentskills.io-compliant skills. **[beta]**
- [litprog-skill](https://github.com/tlehman/litprog-skill) by [tlehman](https://github.com/tlehman) — Literate programming skill across Claude Code, OpenCode, Hermes. Weaves code and prose into documented, executable notebooks. **[beta]**
- [execplan-skill](https://github.com/tiann/execplan-skill) by [tiann](https://github.com/tiann) — Long-running task execution with progress tracking, checkpoints, failure recovery. **[beta]**
- [maestro](https://github.com/ReinaMacCredy/maestro) by [ReinaMacCredy](https://github.com/ReinaMacCredy) — Skill orchestration with Conductor planning + Beads tracking. Multi-step skills as observable pipelines. **[beta]**
- [SkillClaw](https://github.com/AMAP-ML/SkillClaw) by [AMAP-ML](https://github.com/AMAP-ML) — Auto-evolves and dedupes your skill library from session data. Native Hermes integration. 705 stars. **[production]**
- [wondelai/skills](https://github.com/wondelai/skills) by [wondelai](https://github.com/wondelai) — Cross-platform agent skills for Claude Code and agentskills.io platforms. 380+ stars. **[production]**
- [skillsdotnet](https://github.com/PederHP/skillsdotnet) by [PederHP](https://github.com/PederHP) — C# implementation of agentskills.io with MCP integration. **[beta]**
- [Agentic-MCP-Skill](https://github.com/cablate/Agentic-MCP-Skill) by [cablate](https://github.com/cablate) — MCP client with agentskills.io validation. **[beta]**
- [pydantic-ai-skills](https://github.com/DougTrajano/pydantic-ai-skills) by [DougTrajano](https://github.com/DougTrajano) — Pydantic AI with agentskills.io. Type-safe schema validation for skill inputs/outputs. **[production]**
- [evey-bridge-plugin](https://github.com/42-evey/evey-bridge-plugin) by [42-evey](https://github.com/42-evey) — Claude Code plugin that bridges with Hermes. Shared context, task handoffs. **[beta]**
- [lintlang](https://github.com/roli-lpci/lintlang) by [roli-lpci](https://github.com/roli-lpci) — Static linter for AI agent configs and prompts with HERM v1.1 scoring. **[beta]**
- [super-hermes](https://github.com/Cranot/super-hermes) by [Cranot](https://github.com/Cranot) — Teaches Hermes to write its own analytical prompts. Meta-reasoning before execution. **[experimental]**
- [hermes-dojo](https://github.com/Yonkoo11/hermes-dojo) by [Yonkoo11](https://github.com/Yonkoo11) — Self-improvement system that monitors agent performance, identifies weak skills, iterates automatically. **[beta]**
- [hermes-skill-distillation](https://github.com/beardthelion/hermes-skill-distillation) by [beardthelion](https://github.com/beardthelion) — Generates agentic training trajectories from real-world tasks for fine-tuning data. **[beta]**
- [rtk-hermes](https://github.com/ogallotti/rtk-hermes) by [ogallotti](https://github.com/ogallotti) — Compresses terminal output via RTK before it reaches LLM context. 60-90% token reduction. Zero config. **[beta]**

### 🌐 Browser & Web

- [hermes-plugin-chrome-profiles](https://github.com/anpicasso/hermes-plugin-chrome-profiles) by [anpicasso](https://github.com/anpicasso) — Switch browser tools between Chrome profiles via CDP. Multi-account testing. **[experimental]**
- [hermes-cloudflare](https://github.com/raulvidis/hermes-cloudflare) by [raulvidis](https://github.com/raulvidis) — Cloudflare browser rendering plugin. Headless browsing through Cloudflare's infrastructure. **[experimental]**
- [vessel-browser](https://github.com/unmodeled-tyler/vessel-browser) by [unmodeled-tyler](https://github.com/unmodeled-tyler) — AI-native Linux browser with MCP control and autonomous browsing. Built for agent use, not a headless wrapper. **[experimental]**

### ✉️ Communication & Social

- [microsoft-workspace-skill](https://github.com/Andrew-Girgis/microsoft-workspace-skill) by [Andrew-Girgis](https://github.com/Andrew-Girgis) — Full Outlook/Hotmail/Microsoft 365 integration via Graph API. Email, calendar, contacts, free/busy. OAuth2 auto-refresh. Preview-before-send pattern. **[beta]**
- [clawsocial-hermes-plugin](https://github.com/mrpeter2025/clawsocial-hermes-plugin) by [mrpeter2025](https://github.com/mrpeter2025) — Social discovery network. Semantic interest matching, real-time WebSocket messaging, shareable profile cards. Bilingual EN+CN. **[beta]**

### 📊 Productivity & Tasks

- [grill-me](https://github.com/mattpocock/skills/blob/main/skills/productivity/grill-me/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Get relentlessly interviewed by your agent until every branch of the decision tree is resolved. Use *every* time before making a change. Most popular skill in the pack. **[production]**
- [caveman](https://github.com/mattpocock/skills/blob/main/skills/productivity/caveman/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Ultra-compressed communication mode. Cuts token usage ~75% by dropping filler while keeping full technical accuracy. Critical for long sessions. **[production]**
- [hermes-plugins](https://github.com/42-evey/hermes-plugins) by [42-evey](https://github.com/42-evey) — Goal management, inter-agent bridge, model selection, cost control. Four plugins covering common operational needs. **[beta]**
- [agent-analytics-hermes-plugin](https://github.com/Agent-Analytics/agent-analytics-hermes-plugin) by [Agent-Analytics](https://github.com/Agent-Analytics) — Native Signals dashboard tab for Hermes. Read-only multi-project analytics. **[beta]**

### 🎨 Creative & Media Generation

- [black-forest-labs/skills](https://github.com/black-forest-labs/skills) by [Black Forest Labs](https://github.com/black-forest-labs) — Official FLUX model skills for image generation. First-party skills from the FLUX creators. **[production]**
- [hermes-weather-plugin](https://github.com/FahrenheitResearch/hermes-weather-plugin) by [FahrenheitResearch](https://github.com/FahrenheitResearch) — Professional-grade weather plugin with NWS model imagery, NEXRAD radar, meteorological calculations. **[beta]**
- [hermes-wxtrain-plugin](https://github.com/FahrenheitResearch/hermes-wxtrain-plugin) by [FahrenheitResearch](https://github.com/FahrenheitResearch) — ML pipeline for building training datasets from HRRR/GFS/ERA5 weather models. **[experimental]**

### 🔧 DevOps & Deployment

- [hermes-agent-docker](https://github.com/xmbshwll/hermes-agent-docker) by [xmbshwll](https://github.com/xmbshwll) — Minimal Docker sandbox image for Hermes. Pull, run, done. **[beta]**
- [portainer-stack-hermes](https://github.com/ellickjohnson/portainer-stack-hermes) by [ellickjohnson](https://github.com/ellickjohnson) — Docker Compose + Portainer + ttyd web terminal. Browser-accessible Hermes. **[experimental]**
- [nix-hermes-agent](https://github.com/0xrsydn/nix-hermes-agent) by [0xrsydn](https://github.com/0xrsydn) — Nix package and NixOS module. Fully reproducible deployments via Nix flakes. **[beta]**
- [openclaw-to-hermes](https://github.com/0xNyk/openclaw-to-hermes) by [0xNyk](https://github.com/0xNyk) — Community migration tool from OpenClaw to Hermes. **[beta]**
- [evey-setup](https://github.com/42-evey/evey-setup) by [42-evey](https://github.com/42-evey) — One-command setup for full hermes-agent stack with free models and 29 plugins. **[beta]**

### 💰 Finance, Payments & Crypto

- [hermes-payguard](https://github.com/nativ3ai/hermes-payguard) by [nativ3ai](https://github.com/nativ3ai) — Safe USDC and x402 payment plugin with spending limits and approval flows. **[experimental]**
- [AgentCash](https://github.com/Merit-Systems/agentcash-skills) by [Merit-Systems](https://github.com/Merit-Systems) — 300+ premium APIs + wallet for paying via x402 or MPP. Free USDC for trying out. **[beta]**
- [ripley-xmr-gateway](https://github.com/KYC-rip/ripley-xmr-gateway) by [KYC-rip](https://github.com/KYC-rip) — Monero (XMR) blockchain gateway. Private cryptocurrency transactions from agent workflows. **[experimental]**
- [hermes-blockchain-oracle](https://github.com/gizdusum/hermes-blockchain-oracle) by [gizdusum](https://github.com/gizdusum) — Solana blockchain intelligence MCP server. On-chain analytics and wallet data. **[experimental]**
- [chainlink-agent-skills](https://github.com/smartcontractkit/chainlink-agent-skills) by [Chainlink](https://github.com/smartcontractkit) — Official Chainlink skills. Oracle data, CCIP, smart contract interaction. **[production]**
- [mercury](https://github.com/hxsteric/mercury) by [hxsteric](https://github.com/hxsteric) — Multi-chain blockchain cash flow analyzer with WebGL dashboard. On-chain forensics. **[beta]**

### 🤖 Multi-Agent & Swarms

- [hermes-agent-acp-skill](https://github.com/Rainhoole/hermes-agent-acp-skill) by [Rainhoole](https://github.com/Rainhoole) — Multi-agent delegation bridging Hermes, Codex, Claude Code. Routes subtasks to best-suited agent. **[beta]**
- [hermes-council](https://github.com/Ridwannurudeen/hermes-council) by [Ridwannurudeen](https://github.com/Ridwannurudeen) — Adversarial multi-perspective council MCP. Multiple AI viewpoints debate before commit. **[experimental]**
- [opencode-hermes-multiagent](https://github.com/1ilkhamov/opencode-hermes-multiagent) by [1ilkhamov](https://github.com/1ilkhamov) — 17 specialized agents for OpenCode AI with structured interfaces. **[beta]**
- [NemoHermes](https://github.com/Hmbown/NemoHermes) by [Hmbown](https://github.com/Hmbown) — NVIDIA capability registry and Spark-aware routing. Routes compute-heavy tasks to GPU infrastructure. **[experimental]**

### 🏠 Smart Home, IoT & Embodied

- [hermes-android](https://github.com/raulvidis/hermes-android) by [raulvidis](https://github.com/raulvidis) — Android device bridge with full Python toolset. **[beta]**
- [agent-android](https://github.com/aivanelabs/ai-rpa/tree/main/skills/agent-android) by [AIVane Labs](https://github.com/aivanelabs) — LAN-first Android control over WiFi. No USB/ADB/root needed. Health checks, taps, swipes, screenshots, inspect→act→smoke flows. **[beta]**
- [hermescraft](https://github.com/bigph00t/hermescraft) by [bigph00t](https://github.com/bigph00t) — Embodied Minecraft companion with persistent memory. Learns building preferences across sessions. **[beta]**
- [Hermes-mars-rover](https://github.com/Snehal707/Hermes-mars-rover) by [Snehal707](https://github.com/Snehal707) — Mars rover sim with ROS2 and Gazebo. Hermes skill loop for navigation improvement. **[experimental]**
- [hermes-miniverse](https://github.com/teknium1/hermes-miniverse) by [teknium1](https://github.com/teknium1) — Bridge to Miniverse pixel worlds. By a Nous Research co-founder. **[beta]**

### 🔐 Security & Detection

- [resemble-ai/detect-skill](https://github.com/resemble-ai/detect-skill) by [Resemble AI](https://github.com/resemble-ai) — Deepfake detection: AI-generated audio/image/video/text, source tracing, watermarking, speaker ID. **[beta]**
- [hermes-agent-camel](https://github.com/nativ3ai/hermes-agent-camel) by [nativ3ai](https://github.com/nativ3ai) — Hermes with integrated CaMeL trust boundaries. Formal trust verification for safety-critical deployments. **[beta]**

### 🎯 Domain & Novelty

- [anihermes](https://github.com/rodmarkun/anihermes) by [rodmarkun](https://github.com/rodmarkun) — Local anime server and tracker with NL interface. Browse, track, get recommendations via conversation. **[beta]**
- [Wizards-of-the-Ghosts](https://github.com/Hmbown/Wizards-of-the-Ghosts) by [Hmbown](https://github.com/Hmbown) — Fantasy spell-themed skill pack. `cast lint` instead of `npm run lint`. **[experimental]**
- [colony-skill](https://github.com/TheColonyCC/colony-skill) by [TheColonyCC](https://github.com/TheColonyCC) — Collaborative intelligence platform. AI + humans post findings, complete tasks, build reputation. **[beta]**

---

## 🛠️ Tools, Workspaces & GUIs

> Apps and dashboards built on top of or alongside Hermes. Not skills — but they make skills easier to use.

- [hermes-workspace](https://github.com/outsourc-e/hermes-workspace) by [outsourc-e](https://github.com/outsourc-e) — Web-based workspace: chat, terminal, memory browser, skills manager, inspector. Most complete GUI for Hermes. 500★. **[production]**
- [hermes-desktop](https://github.com/dodo-reach/hermes-desktop) by [dodo-reach](https://github.com/dodo-reach) — Native macOS workspace with direct host-first SSH. Real terminal, session browsing, file editing. **[beta]**
- [mission-control](https://github.com/builderz-labs/mission-control) by [builderz-labs](https://github.com/builderz-labs) — Open-source dashboard for AI agent orchestration. Multi-agent fleets, task dispatch, cost tracking. 3.7k★. **[production]**
- [portable-hermes-agent](https://github.com/rookiemann/portable-hermes-agent) by rookiemann — Windows desktop app bundling 100 tools, GUI, local models, ComfyUI in a portable package. **[beta]**
- [hermes-ui](https://github.com/pyrate-llama/hermes-ui) by [pyrate-llama](https://github.com/pyrate-llama) — Single-file glassmorphic web UI with SSE streaming, tool call visualization, PDF export, session/skill/memory viewers. **[beta]**
- [hermes-webui](https://github.com/sanchomuzax/hermes-webui) by [sanchomuzax](https://github.com/sanchomuzax) — Lightweight process monitoring and config dashboard. Simpler ops alternative. **[beta]**
- [orahermes-agent](https://github.com/jasperan/orahermes-agent) by [jasperan](https://github.com/jasperan) — Oracle AI Agent Harness — OCI GenAI and Oracle 26ai integration. **[experimental]**

---

## 📚 Skill Registries & Discovery

- **[Official Hermes Skills Hub](https://hermes-agent.nousresearch.com/docs/skills)** — The full catalog. **600+ skills** indexed by Nous Research. Use this when our curated cut doesn't have what you need.
- [hermeshub](https://github.com/amanning3390/hermeshub) by [amanning3390](https://github.com/amanning3390) — Browse, share, and install community Hermes skills. **[beta]**
- [skilldock.io](https://github.com/chigwell/skilldock.io) by [chigwell](https://github.com/chigwell) — Cross-platform skills marketplace for OpenClaw, Claude Code, Hermes. **[production]**
- **[Skills Hub](https://agentskills.io)** — The open standard for agent skills. Compatible across Hermes, Claude Code, Cursor, Codex.

---

## 📖 Guides & Documentation

- **[Official Documentation](https://hermes-agent.nousresearch.com/docs/)** — Quickstart, CLI, configuration, gateway, security, skills, memory, MCP, cron, ACP, API, architecture.
- **[Release Notes](https://github.com/NousResearch/hermes-agent/releases)** — Official changelog with feature highlights and migration notes.
- [hermes-agent-docs](https://github.com/mudrii/hermes-agent-docs) by [mudrii](https://github.com/mudrii) — Comprehensive community documentation. Useful supplement for deployment patterns. **[beta]**
- [hermes-wsl-ubuntu](https://github.com/metantonio/hermes-wsl-ubuntu) by [metantonio](https://github.com/metantonio) — End-to-end WSL2 + llama.cpp + Qwen3.5 setup with CUDA/Metal acceleration for running Hermes on Windows. **[production]**
- **[Discord](https://discord.gg/NousResearch)** — Bug reports, feature requests, general discussion.

---

## 🛡️ Security Notice

Skills in this list are **curated, not audited**. Maintainers can update or change them at any time after they appear here.

Before installing any skill:
- **Read the source.** Skills can include prompt injections, credential exfiltration, or unsafe shell calls.
- **Pin to a commit SHA in production** rather than tracking `main`.
- **Check the [Official Hermes Skills Hub](https://hermes-agent.nousresearch.com/docs/skills)** for any safety notes or maintainer signals on a skill before installing.

Recommended scanners:
- [Snyk Skill Security Scanner](https://github.com/snyk/agent-scan)
- [Agent Trust Hub](https://ai.gendigital.com/agent-trust-hub)

Spot something risky? [Open an issue](https://github.com/ZeroPointRepo/awesome-hermes-skills/issues).

---

## 🤝 Contributing

PRs welcome. We accept skills that:

1. Have a working `SKILL.md` (Hermes / Agent Skills format)
2. Are reasonably maintained (commits in the last 6 months)
3. Have a clear README and a one-line install command
4. Aren't already on the list (check first)

To submit:
1. Fork this repo
2. Add your skill to the right category in alphabetical order
3. Use the entry format: `[name](repo) by [author](author-url) — one-line description. **[tag]**`
4. Open a PR with a link to a working example

---

## 📰 Stay in the Loop

- **[@therohitdas](https://twitter.com/therohitdas)** — Skill of the Week + new additions
- **GitHub Stars** — Star this repo to keep it visible
- **[Hermes Discord](https://discord.gg/NousResearch)** — Talk shop with other Hermes users

---

<div align="center">

**Built and maintained by [ZeroPointRepo](https://github.com/ZeroPointRepo).**

We ship [youtube-skills](https://github.com/ZeroPointRepo/youtube-skills), powered by [TranscriptAPI](https://transcriptapi.com) — 15M+ transcripts/month, 99.9% uptime.

[TranscriptAPI](https://transcriptapi.com) · [@therohitdas](https://twitter.com/therohitdas) · [Issues & Suggestions](https://github.com/ZeroPointRepo/awesome-hermes-skills/issues)

</div>

## License

[![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This list is licensed under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/). Each linked resource has its own license.
