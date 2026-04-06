# Useful AI Agent Skills

A curated list of **Agent Skills** — modular, reusable capability packages for AI coding agents like Claude Code, Codex, Cursor, Gemini CLI, Copilot, and Antigravity.

The unifying theme: each entry here ships **skills as artifacts** (typically `SKILL.md` files or equivalent) that teach an agent how to do something specific, rather than being a standalone agent harness.

> _Last updated: 2026-04-06. Refreshed on a rolling basis._

## Scope

See [SCOPE.md](./SCOPE.md) for the full inclusion/exclusion rules. In short:

**In scope:** skill collections (1st- and 3rd-party), domain skill packs (PM, marketing, research, SEO, media, finance, mobile), skill tooling (loaders, registries, builders, creators), skill memory systems, benchmarks, specifications, and awesome-lists.

**Out of scope:** generic agent harnesses (see [Local-AI-Agent-Resources](https://github.com/danielrosehill/Local-AI-Agent-Resources)), prompt libraries with no skill packaging, cloud-only SaaS with no installable artifact.

## Badge Legend

| Badge | Meaning |
|---|---|
| ![Type: 1st-party](https://img.shields.io/badge/Type-1st--party-blue) | Built by a model/platform vendor (Anthropic, Google, HuggingFace, Vercel, Cloudflare, Coinbase, Binance…) |
| ![Type: 3rd-party](https://img.shields.io/badge/Type-3rd--party-lightgrey) | Independent / community project |
| ![Domain](https://img.shields.io/badge/Domain-example-yellow) | Primary domain focus (PM, Marketing, Research, etc.) |

## Table of Contents

- [1. Vendor Skill Bundles](#1-vendor-skill-bundles)
- [2. Community Skill Collections](#2-community-skill-collections)
- [3. Awesome Lists](#3-awesome-lists)
- [4. Domain Skill Packs](#4-domain-skill-packs)
  - [Product Management](#product-management)
  - [Marketing & SEO](#marketing--seo)
  - [Research & Science](#research--science)
  - [Frontend / Design Taste](#frontend--design-taste)
  - [Generative Media](#generative-media)
  - [Mobile / Android](#mobile--android)
  - [Social Media](#social-media)
  - [Business & Startup](#business--startup)
- [5. Skill Tooling & Builders](#5-skill-tooling--builders)
- [6. Skill Registries & Hubs](#6-skill-registries--hubs)
- [7. Frameworks & Orchestration](#7-frameworks--orchestration)
- [8. Memory & Context](#8-memory--context)
- [9. Benchmarks](#9-benchmarks)
- [10. Specifications](#10-specifications)
- [11. Wallets & Crypto](#11-wallets--crypto)
- [12. Skill Security](#12-skill-security)

---

## 1. Vendor Skill Bundles

First-party skill collections maintained by model or platform vendors.

#### [Anthropic Skills](https://github.com/anthropics/skills)

![Stars](https://img.shields.io/github/stars/anthropics/skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/anthropics/skills) ![Type](https://img.shields.io/badge/Type-1st--party-blue)

Anthropic's public repository of Agent Skills.

---

#### [Apify Agent Skills](https://github.com/apify/agent-skills)

![Stars](https://img.shields.io/github/stars/apify/agent-skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/apify/agent-skills) ![Type](https://img.shields.io/badge/Type-1st--party-blue)

Collection of Apify Agent Skills for web scraping and automation workflows.

---

#### [Cloudflare Skills](https://github.com/cloudflare/skills)

![Stars](https://img.shields.io/github/stars/cloudflare/skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/cloudflare/skills) ![Type](https://img.shields.io/badge/Type-1st--party-blue)

Skills for teaching agents how to build on Cloudflare.

---

#### [Firebase Agent Skills](https://github.com/firebase/agent-skills)

![Stars](https://img.shields.io/github/stars/firebase/agent-skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/firebase/agent-skills) ![Type](https://img.shields.io/badge/Type-1st--party-blue)

Agent Skills for Firebase.

---

#### [Gemini Skills](https://github.com/google-gemini/gemini-skills)

![Stars](https://img.shields.io/github/stars/google-gemini/gemini-skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/google-gemini/gemini-skills) ![Type](https://img.shields.io/badge/Type-1st--party-blue)

Skills for the Gemini API, SDK, and model/agent interactions.

---

#### [Hugging Face Skills](https://github.com/huggingface/skills)

![Stars](https://img.shields.io/github/stars/huggingface/skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/huggingface/skills) ![Type](https://img.shields.io/badge/Type-1st--party-blue)

Give your agents the power of the Hugging Face ecosystem.

---

#### [Obsidian Skills](https://github.com/kepano/obsidian-skills)

![Stars](https://img.shields.io/github/stars/kepano/obsidian-skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/kepano/obsidian-skills) ![Type](https://img.shields.io/badge/Type-1st--party-blue)

Agent skills for Obsidian — teaches agents Markdown, Bases, JSON Canvas, and the Obsidian CLI.

---

#### [Vercel Agent Skills](https://github.com/vercel-labs/agent-skills)

![Stars](https://img.shields.io/github/stars/vercel-labs/agent-skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/vercel-labs/agent-skills) ![Type](https://img.shields.io/badge/Type-1st--party-blue)

Vercel's official collection of agent skills.

---

## 2. Community Skill Collections

Broad, multi-domain skill bundles from the community.

#### [claude-skills (alirezarezvani)](https://github.com/alirezarezvani/claude-skills)

![Stars](https://img.shields.io/github/stars/alirezarezvani/claude-skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/alirezarezvani/claude-skills) ![Type](https://img.shields.io/badge/Type-3rd--party-lightgrey)

220+ Claude Code skills and agent plugins spanning engineering, marketing, product, compliance, and C-level advisory — compatible with 8+ coding agents.

---

#### [Superpowers](https://github.com/obra/superpowers)

![Stars](https://img.shields.io/github/stars/obra/superpowers?style=social) ![Last commit](https://img.shields.io/github/last-commit/obra/superpowers) ![Type](https://img.shields.io/badge/Type-3rd--party-lightgrey)

An agentic skills framework and software development methodology that works.

---

#### [tech-leads-club Agent Skills](https://github.com/tech-leads-club/agent-skills)

![Stars](https://img.shields.io/github/stars/tech-leads-club/agent-skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/tech-leads-club/agent-skills) ![Type](https://img.shields.io/badge/Type-3rd--party-lightgrey)

Secure, validated skill registry for professional AI coding agents — extends Antigravity, Claude Code, Cursor, Copilot and more.

---

## 3. Awesome Lists

Curated directories of skills.

#### [awesome-agent-skills (VoltAgent)](https://github.com/VoltAgent/awesome-agent-skills)

![Stars](https://img.shields.io/github/stars/VoltAgent/awesome-agent-skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/VoltAgent/awesome-agent-skills) ![Type](https://img.shields.io/badge/Type-3rd--party-lightgrey)

Claude Code Skills and 1000+ agent skills from official dev teams and the community.

---

#### [awesome-agent-skills (heilcheng)](https://github.com/heilcheng/awesome-agent-skills)

![Stars](https://img.shields.io/github/stars/heilcheng/awesome-agent-skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/heilcheng/awesome-agent-skills) ![Type](https://img.shields.io/badge/Type-3rd--party-lightgrey)

Tutorials, guides, and agent skills directories.

---

#### [awesome-agent-skills (skillmatic-ai)](https://github.com/skillmatic-ai/awesome-agent-skills)

![Stars](https://img.shields.io/github/stars/skillmatic-ai/awesome-agent-skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/skillmatic-ai/awesome-agent-skills) ![Type](https://img.shields.io/badge/Type-3rd--party-lightgrey)

A resource for Agent Skills — modular capabilities for AI agent architecture.

---

#### [awesome-llm-skills](https://github.com/Prat011/awesome-llm-skills)

![Stars](https://img.shields.io/github/stars/Prat011/awesome-llm-skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/Prat011/awesome-llm-skills) ![Type](https://img.shields.io/badge/Type-3rd--party-lightgrey)

Curated list of LLM and AI Agent Skills, resources, and tools for customising agent workflows.

---

## 4. Domain Skill Packs

### Product Management

#### [ccpm](https://github.com/automazeio/ccpm)

![Stars](https://img.shields.io/github/stars/automazeio/ccpm?style=social) ![Last commit](https://img.shields.io/github/last-commit/automazeio/ccpm) ![Domain](https://img.shields.io/badge/Domain-PM-yellow)

Project management skill system for agents — uses GitHub Issues and git worktrees for parallel agent execution.

---

#### [pm-skills](https://github.com/phuryn/pm-skills)

![Stars](https://img.shields.io/github/stars/phuryn/pm-skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/phuryn/pm-skills) ![Domain](https://img.shields.io/badge/Domain-PM-yellow)

PM Skills Marketplace — 100+ agentic skills, commands, and plugins covering discovery, strategy, execution, launch, and growth.

---

#### [Product-Manager-Skills](https://github.com/deanpeters/Product-Manager-Skills)

![Stars](https://img.shields.io/github/stars/deanpeters/Product-Manager-Skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/deanpeters/Product-Manager-Skills) ![Domain](https://img.shields.io/badge/Domain-PM-yellow)

Product Management skills framework built on battle-tested methods for Claude Code, Cowork, Codex, and AI agents.

---

### Marketing & SEO

#### [Agentic-SEO-Skill](https://github.com/Bhanunamikaze/Agentic-SEO-Skill)

![Stars](https://img.shields.io/github/stars/Bhanunamikaze/Agentic-SEO-Skill?style=social) ![Last commit](https://img.shields.io/github/last-commit/Bhanunamikaze/Agentic-SEO-Skill) ![Domain](https://img.shields.io/badge/Domain-SEO-yellow)

LLM-first SEO analysis skill for Antigravity, Codex, and Claude — 16 specialized sub-skills, 10 specialist agents, and 33 utility scripts.

---

#### [marketingskills](https://github.com/coreyhaines31/marketingskills)

![Stars](https://img.shields.io/github/stars/coreyhaines31/marketingskills?style=social) ![Last commit](https://img.shields.io/github/last-commit/coreyhaines31/marketingskills) ![Domain](https://img.shields.io/badge/Domain-Marketing-yellow)

Marketing skills for Claude Code and AI agents — CRO, copywriting, SEO, analytics, and growth engineering.

---

#### [seo-geo-claude-skills](https://github.com/aaron-he-zhu/seo-geo-claude-skills)

![Stars](https://img.shields.io/github/stars/aaron-he-zhu/seo-geo-claude-skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/aaron-he-zhu/seo-geo-claude-skills) ![Domain](https://img.shields.io/badge/Domain-SEO-yellow)

20 SEO & GEO skills for Claude Code, Cursor, Codex, and 35+ AI agents — keyword research, content writing, technical audits, rank tracking using CORE-EEAT + CITE frameworks.

---

### Research & Science

#### [AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs)

![Stars](https://img.shields.io/github/stars/Orchestra-Research/AI-Research-SKILLs?style=social) ![Last commit](https://img.shields.io/github/last-commit/Orchestra-Research/AI-Research-SKILLs) ![Domain](https://img.shields.io/badge/Domain-Research-yellow)

Open-source library of AI research and engineering skills — turns any coding agent into a full-horsepower research agent.

---

#### [claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills)

![Stars](https://img.shields.io/github/stars/K-Dense-AI/claude-scientific-skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/K-Dense-AI/claude-scientific-skills) ![Domain](https://img.shields.io/badge/Domain-Science-yellow)

Ready-to-use Agent Skills for research, science, engineering, analysis, finance, and writing.

---

### Frontend / Design Taste

#### [astro-dev-skill](https://github.com/gigio1023/astro-dev-skill)

![Stars](https://img.shields.io/github/stars/gigio1023/astro-dev-skill?style=social) ![Last commit](https://img.shields.io/github/last-commit/gigio1023/astro-dev-skill) ![Domain](https://img.shields.io/badge/Domain-Frontend-yellow)

Agent skill for Astro web development — prevents outdated Astro 3/4/5 patterns, covers Tailwind v4, Content Collections v3, MDX, and React islands.

---

#### [taste-skill](https://github.com/Leonxlnx/taste-skill)

![Stars](https://img.shields.io/github/stars/Leonxlnx/taste-skill?style=social) ![Last commit](https://img.shields.io/github/last-commit/Leonxlnx/taste-skill) ![Domain](https://img.shields.io/badge/Domain-Frontend-yellow)

High-agency frontend skill that gives AI good taste — stops agents from generating boring, generic "slop".

---

### Generative Media

#### [Generative-Media-Skills](https://github.com/SamurAIGPT/Generative-Media-Skills)

![Stars](https://img.shields.io/github/stars/SamurAIGPT/Generative-Media-Skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/SamurAIGPT/Generative-Media-Skills) ![Domain](https://img.shields.io/badge/Domain-Media-yellow)

Multi-modal generative media skills for Claude Code, Cursor, and Gemini CLI — image, video, and audio generation via muapi.ai.

---

### Mobile / Android

#### [awesome-android-agent-skills](https://github.com/new-silvermoon/awesome-android-agent-skills)

![Stars](https://img.shields.io/github/stars/new-silvermoon/awesome-android-agent-skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/new-silvermoon/awesome-android-agent-skills) ![Domain](https://img.shields.io/badge/Domain-Android-yellow)

Standardized Agent Skills that teach Copilot, Claude, Gemini, and Cursor modern Android development (Kotlin, Jetpack Compose).

---

### Social Media

#### [social-push](https://github.com/jihe520/social-push)

![Stars](https://img.shields.io/github/stars/jihe520/social-push?style=social) ![Last commit](https://img.shields.io/github/last-commit/jihe520/social-push) ![Domain](https://img.shields.io/badge/Domain-Social-yellow)

AI social-media automation skill with self-evolution workflows.

---

### Business & Startup

#### [startup-skill](https://github.com/ferdinandobons/startup-skill)

![Stars](https://img.shields.io/github/stars/ferdinandobons/startup-skill?style=social) ![Last commit](https://img.shields.io/github/last-commit/ferdinandobons/startup-skill) ![Domain](https://img.shields.io/badge/Domain-Startup-yellow)

AI agent skills for startup validation, competitive intelligence, and planning — works with Claude Code.

---

## 5. Skill Tooling & Builders

Loaders, creators, and skills-that-create-skills.

#### [agent-skill-creator](https://github.com/FrancyJGLisboa/agent-skill-creator)

![Stars](https://img.shields.io/github/stars/FrancyJGLisboa/agent-skill-creator?style=social) ![Last commit](https://img.shields.io/github/last-commit/FrancyJGLisboa/agent-skill-creator)

Turn any workflow into reusable skills that install on 14+ tools (Claude Code, Copilot, Cursor, Windsurf, Codex, Gemini, Kiro…). One `SKILL.md`, every platform.

---

#### [astro-skills](https://github.com/FredKSchott/astro-skills)

![Stars](https://img.shields.io/github/stars/FredKSchott/astro-skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/FredKSchott/astro-skills)

Load and serve Agent Skills from your Astro site, automatically.

---

#### [claude-workflow-v2](https://github.com/CloudAI-X/claude-workflow-v2)

![Stars](https://img.shields.io/github/stars/CloudAI-X/claude-workflow-v2?style=social) ![Last commit](https://img.shields.io/github/last-commit/CloudAI-X/claude-workflow-v2)

Universal Claude Code workflow plugin bundling agents, skills, hooks, and commands.

---

#### [harness](https://github.com/revfactory/harness)

![Stars](https://img.shields.io/github/stars/revfactory/harness?style=social) ![Last commit](https://img.shields.io/github/last-commit/revfactory/harness)

Meta-skill that designs domain-specific agent teams, defines specialized agents, and generates the skills they use.

---

#### [openskills](https://github.com/numman-ali/openskills)

![Stars](https://img.shields.io/github/stars/numman-ali/openskills?style=social) ![Last commit](https://img.shields.io/github/last-commit/numman-ali/openskills)

Universal skills loader for AI coding agents (`npm i -g openskills`).

---

#### [refly](https://github.com/refly-ai/refly)

![Stars](https://img.shields.io/github/stars/refly-ai/refly?style=social) ![Last commit](https://img.shields.io/github/last-commit/refly-ai/refly)

Open-source agent skills builder — define skills by vibe workflow, run on Claude Code, Cursor, Codex and more.

---

#### [skillkit](https://github.com/rohitg00/skillkit)

![Stars](https://img.shields.io/github/stars/rohitg00/skillkit?style=social) ![Last commit](https://img.shields.io/github/last-commit/rohitg00/skillkit)

Supercharge AI coding agents with portable skills — install, translate, and share skills across Claude Code, Cursor, Codex, Copilot, and 40+ more.

---

#### [skillport](https://github.com/gotalab/skillport)

![Stars](https://img.shields.io/github/stars/gotalab/skillport?style=social) ![Last commit](https://img.shields.io/github/last-commit/gotalab/skillport)

Bring Agent Skills to any AI or coding agent via CLI or MCP — manage once, serve anywhere.

---

#### [Skill Seekers](https://github.com/yusufkaraaslan/Skill_Seekers)

![Stars](https://img.shields.io/github/stars/yusufkaraaslan/Skill_Seekers?style=social) ![Last commit](https://img.shields.io/github/last-commit/yusufkaraaslan/Skill_Seekers)

Convert documentation websites, GitHub repositories, and PDFs into Claude AI skills with automatic conflict detection.

---

## 6. Skill Registries & Hubs

#### [buildwithclaude](https://github.com/davepoon/buildwithclaude)

![Stars](https://img.shields.io/github/stars/davepoon/buildwithclaude?style=social) ![Last commit](https://img.shields.io/github/last-commit/davepoon/buildwithclaude)

Single hub to find Claude Skills, Agents, Commands, Hooks, Plugins, and Marketplace collections for Claude Code, Claude Desktop, Agent SDK, and OpenClaw.

---

#### [skillhub](https://github.com/iflytek/skillhub)

![Stars](https://img.shields.io/github/stars/iflytek/skillhub?style=social) ![Last commit](https://img.shields.io/github/last-commit/iflytek/skillhub)

Self-hosted, open-source agent skill registry for enterprises — publish & version skill packages with RBAC, audit logs, and Docker/Kubernetes deployment.

---

## 7. Frameworks & Orchestration

Frameworks where skills are first-class primitives.

#### [oh-my-agent](https://github.com/first-fluke/oh-my-agent)

![Stars](https://img.shields.io/github/stars/first-fluke/oh-my-agent?style=social) ![Last commit](https://img.shields.io/github/last-commit/first-fluke/oh-my-agent)

Portable multi-agent harness for `.agents`-based skills, workflows, and standards-aware agent teams across Antigravity, Claude Code, Codex, OpenCode, and more.

---

#### [openakita](https://github.com/openakita/openakita)

![Stars](https://img.shields.io/github/stars/openakita/openakita?style=social) ![Last commit](https://img.shields.io/github/last-commit/openakita/openakita)

Open-source AI assistant framework with skills and agent architecture.

---

## 8. Memory & Context

Skill persistence, reuse, and context infrastructure.

#### [Acontext](https://github.com/memodb-io/Acontext)

![Stars](https://img.shields.io/github/stars/memodb-io/Acontext?style=social) ![Last commit](https://img.shields.io/github/last-commit/memodb-io/Acontext)

Agent Skills as a memory layer.

---

#### [AgentHandover](https://github.com/sandroandric/AgentHandover)

![Stars](https://img.shields.io/github/stars/sandroandric/AgentHandover?style=social) ![Last commit](https://img.shields.io/github/last-commit/sandroandric/AgentHandover)

Observes the user, learns their workflows, and teaches agents (OpenClaw, Claude Code, Codex…) via self-improving skills.

---

#### [MemOS](https://github.com/MemTensor/MemOS)

![Stars](https://img.shields.io/github/stars/MemTensor/MemOS?style=social) ![Last commit](https://img.shields.io/github/last-commit/MemTensor/MemOS)

AI memory OS for LLM and agent systems — persistent skill memory for cross-task skill reuse and evolution.

---

#### [OpenViking](https://github.com/volcengine/OpenViking)

![Stars](https://img.shields.io/github/stars/volcengine/OpenViking?style=social) ![Last commit](https://img.shields.io/github/last-commit/volcengine/OpenViking)

Open-source context database for AI agents — unifies memory, resources, and skills through a filesystem paradigm.

---

## 9. Benchmarks

#### [skillsbench](https://github.com/benchflow-ai/skillsbench)

![Stars](https://img.shields.io/github/stars/benchflow-ai/skillsbench?style=social) ![Last commit](https://img.shields.io/github/last-commit/benchflow-ai/skillsbench)

Evaluates how well skills work and how effectively agents use them.

---

## 10. Specifications

#### [agentskills](https://github.com/agentskills/agentskills)

![Stars](https://img.shields.io/github/stars/agentskills/agentskills?style=social) ![Last commit](https://img.shields.io/github/last-commit/agentskills/agentskills)

Specification and documentation for Agent Skills (SOPEC reference).

---

## 11. Wallets & Crypto

#### [agentic-wallet-skills](https://github.com/coinbase/agentic-wallet-skills)

![Stars](https://img.shields.io/github/stars/coinbase/agentic-wallet-skills?style=social) ![Last commit](https://img.shields.io/github/last-commit/coinbase/agentic-wallet-skills) ![Type](https://img.shields.io/badge/Type-1st--party-blue)

Coinbase agentic wallet skills (`npx skills add coinbase/agentic-wallet-skills`).

---

#### [binance-skills-hub](https://github.com/binance/binance-skills-hub)

![Stars](https://img.shields.io/github/stars/binance/binance-skills-hub?style=social) ![Last commit](https://img.shields.io/github/last-commit/binance/binance-skills-hub) ![Type](https://img.shields.io/badge/Type-1st--party-blue)

Open skills marketplace giving AI agents native access to crypto.

---

## 12. Skill Security

#### [agent-skills-guard](https://github.com/bruc3van/agent-skills-guard)

![Stars](https://img.shields.io/github/stars/bruc3van/agent-skills-guard?style=social) ![Last commit](https://img.shields.io/github/last-commit/bruc3van/agent-skills-guard)

Desktop application that provides security scanning and visual management for Agent Skills.

---

#### [agentguard](https://github.com/GoPlusSecurity/agentguard)

![Stars](https://img.shields.io/github/stars/GoPlusSecurity/agentguard?style=social) ![Last commit](https://img.shields.io/github/last-commit/GoPlusSecurity/agentguard)

Security guard for AI agents — blocks malicious skills, prevents data leaks, protects secrets via 24 detection rules, runtime action evaluation, and a trust registry.

---

## Related Resource Lists

- [Local-AI-Agent-Resources](https://github.com/danielrosehill/Local-AI-Agent-Resources) — on-device agent runners, harnesses, and tooling.

## Contributing

Suggestions welcome via issue or PR. See [SCOPE.md](./SCOPE.md) before submitting.

## Disclaimer

Entries here are references for exploration. Inclusion is not an endorsement — verify licenses, security, and fitness for your use case before adopting any skill.
