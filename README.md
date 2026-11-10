### Hi, I'm Ankit 👋

Staff AI Engineer. I build AI systems end to end: agents, retrieval and evaluation, down to LLM inference, request routing and the infrastructure underneath. 7 years shipping ML and LLM products at Amazon, Meesho, Paytm and Innovaccer, and founder of [MarketLane AI](https://pyextreme.github.io/projects/marketlane-ai/).

I measure before I ship. Every change is judged on accuracy, cost and latency together, against a bar set before the experiment runs.

**Portfolio and write-ups:** [pyextreme.github.io](https://pyextreme.github.io)

---

#### 🔧 Open source: LLM inference and gateways

I work on the serving stack: routers, schedulers, KV cache, transfer layers and LLM gateways. Contributions since October 2026, each with a root-cause write-up on [my site](https://pyextreme.github.io/open-source/).

| Project | Change | Status |
|---|---|---|
| [llm-d-router](https://github.com/llm-d/llm-d-router) | [Every 200 response read as an error in the EPP](https://pyextreme.github.io/open-source/llm-d-router-3641/) | ✅ [merged](https://github.com/llm-d/llm-d-router/pull/3697) |
| [llm-d-router](https://github.com/llm-d/llm-d-router) | [Keep a request on one rollout revision across a conditional-decode miss](https://pyextreme.github.io/open-source/llm-d-router-3931/) | ✅ [merged](https://github.com/llm-d/llm-d-router/pull/4044) |
| [llm-d-router](https://github.com/llm-d/llm-d-router) | [Warn when a configured data producer is never read](https://pyextreme.github.io/open-source/llm-d-router-3680/) | ✅ [merged](https://github.com/llm-d/llm-d-router/pull/3825) |
| [NIXL](https://github.com/ai-dynamo/nixl) | [Integer overflow that bypassed registration bounds checks](https://pyextreme.github.io/open-source/nixl-2520/) | ✅ [merged](https://github.com/ai-dynamo/nixl/pull/2548) |
| [LiteLLM](https://github.com/BerriAI/litellm) | [Stop caching empty replies in the response cache](https://pyextreme.github.io/open-source/litellm-49931/) | ✅ [merged](https://github.com/BerriAI/litellm/pull/50057) |
| [llm-d-inference-sim](https://github.com/llm-d/llm-d-inference-sim) | [Cross-request data race fix](https://pyextreme.github.io/open-source/llm-d-inference-sim-801/) | ✅ [merged](https://github.com/llm-d/llm-d-inference-sim/pull/803) |
| [vLLM](https://github.com/vllm-project/vllm) | [Reset prefix cache without preempting running requests](https://pyextreme.github.io/open-source/vllm-64853/) | 🔄 [in review](https://github.com/vllm-project/vllm/pull/64865) |
| [NVIDIA Dynamo](https://github.com/ai-dynamo/dynamo) | [Pin hard session affinity to one data-parallel rank](https://pyextreme.github.io/open-source/dynamo-17641/) | 🔄 [in review](https://github.com/ai-dynamo/dynamo/pull/17761) |
| [NVIDIA Dynamo](https://github.com/ai-dynamo/dynamo) | [`/v1/responses` support via path-based dispatch in the EPP](https://pyextreme.github.io/open-source/dynamo-16583/) | 🔄 [in review](https://github.com/ai-dynamo/dynamo/pull/17529) |
| [vLLM Router](https://github.com/vllm-project/router) | [Persistent worker state for discovered P/D routing](https://pyextreme.github.io/open-source/vllm-router-299/) | 🔄 [in review](https://github.com/vllm-project/router/pull/311) |

#### 🧪 Projects

- **[AI Incident Commander](https://github.com/PyExtreme/agentic-incident-response)** ([write-up](https://pyextreme.github.io/projects/ai-incident-commander/)): a pre-registered, equal-budget comparison of multi-agent vs single-agent LLMs for diagnosing microservice incidents, on two models. The single agent matched multi-agent accuracy at 1/3.4 of the cost; about 600 held-out runs for $33.
- **[MarketLane AI](https://pyextreme.github.io/projects/marketlane-ai/)** (my startup, code is private): AI stock selection, rebuilt three times from one cached LLM call to a verified multi-stage pipeline. 90% on top setups for about $4.5 per 100-symbol scan.
- **[MarketLane Research](https://pyextreme.github.io/projects/marketlane-research-rag/)** (my startup, code is private): answers market questions with cited evidence from SEC filings, XBRL facts and market data.

#### 🧰 Toolkit

**AI and agents:** LLMs, agentic AI, RAG, text-to-SQL, multimodal, LangGraph, PyTorch, evaluation design
**Inference and serving:** vLLM, llm-d, NVIDIA Dynamo, Triton
**LLMOps:** Langfuse, Arize Phoenix, OpenTelemetry
**Infra and data:** AWS, GCP, Kubernetes, Docker, PySpark, PostgreSQL + pgvector, Milvus
**Languages:** Python, Go, Rust, C++

#### 📫 Reach me

[pyextreme.github.io](https://pyextreme.github.io) · [LinkedIn](https://www.linkedin.com/in/ankitjha-42) · [ankitjha.email@gmail.com](mailto:ankitjha.email@gmail.com)
