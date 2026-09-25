# Hi, I'm CodeAlex 👋

### AI Agent Engineer · Agent Reliability · LLM Infrastructure

> **I debug agents where abstractions leak.**

`Agent Runtime · Tool Calling · Structured Output · Streaming · Guardrails · Observability · LLM Gateway`

**Contributor to production AI infrastructure across NVIDIA NeMo Agent Toolkit, Strands Agents, LiteLLM and the OpenTelemetry ecosystem.**

---

## 🏆 Selected Open Source Contributions

### NVIDIA · [NeMo Agent Toolkit](https://github.com/NVIDIA/NeMo-Agent-Toolkit) — **MERGED**

Fixed structured-stream handling in **Agent Security** guardrails, preventing typed streaming chunks from being analyzed as Python representations. Introduced a shared typed stream-to-text conversion path with regression coverage across PII detection, content safety and output verification — [NVIDIA/NeMo-Agent-Toolkit#2236](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2236).

### Strands Agents · [Harness SDK](https://github.com/strands-agents/harness-sdk) — **MERGED**

Fixed forced structured-output retries where a generic `tool_choice` could allow provider-native tools to preempt the required output tool. Added regression coverage for the multi-cycle retry path — [strands-agents/harness-sdk#4263](https://github.com/strands-agents/harness-sdk/pull/4263).

### LiteLLM — **FIX SHIPPED UPSTREAM**

Diagnosed incorrect model-capability metadata that forwarded unsupported `reasoning_effort=minimal` parameters to providers. The fix landed on `main` through the upstream registry batch PR, superseding my original proposal ([#40547](https://github.com/BerriAI/litellm/pull/40547) → [#40581](https://github.com/BerriAI/litellm/pull/40581)).

---

## 🚀 What I Build

### [AgentCorp](https://github.com/CodeAlex52/AgentCorp)

Local-first, event-sourced, crash-recoverable, budget-bounded multi-agent delivery orchestrator.

`PRD → Task DAG → Agent Execution → Review → Report`

308 offline tests · SIGKILL recovery · 64-way concurrent claim race · mypy strict + ruff clean.

### [agent-loop-trace](https://github.com/CodeAlex52/agent-loop-trace)

A lightweight debugging and visualization tool for agent execution traces.

`Agent Loop → Events → JSON IR → Visual Trace`

Built for debugging agent execution, state transitions, tool calls and failures.

---

## 🔬 Currently Working On

### [OpenLLMetry · AWS Bedrock instrumentation](https://github.com/traceloop/openllmetry/pull/4507) — **OPEN**

Fixing Bedrock operation-duration telemetry by moving shared client-level metric state into per-call contexts: correct per-call latency measurement, concurrent request state isolation, and an OpenTelemetry histogram regression test.

---

## 🔁 How I Work

`Reproduce → Trace → Root Cause → Fix → Regression Test → Review → Upstream`

I care less about patch size and more about producing a complete evidence chain from failure to verified fix.

---

## 🧠 Focus Areas

- Agent Runtime & Harness Engineering
- Tool Calling & Structured Output
- Streaming & Guardrails
- LLM Gateway & Provider Compatibility
- Observability & OpenTelemetry
- MCP / Context / Retrieval
- Failure Recovery & Concurrency

---

## 🛠️ Tech Stack

<h3>💻 Languages</h3>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

<h3>🧠 AI & Infra</h3>

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-1F6FEB?style=for-the-badge&logo=modelcontextprotocol&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-4B8BBE?style=for-the-badge)
![Vector DB](https://img.shields.io/badge/Vector_DB-2C3E50?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

<h3>🏗️ Frameworks & Tools</h3>

![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F6821F?style=for-the-badge&logo=cloudflare&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=CodeAlex52&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=CodeAlex52&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />
</p>

---

## 🐍 Contribution Trail

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/CodeAlex52/CodeAlex52/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/CodeAlex52/CodeAlex52/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution grid snake animation" width="92%" src="https://raw.githubusercontent.com/CodeAlex52/CodeAlex52/output/github-contribution-grid-snake.svg" />
</picture>

> `Ship. Break. Trace. Fix. Repeat.`

---

<details>
<summary><b>Other things I've built</b></summary>
<br/>

- [wake-log](https://github.com/CodeAlex52/wake-log) · [Live Demo](https://wake-log.664501775.workers.dev) — habit-tracker PWA for early risers, every check-in recorded.
- [psn-ns-record](https://github.com/CodeAlex52/psn-ns-record) · [Live Demo](https://psn-ns-record.664501775.workers.dev) — PS5 / Switch game library and play-record manager PWA.

</details>

---

## 📫 Contact

<p align="center">
  <a href="mailto:suzhe52@foxmail.com">
    <img src="https://img.shields.io/badge/suzhe52%40foxmail.com-00A1D6?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/CodeAlex52">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://firefly.664501775.workers.dev">
    <img src="https://img.shields.io/badge/Blog-FF5D01?style=for-the-badge&logo=astro&logoColor=white" alt="Blog" />
  </a>
</p>
