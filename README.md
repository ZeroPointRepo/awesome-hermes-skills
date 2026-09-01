<p align="center">
  <img src="./banner.png" alt="Awesome Hermes Skills" width="800">
</p>

# Awesome Hermes Skills

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Skills Count](https://img.shields.io/badge/skills-368-blue?style=flat-square)](#-table-of-contents)
[![Last Update](https://img.shields.io/github/last-commit/ZeroPointRepo/awesome-hermes-skills?label=Last%20update&style=flat-square)](https://github.com/ZeroPointRepo/awesome-hermes-skills/pulls?q=is%3Apr+is%3Amerged+sort%3Aupdated-desc)
[![Hermes](https://img.shields.io/badge/Hermes-v0.20.6-purple?style=flat-square)](https://github.com/NousResearch/hermes-agent/releases)
[![Agent Plugins](https://img.shields.io/badge/Agent%20Plugins-v1.0.0-teal?style=flat-square)](https://agent-plugins.org)

> A curated, install-ready directory for the [Hermes Agent](https://github.com/NousResearch/hermes-agent) ecosystem — the self-improving AI agent from [Nous Research](https://nousresearch.com). Covers the **82 built-in skills** and **117-skill optional catalog** that ship with Hermes v0.20.6, plus **169 community skills, plugins, agent profiles, memory providers, surfaces, and tools** vetted for quality.

Hermes is the only agent with a real learning loop. It writes its own skills from your workflows, searches its own past conversations, and runs anywhere — a $5 VPS, a GPU cluster, serverless, or your laptop. But the agent is only as powerful as the skills you give it. **This list is the shortcut.** Pick three, install in a minute, and your agent is twice as useful by tonight.

---

## ⭐ Featured Skill

> **youtube-full** : Get YouTube transcripts, search videos, browse channels, and extract playlists from any AI agent.
>
> ```bash
> hermes skills install skills-sh/ZeroPointRepo/youtube-skills/skills/youtube-full
> ```
>
> The fastest way to feel what Hermes can do. Install it, then ask: *"Summarize the last 5 videos from Lex Fridman."* Your agent fetches the transcripts, summarizes them, and remembers what you watched, all in one prompt. No Google API key, and nothing to install or maintain. Powered by [TranscriptAPI](https://transcriptapi.com). Works in Hermes, Claude, OpenClaw and other agent runtimes.
>
> [Repo →](https://github.com/ZeroPointRepo/youtube-skills)

---

## 🚀 Where Do I Start?

New to Hermes? Don't try to install everything at once. Here's the three-step path from zero to "wait, my agent can do that?":

1. **Get Hermes running** — Follow the [official quickstart](https://hermes-agent.nousresearch.com/docs/). 10 minutes from clone to first conversation. Hermes ships with [82 built-in skills](#-built-in-skills-ships-with-hermes) — plus a [117-skill optional catalog](#-optional-skills-bundled-with-hermes) — the day you install it, so even before you add anything from this list, you can already do a lot.

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

- [⭐ Featured Skill](#-featured-skill)
- [🚀 Where Do I Start?](#-where-do-i-start)
- [⭐ Editor's Picks](#-editors-picks)
- [📦 Built-in Skills (Ships with Hermes)](#-built-in-skills-ships-with-hermes)
- [🧩 Optional Skills (Bundled with Hermes)](#-optional-skills-bundled-with-hermes)
- [🌟 Community Skills](#-community-skills)
  - [📺 Media & Transcripts](#-media--transcripts)
  - [🔍 Search & Research](#-search--research)
  - [📈 Marketing & Growth](#-marketing--growth)
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
- [🔌 Plugins](#-plugins)
- [🧠 Agent Profiles](#-agent-profiles)
- [💾 Memory Providers](#-memory-providers)
- [🔗 Surfaces & Integrations](#-surfaces--integrations)
- [🛠️ Tools, Workspaces & GUIs](#%EF%B8%8F-tools-workspaces--guis)
- [🔄 Skills → Plugins](#-skills--plugins)
- [📚 Skill Registries & Discovery](#-skill-registries--discovery)
- [📖 Guides & Documentation](#-guides--documentation)
- [🔗 Related Lists](#-related-lists)
- [🛡️ Security Notice](#%EF%B8%8F-security-notice)
- [🤝 Contributing](#-contributing)
- [📰 Stay in the Loop](#-stay-in-the-loop)
- [License](#license)

---

## ⭐ Editor's Picks

A short hand-picked list to get you started. If you install nothing else from this page, install these.

*Selection is editorial; the order is not. Picks are listed **most-starred first**, so the ranking is something you can check rather than something you have to trust. Counts re-pulled from the GitHub API 2026-08-24 09:23 UTC; on a list this size they drift within hours, so treat the figure as of that timestamp and the ordering as the durable claim.*

### 🛠️ mattpocock/skills — Skills For Real Engineers
**production** · [Matt Pocock](https://github.com/mattpocock) · [Repo](https://github.com/mattpocock/skills) · 242.3k★

```bash
npx skills@latest add mattpocock/skills
```

Twenty-three battle-tested skills from the Total TypeScript creator. The `grill-me` and `grill-with-docs` skills force the agent to interview you before writing code — the single best fix for "the agent didn't do what I wanted." `tdd` enforces red-green-refactor. `improve-codebase-architecture` rescues codebases that have become balls of mud. `wayfinder` maps work too big for one session onto decision tickets. Built for real engineering work, not vibe coding. Pick the ones you want with the installer's interactive picker.

### 🖥️ hermes-workspace
**production** · [outsourc-e](https://github.com/outsourc-e) · [Repo](https://github.com/outsourc-e/hermes-workspace) · 6.5k★

Web-based workspace with chat, terminal, memory browser, skills manager, and inspector. The most complete GUI for Hermes. Built during Nous Hackathon 2026. Pairs well with everything else on this list.

### 🔬 SkillClaw
**production** · [AMAP-ML](https://github.com/AMAP-ML) · [Repo](https://github.com/AMAP-ML/SkillClaw) · 2.5k★

Open-source companion that auto-evolves, deduplicates, and improves your skill library from real session data. Sits on top of Hermes's built-in skill creation and adds a post-task evolution loop. Native Hermes integration via `~/.hermes/skills`, with safety flows (`skillclaw doctor hermes` / `skillclaw restore hermes`).

### 🎬 youtube-full
**production** · [@therohitdas](https://github.com/therohitdas) · [Repo](https://github.com/ZeroPointRepo/youtube-skills) · 586★

```bash
hermes skills install skills-sh/ZeroPointRepo/youtube-skills/skills/youtube-full
```

If your agent can't read YouTube, half the internet is invisible to it. This skill gives Hermes transcript extraction, channel browsing, search, and playlist parsing — no Google API key, and nothing to install or maintain. Powered by [TranscriptAPI](https://transcriptapi.com). Works in Hermes, Claude, OpenClaw and other agent runtimes.

### 🛡️ resemble-ai/detect-skill
**beta** · [Resemble AI](https://github.com/resemble-ai) · [Repo](https://github.com/resemble-ai/detect-skill) · 71★

Deepfake detection for agents that ingest user-submitted media. Detects AI-generated audio, image, video, and text. Traces audio source (ElevenLabs, Resemble, etc.), applies invisible watermarks for provenance, and verifies speaker identity. The first thing to install if your agent reads the public internet.

---

## 📦 Built-in Skills (Ships with Hermes)

> Hermes ships with **82 built-in skills** out of the box, across 14 categories — loaded and ready the moment you run `hermes`. You don't install these.
>
> This is what you already have before you add anything. Most "I need a skill for X" questions are answered here first — and the [optional catalog](#-optional-skills-bundled-with-hermes) below covers 117 more you can switch on.

<details open>
<summary><h3 style="display:inline">🍎 Apple (4)</h3></summary>

- **apple-notes** — Manage Apple Notes via memo CLI: create, search, edit.
- **apple-reminders** — Apple Reminders via remindctl: add, list, complete.
- **findmy** — Track Apple devices/AirTags via FindMy.app on macOS.
- **imessage** — Send and receive iMessages/SMS via the imsg CLI on macOS.
</details>

<details open>
<summary><h3 style="display:inline">🤖 Autonomous Ai Agents (6)</h3></summary>

- **claude-code** — Delegate coding to Claude Code CLI (features, PRs).
- **codex** — Delegate coding to OpenAI Codex CLI (features, PRs).
- **computer-use** — Drive the desktop in the background without stealing focus.
- **hermes-agent** — Use, configure, theme, extend, and orchestrate Hermes Agent.
- **merge-reconciler** — Neutral third-party resolution of agent merge conflicts.
- **opencode** — Delegate coding to OpenCode CLI (features, PR review).
</details>

<details open>
<summary><h3 style="display:inline">🎨 Creative (16)</h3></summary>

- **architecture-diagram** — Dark-themed SVG architecture/cloud/infra diagrams as HTML.
- **ascii-art** — ASCII art: pyfiglet, cowsay, boxes, image-to-ascii.
- **ascii-video** — ASCII video: convert video/audio to colored ASCII MP4/GIF.
- **baoyu-infographic** — Infographics: 21 layouts x 21 styles (信息图, 可视化).
- **claude-design** — Design one-off HTML artifacts (landing, deck, prototype).
- **comfyui** — Generate images, video, and audio via diffusion workflows.
- **design-md** — Author/validate/export Google's DESIGN.md token spec files.
- **excalidraw** — Hand-drawn Excalidraw JSON diagrams (arch, flow, seq).
- **humanizer** — Humanize text: strip AI-isms and add real voice.
- **manim-video** — Manim CE animations: 3Blue1Brown math/algo videos.
- **p5js** — p5.js sketches: gen art, shaders, interactive, 3D.
- **popular-web-designs** — 54 real design systems (Stripe, Linear, Vercel) as HTML/CSS.
- **pretext** — Build creative browser demos with DOM-free text layout.
- **sketch** — Throwaway HTML mockups: 2-3 design variants to compare.
- **songwriting-and-ai-music** — Songwriting craft and Suno AI music prompts.
- **touchdesigner-mcp** — Control TouchDesigner via twozero MCP.
</details>

<details open>
<summary><h3 style="display:inline">🔧 DevOps (1)</h3></summary>

- **sdlc-review** — Review Kanban handoffs and route verified outcomes.
</details>

<details open>
<summary><h3 style="display:inline">✉️ Email (2)</h3></summary>

- **email-inbox-triage** — Triage an inbox: prioritize threads, draft replies safely.
- **himalaya** — Himalaya CLI: IMAP/SMTP email from terminal.
</details>

<details open>
<summary><h3 style="display:inline">🐙 GitHub (7)</h3></summary>

- **codebase-inspection** — Inspect codebases w/ pygount: LOC, languages, ratios.
- **github-auth** — GitHub auth setup: HTTPS tokens, SSH keys, gh CLI login.
- **github-code-review** — Review PRs: diffs, inline comments via gh or REST.
- **github-issue-to-pr** — Carry a GitHub issue to a verified PR with honest CI state.
- **github-issues** — Create, triage, label, assign GitHub issues via gh or REST.
- **github-pr-workflow** — GitHub PR lifecycle: branch, commit, open, CI, merge.
- **github-repo-management** — Clone/create/fork repos; manage remotes, releases.
</details>

<details open>
<summary><h3 style="display:inline">📺 Media (3)</h3></summary>

- **gif-search** — Search/download GIFs from Tenor via curl + jq.
- **songsee** — Audio spectrograms/features (mel, chroma, MFCC) via CLI.
- **youtube-content** — YouTube transcripts to summaries, threads, blogs.
</details>

<details open>
<summary><h3 style="display:inline">🤖 MLOps (5)</h3></summary>

- **evaluating-llms-harness** — lm-eval-harness: benchmark LLMs (MMLU, GSM8K, etc.).
- **huggingface-hub** — HuggingFace hf CLI: search/download/upload models, datasets.
- **llama-cpp** — llama.cpp local GGUF inference + HF Hub model discovery.
- **serving-llms-vllm** — vLLM: high-throughput LLM serving, OpenAI API, quantization.
- **weights-and-biases** — W&B: log ML experiments, sweeps, model registry, dashboards.
</details>

<details open>
<summary><h3 style="display:inline">📝 Note Taking (1)</h3></summary>

- **obsidian** — Read, search, create, and edit notes in the Obsidian vault.
</details>

<details open>
<summary><h3 style="display:inline">📊 Productivity (17)</h3></summary>

- **airtable** — Airtable REST API via curl. Records CRUD, filters, upserts.
- **box** — Box cloud storage: files, sharing, search, metadata, content extraction.
- **document-to-action-items** — Extract cited obligations, deadlines, tasks from documents.
- **docx** — Create, read, edit, template, and review Word .docx files.
- **google-workspace** — Gmail, Calendar, Drive, Docs, Sheets via gws CLI or Python.
- **maps** — Geocode, POIs, routes, timezones via OpenStreetMap/OSRM.
- **meeting-action-items** — Turn meeting notes into cited decisions, owners, tickets.
- **nano-pdf** — Edit text in existing PDFs via natural-language prompts.
- **notion** — Notion API + ntn CLI: pages, databases, markdown, Workers.
- **ocr-and-documents** — Extract text from PDFs/scans (pymupdf, marker-pdf).
- **pdf** — Create, read, merge, fill, and secure PDF files.
- **powerpoint** — Create, read, edit .pptx decks with python-pptx.
- **product-price-monitor** — Watch product, flight, or listing prices; alert on target.
- **session-librarian** — Organize sessions by prompt: find, rename, archive, prune.
- **teams-meeting-pipeline** — Teams meeting summaries, job replay, Graph subscriptions.
- **weekly-review-planning** — Weekly reset: commitments, stalled work, next-week plan.
- **xlsx** — Create, read, edit Excel .xlsx workbooks and CSVs.
</details>

<details open>
<summary><h3 style="display:inline">🔬 Research (7)</h3></summary>

- **arxiv** — Search arXiv papers by keyword, author, category, or ID.
- **blocked-page-recovery** — Recover blocked, paywalled or WAF-blocked pages via fallbacks.
- **blogwatcher** — Monitor blogs and RSS/Atom feeds via blogwatcher-cli tool.
- **competitor-news-monitor** — Watch named companies for material news; cited digests.
- **grounded-citations** — Ground answers and documents in cited, verifiable sources.
- **llm-wiki** — Karpathy's LLM Wiki: build/query interlinked markdown KB.
- **research-paper-writing** — Write ML papers for NeurIPS/ICML/ICLR: design→submit.
</details>

<details open>
<summary><h3 style="display:inline">🏠 Smart Home (1)</h3></summary>

- **openhue** — Control Philips Hue lights, scenes, rooms via OpenHue CLI.
</details>

<details open>
<summary><h3 style="display:inline">🐦 Social Media (1)</h3></summary>

- **xurl** — X/Twitter via xurl CLI: raw post search, posting, DM, media.
</details>

<details open>
<summary><h3 style="display:inline">💻 Software Development (11)</h3></summary>

- **dogfood** — Exploratory QA of web apps: find bugs, evidence, reports.
- **hermes-agent-skill-authoring** — Author in-repo SKILL.md files: frontmatter and structure.
- **inspecting-hermes-desktop-dom** — Read the live Hermes desktop DOM/CSS over CDP.
- **node-inspect-debugger** — Debug Node.js via --inspect + Chrome DevTools Protocol CLI.
- **plan** — Write a markdown plan to .hermes/plans/; no execution.
- **python-debugpy** — Debug Python: pdb REPL + debugpy remote (DAP).
- **requesting-code-review** — Pre-commit review: security scan, quality gates, auto-fix.
- **simplify-code** — Parallel 4-agent cleanup of recent code changes.
- **spike** — Throwaway experiments to validate an idea before build.
- **systematic-debugging** — 4-phase root cause debugging: understand bugs before fixing.
- **test-driven-development** — TDD: enforce RED-GREEN-REFACTOR, tests before code.
</details>

---

## 🧩 Optional Skills (Bundled with Hermes)

> Beyond the always-on built-ins, Hermes bundles a **117-skill optional catalog** — shipped in the repo but off by default, so your context stays lean until you need them. Browse [`optional-skills/`](https://github.com/NousResearch/hermes-agent/tree/main/optional-skills) and enable the ones your workflow calls for.
>
> This is where the deep, domain-specific power lives: **31 MLOps skills** (training, serving, vector DBs, interpretability), a full **finance-modeling suite** (DCF, LBO, merger, 3-statement), plus OSINT, blockchain, payments, and more.

<details>
<summary><h3 style="display:inline">🤖 Autonomous Ai Agents (5)</h3></summary>

- **antigravity-cli** — Operate the Antigravity CLI (agy): plugins, auth, sandbox.
- **blackbox** — Delegate coding tasks to the Blackbox AI multi-model CLI.
- **grok** — Delegate coding to xAI Grok Build CLI (features, PRs).
- **honcho** — Configure and troubleshoot Honcho memory for Hermes.
- **openhands** — Delegate coding to OpenHands CLI (model-agnostic, LiteLLM).
</details>

<details>
<summary><h3 style="display:inline">⛓️ Blockchain (3)</h3></summary>

- **evm** — Read-only EVM client: wallets, tokens, gas across 8 chains.
- **hyperliquid** — Hyperliquid market data, account history, trade review.
- **solana** — Query Solana wallets, tokens, txs, and NFTs in USD.
</details>

<details>
<summary><h3 style="display:inline">💬 Communication (1)</h3></summary>

- **one-three-one-rule** — 1-3-1 decision briefs: problem, three options, one pick.
</details>

<details>
<summary><h3 style="display:inline">🎨 Creative (15)</h3></summary>

- **audiocraft-audio-generation** — AudioCraft: MusicGen text-to-music, AudioGen text-to-sound.
- **baoyu-article-illustrator** — Article illustrations: type × style × palette consistency.
- **baoyu-comic** — Knowledge comics (知识漫画): educational, biography, tutorial.
- **concept-diagrams** — Generate flat, minimal educational SVG visuals as HTML.
- **creative-ideation** — Generate ideas via named methods from creative practice.
- **draw-your-font** — Turn a handwriting photo into an installable TTF font.
- **heartmula** — HeartMuLa: Suno-like song generation from lyrics + tags.
- **hyperframes** — Render MP4/WebM videos from HTML compositions.
- **kanban-video-orchestrator** — Plan and run multi-agent video production pipelines.
- **meme-generation** — Create meme PNGs from templates with Pillow text overlay.
- **pixel-art** — Pixel art w/ era palettes (NES, Game Boy, PICO-8).
- **simple-english** — Rewrite text to ASD-STE100 Simplified Technical English.
- **social-media-content-calendar** — Plan multi-platform social campaigns: briefs to posting.
- **tldraw-offline** — Drive and script tldraw offline canvases with an agent.
- **unreal-mcp** — Automate Unreal Engine editor scenes, actors, and renders.
</details>

<details>
<summary><h3 style="display:inline">📊 Data Science (1)</h3></summary>

- **jupyter-notebook** — Iterative Python via live Jupyter kernel (hamelnb).
</details>

<details>
<summary><h3 style="display:inline">🔧 DevOps (6)</h3></summary>

- **actual-setup** — Set up Actual Computer (actual.inc) inference in Hermes.
- **docker-management** — Manage Docker containers, images, volumes, and Compose.
- **hermes-s6-container-supervision** — Modify or debug s6 services in the Hermes Docker image.
- **inference-sh-cli** — Run 150+ AI apps (image, video, LLM) via inference.sh CLI.
- **pinggy-tunnel** — Zero-install localhost tunnels over SSH via Pinggy.
- **watchers** — Poll RSS, JSON APIs, and GitHub with watermark dedup.
</details>

<details>
<summary><h3 style="display:inline">🐶 Dogfood (1)</h3></summary>

- **adversarial-ux-test** — Roleplay a hostile user to find and triage UX pain points.
</details>

<details>
<summary><h3 style="display:inline">✉️ Email (1)</h3></summary>

- **agentmail** — Give the agent its own inbox: send and receive email.
</details>

<details>
<summary><h3 style="display:inline">💰 Finance (9)</h3></summary>

- **3-statement-model** — Build integrated IS/BS/CF financial workbooks in Excel.
- **comps-analysis** — Build comparable-company valuation workbooks in Excel.
- **dcf-model** — Build discounted cash flow valuation workbooks in Excel.
- **excel-author** — Build auditable financial workbooks headless via openpyxl.
- **lbo-model** — Build leveraged buyout workbooks with IRR/MOIC in Excel.
- **merger-model** — Build M&A accretion/dilution workbooks in Excel.
- **polymarket** — Query Polymarket: markets, prices, orderbooks, history.
- **pptx-author** — Build PowerPoint decks headless with python-pptx.
- **stocks** — Stock quotes, history, search, compare, crypto via Yahoo.
</details>

<details>
<summary><h3 style="display:inline">🎮 Gaming (2)</h3></summary>

- **minecraft-modpack-server** — Host modded Minecraft servers (CurseForge, Modrinth).
- **pokemon-player** — Play Pokemon via headless emulator + RAM reads.
</details>

<details>
<summary><h3 style="display:inline">🏥 Health (2)</h3></summary>

- **fitness-nutrition** — Workout planning, macros, and body metrics via wger/USDA.
- **neuroskill-bci** — Use live BCI cognitive and mood state from NeuroSkill.
</details>

<details>
<summary><h3 style="display:inline">🔌 MCP (3)</h3></summary>

- **fastmcp** — Build, test, and deploy Python MCP servers.
- **mcp-oauth-remote-gateway** — Manual OAuth for remote MCP servers on headless gateways.
- **mcporter** — List, auth, and call MCP servers/tools from the terminal.
</details>

<details>
<summary><h3 style="display:inline">🔀 Migration (1)</h3></summary>

- **openclaw-migration** — Import an OpenClaw setup (memories, skills) into Hermes.
</details>

<details>
<summary><h3 style="display:inline">🤖 MLOps (31)</h3></summary>

- **accelerate** — Run PyTorch training across GPUs with minimal changes.
- **axolotl** — Axolotl: YAML LLM fine-tuning (LoRA, DPO, GRPO).
- **chroma** — Embedding database for RAG and semantic search.
- **clip** — Zero-shot image classification and image-text search.
- **dspy** — DSPy: declarative LM programs, auto-optimize prompts, RAG.
- **faiss** — Fast vector similarity search at billion scale.
- **flash-attention** — Speed up long-sequence transformer training and inference.
- **guidance** — Constrain LLM output with grammars; guarantee valid JSON.
- **huggingface-tokenizers** — Fast BPE/WordPiece tokenization and custom vocab training.
- **instructor** — Structured LLM outputs validated with Pydantic.
- **lambda-labs** — On-demand GPU cloud instances for ML training.
- **llava** — Vision-language chat: VQA, captioning, image dialogue.
- **modal** — Serverless GPU cloud for ML jobs and model APIs.
- **nemo-curator** — Curate LLM training data: dedupe, filter, PII redaction.
- **obliteratus** — OBLITERATUS: abliterate LLM refusals (diff-in-means).
- **outlines** — Outlines: structured JSON/regex/Pydantic LLM generation.
- **peft** — Fine-tune large LLMs with LoRA on limited GPU memory.
- **pinecone** — Managed vector DB for production RAG and search.
- **pytorch-fsdp** — Fully sharded data-parallel training for large models.
- **pytorch-lightning** — Clean training loops with built-in distributed support.
- **qdrant** — Vector search engine for production RAG systems.
- **saelens** — Train sparse autoencoders to interpret model features.
- **segment-anything-model** — SAM: zero-shot image segmentation via points, boxes, masks.
- **simpo** — Reference-free preference alignment, simpler than DPO.
- **slime** — RL post-training for LLMs with Megatron and SGLang.
- **stable-diffusion** — Text-to-image generation, inpainting, and img2img.
- **tensorrt-llm** — High-throughput LLM inference on NVIDIA GPUs.
- **torchtitan** — Pretrain LLMs at scale with PyTorch 4D parallelism.
- **trl-fine-tuning** — TRL: SFT, DPO, GRPO, RLOO reward modeling for LLM RLHF.
- **unsloth** — Unsloth: 2-5x faster LoRA/QLoRA fine-tuning, less VRAM.
- **whisper** — Transcribe and translate speech in 99 languages.
</details>

<details>
<summary><h3 style="display:inline">💳 Payments (3)</h3></summary>

- **mpp-agent** — Pay HTTP 402 APIs via Machine Payments Protocol (MPP).
- **stripe-link-cli** — Agent payments via Stripe Link — cards, SPT, approvals.
- **stripe-projects** — Provision SaaS services + sync creds via Stripe Projects.
</details>

<details>
<summary><h3 style="display:inline">📊 Productivity (7)</h3></summary>

- **canvas** — Fetch Canvas LMS courses and assignments via API token.
- **here-now** — Publish sites to {slug}.here.now and store files in Drives.
- **memento-flashcards** — Spaced-repetition flashcards: create, review, quiz, export.
- **shop** — Shop catalog search, checkout, order tracking, returns.
- **shopify** — Query Shopify Admin/Storefront GraphQL APIs via curl.
- **siyuan** — Query and edit a SiYuan knowledge base via its API.
- **telephony** — Provision Twilio numbers, SMS/MMS, and AI outbound calls.
</details>

<details>
<summary><h3 style="display:inline">🔬 Research (12)</h3></summary>

- **bioinformatics** — Gateway to 400+ genomics and computational biology skills.
- **darwinian-evolver** — Evolve prompts/regex/SQL/code with Imbue's evolution loop.
- **domain-intel** — Passive recon of subdomains, SSL certs, WHOIS, and DNS.
- **drug-discovery** — Drug discovery: ChEMBL search, drug-likeness, interactions.
- **duckduckgo-search** — Free keyless web, news, and image search via ddgs.
- **gitnexus-explorer** — Serve an interactive codebase knowledge graph web UI.
- **osint-investigation** — Follow the money via public records and sanctions data.
- **parallel-cli** — Agent-native web search, deep research, and enrichment.
- **pinecone-research** — Agent RAG and long-term memory with Pinecone.
- **qmd** — Hybrid local search over notes, docs, and transcripts.
- **scrapling** — Scrape sites with stealth browsing and Cloudflare bypass.
- **searxng-search** — Free keyless meta-search aggregating 70+ engines.
</details>

<details>
<summary><h3 style="display:inline">🔐 Security (6)</h3></summary>

- **1password** — Set up op CLI, sign in, and read or inject secrets.
- **godmode** — Jailbreak LLMs: Parseltongue, GODMODE, ULTRAPLINIAN.
- **oss-forensics** — GitHub supply-chain forensics: recovery, IOCs, reporting.
- **sherlock** — Find accounts for a username across 400+ platforms.
- **unbroker** — Autonomously remove your info from data-broker sites.
- **web-pentest** — Authorized web pentest: recon, proof-based exploits, report.
</details>

<details>
<summary><h3 style="display:inline">💻 Software Development (4)</h3></summary>

- **ast-grep** — AST-aware structural code search and rewrite via ast-grep.
- **code-wiki** — Generate wiki docs + Mermaid diagrams for any codebase.
- **rest-graphql-debug** — Debug REST/GraphQL APIs: status codes, auth, schemas, repro.
- **subagent-driven-development** — Execute plans via delegate_task subagents (2-stage review).
</details>

<details>
<summary><h3 style="display:inline">🌐 Web Development (3)</h3></summary>

- **cloudflare-temporary-deploy** — Deploy a Worker live, no account, via wrangler --temporary.
- **har-derived-api-client** — Record a site's XHR to a HAR, derive an HTTP client.
- **page-agent** — Embed an in-page natural-language GUI copilot in web apps.
</details>

<details>
<summary><h3 style="display:inline">💬 Yuanbao (1)</h3></summary>

- **yuanbao** — Yuanbao (元宝) groups: @mention users, query info/members.
</details>

---

## 🌟 Community Skills

> Skills, plugins, and integrations built by the Hermes community. Tagged for maturity. Click through for install instructions per project.

### 📺 Media & Transcripts

- [hermes-spotify-skill](https://github.com/Alexeyisme/hermes-spotify-skill) by [Alexeyisme](https://github.com/Alexeyisme) — Spotify control for headless Linux and Raspberry Pi. The only Linux-native Spotify skill in the ecosystem. **[beta]**
- [youtube-skills](https://github.com/ZeroPointRepo/youtube-skills) by [therohitdas](https://github.com/therohitdas) — Transcripts, search, channels, playlists. Cross-agent: Hermes, Claude, OpenClaw and other agent runtimes. Powered by [TranscriptAPI](https://transcriptapi.com). **[production]**

### 🔍 Search & Research

- [consensus-mcp-hermes](https://github.com/ahmdngi/consensus-mcp-hermes) by [ahmdngi](https://github.com/ahmdngi) — Connect 200M+ peer-reviewed research papers to Hermes via the Consensus MCP server. OAuth setup guide for headless environments with mcp-remote bridge. **[beta]**
- [deep-research](https://github.com/moonlight-lupin/agent-skills/tree/main/research/deep-research) by [moonlight-lupin](https://github.com/moonlight-lupin) — Autonomous Think→Search→Extract→Synthesize→Stop loop that produces cited research reports. **[production]**
- [hermes-web-search-plus](https://github.com/robbyczgw-cla/hermes-web-search-plus) by [robbyczgw-cla](https://github.com/robbyczgw-cla) — Multi-provider web search with intelligent routing across Serper, Tavily, Exa, and more. Replaces built-in search with better quality + source diversity. **[beta]**
- [Not Human Search](https://github.com/unitedideas/nothumansearch-mcp) by [unitedideas](https://github.com/unitedideas) — MCP server for discovering other MCP servers. Indexes 8,600+ agent-friendly sites with agentic scoring. Lets Hermes find new tools on its own. **[production]**
- [Scavio](https://github.com/scavio-ai/hermes-agent) by [scavio-ai](https://github.com/scavio-ai) — Structured web data from 31 platforms through one hosted MCP server: search, retail, social, property and SEC filings, plus five research workflow skills. Credit-metered, with 50 free credits on signup. **[beta]**

### 📈 Marketing & Growth

- [hermes-startup](https://github.com/33hodl/hermes-startup) by [33hodl](https://github.com/33hodl) — Walks a personal profile into a ranked idea shortlist and a tool plan for a first paying customer. No income claims. **[beta]**
- [notfair-plugin](https://github.com/nowork-studio/notfair-plugin) by [NoWork Studio](https://github.com/nowork-studio) — 40+ host-agnostic skills for SEO, GEO, Google Ads and Meta Ads, with approval-gated MCP actions on connected accounts. **[beta]**

### 💻 Dev & Skill Authoring

#### 🔥 mattpocock/skills — Engineering bundle
> Install all at once: `npx skills@latest add mattpocock/skills` — pick which skills you want at install time.

- [ask-matt](https://github.com/mattpocock/skills/blob/main/skills/engineering/ask-matt/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Router over the rest of the pack: describe your situation, get told which skill or flow fits. **[production]**
- [code-review](https://github.com/mattpocock/skills/blob/main/skills/engineering/code-review/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Reviews changes since a fixed point along two axes at once — does it follow the repo's standards, and does it match what the spec asked for. **[production]**
- [codebase-design](https://github.com/mattpocock/skills/blob/main/skills/engineering/codebase-design/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Shared vocabulary for designing deep modules: where a seam goes, what makes code testable and AI-navigable. **[production]**
- [diagnosing-bugs](https://github.com/mattpocock/skills/blob/main/skills/engineering/diagnosing-bugs/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Disciplined diagnosis loop for hard bugs and performance regressions: reproduce, minimise, hypothesise, instrument, fix. **[production]**
- [domain-modeling](https://github.com/mattpocock/skills/blob/main/skills/engineering/domain-modeling/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Pins down a project's ubiquitous language and records architectural decisions as you go. **[production]**
- [git-guardrails-claude-code](https://github.com/mattpocock/skills/blob/main/skills/misc/git-guardrails-claude-code/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Blocks dangerous git commands — push, `reset --hard`, `clean`, `branch -D` — before they execute. Hooks-based. **[production]**
- [grill-with-docs](https://github.com/mattpocock/skills/blob/main/skills/engineering/grill-with-docs/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Relentless interview that sharpens a plan and writes the ADRs and glossary entries as it goes. The most popular skill in the pack. **[production]**
- [implement](https://github.com/mattpocock/skills/blob/main/skills/engineering/implement/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Builds a piece of work from an existing spec or set of tickets, rather than from a conversation. **[production]**
- [improve-codebase-architecture](https://github.com/mattpocock/skills/blob/main/skills/engineering/improve-codebase-architecture/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Scans for deepening opportunities, presents them as a visual HTML report, then grills through whichever you pick. **[production]**
- [migrate-to-shoehorn](https://github.com/mattpocock/skills/blob/main/skills/misc/migrate-to-shoehorn/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Migrates test files from `as` type assertions to @total-typescript/shoehorn. **[production]**
- [prototype](https://github.com/mattpocock/skills/blob/main/skills/engineering/prototype/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Builds a throwaway prototype to answer one design question, then throws it away. **[production]**
- [research](https://github.com/mattpocock/skills/blob/main/skills/engineering/research/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Investigates a question against primary sources and commits the findings as Markdown in the repo. **[production]**
- [resolving-merge-conflicts](https://github.com/mattpocock/skills/blob/main/skills/engineering/resolving-merge-conflicts/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Works through an in-progress merge or rebase conflict rather than guessing at it. **[production]**
- [scaffold-exercises](https://github.com/mattpocock/skills/blob/main/skills/misc/scaffold-exercises/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Creates exercise directory structures with sections, problems, solutions and explainers. **[production]**
- [setup-matt-pocock-skills](https://github.com/mattpocock/skills/blob/main/skills/engineering/setup-matt-pocock-skills/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Run once first: configures the repo's issue tracker, triage labels and domain doc layout for the rest of the pack. **[production]**
- [setup-pre-commit](https://github.com/mattpocock/skills/blob/main/skills/misc/setup-pre-commit/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Sets up Husky pre-commit hooks with lint-staged, Prettier, type checking and tests. **[production]**
- [tdd](https://github.com/mattpocock/skills/blob/main/skills/engineering/tdd/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Test-driven development with a red-green-refactor loop, one vertical slice at a time. **[production]**
- [to-spec](https://github.com/mattpocock/skills/blob/main/skills/engineering/to-spec/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Turns the current conversation into a spec and publishes it to your issue tracker. No interview, just synthesis. **[production]**
- [to-tickets](https://github.com/mattpocock/skills/blob/main/skills/engineering/to-tickets/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Breaks a plan or spec into tracer-bullet tickets, each declaring its blocking edges. **[production]**
- [triage](https://github.com/mattpocock/skills/blob/main/skills/engineering/triage/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Moves issues and external PRs through a state machine of triage roles and writes agent-ready briefs. **[production]**
- [wayfinder](https://github.com/mattpocock/skills/blob/main/skills/engineering/wayfinder/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Plans work too large for one agent session as a map of decision tickets, resolved one at a time. **[production]**
- [wizard](https://github.com/mattpocock/skills/blob/main/skills/engineering/wizard/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Generates an interactive bash wizard for the steps only a human can do — dashboards, credentials, cutovers. **[production]**
- [writing-for-agents](https://github.com/mattpocock/skills/blob/main/skills/productivity/writing-for-agents/SKILL.md) by [mattpocock](https://github.com/mattpocock) — How to write documents agents actually follow. Use it when authoring a skill or editing `AGENTS.md`. **[production]**

#### Hermes-native skill builders

- [Agent QA skills](https://github.com/vostride/agent-qa/tree/main/skills) by [Vostride](https://github.com/vostride) — Three portable skills for authoring Agent QA tests, triaging failed runs from evidence, and applying scoped fixes through MCP or CLI. **[beta]**
- [Agentic-MCP-Skill](https://github.com/cablate/Agentic-MCP-Skill) by [cablate](https://github.com/cablate) — MCP client with agentskills.io validation. **[beta]**
- [awesome-agent-skills](https://github.com/shali10/awesome-agent-skills) by [shali10](https://github.com/shali10) — Curated production-ready skills and tools for Hermes Agent: Telegram native table formatting with CJK alignment, multimedia extraction (Bilibili/YouTube/RSS), large file streaming data analysis, magazine-grade HTML/PDF report compilation, human-voice writing, and tiered memory architecture. **[production]**
- [bmad-module-skill-forge](https://github.com/armelhbobdad/bmad-module-skill-forge) by [armelhbobdad](https://github.com/armelhbobdad) — Transforms repos and docs into agentskills.io-compliant skills. **[beta]**
- [claude-plugin-converter](https://github.com/moonlight-lupin/agent-skills/tree/main/agent-ops/claude-plugin-converter) by [moonlight-lupin](https://github.com/moonlight-lupin) — Two-phase converter: analyse a Claude Code plugin, then emit an installable Hermes plugin. **[beta]**
- [evey-bridge-plugin](https://github.com/42-evey/evey-bridge-plugin) by [42-evey](https://github.com/42-evey) — Claude Code plugin that bridges with Hermes. Shared context, task handoffs. **[beta]**
- [execplan-skill](https://github.com/tiann/execplan-skill) by [tiann](https://github.com/tiann) — Long-running task execution with progress tracking, checkpoints, failure recovery. **[beta]**
- [hermes-cursor-dispatcher](https://github.com/matdev83/hermes-cursor-dispatcher/tree/main/skills/cursor-delegate) by [matdev83](https://github.com/matdev83) — Delegates coding tasks to Cursor CLI from Hermes, in isolated git worktrees. **[beta]**
- [hermes-dojo](https://github.com/Yonkoo11/hermes-dojo) by [Yonkoo11](https://github.com/Yonkoo11) — Self-improvement system that monitors agent performance, identifies weak skills, iterates automatically. **[beta]**
- [hermes-skill-distillation](https://github.com/beardthelion/hermes-skill-distillation) by [beardthelion](https://github.com/beardthelion) — Generates agentic training trajectories from real-world tasks for fine-tuning data. **[beta]**
- [hermes-skill-factory](https://github.com/Romanescu11/hermes-skill-factory) by [Romanescu11](https://github.com/Romanescu11) — Meta-skill that auto-generates reusable skills from your workflows. Point it at a repeated task and it creates a skill for it. **[beta]**
- [lintlang](https://github.com/hermes-labs-ai/lintlang) by [Hermes Labs](https://github.com/hermes-labs-ai) — Zero-LLM static analysis for agent configs, tool descriptions and system prompts. Catches vague tool descriptions and missing stop conditions in CI. **[beta]**
- [litprog-skill](https://github.com/tlehman/litprog-skill) by [tlehman](https://github.com/tlehman) — Literate programming skill across Claude Code, OpenCode, Hermes. Weaves code and prose into documented, executable notebooks. **[beta]**
- [maestro](https://github.com/ReinaMacCredy/maestro) by [ReinaMacCredy](https://github.com/ReinaMacCredy) — Skill orchestration with Conductor planning + Beads tracking. Multi-step skills as observable pipelines. **[beta]**
- [model-compare](https://github.com/moonlight-lupin/agent-skills/tree/main/mlops/model-compare) by [moonlight-lupin](https://github.com/moonlight-lupin) — Blind multi-model A/B comparison across tool-calling, coding and review modes, with token-efficiency metrics. **[production]**
- [pydantic-ai-skills](https://github.com/DougTrajano/pydantic-ai-skills) by [DougTrajano](https://github.com/DougTrajano) — Pydantic AI with agentskills.io. Type-safe schema validation for skill inputs/outputs. **[production]**
- [rtk-hermes](https://github.com/ogallotti/rtk-hermes) by [ogallotti](https://github.com/ogallotti) — Compresses terminal output via RTK before it reaches LLM context. 60-90% token reduction. Zero config. **[beta]**
- [skill-maintainer](https://github.com/moonlight-lupin/agent-skills/tree/main/agent-ops/skill-maintainer) by [moonlight-lupin](https://github.com/moonlight-lupin) — End-to-end skill library maintenance: author, curate, track upstream drift, publish. **[beta]**
- [SkillClaw](https://github.com/AMAP-ML/SkillClaw) by [AMAP-ML](https://github.com/AMAP-ML) — Auto-evolves and dedupes your skill library from session data. Native Hermes integration. 2.5k★. **[production]**
- [skillsdotnet](https://github.com/PederHP/skillsdotnet) by [PederHP](https://github.com/PederHP) — C# implementation of agentskills.io with MCP integration. **[beta]**
- [super-hermes](https://github.com/Cranot/super-hermes) by [Cranot](https://github.com/Cranot) — Teaches Hermes to write its own analytical prompts. Meta-reasoning before execution. **[experimental]**
- [windows-terminal-hygiene](https://github.com/vollegrewar/windows-terminal-hygiene) by [vollegrewar](https://github.com/vollegrewar) — Pre-flight checklist that keeps agent terminal commands from hanging on Windows: timeouts, non-interactive flags, pty, encoding, and a 3-minute recovery flow. **[beta]**
- [wondelai/skills](https://github.com/wondelai/skills) by [wondelai](https://github.com/wondelai) — Cross-platform agent skills for Claude Code and agentskills.io platforms. 2.1k★. **[production]**

### 🌐 Browser & Web

- [hermes-cloudflare](https://github.com/raulvidis/hermes-cloudflare) by [raulvidis](https://github.com/raulvidis) — Cloudflare browser rendering plugin. Headless browsing through Cloudflare's infrastructure. **[experimental]**
- [hermes-plugin-chrome-profiles](https://github.com/anpicasso/hermes-plugin-chrome-profiles) by [anpicasso](https://github.com/anpicasso) — Switch browser tools between Chrome profiles via CDP. Multi-account testing. **[experimental]**
- [vessel-browser](https://github.com/unmodeled-tyler/vessel-browser) by [unmodeled-tyler](https://github.com/unmodeled-tyler) — AI-native Linux browser with MCP control and autonomous browsing. Built for agent use, not a headless wrapper. **[experimental]**

### ✉️ Communication & Social

- [clawsocial-hermes-plugin](https://github.com/mrpeter2025/clawsocial-hermes-plugin) by [mrpeter2025](https://github.com/mrpeter2025) — Social discovery network. Semantic interest matching, real-time WebSocket messaging, shareable profile cards. Bilingual EN+CN. **[beta]**
- [famulor-skill](https://github.com/bekservice/Famulor-Skill) by [Famulor](https://github.com/bekservice) — Operates a Famulor voice-agent workspace over a hosted OAuth MCP server: assistants, call, messaging and email history, campaigns and telephony. **[beta]**
- [hermes-tag](https://github.com/DanielLi202/hermes-tag) by [DanielLi202](https://github.com/DanielLi202) — Context-selection layer for Feishu/Lark and Slack group chats. Answers @-mentions from bounded per-chat evidence instead of full-history RAG, with per-chat memory isolation. **[beta]**
- [hermes-telegram-checklist](https://github.com/johnsje183/hermes-telegram-checklist) by [johnsje183](https://github.com/johnsje183) — Creates and toggles native Telegram checklists in chats and forum topics over MTProto, behind a write allowlist. **[beta]**
- [hermes-tweet](https://github.com/Xquik-dev/hermes-tweet) by [Xquik](https://github.com/Xquik-dev) — Native Hermes Agent X/Twitter plugin for tweet search, reply reading, user lookup, monitoring, posting, replies, DMs, and approval-gated X actions through Xquik. **[beta]**
- [microsoft-workspace-skill](https://github.com/Andrew-Girgis/microsoft-workspace-skill) by [Andrew-Girgis](https://github.com/Andrew-Girgis) — Full Outlook/Hotmail/Microsoft 365 integration via Graph API. Email, calendar, contacts, free/busy. OAuth2 auto-refresh. Preview-before-send pattern. **[beta]**
- [tweetclaw](https://github.com/Xquik-dev/tweetclaw) by [Xquik](https://github.com/Xquik-dev) — OpenClaw plugin and agent skill to scrape tweets, search tweet replies, export followers, look up users, run media, monitors, webhooks, giveaway draws, and approval-gated posts through Xquik. **[beta]**
- [twitr-skills](https://github.com/lnvestor/twitr-skills) by [lnvestor](https://github.com/lnvestor) — Six X/Twitter skills: reads and search, bulk exports, keyword monitors with signed webhooks, publishing, and a presence routine. Pay-per-call in USDC over x402, no API key. **[beta]**

### 📊 Productivity & Tasks

- [agent-analytics-hermes-plugin](https://github.com/Agent-Analytics/agent-analytics-hermes-plugin) by [Agent-Analytics](https://github.com/Agent-Analytics) — Native Signals dashboard tab for Hermes. Read-only multi-project analytics. **[beta]**
- [before-you-build](https://github.com/bin1874/before-you-build-skill) by [bin1874](https://github.com/bin1874) — Product-risk review before implementation. Challenges demand, positioning, monetization, retention, trust, distribution, and feature-adoption risk before an agent starts building. Works with Hermes, OpenClaw, Claude Code, Codex, and other `SKILL.md`-compatible agents. **[production]**
- [grill-me](https://github.com/mattpocock/skills/blob/main/skills/productivity/grill-me/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Get relentlessly interviewed by your agent until every branch of the decision tree is resolved. Use *every* time before making a change. Most popular skill in the pack. **[production]**
- [handoff](https://github.com/mattpocock/skills/blob/main/skills/productivity/handoff/SKILL.md) by [mattpocock](https://github.com/mattpocock) — Compacts the current conversation into a handoff document another agent can pick up cold. **[production]**
- [hermes-plugins](https://github.com/42-evey/hermes-plugins) by [42-evey](https://github.com/42-evey) — Goal management, inter-agent bridge, model selection, cost control. Four plugins covering common operational needs. **[beta]**
- [onequery-cli](https://github.com/wordbricks/skills/tree/main/skills/onequery-cli) by [Wordbricks](https://github.com/wordbricks) — CLI skill for safe, auditable queries for agents against approved data sources. **[beta]**

### 🎨 Creative & Media Generation

- [anti-ui-slop](https://github.com/uizze/uizze) by [UIZZE](https://github.com/uizze) — MIT skill for design contracts, required UI states and hard finish gates on agent-generated UI. Works without an account; live reference search, validation and audits need the paid [UIZZE](https://uizze.com) MCP. **[beta]**
- [black-forest-labs/skills](https://github.com/black-forest-labs/skills) by [Black Forest Labs](https://github.com/black-forest-labs) — Official FLUX model skills for image generation. First-party skills from the FLUX creators. **[production]**
- [hermes-weather-plugin](https://github.com/FahrenheitResearch/hermes-weather-plugin) by [FahrenheitResearch](https://github.com/FahrenheitResearch) — Professional-grade weather plugin with NWS model imagery, NEXRAD radar, meteorological calculations. **[beta]**
- [hermes-wxtrain-plugin](https://github.com/FahrenheitResearch/hermes-wxtrain-plugin) by [FahrenheitResearch](https://github.com/FahrenheitResearch) — ML pipeline for building training datasets from HRRR/GFS/ERA5 weather models. **[experimental]**
- [levea-ai-video-editor](https://github.com/brajendrak00068/agentic-ai-video-production/tree/main/skills/media/levea-ai-video-editor) by [brajendrak00068](https://github.com/brajendrak00068) — Agentic video editing: clip selection, captions, silence removal, vertical reframe, chroma key, MP4 export. **[beta]**
- [lora-concept-removal-tagging](https://github.com/kwanmxiii-bit/Loras-training-tap-skill) by [kwanmxiii-bit](https://github.com/kwanmxiii-bit) — Tags LoRA training images and drops target concepts so the weights absorb them instead. Caption-dropout based. **[beta]**
- [OrkasVideoStudio](https://github.com/Orkas-AI/Orkas-VideoStudio) by [Orkas-AI](https://github.com/Orkas-AI) — Local-first TypeScript CLI and MCP toolkit with 14 skills for agent-authored video composition, editing, generation, and plan-based assembly. **[beta]**
- [runapi-cli](https://github.com/runapi-ai/cli-skill) by [RunAPI](https://github.com/runapi-ai) — Runs image, video, music and model API jobs from any CLI-capable agent. **[beta]**
- [typeui-hermes](https://github.com/bergside/typeui) by [Bergside](https://github.com/bergside) — Design skills that give Hermes a consistent component vocabulary when generating UI; setup in the [Hermes guide](https://www.typeui.sh/docs/guides/hermes). **[production]**

### 🔧 DevOps & Deployment

- [aivpn](https://github.com/ZoniBoy00/aivpn) by [ZoniBoy00](https://github.com/ZoniBoy00) — Per-location Docker WireGuard relay for Proton VPN with kill switch, SOCKS5 and prompt-injection-safe fetching. **[beta]**
- [evey-setup](https://github.com/42-evey/evey-setup) by [42-evey](https://github.com/42-evey) — One-command setup for full hermes-agent stack with free models and 29 plugins. **[beta]**
- [hermes-agent-docker](https://github.com/xmbshwll/hermes-agent-docker) by [xmbshwll](https://github.com/xmbshwll) — Minimal Docker sandbox image for Hermes. Pull, run, done. **[beta]**
- [nika](https://github.com/supernovae-st/nika) by [supernovae-st](https://github.com/supernovae-st) — Deterministic workflow runner Hermes can delegate to. Repeatable jobs become reviewable `.nika.yaml` files with plan, cost and permit checks up front and a hash-chained trace after. **[beta]**
- [nix-hermes-agent](https://github.com/0xrsydn/nix-hermes-agent) by [0xrsydn](https://github.com/0xrsydn) — Nix package and NixOS module. Fully reproducible deployments via Nix flakes. **[beta]**
- [openclaw-to-hermes](https://github.com/0xNyk/openclaw-to-hermes) by [0xNyk](https://github.com/0xNyk) — Community migration tool from OpenClaw to Hermes. **[beta]**

### 💰 Finance, Payments & Crypto

- [AgentCash](https://github.com/Merit-Systems/agentcash-skills) by [Merit-Systems](https://github.com/Merit-Systems) — 300+ premium APIs + wallet for paying via x402 or MPP. Free USDC for trying out. **[beta]**
- [barker-mcp](https://github.com/barkermoney/barker-mcp) by [Barker](https://github.com/barkermoney) — Stablecoin yield skills: live APY index, risk signals, yield advisor. Remote MCP with x402 pay-per-call; discovery is free. **[beta]**
- [chainlink-agent-skills](https://github.com/smartcontractkit/chainlink-agent-skills) by [Chainlink](https://github.com/smartcontractkit) — Official Chainlink skills. Oracle data, CCIP, smart contract interaction. **[production]**
- [erpclaw](https://github.com/avansaber/erpclaw) by [AvanSaber](https://github.com/avansaber) — AI-native open-source ERP and double-entry accounting you self-host and run in plain English. Invoicing, inventory, general ledger, payroll, multi-company books. **[beta]**
- [hermes-blockchain-oracle](https://github.com/gizdusum/hermes-blockchain-oracle) by [gizdusum](https://github.com/gizdusum) — Solana blockchain intelligence MCP server. On-chain analytics and wallet data. **[experimental]**
- [hermes-payguard](https://github.com/nativ3ai/hermes-payguard) by [nativ3ai](https://github.com/nativ3ai) — Safe USDC and x402 payment plugin with spending limits and approval flows. **[experimental]**
- [internet-court-skill](https://github.com/internet-court/internet-court-skill) by [Internet Court Consortium](https://github.com/internet-court) — Trust layer for agent-to-agent commerce: mandates, payments, escrow, dispute resolution. **[beta]**
- [mercury](https://github.com/hxsteric/mercury) by [hxsteric](https://github.com/hxsteric) — Multi-chain blockchain cash flow analyzer with WebGL dashboard. On-chain forensics. **[beta]**
- [ripley-xmr-gateway](https://github.com/KYC-rip/ripley-xmr-gateway) by [KYC-rip](https://github.com/KYC-rip) — Monero (XMR) blockchain gateway. Private cryptocurrency transactions from agent workflows. **[experimental]**
- [true402-token-safety](https://github.com/true402/hermes-skills) by [true402](https://github.com/true402) — Pre-trade rug/honeypot check for Base tokens. Runs a real on-chain buy/sell simulation to prove a token can be sold, plus liquidity and contract structure. Free daily checks, no API key; pays per call over x402 after. **[beta]**

### 🤖 Multi-Agent & Swarms

- [hermes-conductor](https://github.com/forcewake/hermes-conductor) by [forcewake](https://github.com/forcewake) — Kanban-orchestrated multi-harness coding swarm: controller/worker/reviewer skills with evidence-only task completion. **[beta]**
- [hermes-council](https://github.com/Ridwannurudeen/hermes-council) by [Ridwannurudeen](https://github.com/Ridwannurudeen) — Adversarial multi-perspective council MCP. Multiple AI viewpoints debate before commit. **[experimental]**
- [NemoHermes](https://github.com/Hmbown/NemoHermes) by [Hmbown](https://github.com/Hmbown) — NVIDIA capability registry and Spark-aware routing. Routes compute-heavy tasks to GPU infrastructure. **[experimental]**
- [opencode-hermes-multiagent](https://github.com/1ilkhamov/opencode-hermes-multiagent) by [1ilkhamov](https://github.com/1ilkhamov) — 17 specialized agents for OpenCode AI with structured interfaces. **[beta]**

### 🏠 Smart Home, IoT & Embodied

- [agent-android](https://github.com/aivanelabs/ai-rpa/tree/main/skills/agent-android) by [AIVane Labs](https://github.com/aivanelabs) — LAN-first Android control over WiFi. No USB/ADB/root needed. Health checks, taps, swipes, screenshots, inspect→act→smoke flows. **[beta]**
- [argo](https://github.com/Allendior/private-agent/tree/main/skills/argo) by [Allendior](https://github.com/Allendior) — Signed typed jobs from Hermes to a paired Android phone. No on-device LLM; fail-closed taps, Home, Back, and screen reads. **[beta]**
- [hermes-android](https://github.com/raulvidis/hermes-android) by [raulvidis](https://github.com/raulvidis) — Android device bridge with full Python toolset. **[beta]**
- [Hermes-mars-rover](https://github.com/Snehal707/Hermes-mars-rover) by [Snehal707](https://github.com/Snehal707) — Mars rover sim with ROS2 and Gazebo. Hermes skill loop for navigation improvement. **[experimental]**
- [hermes-miniverse](https://github.com/teknium1/hermes-miniverse) by [teknium1](https://github.com/teknium1) — Bridge to Miniverse pixel worlds. By a Nous Research co-founder. **[beta]**
- [hermescraft](https://github.com/bigph00t/hermescraft) by [bigph00t](https://github.com/bigph00t) — Embodied Minecraft companion with persistent memory. Learns building preferences across sessions. **[beta]**

### 🔐 Security & Detection

- [Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) by [mukul975](https://github.com/mukul975) — 753+ structured cybersecurity skills mapped to MITRE ATT&CK. 31.8k★. **[production]**
- [hermes-agent-camel](https://github.com/nativ3ai/hermes-agent-camel) by [nativ3ai](https://github.com/nativ3ai) — Hermes with integrated CaMeL trust boundaries. Formal trust verification for safety-critical deployments. **[beta]**
- [incognito-mode](https://github.com/GenmetsuWenxuePress/hermes-skills) by [幻灭文学出版社](https://github.com/GenmetsuWenxuePress) — Defense-in-depth incognito mode: PID-locked sandbox, shell history suppression, 10-step reverse audit with Python secure wipe, subagent inheritance protocol. **[beta]**
- [resemble-ai/detect-skill](https://github.com/resemble-ai/detect-skill) by [Resemble AI](https://github.com/resemble-ai) — Deepfake detection: AI-generated audio/image/video/text, source tracing, watermarking, speaker ID. **[beta]**
- [Verified Memory Vault](https://github.com/secondbrainstarter/verified-memory-vault) by [secondbrainstarter](https://github.com/secondbrainstarter) — Plain-Markdown Obsidian vault that gives AI coding agents persistent memory, with a health checker (protocol violations, dead links, bloat) and a git pre-commit hook that refuses commits mass-deleting memory files. **[beta]**

### 🎯 Domain & Novelty

- [anihermes](https://github.com/rodmarkun/anihermes) by [rodmarkun](https://github.com/rodmarkun) — Local anime server and tracker with NL interface. Browse, track, get recommendations via conversation. **[beta]**
- [colony-skill](https://github.com/TheColonyAI/colony-skill) by [TheColonyAI](https://github.com/TheColonyAI) — Collaborative intelligence platform. AI + humans post findings, complete tasks, build reputation. **[beta]**
- [Wizards-of-the-Ghosts](https://github.com/Hmbown/Wizards-of-the-Ghosts) by [Hmbown](https://github.com/Hmbown) — Fantasy spell-themed skill pack. `cast lint` instead of `npm run lint`. **[experimental]**
- [zillow-skills](https://github.com/ZeroPointRepo/zillow-skills) by [therohitdas](https://github.com/therohitdas) — Zillow property data skills for AI agents — Zestimate, listings, photos, schools, taxes, price history — via the Zillapi REST API. MIT-0, free tier. **[beta]**

---

## 🔌 Plugins

> Hermes **plugins** — installable packages that add tools, commands, hooks or providers to the agent itself, rather than a single `SKILL.md`. Install with `hermes plugins install <repo>`.

- [babysitter](https://github.com/a5c-ai/babysitter) by [a5c-ai](https://github.com/a5c-ai) — Deterministic supervision loop for agentic workforces: enforces plans, retries and completion criteria on long multi-step runs. **[production]**
- [cronalytics](https://github.com/8bit64k/cronalytics) by [8bit64k](https://github.com/8bit64k) — Analytics and observability for Hermes cron jobs. A dashboard for automations you'd otherwise never see fail. **[beta]**
- [hermes-code-bridge](https://github.com/xuyang-liu16/hermes-code-bridge) by [xuyang-liu16](https://github.com/xuyang-liu16) — Makes Hermes the control plane for local coding agents — Codex, Claude Code, OpenCode, Gemini CLI, Kimi Code. **[beta]**
- [Hermes Connector](https://github.com/CorsenAI/hermes-connector) by [Corsen AI](https://github.com/CorsenAI) — Connects an exact Hermes profile and session to user-selected Chrome tabs through a local companion and authenticated loopback broker. **[production]**
- [hermes-curator-evolver](https://github.com/pingchesu/hermes-curator-evolver) by [pingchesu](https://github.com/pingchesu) — Evidence-driven skill evolution: reports, dry-run proposals, candidate search and guarded apply. **[beta]**
- [hermes-dynamic-workflows](https://github.com/lingjiuu/hermes-dynamic-workflows) by [lingjiuu](https://github.com/lingjiuu) — Composes multi-step workflows at runtime instead of hard-coding them into a skill. **[beta]**
- [hermes-humalike-plugin](https://github.com/Humalike/hermes-humalike-plugin) by [Humalike](https://github.com/Humalike) — Makes a chat-connected Hermes read like a person rather than a bot — pacing, typing behaviour, reply timing. **[beta]**
- [hermes-live-voice](https://github.com/bielcarpi/hermes-live-voice) by [bielcarpi](https://github.com/bielcarpi) — Real-time voice control. Keep talking while Hermes keeps working in the background. **[beta]**
- [hermes-plugin-guard](https://github.com/mauricemohr88-debug/hermes-plugin-guard) by [mauricemohr88-debug](https://github.com/mauricemohr88-debug) — Static, no-execution security checks over Hermes plugins before you install them. **[beta]**
- [hermes-telemetry](https://github.com/nujovich/hermes-telemetry) by [nujovich](https://github.com/nujovich) — Budget enforcement plus observability. Stops runaway spend before it happens rather than reporting it after. **[beta]**
- [planning-with-files](https://github.com/OthmanAdi/planning-with-files) by [OthmanAdi](https://github.com/OthmanAdi) — Crash-proof file-based planning for long-running agent tasks, with session recovery after a context clear. **[production]**
- [signetai](https://github.com/Signet-AI/signetai) by [Signet-AI](https://github.com/Signet-AI) — Syncs memories, shared identity files (`AGENTS.md`, `CLAUDE.md`), transcripts and secrets between agents and machines. **[beta]**

---

## 🧠 Agent Profiles

> Installable Hermes **profiles** — a persona, memory and curated skill/plugin bundle that reconfigures the whole agent for one role. Install with `hermes profile install <repo-url>`.

- [donna-starter](https://github.com/AtlasOmnia/donna-starter) by [AtlasOmnia](https://github.com/AtlasOmnia) — Opinionated starter profile with a persona, 73 curated skills and a guided first run. A good first profile. **[beta]**
- [hermes-profile-kit](https://github.com/NewTurn2017/hermes-profile-kit) by [NewTurn2017](https://github.com/NewTurn2017) — Drop-in kit that creates four isolated profiles — coder, assistant, research, community-bot — with separate config and memory. **[beta]**
- [hermes-profile-packs](https://github.com/Dadmin88/hermes-profile-packs) by [Dadmin88](https://github.com/Dadmin88) — Three profile packs kept as coherent teams rather than isolated prompts: Agency for professional work, Council for personal life, Academy for teaching. Each profile ships its own SOUL.md, skills and distribution manifest. **[beta]**
- [hermes-profiles](https://github.com/magnus919/hermes-profiles) by [magnus919](https://github.com/magnus919) — Curated profiles for specialist swarms. The largest profile collection in the ecosystem. **[production]**
- [theheavenlyd3mon/hermes-profiles](https://github.com/theheavenlyd3mon/hermes-profiles) by [theheavenlyd3mon](https://github.com/theheavenlyd3mon) — Persona-driven profiles for orchestration, coding and research. **[beta]**
- [violin](https://github.com/Strategic-Automation/violin) by [Strategic-Automation](https://github.com/Strategic-Automation) — Supervised pentest profile: 31 playbooks across the OWASP, API and LLM Top 10, with interactive scoping and approval gates before any target-touching command runs. Hermes-native, no extra API keys. **[production]**
- [wisdomforge-kids-Hermes-profiles](https://github.com/smfworks/wisdomforge-kids-Hermes-profiles) by [smfworks](https://github.com/smfworks) — Parent-operated kit for standing up a private, child-facing profile in one of three age bands, with a separate profile per child rather than a shared adult one. Says plainly that it does not make AI safe; it gives a parent a design they can inspect and refuse. **[beta]**

---

## 💾 Memory Providers

> Swap-in backends for Hermes's memory layer. A provider changes what the agent remembers and how it recalls it — install one and the built-in memory tools route through it.

- [agentcairn](https://github.com/ccf/agentcairn) by [ccf](https://github.com/ccf) — Long-term cross-project memory backed by your own Obsidian vault. Daemonless, plain files, no opaque store. **[beta]**
- [causal-memory](https://github.com/JingxuanC/causal-memory/tree/main/hermes-plugin) by [JingxuanC](https://github.com/JingxuanC) — Memory provider with a causal core: flat facts plus typed decision→outcome causal edges (caused / enabled / prevented) on one local SQLite store. Survives compaction structurally — the store lives outside the context window. **[beta]**
- [flowstate-qmd](https://github.com/amanning3390/flowstate-qmd) by [amanning3390](https://github.com/amanning3390) — Anticipatory memory with RAG and vector search. Pre-fetches relevant context before queries hit the agent. **[beta]**
- [hermes-membase](https://github.com/aristoapp/hermes-membase) by [aristoapp](https://github.com/aristoapp) — Persistent memory provider backed by Membase. **[beta]**
- [hindsight](https://github.com/vectorize-io/hindsight) by [Vectorize](https://github.com/vectorize-io) — Long-term memory layer with retain/recall/reflect workflows. Semantic + graph + temporal retrieval. Plugin or MCP. **[production]**
- [honcho-self-hosted](https://github.com/elkimek/honcho-self-hosted) by [elkimek](https://github.com/elkimek) — Self-hosted Honcho memory backend setup for Hermes. Stronger cross-session memory with local control. **[beta]**
- [LWC](https://github.com/JanYork/llm-wiki-cli) by [JanYork](https://github.com/JanYork) — Proactive source-grounded project memory with SQLite/FTS5 recall, optional document and code graphs, plus Hermes-native MCP, skill and `pre_llm_call` hook integration. **[beta]**
- [memory-os](https://github.com/ClaudioDrews/memory-os) by [ClaudioDrews](https://github.com/ClaudioDrews) — Seven-layer memory system with Qdrant, structured facts, fabric recall and auto-curation. The most opinionated provider here. **[production]**
- [Open Index](https://github.com/DrDroidLab/open-index) by [DrDroidLab](https://github.com/DrDroidLab) — Structured context graphs with hybrid search, read/write MCP access, and a portable setup skill for Hermes. **[beta]**
- [personal-api](https://github.com/beiyuii/personal-api-skill) by [beiyuii](https://github.com/beiyuii) — Turn your Obsidian vault into an identity layer any AI agent can read in under 30 seconds. **[experimental]**
- [plur](https://github.com/plur-ai/plur) by [plur-ai](https://github.com/plur-ai) — Shared memory layer for AI agents with open engram format (YAML). Persistent learning patterns. **[beta]**
- [remnic](https://github.com/joshuaswarren/remnic) by [joshuaswarren](https://github.com/joshuaswarren) — Scoped memory with provenance, retrieval-quality evals, correction and boundaries. Built for user-aware agents. **[beta]**
- [scope-recall-hermes](https://github.com/410979729/scope-recall-hermes) by [410979729](https://github.com/410979729) — Scope-aware recall over SQLite truth plus LanceDB semantic search, with hybrid retrieval. **[beta]**
- [yantrikdb-hermes-plugin](https://github.com/yantrikos/yantrikdb-hermes-plugin) by [yantrikos](https://github.com/yantrikos) — Hermes-native memory provider for YantrikDB. `think()` canonicalizes duplicates, `conflicts()` surfaces contradictions, every `recall()` carries `why_retrieved` reasons. **[beta]**
- [zeromem](https://github.com/ptaranat/zeromem) by [ptaranat](https://github.com/ptaranat) — Rust implementation of Zero-Mem (arXiv:2607.29377). Zero-token memory — no context tax on every turn. **[experimental]**
- [zettelkasten-second-memory](https://github.com/cx2002302-lang/zettelkasten-second-memory) by [cx2002302-lang](https://github.com/cx2002302-lang) — Turns conversations into a permanent Zettelkasten knowledge base. Also runs on OpenClaw. **[beta]**

---

## 🔗 Surfaces & Integrations

> Where Hermes actually meets you — clients, dashboards, chat platforms and devices that talk to a running Hermes gateway.

- [adebnar/hermes-android](https://github.com/adebnar/hermes-android) by [adebnar](https://github.com/adebnar) — Native Android client for the gateway: chat plus sessions, models, cron and usage over Tailscale. **[beta]**
- [Hermes AI Usage Monitor](https://github.com/masterlf/hermes-ai-usage) by [masterlf](https://github.com/masterlf) — Read-only provider quota and per-profile token telemetry for Hermes Desktop and Web Dashboard, with cache-aware history and no prompt-content collection. **[beta]**
- [hermes-dashboard](https://github.com/chrisryugj/hermes-dashboard) by [chrisryugj](https://github.com/chrisryugj) — Web dashboard for gateway config, MCP, cron and model management without touching the CLI. **[beta]**
- [hermes-desktop-avatar](https://github.com/erenciracioglu-dotcom/hermes-desktop-avatar) by [erenciracioglu-dotcom](https://github.com/erenciracioglu-dotcom) — Always-on-top desktop sprite that fronts a local gateway. PySide6, OpenAI-compatible HTTP. **[experimental]**
- [hermes-live-discord-agent-plugin](https://github.com/Capslockb/hermes-live-discord-agent-plugin) by [Capslockb](https://github.com/Capslockb) — Full-duplex Discord voice with function calling and idle hangup. **[beta]**
- [hermes-multitenancy](https://github.com/eggyrooch-blip/hermes-multitenancy) by [eggyrooch-blip](https://github.com/eggyrooch-blip) — One Feishu bot, N users, N profiles. Multi-tenant routing for a shared gateway. **[beta]**
- [hermes-notebook](https://github.com/lEWFkRAD/hermes-agents-guide-to-the-galaxy) by [lEWFkRAD](https://github.com/lEWFkRAD) — Handwriting-first clients for Kindle Scribe, BOOX and Android stylus devices, with Live Pages. **[beta]**
- [hermes-studio](https://github.com/EKKOLearnAI/hermes-studio) by [EKKOLearnAI](https://github.com/EKKOLearnAI) — Web dashboard for multi-platform chat, session management, scheduled jobs and usage analytics. **[production]**
- [hermes-zalo-plugin](https://github.com/cuongdev/hermes-zalo-plugin) by [cuongdev](https://github.com/cuongdev) — Connects a personal Zalo account to the gateway via zca-js. macOS, Linux and Windows. **[beta]**
- [meshtastic-plugin](https://github.com/merchantmy/meshtastic-plugin) by [merchantmy](https://github.com/merchantmy) — Meshtastic LoRa radio as a first-class messaging platform. Your agent, off-grid. **[experimental]**
- [nesquena/hermes-webui](https://github.com/nesquena/hermes-webui) by [nesquena](https://github.com/nesquena) — The most-starred way to drive Hermes from a browser or a phone. **[production]**
- [screenpipe](https://github.com/screenpipe/screenpipe) by [screenpipe](https://github.com/screenpipe) — Records your screen continuously and feeds it to Hermes and 100+ other agents. Local and private. **[production]**

---

## 🛠️ Tools, Workspaces & GUIs

> Apps and dashboards built on top of or alongside Hermes. Not skills — but they make skills easier to use.

- [hermes-desktop](https://github.com/dodo-reach/hermes-desktop) by [dodo-reach](https://github.com/dodo-reach) — Native macOS workspace with direct host-first SSH. Real terminal, session browsing, file editing. **[beta]**
- [hermes-ui](https://github.com/pyrate-llama/hermes-ui) by [pyrate-llama](https://github.com/pyrate-llama) — Single-file glassmorphic web UI with SSE streaming, tool call visualization, PDF export, session/skill/memory viewers. **[beta]**
- [hermes-webui](https://github.com/sanchomuzax/hermes-webui) by [sanchomuzax](https://github.com/sanchomuzax) — Lightweight process monitoring and config dashboard. Simpler ops alternative. **[beta]**
- [hermes-workspace](https://github.com/outsourc-e/hermes-workspace) by [outsourc-e](https://github.com/outsourc-e) — Web-based workspace: chat, terminal, memory browser, skills manager, inspector. Most complete GUI for Hermes. 6.5k★. **[production]**
- [mission-control](https://github.com/builderz-labs/mission-control) by [builderz-labs](https://github.com/builderz-labs) — Open-source dashboard for AI agent orchestration. Multi-agent fleets, task dispatch, cost tracking. 6.1k★. **[production]**
- [orahermes-agent](https://github.com/jasperan/orahermes-agent) by [jasperan](https://github.com/jasperan) — Oracle AI Agent Harness — OCI GenAI and Oracle 26ai integration. **[experimental]**
- [portable-hermes-agent](https://github.com/aivrar/portable-hermes-agent) by [aivrar](https://github.com/aivrar) — Windows desktop app bundling 100 tools, GUI, local models, ComfyUI in a portable package. **[beta]**

---

## 🔄 Skills → Plugins

> The **[Agent Plugins](https://agent-plugins.org)** standard (spec v1.0.0, published 2026-08-06 by Amazon, Anysphere/Cursor, GitHub, Microsoft, OpenAI and Vercel, with Google as a core maintainer) bundles Agent Skills *and* MCP servers into one portable folder. If you already ship a `SKILL.md`, you are most of the way there.

A plugin is a directory:

```
my-plugin/
├── plugin.json          # $schema + name required; version, description, license, author, repository
├── skills/<skill>/SKILL.md
├── mcp.json             # mcpServers: stdio | streamable-http | sse
└── com.vendor.client/   # namespaced client extensions
```

Runtime variables `${PLUGIN_ROOT}` and `${PLUGIN_DATA}` resolve at load time. Path containment is enforced, `command` does no shell interpolation, and credentials must not be embedded — read the spec before you publish.

**Why it matters for this list:** the artifact churns, the ecosystem doesn't. A skill you wrote for Hermes runs unchanged inside a plugin, and that plugin also loads in ChatGPT, Codex, Cursor, GitHub Copilot, Kiro and VS Code. Several entries here already ship both shapes — look for a `.claude-plugin/` directory or a `plugin.json` next to the `skills/` folder.

**Converting an existing skill:**

- [Agent Plugins spec](https://github.com/agentplugins/agent-plugins-spec) — the normative source. Schemas at [agent-plugins.org/schemas](https://agent-plugins.org/schemas).
- [awesome-agent-plugins](https://github.com/ZeroPointRepo/awesome-agent-plugins): our sister list of plugins that already ship a real 1.0.0 `plugin.json`. Useful as worked examples before you write your own, and it tracks which clients actually load them.
- [claude-plugin-converter](https://github.com/moonlight-lupin/agent-skills/tree/main/agent-ops/claude-plugin-converter) by [moonlight-lupin](https://github.com/moonlight-lupin) — analyses a Claude Code plugin and emits an installable Hermes plugin. The closest thing to a one-command migration today. **[beta]**

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
- [hermes-ai-team](https://github.com/smfworks/hermes-ai-team) by [smfworks](https://github.com/smfworks) — Phase-by-phase guide to building a team of Hermes agents: SOUL, memory, vault, nightly research, kanban and a chief of staff. Written to be read by the agent, not just about it. 55★. **[production]**
- [hermes-agent-docs](https://github.com/mudrii/hermes-agent-docs) by [mudrii](https://github.com/mudrii) — Comprehensive community documentation. Useful supplement for deployment patterns. **[beta]**
- [hermes-wsl-ubuntu](https://github.com/metantonio/hermes-wsl-ubuntu) by [metantonio](https://github.com/metantonio) — End-to-end WSL2 + llama.cpp + Qwen3.5 setup with CUDA/Metal acceleration for running Hermes on Windows. **[production]**
- **[Discord](https://discord.gg/NousResearch)** — Bug reports, feature requests, general discussion.

---

## 🔗 Related Lists

Sister lists, same standard, same maintainer. Each one covers a different agent ecosystem.

- [awesome-agent-plugins](https://github.com/ZeroPointRepo/awesome-agent-plugins): plugins on the open Agent Plugins standard, every entry checked for a real `plugin.json`.
- [awesome-grok-bot](https://github.com/ZeroPointRepo/awesome-grok-bot): skills, plugins and MCP wiring for xAI and Cursor's Grok Bot.
- [awesome-dsh-plugins](https://github.com/ZeroPointRepo/awesome-dsh-plugins): DeepSeek Harness plugins organized by what they do, every install command re-checked weekly by CI.
- [awesome-cursor-plugins](https://github.com/ZeroPointRepo/awesome-cursor-plugins): Cursor plugins from the official marketplace, each with the other agents it also runs in and whether it needs a sign-in.
- [awesome-fx-skills](https://github.com/ZeroPointRepo/awesome-fx-skills): skills, MCP servers and subagents for Vercel's fx coding agent, every install command machine-checked weekly.

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

PRs welcome, and they get read. We accept entries that:

1. **Resolve** — the link works and points at something public
2. **Have substance** — a real `SKILL.md` / `plugin.json` / provider implementation, plus a README that explains it
3. **Are maintained** — a commit in the last six months
4. **Aren't already listed** — search the page first

If your formatting is slightly off we will fix it and merge, rather than bounce it. We only close for dead links, no substance, spam, or duplicates — and we will tell you which, and invite you back once it's fixed.

Entry format:

```
- [name](repo-url) by [author](author-url) — one-line description. **[tag]**
```

Full rules and a copy-paste example: **[CONTRIBUTING.md](CONTRIBUTING.md)**.

---

## 📰 Stay in the Loop

- **[@therohitdas](https://twitter.com/therohitdas)** — New additions and catalog updates
- **GitHub Stars** — Star this repo to keep it visible
- **[Hermes Discord](https://discord.gg/NousResearch)** — Talk shop with other Hermes users

---

<div align="center">

**Built and maintained by [ZeroPointRepo](https://github.com/ZeroPointRepo).**

We ship [youtube-skills](https://github.com/ZeroPointRepo/youtube-skills), powered by [TranscriptAPI](https://transcriptapi.com) — 15M+ transcripts/month, 99.9% uptime.

[TranscriptAPI](https://transcriptapi.com) · [@therohitdas](https://twitter.com/therohitdas) · [Issues & Suggestions](https://github.com/ZeroPointRepo/awesome-hermes-skills/issues)

Built with [crhq.ai](https://crhq.ai)

*This is an unofficial, community-maintained list. It is not affiliated with or endorsed by Nous Research
or the Hermes Agent project.*

</div>

## License

[![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This list is licensed under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/). Each linked resource has its own license.
