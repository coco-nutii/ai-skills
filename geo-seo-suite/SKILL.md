---
name: geo-seo-suite
description: Use when auditing a website's organic search performance, improving visibility in AI answer engines, researching search intent and competitors, planning GEO/SEO content, generating structured data, or preparing an evidence-based SEO growth report.
---

# GEO SEO Suite

A bilingual, evidence-led operating system for GEO (Generative Engine Optimization) and traditional SEO. Use it to diagnose a website, prioritize fixes, and produce implementation-ready recommendations.

## Core operating rules

1. **Separate evidence from inference.** Label every important finding as Observed, User-provided, Inferred, or Not verified.
2. **Never fabricate metrics.** Do not invent rankings, traffic, backlinks, crawl results, AI citations, search volume, conversion rates, or competitor performance.
3. **State data coverage.** Identify the pages, queries, locations, devices, dates, and sources actually inspected. Explain gaps.
4. **No guaranteed rankings or AI citations.** GEO recommendations improve clarity, retrievability, entity understanding, and source quality; they cannot guarantee inclusion in ChatGPT, Gemini, Perplexity, Google AI Overviews, or other answer engines.
5. **Make recommendations actionable.** Each priority item needs an issue, evidence, impact, effort, owner role, exact next action, and validation method.
6. **Respect access boundaries.** Use only public pages, user-supplied exports, or explicitly authorized integrations. Never claim to have crawled or queried a system without access.
7. **Bilingual output.** Respond in the user's language. When asked for both languages, provide parallel English and Simplified Chinese deliverables.

## Workflow selector

| Request | Module |
|---|---|
| Website health check | 1. GEO + SEO Audit |
| AI answer-engine visibility | 2. AI Visibility Research |
| Keyword and topic planning | 3. Keyword Intelligence |
| Competitor benchmarking | 4. Competitor Analysis |
| Crawl/index/technical issues | 5. Technical SEO |
| Page or article rewrite | 6. Content Optimizer |
| JSON-LD / structured data | 7. Schema Generator |
| Editorial roadmap | 8. Content Strategy |
| Brand/entity authority | 9. Authority Building |
| Executive report | 10. Performance & Reporting |

For a full review, run modules in order and mark modules blocked by missing data.

## Intake

Collect only information essential to the requested task. Ask one concise question when a critical input is missing.

Minimum useful inputs:
- Website URL or target page
- Business/brand name and what it offers
- Target market, language, and audience
- Primary conversion goal
- Main competitors, if known
- Available data: Google Search Console, GA4, rank tracker, crawl export, backlink export, or AI answer samples

If inputs are unavailable, proceed with a limited-scope assessment and state assumptions.

## Evidence labels

- **Observed:** directly visible in supplied page/source or returned tool data.
- **User-provided:** supplied by the user, not independently verified.
- **Inferred:** reasoned hypothesis based on available evidence.
- **Not verified:** requires access, a tool, or a data source that is unavailable.

For every quantitative metric, include source, period, scope, and measurement method. If any is missing, do not present it as a measured fact.

## 1. GEO + SEO Audit

Assess the site across these dimensions. Score each from 0–5 only when evidence supports a score; otherwise mark N/A.

- Crawlability and indexability
- Information architecture and internal linking
- Search intent coverage
- Content usefulness, originality, and freshness
- Entity clarity (brand, products, people, locations, category)
- Trust and source transparency
- Structured data validity and relevance
- Page experience and mobile usability
- AI answer extractability (clear definitions, direct answers, factual consistency, accessible HTML)
- Conversion path clarity

Scoring guide: 0 = absent/broken; 1 = major weakness; 2 = below standard; 3 = adequate; 4 = strong; 5 = excellent and evidenced. Never convert missing evidence into a zero.

Output: executive verdict (max 5 bullets), scope and limitations, scorecard with evidence and confidence, critical issues (P0/P1/P2), quick wins, and 30/60/90-day roadmap.

## 2. AI Visibility Research

For each selected query, test or review answer-engine results the user provides or that available authorized tools actually return.

Track engine and access method; exact prompt/query; date and locale; whether the brand is mentioned; whether the brand is cited as a source; mention position/context; competitors mentioned; cited URLs/domains; accuracy and sentiment; repeatability/sample count.

Do not call a brand visible in AI search based on one anecdotal prompt. Use a query set across discovery, comparison, and purchase intent. Distinguish direct observation from hypotheses. When no live engine access exists, provide a repeatable manual testing protocol instead of fabricated results.

## 3. Keyword Intelligence

Build clusters around intent, not just lexical similarity: informational, problem/solution, commercial investigation, transactional, navigational, and local.

For each keyword include phrase, intent, audience stage, proposed page type, parent cluster, differentiation angle, priority, and data status. Search volume, difficulty, CPC, and trend must be marked unavailable unless supplied by a real data source. Label generated question variants as hypotheses unless grounded in actual user language.

## 4. Competitor Analysis

Compare only named competitors or competitors evidenced by supplied search results. Evaluate positioning and audience; category/product coverage; content depth and freshness; search-intent coverage; entity and proof signals; site architecture and internal links; structured data; differentiation and content gaps.

Deliver a comparison matrix, defensible gaps, and actions. Do not invent competitor traffic, ranking positions, backlink counts, or revenue.

## 5. Technical SEO

Review available evidence for HTTP status and redirects; canonical tags; robots.txt and XML sitemap; indexability and meta robots; title and meta description; heading structure; internal and broken links; image alt text and file weight; mobile layout/Core Web Vitals (only from actual measurements); hreflang/localization; duplicate pages; JSON-LD and schema errors.

If the site cannot be crawled, output a technical checklist and request a crawl export. Never imply a full technical crawl from a homepage-only inspection.

## 6. Content Optimizer

For each page:
1. Identify target audience and intent.
2. State the page's current promise and evidence.
3. Identify missing questions and decision criteria.
4. Improve title, H1, introduction, section structure, FAQs, and CTA.
5. Add specific examples, original data, expert attribution, and source links only where genuinely available.
6. Improve answer extractability with concise definitions and direct answers without keyword stuffing.
7. Provide internal-link targets and suggested anchor text.
8. Provide a change log explaining why each change matters.

Do not create fake testimonials, expert credentials, case studies, citations, or statistics.

## 7. Schema Generator

Generate JSON-LD only when page content supports the selected type. Prefer accurate types such as Organization, WebSite, WebPage, Product, Article, BreadcrumbList, LocalBusiness, and Person when applicable.

Requirements: valid JSON syntax; real user-provided facts only; no invented ratings, reviews, prices, availability, authorship, or addresses; no hidden or misleading content. Explain where to place the code and how to validate it. Warn that valid schema does not guarantee rich results or AI citations.

## 8. Content Strategy

Create a topic map linking audience problem, search intent, core pillar page, supporting pages, proof assets/original research, internal links, conversion CTA, and refresh cadence.

Prioritize by business relevance, evidence of demand, competitive gap, ability to provide original value, and production effort. Mark demand evidence as measured or hypothesized.

## 9. Authority Building

Recommend legitimate ways to strengthen brand/entity understanding and source quality: consistent organization/product facts; clear About, Contact, editorial, and author information; original research and useful reference assets; relevant industry publications and partnerships; accurate business profiles where eligible; high-quality mentions earned through genuine contribution.

Do not recommend paid link schemes, fake reviews, fabricated profiles, mass-generated low-value pages, or manipulative citation tactics.

## 10. Performance & Reporting

Build a report from available data only. Useful KPIs include Search Console clicks/impressions/CTR/average position; organic sessions and conversions; indexed pages and crawl errors; keyword visibility; AI answer mentions/citations from repeatable prompt samples; assisted revenue or qualified leads.

For each KPI show definition, source, period, baseline, current value, change, and caveat. If baseline or data is absent, show Not supplied rather than estimating.

## Prioritization model

Rate each recommendation: Impact 1–5; Confidence 1–5; Effort 1–5 (5 = high effort).

Priority score = (Impact × Confidence) ÷ Effort. This is a planning aid, not a forecast. Sort by score, then dependencies and risk. Identify quick wins separately.

## Standard deliverable format

# GEO + SEO Growth Report
**Website:**  
**Business:**  
**Market / language:**  
**Review date:**  
**Scope:**  
**Data sources:**  

## Executive verdict
## Evidence and limitations
## Scorecard
## Critical issues
## Priority action plan
| Priority | Finding | Evidence | Impact | Effort | Next action | Validation |
## AI visibility findings
## Keyword and content opportunities
## Technical recommendations
## 30/60/90-day roadmap
## KPI measurement plan

Close with the three highest-value next actions. Keep the report concise, specific, and implementation-ready.

## Quick-start commands

- Audit this website: [URL]
- Build an AI visibility test set for [brand] in [market].
- Compare [brand] with [competitors] for [audience].
- Optimize this page for SEO and AI answer engines: [URL/text].
- Generate valid JSON-LD for this page: [URL/text].
- Create a 90-day GEO + SEO roadmap for [business].

## 中文操作规范

中文任务遵循同一套证据规则：
- 明确区分“已观察 / 用户提供 / 推断 / 未核实”。
- 没有真实数据来源，不编造搜索量、排名、流量、外链、AI 引用率。
- AI 搜索可见度必须记录平台、提示词、日期、地区、样本量和引用链接。
- 输出给出优先级、具体修改动作、负责人角色和验收方式。
- 不承诺排名、流量增长或被 AI 答案引用。
