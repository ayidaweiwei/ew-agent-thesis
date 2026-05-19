论文开题报告

> 设备延保策略的智能生成研究

## 项目简介

本仓库为硕士研究生学位论文开题报告的工作空间，研究方向为基于 AI Agent 的设备延保策略智能生成系统。核心目标是构建集成"数据驱动-智能推理"的设备延保智能生成系统，融合 RAG 检索增强、ReAct 推理架构与多目标优化算法，实现延保策略的自动化生成。

## 目录结构

```
chengduligong/
├── proposal/                          # 开题报告主目录
│   ├── 硕士研究生学位论文开题报告.md   # 开题报告正文
│   ├── requirement.md                 # 写作要求与评估方法
│   ├── 毕业论文详细完成计划.md           # 详细完成计划
│   ├── 论文完成计划-200h-50周.md        # 工时规划（200h/50周）
│   ├── 延保快速学习手册.md              # 延保业务快速入门
│   └── refer/                         # 参考文献
│       └── business/
│           ├── ew_chapter1.5.md       # Extended Warranties 1.5章（中英双语）
│           └── Extended Warranties... .pdf
├── essay/                             # 参考论文
│   └── example/
│       ├── 20260413121628.pdf         # 参考硕士论文原文
│       └── 20260413121628.md          # 参考论文 Markdown 版
├── skill/                             # 工具与技能
│   └── md-format-skill.md            # Markdown 格式优化规则
└── README.md
```

## 研究内容概览

| 研究内容 | 核心问题 | 关键技术 | 预估工时 |
|---------|---------|---------|---------|
| 一、数据收集与知识提取 | 数据散落、经验隐性化、知识幻觉 | Scrapy/Pandas/FAISS/LangChain/Neo4j | 115h |
| 二、Agent 设计与实现 | 认知模糊、合规失控、决策不可信 | LangChain/ReAct/CoT/Prompt Engineering | 110h |
| 三、决策逻辑与工具协同 | 精算失准、工具冲突、利益权衡 | Weibull/NSGA-II/FastAPI/蒙特卡洛 | 95h |

**总计：约 320h**

## 技术栈

- **数据层：** Python, Pandas, Scrapy, MySQL, Neo4j
- **知识层：** LangChain, FAISS, text2vec, HanLP
- **推理层：** LLM API (智谱/OpenAI), ReAct, CoT, Prompt Engineering
- **工具层：** FastAPI, SciPy, Pymoo (NSGA-II), NumPy, Matplotlib
- **工程化：** Git, pytest, Cron, Docker

## 参考文献

- 参考论文：《多源扰动下感-传-算协同的异构云边算力系统多尺度韧性优化研究》
- 参考书籍：*Extended Warranties, Maintenance Service and Lease* (Murthy et al., Springer)
