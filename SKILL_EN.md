---
name: dtc-brand-playbook
description: Output standardized business playbooks for DTC brand startup projects. Trigger when users submit new brand startup ideas, need feasibility analysis, brand strategy planning, or GTM strategy design. Trigger keywords include "DTC", "brand strategy", "startup idea", "business plan", "GTM", "0-to-1", "brand出海", "cross-border", etc.
version: 1.0.0
author: Leo 屿 | 品牌出海顾问 (Leo_Isle | Brand Strategy Consultant)
license: MIT
---

# DTC Startup Brand Playbook — Brand Startup Business Planning Template

## Overview

This skill provides a standardized framework for DTC brand 0-to-1 business planning, distilled from deep analysis of multiple DTC startup projects. It is designed for DTC consumer brands targeting Western markets (fashion accessories, pet supplies, health & wellness, home & lifestyle, etc.).

## When to Use

This skill auto-triggers when the user makes any of the following requests:

- Submits a new DTC brand startup idea
- Needs systematic business feasibility analysis for a startup direction
- Requests a "brand business plan", "GTM strategy", or "0-to-1 launch plan"
- Discusses brand globalization, cross-border e-commerce, or DTC category creation

## Core Design Philosophy

This template follows three principles:

1. **Verdict First, Evidence Second**: Open with business positioning + GO/NO-GO judgment. No fluff.
2. **Why Now → How to Win → How to Execute**: Standard strategy consulting narrative arc
3. **Data-Driven, Insight-Closed**: Every module presented as a data table, closed with one sharp insight

## Output Structure (7 Modules)

```
Business Positioning   ← Define what we ARE vs. what we are NOT in one sentence
GO / NO-GO Verdict     ← Give the verdict first, then build the case
01 Opportunity Analysis ← Why Now: Market signals + Competitive vacuum + Market sizing
02 Brand Strategy      ← How to Win: STP positioning + Moat + Product + Pricing
03 Business Model      ← How to Make Money: Revenue flywheel + Unit Economics
04 GTM Strategy        ← How to Execute: 5P model (Product/Price/Place/Promotion/Packaging)
05 12-Month Roadmap    ← MVP phase (4mo) + Growth phase (8mo) + ROAS/MER evolution + Go/No-Go gate
06 Risk & Organization ← Risk matrix + Phased team structure
Appendix              ← Product concept matrix / Data sources
```

## Usage Guide

### 1. Basic Workflow

When a user submits an idea, follow these steps:

1. **Understand the idea**: Extract core concept, target category, target market
2. **Market research**: Use WebSearch to gather competitor data, industry benchmarks, and market trends
3. **Apply the template**: Fill in content across all 7 modules
4. **Output file**: Save as `/workspace/dtc-incubator/ideas/00X-project-name.md`

### 2. Data Requirements

Every module's data source must be cited in the appendix. Key benchmark data sources include:

- Polar Analytics Ecommerce Benchmarks (ROAS/CAC/CVR by industry)
- Ecom CFO Annual Benchmark Report (DTC financial metrics)
- Technavio / MarketIntelo / GrowthMarketReports (market sizing)
- Public competitor funding/revenue data (36Kr/WWD/BeautyMatter, etc.)

### 3. Formatting Standards

- File naming: `00X-short-english-project-name.md` (e.g., `001-tcm-fashion-wearable.md`)
- Title format: `# [Brand/Category] DTC Brand 0-1 Business Plan & GTM Strategy`
- Version header: Include version number, date, and document type
- Tables over prose: Present data in tables whenever possible
- Insight markers: Close key modules with `> **XXX Insight**:`

### 4. Output Quality Checklist

- [ ] Business positioning is clear (what we ARE vs. what we are NOT)
- [ ] GO/NO-GO includes explicit verdict AND strategic discipline
- [ ] Every major module has at least one data-backed insight
- [ ] Competitor benchmarking includes concrete data (revenue/funding/scale)
- [ ] Unit Economics include industry benchmark comparison
- [ ] MVP phase has a hard Go/No-Go decision gate (≥4 quantified metrics)
- [ ] ROAS/MER evolution is projected across phases
- [ ] Risk matrix includes probability AND impact assessment
- [ ] Team structure is phased (MVP → Growth → Scale)
- [ ] Appendix cites all data sources

### 5. Customization by Category

| Category Characteristics | Adjustment Recommendation |
|--------------------------|---------------------------|
| Pure online DTC (no physical) | Remove CLUB/Pop-up modules, focus on DTC channels |
| High AOV (>$500) | Adjust AOV/CAC benchmarks, increase content education weight |
| B2B attributes | Replace "Packaging" in 5P with "People/Process" |
| Non-consumer goods (SaaS, etc.) | This template is not applicable |

## Template File

The complete template is available in `template.md` in the same directory.

## Example Output

See `examples/001-tcm-fashion-wearable.md` for a complete example (TCM-Inspired Fashion DTC Brand Business Plan v4.0).

## License

MIT License — Free to use, modify, and distribute.

---

## Author

**Leo_Isle | Brand Strategy Consultant (Leo 屿｜品牌出海顾问)**

> Craft lasting global brand equity & full-funnel growth for DTC and B2B brands  
> Specializing in: Brand出海 Full-Case Consulting | DTC Cold Start / IMC | Overseas Growth Advisory  
> *Building enduring global brand influence — no short-term ad arbitrage*
>
> 专注 品牌出海全案咨询｜DTC 冷启动 / IMC 整合营销｜海外增长陪跑顾问  
> 只做长期可沉淀的海外品牌影响力，拒绝短期广告投流主义
