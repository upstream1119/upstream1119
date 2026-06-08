# Peng Yihan

中国传媒大学智能科学与技术 2028 届本科生。  
关注 **Evidence-grounded AI Systems**、可信 RAG、大模型后端工程，以及低容错场景下的生成内容审计。

我现在主要做的事情不是单纯“把模型接进应用”，而是让 AI 系统具备更清楚的证据边界：能检索来源、展示证据、审计回答，并在证据不足时保守拒答或进入人工复核。

## Focus

- Evidence-grounded RAG and answer auditing
- Trust-Score gating, fail-closed refusal and human-review fallback
- Claim-evidence alignment and replayable audit traces
- AI backend engineering with FastAPI, LangGraph, ChromaDB, SSE and Docker
- Medical, educational and scientific-document scenarios where hallucination is costly

## Featured AI Systems

### VeriMind-MedAudit

A pediatric-medication evidence auditing prototype for safer medical AI responses.

The project is not designed to replace doctors or generate confident medication advice. Its core goal is to audit whether a medical answer is supported by retrieved evidence, faithful to guidelines, within safety boundaries, and safe enough to show. When the knowledge base is incomplete, evidence is insufficient, or the index is not ready, the system follows a fail-closed strategy and prefers refusal or human review over unsupported generation.

**Keywords:** medical answer auditing, evidence chain, Trust-Score, fail-closed safety, pediatric medication  
**Tech stack:** FastAPI, LangGraph, ChromaDB, React, Ant Design, SSE

### VeriMind

A trustworthy Agentic RAG prototype for scientific knowledge bases.

It explores intent-aware routing, multi-granularity retrieval, answer faithfulness auditing, Trust-Score gating and conservative refusal when evidence is insufficient.

**Keywords:** Agentic RAG, hallucination control, evidence-grounded generation, scientific QA  
**Tech stack:** Python, LlamaIndex, DashScope, ChromaDB, Streamlit

### Traceable Cross-modal System for Ideological Education

National College Student Innovation and Entrepreneurship Training Program project.

The project explores traceable educational AI interaction with hybrid retrieval, knowledge graph modules, citation grounding, political safety review and cross-modal presentation.

**Keywords:** KG-RAG, traceable generation, educational AI, citation grounding  
**Tech stack:** FastAPI, schema-driven API, hybrid retrieval, knowledge graph modules planned

## Research & Modeling

### Statistical Modeling 2026

A reproducible modeling project on digital inclusive finance and regional low-carbon transition, focusing on provincial panel data, spatial autocorrelation, SAR / SEM / SDM models, robustness checks and result tables.

## Roadmap

- Short term: harden MedAudit into a clearer evidence-auditing demo and evaluation workflow
- Summer 2026: explore multimodal RAG and chart-text / figure-caption evidence alignment
- Long term: build personal Agent OS and reusable evidence-grounded workflow systems
