# Peng Yihan｜彭意涵

中国传媒大学智能科学与技术 2028 届本科生。  
Undergraduate student in Intelligent Science and Technology, Communication University of China, Class of 2028.

我关注 **Evidence-grounded AI Systems**、可信 RAG、大模型后端工程，以及低容错场景下的生成内容审计。  
I focus on **evidence-grounded AI systems**, trustworthy RAG, LLM backend engineering, and generation auditing in low-tolerance scenarios.

我现在主要做的事情不是单纯“把模型接进应用”，而是让 AI 系统具备更清楚的证据边界：能检索来源、展示证据、审计回答，并在证据不足时保守拒答或进入人工复核。  
My current work is not just about plugging models into applications. I care more about building systems that can retrieve evidence, expose sources, audit generated answers, and trigger refusal or human review when evidence is insufficient.

## 研究与工程方向｜Focus

- **证据驱动 RAG 与回答审计**｜Evidence-grounded RAG and answer auditing
- **Trust-Score 门控、fail-closed 拒答与人工复核**｜Trust-Score gating, fail-closed refusal and human-review fallback
- **Claim-evidence alignment 与可回放审计轨迹**｜Claim-evidence alignment and replayable audit traces
- **AI 后端工程**：FastAPI、LangGraph、ChromaDB、SSE、Docker｜AI backend engineering with FastAPI, LangGraph, ChromaDB, SSE and Docker
- **医疗、教育、科研文献等低容错场景**｜Medical, educational and scientific-document scenarios where hallucination is costly

## 代表项目｜Featured AI Systems

### MedAudit-RAG

MedAudit-RAG：基于规则感知证据审计的儿科用药低幻觉问答系统。  
MedAudit-RAG: Rule-Aware Evidence Auditing for Low-Hallucination Pediatric Medication QA.

项目目标不是替代医生，也不是生成看似确定的用药建议，而是审计医学回答是否有证据支撑、是否忠实于指南、是否越过安全边界，以及是否应该展示给用户。  
The goal is not to replace doctors or generate confident medication advice. The system audits whether a medical answer is evidence-supported, faithful to guidelines, within safety boundaries, and safe enough to show.

当知识库不完整、证据不足或索引状态异常时，系统采用 **fail-closed** 策略，优先拒答或提示人工复核，而不是继续生成无依据结论。  
When the knowledge base is incomplete, evidence is insufficient, or the index is not ready, the system follows a **fail-closed** strategy and prefers refusal or human review over unsupported generation.

**关键词｜Keywords:** 医学回答审计、证据链、Trust-Score、fail-closed 安全策略、儿科用药｜medical answer auditing, evidence chain, Trust-Score, fail-closed safety, pediatric medication  
**技术栈｜Tech stack:** FastAPI, LangGraph, ChromaDB, React, Ant Design, SSE

### VeriMind

面向科研知识库的可信 Agentic RAG 原型系统。  
A trustworthy Agentic RAG prototype for scientific knowledge bases.

项目探索意图感知路由、多粒度检索、回答忠实度审计、Trust-Score 门控，以及证据不足时的保守拒答机制。  
It explores intent-aware routing, multi-granularity retrieval, answer faithfulness auditing, Trust-Score gating, and conservative refusal when evidence is insufficient.

**关键词｜Keywords:** Agentic RAG、幻觉控制、证据驱动生成、科研问答｜Agentic RAG, hallucination control, evidence-grounded generation, scientific QA  
**技术栈｜Tech stack:** Python, LlamaIndex, DashScope, ChromaDB, Streamlit

### 可溯源跨模态思政教育系统｜Traceable Cross-modal System for Ideological Education

国家级大学生创新创业训练计划项目。  
A National College Student Innovation and Entrepreneurship Training Program project.

项目面向思政教育场景，探索混合检索、知识图谱模块、Citation 溯源、政治安全审查与跨模态交互展示。  
The project explores traceable educational AI interaction with hybrid retrieval, knowledge graph modules, citation grounding, political safety review, and cross-modal presentation.

**关键词｜Keywords:** KG-RAG、可溯源生成、教育 AI、引用溯源｜KG-RAG, traceable generation, educational AI, citation grounding  
**技术栈｜Tech stack:** FastAPI, schema-driven API, hybrid retrieval, knowledge graph modules planned

## 建模项目｜Research & Modeling

### Statistical Modeling 2026

围绕数字普惠金融与区域低碳转型的空间计量建模项目，重点是省级面板数据、空间自相关、SAR / SEM / SDM 模型、稳健性检验和可复现结果表。  
A reproducible modeling project on digital inclusive finance and regional low-carbon transition, focusing on provincial panel data, spatial autocorrelation, SAR / SEM / SDM models, robustness checks, and result tables.

## 近期路线｜Roadmap

- **近期**：完善 MedAudit 的证据审计演示和评测工作流｜Harden MedAudit into a clearer evidence-auditing demo and evaluation workflow
- **2026 暑期**：探索多模态 RAG 与图表-正文证据对齐｜Explore multimodal RAG and chart-text / figure-caption evidence alignment
- **长期**：构建个人 Agent OS 与可复用的 evidence-grounded workflow systems｜Build personal Agent OS and reusable evidence-grounded workflow systems
