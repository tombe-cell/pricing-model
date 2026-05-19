# Trial experience — synthesis (decision doc)

**Last updated:** May 2026  
**Full research:** [trial-experience-competitors.md](trial-experience-competitors.md) · [monday doc](https://monday.monday.com/docs/18413672392)

---

## One-line recommendation

**Ship O5 (guided hybrid trial):** keep **14 days**, **enforce a visible credit pool** (~2K–3K, aligned to Pro monthly minimum), add **2–3 AI missions in week 1**. Fallback: **O3** without missions.

---

## monday today vs peers

| | monday (today) | Typical PLG peer | AI-native peer |
|--|----------------|------------------|----------------|
| Time cap | **14d enforced** | 14d or none (freemium) | Hours–14d |
| Credit cap | 6K granted, **not enforced** | 20 actions – 1K credits | 5/day – usage windows |
| What binds first | **Day 14** | AI limit or 14d | Usage/credits |
| Post-trial | Pay / Free / churn | Pay / free tier | Pay / capped free |

---

## Options O1–O5

| Option | Description | When to use |
|--------|-------------|-------------|
| **O1** | Status quo: 14d, 6K, no enforcement | Only if packaging delay |
| **O2** | Longer time (21–30d), same credits | If activation data shows time-only gap |
| **O3** | Hybrid strict: 14d + enforce credits + visible bar | Minimum viable alignment with paid model |
| **O4** | Credit-first, minimal/no time cap | **Not recommended** (low burn + freemium risk) |
| **O5** | O3 + guided AI missions + credit literacy | **Recommended** default |

---

## Why O5

1. Paid model = **seats + mandatory monthly credits** — trial must teach the meter.
2. **Low trial burn** today means credit-only caps won't bite without **activation design**.
3. Competitors (Notion, ClickUp, Lovable, Clay) **enforce AI early** — monday is the outlier.
4. **14-day backstop** preserves familiar motion and matches Atlassian.

---

## Internal data (BigBrain, Nov 2025 – May 2026)

| Metric | Value |
|--------|-------|
| Trial accounts (~14d cohort) | ~2.0M |
| **% using any AI in trial** | **16.4%** |
| Median credits (AI users only) | **16** (~0.4% of ~4K avg limit) |
| P90 credits (AI users only) | **168** (~4.2% of limit) |
| **Blocked for credit exhaustion** | **0** |
| Reached 80% utilization | **16 accounts** (of ~2M) |
| **% hitting day 14 vs credits** | **~100% time** — credits never bind |

**Implication:** Trial credit pool is **oversized vs demand**; enforcement would only matter after **AI activation** (missions). O5 > O3 for adoption; cap can be **2K–3K** not 6K for trialists who do use AI.

---

## Still optional

- In-product paywall screenshots (Notion 20-response modal, etc.)
- Swan trial credit grant (verify at signup)
- Segment D deep dives (low relevance)

---

## Segments covered

| Segment | Products | Status |
|---------|----------|--------|
| A — PLG workspace | Notion, ClickUp, Atlassian, Rovo Dev | Done |
| B — AI-native | Claude, ChatGPT, Cursor, Lovable, Gemini, Copilot Studio | Done |
| C — GTM | Clay, relay.app, Swan, Intercom Fin | Done |
| D — Data | Databricks, Snowflake | Done (brief) |
