<div align="center">

<a href="https://github.com/CodeAlex52">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&duration=3200&pause=800&color=58A6FF&center=true&vCenter=true&width=820&height=90&lines=AI+Agent+%26+LLM+Infra+Engineer;I+debug+agents+where+abstractions+leak.;Merged+fixes+in+NVIDIA%2C+Google+%26+AWS+agent+stacks" alt="AI Agent & LLM Infra Engineer" />
</a>

**`Agent Runtime` · `Tool Calling` · `Structured Output` · `Streaming` · `Guardrails` · `Observability` · `LLM Gateway`**

<p>
  <a href="https://github.com/NVIDIA/NeMo-Agent-Toolkit/pulls?q=is%3Apr+author%3ACodeAlex52"><img alt="NVIDIA · 2 merged PRs" src="https://img.shields.io/badge/NVIDIA-2_merged_PRs-76B900?style=for-the-badge&logo=nvidia&logoColor=white"></a>
  <a href="https://github.com/google/adk-js/pull/922"><img alt="Google ADK-JS · merged" src="https://img.shields.io/badge/Google_ADK--JS-merged-4285F4?style=for-the-badge&logo=google&logoColor=white"></a>
  <a href="https://github.com/strands-agents/harness-sdk/pull/4263"><img alt="AWS Strands · merged" src="https://img.shields.io/badge/AWS_Strands-merged-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white"></a>
  <a href="https://github.com/BerriAI/litellm/pull/40581"><img alt="LiteLLM · fix shipped" src="https://img.shields.io/badge/LiteLLM-fix_shipped-2F81F7?style=for-the-badge&logo=python&logoColor=white"></a>
</p>

**4 upstream PRs merged · 21 in review · across NVIDIA, Google, AWS, Cloudflare, Meta, Kubernetes, Sentry, Vercel, Stanford, Anthropic**

</div>

---

## 🏆 Merged in production AI stacks

| Contribution | Status |
| --- | --- |
| **NVIDIA · NeMo Agent Toolkit** — the ReAct parser silently accepted JSON-formatted actions as *final answers*, so the tool the model asked for was never called. Quoted keys plus `action_input`/`input` variants now parse explicitly, and a JSON action missing its input raises instead of being swallowed. — [#2275](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2275) | ✅ **Merged** |
| **NVIDIA · NeMo Agent Toolkit** — Agent Security guardrails analyzed typed streaming chunks as Python reprs, corrupting PII detection, content safety and output verification. Shared typed stream→text conversion path + regression coverage across all three middlewares. — [#2236](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2236) | ✅ **Merged** |
| **Google · ADK-JS** — Gemini 3.5 Live Translate was routed through the Gemini 3.x Live path; now excluded so live translation resolves through the supported model, matching `adk-python`. — [#922](https://github.com/google/adk-js/pull/922) | ✅ **Merged** |
| **AWS · Strands Agents** — forced structured-output retries could be preempted by provider-native tools through a generic `tool_choice`; fixed with multi-cycle retry regression tests. — [#4263](https://github.com/strands-agents/harness-sdk/pull/4263) | ✅ **Merged** |
| **LiteLLM** — diagnosed wrong model-capability metadata forwarding unsupported `reasoning_effort=minimal`; the fix landed on `main` through the upstream registry batch PR. — [#40547](https://github.com/BerriAI/litellm/pull/40547) → [#40581](https://github.com/BerriAI/litellm/pull/40581) | 🚢 **Fix shipped upstream** |

<details>
<summary><b>🔬 21 PRs in review — NVIDIA · Cloudflare · Meta · Kubernetes · Sentry · Vercel · Stanford · Anthropic · …</b></summary>

<br/>

| Project | PR | What |
| --- | --- | --- |
| NVIDIA · k8s-device-plugin | [#2067](https://github.com/NVIDIA/k8s-device-plugin/pull/2067) | wait for the node label before the first config sync |
| Cloudflare · Pingora | [#1021](https://github.com/cloudflare/pingora/pull/1021) | finish the brotli stream before returning its output |
| Meta · RocksDB | [#15275](https://github.com/facebook/rocksdb/pull/15275) | restore `value_size_soft_limit` progress guarantee for blob reads in MultiGet |
| Kubernetes · Cluster API | [#14301](https://github.com/kubernetes-sigs/cluster-api/pull/14301) | KCP: propagate `DNS.imageRepository` when updating the kubeadm config map |
| Sentry | [#126044](https://github.com/getsentry/sentry/pull/126044) | keep fix-keyword ID lists on a single line |
| Vercel · AI SDK | [#21214](https://github.com/vercel/ai/pull/21214) | skip `onInputAvailable` for invalid streamed tool inputs |
| Vercel · AI SDK | [#21352](https://github.com/vercel/ai/pull/21352) | await `onFinish` in `useObject` so rejected async callbacks surface via `onError` |
| Stanford · DSPy | [#10487](https://github.com/stanfordnlp/dspy/pull/10487) | trust `Prediction(score=...)` when accepting bootstrapped traces |
| Stanford · DSPy | [#10363](https://github.com/stanfordnlp/dspy/pull/10363) | partial-credit fraction and zero `format_reward` handling |
| Anthropic · sandbox-runtime | [#558](https://github.com/anthropics/sandbox-runtime/pull/558) | drain a denied upload before tearing the socket down |
| Prometheus · procfs | [#876](https://github.com/prometheus/procfs/pull/876) | parse arm64 CPU identity fields (implementer / variant / part / revision) |
| CrewAI | [#7620](https://github.com/crewAIInc/crewAI/pull/7620) | strip single quotes when matching coworker roles |
| Helicone | [#5817](https://github.com/Helicone/helicone/pull/5817) | stop double counting accepted prediction tokens in usage processors |
| AWS Strands · Harness SDK | [#4655](https://github.com/strands-agents/harness-sdk/pull/4655) | report malformed tool input JSON to the model as an error tool result |
| Traceloop · OpenLLMetry | [#4507](https://github.com/traceloop/openllmetry/pull/4507) | record Bedrock operation duration per call instead of client age |
| Agent Router · Envoy AI Gateway | [#2730](https://github.com/theagentrouter/agent-router/pull/2730) | redact error response bodies per OpenInference `TraceConfig` |
| TencentCloud · Octop | [#703](https://github.com/TencentCloud/Octop/pull/703) | align dashboard Ollama-local detection with backend |
| TencentCloud · TencentDB Agent Memory | [#1378](https://github.com/TencentCloud/TencentDB-Agent-Memory/pull/1378) | skip DSH permission notice in fresh-session detection |
| Prefect · Marvin | [#1393](https://github.com/PrefectHQ/marvin/pull/1393) | handle bare `List` in `is_classifier` / `as_classifier` |
| Milvus · pymilvus | [#3792](https://github.com/milvus-io/pymilvus/pull/3792) | align membership filter expressions with `membership_match` |
| Desktop Commander MCP | [#726](https://github.com/wonderwhy-er/DesktopCommanderMCP/pull/726) | accept `limit` as an alias for `length` in `read_file` |

</details>

<p align="right"><a href="https://github.com/search?q=is%3Apr+author%3ACodeAlex52&type=pullrequests">All pull requests →</a></p>

---

## 🚀 Selected work

### [AgentCorp](https://github.com/CodeAlex52/AgentCorp) — local-first multi-agent delivery orchestrator

> `PRD → Task DAG → Agent Execution → Review → Report`

Event-sourced · crash-recoverable (**SIGKILL** recovery) · budget-bounded · **308 offline tests** · 64-way concurrent claim races · `mypy --strict` + `ruff` clean.

### [agent-loop-trace](https://github.com/CodeAlex52/agent-loop-trace) — visual trace debugger for agent loops

> `Agent Loop → Events → JSON IR → Visual Trace`

Built for debugging agent execution, state transitions, tool calls and failures.

---

## 🔁 How I work

```text
Reproduce → Trace → Root Cause → Fix → Regression Test → Review → Upstream
```

I optimize for a complete evidence chain from failure to a verified fix — not patch size.

---

## 🧠 Focus areas

- Agent Runtime & Harness Engineering
- Tool Calling & Structured Output
- Streaming & Guardrails
- LLM Gateway & Provider Compatibility
- Observability & OpenTelemetry
- MCP / Context / Retrieval
- Failure Recovery & Concurrency

---

## 🛠️ Tech stack

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3176C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img alt="Go" src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white">
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
</p>

<p align="center">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
  <img alt="OpenTelemetry" src="https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white">
  <img alt="MCP" src="https://img.shields.io/badge/MCP-1F6FEB?style=for-the-badge&logo=modelcontextprotocol&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
</p>

<p align="center">
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">
  <img alt="Cloudflare" src="https://img.shields.io/badge/Cloudflare-F6821F?style=for-the-badge&logo=cloudflare&logoColor=white">
</p>

---

## 📈 By the numbers

<p align="center">
  <img height="150" alt="Merged pull requests" src="https://github-readme-stats.vercel.app/api?username=CodeAlex52&show_icons=true&hide=stars,commits,issues,contribs&show=prs_merged,prs_merged_percentage&theme=tokyonight&hide_border=true&rank_icon=github">
  &nbsp;
  <img height="150" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=CodeAlex52&layout=compact&langs_count=8&theme=tokyonight&hide_border=true">
</p>

---

<div align="center">

**The fastest way to judge me is to read a PR diff.**

</div>
