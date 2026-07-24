# 🌐 Language Switch / 语言切换
- 🌍 English Version: [README_EN.md](./README_EN.md)

---

# DTC Brand Playbook

> 一套标准化的 DTC 品牌 0-1 商业策划书输出框架 —— 从 idea 到可执行的 GTM 策略。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)]()

---

## 这是什么？

当你有一个 DTC 品牌创业 idea，你需要快速回答几个问题：

- 这个方向值得做吗？（GO / NO-GO）
- 市场窗口在哪里？（机会论证）
- 怎么赢？（品牌战略 + 竞争壁垒）
- 怎么赚钱？（商业模型 + Unit Economics）
- 怎么落地？（GTM 策略 + 12 个月执行路线）

**DTC Brand Playbook** 就是一套帮你系统化回答这些问题的模板和方法论。

---

## 核心设计理念

```
业态定位 → GO/NO-GO → 机会论证 → 品牌战略 → 商业模型 → GTM策略 → 执行路线 → 风险与组织
   ↓           ↓          ↓          ↓          ↓         ↓          ↓          ↓
 说清楚     先给结论    Why Now   How to Win  How to    How to    12个月    团队+风险
 是什么                  ?          ?       Make $   Execute   RoadMap
```

### 三条原则

1. **先结论，后论证** — 开头即给出业态定位 + GO/NO-GO 判断
2. **Why Now → How to Win → How to Execute** — 标准战略咨询叙事逻辑
3. **数据驱动 + 洞察点睛** — 每个模块以数据表格呈现，以洞察收尾

---

## 模板结构（7 大模块）

| # | 模块 | 核心问题 | 关键输出 |
|---|------|---------|---------|
| — | **业态定位** | 我们是什么/不是什么？ | 一句话业态 + 品类归属 |
| — | **GO/NO-GO** | 这个方向值得做吗？ | 5维判断 + 战略纪律 |
| 01 | **机会论证** | 为什么是现在？ | 市场信号 + 四象限图 + 规模锚点 |
| 02 | **品牌战略** | 我们如何赢？ | STP + 护城河 + 产品金字塔 + 定价 |
| 03 | **商业模型** | 怎么赚钱？ | 收入飞轮 + Unit Economics |
| 04 | **GTM 策略** | 怎么落地？ | 5P 模型（Product/Price/Place/Promotion/Packaging） |
| 05 | **执行路线** | 12个月怎么走？ | MVP期(4月) + 增长期(8月) + ROAS/MER演变 + Go/No-Go决策门 |
| 06 | **风险与组织** | 谁来做？风险在哪？ | 风险矩阵 + 分阶段团队架构 |
| — | **附录** | 支撑数据 | 产品矩阵 + 数据来源 |

---

## 快速开始

### 1. 安装

```bash
npx skills add <your-repo>@dtc-brand-playbook
```

### 2. 使用

在 AI 对话中直接描述你的 DTC 创业 idea：

> "我想做一个面向北美市场的 [品类] DTC 品牌，核心理念是 [概念]……"

Skill 会自动触发，按模板输出完整的商业策划书。

### 3. 模板文件

- **[SKILL.md](./SKILL.md)** — Skill 定义文件（触发规则 + 使用说明）| 🇨🇳 中文
- **[SKILL_EN.md](./SKILL_EN.md)** — Skill 定义文件（触发规则 + 使用说明）| 🌍 English
- **[template.md](./template.md)** — 可复用模板（用 `[占位符]` 标记需填充的内容）
- **示例输出** — 见 `examples/001-tcm-fashion-wearable.md`（中医时尚体验 DTC 品牌商业策划书）

---

## 适用场景

| 适用 | 不适用 |
|------|--------|
| ✅ DTC 消费品牌（时尚/宠物/健康/家居等） | ❌ B2B SaaS |
| ✅ 面向欧美市场的品牌出海 | ❌ 纯国内市场（需调整模型） |
| ✅ 品牌 0-1 冷启动阶段 | ❌ 成熟品牌的增量优化 |
| ✅ 需要融资/说服合伙人的场景 | ❌ 纯技术/工具类产品 |

---

## 数据基准

模板中涉及的所有行业基准数据来自：

| 数据类型 | 来源 |
|---------|------|
| ROAS / CAC / CVR 行业数据 | [Polar Analytics Ecommerce Benchmarks](https://www.polaranalytics.com/ecommerce-benchmarks) |
| DTC 财务指标（毛利率/EBITDA等） | [Ecom CFO Annual Benchmark Report](https://ecomcfo.co) |
| 市场规模数据 | Technavio / MarketIntelo / GrowthMarketReports |
| 竞品融资/营收数据 | 36Kr / WWD / BeautyMatter / Compworth |

> ⚠️ 每次生成报告时应实时搜索最新数据，模板中的数据仅为结构示例。

---

## 文件结构

```
dtc-brand-playbook/
├── SKILL.md           # Skill 定义 — 中文（触发规则 + 使用说明 + 质量检查清单）
├── SKILL_EN.md        # Skill 定义 — English
├── template.md        # 通用模板（[占位符]格式，可直接复制填充）
├── README.md          # 本文件（中文文档）
├── README_EN.md       # English Documentation
├── LICENSE            # MIT License
└── examples/          # 示例输出
    └── 001-tcm-fashion-wearable.md
```

---

## 输出质量检查清单

生成策划书后，逐项检查：

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

---

## 版本历史

| 版本 | 日期 | 变更 |
|------|------|------|
| v1.0 | 2026-07-24 | 初始版本，提炼自 001-tcm-fashion-wearable v4.0 |

---

## 许可

MIT License — 可自由使用、修改、分发。详见 [LICENSE](./LICENSE)。

---

## 作者

**Leo 屿｜品牌出海顾问 (Leo_Isle | Brand Strategy Consultant)**

> 专注 品牌出海全案咨询｜DTC 冷启动 / IMC 整合营销｜海外增长陪跑顾问  
> 只做长期可沉淀的海外品牌影响力，拒绝短期广告投流主义
>
> *Craft lasting global brand equity & full-funnel growth for DTC and B2B brands*

---

## 贡献

欢迎提交 Issue / PR 改进模板结构和内容。

---

*Made with ❤️ by Leo 屿*
