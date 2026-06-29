# Peng Yihan

CS & AI undergraduate at Communication University of China, Class of 2028.

中国传媒大学智能科学与技术 2028 届本科生。

I build trustworthy and cost-aware LLM systems for knowledge-intensive tasks, focusing on evidence auditing, risk-aware refusal, and reliable RAG / agentic workflows.

我目前关注面向知识密集与高风险任务的可信、低成本大模型系统，重点是证据审计、风险门控、可靠 RAG / Agent 工作流，以及证据不足时的保守拒答与人工复核。

## Focus / 研究与工程方向

- **Trustworthy and cost-aware LLM systems / 可信、低成本大模型系统**
- **Evidence auditing, claim-evidence alignment, and source-grounded generation / 证据审计、声明-证据对齐与来源可追溯生成**
- **TrustScore gates, fail-safe refusal, and human-review fallback / TrustScore 门控、保守拒答与人工复核**
- **RAG, KG-RAG, and controlled agentic workflows for high-risk domains / 面向高风险场景的 RAG、KG-RAG 与受控式 Agent 工作流**
- **Reproducible experiments and reliability-cost trade-off analysis / 可复现实验与可靠性-成本权衡分析**

## Featured AI Systems / 代表项目

### MedAudit-RAG / Pediatric Medication Evidence Auditing

Evidence-auditing system for pediatric medication QA, with retrieval, source tracing, TrustScore gating, conservative refusal, and human-review fallback for high-risk medication questions.

面向儿科用药问答的证据审计系统，通过医学指南检索、来源溯源、TrustScore 门控、保守拒答与人工复核提示，降低高风险用药场景中的无证据回答风险。

The goal is not to replace doctors or generate confident medication advice. The system audits whether an answer is evidence-supported, faithful to sources, within safety boundaries, and safe enough to show.

项目目标不是替代医生，也不是生成看似确定的用药建议，而是审计回答是否有证据支持、是否忠实于来源、是否越过安全边界，以及是否适合展示给用户。

**Keywords / 关键词:** medical answer auditing, evidence chain, TrustScore, fail-safe refusal, pediatric medication  
**Tech stack / 技术栈:** FastAPI, LangGraph, ChromaDB, React, Ant Design, SSE

### Traceable Ideological Education KG-RAG

National innovation project for auditable educational QA, exploring KG-RAG, citation tracing, controlled multi-agent review, source checking, and policy-safe answer generation.

国家级大学生创新创业训练计划项目，面向思政教育场景，探索 KG-RAG、Citation 溯源、受控式多智能体审查、来源核验与政治安全回答生成。

The project is designed as an engineering testbed for traceable, source-aware, and reviewable knowledge-intensive AI workflows.

该项目作为可追溯、来源感知、可审查知识密集型 AI 工作流的工程验证场景。

**Keywords / 关键词:** KG-RAG, controlled multi-agent review, traceable generation, educational AI, citation grounding  
**Tech stack / 技术栈:** FastAPI, schema-driven API, hybrid retrieval, knowledge graph modules planned

### VeriMind

Early prototype for trustworthy academic RAG, exploring intent-aware routing, multi-granularity retrieval, faithfulness auditing, and conservative refusal under insufficient evidence.

面向学术知识库的可信 RAG 原型系统，探索意图感知路由、多粒度检索、回答忠实度审计，以及证据不足时的保守拒答机制。

**Keywords / 关键词:** Agentic RAG, hallucination control, evidence-grounded generation, scientific QA  
**Tech stack / 技术栈:** Python, LlamaIndex, DashScope, ChromaDB, Streamlit
