# EPAM Technical Training & Assessment Portfolio — Sprint 1

> **Track:** Software & AI Systems Engineering  
> **Submission:** Training & Placement (TNP) Cell  
> **Directory:** `sprint 1/`

---

## 📌 Overview

This repository folder (`sprint 1`) contains structured architectural study documentation, trade-off analyses, and assessment readiness notes completed as part of the **EPAM Technical Training & Team Cadence Evaluation** program.

The curriculum spans **10 core engineering modules**, bridging low-level multi-core hardware concurrency and CPython runtime internals with modern production AI systems engineering—covering Large Language Model (LLM) internals, automated prompt evaluation, context engineering, multi-agent orchestration, Agent-to-Agent (A2A) protocols, and the Model Context Protocol (MCP).

---

## 📂 Sprint 1 Documentation Index

All study modules are organized sequentially inside the `sprint 1` directory as professionally formatted `.docx` technical reports:

| # | Module Title | Document File | Core Engineering Focus |
| :-: | :--- | :--- | :--- |
| **01** | **Hardware Concurrency & Memory Models** | [`01_Hardware_Concurrency_and_MESI.docx`](./01_Hardware_Concurrency_and_MESI.docx) | Store buffers, CPU instruction reordering, Acquire-Release memory barriers, and MESI cache coherence states. |
| **02** | **Lock-Free Systems & Cache Performance** | [`02_Lock_Free_Concurrency_and_LMAX_Disruptor.docx`](./02_Lock_Free_Concurrency_and_LMAX_Disruptor.docx) | Cache-line bouncing, false sharing mitigations, atomic Compare-And-Swap (CAS), ABA prevention, and the LMAX Disruptor pattern. |
| **03** | **AI Foundations & LLM Internals** | [`03_AI_Foundations_and_LLM_Internals.docx`](./03_AI_Foundations_and_LLM_Internals.docx) | Tokenization, embeddings, self-attention, autoregressive inference, Prompting vs. RAG vs. Fine-Tuning, sampling controls, and hallucination guardrails. |
| **04** | **Prompt Evaluation & Automated QA** | [`04_Prompt_Evaluation_and_QA_Pipelines.docx`](./04_Prompt_Evaluation_and_QA_Pipelines.docx) | Golden evaluation datasets, deterministic assertions vs. LLM-as-a-Judge, CI/CD regression gates, and judge bias calibration. |
| **05** | **Context Engineering & Memory Systems** | [`05_Context_Engineering_and_Memory_Systems.docx`](./05_Context_Engineering_and_Memory_Systems.docx) | Runtime context budgeting, short-term vs. long-term memory, compaction, tool-output pruning, and hybrid RAG search (dense + BM25 + reranking). |
| **06** | **AI Fluency in Software Engineering** | [`06_AI_Fluency_in_Software_Engineering.docx`](./06_AI_Fluency_in_Software_Engineering.docx) | Problem decomposition, critical verification of AI-generated code, deterministic vs. probabilistic tool selection, and privacy hygiene. |
| **07** | **AI Orchestration & Resilient Workflows** | [`07_AI_Orchestration_and_Resilient_Workflows.docx`](./07_AI_Orchestration_and_Resilient_Workflows.docx) | Single vs. multi-agent architecture, sequential/parallel/supervisor patterns, step checkpointing, fault recovery, and distributed observability. |
| **08** | **Agent-to-Agent (A2A) Communication** | [`08_Agent_to_Agent_A2A_Communication.docx`](./08_Agent_to_Agent_A2A_Communication.docx) | Versioned JSON contracts, Agent Cards, shared state vs. message passing, ping-pong loop prevention, and least-privilege security. |
| **09** | **Model Context Protocol (MCP)** | [`09_Model_Context_Protocol_MCP.docx`](./09_Model_Context_Protocol_MCP.docx) | Client-Host-Server topology, Tools/Resources/Prompts primitives, `stdio` vs. `Streamable HTTP` transports, and security governance. |
| **10** | **Python Internals & Concurrency** | [`10_Python_Internals_and_Concurrency_Performance.docx`](./10_Python_Internals_and_Concurrency_Performance.docx) | CPython Global Interpreter Lock (GIL), `asyncio` vs. `threading` vs. `multiprocessing`, $O(1)$ memory generators, and object semantics. |

---

## 🏗️ Structure of Each Document

Every module report follows a standardized three-part engineering template:
1. **Architectural Overview & Core Concepts:** Deep-dive explanations of underlying mechanics and runtime behavior.
2. **Technical Reference & Trade-Off Matrix:** Structured side-by-side comparison tables mapping architectural choices to production workloads.
3. **Assessment Questions, Solutions & Anti-Patterns:** Interview-grade engineering solutions paired with common pitfalls and key takeaways.

---

## 🚀 Repository Layout

```text
├── readme
└── sprint 1/
    ├── 01_Hardware_Concurrency_and_MESI.docx
    ├── 02_Lock_Free_Concurrency_and_LMAX_Disruptor.docx
    ├── 03_AI_Foundations_and_LLM_Internals.docx
    ├── 04_Prompt_Evaluation_and_QA_Pipelines.docx
    ├── 05_Context_Engineering_and_Memory_Systems.docx
    ├── 06_AI_Fluency_in_Software_Engineering.docx
    ├── 07_AI_Orchestration_and_Resilient_Workflows.docx
    ├── 08_Agent_to_Agent_A2A_Communication.docx
    ├── 09_Model_Context_Protocol_MCP.docx
    └── 10_Python_Internals_and_Concurrency_Performance.docx
```

> **Note for Reviewers:** If placing `readme` inside the `sprint 1/` folder directly, the relative document links in the index table above (`./01_...docx`) will open each file directly in GitHub. If placing `readme` at the repository root, prefix the links with `./sprint%201/`.