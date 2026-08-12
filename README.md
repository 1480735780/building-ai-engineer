<div align="center">

# Building AI Engineer

### 从计算机研究生到 AI 系统工程师的公开成长记录

![GitHub](https://img.shields.io/badge/GitHub-Building_AI_Engineer-181717?style=flat-square&logo=github)
![Markdown](https://img.shields.io/badge/Markdown-Notes-000000?style=flat-square&logo=markdown)
![LLM](https://img.shields.io/badge/LLM-Principles-412991?style=flat-square&logo=openai)
![RAG](https://img.shields.io/badge/RAG-Retrieval_Augmented-FF6F00?style=flat-square)
![Agent](https://img.shields.io/badge/Agent-Autonomous-00B8A9?style=flat-square)
![Obsidian](https://img.shields.io/badge/Obsidian-Knowledge_Graph-7C3AED?style=flat-square&logo=obsidian)
![License](https://img.shields.io/badge/License-Open_Learning-2ECC71?style=flat-square)

</div>

---

> **核心理念**：这个仓库不是教程合集，而是一份**公开构建的 AI 工程能力档案**。
>
> 它记录的是一条真实路径——从 N-gram 的概率统计，到 Transformer 的注意力机制，再到 RAG 的检索增强、Agent 的自主决策，最终落地为可承载真实业务的 AI 系统。
>
> 每一篇笔记都对应一次**认知修正**，每一次实战都对应一次**版本演进**。不写空泛鸡汤，只沉淀可复用的工程判断。

---

## 目录

- [项目简介](#项目简介)
- [我为什么做这个仓库](#我为什么做这个仓库)
- [学习与更新原则](#学习与更新原则)
- [仓库结构说明](#仓库结构说明)
- [重点学习路线](#重点学习路线)
- [最近更新](#最近更新)
- [推荐阅读](#推荐阅读)
- [如何使用这个仓库](#如何使用这个仓库)
- [长期目标](#长期目标)

---

## 项目简介

`building-ai-engineer` 是一个**长期公开更新**的技术成长仓库，围绕 **LLM 原理 → RAG → Agent → AI Systems → 部署落地** 这条主线，持续沉淀每日学习日志、项目实战、热点拆解与认知修正。

它不追求"大全而全"的知识罗列，而是以**真实业务场景**（智能仓储 WMS、订单调度、库存优化、物流协同等）为锚点，把抽象的 AI 能力转化为可工程化、可度量、可演进的产品与系统。

| 维度 | 定位 |
| :--- | :--- |
| **每日学习日志** | 原理拆解、论文精读、实验记录，日更不辍 |
| **项目实战** | 真实业务中的 RAG / Agent 落地，含架构图与决策依据 |
| **热点拆解** | 跟踪 LLM 生态最新动态，拆解其工程价值与边界 |
| **认知修正** | 公开记录"我之前想错了什么、现在怎么想"，对抗知识幻觉 |
| **版本演进** | 系统设计的迭代记录，保留从 v0.1 到 v1.0 的决策路径 |
| **真实生产力视角** | 不止讲"能做什么"，更讲"在真实约束下该怎么做" |

---

## 我为什么做这个仓库

市面上不缺 AI 教程，但缺一种东西：**一个真实学习者在不确定中做判断的全过程**。

教程是结果导向的——它隐去了试错、回头、推翻自己的部分。而工程能力的本质，恰恰是在**信息不全、约束复杂、目标漂移**的情况下，做出当下最优的取舍。

这个仓库要回答的不是"RAG 是什么"，而是：

- 当 WMS 的订单数据格式不统一、SKU 编码错误频发时，**检索增强到底补在哪一层**才有效？
- 当 Agent 调用外部接口超时、库存数据异常时，**自主决策的边界该划在哪里**才不会失控？
- 当业务规模从单仓扩展到多仓协同时，**系统架构该怎么演进**才能承载真实流量？

> 把"学过"变成"能判断"，把"能跑通"变成"敢上线"。这是这个仓库存在的意义。

---

## 学习与更新原则

1. **原理先行，工程落地** —— 先把底层机制吃透，再谈框架与工具。不跳过 Transformer 的注意力计算，直接调 API。
2. **真实场景驱动** —— 每个技术点都尽量绑定一个真实业务问题，而不是孤立的知识点。
3. **可复现 > 可阅读** —— 关键实验保留可复现的配置、prompt、数据样例，而非仅结论。
4. **公开纠错** —— 认知迭代时保留旧观点与修正过程，不偷偷改掉过去的错误。
5. **持续小步** —— 每日增量更新优于憋大招，长期复利大于短期冲刺。
6. **拒绝空泛** —— 不写"AI 改变世界"这类废话，每句话都要能落到一个具体决策上。

---

## 仓库结构说明

```
building-ai-engineer/
├── daily/            # 每日学习日志（原理拆解、论文精读、实验记录）
│   └── 图片和附件/   # 每篇笔记对应的图片资源，保证引用不失效
├── weekly/           # 周度小结与阶段性复盘
├── hot-topics/       # 热点拆解：LLM 生态动态的工程价值分析
├── rag/              # RAG 专题：检索增强的架构、调优、落地
├── agent/            # Agent 专题：自主决策、工具调用、多智能体
├── systems/          # AI Systems：架构设计、性能、可观测性、部署
├── projects/         # 项目实战：真实业务落地的完整案例
└── assets/           # 共享资源（跨笔记复用的图、表、模板）
```

| 目录 | 用途 | 更新频率 |
| :--- | :--- | :--- |
| [`daily/`](./daily) | 每日学习日志，含 LLM 原理、RAG、Agent 等主题拆解 | 日更 |
| [`weekly/`](./weekly) | 周度复盘，提炼一周关键认知与决策 | 周更 |
| [`hot-topics/`](./hot-topics) | 热点动态拆解，聚焦工程价值与适用边界 | 随热点 |
| [`rag/`](./rag) | RAG 专题：检索策略、重排、向量库、评测 | 持续 |
| [`agent/`](./agent) | Agent 专题：规划、工具调用、记忆、多智能体协作 | 持续 |
| [`systems/`](./systems) | AI 系统设计：架构、并发、可观测性、成本 | 持续 |
| [`projects/`](./projects) | 项目实战：WMS 智能仓储等真实业务落地 | 按里程碑 |
| [`assets/`](./assets) | 跨笔记共享的图、表、模板资源 | 按需 |

---

## 重点学习路线

> 路线不是线性教程，而是**能力栈的逐层加固**：每一层都为下一层提供工程地基。

```
LLM 原理  →  RAG 检索增强  →  Agent 自主决策  →  AI Systems 系统化  →  部署落地
   │              │                │                   │                  │
   │              │                │                   │                  └─ 真实流量、成本、可观测
   │              │                │                   └─ 架构、并发、稳定性
   │              │                └─ 规划、工具调用、记忆、协作
   │              └─ 向量检索、重排、多路召回、评测
   └─ Transformer、注意力、训练范式、对齐
```

<details>
<summary><b>展开：各阶段核心问题与产出</b></summary>

### 阶段一 · LLM 原理剖析
- **核心问题**：模型到底"理解"了什么？注意力机制在算什么？
- **关键产出**：从 N-gram → RNN → Transformer 的演进逻辑，能用自己的话讲清 Self-Attention。

### 阶段二 · RAG 检索增强
- **核心问题**：检索结果不准时，是该改 embedding、改 chunk，还是改 prompt？
- **关键产出**：多路召回 + 重排的完整链路，以及一套可度量的评测方法。

### 阶段三 · Agent 自主决策
- **核心问题**：Agent 的"自主"边界在哪？什么时候该用 Workflow，什么时候该用 Agent？
- **关键产出**：基于真实 WMS 场景的 Agent 设计，含异常订单处理、库存调拨决策。

### 阶段四 · AI Systems 系统化
- **核心问题**：单机 Demo 到生产系统之间，差的是哪几层？
- **关键产出**：并发、缓存、可观测性、降级策略的工程方案。

### 阶段五 · 部署落地
- **核心问题**：成本、延迟、稳定性如何同时满足？
- **关键产出**：从模型选型到上线监控的完整闭环。

</details>

---

## 最近更新

> 本节为自动可维护格式，按时间倒序排列，便于快速定位最新内容。

| 日期 | 类型 | 标题 | 链接 |
| :--- | :--- | :--- | :--- |
| 2026-08-12 | daily | Mneme-rag Embedding 能力层落地与降级策略设计 | [`daily/2026-08-12.md`](./daily/2026-08-12.md) |
| 2026-08-11 | daily | Mneme-rag RoutingLLMService 重构与流式降级（ProbeStreamBridge） | [`daily/2026-08-11.md`](./daily/2026-08-11.md) |
| 2026-08-10 | daily | Mneme-rag 项目开发进度报告 | [`daily/2026-08-10.md`](./daily/2026-08-10.md) |
| 2026-08-09 | daily | 第⑤章 项目 Mneme-rag | [`daily/2026-08-09.md`](./daily/2026-08-09.md) |
| 2026-08-08 | daily | RAG 检索进阶：Lost in the Middle 现象与 Middle-Out 重排、SelfQueryRetriever 元数据过滤、MultiVectorRetriever 多视角表征 | [`daily/2026-08-08.md`](./daily/2026-08-08.md) |
| 2026-08-07 | daily | RAG Reranker 原理与工业级实战：Cross-Encoder 精排、BGE-Reranker 微服务架构与 Context Compression 三级压缩 | [`daily/2026-08-07.md`](./daily/2026-08-07.md) |
| 2026-08-06 | daily | RAG 切分进阶：Proposition Chunking、Agentic Chunking 与多级精排架构 | [`daily/2026-08-06.md`](./daily/2026-08-06.md) |
| 2026-08-05 | daily | RAG 高级分块：Semantic Chunking、Parent-Child 拓扑、Contextual Retrieval 与 Prompt Caching | [`daily/2026-08-05.md`](./daily/2026-08-05.md) |
| 2026-07 | daily | Agent Learning 记录：LLM 原理剖析（N-gram → Transformer） | [`daily/Agent Learning记录.md`](./daily/Agent%20Learning记录.md) |
| 2026-07 | hot-topic | 我的场景为什么需要 Agents，而不是普通的 Workflow？ | [`assets/README.md`](./assets/README.md) |

<!-- 最近更新格式说明：
| YYYY-MM-DD | 类型 | 标题 | 链接 |
类型可选：daily / weekly / hot-topic / project / system
新增内容时在表格首行插入，保持倒序。-->

---

## 推荐阅读

<details>
<summary><b>展开：基础与进阶资料</b></summary>

**LLM 基础**
- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) — Transformer 原论文
- [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/) — 直观图解注意力机制

**RAG**
- [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/abs/2005.11401) — RAG 原论文
- [Anthropic: Contextual Retrieval](https://www.anthropic.com/news/contextual-retrieval) — 检索增强的工程优化

**Agent**
- [ReAct: Synergizing Reasoning and Acting](https://arxiv.org/abs/2210.03629) — 推理与行动协同
- [LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/) — Lilian Weng 的 Agent 综述

**系统与工程**
- [Building LLM Applications for Production](https://huyenchip.com/ml-interviews-book/) — Chip Huyen 的工程视角
- [Datawhale Agent Learning Hub](https://github.com/datawhalechina/agent-learning) — 中文 Agent 学习开源项目

</details>

---

## 如何使用这个仓库

1. **看路线**：先读 [重点学习路线](#重点学习路线)，了解整体能力栈的构建顺序。
2. **看日志**：从 [`daily/`](./daily) 入手，按时间顺序跟踪认知演进。
3. **看实战**：关注 [`projects/`](./projects) 中的真实业务落地，看决策是怎么做出来的。
4. **看修正**：留意笔记中的"认知修正"标记，这些是避坑的关键经验。
5. **提问题**：如果对某个决策有疑问，欢迎在 GitHub 提 Issue 讨论。

> 这个仓库欢迎被 Fork、引用与讨论，但**不欢迎被搬运成付费课程**。学习应该是开放的。

---

## 长期目标

### 100 天目标
- 完成从 LLM 原理到 Agent 自主决策的完整知识闭环
- 在真实 WMS 业务中跑通至少一个 RAG + Agent 的可用模块
- 沉淀一套可复用的检索增强评测方法

### 1 年目标
- 构建"多仓协同 + 智能调度"的 AI 系统原型，具备并发与可观测性
- 形成一套从需求到上线的 AI 工程方法论，可迁移到其他业务域
- 把这份成长记录打磨成对后来者真正有用的公开资产

> 衡量标准不是"学了多少"，而是**"上线了什么、解决了什么真实问题、修正了多少次错误"**。

---

<div align="center">

**Building in public. Learning in public. Shipping in public.**

</div>
