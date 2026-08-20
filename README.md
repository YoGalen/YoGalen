<h1 align="center">Hi, I'm Jialun Yao</h1>

<p align="center">
  <strong>AI Agent Engineer focused on reliable workflow automation and production-grade LLM applications.</strong>
</p>

<p align="center">
  I build agent runtimes, multi-agent systems, RAG pipelines, and evaluation-driven AI products.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" alt="LangGraph" />
  <img src="https://img.shields.io/badge/AutoGen-0066CC?style=flat-square" alt="AutoGen" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/vLLM-7C3AED?style=flat-square" alt="vLLM" />
</p>

## About Me

I enjoy turning LLM capabilities into dependable systems that can be measured, tested, and improved. My recent work spans natural-language-to-workflow generation, agent runtime design, prompt caching, multi-agent orchestration, retrieval-augmented generation, lightweight fine-tuning, and automated evaluation.

- Building Agent Harness and Runtime components for enterprise workflow automation
- Experienced with ReAct, MCP, workflow DSLs, state management, and tool orchestration
- Hands-on with LangGraph, AutoGen, LangChain, QLoRA, RAGAS, and vLLM
- Comfortable reading English technical documentation and working in international teams
- Open to graduate opportunities in AI Agent and LLM application engineering

## Experience

### AI Agent Engineering Intern | Zoom

`May 2026 - Present` | `Hangzhou, China`

Contributing to the Zoom Agentic Workflow platform, integrating Zoom services with tools such as Gmail and Salesforce and developing a CUI Harness that converts natural-language requests into executable workflows.

- Built a CUI-to-Workflow pipeline covering routing, agent management, intent classification, ambiguity handling, dependency resolution, sequential reasoning, tool validation, fallback strategies, and DSL generation.
- Increased CUI intent recognition accuracy from **77% to approximately 95%**, reduced end-to-end generation failures by **about 30%**, and improved weekly user retention by **7%**.
- Designed hierarchical prompt caching, tool eviction, token estimation, and workflow contract validation, reducing average token usage per turn by **68%** and average latency by **about 50%**.
- Built an automated workflow-tool inspection pipeline with **95% regression coverage**, surfacing integration issues at least one week earlier.
- Delivered **12 reusable workflow templates** across HR, sales, and meeting-summary scenarios, supporting **80K+ weekly runs** with **97% end-to-end success** and over **40% lower token usage** than comparable earlier templates.

## Featured Projects

### Qwen_Medical_Q-A

An intelligent pre-consultation agent that turns multi-turn symptom conversations into structured medical records and assisted triage suggestions, with retrieval augmentation and explicit safety controls.

- Fine-tuned **Qwen3-32B-Instruct** with 4-bit NF4 QLoRA, keeping trainable parameters below **1%** and reducing GPU memory usage by more than **70%**.
- Rebuilt the RAG flow as a multi-node LangGraph agent with an upfront safety gate, cross-turn profile tracking, and LLM-as-Judge reflection.
- Combined Redis short-term memory, SQLite structured profiles, and Milvus semantic retrieval with token-budget-aware context truncation.
- Deployed dynamic LoRA adapters with vLLM and PagedAttention-based KV cache management.
- Built a three-layer retrieval, generation, and safety evaluation pipeline, improving the RAGAS score from **0.71 to 0.89** and reaching a **90% hallucination suppression rate**.

### AutoGen_Trading_Agent

A multi-agent A-share market analysis system that transforms market news, watchlists, and sector movements into scheduled analytical reports and risk-aware insights.

- Designed an AutoGen GroupChat architecture and replaced free-form LLM routing with an FSM for deterministic state transitions, reducing multi-turn token usage by **about 20%**.
- Built bilingual semantic retrieval with ChromaDB and multilingual embeddings, improving Top-3 retrieval recall by **about 15%**.
- Added sandbox execution, static scanning, safety review, and self-correction loops, reducing API-related errors to **2%**.
- Developed a DistilBERT-based financial sentiment pipeline with a keyword-weighted fallback path and integrated its score into downstream risk analysis.

## Technical Toolbox

| Area | Technologies |
| --- | --- |
| Agent Engineering | Agent Harness, Agent Runtime, ReAct, MCP, Workflow DSL, tool orchestration |
| Frameworks | LangGraph, AutoGen, LangChain, FastAPI |
| LLM and Fine-Tuning | Transformer, QLoRA, LoRA, PEFT, prompt engineering |
| RAG and Evaluation | Hybrid retrieval, reranking, RAGAS, LLM-as-Judge, safety evaluation |
| Inference and Storage | vLLM, Milvus, ChromaDB, Redis, SQLite |
| Development | Python, PyTorch, SSE, Git, Jira, Slack |

## Engineering Principles

- Prefer reliable execution paths over opaque agent behavior.
- Use deterministic control flow where business rules demand predictability.
- Treat evaluation, observability, and fallback handling as product features.
- Optimize quality, latency, and token cost together.
- Build reusable components that can move from prototypes to real workloads.

---

Open to graduate opportunities and technical collaboration in AI Agent Engineering, LLM applications, and intelligent workflow systems.

