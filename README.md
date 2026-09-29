<div align="center">
	<br>
	<a href="https://www.agentlist.io"><img width="720" src="media/banner.png" alt="Awesome Agent List — agentlist.io"></a>
	<br>
	<br>
	<div>
		<a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
		<a href="CONTRIBUTING.md"><img src="https://img.shields.io/badge/contributions-welcome-f04424.svg" alt="Contributions welcome"></a>
		<a href="https://www.agentlist.io/changelog"><img src="https://img.shields.io/badge/systems-108-171714.svg" alt="108 systems cataloged"></a>
		<a href="LICENSE"><img src="https://img.shields.io/badge/license-CC0_1.0-6b6a64.svg" alt="License: CC0"></a>
	</div>
	<br>
	<h3><a href="https://www.agentlist.io">agentlist.io</a> — every agent, one spec sheet</h3>
	<sub>108 systems · 89 vendors · 14 categories — verified 2026-09-25. Pricing and status are approximate; confirm on vendor pages.</sub>
	<br>
	<br>
	<p>
		<a href="https://www.agentlist.io/list-of-ai-agents">Browse the list on the web</a>&nbsp;&nbsp;&nbsp;
		<a href="https://www.agentlist.io/capabilities">Capability tags</a>&nbsp;&nbsp;&nbsp;
		<a href="https://www.agentlist.io/integrations">Integrations</a>&nbsp;&nbsp;&nbsp;
		<a href="https://www.agentlist.io/compare">Compare agents</a>&nbsp;&nbsp;&nbsp;
		<a href="https://www.agentlist.io/feed.xml">RSS</a>&nbsp;&nbsp;&nbsp;
		<a href="https://www.agentlist.io/api/v1/systems">JSON API</a>
	</p>
</div>

> A maintained list of AI agents — coding agents, digital employees, ops agents, computer-use agents, research agents, voice agents, and the routers and protocols behind them. Every entry normalizes to the same spec fields on agentlist.io; the `spec` link opens the full record, and trailing `tags` are capability facets from the catalog taxonomy.

## Contents

- [AI IDEs](#ai-ides) (6)
- [IDE extensions & copilots](#ide-extensions--copilots) (8)
- [CLI & terminal agents](#cli--terminal-agents) (15)
- [Cloud & autonomous agents](#cloud--autonomous-agents) (5)
- [Model routers & gateways](#model-routers--gateways) (2)
- [Bridges, brokers & protocols](#bridges-brokers--protocols) (2)
- [Agent communication & collaboration](#agent-communication--collaboration) (13)
- [Agent services](#agent-services) (15)
- [Personal & always-on agents](#personal--always-on-agents) (6)
- [AI employees & digital coworkers](#ai-employees--digital-coworkers) (10)
- [On-call & ops agents](#on-call--ops-agents) (7)
- [Browser & computer-use agents](#browser--computer-use-agents) (6)
- [Research & analyst agents](#research--analyst-agents) (7)
- [Voice & phone agents](#voice--phone-agents) (6)

## AI IDEs

*Editors where the agent is the product surface.* An AI IDE is a forked or purpose-built code editor whose primary interface is an AI agent: repo-aware chat, multi-file edits, and agent modes are first-class, not a plugin. Most are VS Code forks; some are native editors that add agent panels.

- [Cursor](https://cursor.com) - A VS Code–based AI-native editor with repo-aware chat, multi-file edits, Composer/agent modes, and cloud background agents. · `file-edits` `repo-context` `code-exec` `background-tasks` `mcp` +2 · [spec](https://www.agentlist.io/systems/cursor)
- [Google Antigravity](https://antigravity.google) - Google's agent-first IDE and CLI, the successor surface to Gemini Code Assist for individuals and Gemini CLI. · `file-edits` `repo-context` `code-exec` `browser-ops` `long-horizon` +1 · [spec](https://www.agentlist.io/systems/antigravity)
- [Kiro](https://kiro.dev) - AWS's agent-first IDE: spec-driven development (requirements → design → tasks), agent hooks, and an Auto agent, with a CLI. · `file-edits` `repo-context` `shell` `mcp` `long-horizon` · [spec](https://www.agentlist.io/systems/kiro)
- [Trae](https://www.trae.ai) - ByteDance's AI-native VS Code fork with Builder chat and SOLO, an autonomous mode that plans and builds whole apps from a brief. · `file-edits` `repo-context` `code-exec` `long-horizon` `model-routing` · [spec](https://www.agentlist.io/systems/trae)
- [Windsurf / Devin Desktop](https://windsurf.com) - Cognition's AI IDE (ex-Codeium) built around Cascade multi-step agent flows, sold on the same Free / Pro / Max / Teams sheet as Devin. · `file-edits` `repo-context` `code-exec` `shell` `mcp` +3 · [spec](https://www.agentlist.io/systems/windsurf)
- [Zed](https://zed.dev) - A fast native editor (Rust, GPU-rendered) with a built-in agent panel, edit predictions, and hosted or BYOK models. · `file-edits` `repo-context` `shell` `mcp` · [spec](https://www.agentlist.io/systems/zed)

## IDE extensions & copilots

*Agents that live inside the editor you already run.* IDE extensions add completion, chat, and agent modes to an existing editor — VS Code, JetBrains, Neovim — through the editor's plugin system. They range from vendor copilots to open-source, bring-your-own-key agents.

- [Amazon Q Developer](https://aws.amazon.com) - AWS's coding assistant with IDE and CLI agents plus Java/.NET transformation. · `file-edits` `repo-context` `shell` `code-review` · [spec](https://www.agentlist.io/systems/amazon-q-developer)
- [Augment Code](https://www.augmentcode.com) - A context-engine coding agent for large codebases, available in VS Code, JetBrains, and a CLI (Auggie), priced as one flat team plan. · `file-edits` `repo-context` `long-horizon` `mcp` · [spec](https://www.agentlist.io/systems/augment)
- [Cline](https://github.com/cline/cline) - An open-source VS Code agent that plans, edits, and runs tools with BYOK models and approval controls. · `file-edits` `repo-context` `shell` `browser-ops` `mcp` +2 · [spec](https://www.agentlist.io/systems/cline) ![GitHub Repo stars](https://img.shields.io/github/stars/cline/cline?style=flat)
- [Gemini Code Assist](https://codeassist.google) - Google's per-seat coding assistant for IDEs and Google Cloud workflows, now sold only as Standard and Enterprise. **(caution)** · `file-edits` `repo-context` · [spec](https://www.agentlist.io/systems/gemini-code-assist)
- [GitHub Copilot](https://github.com) - The GitHub-native coding assistant: completions, chat, agent mode, and PR coding agents across many IDEs. · `file-edits` `repo-context` `code-review` `git-pr` `model-routing` +2 · [spec](https://www.agentlist.io/systems/copilot)
- [Junie](https://www.jetbrains.com) - JetBrains' coding agent — inside JetBrains IDEs (Junie Local in AI Chat) and as a terminal CLI. · `file-edits` `repo-context` `code-exec` `git-pr` · [spec](https://www.agentlist.io/systems/junie)
- [Kilo Code](https://marketplace.visualstudio.com) - An open-source agentic platform — VS Code/JetBrains extension, CLI, Slack, and cloud agents over a shared OpenCode engine. · `file-edits` `repo-context` `shell` `mcp` `model-routing` +1 · [spec](https://www.agentlist.io/systems/kilo-code)
- [Sourcegraph Cody](https://sourcegraph.com) - A codebase-aware assistant powered by Sourcegraph's code graph, now enterprise-focused. **(caution)** · `file-edits` `repo-context` · [spec](https://www.agentlist.io/systems/cody)

## CLI & terminal agents

*Terminal-native agents that edit repos, run commands, and commit.* CLI agents run in the shell against a local checkout. They read the repository, plan changes, edit files, execute commands and tests, and often commit — usually with tool protocols like MCP for extension.

- [Aider](https://github.com/Aider-AI/aider) - An open-source, Git-native pair programmer: it maps the repo, proposes commits, and works with any model via BYOK or OpenRouter. **(caution)** · `file-edits` `repo-context` `shell` `git-pr` · [spec](https://www.agentlist.io/systems/aider) ![GitHub Repo stars](https://img.shields.io/github/stars/Aider-AI/aider?style=flat)
- [Amp](https://ampcode.com) - A terminal-first, multi-model coding agent with subagents, an Oracle second-opinion model, threads, and MCP plugins. · `file-edits` `repo-context` `shell` `mcp` `long-horizon` · [spec](https://www.agentlist.io/systems/amp)
- [Claude Code](https://claude.com) - Anthropic's terminal-native coding agent: it plans, edits, runs commands, uses Git and MCP, and sustains long agentic loops. · `file-edits` `repo-context` `shell` `code-exec` `git-pr` +5 · [spec](https://www.agentlist.io/systems/claude-code)
- [Codex CLI](https://github.com/openai/codex) - OpenAI's coding agent: an open-source terminal CLI, a desktop app, IDE extensions, and a cloud lane for async tasks, all included in ChatGPT plans. · `file-edits` `repo-context` `shell` `code-exec` `git-pr` +3 · [spec](https://www.agentlist.io/systems/codex-cli) ![GitHub Repo stars](https://img.shields.io/github/stars/openai/codex?style=flat)
- [Crush](https://github.com/charmbracelet/crush) - Charm's open-source terminal coding agent — multi-model sessions that can switch providers mid-session, LSP-enhanced context, MCP support, and a polished TUI on every major platform. · `file-edits` `repo-context` `shell` `mcp` `model-routing` · [spec](https://www.agentlist.io/systems/crush) ![GitHub Repo stars](https://img.shields.io/github/stars/charmbracelet/crush?style=flat)
- [Gemini CLI](https://github.com/google-gemini/gemini-cli) - Google's open-source terminal agent; on June 18, 2026 it stopped serving free and Google AI Pro/Ultra accounts in favor of the Antigravity CLI. **(caution)** · `file-edits` `repo-context` `shell` `mcp` `web-research` · [spec](https://www.agentlist.io/systems/gemini-cli) ![GitHub Repo stars](https://img.shields.io/github/stars/google-gemini/gemini-cli?style=flat)
- [Goose](https://github.com/block/goose) - Block's local-first agent runtime with many model providers and extensible tool plugins. · `file-edits` `shell` `mcp` `model-routing` `self-hostable` · [spec](https://www.agentlist.io/systems/goose) ![GitHub Repo stars](https://img.shields.io/github/stars/block/goose?style=flat)
- [Grok Build](https://github.com/xai-org/grok-build) - XAI's terminal coding agent — a full-screen, mouse-interactive TUI (open-source Rust) powered by Grok 4.6, with skills, subagents in Git worktrees, headless mode, and ACP embedding for editors. · `file-edits` `repo-context` `shell` `web-research` · [spec](https://www.agentlist.io/systems/grok-build) ![GitHub Repo stars](https://img.shields.io/github/stars/xai-org/grok-build?style=flat)
- [Kimi Code](https://github.com/MoonshotAI/kimi-code) - Moonshot AI's single-binary terminal agent — tuned TUI, subagents, conversational MCP setup, lifecycle hooks, and ACP for Zed/JetBrains. · `file-edits` `repo-context` `shell` `mcp` · [spec](https://www.agentlist.io/systems/kimi-code) ![GitHub Repo stars](https://img.shields.io/github/stars/MoonshotAI/kimi-code?style=flat)
- [Mistral Vibe](https://mistral.ai) - Mistral's open-source CLI coding agent powered by Devstral 2 — terminal-native multi-file automation with IDE extensions for VS Code, JetBrains, and Zed over ACP. · `file-edits` `repo-context` `shell` · [spec](https://www.agentlist.io/systems/mistral-vibe)
- [Muse Code](https://dev.meta.ai) - Meta's terminal coding agent powered by Muse Spark 1.2 — persistent background subagents, a replay-exact event log, workflow orchestration, and a TypeScript SDK over the Muse Session Protocol. · `file-edits` `repo-context` `shell` · [spec](https://www.agentlist.io/systems/muse-code)
- [OpenCode](https://github.com/sst/opencode) - An MIT-licensed open-source terminal coding agent that is fully BYOK, with optional hosted model access via Zen and Go. · `file-edits` `repo-context` `shell` `mcp` `model-routing` +1 · [spec](https://www.agentlist.io/systems/opencode) ![GitHub Repo stars](https://img.shields.io/github/stars/sst/opencode?style=flat)
- [OpenHands](https://github.com/OpenHands/openhands) - An open-source software engineering agent you can self-host, using LiteLLM or OpenRouter for models. · `file-edits` `repo-context` `shell` `code-exec` `browser-ops` +3 · [spec](https://www.agentlist.io/systems/openhands) ![GitHub Repo stars](https://img.shields.io/github/stars/OpenHands/openhands?style=flat)
- [Qwen Code](https://github.com/QwenLM/qwen-code) - Alibaba's open-source terminal agent — adapted from Gemini CLI and tuned for Qwen3-Coder — with subagents, agent teams, auto-memory and auto-skills, IDE plugins, a desktop app, daemon mode, and SDKs. · `file-edits` `repo-context` `shell` `mcp` · [spec](https://www.agentlist.io/systems/qwen-code) ![GitHub Repo stars](https://img.shields.io/github/stars/QwenLM/qwen-code?style=flat)
- [Warp](https://www.warp.dev) - A terminal that ships its own coding agent (Warp Agent / Oz) with plan-bundled credits, so the shell itself runs agentic tasks. · `shell` `file-edits` `repo-context` `long-horizon` `mcp` · [spec](https://www.agentlist.io/systems/warp)

## Cloud & autonomous agents

*Ticket-in, PR-out workers running outside your editor.* Cloud agents run in a vendor-hosted sandbox rather than on your machine. You hand them a task — an issue, a ticket, a prompt — and they return a pull request or a deployed change for human review.

- [Devin](https://devin.ai) - Cognition's autonomous software engineer: cloud sandboxes for ticket-in / PR-out work, plus Devin Desktop and CLI on the same plan as Windsurf. · `file-edits` `repo-context` `shell` `code-exec` `browser-ops` +5 · [spec](https://www.agentlist.io/systems/devin)
- [Factory Droids](https://factory.ai) - Enterprise agent fleets for code, review, docs, tests, and knowledge, run via CLI, desktop, or cloud Missions. · `file-edits` `repo-context` `shell` `code-exec` `git-pr` +2 · [spec](https://www.agentlist.io/systems/droid)
- [Jules](https://jules.google) - Google's async issue-to-PR coding agent, running tasks in the cloud from a GitHub issue handoff. · `file-edits` `repo-context` `code-exec` `git-pr` `long-horizon` +1 · [spec](https://www.agentlist.io/systems/jules)
- [Replit Agent](https://replit.com) - Full-stack apps in the browser on Replit's hosted runtime. · `file-edits` `code-exec` `long-horizon` `background-tasks` · [spec](https://www.agentlist.io/systems/replit-agent)
- [Roomote](https://github.com/RooCodeInc/Roomote) - The Roo Code team's single-tenant cloud coding agent: your own hosted or self-hosted instance that runs tasks against your repos. · `long-horizon` `human-handoff` `multi-agent` · [spec](https://www.agentlist.io/systems/roomote) ![GitHub Repo stars](https://img.shields.io/github/stars/RooCodeInc/Roomote?style=flat)

## Model routers & gateways

*One API in front of many LLM providers.* Model routers expose a single, usually OpenAI-compatible API and route requests across providers with fallbacks, spend controls, and usage billing. Most BYOK coding agents can point at one.

- [LiteLLM](https://github.com/BerriAI/litellm) - A self-hostable proxy that normalizes hundreds of LLM APIs behind an OpenAI-compatible endpoint. · `model-routing` `api-native` `self-hostable` · [spec](https://www.agentlist.io/systems/litellm) ![GitHub Repo stars](https://img.shields.io/github/stars/BerriAI/litellm?style=flat)
- [OpenRouter](https://openrouter.ai) - A single API to many LLM providers with routing, fallbacks, and usage billing — widely wired into Aider, Continue, Goose, and OpenHands. · `model-routing` `api-native` · [spec](https://www.agentlist.io/systems/openrouter)

## Bridges, brokers & protocols

*Connective tissue: tool protocols and transports.* Bridges attach agents to tools, data, and channels — tool protocols (MCP), memory servers, and transport bindings that expose an agent through chat or voice. For agents talking to agents, see agent communication.

- [Instinct](https://pypi.org/project/instinct-mcp/) - A self-learning memory MCP server for coding agents — it observes repeated patterns, scores them by confidence, and promotes mature ones into suggestions it exports back to Claude Code, Cursor, Windsurf, Codex, and CLAUDE.md. **(caution)** · `mcp` `a2a` `api-native` `self-hostable` · [spec](https://www.agentlist.io/systems/instinct)
- [Model Context Protocol](https://github.com/modelcontextprotocol/specification) - An open protocol for connecting agents and IDEs to tools and data sources through MCP servers. · `mcp` `tool-calling` `api-native` · [spec](https://www.agentlist.io/systems/mcp) ![GitHub Repo stars](https://img.shields.io/github/stars/modelcontextprotocol/specification?style=flat)

## Agent communication & collaboration

*Protocols and frameworks for agents that talk to agents.* Bridges connect agents to tools; this category connects agents to each other. It splits into open protocols for cross-vendor discovery and messaging (A2A, AGNTCY, ANP, NANDA) and multi-agent frameworks where a supervisor delegates work to specialists through handoffs (CrewAI, Microsoft Agent Framework, LangGraph, MetaGPT, CAMEL).

- [A2A Protocol](https://github.com/a2aproject/A2A) - A2A (Agent2Agent) is the open protocol for cross-vendor agent communication — Google-originated, now governed at the Linux Foundation — standardizing Agent Cards for capability discovery plus task-based messaging between agents. · `a2a` `api-native` · [spec](https://www.agentlist.io/systems/a2a) ![GitHub Repo stars](https://img.shields.io/github/stars/a2aproject/A2A?style=flat)
- [Agency Swarm](https://github.com/VRSEN/agency-swarm) - VRSEN's framework for building 'agencies' of OpenAI-powered agents — defining agents, their tools, and which agents are allowed to talk to which over an explicit communication-flow graph. · `multi-agent` `tool-calling` `api-native` · [spec](https://www.agentlist.io/systems/agency-swarm) ![GitHub Repo stars](https://img.shields.io/github/stars/VRSEN/agency-swarm?style=flat)
- [Agent Network Protocol](https://github.com/agent-network-protocol/AgentNetworkProtocol) - An open spec for a decentralized web of agents — DID-based identity, capability description, and peer-to-peer agent messaging without a central directory. · `a2a` `identity` `api-native` · [spec](https://www.agentlist.io/systems/anp) ![GitHub Repo stars](https://img.shields.io/github/stars/agent-network-protocol/AgentNetworkProtocol?style=flat)
- [AGNTCY](https://agntcy.org) - The Cisco-originated 'Internet of Agents' collective — an open-source stack for agent discovery (directory), secure messaging (SLIM), identity, and observability across vendors. · `a2a` `identity` `api-native` · [spec](https://www.agentlist.io/systems/agntcy)
- [BeeAI](https://github.com/i-am-bee/beeai-framework) - IBM's open-source agent platform — run, compose, and observe agents locally or on a cluster, with ACP/A2A-style interop and a web UI for non-technical operators. · `multi-agent` `a2a` `api-native` · [spec](https://www.agentlist.io/systems/beeai) ![GitHub Repo stars](https://img.shields.io/github/stars/i-am-bee/beeai-framework?style=flat)
- [CAMEL](https://github.com/camel-ai/camel) - The research-rooted multi-agent framework: role-playing agents, agent societies, and toolkits for scaling multi-agent behavior — widely used in academic multi-agent studies. · `multi-agent` `tool-calling` `api-native` · [spec](https://www.agentlist.io/systems/camel) ![GitHub Repo stars](https://img.shields.io/github/stars/camel-ai/camel?style=flat)
- [CrewAI](https://github.com/crewAIInc/crewAI) - The most widely adopted multi-agent framework: model crews of role-based agents in YAML or Python, run sequential or hierarchical processes, and manage fleets through the CrewAI control plane. · `multi-agent` `tool-calling` `api-native` `workflow-builder` · [spec](https://www.agentlist.io/systems/crewai) ![GitHub Repo stars](https://img.shields.io/github/stars/crewAIInc/crewAI?style=flat)
- [LangGraph](https://github.com/langchain-ai/langgraph) - LangChain's agent orchestration framework — durable stateful graphs with supervisor and swarm multi-agent patterns, checkpointing, and LangGraph Platform for deployment. · `multi-agent` `tool-calling` `api-native` `memory` `workflow-builder` +1 · [spec](https://www.agentlist.io/systems/langgraph) ![GitHub Repo stars](https://img.shields.io/github/stars/langchain-ai/langgraph?style=flat)
- [MetaGPT](https://github.com/FoundationAgents/MetaGPT) - The multi-agent framework that turns a one-line brief into a simulated software company — PM, architect, and engineer agents handing off artifacts along an assembly line. · `multi-agent` `tool-calling` `api-native` `code-exec` · [spec](https://www.agentlist.io/systems/metagpt) ![GitHub Repo stars](https://img.shields.io/github/stars/FoundationAgents/MetaGPT?style=flat)
- [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) - The successor to AutoGen and Semantic Kernel's agent pieces — one OSS framework (Python and .NET) for single agents, multi-agent graphs, and Magentic-style orchestration. · `multi-agent` `tool-calling` `api-native` `workflow-builder` · [spec](https://www.agentlist.io/systems/agent-framework) ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/agent-framework?style=flat)
- [NANDA](https://nanda.media.mit.edu) - MIT Media Lab's 'Internet of AI Agents' research program — a registry and index layer plus protocols for discovering, verifying, and composing agents at internet scale. · `a2a` `identity` `api-native` · [spec](https://www.agentlist.io/systems/nanda)
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) - The OpenAI Agents SDK is OpenAI's lightweight framework for agentic apps — its handoffs primitive is a first-class agent-to-agent mechanism: one agent transfers the live conversation to a specialist. · `multi-agent` `tool-calling` `api-native` `human-handoff` · [spec](https://www.agentlist.io/systems/openai-agents-sdk) ![GitHub Repo stars](https://img.shields.io/github/stars/openai/openai-agents-python?style=flat)
- [OpenScout / Scout](https://github.com/arach/openscout) - A local-first broker that lets addressable agents (Claude Code, Codex, Cursor) send and ask across harnesses on one mesh. · `a2a` `messaging-infra` `multi-agent` `api-native` `self-hostable` +1 · [spec](https://www.agentlist.io/systems/scout) ![GitHub Repo stars](https://img.shields.io/github/stars/arach/openscout?style=flat)

## Agent services

*The substrate agents can't self-provision — payments, identity, inboxes, sandboxes, search, memory.* Agent services are purpose-built primitives whose customer is the agent (or its builder): ways to pay (x402, AP2, AgentCard, Skyfire), ways to authenticate (Keycard, Arcade, Scalekit), places to exist (AgentMail inboxes, E2B sandboxes, Browserbase browsers), and senses (Exa search, Mem0 memory). Where bridges give agents protocols, services give them accounts — metered, billable capabilities the agent can't synthesize.

- [Agent Payments Protocol](https://github.com/google-agentic-commerce/AP2) - Google's open spec for agent-initiated payments — signed mandates that prove a user authorized a purchase, riding existing card networks and payment rails instead of inventing new ones. · `payments` `a2a` `api-native` · [spec](https://www.agentlist.io/systems/ap2) ![GitHub Repo stars](https://img.shields.io/github/stars/google-agentic-commerce/AP2?style=flat)
- [AgentCard](https://agentcard.ai) - Virtual payment cards for agents from a CLI — a one-line install provisions the agent's card, email inbox, and x402 wallet so it can check out anywhere a card is accepted. · `identity` `api-native` · [spec](https://www.agentlist.io/systems/agentcard)
- [AgentMail](https://github.com/agentmail-to/agentmail-mcp) - Email infrastructure for agents — API-created inboxes, sending, and parsing that give an agent a durable, interoperable address for agent-to-agent and agent-to-human communication. · `messaging-infra` `api-native` · [spec](https://www.agentlist.io/systems/agentmail) ![GitHub Repo stars](https://img.shields.io/github/stars/agentmail-to/agentmail-mcp?style=flat)
- [Arcade](https://github.com/ArcadeAI/arcade-ai) - Auth and tools for agent builders — a managed way for agents to act on a user's behalf (email, calendar, Slack, GitHub) with scoped OAuth tokens, plus a tool-calling SDK. · `tool-calling` `identity` `api-native` · [spec](https://www.agentlist.io/systems/arcade) ![GitHub Repo stars](https://img.shields.io/github/stars/ArcadeAI/arcade-ai?style=flat)
- [Browserbase](https://www.browserbase.com) - Browsers-as-a-service for web agents — hosted headless browsers with stealth, proxies, sessions, and replay, the runtime underneath its own Stagehand framework and third-party agents. · `browser-ops` `sandbox-runtime` `api-native` · [spec](https://www.agentlist.io/systems/browserbase)
- [Composio](https://github.com/ComposioHQ/composio) - A tool-and-integration platform for agents — hundreds of SaaS tools (Gmail, Slack, GitHub, Linear) exposed to any agent framework with managed auth and consistent schemas. · `tool-calling` `mcp` `api-native` · [spec](https://www.agentlist.io/systems/composio) ![GitHub Repo stars](https://img.shields.io/github/stars/ComposioHQ/composio?style=flat)
- [E2B](https://github.com/e2b-dev/E2B) - Secure sandboxes for agent-generated code — instant isolated VMs where an agent can run untrusted code, install packages, and keep files, widely used as the compute layer behind AI apps. · `sandbox-runtime` `code-exec` `api-native` · [spec](https://www.agentlist.io/systems/e2b) ![GitHub Repo stars](https://img.shields.io/github/stars/e2b-dev/E2B?style=flat)
- [Exa](https://github.com/exa-labs/exa-py) - A search engine built for agents — an index queried by meaning (neural + keyword) with APIs that return clean page contents instead of a page of links. · `web-research` `api-native` · [spec](https://www.agentlist.io/systems/exa) ![GitHub Repo stars](https://img.shields.io/github/stars/exa-labs/exa-py?style=flat)
- [Keycard](https://keycard.sh) - Identity and access for autonomous agents — issues agents their own credentials, applies policy to what each agent may touch, and audits it like an employee's badge. · `identity` `api-native` · [spec](https://www.agentlist.io/systems/keycard)
- [Mem0](https://github.com/mem0ai/mem0) - The memory layer for agents — extract, store, and retrieve user-and-agent memories across sessions, as open-source SDK or hosted API. · `memory` `api-native` `self-hostable` · [spec](https://www.agentlist.io/systems/mem0) ![GitHub Repo stars](https://img.shields.io/github/stars/mem0ai/mem0?style=flat)
- [Nevermined](https://nevermined.io) - Agentic-commerce infrastructure — payments, subscriptions, and metering built for agents buying from agents, with agent-to-agent payment plans and credits. · `payments` `api-native` · [spec](https://www.agentlist.io/systems/nevermined)
- [Payman](https://paymanai.com) - Agent payments with the approval layer built in — wallets, policies, and human-in-the-loop sign-off so an agent can spend money it can't lose. · `payments` `human-handoff` `api-native` · [spec](https://www.agentlist.io/systems/payman)
- [Scalekit](https://www.scalekit.com) - The auth stack for agent apps — MCP-server auth, agent OAuth flows, and SSO/SCIM for the humans, so one platform covers who the user is and what the agent may do. · `identity` `api-native` · [spec](https://www.agentlist.io/systems/scalekit)
- [Skyfire](https://skyfire.xyz) - A payments and identity network for the agent economy — it gives agents a wallet and verifiable 'KYA' (know-your-agent) credentials so they can pay APIs, MCP servers, and each other. · `payments` `api-native` · [spec](https://www.agentlist.io/systems/skyfire)
- [x402](https://github.com/coinbase/x402) - Coinbase's open payment protocol — it revives HTTP 402 Payment Required so an agent that hits a paid resource can settle programmatically in stablecoins (USDC on Base) and get the resource, no human checkout step. · `payments` `api-native` · [spec](https://www.agentlist.io/systems/x402) ![GitHub Repo stars](https://img.shields.io/github/stars/coinbase/x402?style=flat)

## Personal & always-on agents

*Self-hosted assistants that live in your chat apps, not your editor.* Personal agents are self-hosted assistant runtimes: one gateway or process that holds sessions, memory, tools, and skills, and meets you in the channels you already use — Telegram, WhatsApp, Discord, Slack, Signal, iMessage — alongside CLIs, TUIs, and web dashboards. They run on your hardware or your VPS, keep state on your machine, and delegate to repo-native coding agents when the task is code.

- [Hermes Agent](https://github.com/NousResearch/hermes-agent) - Nous Research's self-improving assistant — a closed learning loop creates skills from experience and refines them in use, with agent-curated memory, periodic nudges, FTS5 session search, and Honcho user modeling. · `memory` `messaging-infra` `long-horizon` `api-native` · [spec](https://www.agentlist.io/systems/hermes-agent) ![GitHub Repo stars](https://img.shields.io/github/stars/NousResearch/hermes-agent?style=flat)
- [nanobot](https://github.com/HKUDS/nanobot) - HKUDS's Python answer to OpenClaw — a compact, MCP-native assistant codebase you can audit in an afternoon, popular as a learning platform and a base for custom assistants. · `memory` `messaging-infra` `api-native` `self-hostable` · [spec](https://www.agentlist.io/systems/nanobot) ![GitHub Repo stars](https://img.shields.io/github/stars/HKUDS/nanobot?style=flat)
- [NanoClaw](https://github.com/qwibitai/nanoclaw) - A TypeScript OpenClaw fork built for isolation — each agent runs in its own container, with Agent Swarms for multi-agent collaboration — the security-first direct replacement for the original gateway. · `memory` `messaging-infra` `api-native` `self-hostable` · [spec](https://www.agentlist.io/systems/nanoclaw) ![GitHub Repo stars](https://img.shields.io/github/stars/qwibitai/nanoclaw?style=flat)
- [OpenClaw](https://github.com/openclaw/openclaw) - The category-defining self-hosted assistant: one Gateway on your own hardware connects ~29 chat channels (WhatsApp, Telegram, Signal, iMessage, Slack, Discord…) to an agent with memory, skills, sessions, and multi-agent routing — stewarded by an independent 501(c)(3). · `memory` `messaging-infra` `long-horizon` `self-hostable` `browser-ops` +1 · [spec](https://www.agentlist.io/systems/openclaw) ![GitHub Repo stars](https://img.shields.io/github/stars/openclaw/openclaw?style=flat)
- [PicoClaw](https://github.com/sipeed/picoclaw) - Sipeed's Go rewrite for embedded — one binary that cold-starts in under a second inside ~10MB of RAM on single-board computers; roughly 95% of its core was written by an AI agent. · `memory` `messaging-infra` `api-native` `self-hostable` · [spec](https://www.agentlist.io/systems/picoclaw) ![GitHub Repo stars](https://img.shields.io/github/stars/sipeed/picoclaw?style=flat)
- [ZeroClaw](https://github.com/zeroclaw-labs/zeroclaw) - A Rust rewrite of the personal-agent shape — a single binary under ~5MB RAM that talks to ~20 model providers and 30+ channels, with supervised-by-default autonomy, OS-level sandboxes, signed tool receipts, and GPIO/I2C/SPI for real hardware. · `memory` `messaging-infra` `api-native` `self-hostable` · [spec](https://www.agentlist.io/systems/zeroclaw) ![GitHub Repo stars](https://img.shields.io/github/stars/zeroclaw-labs/zeroclaw?style=flat)

## AI employees & digital coworkers

*Agents hired for a role, not opened like a tool.* AI employees are agents packaged as a job function — an SDR that prospects, a support rep that resolves tickets, a recruiter that screens candidates. They arrive with an identity, a role, and integrations into the systems that role touches (CRM, helpdesk, ATS, email, phone), and they're sold on seats or outcomes rather than editor features.

- [Alice](https://www.11x.ai) - 11x's AI SDR: she researches accounts, writes outbound sequences across email and LinkedIn, and books meetings — with sibling agent Julian handling inbound phone calls. · `human-handoff` `web-research` `api-native` · [spec](https://www.agentlist.io/systems/alice)
- [Ava](https://www.artisan.co) - Artisan's AI BDR: she mines a large contact database, personalizes outbound at scale, and manages replies through to booked meetings. · `human-handoff` `web-research` `api-native` · [spec](https://www.agentlist.io/systems/ava)
- [Decagon](https://decagon.ai) - Autonomous customer-support agents that resolve chats, emails, and calls for mid-market and enterprise brands, with engineering-grade tooling for the ops team behind them. · `human-handoff` `voice` `memory` `api-native` · [spec](https://www.agentlist.io/systems/decagon)
- [Fin](https://www.intercom.com) - Intercom's AI support agent: it answers customer questions from your help content, resolves conversations end-to-end, and charges only when it resolves. · `human-handoff` `memory` `api-native` · [spec](https://www.agentlist.io/systems/fin)
- [Harvey](https://www.harvey.ai) - The AI associate for legal work: drafting, review, diligence, and research grounded in legal corpora, deployed inside law firms and enterprise legal departments. · `citations` `web-research` `human-handoff` · [spec](https://www.agentlist.io/systems/harvey)
- [Juicebox (PeopleGPT)](https://juicebox.ai) - The recruiting AI employee: it searches candidate pools in natural language, runs outbound outreach, and ranks talent against your rubric. · `web-research` `human-handoff` `api-native` · [spec](https://www.agentlist.io/systems/juicebox)
- [Lindy](https://www.lindy.ai) - The build-your-own-employee platform: no-code agents that handle email triage, scheduling, meeting notes, CRM updates, and custom back-office workflows. · `workflow-builder` `human-handoff` `tool-calling` `api-native` · [spec](https://www.agentlist.io/systems/lindy)
- [Mercor](https://mercor.com) - The AI interviewer and talent marketplace: its agent screens candidates in structured video interviews and matches them to roles — and increasingly to AI-training gigs. · `human-handoff` `api-native` · [spec](https://www.agentlist.io/systems/mercor)
- [Piper](https://www.qualified.com) - Qualified's inbound AI SDR: she greets and qualifies website visitors in chat, works target accounts, and routes or books meetings against your CRM. · `human-handoff` `web-research` `api-native` · [spec](https://www.agentlist.io/systems/piper)
- [Sierra](https://sierra.ai) - The customer-service AI employee for large consumer brands: it resolves support conversations across chat and voice, takes actions in business systems, and bills on outcomes. · `human-handoff` `voice` `memory` `api-native` · [spec](https://www.agentlist.io/systems/sierra)

## On-call & ops agents

*Agents that hold the pager — triage, investigate, resolve.* Ops agents sit inside the incident and security loop: they watch alerts, correlate telemetry, investigate pages, draft root-cause analyses, and propose or apply remediations. AI SREs handle production incidents; AI SOC analysts (Dropzone, Simbian) handle security queues.

- [Bits AI](https://www.datadoghq.com) - Datadog's in-platform agent: it answers observability questions in natural language, investigates anomalies, and drafts incident summaries against the telemetry you already pay Datadog for. · `incident-response` `human-handoff` `api-native` · [spec](https://www.agentlist.io/systems/bits-ai)
- [Cleric](https://www.cleric.io) - A dedicated AI SRE: it investigates production alerts across logs, metrics, deploys, and code history, then hands on-call engineers a root-cause hypothesis with evidence. · `incident-response` `human-handoff` `api-native` · [spec](https://www.agentlist.io/systems/cleric)
- [Dropzone AI](https://www.dropzone.ai) - The AI SOC analyst: it investigates every alert end-to-end — triage, evidence gathering, verdict — so human analysts only see the ones that matter. · `incident-response` `human-handoff` `api-native` · [spec](https://www.agentlist.io/systems/dropzone)
- [incident.io](https://incident.io) - The incident-management platform whose AI assistant drafts timelines, summarizes channels, surfaces similar past incidents, and nudges responders — inside the tool that already runs your incidents. · `incident-response` `human-handoff` `messaging-infra` `api-native` · [spec](https://www.agentlist.io/systems/incident-io)
- [Resolve](https://resolve.ai) - An AI SRE from ex-Splunk/Observability leadership: it triages alerts, investigates incidents across your stack, and drafts remediations for approval. · `incident-response` `human-handoff` `api-native` · [spec](https://www.agentlist.io/systems/resolve)
- [Rootly](https://rootly.com) - The incident-response platform with AI woven through it: auto-drafted summaries, suggested next steps, retrospectives, and noise reduction on the alert stream. · `incident-response` `human-handoff` `messaging-infra` `api-native` · [spec](https://www.agentlist.io/systems/rootly)
- [Simbian](https://www.simbian.ai) - Autonomous SOC agents that hunt, investigate, and respond across the security stack, plus GRC automation — aimed at teams running lean against enterprise-scale alert volume. · `incident-response` `human-handoff` `api-native` · [spec](https://www.agentlist.io/systems/simbian)

## Browser & computer-use agents

*Agents that drive a GUI — clicks, forms, and logins, not commits.* Computer-use agents operate software through its interface — a browser, a desktop, a remote session — by reading the screen or DOM and acting with clicks, keystrokes, and navigation. Some are hosted products that take a goal and return a result (ChatGPT Agent, Manus); others are open frameworks and APIs for building your own (Browser Use, Skyvern, Stagehand, Claude Computer Use).

- [Browser Use](https://github.com/browser-use/browser-use) - The breakout open-source framework for browser agents: connect an LLM to a controllable browser, describe a task, and let it click, type, and navigate to completion — self-hosted or via Browser Use Cloud. · `browser-ops` `api-native` `self-hostable` `long-horizon` · [spec](https://www.agentlist.io/systems/browser-use) ![GitHub Repo stars](https://img.shields.io/github/stars/browser-use/browser-use?style=flat)
- [ChatGPT Agent](https://chatgpt.com) - OpenAI's hosted computer-use mode — the Operator lineage: it spins up a managed browser, works through multi-step web tasks, and can take actions after confirmation. · `browser-ops` `desktop-use` `web-research` `code-exec` `long-horizon` · [spec](https://www.agentlist.io/systems/chatgpt-agent)
- [Claude Computer Use](https://www.anthropic.com) - Anthropic's API capability: Claude reads screenshots and emits mouse/keyboard actions, letting developers build agents that operate desktops and browsers in their own sandboxes. · `desktop-use` `browser-ops` `api-native` · [spec](https://www.agentlist.io/systems/claude-computer-use)
- [Manus](https://manus.im) - The hosted general agent: give it a goal in chat and it works a cloud session — browsing, running code, building artifacts — returning finished deliverables rather than suggestions. · `browser-ops` `desktop-use` `web-research` `code-exec` `long-horizon` +1 · [spec](https://www.agentlist.io/systems/manus)
- [Skyvern](https://github.com/Skyvern-AI/skyvern) - An open-source browser-automation agent that uses LLMs plus computer vision to operate websites it's never seen — no brittle per-site selectors. · `browser-ops` `api-native` `self-hostable` `workflow-builder` · [spec](https://www.agentlist.io/systems/skyvern) ![GitHub Repo stars](https://img.shields.io/github/stars/Skyvern-AI/skyvern?style=flat)
- [Stagehand](https://github.com/browserbase/stagehand) - Browserbase's open-source agent framework: act/extract/observe primitives over a controllable browser, mixing deterministic Playwright code with LLM-driven steps. · `browser-ops` `api-native` `self-hostable` · [spec](https://www.agentlist.io/systems/stagehand) ![GitHub Repo stars](https://img.shields.io/github/stars/browserbase/stagehand?style=flat)

## Research & analyst agents

*Prompt in, cited report out.* Research agents take a question and return a structured, cited report — searching, reading, and synthesizing dozens of sources over minutes-long runs. Consumer 'deep research' modes live inside chat products (ChatGPT, Gemini, Perplexity); enterprise analysts work over licensed or internal corpora (Hebbia, AlphaSense); academic tools ground in the literature (Elicit).

- [AlphaSense](https://www.alpha-sense.com) - The institutional market-intelligence platform whose Deep Research agents search premium content — broker research, filings, transcripts, expert calls — and return decision-grade cited reports. · `web-research` `citations` · [spec](https://www.agentlist.io/systems/alphasense)
- [ChatGPT Deep Research](https://openai.com) - OpenAI's research-agent mode: a prompt becomes a 5–30 minute browsing run that returns a cited report — now also reachable via API as a deep-research model. · `web-research` `citations` `long-horizon` `api-native` · [spec](https://www.agentlist.io/systems/deep-research)
- [Elicit](https://elicit.com) - The research agent for scientific literature: it searches 125M+ papers, extracts methods and findings into structured tables, and drafts systematic-review-grade summaries with citations. · `web-research` `citations` · [spec](https://www.agentlist.io/systems/elicit)
- [Gemini Deep Research](https://gemini.google) - Google's research-agent mode: it plans a multi-step search, fans out across the web, and delivers a structured report — with tight integration into Workspace docs and Drive. · `web-research` `citations` `long-horizon` · [spec](https://www.agentlist.io/systems/gemini-deep-research)
- [Genspark](https://www.genspark.ai) - The all-in-one agent workspace from ex-Baidu leadership: Super Agent runs research and produces 'Sparkpages', slides, sheets, and calls — a research agent that finishes artifacts, not just text. · `web-research` `citations` `long-horizon` · [spec](https://www.agentlist.io/systems/genspark)
- [Hebbia (Matrix)](https://www.hebbia.ai) - The analyst agent for finance, legal, and consulting: it runs multi-step queries across thousands of internal documents — filings, contracts, transcripts — and returns structured, cited grids. · `web-research` `citations` · [spec](https://www.agentlist.io/systems/hebbia)
- [Perplexity](https://www.perplexity.ai) - The answer-engine that grew into a research agent: Deep Research and Labs modes run multi-step searches, build reports, and even produce dashboards and mini-apps. · `web-research` `citations` `api-native` · [spec](https://www.agentlist.io/systems/perplexity)

## Voice & phone agents

*Agents that answer the phone — and make calls.* Voice agents handle real-time spoken conversations: inbound reception and support, outbound reminders and qualification, scheduling, intake, and surveys. The category is mostly developer platforms (Vapi, Retell, Bland, Deepgram, ElevenLabs Agents) that orchestrate speech-to-text, a model, and text-to-speech over telephony — plus no-code products (Synthflow) that ship a ready receptionist.

- [Bland AI](https://www.bland.ai) - The enterprise phone-agent platform: autonomous inbound/outbound calls at scale with an emphasis on security, compliance, and call-center-grade throughput. · `voice` `human-handoff` `api-native` · [spec](https://www.agentlist.io/systems/bland)
- [Deepgram Voice Agent](https://deepgram.com) - The speech-native API: a single endpoint that combines Deepgram's STT/TTS with an LLM loop for real-time voice agents, priced per minute. · `voice` `api-native` `human-handoff` · [spec](https://www.agentlist.io/systems/deepgram-voice-agent)
- [ElevenLabs Agents](https://elevenlabs.io) - The voice agent platform built on the industry's best-known TTS: conversational agents with top-tier voices, phone and web deployment, and model-agnostic reasoning. · `voice` `api-native` `human-handoff` · [spec](https://www.agentlist.io/systems/elevenlabs-agents)
- [Retell AI](https://www.retellai.com) - A voice-agent platform focused on production call quality: fine-grained latency tuning, interruption handling, and both API and no-code agent building for phone agents. · `voice` `human-handoff` `api-native` · [spec](https://www.agentlist.io/systems/retell)
- [Synthflow](https://synthflow.ai) - The no-code voice-agent product: agencies and SMBs build receptionist, intake, and outbound agents from templates without touching telephony or APIs. · `voice` `human-handoff` `api-native` `workflow-builder` · [spec](https://www.agentlist.io/systems/synthflow)
- [Vapi](https://vapi.ai) - The developer platform for voice agents: API-first orchestration of STT, LLM, TTS, and telephony so you can put an agent on a phone number in minutes — and swap every layer. · `voice` `human-handoff` `api-native` · [spec](https://www.agentlist.io/systems/vapi)

---

*Maintained from the [www.agentlist.io](https://www.agentlist.io) catalog — additions and corrections go through [CONTRIBUTING.md](CONTRIBUTING.md), not hand edits to this README. Entries are editorial records, not endorsements or paid placements. [CC0](LICENSE).*
