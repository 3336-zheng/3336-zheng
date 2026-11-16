<div align="center">

**Python Backend · AI Agent · RAG Systems · Edge Speech**

构建可解释、可恢复、可持续演进的智能应用。<br>
Building intelligent applications that are explainable, recoverable, and built to evolve.

[![GitHub](https://img.shields.io/badge/GitHub-3336--zheng-181717?style=flat-square&logo=github)](https://github.com/3336-zheng)
[![Email](https://img.shields.io/badge/Email-2868687158%40qq.com-2C7A7B?style=flat-square&logo=maildotru&logoColor=white)](mailto:2868687158@qq.com)
[![CSDN](https://img.shields.io/badge/CSDN-zhengjhzuishuai-FC5531?style=flat-square&logo=csdn&logoColor=white)](https://blog.csdn.net/zhengjhzuishuai)

</div>

```text
关注最前沿的 AI 领域，探讨 AI 提效的可能性
Exploring the frontier of AI and how it can make engineering teams more effective.
```

## 关于我 / About Me

目前专注于 Python 后端、AI Agent、可信 RAG 与端侧语音技术。我更关注模型之外的工程问题：数据如何可靠落盘、检索结果如何追溯、Agent 如何恢复与观测，以及写操作如何保持可控。

I focus on Python backend engineering, AI agents, trustworthy RAG, and on-device speech. My interests sit beyond the model itself: how data is durably persisted, how retrieval results can be traced, how agents recover and are observed, and how write operations stay under control.

- **Agent 工程 / Agent Engineering**：LangGraph 状态编排、多 Agent 协作、流式事件、失败恢复与幂等执行。<br>
  LangGraph state orchestration, multi-agent collaboration, streaming events, failure recovery, and idempotent execution.
- **RAG 系统 / RAG Systems**：BM25、Embedding、RRF、Reranker、父子分块、Token 预算与证据判断。<br>
  BM25, embeddings, RRF, rerankers, parent-child chunking, token budgets, and evidence gating.
- **后端工程 / Backend Engineering**：FastAPI、SQLAlchemy、SQLite、异步任务、生命周期管理与可观测性。<br>
  FastAPI, SQLAlchemy, SQLite, asynchronous tasks, lifecycle management, and observability.
- **端侧智能 / On-Device AI**：ASR、关键词识别、PyTorch、ONNX 与本地模型部署。<br>
  ASR, keyword spotting, PyTorch, ONNX, and local model deployment.

## 代表项目 / Featured Projects

| 项目 / Project | 核心内容 / Highlights | 技术栈 / Stack |
| --- | --- | --- |
| [DSH Observatory](https://github.com/3336-zheng/dsh-observatory) | **中**：DeepSeek Harness 的 Agent 可观测工作台，让执行轨迹、上下文来源、工具表现和插件配置可见、可诊断、可复盘。<br>**EN**: An agent observability workbench for DeepSeek Harness that makes execution traces, context provenance, tool performance, and plugin configuration visible, diagnosable, and reviewable. | TypeScript · React · DeepSeek Harness · Vitest · Playwright |
| [智语 / Zhiyu](https://github.com/3336-zheng/zhiyu-voice-assistant) | **中**：本地优先 AI Wiki，将语音、文档和笔记沉淀为可维护知识库；支持可信 RAG、可恢复 Agent Runtime、MCP 外部研究与确认式写入。<br>**EN**: A local-first AI wiki that turns voice, documents, and notes into a maintainable knowledge base, with trustworthy RAG, a recoverable agent runtime, MCP-based external research, and confirmation-based writes. | Python · FastAPI · LangGraph · ChromaDB · Agent · RAG |
| [CodeReviewer Orchestrator](https://github.com/3336-zheng/CodeReviewer-Orchestrator) | **中**：多智能体代码评审系统，并行执行风格、安全、性能、逻辑与提交质量检查，再由仲裁 Agent 去重并生成结构化报告。<br>**EN**: A multi-agent code review system that runs style, security, performance, logic, and commit-quality checks in parallel, then uses an arbitration agent to deduplicate findings and generate a structured report. | Python · LangGraph · LangChain · FastAPI · SSE · SQLite |
| [ArcFace CNN Word Classifier](https://github.com/3336-zheng/ArcFace-CNN-classifying_words-model_ONNX) | **中**：面向词分类识别的机器学习项目，覆盖 CNN 模型训练与 ONNX 推理。<br>**EN**: A machine learning project for word classification, covering CNN model training and ONNX inference. | Python · CNN · ONNX |

## 技术栈 / Tech Stack

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img alt="LangGraph" src="https://img.shields.io/badge/LangGraph-20232A?style=flat-square" />
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img alt="ONNX" src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" />
</p>

## 工程关注点 / Engineering Focus

| 关注点 / Focus | 实践 / Practices |
| --- | --- |
| 可靠性 / Reliability | 状态机 · 幂等 · 超时 · 重试 · 重启恢复<br>State machines · Idempotency · Timeouts · Retries · Restart recovery |
| 可信检索 / Trustworthy Retrieval | 混合召回 · 统一融合 · 精排 · 引用 · 证据门禁<br>Hybrid recall · Unified fusion · Reranking · Citations · Evidence gating |
| 数据边界 / Data Boundaries | Markdown 主数据 · SQLite 元数据 · 可重建索引<br>Markdown as the source of truth · SQLite metadata · Rebuildable indexes |
| 可观测性 / Observability | Request ID · 阶段耗时 · Token 用量 · 运行记录<br>Request IDs · Stage latency · Token usage · Execution records |
| 安全性 / Security | 输入校验 · 确认式写入 · 外部来源隔离 · 密钥边界<br>Input validation · Confirmation-based writes · External-source isolation · Secret boundaries |

> 持续学习如何把模型能力变成真正可靠、可维护的产品能力。<br>
> Continuously learning how to turn model capabilities into genuinely reliable, maintainable product capabilities.
