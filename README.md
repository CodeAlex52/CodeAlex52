<div align="center">

# CodeAlex

**AI Agent & LLM Infra** — I debug agents where abstractions leak.

<a href="https://github.com/NVIDIA/NeMo-Agent-Toolkit/pulls?q=is%3Apr+author%3ACodeAlex52"><img alt="NVIDIA · 2 merged" src="https://img.shields.io/badge/NVIDIA-2_merged-76B900?style=flat-square&logo=nvidia&logoColor=white"></a>
<a href="https://github.com/google/adk-js/pull/922"><img alt="Google ADK-JS · merged" src="https://img.shields.io/badge/Google_ADK--JS-merged-4285F4?style=flat-square&logo=google&logoColor=white"></a>
<a href="https://github.com/strands-agents/harness-sdk/pull/4263"><img alt="AWS Strands · merged" src="https://img.shields.io/badge/AWS_Strands-merged-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white"></a>
<a href="https://github.com/BerriAI/litellm/pull/40581"><img alt="LiteLLM · fix shipped" src="https://img.shields.io/badge/LiteLLM-shipped-2F81F7?style=flat-square&logo=python&logoColor=white"></a>

</div>

## Merged upstream

- **NVIDIA · NeMo Agent Toolkit** — [ReAct parser swallowed JSON actions as final answers](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2275) · [guardrails parsed typed stream chunks as Python reprs](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2236)
- **Google · ADK-JS** — [Gemini 3.5 Live Translate misrouted through the Gemini 3.x Live path](https://github.com/google/adk-js/pull/922)
- **AWS · Strands Agents** — [structured-output retry preempted by provider-native tools](https://github.com/strands-agents/harness-sdk/pull/4263)
- **LiteLLM** — [`reasoning_effort=minimal` capability metadata, shipped on main](https://github.com/BerriAI/litellm/pull/40581)

## Projects

### [AgentCorp](https://github.com/CodeAlex52/AgentCorp) — crash-recoverable multi-agent orchestrator

`310 offline tests` · `SIGKILL-safe resume` · `budget hard-stops` · `replayable event log`

```mermaid
flowchart LR
    PRD([PRD]) --> DAG[Task DAG] --> S[scheduler] --> W[worker] --> R[reviewer] --> OUT([report])
    S <--> E[(crash-safe event log)]
```

### [agent-loop-trace](https://github.com/CodeAlex52/agent-loop-trace) — agent loop bugs → single-file timeline

<a href="https://github.com/CodeAlex52/agent-loop-trace"><img src="https://raw.githubusercontent.com/CodeAlex52/agent-loop-trace/main/docs/assets/trace-demo.png" width="660" alt="rendered trace: Strands forced-retry preemption" /></a>

<p align="center"><a href="https://github.com/search?q=is%3Apr+author%3ACodeAlex52+is%3Amerged&type=pullrequests">Merged PRs</a> · <a href="https://github.com/search?q=is%3Apr+author%3ACodeAlex52&type=pullrequests">All pull requests →</a></p>
