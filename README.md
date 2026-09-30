# My Awesome List [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A personal, curated catalog of repositories I've found genuinely good, organized by category.

## Contents

- [AI Agents & Memory](#ai-agents--memory)
- [Agent Skills](#agent-skills)
- [Security](#security)
- [Compliance & GRC](#compliance--grc)
- [AI Pentesting](#ai-pentesting)
- [Agent Security](#agent-security)
- [Code Review](#code-review)
- [Learning Resources](#learning-resources)

---

## AI Agents & Memory

| Repo | Description | How this helps |
|---|---|---|
| [hindsight](https://github.com/vectorize-io/hindsight) | Agent memory that learns. | Gives agents long-term memory that improves over time, so they don't start from zero every session. |
| [financial-services](https://github.com/anthropics/financial-services) | Anthropic's reference agents, skills, and data connectors for investment banking, equity research, private equity, and wealth management. | Ready-made starting points for finance workflows (comps, DCF, earnings reviews, reconciliations) and a solid reference for structuring agent plugins. |

## Agent Skills

| Repo | Description | How this helps |
|---|---|---|
| [archify](https://github.com/tt-a1i/archify) | Agent skill for architecture, workflow, sequence, data-flow, and lifecycle diagrams as self-contained HTML. | Lets your coding agent produce clean, exportable diagrams straight from code or a description — no manual diagramming. |
| [i-have-adhd](https://github.com/ayghri/i-have-adhd) | Skill that stops your coding agent from burying the answer; ADHD-friendly output. | Makes agent responses lead with the answer and stay scannable, cutting noise and reading time. |

## Security

| Repo | Description | How this helps |
|---|---|---|
| [security-audit-skill](https://github.com/cloudflare/security-audit-skill) | Coding-agent skill for multi-phase security audits with independently verified, machine-readable findings. | Turns your agent into a structured security auditor with fewer false positives and findings you can feed into other tools. |
| [trailofbits/skills](https://github.com/trailofbits/skills) | Trail of Bits' Claude Code skills for security research, vulnerability detection, and audit workflows. | Brings a top security firm's audit know-how straight into your coding agent. |
| [semgrep/mcp](https://github.com/semgrep/mcp) | MCP server for scanning code with Semgrep. | Lets any MCP-compatible agent run static analysis and catch vulnerabilities while it writes code. |

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

## Learning Resources

| Repo | Description | How this helps |
|---|---|---|
| [ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch) | Hands-on course covering ML, deep learning, LLMs, agents, and more. | A structured, build-it-yourself path to understanding AI engineering end to end, from fundamentals to shipping. |
