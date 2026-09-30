# My Awesome List [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A personal, curated catalog of repositories I've found genuinely good, organized by category.

## Contents

- [AI Agents & Memory](#ai-agents--memory)
- [Agent Skills](#agent-skills)
- [AI Models & LLM Tooling](#ai-models--llm-tooling)
- [Music & Audio AI](#music--audio-ai)
- [Security](#security)
- [Compliance & GRC](#compliance--grc)
- [AI Pentesting](#ai-pentesting)
- [Agent Security](#agent-security)
- [Code Review](#code-review)
- [Kubernetes](#kubernetes)
- [Terraform & IaC](#terraform--iac)
- [Docker & CI/CD](#docker--cicd)
- [Observability & Networking](#observability--networking)
- [Self-Hosting & Home Lab](#self-hosting--home-lab)
- [Developer Tools](#developer-tools)
- [Learning Resources](#learning-resources)
- [Other Awesome Lists](#other-awesome-lists)
- [Miscellaneous](#miscellaneous)

---

## AI Agents & Memory

| Repo | Description | How this helps |
|---|---|---|
| [hindsight](https://github.com/vectorize-io/hindsight) | Agent memory that learns. | Gives agents long-term memory that improves over time, so they don't start from zero every session. |
| [financial-services](https://github.com/anthropics/financial-services) | Anthropic's reference agents, skills, and data connectors for investment banking, equity research, private equity, and wealth management. | Ready-made starting points for finance workflows (comps, DCF, earnings reviews, reconciliations) and a solid reference for structuring agent plugins. |
| [openclaw](https://github.com/openclaw/openclaw) | Personal AI assistant that really does things, on any OS and platform. | A self-hosted agent that acts on your behalf across apps and devices, not just chats. |
| [openclaw-reference-setup](https://github.com/Atlas-Cowork/openclaw-reference-setup) | Production-grade, security-hardened OpenClaw setup with 15+ custom tools. | A proven blueprint for running OpenClaw safely instead of wiring it up from scratch. |
| [agency-agents](https://github.com/msitarzewski/agency-agents) | A complete AI agency: specialized agents from frontend to community management. | Drop-in agent personas for many roles, so you can delegate whole workstreams. |
| [goose](https://github.com/aaif-goose/goose) | Open-source, extensible AI agent that installs, executes, edits, and tests. | A local, model-agnostic agent you can extend with MCP tools. |
| [aider](https://github.com/Aider-AI/aider) | AI pair programming in your terminal. | Edits your repo with git-aware commits, working with almost any LLM. |
| [claude-mem](https://github.com/thedotmack/claude-mem) | Persistent context across sessions for every agent. | Captures what your agent did and feeds it back, so later sessions keep the context. |
| [mempalace](https://github.com/MemPalace/mempalace) | Best-benchmarked open-source AI memory system. | A free, high-accuracy memory layer for agents and assistants. |
| [supermemory](https://github.com/supermemoryai/supermemory) | Fast, scalable memory and context engine that can run fully locally. | Adds long-term memory to AI apps without sending data to a third party. |
| [graphify](https://github.com/Graphify-Labs/graphify) | Turns a codebase, docs, SQL schemas, configs, and PDFs into a queryable knowledge graph. | Gives agents structured understanding of large projects instead of blind grepping. |
| [repowise](https://github.com/repowise-dev/repowise) | Codebase intelligence: health scores, auto-generated docs, git analytics. | Quickly understand an unfamiliar repo, for you or your agent. |
| [n8n-mcp](https://github.com/czlonkowski/n8n-mcp) | MCP server that lets Claude, Cursor, and others build n8n workflows. | Describe an automation in plain language and get a working n8n workflow. |
| [CodeShellManager](https://github.com/umage-ai/CodeShellManager) | Workspace manager for AI coding shells and agents. | Keeps many parallel agent sessions organized in one place. |

## Agent Skills

| Repo | Description | How this helps |
|---|---|---|
| [archify](https://github.com/tt-a1i/archify) | Agent skill for architecture, workflow, sequence, data-flow, and lifecycle diagrams as self-contained HTML. | Lets your coding agent produce clean, exportable diagrams straight from code or a description — no manual diagramming. |
| [i-have-adhd](https://github.com/ayghri/i-have-adhd) | Skill that stops your coding agent from burying the answer; ADHD-friendly output. | Makes agent responses lead with the answer and stay scannable, cutting noise and reading time. |
| [agent-skills (addyosmani)](https://github.com/addyosmani/agent-skills) | Production-grade engineering skills for AI coding agents. | Raises the baseline quality of what your agent ships: testing, performance, accessibility, and more. |
| [ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | Design intelligence for building professional UI/UX across platforms. | Makes agent-built interfaces look designed rather than generic. |
| [obsidian-skills](https://github.com/kepano/obsidian-skills) | Agent skills for the Obsidian CLI and its open formats. | Lets your agent read, write, and organize your Obsidian vault correctly. |
| [skill-issue](https://github.com/paultyng/skill-issue) | Personal Claude Code / Cursor skills, rules, and config. | A real-world example of a tuned agent setup to borrow from. |
| [agent-skills (actuated)](https://github.com/self-actuated/agent-skills) | Agent skills for actuated. | Teaches agents to work with actuated's CI runners. |

## AI Models & LLM Tooling

| Repo | Description | How this helps |
|---|---|---|
| [spec-kit](https://github.com/github/spec-kit) | GitHub's toolkit for spec-driven development. | Structures AI coding around specs and plans, so agents build what you actually meant. |
| [OmniRoute](https://github.com/diegosouzapw/OmniRoute) | Free AI gateway: one endpoint for 359 providers and 1200+ models. | Swap or fall back between models and providers without changing your code. |
| [colibri](https://github.com/JustVugg/colibri) | Runs frontier MoE models on existing hardware in pure C with zero dependencies. | Run big models locally without a high-end GPU. |
| [airllm](https://github.com/lyogavin/airllm) | 70B model inference on a single 4GB GPU. | Makes large models usable on modest hardware. |
| [lightpanda browser](https://github.com/lightpanda-io/browser) | Headless browser designed for AI and automation. | Much faster, lighter web automation for agents and scrapers than headless Chrome. |
| [whisper](https://github.com/openai/whisper) | Robust speech recognition. | Accurate, multilingual transcription you can run locally. |
| [timesfm](https://github.com/google-research/timesfm) | Google's pretrained time-series foundation model. | Solid forecasts without training a model per dataset. |
| [Fooocus](https://github.com/lllyasviel/Fooocus) | Image generation focused on prompting. | High-quality image generation with minimal tuning. |
| [FluxRT](https://github.com/tensorforger/FluxRT) | Real-time stream editing pipeline powered by FLUX.2-klein-4B. | Live AI video and stream effects on consumer GPUs. |
| [C2C](https://github.com/thu-nics/C2C) | Cache-to-Cache: direct semantic communication between LLMs (ICLR'26). | Research on letting models share KV-cache instead of text, making multi-model systems faster. |
| [porcupine](https://github.com/Picovoice/porcupine) | On-device wake word detection. | Add "hey assistant"-style voice triggers without cloud calls. |

## Music & Audio AI

| Repo | Description | How this helps |
|---|---|---|
| [bark](https://github.com/suno-ai/bark) | Suno's text-prompted generative audio model. | Generates speech, music snippets, and sound effects from text. |
| [voice-pro](https://github.com/abus-aikorea/voice-pro) | Web UI for TTS and zero-shot voice cloning. | One interface for TTS, voice cloning, and dubbing. |
| [MisoTTS](https://github.com/MisoLabsAI/MisoTTS) | 8B highly emotive text-to-speech model. | Expressive, natural-sounding voices for narration and vocals. |
| [demucs](https://github.com/adefossez/demucs) | Hybrid spectrogram/waveform music source separation. | Splits a mix into stems (vocals, drums, bass, other) for remixing and practice. |
| [NeuralNote](https://github.com/DamRsn/NeuralNote) | Audio plugin for audio-to-MIDI transcription. | Turns a recorded part into editable MIDI right in your DAW. |
| [mt3](https://github.com/magenta/mt3) | Multi-task multitrack music transcription. | Transcribes full multi-instrument recordings to MIDI. |
| [all-in-one](https://github.com/mir-aidj/all-in-one) | All-in-one music structure analyzer. | Detects tempo, beats, downbeats, and sections (verse, chorus) automatically. |
| [openvino-plugins-ai-audacity](https://github.com/intel/openvino-plugins-ai-audacity) | AI effects, generators, and analyzers for Audacity. | Brings stem separation, noise suppression, and transcription into Audacity. |
| [producer-pal](https://github.com/adamjmurray/producer-pal) | AI music production assistant for Ableton Live. | Control and compose in Ableton by talking to an AI. |
| [LiveChord](https://github.com/JJ110112/LiveChord) | Turns an audio file into a real-time, playable chord chart. | Practice songs with synced chords, transpose, A-B loop, and slow-down. |
| [lyrics.ovh](https://github.com/NTag/lyrics.ovh) | Source and API for searching song lyrics. | A simple lyrics API for music apps. |

## Security

| Repo | Description | How this helps |
|---|---|---|
| [security-audit-skill](https://github.com/cloudflare/security-audit-skill) | Coding-agent skill for multi-phase security audits with independently verified, machine-readable findings. | Turns your agent into a structured security auditor with fewer false positives and findings you can feed into other tools. |
| [trailofbits/skills](https://github.com/trailofbits/skills) | Trail of Bits' Claude Code skills for security research, vulnerability detection, and audit workflows. | Brings a top security firm's audit know-how straight into your coding agent. |
| [semgrep/mcp](https://github.com/semgrep/mcp) | MCP server for scanning code with Semgrep. | Lets any MCP-compatible agent run static analysis and catch vulnerabilities while it writes code. |
| [infisical](https://github.com/Infisical/infisical) | Open-source platform for secrets, certificates, and privileged access management. | Takes secrets out of `.env` files and repos, with rotation and access control. |
| [checkov](https://github.com/bridgecrewio/checkov) | Finds cloud misconfigurations and vulnerabilities in IaC at build time. | Catches insecure Terraform, Kubernetes, and CloudFormation before it deploys. |
| [detect-secrets](https://github.com/Yelp/detect-secrets) | Enterprise-friendly secret detection and prevention in code. | Stops credentials from being committed, via a pre-commit hook and a baseline. |
| [sealed-secrets](https://github.com/bitnami/sealed-secrets) | Kubernetes controller for one-way encrypted Secrets. | Lets you safely store Kubernetes secrets in Git for GitOps. |
| [docker-bench-security](https://github.com/docker/docker-bench-security) | Checks dozens of Docker production best practices. | A quick CIS-style audit of your Docker hosts. |
| [kubesec](https://github.com/controlplaneio/kubesec) | Security risk analysis for Kubernetes resources. | Scores manifests for risky settings before you apply them. |
| [red-kube](https://github.com/lightspin-tech/red-kube) | Kubernetes red-team adversary emulation based on kubectl. | Tests your cluster defenses the way an attacker would. |
| [Azure-Sentinel](https://github.com/Azure/Azure-Sentinel) | Microsoft Sentinel detections, hunting queries, and playbooks. | A large library of ready-made detections for SIEM and SOC work. |
| [Azure-Network-Security](https://github.com/Azure/Azure-Network-Security) | Resources for Azure network security. | Templates and guidance for Azure Firewall, WAF, and DDoS protection. |
| [portmaster](https://github.com/safing/portmaster) | Privacy app and firewall that blocks mass surveillance. | See and control every connection your computer makes. |
| [bad-practices](https://github.com/cisagov/bad-practices) | CISA's catalog of exceptionally risky practices. | An authoritative "don't do this" checklist for security reviews. |
| [painless-password-rotation](https://github.com/scarolan/painless-password-rotation) | Easy, secure password rotation for Linux and Windows system accounts. | Automates rotating local admin passwords with Vault. |

## Compliance & GRC

| Repo | Description | How this helps |
|---|---|---|
| [probo](https://github.com/getprobo/probo) | Self-hostable GRC platform for SOC 2, ISO 27001, and GDPR with 270+ MCP tools. | Agents can draft policies, run risk assessments, and generate audit evidence packs directly against your compliance data. |
| [prowler](https://github.com/prowler-cloud/prowler) | Open-source cloud security platform for AWS, Azure, GCP, and Kubernetes, with its own MCP server and Claude plugin. | Automates cloud security checks and produces SOC 2 / ISO / CIS compliance reports agents can query and act on. |
| [ciso-assistant-community](https://github.com/intuitem/ciso-assistant-community) | One-stop GRC platform: risk, AppSec, compliance & audit, TPRM, with 100+ frameworks and MCP support. | A full open-source alternative to paid GRC tools, with framework mappings done for you. |
| [Claude-Skills-Governance-Risk-and-Compliance](https://github.com/Sushegaad/Claude-Skills-Governance-Risk-and-Compliance) | Claude skills for GRC: ISO 27001, SOC 2, and more. | Gives your agent expert-level compliance guidance for audit prep and control design. |

## AI Pentesting

| Repo | Description | How this helps |
|---|---|---|
| [strix](https://github.com/usestrix/strix) | Open-source AI penetration testing tool. | Autonomous agents find real, validated vulnerabilities in your app and help fix them. |
| [shannon](https://github.com/KeygraphHQ/shannon) | AI pentester for web applications and APIs. | Combines source-code analysis with live attacks against the running app to prove exploitability. |

## Agent Security

| Repo | Description | How this helps |
|---|---|---|
| [SkillSpector](https://github.com/NVIDIA/SkillSpector) | Security scanner for AI agent skills (Claude Code, Codex, MCP). | Vets third-party skills for prompt injection, data exfiltration, and supply-chain risks *before* you install them. |
| [agent-scan](https://github.com/snyk/agent-scan) | Security scanner for AI agents, MCP servers, and agent skills. | Audits your whole agent setup for tool poisoning, prompt injection, and risky configurations. |
| [mcp-scanner](https://github.com/cisco-ai-defense/mcp-scanner) | Scans MCP servers for threats and security findings. | Checks MCP servers before you connect them to your agents. |
| [promptfoo](https://github.com/promptfoo/promptfoo) | Testing and red-teaming for prompts, agents, and RAG. | Red-teams your own AI apps for jailbreaks, injection, and data leaks, and catches regressions in CI. |

## Code Review

| Repo | Description | How this helps |
|---|---|---|
| [open-code-review](https://github.com/alibaba/open-code-review) | Hybrid code review tool (deterministic pipelines + LLM agent) with line-level comments and a built-in multi-language ruleset. | Automates PR review with precise, line-level feedback on real bug classes (NPE, thread-safety, XSS, SQL injection); works with OpenAI and Anthropic models. |

## Kubernetes

| Repo | Description | How this helps |
|---|---|---|
| [crossplane](https://github.com/crossplane/crossplane) | The cloud-native control plane. | Manage cloud infrastructure as Kubernetes resources and build your own platform APIs. |
| [cloudnative-pg](https://github.com/cloudnative-pg/cloudnative-pg) | The most popular Kubernetes operator for PostgreSQL. | Production Postgres on Kubernetes with HA, backups, and failover handled for you. |
| [k3d](https://github.com/k3d-io/k3d) | Runs k3s clusters in Docker. | Spin up disposable multi-node clusters locally in seconds. |
| [popeye](https://github.com/derailed/popeye) | Kubernetes cluster resource sanitizer. | Flags misconfigurations and unused resources in a live cluster. |
| [polaris](https://github.com/FairwindsOps/polaris) | Validates best practices in Kubernetes clusters. | Enforces reliability, efficiency, and security checks, including as an admission controller. |
| [goldilocks](https://github.com/FairwindsOps/goldilocks) | Gets your resource requests "just right". | Recommends CPU and memory requests from real usage, which cuts waste and OOMs. |
| [chaoskube](https://github.com/linki/chaoskube) | Periodically kills random pods. | Proves your workloads survive pod failure. |
| [kubevious](https://github.com/kubevious/kubevious) | Kubernetes without disasters. | Visualizes the app-centric cluster state and catches config errors. |
| [havener](https://github.com/homeport/havener) | Swiss army knife for Kubernetes tasks. | Handy shortcuts for common cluster operations and debugging. |
| [kvass](https://github.com/tkestack/kvass) | Prometheus horizontal auto-scaling via a sidecar. | Scales Prometheus scraping across many shards for huge clusters. |
| [cluster-monitoring](https://github.com/carlosedp/cluster-monitoring) | Monitoring stack built on the Prometheus Operator. | A ready Prometheus and Grafana setup, including ARM clusters. |

## Terraform & IaC

| Repo | Description | How this helps |
|---|---|---|
| [terraformer](https://github.com/GoogleCloudPlatform/terraformer) | Generates Terraform files from existing infrastructure. | Brings click-ops infrastructure under code fast. |
| [cf-terraforming](https://github.com/cloudflare/cf-terraforming) | Generates Terraform from existing Cloudflare resources. | Imports your Cloudflare setup into Terraform. |
| [infracost](https://github.com/infracost/infracost) | Cloud cost intelligence for engineers, AI agents, and CI/CD. | Shows the cost impact of a Terraform change in the PR, before you merge. |
| [terraform-docs](https://github.com/terraform-docs/terraform-docs) | Generates documentation from Terraform modules. | Keeps module READMEs in sync with inputs and outputs automatically. |
| [terraform-landscape](https://github.com/coinbase/terraform-landscape) | Makes Terraform plan output easier to read. | Makes large plans reviewable at a glance. |
| [blast-radius](https://github.com/28mm/blast-radius) | Interactive visualizations of Terraform dependency graphs. | Shows what a change will touch before you apply it. |
| [pluralith-cli](https://github.com/Pluralith/pluralith-cli) | Terraform state visualization and automated infra docs. | Auto-generates infrastructure diagrams from state. |
| [diagrams](https://github.com/mingrammer/diagrams) | Diagrams as code for cloud system architectures. | Version-controlled architecture diagrams written in Python. |

## Docker & CI/CD

| Repo | Description | How this helps |
|---|---|---|
| [distroless](https://github.com/GoogleContainerTools/distroless) | Language-focused Docker images without an operating system. | Smaller images with a much smaller attack surface. |
| [official-images](https://github.com/docker-library/official-images) | Source of truth for Docker Official Images. | See exactly how official images are built and tagged. |
| [docker-library/docs](https://github.com/docker-library/docs) | Documentation for Docker Official Images. | Reference for image variants, tags, and usage. |
| [gocd](https://github.com/gocd/gocd) | Continuous delivery server. | Models complex deployment pipelines with first-class value-stream visualization. |
| [jenkins-pipeline-examples](https://github.com/cvitter/jenkins-pipeline-examples) | Example declarative Jenkins pipelines. | Copy-paste starting points for Jenkinsfiles. |
| [jfrog/project-examples](https://github.com/jfrog/project-examples) | Small projects for configuring CI with Artifactory. | Working examples across build tools for publishing to Artifactory. |
| [pentaho-containers](https://github.com/hv-support/pentaho-containers) | Templates for running Pentaho in containers. | Ready Docker setups for Pentaho deployments. |
| [alexa-swarm](https://github.com/mlabouardy/alexa-swarm) | Deploys a Docker Swarm cluster on AWS using Amazon Echo. | A fun voice-driven infrastructure demo. |
| [docker-inbound-agent](https://github.com/jenkinsci/docker-inbound-agent) | Docker image for a Jenkins inbound agent. ⚠️ Deprecated, merged into docker-agent. | Reference only; use `jenkins/docker-agent` instead. |

## Observability & Networking

| Repo | Description | How this helps |
|---|---|---|
| [caddy](https://github.com/caddyserver/caddy) | Fast, extensible web server with automatic HTTPS. | TLS out of the box with a tiny config; a great reverse proxy. |
| [vector](https://github.com/vectordotdev/vector) | High-performance observability data pipeline. | Collects, transforms, and routes logs and metrics anywhere, cheaply. |
| [elasticsearch_exporter](https://github.com/prometheus-community/elasticsearch_exporter) | Elasticsearch stats exporter for Prometheus. | Monitors Elasticsearch health in your Prometheus stack. |
| [elasticsearch-stress-test](https://github.com/logzio/elasticsearch-stress-test) | Stress test tool for Elasticsearch. | Validates cluster capacity before production load hits. |
| [roxy-wi](https://github.com/roxy-wi/roxy-wi) | Web interface for HAProxy, Nginx, Apache, and Keepalived. | Manages load balancers and web servers from one UI. |
| [go-feedback-agent](https://github.com/loadbalancerorg/go-feedback-agent) | Sets real server weight from available resources. | Load-aware HAProxy balancing on Linux. |
| [windows_feedback_agent](https://github.com/loadbalancerorg/windows_feedback_agent) | Windows feedback agent for HAProxy server weight. | Load-aware HAProxy balancing for Windows backends. |
| [dpbench](https://github.com/dpbench/dpbench) | Dataplane benchmarking suite. | Fair, reproducible benchmarks for proxies and load balancers. |
| [chaosmonkey](https://github.com/Netflix/chaosmonkey) | Netflix's resiliency tool that randomly terminates instances. | Forces your systems to tolerate instance failure. |
| [Logstalgia](https://github.com/acaudwell/Logstalgia) | Replays or streams web access logs as a retro arcade game. | A fun, surprisingly useful way to see traffic patterns. |

## Self-Hosting & Home Lab

| Repo | Description | How this helps |
|---|---|---|
| [restic](https://github.com/restic/restic) | Fast, secure, efficient backup program. | Encrypted, deduplicated backups to almost any storage backend. |
| [docker-pi-hole](https://github.com/pi-hole/docker-pi-hole) | Official Pi-hole Docker image. | Network-wide ad and tracker blocking in one container. |
| [docker-openvpn](https://github.com/kylemanna/docker-openvpn) | OpenVPN server in Docker with an EasyRSA PKI CA. | Your own VPN up in minutes. |
| [cloudflare-ddns](https://github.com/timothymiller/cloudflare-ddns) | Rust-based dynamic DNS updater for Cloudflare. | Keeps your home IP reachable through a Cloudflare domain. |
| [dyn-dns](https://github.com/ngalaiko/dyn-dns) | Dynamic DNS updater. | A minimal DDNS alternative. |
| [docker-plex](https://github.com/jaymoulin/docker-plex) | Multi-arch Plex Media Server image, including Raspberry Pi. | Plex on ARM boards without hassle. |
| [Varken](https://github.com/Boerderij/Varken) | Aggregates Plex ecosystem data into InfluxDB for Grafana. | Dashboards for your media server usage. |
| [postiz-app](https://github.com/gitroomhq/postiz-app) | Agentic social media scheduling tool. | A self-hosted alternative to Buffer and Hootsuite, with AI help. |

## Developer Tools

| Repo | Description | How this helps |
|---|---|---|
| [atuin](https://github.com/atuinsh/atuin) | Magical shell history. | Searchable, synced shell history across machines. |

## Learning Resources

| Repo | Description | How this helps |
|---|---|---|
| [ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch) | Hands-on course covering ML, deep learning, LLMs, agents, and more. | A structured, build-it-yourself path to understanding AI engineering end to end, from fundamentals to shipping. |
| [hacker-laws](https://github.com/dwmkerr/hacker-laws) | Laws, theories, principles, and patterns for developers. | Shared vocabulary for engineering trade-offs (Conway, Hyrum, Brooks, and more). |
| [kubernetes-failure-stories](https://github.com/hjacobs/kubernetes-failure-stories) | Public Kubernetes failure and horror stories. | Learn from others' incidents before you repeat them. |
| [The-HustleGPT-Challenge](https://github.com/jtmuller5/The-HustleGPT-Challenge) | Building startups with an AI co-founder. | Real examples of founders using AI to build businesses. |

## Other Awesome Lists

| Repo | Description | How this helps |
|---|---|---|
| [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) | Free software you can host yourself. | The go-to catalog for replacing SaaS with self-hosted apps. |
| [awesome-mac](https://github.com/jaywcjlove/awesome-mac) | High-quality macOS software. | Find the best Mac app for any job. |
| [awesome-docker](https://github.com/veggiemonk/awesome-docker) | Docker resources and projects. | Tools and guides across the Docker ecosystem. |
| [awesome-kubernetes (ramitsurana)](https://github.com/ramitsurana/awesome-kubernetes) | Kubernetes resources. | Broad coverage of Kubernetes tools and learning. |
| [awesome-kubernetes (run-x)](https://github.com/run-x/awesome-kubernetes) | Kubernetes projects, tools, and resources. | A more tightly curated Kubernetes tool list. |
| [awesome-helm](https://github.com/cdwv/awesome-helm) | Helm charts and resources. | Find charts and Helm tooling. |
| [awesome-terraform (Azure)](https://github.com/Azure/awesome-terraform) | Azure Terraform tools and samples. | Terraform-on-Azure references. |
| [awesome-privacy](https://github.com/lissy93/awesome-privacy) | Privacy- and security-focused software and services. | Privacy-respecting alternatives for everyday tools. |
| [awesome-raspberry-pi](https://github.com/thibmaek/awesome-raspberry-pi) | Raspberry Pi tools, projects, and images. | Ideas and software for Pi projects. |
| [awesome-functional-python](https://github.com/sfermigier/awesome-functional-python) | Functional programming in Python. | Libraries and reading for FP-style Python. |
| [awesome-musicdsp](https://github.com/olilarkin/awesome-musicdsp) | Music DSP and audio programming resources. | Learning path for building audio plugins and DSP. |
| [awesome-music-production](https://github.com/ad-si/awesome-music-production) | Software and services to create and distribute music. | Tools for every stage of music production. |

## Miscellaneous

| Repo | Description | How this helps |
|---|---|---|
| [PathOfBuilding-PoE2](https://github.com/PathOfBuildingCommunity/PathOfBuilding-PoE2) | Offline build planner for Path of Exile 2. | Calculates DPS and defenses to theory-craft builds before investing in them. |
| [arctic_shift_ui](https://github.com/ArthurHeitmann/arctic_shift_ui) | Web UI for searching and downloading archived Reddit data. | Search old Reddit content beyond what Reddit's own search shows. |
| [reddit-gems](https://github.com/hoveychen/reddit-gems) | Full archive and media browser for r/coolgithubprojects (2014–2026). | A goldmine for discovering interesting projects. |
| [ByteOrder](https://github.com/Matts-Baps/ByteOrder) | Home kitchen ordering system. | A fun self-hosted "restaurant menu" for your household. |
