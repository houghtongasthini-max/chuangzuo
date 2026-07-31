# 创作仓库 (chuangzuo Repository)

本仓库为 **AI 伪纪实图文/短视频爆款内容创作矩阵** 的核心储存库，收录了从工作流 1.0 到 3.0 的全套提示词工程（Prompt Engineering）、演进门禁、数据反馈以及产出的所有作品案卷。

---

## 📂 仓库目录架构 (Repository Structure)

```
chuangzuo/
├─ README.md                     # 本文档：仓库主索引与使用指引
├─ WORKFLOW_TIMELINE.md          # 工作流演进与作品产出完整时间线
│
├─ workflow/                     # 提示词工作流模块 (按版本管理)
│  ├─ v1.0/                      # 基础三段式工作流 (Prompt3~5)
│  │  ├─ README.md
│  │  └─ prompts/
│  ├─ v2.0-transition/           # 2.0 过渡期工作流与多方案融合测试
│  │  ├─ README.md
│  │  └─ prompts/
│  ├─ v2.1-rejected/             # 2.1 被否决版本及败因复盘
│  │  ├─ README.md
│  │  └─ failure-review.md
│  └─ v3.0-current/              # 3.0 当前最新量产工作流标准体系
│     ├─ README.md
│     └─ prompts/
│
├─ works/                        # 作品归档模块 (按日期与版本命名)
│  ├─ 2026-07-22-demo-商场撤离图/
│  ├─ 2026-07-23-v1.0-长城烽火/
│  ├─ 2026-07-24-v1.0-零号线/
│  ├─ 2026-07-25-v1.0-替死影衣/
│  ├─ 2026-07-25-v1.0-深海光缆/
│  ├─ 2026-07-27-v2.1-rejected-黄河退水/
│  ├─ 2026-07-27-v3.0-白雀谷气象站/
│  └─ 2026-07-28-v3.0-返厂旧手机/
│
├─ feedback/                     # 平台数据反馈与复盘记录
│  ├─ data-feedback.md           # 核心作品播放/爆款指标数据汇总
│  ├─ improvement-log.md        # 迭代改进意见与优化记录
│  └─ retrospective-template.md  # 创作复盘标准模板
│
└─ assets/                       # 媒体资产与参考档案
   ├─ image-exports/             # 导出的生成图包 (.zip)
   └─ archives/                  # 对标作品拆解与真实感系统研究
```

---

## 🛠️ 当前推荐工作流 (Current Standard Workflow)

对于新的图文/短视频爆款创作，**必须统一使用 [workflow/v3.0-current/](file:///c:/Users/72998/Desktop/优化版/workflow/v3.0-current) 的提示词标准**：

1. **选题创作与筛选**：运行 `Prompt3-选题创作版-3.0.md` 并通过 `融合审查-选题-3.0.md` 进行门禁过滤。
2. **故事骨架与剧本**：运行 `Prompt4-故事创作版-3.0.md` 并通过 `融合审查-故事-3.0.md` 校验能动性与情绪变轨。
3. **视觉导演与生图**：运行 `Prompt5-视觉导演与生图提示词-3.0.md` 导出分镜提示词。

---

## 📖 相关文档与快捷入口

* [工作流演进与作品时间线](file:///c:/Users/72998/Desktop/优化版/WORKFLOW_TIMELINE.md)
* [v3.0 工作流规范](file:///c:/Users/72998/Desktop/优化版/workflow/v3.0-current/README.md)
* [v2.1 失败复盘报告](file:///c:/Users/72998/Desktop/优化版/workflow/v2.1-rejected/failure-review.md)
* [全站数据反馈汇总](file:///c:/Users/72998/Desktop/优化版/feedback/data-feedback.md)
