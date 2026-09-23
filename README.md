<h1 align="center">👋 Hi, I'm CodeAlex</h1>
<h3 align="center">AI Agent Engineer · Open-Source Contributor</h3>

<p align="center">
  <a href="https://github.com/CodeAlex52">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&random=false&width=500&lines=Event+loops.+Tool+calling.+Structured+output.;I+fix+agents+where+they+actually+break.;Repro+%3E+root+cause+%3E+regression+test." alt="Typing SVG" />
  </a>
</p>

---

## 🧑‍💻 About Me

- 🔧 **Agent reliability** — event-loop semantics, tool calling, forced structured output, cross-provider compatibility
- 🌐 **LLM gateway** — provider capability mapping, model parameter conversion across 100+ providers
- 🧩 **Protocols & retrieval** — MCP, vector-database SDKs, RAG retrieval paths
- 📦 **How I work** — minimal repro → wire-level root cause → mutation-verified regression test → merged upstream

---

## 🏆 Open Source

- ✅ **[NVIDIA/NeMo-Agent-Toolkit#2236](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2236)** (merged) — fixed streaming guardrail defects in NVIDIA's agent security framework: three defense middlewares (PII, content safety, output verifier) analyzed structured stream chunks as Python reprs, so typed chunks were scanned as repr dumps and length guards could stop early; introduced a shared typed `stream_chunk_to_text` converter with 3 mutation-verified regression tests. Filed the issue and the fix together; merged through NVIDIA's DCO/vetter/maintainer pipeline as submitted.
- ✅ **[strands-agents/harness-sdk#4263](https://github.com/strands-agents/harness-sdk/pull/4263)** (merged) — fixed forced structured-output retry in the AWS Strands Agents SDK: `tool_choice: any` let provider built-in tools preempt the output tool; forced by tool name instead, with a two-cycle regression test. Approved and merged as submitted.
- 🚢 **[BerriAI/litellm](https://github.com/BerriAI/litellm)** (fix shipped upstream) — diagnosed a model-capability mapping error where gpt-5.1/5.4 forwarded a rejected `reasoning_effort=minimal`; corrected the flags plus the backup map with regression tests. Shipped to `main` via the upstream registry batch PR.

---

## 📊 Stats

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=CodeAlex52&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=CodeAlex52&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />
</p>

---

## 🛠️ Tech Stack

<h3>💻 Languages</h3>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

<h3>🏗️ Frameworks & Infra</h3>

![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F6821F?style=for-the-badge&logo=cloudflare&logoColor=white)

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/CodeAlex52/wake-log"><b>🔥 wake-log</b></a>
      · <a href="https://wake-log.664501775.workers.dev">🟢 Live Demo</a><br/>
      Habit-tracker PWA for early risers — every check-in recorded.<br/>
      <sub><b>TypeScript · Vite · Cloudflare Workers</b></sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/CodeAlex52/psn-ns-record"><b>🎮 psn-ns-record</b></a>
      · <a href="https://psn-ns-record.664501775.workers.dev">🟢 Live Demo</a><br/>
      PS5 / Switch game library and play-record manager PWA.<br/>
      <sub><b>React · TypeScript · Vite · PWA</b></sub>
    </td>
  </tr>
</table>

---

## 🐍 Contribution Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/CodeAlex52/CodeAlex52/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/CodeAlex52/CodeAlex52/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution grid snake animation" width="92%" src="https://raw.githubusercontent.com/CodeAlex52/CodeAlex52/output/github-contribution-grid-snake.svg" />
</picture>

---

## 📫 Contact

<p align="center">
  <a href="https://firefly.664501775.workers.dev">
    <img src="https://img.shields.io/badge/Blog-FF5D01?style=for-the-badge&logo=astro&logoColor=white" alt="Blog" />
  </a>
  <a href="mailto:suzhe52@foxmail.com">
    <img src="https://img.shields.io/badge/suzhe52%40foxmail.com-00A1D6?style=for-the-badge&label=%F0%9F%93%AE%20Email" alt="Email" />
  </a>
  <a href="https://github.com/CodeAlex52">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=CodeAlex52&label=✨%20Profile%20Views&color=blueviolet&style=for-the-badge" alt="profile views" />
</p>

<hr />

<p align="center">
  <i>🌟 "Code is like poetry — every line tells a story, every commit builds the future."</i>
</p>
