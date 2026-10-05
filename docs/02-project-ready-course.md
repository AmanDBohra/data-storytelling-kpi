# DATA STORYTELLING & KPI DESIGN — 6-HOUR PROJECT-READY COURSE

> **Goal:** Not "how to make charts." The skill is converting a vague business requirement → the right questions → the right KPIs → analysis → what changed → why → insight → recommendation → how we'll measure the outcome.
> **How to use:** Read a section, then do the EXERCISE before reading the model answer. One company throughout: **Northwind Commerce** (~$110M online retailer; Electronics/Home/Apparel/Beauty; North/South/East/West; Web/App/Marketplace; ~800k customers).

## THE MASTER MENTAL MODEL
```
BUSINESS OBJECTIVE → BUSINESS QUESTION → KPI → TARGET → ACTUAL → VARIANCE
→ TREND → SEGMENTATION → DRIVERS → ROOT CAUSE → BUSINESS IMPACT ($)
→ INSIGHT → RECOMMENDATION → ACTION → OWNER → FOLLOW-UP KPI → OUTCOME
```

---
---
# HOUR 1 — DATA → INFORMATION → INSIGHT, AND BUSINESS QUESTIONS

**1.1 What storytelling is.** A doctor doesn't hand you the blood-test printout — they say what's wrong (what), likely cause (why), the risk (so what), and the fix (now what). The printout is the dashboard; nobody decides from it alone. `DATA + VISUAL + CONTEXT + NARRATIVE = DATA STORY → UNDERSTANDING → DECISION → ACTION`.

**The four inequalities:** DATA ≠ INSIGHT · CHART ≠ STORY · KPI ≠ DECISION · DASHBOARD ≠ BUSINESS VALUE.

**1.2 The value ladder** (climb it every time):
| Rung | Answers | Northwind |
|---|---|---|
| DATA | the raw number | Revenue = $10M |
| INFORMATION | how it compares | Revenue fell 8% YoY |
| INSIGHT | what it means | 70% of the decline is Electronics in the West |
| IMPLICATION | why care | annual target missed at this rate |
| ACTION | what to do | investigate West pricing/inventory/churn |
| OUTCOME | how we'll know | track weekly West revenue, conversion, availability |
Juniors stop at Information. The jump to "70% is one category in one region" is what makes you valuable.

**EXERCISE 1A** — climb the ladder for *return rate = 9%*. (Model: up from 6% → concentrated in Apparel "wrong size" → erodes margin & logistics → add size-guide + fit reviews, audit suppliers → track Apparel return rate weekly, target <10%.)

**1.3 Reporting vs Analysis vs Storytelling** — what happened / why / what+why+so-what+now-what. Most "dashboards" are reporting in a storytelling costume (no conclusion headline, no implied action).

**1.4 Fact vs Insight.** "Sales dropped 10%" (fact) vs "dropped 10% because our largest segment cut order frequency after the June price increase" (insight = meaning + comparison + driver + relevance + action-hint).

**1.5 SO WHAT? / NOW WHAT?** SO WHAT pushes to meaning (a 15% revenue rise on deep discounting with falling margin is often *bad* news). NOW WHAT pushes to action (identify, check, define action, owner, follow-up KPI).

**EXERCISE 1B** — app conversion 2.8%→3.4%: run SO WHAT then NOW WHAT.

**1.6–1.7 Vague → analytical questions.** Decompose, never chart first. `Business question → Analytical question → Data question → KPI → Analysis → Insight`.

**CHEAT SHEET H1:** climb DATA→…→OUTCOME · interrogate every finding SO WHAT? NOW WHAT? · insight = meaning+comparison+driver+relevance+action-hint · decompose vague asks.

---
---
# HOUR 2 — KPI FUNDAMENTALS, DESIGN, HIERARCHY, DEFINITIONS

**2.1 What a KPI is.** A car has dozens of readings; you steer by a few *key* ones. A KPI tells you whether something **business-critical** is moving toward a desired outcome. `ALL METRICS ⊃ IMPORTANT ⊃ BUSINESS-CRITICAL ⊃ KPIs`. **Test: will someone act differently based on this number?** No → metric, not KPI.

**2.3 KPI design formula:** `KPI = OBJECTIVE + MEASUREMENT + TARGET + TIMEFRAME + OWNER + ACTION`.

**2.4 Definition template:** Name · Purpose · Definition · Formula · Numerator · Denominator · Unit · Grain · Time · Source · Target · Threshold · Owner · Direction · Action. 🎯 **The denominator is where KPIs quietly go wrong** (conversion with all sessions vs eligible sessions differs ~20%).

**2.5 Explicit formulas:** `Revenue = Gross Sales − Discounts − Returns`, not "sales."

**2.6 Grain** — the measurement level. Averaging an average breaks; aggregate with correct weights.

**2.7 Direction** — revenue/margin/CSAT/retention higher-better; cost/defect/churn/response lower-better.

**CHEAT SHEET H2:** KPI = Objective+Measurement+Target+Timeframe+Owner+Action · pin formula/denominator/grain/direction/owner.

---
---
# HOUR 3 — TARGETS, BENCHMARKS, LEADING/LAGGING, KPI TREES

**3.1 Targets/variance:** `Variance = Actual − Target`, `Achievement = Actual ÷ Target`. Report $ and %.
**3.2 Thresholds (RAG):** business-defined, tied to the cost of missing.
**3.3 Benchmarks vs Targets:** target = our commitment; benchmark = past/budget/industry/best. You need both lenses.
**3.4 Leading vs Lagging:** lagging = where you landed (can't change); leading = steering wheel. Carry both.
**3.5 KPI tree:** `PROFIT = REVENUE − COST`; `REVENUE = TRAFFIC × CONVERSION × AOV`. Turns "revenue is down" into three testable branches.
**3.6 Hierarchy & cascade:** North Star → Strategic → Tactical → Operational, cascaded to teams.
**3.7 North Star:** Northwind = "monthly repeat purchasing customers." Don't copy another company's.
**3.9 Trade-offs:** never optimize one KPI alone; pair efficiency with a guardrail.
**3.10 Vanity & anti-patterns:** pair vanity totals with a rate/cohort.

**CHEAT SHEET H3:** Variance=$ and %; compare vs target AND benchmark; leading steers, lagging scores; Revenue=Traffic×Conversion×AOV; decompose every outcome KPI into a tree; pair efficiency with a guardrail.

---
---
# HOUR 4 — BUILDING THE DATA STORY

**4.1 Spine:** WHAT → SO WHAT → NOW WHAT.
**4.2 Arc:** CONTEXT → TENSION/PROBLEM → EVIDENCE → DRIVERS → IMPACT → RECOMMENDATION → ACTION.
**4.3 Correlation vs causation:** say "the data is consistent with X," not "X caused it," until a controlled comparison or mechanism is established.
**4.4 Driver trees & variance bridges:** decompose the *change* into additive $ drivers. `Revenue shortfall −$500K = Volume −$250K + Price +$100K + Mix −$200K + Returns −$150K`. The bridge turns "we missed by $500K" into "here's exactly where it went."
**4.5 Trend vs seasonality vs spike vs anomaly vs structural change:** confusing seasonality for performance is the most common reporting error.
**4.6 Context & comparison:** a number needs at least one comparison.
**4.7 Root-cause toolkit:** 5 Whys · Fishbone · Driver tree · Pareto · Segmentation · Cohort. (Northwind 5 Whys: revenue↓→West↓→Electronics↓→top SKUs out of stock→supplier delay→no safety-stock rule. Root cause = inventory policy.)
**4.8 WHY framework:** WHAT changed → WHERE → WHEN → WHO → WHICH product/customer/channel → WHICH driver → HOW LARGE → WHY → ACTION.

**EXERCISE 4A** — revenue −8% YoY: using Revenue=Traffic×Conversion×AOV + segmentation, order of tests = **Localize → Decompose → Operationalize → Quantify** (+ separate seasonality via YoY).

**CHEAT SHEET H4:** spine + arc · decompose the CHANGE with a variance bridge · correlation ≠ causation · separate trend/seasonality/spike/anomaly/structural · Localize→Decompose→Operationalize→Quantify.

---
---
# HOUR 5 — VISUAL & EXECUTIVE STORYTELLING

**5.1 Start with the answer (BLUF):** "We're 8% below target, driven mostly by the West — here's why and what I recommend."
**5.2 Executive format:** summary → what changed → why → impact ($) → what to do → what next → how we'll measure.
**5.3 One-slide story:** HEADLINE → one primary chart → two sized drivers → business impact → recommended action.
**5.4 Headlines as insights:** "West drives 70% of the revenue decline," not "Revenue by Region." If the reader only reads titles, they get the story.
**5.5 Sequence & hierarchy:** SUMMARY → TREND → BREAKDOWN → DRIVERS → DETAIL → ACTION. Most important = largest visual.
**5.6 Preattentive attributes & color:** gray baseline + ONE accent; red=risk, green=good; never color alone.
**5.7 Data-ink:** remove anything without meaning.
**5.8 Chart selection:** trend→line, rank→horizontal bar, vs target→bullet/KPI, change→waterfall, composition→stacked, distribution→histogram, relationship→scatter, geography→map, single number→card, exact→table. Pie only 2–3 slices.
**5.9 Dashboard story structure:** pages read top-to-bottom like an argument, not a wall of tiles.

**CHEAT SHEET H5:** BLUF; headline = conclusion; titles = insights; Summary→…→Action; gray + one accent; kill non-data ink; chart from the QUESTION.

---
---
# HOUR 6 — EXECUTIVE COMMUNICATION, GOVERNANCE & CAPSTONE

**6.1 Audience:** same data, different story — CEO (growth/profit/risk/decision), CFO (revenue/margin/variance/forecast), COO (efficiency/SLA/capacity), Sales (pipeline/conversion/quota), Product (adoption/retention/churn), Customer lead (acquisition→retention→LTV).
**6.2 Fact vs Inference vs Hypothesis:** label which is which; presenting a hypothesis as fact loses credibility. Communicate uncertainty (confidence, limitations, missing data, assumptions, sample size, bias).
**6.3 Function KPI library:** Sales/Marketing/Product/CS/Operations/Finance quick lists.
**6.4 KPI selection framework:** connects to an objective? influenceable? measurable? defined? reliable data? owner? target? will someone act? Any "no" → challenge it.
**6.5 Scorecard:** read it, don't just display — KPI · Actual · Target · Variance · Trend · Status · Owner · Action.
**6.6 Cadence/governance:** real-time/daily=operational, weekly=tactical, monthly=management, quarterly=strategic. Frequency matches decision frequency. Governance = one agreed definition per metric.
**6.7 KPI → Decision matrix:** each KPI's Green/Amber/Red maps to a decision and an owner. A KPI with no decision rule may not be worth tracking.
**6.8 Action tracker:** INSIGHT → ACTION → OWNER → DEADLINE → EXPECTED IMPACT → FOLLOW-UP KPI.
**6.9 Analytics ladder:** DESCRIPTIVE → DIAGNOSTIC → PREDICTIVE → PRESCRIPTIVE.

## 6.10 THE CAPSTONE — "Growth has slowed. Why?"
Data (this Q vs LY): Revenue 30.0M→27.6M (−8%), Orders −6%, Traffic +2%, Conversion −8%, AOV −2.1%, Gross margin 30%→28%, High-value retention 80%→71% (−9 pts), Return rate 6%→9%, Marketing spend +15%, CAC +18%, Stock-out days 40→150 (+275%).

**Decompose with the identity:** Revenue = Traffic × Conversion × AOV. Traffic is *up* 2% → the −8% comes from **conversion (−8%)** and **AOV (−2%)**; traffic is NOT the problem (the key reframe). **Segment:** conversion drop concentrates where top SKUs went out of stock (+275% stock-out days) — can't convert what you can't buy. **Retention & returns:** high-value retention −9 pts, returns to 9% (Apparel fit) — losing your best customers AND giving back revenue. **Marketing:** spend +15%, CAC +18%, new customers −1.7% → buying less for more.

**Variance bridge (vs LY revenue −$2.4M):** Conversion ≈ −$2.2M (biggest lever), AOV ≈ −$0.6M, Traffic ≈ +$0.4M → net −$2.4M. Plus margin erosion & returns drag.

**Executive headline:** *"Revenue is 8% below last year — and it's not a traffic problem. Traffic grew 2%, but conversion fell 8% because top products were out of stock 4× more often, while our highest-value customers churned (retention −9 pts) and returns rose to 9%. The biggest lever is availability (~$2.2M of the $2.4M gap). Recommend: (1) fix inventory on top SKUs, (2) high-value retention play, (3) fix Apparel fit — and pause the marketing-spend increase until conversion recovers. Track weekly: availability, conversion, high-value retention, return rate, revenue."*

**Actions/owners/follow-up KPIs:** stock-outs→safety-stock rule (Ops, 2wks, availability%); high-value churn→retention offer (CS, 30d, retention); Apparel returns→size guide + supplier audit (Product/Merch, 30d, return rate); CAC rising→hold spend, reallocate to retention (Marketing, now, CAC).

**6.11 Presentation drills:** 30s (headline + #1 driver + #1 action) · 1m (+ variance bridge) · 3m (+ retention/returns/marketing) · 5m (full arc + monitoring + fact/hypothesis labels). "One chart only" = the **variance bridge**.

---
# SURVIVAL KIT (17 cheat sheets)
Data→Insight ladder · What/So-what/Now-what · KPI design · KPI dictionary template · KPI trees (Profit=Rev−Cost; Rev=Traffic×Conversion×AOV; ARR=New+Expansion−Contraction−Churn) · Leading vs Lagging · Target vs Benchmark · Variance analysis + bridge · Root cause (5 Whys/Fishbone/Driver tree/Pareto/Segmentation/Cohort; Localize→Decompose→Operationalize→Quantify) · Executive storytelling (BLUF; label Fact/Inference/Hypothesis) · Chart selection · Dashboard storytelling · Executive presentation (30s/1m/3m/5m) · Insight writing · Action plan · KPI governance · Function KPI library.

# SCORING RUBRICS
Insight Quality /70 (Observation·Context·Driver·Impact·Actionability·Evidence·Clarity). KPI Quality /80. Dashboard Story /100.

# INTERVIEW BANK (sample)
KPI design, data storytelling, business-analysis case rounds (15 each). For each answer: what was right, what missing, better answer, senior answer, project perspective.

# SIX CASE STUDIES
Revenue↑ profit↓ · Customers↑ retention↓ · Leads+50% sales flat · Cost−15% CSAT↓ · Revenue>target cash<target · Sales−10% (run the WHY framework).

# THE GOLDEN RULE
Don't be the person who says *"Revenue is down 10%."* Be the person who says *"Revenue is 10% below plan, mostly West and two high-value categories, driven by lower conversion and stock-outs; the quarter is at risk; prioritize stock recovery and a checkout audit; monitoring conversion, availability, and weekly revenue"* — **and can prove every clause with data.**
*QUESTION → THINK → MEASURE → ANALYZE → EXPLAIN → RECOMMEND → ACT → MEASURE AGAIN.*
