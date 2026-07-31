# AI 拟真连续图片叙事工作流研究档案 (chuangzuo Repository)

本仓库记录一套 AI 拟真连续图片叙事工作流的建立、试验与迭代过程，包含从 1.0 到 3.0 的提示词体系、作品创作档案、失败版本、数据反馈和复盘记录。

---

## 📂 仓库目录架构 (Repository Structure)

```
chuangzuo/
├─ README.md                     # 本文档：项目定位与全局导航
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

## 💡 工作流核心理念 (Workflow Core Principles)

在 v3.0 版本中，工作流已从早期的单套模板拓展为完整的**拟真类型叙事**体系，重点关注五大叙事维度：
1. **记录门槛**：现实入口是否秒懂，凭证链是否具备物理可信度。
2. **故事活性**：人物是否具备独立能动性，而非规则机械执行器。
3. **情绪驱动力**：从单纯微恐/悬疑转向情感变轨与高情绪回报。
4. **视觉变化**：分镜间景别与视觉焦点的连续推进。
5. **结构距离**：主动与既有爆款题材拉开差异，防止同质化。

---

## 📖 相关文档与快捷入口

* [工作流演进与作品时间线](WORKFLOW_TIMELINE.md)
* [v3.0 工作流规范说明](workflow/v3.0-current/README.md)
* [v2.1 失败复盘报告](workflow/v2.1-rejected/failure-review.md)
* [全站数据反馈汇总](feedback/data-feedback.md)
