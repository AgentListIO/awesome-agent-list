# Awesome Agent List

> A maintained list of AI agents — coding agents, digital employees, ops agents, computer-use agents, research agents, voice agents, and the routers/protocols behind them — each normalized to the same spec fields at [agentlist.io](https://agentlist.io).

81 systems · 66 vendors · 13 categories — verified 2026-09-24. Every entry links its full spec sheet.

## Contents

- [AI IDEs](#ai-ides) (6)
- [IDE extensions & copilots](#ide-extensions--copilots) (8)
- [CLI & terminal agents](#cli--terminal-agents) (15)
- [Cloud & autonomous agents](#cloud--autonomous-agents) (5)
- [Model routers & gateways](#model-routers--gateways) (2)
- [Bridges, brokers & protocols](#bridges-brokers--protocols) (3)
- [Personal & always-on agents](#personal--always-on-agents) (6)
- [AI employees & digital coworkers](#ai-employees--digital-coworkers) (10)
- [On-call & ops agents](#on-call--ops-agents) (7)
- [Browser & computer-use agents](#browser--computer-use-agents) (6)
- [Research & analyst agents](#research--analyst-agents) (7)
- [Voice & phone agents](#voice--phone-agents) (6)
- [Contributing](#contributing)

## AI IDEs

*Editors where the agent is the product surface.* — An AI IDE is a forked or purpose-built code editor whose primary interface is an AI agent: repo-aware chat, multi-file edits, and agent modes are first-class, not a plugin. Most are VS Code forks; some are native editors that add agent panels.

- [Cursor](https://cursor.com) — A VS Code–based AI-native editor with repo-aware chat, multi-file edits, Composer/agent modes, and cloud background agents. · [spec](https://agentlist.io/systems/cursor)
- [Google Antigravity](https://ai.google) — Google's agent-first IDE and CLI, the successor surface to Gemini Code Assist for individuals and Gemini CLI. · [spec](https://agentlist.io/systems/antigravity)
- [Kiro](https://aws.amazon.com) — AWS's agent-first IDE: spec-driven development (requirements → design → tasks), agent hooks, and an Auto agent, with a CLI. · [spec](https://agentlist.io/systems/kiro)
- [Trae](https://www.trae.ai) — ByteDance's AI-native VS Code fork with Builder chat and SOLO, an autonomous mode that plans and builds whole apps from a brief. · [spec](https://agentlist.io/systems/trae)
- [Windsurf / Devin Desktop](https://cognition.ai) — Cognition's AI IDE (ex-Codeium) built around Cascade multi-step agent flows, sold on the same Free / Pro / Max / Teams sheet as Devin. · [spec](https://agentlist.io/systems/windsurf)
- [Zed](https://zed.dev) — A fast native editor (Rust, GPU-rendered) with a built-in agent panel, edit predictions, and hosted or BYOK models. · [spec](https://agentlist.io/systems/zed)

## IDE extensions & copilots

*Agents that live inside the editor you already run.* — IDE extensions add completion, chat, and agent modes to an existing editor — VS Code, JetBrains, Neovim — through the editor's plugin system. They range from vendor copilots to open-source, bring-your-own-key agents.

- [Amazon Q Developer](https://aws.amazon.com) — Amazon Q Developer (formerly CodeWhisperer) is AWS's coding assistant with IDE and CLI agents plus Java/.NET transformation. · [spec](https://agentlist.io/systems/amazon-q-developer)
- [Augment Code](https://www.augmentcode.com) — A context-engine coding agent for large codebases, available in VS Code, JetBrains, and a CLI (Auggie), priced as one flat team plan. · [spec](https://agentlist.io/systems/augment)
- [Cline](https://cline.bot/pricing) — An open-source VS Code agent that plans, edits, and runs tools with BYOK models and approval controls. · [spec](https://agentlist.io/systems/cline)
- [Gemini Code Assist](https://ai.google) — Google's per-seat coding assistant for IDEs and Google Cloud workflows, now sold only as Standard and Enterprise. **(caution)** · [spec](https://agentlist.io/systems/gemini-code-assist)
- [GitHub Copilot](https://github.com) — The GitHub-native coding assistant: completions, chat, agent mode, and PR coding agents across many IDEs. · [spec](https://agentlist.io/systems/copilot)
- [Junie](https://www.jetbrains.com) — JetBrains' coding agent — inside JetBrains IDEs (Junie Local in AI Chat) and as a terminal CLI. · [spec](https://agentlist.io/systems/junie)
- [Kilo Code](https://kilo.ai) — An open-source agentic platform — VS Code/JetBrains extension, CLI, Slack, and cloud agents over a shared OpenCode engine. · [spec](https://agentlist.io/systems/kilo-code)
- [Sourcegraph Cody](https://sourcegraph.com) — A codebase-aware assistant powered by Sourcegraph's code graph, now enterprise-focused. **(caution)** · [spec](https://agentlist.io/systems/cody)

## CLI & terminal agents

*Terminal-native agents that edit repos, run commands, and commit.* — CLI agents run in the shell against a local checkout. They read the repository, plan changes, edit files, execute commands and tests, and often commit — usually with tool protocols like MCP for extension.

- [Aider](https://aider.chat) — An open-source, git-native pair programmer: it maps the repo, proposes commits, and works with any model via BYOK or OpenRouter. **(caution)** · [spec](https://agentlist.io/systems/aider)
- [Amp](https://ampcode.com) — A terminal-first, multi-model coding agent with subagents, an Oracle second-opinion model, threads, and MCP plugins. · [spec](https://agentlist.io/systems/amp)
- [Claude Code](https://www.anthropic.com) — Anthropic's terminal-native coding agent: it plans, edits, runs commands, uses git and MCP, and sustains long agentic loops. · [spec](https://agentlist.io/systems/claude-code)
- [Codex CLI](https://openai.com) — OpenAI's coding agent: an open-source terminal CLI, a desktop app, IDE extensions, and a cloud lane for async tasks, all included in ChatGPT plans. · [spec](https://agentlist.io/systems/codex-cli)
- [Crush](https://charm.land) — Charm's open-source terminal coding agent — multi-model sessions that can switch providers mid-session, LSP-enhanced context, MCP support, and a polished TUI on every major platform. · [spec](https://agentlist.io/systems/crush)
- [Gemini CLI](https://ai.google) — Google's open-source terminal agent; on June 18, 2026 it stopped serving free and Google AI Pro/Ultra accounts in favor of the Antigravity CLI. **(caution)** · [spec](https://agentlist.io/systems/gemini-cli)
- [Goose](https://block.xyz) — Block's local-first agent runtime with many model providers and extensible tool plugins. · [spec](https://agentlist.io/systems/goose)
- [Grok Build](https://x.ai) — XAI's terminal coding agent — a full-screen, mouse-interactive TUI (open-source Rust) powered by Grok 4.6, with skills, subagents in git worktrees, headless mode, and ACP embedding for editors. · [spec](https://agentlist.io/systems/grok-build)
- [Kimi Code](https://www.moonshot.ai) — Moonshot AI's single-binary terminal agent — tuned TUI, subagents, conversational MCP setup, lifecycle hooks, and ACP for Zed/JetBrains. · [spec](https://agentlist.io/systems/kimi-code)
- [Mistral Vibe](https://mistral.ai) — Mistral's open-source CLI coding agent powered by Devstral 2 — terminal-native multi-file automation with IDE extensions for VS Code, JetBrains, and Zed over ACP. · [spec](https://agentlist.io/systems/mistral-vibe)
- [Muse Code](https://dev.meta.ai) — Meta's terminal coding agent powered by Muse Spark 1.2 — persistent background subagents, a replay-exact event log, workflow orchestration, and a TypeScript SDK over the Muse Session Protocol. · [spec](https://agentlist.io/systems/muse-code)
- [OpenCode](https://opencode.ai/docs/zen/) — An MIT-licensed open-source terminal coding agent that is fully BYOK, with optional hosted model access via Zen and Go. · [spec](https://agentlist.io/systems/opencode)
- [OpenHands](https://www.openhands.dev/pricing) — OpenHands (formerly OpenDevin) is an open-source software engineering agent you can self-host, using LiteLLM or OpenRouter for models. · [spec](https://agentlist.io/systems/openhands)
- [Qwen Code](https://www.alibabacloud.com) — Alibaba's open-source terminal agent — adapted from Gemini CLI and tuned for Qwen3-Coder — with subagents, agent teams, auto-memory and auto-skills, IDE plugins, a desktop app, daemon mode, and SDKs. · [spec](https://agentlist.io/systems/qwen-code)
- [Warp](https://www.warp.dev) — A terminal that ships its own coding agent (Warp Agent / Oz) with plan-bundled credits, so the shell itself runs agentic tasks. · [spec](https://agentlist.io/systems/warp)

## Cloud & autonomous agents

*Ticket-in, PR-out workers running outside your editor.* — Cloud agents run in a vendor-hosted sandbox rather than on your machine. You hand them a task — an issue, a ticket, a prompt — and they return a pull request or a deployed change for human review.

- [Devin](https://cognition.ai) — Cognition's autonomous software engineer: cloud sandboxes for ticket-in / PR-out work, plus Devin Desktop and CLI on the same plan as Windsurf. · [spec](https://agentlist.io/systems/devin)
- [Factory Droids](https://factory.ai) — Enterprise agent fleets for code, review, docs, tests, and knowledge, run via CLI, desktop, or cloud Missions. · [spec](https://agentlist.io/systems/droid)
- [Jules](https://ai.google) — Google's async issue-to-PR coding agent, running tasks in the cloud from a GitHub issue handoff. · [spec](https://agentlist.io/systems/jules)
- [Replit Agent](https://replit.com) — Replit Agent builds full-stack apps in the browser on Replit's hosted runtime. · [spec](https://agentlist.io/systems/replit-agent)
- [Roomote](https://roomote.dev) — The Roo Code team's single-tenant cloud coding agent: your own hosted or self-hosted instance that runs tasks against your repos. · [spec](https://agentlist.io/systems/roomote)

## Model routers & gateways

*One API in front of many LLM providers.* — Model routers expose a single, usually OpenAI-compatible API and route requests across providers with fallbacks, spend controls, and usage billing. Most BYOK coding agents can point at one.

- [LiteLLM](https://www.litellm.ai/pricing) — A self-hostable proxy that normalizes hundreds of LLM APIs behind an OpenAI-compatible endpoint. · [spec](https://agentlist.io/systems/litellm)
- [OpenRouter](https://openrouter.ai) — A single API to many LLM providers with routing, fallbacks, and usage billing — widely wired into Aider, Continue, Goose, and OpenHands. · [spec](https://agentlist.io/systems/openrouter)

## Bridges, brokers & protocols

*Connective tissue: tool protocols, inter-agent messaging, transports.* — Bridges connect agents to tools, data, and each other. This covers tool protocols (MCP), inter-agent messaging standards and brokers, and transport bindings that attach chat or voice channels to an agent runtime.

- [Instinct](https://github.com/WRG-11/instinct) — A self-learning memory MCP server for coding agents — it observes repeated patterns, scores them by confidence, and promotes mature ones into suggestions it exports back to Claude Code, Cursor, Windsurf, Codex, and CLAUDE.md. · [spec](https://agentlist.io/systems/instinct)
- [Model Context Protocol](https://modelcontextprotocol.io) — An open protocol for connecting agents and IDEs to tools and data sources through MCP servers. · [spec](https://agentlist.io/systems/mcp)
- [OpenScout / Scout](https://openscout.app) — A local-first broker that lets addressable agents (Claude Code, Codex, Cursor) send and ask across harnesses on one mesh. · [spec](https://agentlist.io/systems/scout)

## Personal & always-on agents

*Self-hosted assistants that live in your chat apps, not your editor.* — Personal agents are self-hosted assistant runtimes: one gateway or process that holds sessions, memory, tools, and skills, and meets you in the channels you already use — Telegram, WhatsApp, Discord, Slack, Signal, iMessage — alongside CLIs, TUIs, and web dashboards. They run on your hardware or your VPS, keep state on your machine, and delegate to repo-native coding agents when the task is code.

- [Hermes Agent](https://nousresearch.com) — Nous Research's self-improving assistant — a closed learning loop creates skills from experience and refines them in use, with agent-curated memory, periodic nudges, FTS5 session search, and Honcho user modeling. · [spec](https://agentlist.io/systems/hermes-agent)
- [nanobot](https://github.com/HKUDS) — HKUDS's Python answer to OpenClaw — a compact, MCP-native assistant codebase you can audit in an afternoon, popular as a learning platform and a base for custom assistants. · [spec](https://agentlist.io/systems/nanobot)
- [NanoClaw](https://github.com/qwibitai/nanoclaw) — A TypeScript OpenClaw fork built for isolation — each agent runs in its own container, with Agent Swarms for multi-agent collaboration — the security-first direct replacement for the original gateway. · [spec](https://agentlist.io/systems/nanoclaw)
- [OpenClaw](https://openclaw.ai) — The category-defining self-hosted assistant: one Gateway on your own hardware connects ~29 chat channels (WhatsApp, Telegram, Signal, iMessage, Slack, Discord…) to an agent with memory, skills, sessions, and multi-agent routing — stewarded by an independent 501(c)(3). · [spec](https://agentlist.io/systems/openclaw)
- [PicoClaw](https://sipeed.com) — Sipeed's Go rewrite for embedded — one binary that cold-starts in under a second inside ~10MB of RAM on single-board computers; roughly 95% of its core was written by an AI agent. · [spec](https://agentlist.io/systems/picoclaw)
- [ZeroClaw](https://github.com/zeroclaw-labs/zeroclaw) — A Rust rewrite of the personal-agent shape — a single binary under ~5MB RAM that talks to ~20 model providers and 30+ channels, with supervised-by-default autonomy, OS-level sandboxes, signed tool receipts, and GPIO/I2C/SPI for real hardware. · [spec](https://agentlist.io/systems/zeroclaw)

## AI employees & digital coworkers

*Agents hired for a role, not opened like a tool.* — AI employees are agents packaged as a job function — an SDR that prospects, a support rep that resolves tickets, a recruiter that screens candidates. They arrive with an identity, a role, and integrations into the systems that role touches (CRM, helpdesk, ATS, email, phone), and they're sold on seats or outcomes rather than editor features.

- [Alice](https://www.11x.ai) — 11x's AI SDR: she researches accounts, writes outbound sequences across email and LinkedIn, and books meetings — with sibling agent Julian handling inbound phone calls. · [spec](https://agentlist.io/systems/alice)
- [Ava](https://www.artisan.co) — Artisan's AI BDR: she mines a large contact database, personalizes outbound at scale, and manages replies through to booked meetings. · [spec](https://agentlist.io/systems/ava)
- [Decagon](https://decagon.ai) — Decagon builds autonomous customer-support agents that resolve chats, emails, and calls for mid-market and enterprise brands, with engineering-grade tooling for the ops team behind them. · [spec](https://agentlist.io/systems/decagon)
- [Fin](https://www.intercom.com) — Intercom's AI support agent: it answers customer questions from your help content, resolves conversations end-to-end, and charges only when it resolves. · [spec](https://agentlist.io/systems/fin)
- [Harvey](https://www.harvey.ai) — The AI associate for legal work: drafting, review, diligence, and research grounded in legal corpora, deployed inside law firms and enterprise legal departments. · [spec](https://agentlist.io/systems/harvey)
- [Juicebox (PeopleGPT)](https://juicebox.ai) — The recruiting AI employee: it searches candidate pools in natural language, runs outbound outreach, and ranks talent against your rubric. · [spec](https://agentlist.io/systems/juicebox)
- [Lindy](https://www.lindy.ai) — The build-your-own-employee platform: no-code agents that handle email triage, scheduling, meeting notes, CRM updates, and custom back-office workflows. · [spec](https://agentlist.io/systems/lindy)
- [Mercor](https://mercor.com) — The AI interviewer and talent marketplace: its agent screens candidates in structured video interviews and matches them to roles — and increasingly to AI-training gigs. · [spec](https://agentlist.io/systems/mercor)
- [Piper](https://www.qualified.com) — Qualified's inbound AI SDR: she greets and qualifies website visitors in chat, works target accounts, and routes or books meetings against your CRM. · [spec](https://agentlist.io/systems/piper)
- [Sierra](https://sierra.ai) — The customer-service AI employee for large consumer brands: it resolves support conversations across chat and voice, takes actions in business systems, and bills on outcomes. · [spec](https://agentlist.io/systems/sierra)

## On-call & ops agents

*Agents that hold the pager — triage, investigate, resolve.* — Ops agents sit inside the incident and security loop: they watch alerts, correlate telemetry, investigate pages, draft root-cause analyses, and propose or apply remediations. AI SREs handle production incidents; AI SOC analysts (Dropzone, Simbian) handle security queues.

- [Bits AI](https://www.datadoghq.com) — Datadog's in-platform agent: it answers observability questions in natural language, investigates anomalies, and drafts incident summaries against the telemetry you already pay Datadog for. · [spec](https://agentlist.io/systems/bits-ai)
- [Cleric](https://www.cleric.io) — A dedicated AI SRE: it investigates production alerts across logs, metrics, deploys, and code history, then hands on-call engineers a root-cause hypothesis with evidence. · [spec](https://agentlist.io/systems/cleric)
- [Dropzone AI](https://www.dropzone.ai) — The AI SOC analyst: it investigates every alert end-to-end — triage, evidence gathering, verdict — so human analysts only see the ones that matter. · [spec](https://agentlist.io/systems/dropzone)
- [incident.io](https://incident.io) — The incident-management platform whose AI assistant drafts timelines, summarizes channels, surfaces similar past incidents, and nudges responders — inside the tool that already runs your incidents. · [spec](https://agentlist.io/systems/incident-io)
- [Resolve](https://resolve.ai) — Resolve (resolve.ai) is an AI SRE from ex-Splunk/Observability leadership: it triages alerts, investigates incidents across your stack, and drafts remediations for approval. · [spec](https://agentlist.io/systems/resolve)
- [Rootly](https://rootly.com) — The incident-response platform with AI woven through it: auto-drafted summaries, suggested next steps, retrospectives, and noise reduction on the alert stream. · [spec](https://agentlist.io/systems/rootly)
- [Simbian](https://www.simbian.ai) — Simbian builds autonomous SOC agents that hunt, investigate, and respond across the security stack, plus GRC automation — aimed at teams running lean against enterprise-scale alert volume. · [spec](https://agentlist.io/systems/simbian)

## Browser & computer-use agents

*Agents that drive a GUI — clicks, forms, and logins, not commits.* — Computer-use agents operate software through its interface — a browser, a desktop, a remote session — by reading the screen or DOM and acting with clicks, keystrokes, and navigation. Some are hosted products that take a goal and return a result (ChatGPT Agent, Manus); others are open frameworks and APIs for building your own (Browser Use, Skyvern, Stagehand, Claude Computer Use).

- [Browser Use](https://browser-use.com) — The breakout open-source framework for browser agents: connect an LLM to a controllable browser, describe a task, and let it click, type, and navigate to completion — self-hosted or via Browser Use Cloud. · [spec](https://agentlist.io/systems/browser-use)
- [ChatGPT Agent](https://openai.com) — OpenAI's hosted computer-use mode — the Operator lineage: it spins up a managed browser, works through multi-step web tasks, and can take actions after confirmation. · [spec](https://agentlist.io/systems/chatgpt-agent)
- [Claude Computer Use](https://www.anthropic.com) — Anthropic's API capability: Claude reads screenshots and emits mouse/keyboard actions, letting developers build agents that operate desktops and browsers in their own sandboxes. · [spec](https://agentlist.io/systems/claude-computer-use)
- [Manus](https://manus.im) — The hosted general agent: give it a goal in chat and it works a cloud session — browsing, running code, building artifacts — returning finished deliverables rather than suggestions. · [spec](https://agentlist.io/systems/manus)
- [Skyvern](https://www.skyvern.com) — An open-source browser-automation agent that uses LLMs plus computer vision to operate websites it's never seen — no brittle per-site selectors. · [spec](https://agentlist.io/systems/skyvern)
- [Stagehand](https://www.browserbase.com) — Browserbase's open-source agent framework: act/extract/observe primitives over a controllable browser, mixing deterministic Playwright code with LLM-driven steps. · [spec](https://agentlist.io/systems/stagehand)

## Research & analyst agents

*Prompt in, cited report out.* — Research agents take a question and return a structured, cited report — searching, reading, and synthesizing dozens of sources over minutes-long runs. Consumer 'deep research' modes live inside chat products (ChatGPT, Gemini, Perplexity); enterprise analysts work over licensed or internal corpora (Hebbia, AlphaSense); academic tools ground in the literature (Elicit).

- [AlphaSense](https://www.alpha-sense.com) — The institutional market-intelligence platform whose Deep Research agents search premium content — broker research, filings, transcripts, expert calls — and return decision-grade cited reports. · [spec](https://agentlist.io/systems/alphasense)
- [ChatGPT Deep Research](https://openai.com) — OpenAI's research-agent mode: a prompt becomes a 5–30 minute browsing run that returns a cited report — now also reachable via API as a deep-research model. · [spec](https://agentlist.io/systems/deep-research)
- [Elicit](https://elicit.com) — The research agent for scientific literature: it searches 125M+ papers, extracts methods and findings into structured tables, and drafts systematic-review-grade summaries with citations. · [spec](https://agentlist.io/systems/elicit)
- [Gemini Deep Research](https://ai.google) — Google's research-agent mode: it plans a multi-step search, fans out across the web, and delivers a structured report — with tight integration into Workspace docs and Drive. · [spec](https://agentlist.io/systems/gemini-deep-research)
- [Genspark](https://www.genspark.ai) — The all-in-one agent workspace from ex-Baidu leadership: Super Agent runs research and produces 'Sparkpages', slides, sheets, and calls — a research agent that finishes artifacts, not just text. · [spec](https://agentlist.io/systems/genspark)
- [Hebbia (Matrix)](https://www.hebbia.ai) — The analyst agent for finance, legal, and consulting: it runs multi-step queries across thousands of internal documents — filings, contracts, transcripts — and returns structured, cited grids. · [spec](https://agentlist.io/systems/hebbia)
- [Perplexity](https://www.perplexity.ai) — The answer-engine that grew into a research agent: Deep Research and Labs modes run multi-step searches, build reports, and even produce dashboards and mini-apps. · [spec](https://agentlist.io/systems/perplexity)

## Voice & phone agents

*Agents that answer the phone — and make calls.* — Voice agents handle real-time spoken conversations: inbound reception and support, outbound reminders and qualification, scheduling, intake, and surveys. The category is mostly developer platforms (Vapi, Retell, Bland, Deepgram, ElevenLabs Agents) that orchestrate speech-to-text, a model, and text-to-speech over telephony — plus no-code products (Synthflow) that ship a ready receptionist.

- [Bland AI](https://www.bland.ai) — The enterprise phone-agent platform: autonomous inbound/outbound calls at scale with an emphasis on security, compliance, and call-center-grade throughput. · [spec](https://agentlist.io/systems/bland)
- [Deepgram Voice Agent](https://deepgram.com) — The speech-native API: a single endpoint that combines Deepgram's STT/TTS with an LLM loop for real-time voice agents, priced per minute. · [spec](https://agentlist.io/systems/deepgram-voice-agent)
- [ElevenLabs Agents](https://elevenlabs.io) — The voice agent platform built on the industry's best-known TTS: conversational agents with top-tier voices, phone and web deployment, and model-agnostic reasoning. · [spec](https://agentlist.io/systems/elevenlabs-agents)
- [Retell AI](https://www.retellai.com) — A voice-agent platform focused on production call quality: fine-grained latency tuning, interruption handling, and both API and no-code agent building for phone agents. · [spec](https://agentlist.io/systems/retell)
- [Synthflow](https://synthflow.ai) — The no-code voice-agent product: agencies and SMBs build receptionist, intake, and outbound agents from templates without touching telephony or APIs. · [spec](https://agentlist.io/systems/synthflow)
- [Vapi](https://vapi.ai) — The developer platform for voice agents: API-first orchestration of STT, LLM, TTS, and telephony so you can put an agent on a phone number in minutes — and swap every layer. · [spec](https://agentlist.io/systems/vapi)

## Contributing

This list is generated from the catalog behind [agentlist.io](https://agentlist.io). To add or correct an agent, open an issue there or edit `data/catalog-seed.json` and `data/catalog-content.json` — the README rebuilds from those records. Entries are editorial records, not endorsements; pricing and status are approximate as of the seed date.

## License

[CC0](https://creativecommons.org/publicdomain/zero/1.0/) — public domain. Attribution welcome, not required.
