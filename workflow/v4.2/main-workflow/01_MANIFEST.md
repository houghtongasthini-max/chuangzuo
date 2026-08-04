# V4.2 Candidate｜权威文件清单

## 一、版本状态

- 版本：V4.2 Candidate；
- 性质：事件优先、主题后置、参考隔离的候选工作流；
- 主体工作流与独立研究系统分开保存；
- 本交付包不包含回归测试与仓库发布治理文件。

## 二、权威关系

| 信息类型 | 唯一权威文件 |
|---|---|
| 全局原则、默认设置、权限和返回关系 | `core/00_GLOBAL_CONTRACT.md` |
| 操作方式和加载纪律 | `00_README.md` |
| 用户输入字段 | `02_INPUT_TEMPLATE.md` |
| 市场与受众快照 | `background/B1_MARKET_AUDIENCE.md` |
| 创意资产、来源索引和暂停资产 | `background/B2_ASSET_SOURCE_INDEX.md` |
| 生产数据与复盘事实 | `background/B3_PRODUCTION_REVIEW_LEDGER.md` |
| 完整参考样本与研究结论 | `../independent-research/` |

其他文件不得重新定义与`00`冲突的默认值。

## 三、主体工作流完整文件

### 顶层

- `00_README.md`
- `01_MANIFEST.md`
- `02_INPUT_TEMPLATE.md`

### Core

- `core/00_GLOBAL_CONTRACT.md`
- `core/01A_IDEA_DISCOVERY.md`
- `core/01B_PROMISE_SELECTION.md`
- `core/02_STORY_DEVELOPMENT.md`
- `core/03_INDEPENDENT_REVIEW.md`
- `core/04_VISUAL_QUALIFICATION.md`
- `core/05_STORYBOARD_RELEASE.md`

### Repair

- `repair/R1_HIGH_POTENTIAL_REPAIR.md`

### Background

- `background/B1_MARKET_AUDIENCE.md`
- `background/B2_ASSET_SOURCE_INDEX.md`
- `background/B3_PRODUCTION_REVIEW_LEDGER.md`

### Tools

- `tools/T1_REFERENCE_SOURCE_PACK.md`
- `tools/T2_STRUCTURAL_DISTANCE.md`
- `tools/T3_VISUAL_KEYFRAME_TEST.md`

## 四、独立研究系统

- `../independent-research/00_RESEARCH_SYSTEM_GUIDE.md`
- `../independent-research/01_EXTERNAL_REFERENCE_SAMPLES.md`
- `../independent-research/02_INTERNAL_WORK_SAMPLES.md`
- `../independent-research/03_COMPARISON_MATRICES.md`
- `../independent-research/04_TEMPORARY_SOURCE_PACK.md`
- `../independent-research/05_WORKFLOW_FAILURE_HISTORY.md`

## 五、加载纪律

每次只加载：

```text
core/00_GLOBAL_CONTRACT.md
＋当前模块
＋上一阶段正式交接对象
＋少量直接相关背景
```

完整外部样本、自有样本、比较矩阵和失败史不属于日常创作默认上下文。
