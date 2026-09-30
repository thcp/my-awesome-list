# My Awesome List [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A personal, curated catalog of repositories I've found genuinely good, organized by category.

## Contents

- [AI Agents & Memory](#ai-agents--memory)
- [Agent Skills](#agent-skills)
- [AI Models & LLM Tooling](#ai-models--llm-tooling)
- [Music & Audio AI](#music--audio-ai)
- [Research Papers](#research-papers)
- [Security](#security)
- [Compliance & GRC](#compliance--grc)
- [AI Pentesting](#ai-pentesting)
- [Agent Security](#agent-security)
- [Code Review](#code-review)
- [Observability & Networking](#observability--networking)
- [Self-Hosting & Home Lab](#self-hosting--home-lab)
- [Developer Tools](#developer-tools)
- [Learning Resources](#learning-resources)
- [Other Awesome Lists](#other-awesome-lists)
- [Miscellaneous](#miscellaneous)

---

## AI Agents & Memory

| Repo | Stars | Description | How this helps |
|---|---|---|---|
| [hindsight](https://github.com/vectorize-io/hindsight) | [![Stars](https://img.shields.io/github/stars/vectorize-io/hindsight?style=flat&label=%E2%98%85)](https://github.com/vectorize-io/hindsight/stargazers) | Agent memory that learns. | Gives agents long-term memory that improves over time, so they don't start from zero every session. |
| [financial-services](https://github.com/anthropics/financial-services) | [![Stars](https://img.shields.io/github/stars/anthropics/financial-services?style=flat&label=%E2%98%85)](https://github.com/anthropics/financial-services/stargazers) | Anthropic's reference agents, skills, and data connectors for investment banking, equity research, private equity, and wealth management. | Ready-made starting points for finance workflows (comps, DCF, earnings reviews, reconciliations) and a solid reference for structuring agent plugins. |
| [openclaw-reference-setup](https://github.com/Atlas-Cowork/openclaw-reference-setup) | [![Stars](https://img.shields.io/github/stars/Atlas-Cowork/openclaw-reference-setup?style=flat&label=%E2%98%85)](https://github.com/Atlas-Cowork/openclaw-reference-setup/stargazers) | Production-grade, security-hardened OpenClaw setup with 15+ custom tools. | A proven blueprint for running OpenClaw safely instead of wiring it up from scratch. |
| [agency-agents](https://github.com/msitarzewski/agency-agents) | [![Stars](https://img.shields.io/github/stars/msitarzewski/agency-agents?style=flat&label=%E2%98%85)](https://github.com/msitarzewski/agency-agents/stargazers) | A complete AI agency: specialized agents from frontend to community management. | Drop-in agent personas for many roles, so you can delegate whole workstreams. |
| [claude-mem](https://github.com/thedotmack/claude-mem) | [![Stars](https://img.shields.io/github/stars/thedotmack/claude-mem?style=flat&label=%E2%98%85)](https://github.com/thedotmack/claude-mem/stargazers) | Persistent context across sessions for every agent. | Captures what your agent did and feeds it back, so later sessions keep the context. |
| [mempalace](https://github.com/MemPalace/mempalace) | [![Stars](https://img.shields.io/github/stars/MemPalace/mempalace?style=flat&label=%E2%98%85)](https://github.com/MemPalace/mempalace/stargazers) | Best-benchmarked open-source AI memory system. | A free, high-accuracy memory layer for agents and assistants. |
| [supermemory](https://github.com/supermemoryai/supermemory) | [![Stars](https://img.shields.io/github/stars/supermemoryai/supermemory?style=flat&label=%E2%98%85)](https://github.com/supermemoryai/supermemory/stargazers) | Fast, scalable memory and context engine that can run fully locally. | Adds long-term memory to AI apps without sending data to a third party. |
| [graphify](https://github.com/Graphify-Labs/graphify) | [![Stars](https://img.shields.io/github/stars/Graphify-Labs/graphify?style=flat&label=%E2%98%85)](https://github.com/Graphify-Labs/graphify/stargazers) | Turns a codebase, docs, SQL schemas, configs, and PDFs into a queryable knowledge graph. | Gives agents structured understanding of large projects instead of blind grepping. |
| [repowise](https://github.com/repowise-dev/repowise) | [![Stars](https://img.shields.io/github/stars/repowise-dev/repowise?style=flat&label=%E2%98%85)](https://github.com/repowise-dev/repowise/stargazers) | Codebase intelligence: health scores, auto-generated docs, git analytics. | Quickly understand an unfamiliar repo, for you or your agent. |
| [n8n-mcp](https://github.com/czlonkowski/n8n-mcp) | [![Stars](https://img.shields.io/github/stars/czlonkowski/n8n-mcp?style=flat&label=%E2%98%85)](https://github.com/czlonkowski/n8n-mcp/stargazers) | MCP server that lets Claude, Cursor, and others build n8n workflows. | Describe an automation in plain language and get a working n8n workflow. |
| [CodeShellManager](https://github.com/umage-ai/CodeShellManager) | [![Stars](https://img.shields.io/github/stars/umage-ai/CodeShellManager?style=flat&label=%E2%98%85)](https://github.com/umage-ai/CodeShellManager/stargazers) | Workspace manager for AI coding shells and agents. | Keeps many parallel agent sessions organized in one place. |

## Agent Skills

| Repo | Stars | Description | How this helps |
|---|---|---|---|
| [archify](https://github.com/tt-a1i/archify) | [![Stars](https://img.shields.io/github/stars/tt-a1i/archify?style=flat&label=%E2%98%85)](https://github.com/tt-a1i/archify/stargazers) | Agent skill for architecture, workflow, sequence, data-flow, and lifecycle diagrams as self-contained HTML. | Lets your coding agent produce clean, exportable diagrams straight from code or a description — no manual diagramming. |
| [i-have-adhd](https://github.com/ayghri/i-have-adhd) | [![Stars](https://img.shields.io/github/stars/ayghri/i-have-adhd?style=flat&label=%E2%98%85)](https://github.com/ayghri/i-have-adhd/stargazers) | Skill that stops your coding agent from burying the answer; ADHD-friendly output. | Makes agent responses lead with the answer and stay scannable, cutting noise and reading time. |
| [agent-skills (addyosmani)](https://github.com/addyosmani/agent-skills) | [![Stars](https://img.shields.io/github/stars/addyosmani/agent-skills?style=flat&label=%E2%98%85)](https://github.com/addyosmani/agent-skills/stargazers) | Production-grade engineering skills for AI coding agents. | Raises the baseline quality of what your agent ships: testing, performance, accessibility, and more. |
| [ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | [![Stars](https://img.shields.io/github/stars/nextlevelbuilder/ui-ux-pro-max-skill?style=flat&label=%E2%98%85)](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill/stargazers) | Design intelligence for building professional UI/UX across platforms. | Makes agent-built interfaces look designed rather than generic. |
| [obsidian-skills](https://github.com/kepano/obsidian-skills) | [![Stars](https://img.shields.io/github/stars/kepano/obsidian-skills?style=flat&label=%E2%98%85)](https://github.com/kepano/obsidian-skills/stargazers) | Agent skills for the Obsidian CLI and its open formats. | Lets your agent read, write, and organize your Obsidian vault correctly. |
| [agent-skills (actuated)](https://github.com/self-actuated/agent-skills) | [![Stars](https://img.shields.io/github/stars/self-actuated/agent-skills?style=flat&label=%E2%98%85)](https://github.com/self-actuated/agent-skills/stargazers) | Agent skills for actuated. | Teaches agents to work with actuated's CI runners. |

## AI Models & LLM Tooling

| Repo | Stars | Description | How this helps |
|---|---|---|---|
| [spec-kit](https://github.com/github/spec-kit) | [![Stars](https://img.shields.io/github/stars/github/spec-kit?style=flat&label=%E2%98%85)](https://github.com/github/spec-kit/stargazers) | GitHub's toolkit for spec-driven development. | Structures AI coding around specs and plans, so agents build what you actually meant. |
| [OmniRoute](https://github.com/diegosouzapw/OmniRoute) | [![Stars](https://img.shields.io/github/stars/diegosouzapw/OmniRoute?style=flat&label=%E2%98%85)](https://github.com/diegosouzapw/OmniRoute/stargazers) | Free AI gateway: one endpoint for 359 providers and 1200+ models. | Swap or fall back between models and providers without changing your code. |
| [colibri](https://github.com/JustVugg/colibri) | [![Stars](https://img.shields.io/github/stars/JustVugg/colibri?style=flat&label=%E2%98%85)](https://github.com/JustVugg/colibri/stargazers) | Runs frontier MoE models on existing hardware in pure C with zero dependencies. | Run big models locally without a high-end GPU. |
| [airllm](https://github.com/lyogavin/airllm) | [![Stars](https://img.shields.io/github/stars/lyogavin/airllm?style=flat&label=%E2%98%85)](https://github.com/lyogavin/airllm/stargazers) | 70B model inference on a single 4GB GPU. | Makes large models usable on modest hardware. |
| [lightpanda browser](https://github.com/lightpanda-io/browser) | [![Stars](https://img.shields.io/github/stars/lightpanda-io/browser?style=flat&label=%E2%98%85)](https://github.com/lightpanda-io/browser/stargazers) | Headless browser designed for AI and automation. | Much faster, lighter web automation for agents and scrapers than headless Chrome. |
| [whisper](https://github.com/openai/whisper) | [![Stars](https://img.shields.io/github/stars/openai/whisper?style=flat&label=%E2%98%85)](https://github.com/openai/whisper/stargazers) | Robust speech recognition. | Accurate, multilingual transcription you can run locally. |
| [Fooocus](https://github.com/lllyasviel/Fooocus) | [![Stars](https://img.shields.io/github/stars/lllyasviel/Fooocus?style=flat&label=%E2%98%85)](https://github.com/lllyasviel/Fooocus/stargazers) | Image generation focused on prompting. | High-quality image generation with minimal tuning. |
| [FluxRT](https://github.com/tensorforger/FluxRT) | [![Stars](https://img.shields.io/github/stars/tensorforger/FluxRT?style=flat&label=%E2%98%85)](https://github.com/tensorforger/FluxRT/stargazers) | Real-time stream editing pipeline powered by FLUX.2-klein-4B. | Live AI video and stream effects on consumer GPUs. |

## Music & Audio AI

| Repo | Stars | Description | How this helps |
|---|---|---|---|
| [bark](https://github.com/suno-ai/bark) | [![Stars](https://img.shields.io/github/stars/suno-ai/bark?style=flat&label=%E2%98%85)](https://github.com/suno-ai/bark/stargazers) | Suno's text-prompted generative audio model. | Generates speech, music snippets, and sound effects from text. |
| [voice-pro](https://github.com/abus-aikorea/voice-pro) | [![Stars](https://img.shields.io/github/stars/abus-aikorea/voice-pro?style=flat&label=%E2%98%85)](https://github.com/abus-aikorea/voice-pro/stargazers) | Web UI for TTS and zero-shot voice cloning. | One interface for TTS, voice cloning, and dubbing. |
| [MisoTTS](https://github.com/MisoLabsAI/MisoTTS) | [![Stars](https://img.shields.io/github/stars/MisoLabsAI/MisoTTS?style=flat&label=%E2%98%85)](https://github.com/MisoLabsAI/MisoTTS/stargazers) | 8B highly emotive text-to-speech model. | Expressive, natural-sounding voices for narration and vocals. |
| [demucs](https://github.com/adefossez/demucs) | [![Stars](https://img.shields.io/github/stars/adefossez/demucs?style=flat&label=%E2%98%85)](https://github.com/adefossez/demucs/stargazers) | Hybrid spectrogram/waveform music source separation. | Splits a mix into stems (vocals, drums, bass, other) for remixing and practice. |
| [NeuralNote](https://github.com/DamRsn/NeuralNote) | [![Stars](https://img.shields.io/github/stars/DamRsn/NeuralNote?style=flat&label=%E2%98%85)](https://github.com/DamRsn/NeuralNote/stargazers) | Audio plugin for audio-to-MIDI transcription. | Turns a recorded part into editable MIDI right in your DAW. |
| [mt3](https://github.com/magenta/mt3) | [![Stars](https://img.shields.io/github/stars/magenta/mt3?style=flat&label=%E2%98%85)](https://github.com/magenta/mt3/stargazers) | Multi-task multitrack music transcription. | Transcribes full multi-instrument recordings to MIDI. |
| [all-in-one](https://github.com/mir-aidj/all-in-one) | [![Stars](https://img.shields.io/github/stars/mir-aidj/all-in-one?style=flat&label=%E2%98%85)](https://github.com/mir-aidj/all-in-one/stargazers) | All-in-one music structure analyzer. | Detects tempo, beats, downbeats, and sections (verse, chorus) automatically. |
| [LiveChord](https://github.com/JJ110112/LiveChord) | [![Stars](https://img.shields.io/github/stars/JJ110112/LiveChord?style=flat&label=%E2%98%85)](https://github.com/JJ110112/LiveChord/stargazers) | Turns an audio file into a real-time, playable chord chart. | Practice songs with synced chords, transpose, A-B loop, and slow-down. |
| [lyrics.ovh](https://github.com/NTag/lyrics.ovh) | [![Stars](https://img.shields.io/github/stars/NTag/lyrics.ovh?style=flat&label=%E2%98%85)](https://github.com/NTag/lyrics.ovh/stargazers) | Source and API for searching song lyrics. | A simple lyrics API for music apps. |

## Research Papers

| Paper | Description | How this helps |
|---|---|---|
| [Music Source Separation in the Waveform Domain](https://arxiv.org/abs/1911.13254) (Défossez et al., 2019) | The original Demucs: a waveform-to-waveform model for separating music into stems. | The foundation of Demucs. |
| [Hybrid Spectrogram and Waveform Source Separation](https://arxiv.org/abs/2111.03600) (Défossez, 2021) | Hybrid Demucs: processes the spectrogram and the raw waveform together. | Explains why Demucs separates better than pure-spectrogram or pure-waveform models. |
| [Hybrid Transformers for Music Source Separation](https://arxiv.org/abs/2211.08553) (Rouard, Massa, Défossez, 2022) | HT Demucs: adds a cross-domain transformer to Hybrid Demucs. | The architecture behind `htdemucs_6s`, a 6-stem separation model. |
| [KUIELab-MDX-Net: A Two-Stream Neural Network for Music Demixing](https://arxiv.org/abs/2111.12203) (Kim et al., 2021) | Two-stream demixing network that placed highly in the Music Demixing Challenge. | The MDX-Net family behind the UVR karaoke models that split lead and backing vocals. |
| [Beat Tracking by Dynamic Programming](https://doi.org/10.1080/09298210701653344) (Ellis, 2007) | Finds beats by dynamic programming over an onset-strength signal. | The approach behind librosa's beat tracker, used for BPM detection. |
| [pyloudnorm: A simple yet flexible loudness meter in Python](https://csteinmetz1.github.io/pyloudnorm-eval/paper/pyloudnorm_preprint.pdf) (Steinmetz & Reiss, AES 150th Convention, 2021) | Open-source implementation of the ITU-R BS.1770 loudness standard, with an evaluation. | A reference for measuring integrated loudness (LUFS). |
| [The Use of Large Corpora to Train a New Type of Key-Finding Algorithm](https://doi.org/10.1525/mp.2013.31.1.59) (Albrecht & Shanahan, *Music Perception*, 2013) | Key-finding profiles trained on a large corpus of music. | The key and scale profiles used for key detection. |

## Security

| Repo | Stars | Description | How this helps |
|---|---|---|---|
| [security-audit-skill](https://github.com/cloudflare/security-audit-skill) | [![Stars](https://img.shields.io/github/stars/cloudflare/security-audit-skill?style=flat&label=%E2%98%85)](https://github.com/cloudflare/security-audit-skill/stargazers) | Coding-agent skill for multi-phase security audits with independently verified, machine-readable findings. | Turns your agent into a structured security auditor with fewer false positives and findings you can feed into other tools. |
| [trailofbits/skills](https://github.com/trailofbits/skills) | [![Stars](https://img.shields.io/github/stars/trailofbits/skills?style=flat&label=%E2%98%85)](https://github.com/trailofbits/skills/stargazers) | Trail of Bits' Claude Code skills for security research, vulnerability detection, and audit workflows. | Brings a top security firm's audit know-how straight into your coding agent. |
| [semgrep/mcp](https://github.com/semgrep/mcp) | [![Stars](https://img.shields.io/github/stars/semgrep/mcp?style=flat&label=%E2%98%85)](https://github.com/semgrep/mcp/stargazers) | MCP server for scanning code with Semgrep. | Lets any MCP-compatible agent run static analysis and catch vulnerabilities while it writes code. |
| [infisical](https://github.com/Infisical/infisical) | [![Stars](https://img.shields.io/github/stars/Infisical/infisical?style=flat&label=%E2%98%85)](https://github.com/Infisical/infisical/stargazers) | Open-source platform for secrets, certificates, and privileged access management. | Takes secrets out of `.env` files and repos, with rotation and access control. |

## Compliance & GRC

| Repo | Stars | Description | How this helps |
|---|---|---|---|
| [probo](https://github.com/getprobo/probo) | [![Stars](https://img.shields.io/github/stars/getprobo/probo?style=flat&label=%E2%98%85)](https://github.com/getprobo/probo/stargazers) | Self-hostable GRC platform for SOC 2, ISO 27001, and GDPR with 270+ MCP tools. | Agents can draft policies, run risk assessments, and generate audit evidence packs directly against your compliance data. |
| [prowler](https://github.com/prowler-cloud/prowler) | [![Stars](https://img.shields.io/github/stars/prowler-cloud/prowler?style=flat&label=%E2%98%85)](https://github.com/prowler-cloud/prowler/stargazers) | Open-source cloud security platform for AWS, Azure, GCP, and Kubernetes, with its own MCP server and Claude plugin. | Automates cloud security checks and produces SOC 2 / ISO / CIS compliance reports agents can query and act on. |
| [ciso-assistant-community](https://github.com/intuitem/ciso-assistant-community) | [![Stars](https://img.shields.io/github/stars/intuitem/ciso-assistant-community?style=flat&label=%E2%98%85)](https://github.com/intuitem/ciso-assistant-community/stargazers) | One-stop GRC platform: risk, AppSec, compliance & audit, TPRM, with 100+ frameworks and MCP support. | A full open-source alternative to paid GRC tools, with framework mappings done for you. |
| [Claude-Skills-Governance-Risk-and-Compliance](https://github.com/Sushegaad/Claude-Skills-Governance-Risk-and-Compliance) | [![Stars](https://img.shields.io/github/stars/Sushegaad/Claude-Skills-Governance-Risk-and-Compliance?style=flat&label=%E2%98%85)](https://github.com/Sushegaad/Claude-Skills-Governance-Risk-and-Compliance/stargazers) | Claude skills for GRC: ISO 27001, SOC 2, and more. | Gives your agent expert-level compliance guidance for audit prep and control design. |

## AI Pentesting

| Repo | Stars | Description | How this helps |
|---|---|---|---|
| [strix](https://github.com/usestrix/strix) | [![Stars](https://img.shields.io/github/stars/usestrix/strix?style=flat&label=%E2%98%85)](https://github.com/usestrix/strix/stargazers) | Open-source AI penetration testing tool. | Autonomous agents find real, validated vulnerabilities in your app and help fix them. |
| [shannon](https://github.com/KeygraphHQ/shannon) | [![Stars](https://img.shields.io/github/stars/KeygraphHQ/shannon?style=flat&label=%E2%98%85)](https://github.com/KeygraphHQ/shannon/stargazers) | AI pentester for web applications and APIs. | Combines source-code analysis with live attacks against the running app to prove exploitability. |

## Agent Security

| Repo | Stars | Description | How this helps |
|---|---|---|---|
| [SkillSpector](https://github.com/NVIDIA/SkillSpector) | [![Stars](https://img.shields.io/github/stars/NVIDIA/SkillSpector?style=flat&label=%E2%98%85)](https://github.com/NVIDIA/SkillSpector/stargazers) | Security scanner for AI agent skills (Claude Code, Codex, MCP). | Vets third-party skills for prompt injection, data exfiltration, and supply-chain risks *before* you install them. |
| [agent-scan](https://github.com/snyk/agent-scan) | [![Stars](https://img.shields.io/github/stars/snyk/agent-scan?style=flat&label=%E2%98%85)](https://github.com/snyk/agent-scan/stargazers) | Security scanner for AI agents, MCP servers, and agent skills. | Audits your whole agent setup for tool poisoning, prompt injection, and risky configurations. |
| [mcp-scanner](https://github.com/cisco-ai-defense/mcp-scanner) | [![Stars](https://img.shields.io/github/stars/cisco-ai-defense/mcp-scanner?style=flat&label=%E2%98%85)](https://github.com/cisco-ai-defense/mcp-scanner/stargazers) | Scans MCP servers for threats and security findings. | Checks MCP servers before you connect them to your agents. |
| [promptfoo](https://github.com/promptfoo/promptfoo) | [![Stars](https://img.shields.io/github/stars/promptfoo/promptfoo?style=flat&label=%E2%98%85)](https://github.com/promptfoo/promptfoo/stargazers) | Testing and red-teaming for prompts, agents, and RAG. | Red-teams your own AI apps for jailbreaks, injection, and data leaks, and catches regressions in CI. |

## Code Review

| Repo | Stars | Description | How this helps |
|---|---|---|---|
| [open-code-review](https://github.com/alibaba/open-code-review) | [![Stars](https://img.shields.io/github/stars/alibaba/open-code-review?style=flat&label=%E2%98%85)](https://github.com/alibaba/open-code-review/stargazers) | Hybrid code review tool (deterministic pipelines + LLM agent) with line-level comments and a built-in multi-language ruleset. | Automates PR review with precise, line-level feedback on real bug classes (NPE, thread-safety, XSS, SQL injection); works with OpenAI and Anthropic models. |

## Observability & Networking

| Repo | Stars | Description | How this helps |
|---|---|---|---|
| [Logstalgia](https://github.com/acaudwell/Logstalgia) | [![Stars](https://img.shields.io/github/stars/acaudwell/Logstalgia?style=flat&label=%E2%98%85)](https://github.com/acaudwell/Logstalgia/stargazers) | Replays or streams web access logs as a retro arcade game. | A fun, surprisingly useful way to see traffic patterns. |

## Self-Hosting & Home Lab

| Repo | Stars | Description | How this helps |
|---|---|---|---|
| [restic](https://github.com/restic/restic) | [![Stars](https://img.shields.io/github/stars/restic/restic?style=flat&label=%E2%98%85)](https://github.com/restic/restic/stargazers) | Fast, secure, efficient backup program. | Encrypted, deduplicated backups to almost any storage backend. |
| [postiz-app](https://github.com/gitroomhq/postiz-app) | [![Stars](https://img.shields.io/github/stars/gitroomhq/postiz-app?style=flat&label=%E2%98%85)](https://github.com/gitroomhq/postiz-app/stargazers) | Agentic social media scheduling tool. | A self-hosted alternative to Buffer and Hootsuite, with AI help. |

## Developer Tools

| Repo | Stars | Description | How this helps |
|---|---|---|---|
| [atuin](https://github.com/atuinsh/atuin) | [![Stars](https://img.shields.io/github/stars/atuinsh/atuin?style=flat&label=%E2%98%85)](https://github.com/atuinsh/atuin/stargazers) | Magical shell history. | Searchable, synced shell history across machines. |

## Learning Resources

| Repo | Stars | Description | How this helps |
|---|---|---|---|
| [hacker-laws](https://github.com/dwmkerr/hacker-laws) | [![Stars](https://img.shields.io/github/stars/dwmkerr/hacker-laws?style=flat&label=%E2%98%85)](https://github.com/dwmkerr/hacker-laws/stargazers) | Laws, theories, principles, and patterns for developers. | Shared vocabulary for engineering trade-offs (Conway, Hyrum, Brooks, and more). |
| [The-HustleGPT-Challenge](https://github.com/jtmuller5/The-HustleGPT-Challenge) | [![Stars](https://img.shields.io/github/stars/jtmuller5/The-HustleGPT-Challenge?style=flat&label=%E2%98%85)](https://github.com/jtmuller5/The-HustleGPT-Challenge/stargazers) | Building startups with an AI co-founder. | Real examples of founders using AI to build businesses. |

## Other Awesome Lists

| Repo | Stars | Description | How this helps |
|---|---|---|---|
| [awesome-mac](https://github.com/jaywcjlove/awesome-mac) | [![Stars](https://img.shields.io/github/stars/jaywcjlove/awesome-mac?style=flat&label=%E2%98%85)](https://github.com/jaywcjlove/awesome-mac/stargazers) | High-quality macOS software. | Find the best Mac app for any job. |
| [awesome-privacy](https://github.com/lissy93/awesome-privacy) | [![Stars](https://img.shields.io/github/stars/lissy93/awesome-privacy?style=flat&label=%E2%98%85)](https://github.com/lissy93/awesome-privacy/stargazers) | Privacy- and security-focused software and services. | Privacy-respecting alternatives for everyday tools. |
| [awesome-musicdsp](https://github.com/olilarkin/awesome-musicdsp) | [![Stars](https://img.shields.io/github/stars/olilarkin/awesome-musicdsp?style=flat&label=%E2%98%85)](https://github.com/olilarkin/awesome-musicdsp/stargazers) | Music DSP and audio programming resources. | Learning path for building audio plugins and DSP. |
| [awesome-music-production](https://github.com/ad-si/awesome-music-production) | [![Stars](https://img.shields.io/github/stars/ad-si/awesome-music-production?style=flat&label=%E2%98%85)](https://github.com/ad-si/awesome-music-production/stargazers) | Software and services to create and distribute music. | Tools for every stage of music production. |

## Miscellaneous

| Repo | Stars | Description | How this helps |
|---|---|---|---|
| [arctic_shift_ui](https://github.com/ArthurHeitmann/arctic_shift_ui) | [![Stars](https://img.shields.io/github/stars/ArthurHeitmann/arctic_shift_ui?style=flat&label=%E2%98%85)](https://github.com/ArthurHeitmann/arctic_shift_ui/stargazers) | Web UI for searching and downloading archived Reddit data. | Search old Reddit content beyond what Reddit's own search shows. |
| [reddit-gems](https://github.com/hoveychen/reddit-gems) | [![Stars](https://img.shields.io/github/stars/hoveychen/reddit-gems?style=flat&label=%E2%98%85)](https://github.com/hoveychen/reddit-gems/stargazers) | Full archive and media browser for r/coolgithubprojects (2014–2026). | A goldmine for discovering interesting projects. |
| [ByteOrder](https://github.com/Matts-Baps/ByteOrder) | [![Stars](https://img.shields.io/github/stars/Matts-Baps/ByteOrder?style=flat&label=%E2%98%85)](https://github.com/Matts-Baps/ByteOrder/stargazers) | Home kitchen ordering system. | A fun self-hosted "restaurant menu" for your household. |
