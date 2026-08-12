# Contributing

Thanks for adding something. This list is maintained by hand and every PR gets a human reply — merged or not.

## The bar

We merge an entry when all four are true:

1. **The link resolves.** Public, not 404, not a private repo, not a redirect to a dead org.
2. **There's something behind it.** A real `SKILL.md`, `plugin.json`, memory-provider implementation, or working client — plus a README that explains what it does. A repo containing only a title is not an entry.
3. **It's maintained.** A commit in the last six months. If it's older but still correct, say so in the PR and we'll usually take it.
4. **It isn't already here.** Search the page first. Ctrl-F the repo name.

We close for exactly four reasons: dead link, no substance, spam, duplicate. You'll get told which one, and you're welcome back the moment it's fixed.

**We do not bounce PRs over formatting.** If your entry is in the wrong alphabetical slot, or the dash is wrong, or the tag is missing, we'll fix it and merge. Don't let a comma stop you opening the PR.

## Entry format

One line, exactly this shape:

```
- [name](repo-url) by [author](author-url) — one-line description. **[tag]**
```

- **`name`** — what the thing is called. Use the skill or plugin name, not the repo slug, unless they're the same. If two entries would collide, prefix yours with the owner (`owner/name`).
- **`repo-url`** — link as deep as is useful. If your repo holds twenty skills and you're listing one, link the skill directory.
- **`author-url`** — your GitHub profile or org. A product homepage is fine only if there's no GitHub presence at all.
- **`—`** — an em dash, with a space each side.
- **description** — one line. What it does and why someone would install it. Present tense, no marketing. It will be trimmed if it reads like a landing page.
- **`tag`** — one of the four below, in bold square brackets, at the end.

### Tags

| Tag | Means |
|---|---|
| `production` | Stable, documented, actively maintained. Safe to build on. |
| `beta` | Works, still moving. Expect rough edges. |
| `experimental` | Proof of concept. Fun, don't depend on it. |
| `built-in` | Ships with Hermes. Reserved for the bundled catalogs. |

Tag honestly. We adjust tags that don't match what's in the repo, and we'll say so in the PR.

### Copy-paste example

```markdown
- [lintlang](https://github.com/hermes-labs-ai/lintlang) by [Hermes Labs](https://github.com/hermes-labs-ai) — Zero-LLM static analysis for agent configs, tool descriptions and system prompts. Catches vague tool descriptions and missing stop conditions in CI. **[beta]**
```

## Where it goes

Add your entry to the right section, **alphabetically by display name**, case-insensitive.

**Community Skills** — things that install as a `SKILL.md`:

| Section | For |
|---|---|
| 📺 Media & Transcripts | Video, audio, transcripts, podcasts |
| 🔍 Search & Research | Web search, papers, deep research, model comparison |
| 📈 Marketing & Growth | SEO, GEO, ads, content, growth workflows |
| 💻 Dev & Skill Authoring | Coding workflows, skill builders, linters, dev tooling |
| 🌐 Browser & Web | Browser control, scraping, rendering |
| ✉️ Communication & Social | Email, chat platforms, social posting |
| 📊 Productivity & Tasks | Planning, notes, task management, analytics |
| 🎨 Creative & Media Generation | Image, video, audio, design |
| 🔧 DevOps & Deployment | Containers, packaging, CI, workflow runners |
| 💰 Finance, Payments & Crypto | Payments, x402, on-chain, accounting |
| 🤖 Multi-Agent & Swarms | Delegation, orchestration, agent-to-agent |
| 🏠 Smart Home, IoT & Embodied | Devices, robots, game worlds |
| 🔐 Security & Detection | Pentest, detection, sandboxing, trust boundaries |
| 🎯 Domain & Novelty | Everything that doesn't fit above |

**Other top-level sections:**

| Section | For |
|---|---|
| 🔌 Plugins | Packages that add tools, commands, hooks or providers to the agent itself |
| 🧠 Agent Profiles | Persona + memory + curated bundle, installed with `hermes profile install` |
| 💾 Memory Providers | Swap-in backends for the memory layer |
| 🔗 Surfaces & Integrations | Clients, dashboards, chat platforms and devices that talk to a gateway |
| 🛠️ Tools, Workspaces & GUIs | Apps built alongside Hermes rather than inside it |
| 📚 Skill Registries & Discovery | Places to find more skills |
| 📖 Guides & Documentation | Docs, tutorials, setup writeups |

Not sure which? Pick the closest one and say so in the PR. Putting it in the wrong section is not a reason to close.

## Submitting

1. Fork, branch, add your one line.
2. Open a PR. The template asks five yes/no questions — answering them honestly is the fastest way to get merged.
3. One logical addition per PR where you can. Three skills from the same author in one PR is fine; we'll review them independently and may merge some and not others.

## Reporting a broken entry

Open an issue with the [report-broken](../../issues/new?template=report-broken.yml) template, or just say which line is dead. A weekly job sweeps for dead links, but it doesn't catch repos that went empty or abandoned.

## A note on our own entries

The maintainers build some of the tools listed here — `youtube-skills` (powered by [TranscriptAPI](https://transcriptapi.com)) and `zillow-skills` (powered by Zillapi) are ours. We say so plainly, and we hold them to rules that are stricter than the ones above, not looser:

- **Never more than one of our entries per section.**
- **Same format, no decoration.** They sit in the same alphabetical order, next to their direct competitors, with no bold, badge, or "featured" marker.
- **A competitor's entry is never rejected to protect ours.** If a better alternative to something we build shows up, it goes in — next to ours.
- **The list has to be useful with every one of our entries deleted.** That's the test we apply.

If you think we've broken one of those, open an issue and say so. We'd rather fix it than argue about it.

## Licence

This list is [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). By contributing you agree your entry is published under it. Each linked project keeps its own licence.
