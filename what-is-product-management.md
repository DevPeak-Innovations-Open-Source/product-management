# 1 — Quick reality check (what marketplace PMs actually do)

A marketplace connects supply and demand. Your job: get both sides to show up, trust the platform, and keep transacting while making unit economics work. That means obsessing over liquidity, trust, conversion, retention, margins, and operations — not “features.” If you like building dashboards and debating colors more than fixing buyer/seller supply mismatches, this role will eat you.

# 2 — Core concepts you must master (no excuses)

* **Two-sided network effects** — value grows when both sides increase. Measure and manage growth for both.
* **Liquidity** — enough supply where demand is. First metric to optimize.
* **GMV (Gross Merchandise Value)** — total transaction value. Primary growth KPI.
* **Take rate** — % you keep of each transaction (revenue/GMV).
* **Unit economics** — CAC, LTV, contribution margin per transaction.
* **CAC payback** and **CAC by cohort**.
* **Conversion funnel** (visit → listing view → add to cart/booking → purchase).
* **Trust & safety** — ratings, disputes, identity verification, refunds.
* **Marketplace types**: inventory-led vs. inventory-less (peer/third-party), C2C, B2C, vertical vs. horizontal.
* **Chicken-and-egg problem** — early tactics to get both sides to critical mass.
* **Price discovery & incentives** — matching algorithms, search ranking, fees, subsidies.

# 3 — Mindset & priorities (ruthless)

* Prioritize experiments that improve **liquidity** and **conversion**. Everything else is secondary.
* If a feature doesn’t improve one of these or reduce cost of operations, it’s probably nice-to-have.
* Ship fast. Measure. Kill it if it doesn’t move metrics in 2–6 weeks. If you can’t measure it, don’t ship it.
* Build smallest experiments possible to test assumptions (landing pages, manual concierge, Craigslist-style MVP).
* Say “no” to shiny ideas that require high ops cost unless they show unit economics quickly.

# 5 — How I’ll judge your ideas (quick checklist)

For any idea you propose I’ll immediately ask:

1. What **hypothesis** are you testing? (single sentence)
2. What **metric** will move if hypothesis true? (primary KPI)
3. What’s the **smallest experiment** to test it? (landing page, concierge, A/B)
4. What’s the **expected lift** and how will you measure significance?
5. What are the **ops costs** and can they scale?
6. Does it help liquidity or conversion? If not — why are you building it?

If you can’t answer those five, your idea is early-stage crap. I’ll tell you bluntly.

# 6 — Common weak/overbuilt ideas (and why they fail)

* “Let’s build a huge loyalty rewards program before product-market fit.” — Bad. Rewards hide a broken product. Fix conversion first.
* “We’ll subsidize both sides forever.” — Unsustainable. Test payback quickly. If CAC > LTV, the model fails.
* “We need a fancy matching algorithm.” — Don’t. Manual rules + data labeling until you have scale. Algorithms can be a costly distraction.
* “Let’s copy feature X from Amazon.” — Feature parity doesn’t solve liquidity or unit economics. Copying is lazy.

# 7 — Tactical playbook (concrete actions you can run now)

### Early-stage (0–10k GMV/month)

* Launch *hyperlocal* or *vertical* MVP: fewer categories = easier liquidity.
* Use manual curation/concierge to guarantee first transactions.
* Seed supply via partnerships rather than product features.
* Run paid acquisition to one cohort + onboarding handholding.

### Growth (post-product market fit)

* Optimize search ranking with strongest indicators (fulfillment speed, price, seller rating).
* Personalize listings and email/SMS retargeting to convert.
* Introduce marketplace fees slowly; test different take rates in cohorts.
* Build features to reduce ops cost (automated payouts, dispute triage).

### Reliability & scale

* Build fraud detection, identity verification, scalable onboarding flows.
* Automate refunds and create clear SLA for support.
* Localize operations to comply with regulations.

# 8 — Experiment design template (use this every time)

* **Name:** short
* **Hypothesis:** If we X, then Y will change by Z% in T days.
* **Primary metric:** (e.g., 7-day conversion rate)
* **Secondary metrics:** (GMV, return rate, time to first transaction)
* **Experiment:** smallest realistic test (MVP or A/B)
* **Segments:** which cohorts?
* **Duration & sample size:** expected weeks and min N
* **Success criteria:** clear pass/fail
* **Ops cost & rollback plan**

# 9 — PRD template (concise, use every time)

1. **Title & owner**
2. **Problem statement** (1–2 sentences, with data)
3. **Goal / KPIs** (quantitative)
4. **User stories** (buyers, sellers, ops)
5. **Scope** (MVP vs later)
6. **Experiment plan** (A/B, rollout)
7. **Metrics & instrumentation**
8. **Risks & mitigation**
9. **Launch plan** (training, ops support)
10. **Postmortem criteria & timeline**

# 10 — KPIs you must track (daily & weekly)

Daily: sessions, listing views, new listings, active sellers, new buyers, transactions, GMV, failed transactions.
Weekly: conversion rates across funnel steps, time to first sale (seller), retention by cohort, CAC, LTV estimate, take rate, refunds rate, dispute volume, ops tickets per transaction.

# 11 — Playbook for judging scaling potential quickly

If your idea is a feature, answer:

* Does it increase transactions per user or lower cost per transaction? If no → low priority.
* Can it be tested in one city/cohort? If no → too big.
* Does it add permanent ops cost per transaction? Ops cost must not grow faster than GMV.
* Is the hypothesis about human behavior or system performance? Human behavior is scoreable via small experiments.

# 12 — 10 practical exercises (do them, send results, I’ll roast)

1. Map your marketplace’s funnel and annotate numbers for each step.
2. Interview 3 sellers and 3 buyers; summarize top pain points.
3. Write one hypothesis and design the smallest experiment to test it.
4. Run a concierge onboarding for 5 sellers — convert at least 1 sale.
5. Build a one-page dashboard with funnel metrics (even in a spreadsheet).
6. A/B test two listing titles for conversion on 100 impressions.
7. Calculate CAC and estimate LTV for the next 12 months.
8. Draft an ops SOP for refunds and disputes in <1 page.
9. Set up a fake “landing page” to validate demand for a new category.
10. Price elasticity test: show 2 price points to sellers and measure acceptance.

# 15 — Resources & tools (practical)

* Analytics: Mixpanel / Amplitude / GA4 for funnel events (instrumentation first).
* Data: BigQuery / Redshift for cohort analysis.
* Experimentation: Optimizely / internal A/B or simple feature flags.
* Ops: Zendesk / Intercom; payment partner with good dispute tools.
* Marketplace features to consider building later: instant payouts, insurance/guarantees, logistics integration.

---
