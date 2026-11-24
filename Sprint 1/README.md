# Sprint 1 Deliverables — EPAM Technical Training

> **Track:** Software Engineering, Systems Architecture & Enterprise AI  
> **Submission Period:** Sprint 1 Review  

---

## 📌 Overview

This directory contains the finalized technical documentation and architectural research reports for **Sprint 1**. All documents are published in **PDF format** for direct in-browser previewing on GitHub.

Topics span hardware-level memory models and low-latency concurrency patterns up to enterprise Large Language Model (LLM) orchestration, evaluation harnesses, and agent interaction standards.

---

## 📑 Module Index

| Topic | Document (PDF) | Core Engineering Focus |
| :--- | :--- | :--- |
| **Hardware Concurrency** | [Hardware Concurrency and MESI Protocol.pdf](./Hardware%20Concurrency%20and%20MESI%20Protocol.pdf) | Store buffers, instruction reordering, Acquire-Release semantics, and MESI cache states. |
| **Lock-Free Concurrency** | [Lock-Free Data Structures and LMAX Disruptor.pdf](./Lock-Free%20Data%20Structures%20and%20LMAX%20Disruptor.pdf) | Cache-line bouncing, false sharing mitigation, CAS atomics, and Disruptor ring buffers. |
| **AI Foundations** | [AI Foundations and LLM Architecture.pdf](./AI%20Foundations%20and%20LLM%20Architecture.pdf) | Tokenization, self-attention mechanics, temperature sampling, and hallucination guardrails. |
| **Prompt Evaluation** | [Prompt Evaluation and Automated QA Testing.pdf](./Prompt%20Evaluation%20and%20Automated%20QA%20Testing.pdf) | Golden datasets, deterministic test assertions, and LLM-as-a-Judge calibration. |
| **Context Engineering** | [Context Window Management and Memory Systems.pdf](./Context%20Window%20Management%20and%20Memory%20Systems.pdf) | Context budgeting, tool output pruning, short/long-term memory, and hybrid RAG. |
| **AI Fluency** | [AI Fluency and Engineering Workflows.pdf](./AI%20Fluency%20and%20Engineering%20Workflows.pdf) | Task decomposition, critical verification of AI output, and deterministic tooling. |
| **AI Orchestration** | [AI Orchestration and Fault-Tolerant Pipelines.pdf](./AI%20Orchestration%20and%20Fault-Tolerant%20Pipelines.pdf) | Multi-agent architectures, supervisor patterns, checkpointing, and error recovery. |
| **Agent Communication** | [Agent-to-Agent Protocols and Interaction Contracts.pdf](./Agent-to-Agent%20Protocols%20and%20Interaction%20Contracts.pdf) | JSON communication contracts, Agent Cards, loop detection, and isolation boundaries. |
| **Model Context Protocol** | [Model Context Protocol and Tool Integration.pdf](./Model%20Context%20Protocol%20and%20Tool%20Integration.pdf) | Client-Host-Server architecture, standard primitives (Tools, Resources, Prompts). |
| **Python Internals** | [Python Runtime Internals and Concurrency Tuning.pdf](./Python%20Runtime%20Internals%20and%20Concurrency%20Tuning.pdf) | CPython GIL mechanics, `asyncio` event loops, multiprocessing, and generator optimization. |

---

## 🏗️ Document Architecture

Each document follows a structured 3-part layout:
1. **Architectural Foundations & Theory:** Deep dive into mechanics, execution models, and operational tradeoffs.
2. **Technical Reference & Comparison:** Side-by-side matrices contrasting alternative designs.
3. **Assessment Scenarios & Case Studies:** Scenario-based engineering problem breakdowns and anti-patterns.
