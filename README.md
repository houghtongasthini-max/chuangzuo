# AI 拟真连续图片叙事工作流研究档案 (chuangzuo Repository)

本仓库记录一套 AI 拟真连续图片叙事工作流的建立、试验与迭代过程，包含从 1.0 到 3.0 的提示词体系、作品创作档案、失败版本、数据反馈和复盘记录。

---

## 📌 当前状态 (Current Status)

当前正式使用版本为：
* [Workflow v3.0](workflow/v3.0-current/)

当前未采用的架构实验：
* [P³-D v0.2](experiments/2026-08-p3d-v0.2-not-adopted/)

最新工作流复盘研究：
* [2026年8月工作流再审查](research/2026-08-workflow-reassessment/)

各版本详细状态对比与实施决定请参阅 [WORKFLOW_STATUS.md](WORKFLOW_STATUS.md)。

---

## 📂 仓库目录架构 (Repository Structure)

```
chuangzuo/
├─ README.md                     # 本文档：项目定位与全局导航
├─ WORKFLOW_STATUS.md            # 工作流版本状态与当前决策
├─ WORKFLOW_TIMELINE.md          # 工作流演进与作品试验时间线
│
├─ workflow/                     # 提示词工作流模块 (按版本迭代)
│  ├─ v1.0/                      # 1.0 基础三段式工作流 (Prompt3~5)
│  │  ├─ README.md
│  │  └─ prompts/
│  ├─ v2.0-transition/           # 2.0 过渡期工作流与多方案竞演试验
│  │  ├─ README.md
│  │  └─ prompts/
│  ├─ v2.1-rejected/             # 2.1 被否决版本及规则过载复盘
│  │  ├─ README.md
│  │  └─ failure-review.md       # 《v2.1 失败复盘报告》
│  └─ v3.0-current/              # 3.0 当前拟真叙事工作流标准体系
│     ├─ README.md
│     └─ prompts/
│
├─ experiments/                  # 未采用或待验证的工作流实验
│  └─ 2026-08-p3d-v0.2-not-adopted/ # P³-D v0.2 架构实验 (未采用)
│     ├─ README.md
│     ├─ STATUS.md
│     └─ modules/
│
├─ research/                     # 市场研究、内部复盘与架构提案
│  └─ 2026-08-workflow-reassessment/ # 2026年8月工作流再审查与评估
│     ├─ README.md
│     ├─ EVIDENCE_INDEX.md
│     ├─ 00-overview/
│     ├─ 01-evidence/
│     ├─ 02-analysis/
│     ├─ 03-proposals/
│     ├─ 04-decisions/
│     └─ 99-raw-reports/
│
├─ works/                        # 作品创作档案 (按日期与版本归档)
│  ├─ 2026-07-22-demo-商场撤离图/
│  ├─ 2026-07-23-v1.0-长城烽火/
│  ├─ 2026-07-24-v1.0-零号线/
│  ├─ 2026-07-25-v1.0-替死影衣/
│  ├─ 2026-07-25-v1.0-深海光缆/
│  ├─ 2026-07-27-v2.1-rejected-黄河退水/
│  ├─ 2026-07-27-v3.0-白雀谷气象站/
│  └─ 2026-07-28-v3.0-返厂旧手机/
│
├─ feedback/                     # 数据反馈与复盘记录
│  ├─ data-feedback.md           # 作品数据与评论反馈汇总
│  ├─ improvement-log.md        # 工作流改进日志
│  └─ retrospective-template.md  # 创作复盘标准模板
│
└─ assets/                       # 媒体资产与参考档案
   ├─ image-exports/             # 导出的生成图包 (.zip)
   └─ archives/                  # 对标作品拆解与真实感系统研究
```

---

## 📖 相关文档与快捷入口

* [工作流版本状态与决策](WORKFLOW_STATUS.md)
* [工作流演进与作品时间线](WORKFLOW_TIMELINE.md)
* [v3.0 工作流规范说明](workflow/v3.0-current/README.md)
* [v2.1 失败复盘报告](workflow/v2.1-rejected/failure-review.md)
* [全站数据反馈汇总](feedback/data-feedback.md)
