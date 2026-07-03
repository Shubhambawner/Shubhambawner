# Hi, I'm Shubham 👋

I am a Software Engineer building AI-powered systems, agentic workflows, and scalable backend platforms.

Currently working on:
* AI Agents & Multi-Agent Systems
* Retrieval Augmented Generation (RAG)
* FastAPI & Distributed Backend Services
* Search & Knowledge Systems using Elasticsearch
* LLM-powered Developer Productivity Tools

---

### Let's Talk Production AI Architecture
I am deeply focused on the practical design patterns of agentic systems. Here are the core architectural challenges I am actively solving, along with the engineering blueprints I reference:

* **Chunking & Embedding Pipelines**
  * *The Challenge:* How do we decide on appropriate chunking and embedding strategies for different data types and sources?
  * *Core Reference:* LlamaIndex's [Advanced Chunking and Strategy Playbook](https://docs.llamaindex.ai/en/stable/optimizing/advanced_retrieval/advanced_retrieval/) for handling heterogeneous data parsing, semantic splitting, and embedding drift.

* **Retrieval Strategy Optimization**
  * *The Challenge:* How do we design retrieval strategies that balance recall constraints with strict latency budgets?
  * *Core Reference:* Pinecone's [System Architecture Blueprints](https://www.pinecone.io/learn/retrieval-augmented-generation/) and Arize Phoenix's [RAG Evaluation Framework](https://docs.arize.com/phoenix/) for optimizing hybrid search, reranking via tools like Cohere, and handling document attribution.

* 💸 **Cost-Efficient Execution & Workflow Discovery**
  * *The Challenge:* How do we prevent token bloat, optimize agentic runtimes, and automatically discover/reuse workflow patterns to minimize cost?
  * *Core Reference:* arXiv's [Agent Workflow Optimization (AWO) Framework](https://arxiv.org/html/2601.22037v2) and GitHub's [Engineering Guide to Token Efficiency](https://github.blog/ai-and-ml/github-copilot/improving-token-efficiency-in-github-agentic-workflows/) for analyzing trajectory traces, compressing iterative loops into deterministic meta-tools, and utilizing semantic tool caching.
 
* **Production Agent Evaluation**
  * *The Challenge:* How do we evaluate agentic solutions and iteration changes for true production fit?
  * *Core Reference:* Anthropic’s [Building Effective Agents](https://www.anthropic.com/research/building-effective-agents) and MLflow's [LLM-as-a-Judge Evaluation Suites](https://mlflow.org/articles/top-llm-observability-tools-in-2026-a-pro-guide/) to transition away from static checklists toward step-wise and end-to-end evaluation metrics.

* **Memory Architecture Design**
  * *The Challenge:* How do we build appropriate memory architectures tailored to specific production use cases?
  * *Core Reference:* LangChain and LangGraph's [State and Memory Persistence Concepts](https://python.langchain.com/v0.2/docs/concepts/#memory) for tracking conversational buffers, semantic summary layers, and rigid token limits.

* **Logging, Tracing, & Observability**
  * *The Challenge:* How do we implement reliable logging, tracing, and monitoring across complex agent networks?
  * *Core Reference:* Langfuse's [Distributed Trace Instrumentation Guides](https://medium.com/@writetopavan/evaluating-agentic-systems-with-langfuse-a-short-guide-c227a6b75fc6) for tracking nested sub-agent spans, tool execution delays, and transaction graph exceptions under live user traffic.

---

### Technical Specializations
* **Agentic AI:** Multi-Agent Orchestration | Self-Healing State Loops | Token-Optimized Workflows
* **Information Retrieval:** Advanced RAG | Hybrid Vector Search | Semantic Document Chunking | Elasticsearch
* **Backend Platform:** FastAPI | Distributed Background Workers | Prompt Engineering Production Primitives

---

### Areas of Interest 

* Generative AI & Agentic Workflows
* Multi-Agent Systems & Tool Calling
* Model Context Protocol (MCP)
* Advanced RAG & Vector Databases
* Semantic Search & Enterprise Search Systems
* LLM Evaluation, Prompt, and Context Engineering
* Workflow Orchestration & Knowledge Graphs

---

### Open Source Involvements

* **[shiksha-platform/frontend-modulefederation (#119)](https://github.com/shiksha-platform/frontend-modulefederation/pull/119)**: Implemented micro-frontend architecture solutions to scale web platform modularity.
* **[microsoft/STL (#2844)](https://github.com/microsoft/STL/discussions/2844)**: Engaged in low-level systems architecture design discussions regarding the standard template library.
* **[primer/react (#2284)](https://github.com/primer/react/discussions/2284)**: Collaborated on UI framework design patterns within GitHub's official Primer design system.
