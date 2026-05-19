# Trial experience — competitive research

**Segment A (PLG workspace):** Notion, ClickUp, Atlassian  
**Storage:** This repo — [`trial-experience-baseline-monday.md`](trial-experience-baseline-monday.md), screenshots in [`trial-research/screenshots/`](trial-research/screenshots/)  
**Visual gallery:** Open [`trial-research/trial-experience-screenshots.html`](trial-research/trial-experience-screenshots.html) in a browser.

**Confidence:** High = official help/pricing; Medium = third-party + logical inference; Low = unverified.

---

## Segment A at a glance

| Product | Trial archetype | Primary enforced cap | AI credits? | Credits enforced in trial? | Time to first paywall (typical) | Monetization |
|---------|-----------------|----------------------|-------------|----------------------------|----------------------------------|--------------|
| **Notion** | T4 freemium + T2 AI cap | **AI actions** (20 total); platform is not time-limited | No separate “credits” — **responses** | **Yes** (AI hard stop) | **~20 AI actions** (power user: same session; casual: days–weeks) | Seats ($10 Plus, $20 Business) + AI bundled in Business+ |
| **ClickUp** | T4 freemium + T3 hybrid AI trial | **AI trial uses** + optional **paid plan trial** | **AI Super Credits** (500–1K trial; 1.5K–5K/mo paid) | **Yes** (AI trial limits; notify at 100%) | **25–175 Brain uses** (hours–days); platform paywall only if you start paid trial or hit free limits | Seat plans + AI SKUs ($9 Brain, $28 Everything AI) + credit packs |
| **Atlassian** (Jira/Confluence) | T1 time-capped cloud trial | **14 days** (Standard); 30d Premium/Ent | **Rovo credits** (pooled monthly) | **Soft** — quotas exist; **overage not billed yet** (90-day opt-in notice) | **14 days** (platform); Rovo: **~2–3 heavy chats/mo** at Standard allowance if only metered features used | Per-seat cloud + Rovo bundled; Rovo Dev $20/dev + credits |
| **Atlassian Rovo Dev** | T1 (30-day) + T2 credits | **2,000 credits/dev/mo** | **Rovo Dev credits** | **Yes** (paid overflow $0.01/credit) | **30-day trial**, then pay; credits can exhaust mid-cycle | $20/dev/mo + usage |

---

## Notion

### What they limit

| Layer | Limit | Enforced? | Resets? |
|-------|-------|-----------|---------|
| **Workspace (Free/Plus)** | Blocks, guests, file size, history — not a time trial | Soft (feature caps) | N/A — ongoing freemium |
| **Notion AI (Free/Plus)** | **20 complimentary AI responses per workspace** | **Yes** — upgrade message; AI stops | **Never** (one-time trial) |
| **Notion AI (Business+)** | “Unlimited” with fair-use; paid: **30 responses / 24h** soft cap reported | Soft daily cap on paid | Daily (paid) |

Sources: [Complimentary AI responses](https://www.notion.com/help/complimentary-ai-responses), [Notion AI FAQs](https://www.notion.com/help/notion-ai-faqs), [2025 pricing changes](https://www.notion.com/help/2025-pricing-changes)

### AI credits?

**No credit currency.** Usage is counted as **AI responses** (1 per action, including “Try again”).

### Credits cap during trial?

N/A — **response cap: 20 total** on Free/Plus. Not monthly.

### How they monetize

- **Plus:** ~$10/seat/mo — workspace features, still only 20 AI responses.
- **Business:** ~$20/seat/mo — **Notion AI included** (Agent, Enterprise Search, Meeting Notes, etc.).
- **Enterprise:** custom.
- As of May 2025, **no AI add-on** on Free/Plus for new users — must upgrade tier.

### Time to paywall

| User type | Platform paywall | AI paywall |
|-----------|------------------|------------|
| Free user building wiki | None (freemium) | **After ~20 AI actions** |
| Team needing AI daily | Upgrade to Business | Immediate if >20 responses needed |
| **Estimate** | No time wall | **15–60 min** of active AI use, or **never** if they don’t use AI |

### End-of-trial / paywall UX

- **AI exhausted:** Message that **Business or Enterprise** is required; owner must upgrade on desktop.
- **Platform:** No “trial expired” — optional upgrade for limits (blocks, guests, etc.).

### Screenshots

| Asset | File / link |
|-------|-------------|
| Notion AI agent in product | `trial-research/screenshots/segment-a/notion-ai-agent-ui.png` |
| Brainstorm / AI inline UI | `trial-research/screenshots/segment-a/notion-brainstorm-ui.png` |
| Pricing / AI bundled in Business | `trial-research/screenshots/segment-a/notion-pricing-explained.png` |
| **Missing: AI limit paywall** | Capture: use 20 AI actions on Free → screenshot upgrade modal |

---

## ClickUp

### What they limit

| Layer | Limit | Enforced? |
|-------|-------|-----------|
| **Workspace** | Starts **Free Forever** — no automatic time trial | Upgrade prompts when hitting storage (100MB+) or feature caps |
| **Optional paid plan trial** | “Free trials” when testing Unlimited/Business/etc. — duration **not stated in help** | On expiry: **read-only** for paid features; data kept |
| **ClickUp AI trial** (auto in all workspaces) | **Brain uses** (25–175 by plan/size), **Talk to Text** words, **500–1,000 AI Super Credits** (trial pool) | **Yes** — notified at **100%** of trial limits; must purchase AI add-ons after |

Sources: [AI limits](https://help.clickup.com/hc/en-us/articles/20686299081879), [Intro to pricing](https://help.clickup.com/hc/en-us/articles/10129535087383), [Upgrade plan / free trials](https://help.clickup.com/hc/en-us/articles/6303314345623), [AI pricing page](https://clickup.com/pricing)

### AI credits?

**Yes — AI Super Credits** for premium AI (agents, automations, image gen, etc.).

| Phase | Super Credits |
|-------|----------------|
| **AI trial** | 500 total (Free Forever) or **1,000 per user** (paid plans during trial) |
| **Paid Brain AI** | +1,500 / user / mo |
| **Paid Everything AI** | +5,000 / user / mo |
| **Top-up** | $10 / 10,000 credits |

**Brain “uses”** are a separate meter from Super Credits (assistant / @Brain).

### Credits cap during trial?

**Yes** — trial Super Credit pool + Brain use caps. **Enforced** with notification at 100%.

### How they monetize

1. **Seat plans:** Free → Unlimited ($7) → Business ($12) → Enterprise  
2. **AI plans:** Brain AI **$9/user/mo**, Everything AI **$28/user/mo**  
3. **Credit packs** and add-ons (Notetaker, Talk to Text)  
4. **30-day money-back** on first paid subscription

### Time to paywall

| Path | Time to wall |
|------|----------------|
| Stay on Free Forever, use AI trial | **25–50 Brain uses** → often **same day** for evaluators |
| Start paid plan trial | **Unknown days** (check Billing → trial details in-product) — third parties often cite **~14 days** |
| Never buy AI | AI trial ends → **purchase AI add-on** or lose AI |

### End-of-trial UX

- AI: Must buy **Brain AI**, **Everything AI**, or individual add-ons.
- Free Forever: Cannot buy AI until on a **paid seat plan**.

### Screenshots

| Asset | File / link |
|-------|-------------|
| AI pricing / Trial column on SKUs | `trial-research/screenshots/segment-a/clickup-ai-pricing-compare.webp` |
| Live pricing | https://clickup.com/pricing (scroll to **AI PRICING**) |
| Brain pricing LP | https://clickup.com/lp/brain/pricing |
| **Missing: 100% trial notification** | Capture: burn Brain uses on trial → screenshot notification |

---

## Atlassian (Jira / Confluence / Rovo)

Treat as **three related products**:

### A) Cloud product trial (Jira, Confluence, etc.)

| Dimension | Detail |
|-----------|--------|
| **Archetype** | **T1 – Time-capped** |
| **Duration** | **14 days** Standard; **30 days** Premium/Enterprise |
| **After trial** | Add card → paid, or **downgrade to Cloud Free** (no card) |
| **AI during trial** | Can trial **Rovo** via cloud trial of eligible products |

Source: [Atlassian licensing – trials](https://www.atlassian.com/licensing/purchase-licensing#trials)

**Time to paywall:** **14 days** (Standard) — comparable to monday.

### B) Rovo (included AI on paid cloud)

| Dimension | Detail |
|-----------|--------|
| **AI credits?** | **Yes — Rovo credits** (pooled org-wide, **monthly reset**, no rollover) |
| **Allowance (examples)** | Standard Jira/Confluence: **25 credits/user/mo**; Premium: **70**; Enterprise: **150**; Teamwork Collection: **250–1,500** |
| **What spends credits** | Rovo Chat, Agents (**10**/request), Deep Research (**100**/request). Search/summaries often **free** today |
| **Enforcement** | Limits exist; **extra usage not billed yet** — 90-day notice + opt-in before charges |
| **Trial-specific cap?** | During cloud trial you get plan features; same credit pool mechanics |

Sources: [Rovo usage allowance](https://support.atlassian.com/rovo/docs/rovo-usage-limits/), [Rovo pricing FAQ](https://www.atlassian.com/software/rovo/pricing)

**Time to “paywall”:** Usually **14-day site trial** binds before credits. Heavy Rovo Chat could hit pool limits in **days** on small teams — enforcement UX unclear until billing turns on.

### C) Rovo Dev (separate SKU)

| Dimension | Detail |
|-----------|--------|
| **Trial** | **30-day free trial** |
| **Credits** | **2,000 Rovo Dev credits / developer / month** |
| **Enforcement** | **Yes** — **$0.01/credit** overage; default extra 2K credits/mo auto-enabled |
| **Free tier** | No — limited credits may roll out to some Jira sites (admin opt-out) |

Source: [Rovo Dev pricing](https://www.atlassian.com/software/rovo-dev/pricing)

### How Atlassian monetizes AI

- **Rovo:** Bundled into Standard+ cloud (seat uplift); future consumption billing.
- **Rovo Dev:** **$20/developer/mo** + overage credits.
- **No freemium** for Rovo itself on free cloud sites (Rovo requires Standard+).

### Screenshots

| Asset | File / link |
|-------|-------------|
| Rovo marketing / product visual | `trial-research/screenshots/segment-a/atlassian-rovo-hero.png` |
| Rovo in Jira (docs reference screenshots) | https://support.atlassian.com/rovo/docs/using-rovo/ |
| **Missing: usage dashboard / limit warning** | Capture: Admin → Platform usage; or community-reported limit state |

---

## Comparison to monday (today)

| Dimension | monday | Notion | ClickUp | Atlassian |
|-----------|--------|--------|---------|-----------|
| Time trial | **14d Pro** | No (freemium) | Optional on upgrade | **14d** Standard cloud |
| AI unit | Credits (6K once) | 20 responses | Super Credits + Brain uses | Rovo credits |
| AI enforced in trial | **No** | **Yes** | **Yes** | Partial / evolving |
| Primary wall | **Day 14** | **20 AI actions** | **AI uses** or plan trial | **Day 14** |
| Freemium after | **Free plan** | **Free plan** | **Free Forever** | **Cloud Free** |

---

## Screenshot capture playbook (paywalls we could not fetch)

| # | Product | Steps | Est. time |
|---|---------|-------|-----------|
| 1 | **Notion** | Free workspace → run AI 20× (summarize, brainstorm) → capture upgrade modal | ~10 min |
| 2 | **ClickUp** | Free Forever workspace → exhaust Brain trial uses → capture 100% notification | ~15 min |
| 3 | **ClickUp** | Settings → Billing → start Unlimited trial → capture trial banner (if shown) | ~5 min |
| 4 | **Atlassian** | New cloud Standard trial → open Rovo Chat → Admin Platform usage | ~15 min |
| 5 | **Rovo Dev** | Start 30-day trial → burn credits in CLI/review → capture overage UX | ~20 min |

Save captures under `trial-research/screenshots/segment-a/` with names like `notion-ai-paywall.png`.

---

## Sources

- Notion: https://www.notion.com/help/complimentary-ai-responses , https://www.notion.com/pricing  
- ClickUp: https://help.clickup.com/hc/en-us/articles/20686299081879 , https://clickup.com/pricing  
- Atlassian: https://www.atlassian.com/licensing/purchase-licensing#trials , https://support.atlassian.com/rovo/docs/rovo-usage-limits/ , https://www.atlassian.com/software/rovo-dev/pricing  

---

## Segment B at a glance (AI-native / builder)

| Product | Trial archetype | Primary enforced cap | AI credits? | Credits enforced? | Time to first paywall | Monetization |
|---------|-----------------|----------------------|-------------|-----------------|----------------------|--------------|
| **Claude** | T4 freemium | **Usage limit** (rolling session window) | No — **usage sessions** | **Yes** — hard stop, wait for reset | **Hours** (variable; ~15–40 msgs / ~5hr reported) | Pro $20, Max $100–200, Team, API |
| **ChatGPT** | T4 freemium | **Rate limit** on GPT-5.5 (5-hour window) | No — rate limits | **Yes** — notify + upgrade prompt; can use other tools separately | **Hours** (limited GPT-5.5 msgs per 5hr) | Plus ~$20, Pro, Business, API |
| **Cursor** | T1 (14d Pro trial) + T4 Hobby | **Included API $** on paid; Hobby limited | **Token/API usage** (not “credits”) | **Yes** on Hobby; paid = pay-as-you-go at limit (no downgrade) | **14-day trial** then Hobby limits; power users hit monthly $ fast | Pro $20/mo (+$20 API pool), Pro+ $60, Ultra $200 |
| **Lovable** | T4 freemium (no time trial) | **Daily + monthly credits** | **Yes** — credits per message | **Yes** — hard block when out | **~5 credits/day** → **1–5 messages** for heavy prompts | Pro from $25/mo + top-ups |
| **Google Gemini** | T4 freemium | **Prompts/day** by model tier | No — prompt counts | **Yes** — fall back to Fast model or wait | **Same day** for Pro model (e.g. 10–30 prompts/day free) | Google AI Pro ~$20/mo, Ultra $250 |
| **Copilot Studio** | T1 trial (maker) | **Trial = build only**; paid = **Copilot Credits** | **Yes** — Copilot Credits | **Yes** on paid (capacity enforcement) | **Trial:** test panel only; **Paid:** monthly capacity | Prepaid packs, PAYG, M365 Copilot bundle |
| **Rovo Dev** | *(see Segment A)* | 30-day trial + 2K credits/dev/mo | Rovo Dev credits | Yes | 30 days | $20/dev/mo |

---

## Claude

### What they limit

| Layer | Limit | Enforced? | Resets? |
|-------|-------|-----------|---------|
| **Free** | Usage limits across claude.ai, Claude Code, Desktop (shared pool) | **Yes** — must wait, upgrade, or buy extra usage | **Rolling** (session-based; not published as fixed daily count) |
| **Length** | 200K token context window (500K Enterprise) | Soft — auto-summarize if code execution enabled | Per conversation |

Sources: [Usage and length limits](https://support.claude.com/en/articles/11647753), [Choosing a plan](https://support.claude.com/en/articles/11049762)

### AI credits?

**No credit currency.** “Usage” = message/session budget affected by model, length, tools, file uploads.

### Credits cap during trial?

N/A — **usage cap**, not credits. Free tier is ongoing freemium, not a time-boxed trial.

### How they monetize

- **Pro:** ~$20/mo — higher usage
- **Max:** $100 or $200/mo — much higher limits
- **Team / Enterprise:** seat-based
- **Extra usage** purchasable on paid plans
- **API** separate consumption pricing

### Time to paywall

- **Typical:** Heavy user hits limit in **one session** (hours)
- **Light user:** May not hit limit for days
- **Paywall UX:** Wait for limit reset **or** upgrade to Pro/Max **or** buy extra usage

### End-of-trial UX

No classic “14-day trial expired.” **Usage exhausted** → hard pause with reset timer / upgrade CTA.

### Screenshots

| Asset | Link |
|-------|------|
| Pricing | https://www.anthropic.com/pricing |
| **Missing:** limit message in chat | Capture after heavy use on free account |

---

## ChatGPT

### What they limit

| Layer | Limit | Enforced? |
|-------|-------|-----------|
| **Free** | **GPT-5.5** limited number of times per **5-hour window** | **Yes** — notified + invited to upgrade |
| **Free** | Separate limits for: data analysis, file uploads, image creation | **Yes** — each tool has own rate limit |
| **GPTs** | Same pool as GPT-5.5 text limit | Stops when text limit hit |
| **Ads** | Rolling out in free tier (some countries) — may reduce limits vs. paid | — |

Source: [ChatGPT Free Tier FAQ](https://help.openai.com/en/articles/9275245)

### AI credits?

**No.** Rate limits on messages and tools.

### Credits cap during trial?

N/A — freemium with **metered GPT-5.5 access**, not a time trial.

### How they monetize

- **Plus** ~$20/mo — higher rate limits
- **Pro, Business, Enterprise**
- **API** usage-based
- **Ads** on free tier (emerging)

### Time to paywall

- **5-hour window** on flagship model — active user can hit in **one afternoon**
- Upgrade **immediately resets** limits (per FAQ)

### End-of-trial UX

**In-session notification** when limit reached → upgrade to Plus/Pro/Business. No account expiry — ongoing free tier.

### Screenshots

| Asset | Link |
|-------|------|
| Pricing | https://openai.com/chatgpt/pricing |
| **Missing:** rate limit notification | Capture on free account after heavy GPT-5.5 use |

---

## Cursor

### What they limit

| Layer | Limit | Enforced? |
|-------|-------|-----------|
| **Hobby (free)** | Limited **API usage** + **Auto/Composer** pools; unlimited Tab completions | **Yes** at pool exhaustion |
| **14-day Pro trial** | Full Pro access (community/docs reference; verify in signup) | Reverts to Hobby after 14 days |
| **Pro ($20/mo)** | $20/mo **API pool** + generous **Auto+Composer** pool | At limit: **pay-as-you-go** or upgrade — **no quality downgrade** |
| **Pro+ / Ultra** | $70 / $400 API included | Same |

Sources: [Cursor pricing docs](https://cursor.com/docs/account/pricing), [cursor.com/pricing](https://cursor.com/pricing)

**Note:** Older “50 slow premium requests” model may apply to legacy accounts; current docs emphasize **$ usage pools**.

### AI credits?

**Token-based API billing**, not branded “credits.” Two pools: **Auto+Composer** and **API** (per-model rates).

### Credits cap during trial?

**14-day Pro trial** = full Pro allowances. After trial → **Hobby caps**.

### How they monetize

- **Pro** $20/mo, **Pro+** $60, **Ultra** $200
- **Teams** $40/user/mo
- **On-demand** API usage at provider rates when over included $

### Time to paywall

| Path | Time to wall |
|------|----------------|
| **14-day Pro trial** | **14 days** then Hobby |
| **Hobby only** | Depends on agent usage — power users **days to weeks** |
| **Pro subscriber** | Monthly reset; heavy users add on-demand same month |

### End-of-trial UX

**Trial end:** Downgrade to Hobby (limited pools). **Limit hit on paid:** Pay-as-you-go or upgrade — explicitly **not** slowed/downgraded model quality.

### Screenshots

| Asset | Link |
|-------|------|
| Pricing | https://cursor.com/pricing |
| Usage dashboard | https://cursor.com/dashboard/usage |
| **Missing:** limit / upgrade modal | Capture when API pool exhausted |

---

## Lovable

### What they limit

| Layer | Limit | Enforced? | Resets? |
|-------|-------|-----------|---------|
| **Free** | **5 daily credits**, max **30 credits/month** | **Yes** — cannot send messages when out | Daily: midnight UTC; monthly cap on free |
| **Pro** | 5 daily (up to 150/mo) + **monthly credit pack** (100–10K tiers) | **Yes** | Monthly billing cycle; daily credits don’t roll over |
| **Paid top-ups** | 50-credit increments ($15 Pro / $30 Business) | — | Valid 12 months |

Source: [Plans and credits](https://docs.lovable.dev/introduction/plans-and-credits)

**No traditional free trial** — freemium with credit meter from day one.

### AI credits?

**Yes.** Credits per message (0.5–2+ depending on complexity). Visible credit bar in UI.

### Credits cap during trial?

**Always on** — free tier is credit-capped from signup.

### How they monetize

- **Pro** from **$25/mo** (100 credits/mo) scaling to $2,250/mo for 10K credits
- **Business** 2× Pro price for same credit tiers
- **Credit top-ups** on paid plans

### Time to paywall

- **5 daily credits** ≈ **1–5 messages** (complex builds cost 1.2–2 credits each)
- **30/month cap** can bind before daily reset for active builders
- **Very fast** paywall vs. monday’s 14-day time wall

### End-of-trial UX

**Out of credits:** Low-credits alert in chat → upgrade or top-up. **Hard block** on send.

### Screenshots

| Asset | Link |
|-------|------|
| Pricing | https://lovable.dev/pricing |
| Credit bar | In-product (workspace name / project header) |
| **Missing:** out-of-credits modal | Capture after 5 credits consumed |

---

## Google Gemini (consumer)

### What they limit

| Layer | Limit (Free / no Google AI plan) | Enforced? |
|-------|----------------------------------|-----------|
| **Gemini 3.1 Pro** | **Up to 10 prompts/day** (192K context) | **Yes** — switch to Fast or wait |
| **Thinking** | Basic access (limits change frequently) | Yes |
| **Deep Research** | **5 reports/month** | Yes |
| **Images** | **Up to 20 images/day** | Yes |
| **Context** | 32K tokens (vs 1M on paid) | — |

**Google AI Pro (~$20/mo):** e.g. 100 Pro prompts/day, 100 images/day, 12 Deep Research/day.

Source: [Gemini Apps limits](https://support.google.com/gemini/answer/16275805)

### AI credits?

**No.** Prompt/day and feature/day counters.

### Credits cap during trial?

No time trial — **freemium with daily/monthly feature caps**.

### How they monetize

- **Google AI Plus / Pro** ~$19.99/mo (via Google One)
- **Google AI Ultra** ~$249.99/mo
- Bundled storage and Google services

### Time to paywall

- **Pro model 10 prompts/day** → **same day** for evaluators
- In-app notification when near limit + when limit refreshes

### End-of-trial UX

**At limit:** Prompt to upgrade to Google AI Pro **or** continue with **Fast** model in same chat.

### Screenshots

| Asset | Link |
|-------|------|
| Limits table | https://support.google.com/gemini/answer/16275805 |
| **Missing:** limit notification in Gemini app | Capture after 10 Pro prompts |

---

## Microsoft Copilot Studio

### What they limit

| Layer | Limit | Enforced? |
|-------|-------|-----------|
| **Trial license** | Build agents + **test chat only** — **cannot publish** | Trial expiry blocks publish |
| **Trial extension** | Can extend 30 days; agents work up to 90 days post-expiry (per signup docs) | — |
| **Paid** | **Copilot Credits** (formerly messages) — monthly capacity, **no rollover** | **Yes** — service denial if over capacity without adjustment |
| **Dev/trial env** | 10 RPM / 200 RPH quota for generative AI messages | Yes |

Sources: [Billing & licensing](https://learn.microsoft.com/en-us/microsoft-copilot-studio/billing-licensing), [Sign up](https://learn.microsoft.com/en-us/microsoft-copilot-studio/sign-up-individual)

### AI credits?

**Yes — Copilot Credits** (common currency since Sep 2025).

### Credits cap during trial?

Trial is **access-limited** (no publish), not credit-metered for makers testing in panel.

### How they monetize

- **Prepaid Copilot Credit packs** (tenant subscription)
- **Pay-as-you-go** via Azure
- **Microsoft 365 Copilot** license — extend M365 with agents (zero-rated in some M365 surfaces)
- **Capacity packs** e.g. $200 / 25K messages legacy framing

### Time to paywall

- **Trial:** Time-bound license (extendable) — not a PLG “try AI in product” like monday
- **Paid:** Monthly credit pool exhaustion → enforcement / purchase more

### End-of-trial UX

**Trial:** Cannot publish agents; must license. **Over capacity:** Technical enforcement per Microsoft policy.

### Screenshots

| Asset | Link |
|-------|------|
| Licensing | https://learn.microsoft.com/en-us/microsoft-copilot-studio/billing-licensing |
| **Missing:** test vs publish gate | Capture trial publish attempt |

---

## Segment A vs B — patterns for monday

| Pattern | Segment A (workspace) | Segment B (AI-native) |
|---------|----------------------|------------------------|
| **Time trial** | Atlassian 14d; ClickUp optional | Cursor 14d Pro trial |
| **Freemium + usage cap** | Notion 20 responses | Claude, ChatGPT, Gemini, Lovable credits |
| **Credit currency** | ClickUp Super Credits, Rovo | Lovable, Copilot Studio |
| **No downgrade** | — | Cursor paid (explicit); ChatGPT may use lighter model on free |
| **Fastest paywall** | Notion ~20 actions | **Lovable ~5 credits/day** |

**monday implication:** Peers in AI-native space **enforce usage early** to drive upgrade. monday’s **non-enforced 6K credits + 14-day-only wall** is an outlier in Segment B and most of A.

---

## Screenshot capture playbook (Segment B)

| File | Product | Trigger |
|------|---------|---------|
| `claude-usage-limit.png` | Claude | Exhaust free usage in one session |
| `chatgpt-rate-limit.png` | ChatGPT | Hit GPT-5.5 limit in 5hr window |
| `cursor-usage-limit.png` | Cursor | Exhaust Hobby API pool or post-trial |
| `lovable-out-of-credits.png` | Lovable | Use 5 daily credits |
| `gemini-limit-prompt.png` | Gemini | Exceed 10 Pro prompts/day |
| `copilot-studio-publish-block.png` | Copilot Studio | Try to publish on trial |

---

## Sources (Segment B)

- Claude: https://support.claude.com/en/articles/11647753 , https://www.anthropic.com/pricing  
- ChatGPT: https://help.openai.com/en/articles/9275245 , https://openai.com/chatgpt/pricing  
- Cursor: https://cursor.com/docs/account/pricing , https://cursor.com/pricing  
- Lovable: https://docs.lovable.dev/introduction/plans-and-credits , https://lovable.dev/pricing  
- Gemini: https://support.google.com/gemini/answer/16275805  
- Copilot Studio: https://learn.microsoft.com/en-us/microsoft-copilot-studio/billing-licensing  

---

## Segment C at a glance (GTM / automation)

| Product | Trial archetype | Primary enforced cap | AI / usage credits? | Enforced in trial? | Time to paywall | Monetization |
|---------|-----------------|----------------------|---------------------|-------------------|-----------------|--------------|
| **Clay** | **T3 hybrid** | **14 days** + **1,000 data credits** | **Data credits** + actions | **Yes** (credits + 50-row table cap) | **Days** (credits or row cap) | Launch from ~$185/mo |
| **relay.app** | **T4 freemium** | **200 workflow steps/mo** + **500 AI credits/mo** | **AI credits** (steps separate) | **Yes** | **Same month** if heavy automation | Pro $19/mo+ |
| **Swan** (getswan.com) | **T1 + T2** | **14-day trial** (reported) + **credit pool** on paid | **GTM credits** | **Yes** on paid; trial credits TBD | **Trial: 14d**; paid: credits mid-cycle | Solo $50/200 cr → custom |
| **Intercom Fin** | **T1 time trial** | **14 days** — **unlimited outcomes** in trial | **Outcomes** ($0.99/resolution paid) | **Soft in trial** (unlimited); hard on paid | **14 days** then outcome billing | $0.99/outcome + seats |

**Swan note:** Competitor = **Swan AI GTM Engineer** ([getswan.com](https://www.getswan.com/)) — not Swan banking. Trial length confirmed via third-party; **trial credit allocation not published** — verify in signup flow.

### Clay

- **14-day trial**, Pro-plan features, **1,000 data credits**, tables capped at **50 rows**
- **Two meters:** actions (platform) vs **data credits** (marketplace enrichment)
- **Enforcement:** credits deplete; row limit blocks scale testing
- **Paywall:** end of 14 days or credit exhaustion → paid Launch/Growth/Enterprise
- Source: [Clay trial FAQ](https://clay.com/faq/what-do-i-get-in-the-free-trial), [Credits guide](https://clay.com/university/guide/credits)

### relay.app

- **No time-based trial** — permanent **Free** tier
- **Free:** 200 workflow steps/mo, **500 AI credits/mo**, 1 user, all core features
- **Enforcement:** hard caps on steps + AI credits; top-ups on annual plans
- **Comparable pattern:** freemium with dual meters (like ClickUp Brain + credits)
- Source: [relay.app pricing](https://www.relay.app/pricing), [Billing docs](https://docs.relay.app/workspace/billing-and-plans)

### Swan (GTM)

- **Credit-based GTM automation** — research, enrich, draft, CRM updates consume credits
- **Paid:** Solo $50/200 credits, Starter $200/1K credits; seats $20/mo for active conversers
- **Rollover** on monthly/annual commitments; top-ups at 150% plan rate
- **Trial:** 14-day free trial cited (third-party); **in-product credit grant during trial unverified**
- Source: [Swan pricing](https://www.getswan.com/pricing)

### Intercom Fin

- **14-day trial**, no credit card; **unlimited Fin outcomes during trial**
- **Paid:** **$0.99 per outcome** (resolved ticket or successful procedure), 50 outcomes/mo minimum
- **Usage alerts/limits** configurable on paid; Copilot $35/user/mo add-on
- **Not PLG workspace trial** — support/CS buyer; trial optimizes for **resolution proof**, not seat exploration
- **Fin Million Dollar Guarantee** — risk reversal for enterprise evals
- Sources: [Fin pricing](https://fin.ai/pricing), [Usage limits](https://fin.ai/help/en/articles/10672156-pricing-and-usage-limits)

**Relevance to monday:** Clay/Swan = **credit + time hybrid** closest to monday’s target model. Fin = **outcome-based** (different unit). relay = **always-free cap** (ruled out for monday primary motion).

---

## Segment D at a glance (data platform — low relevance)

| Product | Trial archetype | Primary cap | Credits? | Enforced? | Time to paywall | Notes |
|---------|-----------------|-------------|----------|-----------|-----------------|-------|
| **Databricks** | **T3 hybrid** | **14 days** workspace credits (DBUs) | **Compute credits** (DBUs) | **Yes** | **14 days** or credit exhaustion | Enterprise/data eng; not PLG seat trial |
| **Snowflake** | **T3 hybrid** | **30 days** OR **$400** free usage | **$ credits** | **Yes** | Whichever first | Warehouse/storage metered |

**Relevance to monday:** Low — validates **time + dollar/credit pool** pattern for technical products, not work-management PLG. Included for completeness only.

- Databricks: [Free trial](https://docs.databricks.com/getting-started/free-trial.html)
- Snowflake: [Trial accounts](https://docs.snowflake.com/en/user-guide/admin-trial-account)

---

# Synthesis — trial options for monday

## Master archetype map (all competitors)

| Archetype | Who uses it | Binding constraint (typical) |
|-----------|-------------|------------------------------|
| **T1 Time-capped** | monday, Atlassian, Cursor (phase 1), Clay (partial), Fin, Databricks | Calendar days |
| **T2 Credit/action-capped** | Notion AI (20 responses), Lovable, Clay credits, Swan | Fixed pool or daily cap |
| **T3 Hybrid (time + usage)** | ClickUp, Clay, Databricks, Snowflake | **Whichever hits first** |
| **T4 Freemium** | Notion workspace, relay, Claude, ChatGPT, Gemini | Ongoing caps, no end date |
| **T5 Consumption-only** | — | Pay-as-you-go (Cursor paid tier) |
| **T6 Card-upfront** | — | Not observed in this set |

## Cross-segment patterns

1. **PLG workspace peers (A):** Split between **time trial** (Atlassian ≈ monday) and **AI-gated freemium** (Notion, ClickUp).
2. **AI-native (B):** **Usage/credits bind before or instead of time** for active users (Lovable same-day, Claude/ChatGPT hours).
3. **GTM automation (C):** **Hybrid time + credits** is standard (Clay 14d + 1K credits; Swan credits on paid).
4. **monday outlier:** Only major PLG peer with **allocated credits that are not enforced** during trial; **day 14 binds** for almost everyone given low burn.

## Trial options for monday (O1–O5)

| Option | Model | Pros | Cons | Closest peers |
|--------|-------|------|------|---------------|
| **O1 — Status quo** | 14d Pro trial, 6K credits, **no enforcement** | No product change; familiar UX | Misaligns with paid **mandatory credits**; no AI urgency; low credit learning | monday today, Atlassian (time only) |
| **O2 — Longer time** | 21–30d trial, same credit grant, still no enforcement | More seat/AI adoption time | Still no credit habit; delays revenue; doesn't fix packaging mismatch | Atlassian Premium 30d |
| **O3 — Hybrid strict** | **14d AND enforce 6K** (or lower trial pool, e.g. 2K); visible credit bar; block AI at 100% | Aligns trial with **paid meter**; creates upgrade moment **before** day 14 for power users | Riskier activation; needs strong onboarding; may need **higher trial grant** if missions added | Clay, ClickUp, Lovable |
| **O4 — Credit-first trial** | Shorter time (7d) or **no time cap** with **fixed credit pool** only | Forces AI value proof early | Freemium-like; **low burn** today means many never hit wall; conflicts with "no endless free" goal | Lovable, Notion AI cap |
| **O5 — Guided AI trial** | O3 + **missions** (e.g. "run 3 AI blocks") + credit visibility + optional **bonus credits** for completion | Drives consumption without arbitrary pain; teaches paid unit | Requires eng + PMM; mission design overhead | Best-of ClickUp onboarding + Lovable credit clarity |

### Recommendation (desk research)

**Lead with O5 (guided hybrid), fallback O3.**

- **Why not O1/O2 alone:** New pricing is **seats + mandatory monthly credits**; trial that never enforces credits **doesn't train the paid contract**.
- **Why not O4 alone:** monday's observed **very low trial burn** means credit-only caps won't bite without **activation design** — pure credit-first recreates freemium without the upside.
- **O5 packages:** Keep **14-day time backstop** (familiar, matches Atlassian) + **enforce a visible credit pool** (suggest **2K–3K** trial allocation aligned to Pro minimum monthly, not 6K one-time) + **2–3 guided AI missions** in first 48h to increase burn intentionally.
- **Measure before ship:** % trialists hitting credit wall vs day 14; AI feature adoption in trial; conversion by path.

## Internal data (BigBrain — Nov 2025 to May 2026)

| Metric | Value | Implication |
|--------|-------|-------------|
| Trial accounts (~14d) | ~2.0M | Large cohort |
| **% any AI in trial** | **16.4%** | **84% never touch AI** — missions target non-users |
| Median credits (AI users) | **16** | vs ~4K avg limit — vast headroom |
| P90 credits (AI users) | **168** | Even power users << 6K one-time grant |
| Blocked for credits | **0** | Confirms no enforcement today |
| At 80% utilization | **16 accounts** | Credit wall is theoretical |
| Binds first | **~100% time (day 14)** | Credits never gate |

**Still useful:** conversion by pay/free/churn; time-to-first-AI-action; AI usage → paid correlation.

## Executive summary (1 page)

**Question:** In a world of **seats + AI credits**, should monday's trial stay **14-day time-only**, add **credit enforcement**, extend time, or use **guided activation**?

**Today:** monday runs a **14-day Pro trial** with **6,000 one-time AI credits** that are **not enforced**. Users almost always hit the **time wall** first because credit usage in trial is very low. That is **unusual** among competitors: Notion, ClickUp, Lovable, Clay, and AI-native tools **enforce AI limits early** to drive upgrade.

**Competitive landscape (17 products, 4 segments):**
- **Segment A (PLG workspace):** Peers split between **14-day trials** (Atlassian) and **AI-gated freemium** (Notion ~20 actions, ClickUp Brain uses + Super Credits).
- **Segment B (AI-native):** **Usage/credits hit in hours or same day** (Lovable hardest at 5 credits/day).
- **Segment C (GTM):** **Hybrid time + credits** (Clay: 14d + 1,000 credits); Fin uses **14d unlimited outcomes** then **per-resolution pricing**.
- **Segment D (data):** **Time + dollar/compute pool** — low relevance to monday PLG.

**Strategic tension:** monday cannot rely on **unenforced credits** if paid plans require **monthly credit purchase**. Freemium without time cap is **ruled out** (low burn + Free plan without AI in new model).

**Recommended direction:** **O5 — Guided hybrid trial** — retain **14-day cap**, **enforce a smaller visible credit pool** aligned to paid tiers, and add **guided AI missions** in week 1 to increase intentional consumption and credit literacy. **Fallback:** O3 (hybrid strict without missions) if mission scope is blocked.

**Data-backed:** BigBrain (Nov 2025–May 2026) — **16.4%** trial AI adoption; **0** credit blocks; P90 burn **168** credits. **Open:** in-product paywall screenshots; Swan trial credit grant; conversion × AI correlation A/B.

---

**Research complete:** Segments A–D desk research · Synthesis O1–O5 · [monday doc](https://monday.monday.com/docs/18413672392)
