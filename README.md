<div align="center">

# CodeAlex

**AI Agent & LLM Infra** — I debug agents where abstractions leak.

<a href="https://github.com/NVIDIA/NeMo-Agent-Toolkit/pulls?q=is%3Apr+author%3ACodeAlex52"><img alt="NVIDIA · 2 merged" src="https://img.shields.io/badge/NVIDIA-2_merged-76B900?style=flat-square&logo=nvidia&logoColor=white"></a>
<a href="https://github.com/google/adk-js/pull/922"><img alt="Google ADK-JS · merged" src="https://img.shields.io/badge/Google_ADK--JS-merged-4285F4?style=flat-square&logo=google&logoColor=white"></a>
<a href="https://github.com/langgenius/dify/pull/43875"><img alt="Dify · merged" src="https://img.shields.io/badge/Dify-merged-1C64F2?style=flat-square&logo=dify&logoColor=white"></a>
<a href="https://github.com/bytedance/deer-flow/pull/6689"><img alt="ByteDance DeerFlow · merged" src="https://img.shields.io/badge/ByteDance_DeerFlow-merged-325AB4?style=flat-square&logo=bytedance&logoColor=white"></a>
<a href="https://github.com/strands-agents/harness-sdk/pull/4263"><img alt="AWS Strands · merged" src="https://img.shields.io/badge/AWS_Strands-merged-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white"></a>
<a href="https://github.com/morluto/rea/pull/2936"><img alt="rea · merged" src="https://img.shields.io/badge/morluto_rea-merged-2F81F7?style=flat-square&logo=github&logoColor=white"></a>

</div>

## Merged upstream

- **NVIDIA · NeMo Agent Toolkit** — [ReAct parser swallowed JSON actions as final answers](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2275) · [guardrails parsed typed stream chunks as Python reprs](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2236)
- **NVIDIA · NeMo Agent Toolkit (ctd.)** — [guardrails middleware returned chunk reprs instead of reply text](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2308) · [converter matched source types with raw isinstance](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2310)
- **Google · ADK-JS** — [Gemini 3.5 Live Translate misrouted through the Gemini 3.x Live path](https://github.com/google/adk-js/pull/922)
- **Dify** — [strict typing for the workspace permission tests, part of the repo-wide strict Pyrefly effort](https://github.com/langgenius/dify/pull/43875)
- **ByteDance · DeerFlow** — [skill scanner matched fork bombs by spelling, so renamed and respaced payloads passed the blocking gate](https://github.com/bytedance/deer-flow/pull/6689)
- **AWS · Strands Agents** — [structured-output retry preempted by provider-native tools](https://github.com/strands-agents/harness-sdk/pull/4263)
- **morluto/rea** — [packaged platform check accepted overview responses without a procedure count](https://github.com/morluto/rea/pull/2936)

## In review

- **Kubernetes SIG · Cluster API** — [KCP propagates `DNS.imageRepository` when updating the kubeadm config map](https://github.com/kubernetes-sigs/cluster-api/pull/14301)
- **Prometheus · procfs** — [arm64 CPU identity fields: implementer / variant / part / revision](https://github.com/prometheus/procfs/pull/876)
- **NVIDIA · NeMo Agent Toolkit** — [union targets in `DecomposedType.is_subtype`](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2309)
- **Agent Router** — [redact error response bodies per OpenInference TraceConfig](https://github.com/theagentrouter/agent-router/pull/2730)

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
