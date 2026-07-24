---
name: dtc-brand-playbook
description: 为 DTC 品牌创业项目输出标准化商业策划书。当用户提交新品牌创业 idea、需要进行可行性分析、品牌战略规划、GTM 策略设计时使用。触发关键词包括"DTC"、"品牌策划"、"创业idea"、"商业计划书"、"GTM"、"0-1"、"品牌出海"等。
version: 1.0.0
author: Leo 屿 | 品牌出海顾问 (Leo_Isle | Brand Strategy Consultant)
license: MIT
---

# DTC Brand Playbook — 品牌创业商业策划书模板

## 概述

本 skill 提供了一套标准化的 DTC 品牌 0-1 商业策划书输出框架，源自对多个 DTC 创业项目深度分析的提炼。适用于面向欧美市场的 DTC 消费品牌（时尚配饰、宠物用品、健康养生、家居生活等品类）。

## 何时使用

当用户提出以下任一需求时，自动触发本 skill：

- 提交一个新的 DTC 品牌创业 idea
- 需要对某个创业方向进行系统化的商业可行性分析
- 要求输出"品牌商业策划书"、"GTM 策略"、"0-1 启动方案"
- 涉及品牌出海、跨境电商、DTC 品类创建等话题

## 核心设计理念

本模板遵循三条原则：

1. **先结论，后论证**：开头即给出业态定位 + GO/NO-GO 判断，不兜圈子
2. **Why Now → How to Win → How to Execute**：标准战略咨询叙事逻辑链
3. **数据驱动 + 洞察点睛**：每个模块以数据表格呈现，以一段洞察收尾

## 输出结构（7 大模块）

```
业态定位           ← 一句话说清楚是什么/不是什么
GO / NO-GO 结论    ← 先给答案再展开论证
01 机会论证        ← Why Now：市场信号 + 竞争真空 + 规模锚点
02 品牌战略        ← How to Win：STP定位 + 护城河 + 产品 + 定价
03 商业模型        ← How to Make Money：收入飞轮 + Unit Economics
04 GTM 策略        ← How to Execute：5P模型（Product/Price/Place/Promotion/Packaging）
05 12个月执行路线   ← MVP验证期(4月) + 增长期(8月) + ROAS/MER演变 + Go/No-Go决策门
06 风险与组织保障    ← 风险矩阵 + 团队架构
附录               ← 产品创意矩阵 / 数据来源
```

## 使用说明

### 1. 基本调用

当用户提交一个 idea 时，按以下步骤执行：

1. **理解 idea**：提取核心概念、目标品类、目标市场
2. **市场调研**：使用 WebSearch 获取竞品数据、市场基准数据、行业趋势
3. **套用模板**：按 7 大模块填充内容
4. **输出文件**：保存为 `/workspace/dtc-incubator/ideas/00X-project-name.md`

### 2. 数据要求

每个模块的数据来源必须在附录中标注。关键基准数据来源包括：

- Polar Analytics Ecommerce Benchmarks（ROAS/CAC/CVR 行业数据）
- Ecom CFO Annual Benchmark Report（DTC 财务指标）
- Technavio / MarketIntelo / GrowthMarketReports（市场规模数据）
- 具体竞品的公开融资/营收数据（36Kr/WWD/BeautyMatter 等）

### 3. 格式规范

- 文件命名：`00X-简短英文项目名.md`（如 `001-tcm-fashion-wearable.md`）
- 标题格式：`# [品牌/品类] DTC 品牌 0-1 商业策划及 GTM 策略`
- 版本标注：文件头包含版本号、日期、类型
- 表格优先：能用表格呈现的数据不用段落堆砌
- 洞察标记：关键模块以 `> **XXX洞察**：` 收尾

### 4. 输出质量检查清单

- [ ] 业态定位清晰（是什么/不是什么）
- [ ] GO/NO-GO 有明确判断和战略纪律
- [ ] 每个主模块有至少一个数据驱动的洞察
- [ ] 竞品对标包含具体数据（营收/融资/规模）
- [ ] Unit Economics 包含行业基准对比
- [ ] MVP 期有硬性 Go/No-Go 决策门（≥4 项量化指标）
- [ ] ROAS/MER 有阶段演变预期
- [ ] 风险矩阵包含概率和影响评估
- [ ] 团队架构分阶段规划（MVP/增长/规模化）
- [ ] 附录标注数据来源

### 5. 定制化调整

不同品类可根据实际情况调整：

| 品类特征 | 调整建议 |
|---------|---------|
| 纯线上 DTC（无线下） | 删除线下 CLUB/Pop-up 模块，聚焦 DTC 渠道 |
| 高客单价（>$500） | 调整 AOV/CAC 基准，增加内容教育权重 |
| B2B 属性 | 替换 5P 中的 Packaging 为 People/Process |
| 非消费品（SaaS 等） | 不适用本模板 |

## 模板文件

完整模板见同目录下的 `template.md`。

## 示例输出

完整示例见 `/workspace/dtc-incubator/ideas/001-tcm-fashion-wearable.md`（中医时尚体验 DTC 品牌商业策划书 v4.0）。

## 许可

MIT License — 可自由使用、修改、分发。

---

## 作者

**Leo 屿｜品牌出海顾问 (Leo_Isle | Brand Strategy Consultant)**

> 专注 品牌出海全案咨询｜DTC 冷启动 / IMC 整合营销｜海外增长陪跑顾问  
> 只做长期可沉淀的海外品牌影响力，拒绝短期广告投流主义
>
> *Craft lasting global brand equity & full-funnel growth for DTC and B2B brands*
