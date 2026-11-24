# EPAM Systems Engineering & AI Architectures Portfolio

> **Author:** Pratyaksh Kumar ([@Pratyaksh82](https://github.com/Pratyaksh82))  
> **Track:** Software Engineering, Distributed Systems & Enterprise AI  
> **Program:** EPAM Technical Training & Team Cadence Evaluation

---

## 📌 Executive Summary

This repository hosts a curated collection of deep-dive architectural documents, hardware-level systems research, and enterprise AI engineering modules created during the **EPAM Technical Training** program.

The curriculum is structured around high-concurrency systems, low-level execution models, and modern agentic AI infrastructure:
- **Low-Level Hardware & Systems:** Cache coherency (MESI), store buffers, instruction reordering, memory barriers, lock-free concurrency, CAS mechanics, and CPython runtime internals.
- **Enterprise AI Systems & LLM Internals:** Transformer tokenization, self-attention, context window budgeting, automated evaluation harnesses, LLM-as-a-Judge validation, Agent-to-Agent (A2A) protocols, and the Model Context Protocol (MCP).

---

## 📂 Repository Structure

```text
epam/
├── README.md               <-- Main repository overview (this document)
│
├── Sprint 1/               <-- Sprint 1: Concurrency, Hardware Models & AI Foundations
│   ├── README.md           <-- Sprint 1 detailed syllabus and topic breakdown
│   ├── 01_Hardware_Concurrency_and_MESI.docx
│   ├── 02_Lock_Free_Concurrency_and_LMAX_Disruptor.docx
│   ├── 03_AI_Foundations_and_LLM_Internals.docx
│   ├── 04_Prompt_Evaluation_and_QA_Pipelines.docx
│   ├── 05_Context_Engineering_and_Memory_Systems.docx
│   ├── 06_AI_Fluency_in_Software_Engineering.docx
│   ├── 07_AI_Orchestration_and_Resilient_Workflows.docx
│   ├── 08_Agent_to_Agent_A2A_Communication.docx
│   ├── 09_Model_Context_Protocol_MCP.docx
│   └── 10_Python_Internals_and_Concurrency_Performance.docx
│
└── [Upcoming Sprints]      <-- Additional sprint modules, case studies, and code benchmarks
```

---

## 📑 Sprint-by-Sprint Curriculum Overview

### 🔹 Sprint 1: Concurrency, Memory Models & Agentic AI

| # | Topic | Document | Key Technical Highlights |
| :-: | :--- | :--- | :--- |
| **01** | **Hardware Concurrency & MESI** | [01_Hardware_Concurrency_and_MESI.docx](Sprint%201/01_Hardware_Concurrency_and_MESI.docx) | Store buffers, invalidate queues, Acquire-Release semantics, and memory barriers. |
| **02** | **Lock-Free Concurrency & Disruptor** | [02_Lock_Free_Concurrency_and_LMAX_Disruptor.docx](Sprint%201/02_Lock_Free_Concurrency_and_LMAX_Disruptor.docx) | Cache-line bouncing, false sharing mitigation, CAS atomics, and LMAX Disruptor ring buffers. |
| **03** | **AI Foundations & LLM Internals** | [03_AI_Foundations_and_LLM_Internals.docx](Sprint%201/03_AI_Foundations_and_LLM_Internals.docx) | Self-attention mechanics, tokenization, temperature/Top-P sampling, and hallucination guardrails. |
| **04** | **Prompt Evaluation & QA Pipelines** | [04_Prompt_Evaluation_and_QA_Pipelines.docx](Sprint%201/04_Prompt_Evaluation_and_QA_Pipelines.docx) | Golden evaluation datasets, deterministic unit checks, and LLM-as-a-Judge calibration. |
| **05** | **Context Engineering & Memory** | [05_Context_Engineering_and_Memory_Systems.docx](Sprint%201/05_Context_Engineering_and_Memory_Systems.docx) | Context budget allocation, tool output pruning, short/long-term memory, and hybrid RAG. |
| **06** | **AI Fluency in Software Engineering** | [06_AI_Fluency_in_Software_Engineering.docx](Sprint%201/06_AI_Fluency_in_Software_Engineering.docx) | Problem decomposition, critical code verification, and deterministic vs. probabilistic tooling. |
| **07** | **AI Orchestration & Workflows** | [07_AI_Orchestration_and_Resilient_Workflows.docx](Sprint%201/07_AI_Orchestration_and_Resilient_Workflows.docx) | Multi-agent architectures, supervisor patterns, state checkpointing, and distributed tracing. |
| **08** | **Agent-to-Agent (A2A) Protocols** | [08_Agent_to_Agent_A2A_Communication.docx](Sprint%201/08_Agent_to_Agent_A2A_Communication.docx) | Contract schemas, Agent Cards, loop detection, and least-privilege security boundaries. |
| **09** | **Model Context Protocol (MCP)** | [09_Model_Context_Protocol_MCP.docx](Sprint%201/09_Model_Context_Protocol_MCP.docx) | Client-Host-Server topology, standard primitives (Tools, Prompts, Resources), and security. |
| **10** | **Python Internals & Concurrency** | [10_Python_Internals_and_Concurrency_Performance.docx](Sprint%201/10_Python_Internals_and_Concurrency_Performance.docx) | CPython GIL mechanics, `asyncio` event loops, multiprocessing, and generator optimization. |

---

## 🛠️ Document Standards

Every module document follows an enterprise-grade technical format:
1. **Architectural Foundations:** Rigorous explanation of runtime theory, mechanics, and design constraints.
2. **Trade-Off & Decision Matrix:** Comparison frameworks mapping design patterns to production scale.
3. **Assessment Scenarios & Solutions:** Architectural problem-solving, code solutions, and anti-patterns.

---

## 👤 Author & Acknowledgments

- **Pratyaksh Kumar** — [GitHub Profile](https://github.com/Pratyaksh82)
- Prepared for the **EPAM Technical Assessment & Training Track**.
