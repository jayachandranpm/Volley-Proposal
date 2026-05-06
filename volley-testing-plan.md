# Volley · 1-Page Testing Plan

**Goal:** Find the lowest **Cost Per Trial Start (CPT)** in 21 days, then scale the winner without breaking ROAS.
**Budget:** $4,500 over 3 weeks ($150/day baseline, scaled to $300/day in Phase 3).
**Conversion event:** `StartTrial` (placement quiz completed email captured trial activated).

---

## Phase Sequence

| Phase | Days | Test | Structure | Daily Spend |
|---|---|---|---|---|
| **1 · Angle Test** | 1–7 | Which psychological hook wins? | 1 CBO campaign · 3 ad sets (1 per angle) · 2 creatives each | $150 |
| **2 · Format Test** | 8–14 | What format amplifies the winning angle? | Winning angle only · UGC video vs. motion graphic vs. static carousel | $200 |
| **3 · Scale & Funnel** | 15–21 | Can we cut CPT 30%+ at higher spend? | Duplicate winner into ABO at 2× budget · A/B test landing page (chatbot vs. static form) | $300 |

**Audience strategy:** Broad targeting (US, 25–55, English speakers). No interest stacking — let Meta's algo find the pocket. Lookalikes only enter Phase 3 if Phase 1+2 produce 50+ conversions.

---

## Metrics That Matter (in priority order)

| Tier | Metric | Why it matters | Healthy threshold |
|---|---|---|---|
| **Primary** | **CPT (Cost Per Trial)** | The only metric that pays the bills | ≤ $35 |
| **Primary** | **Trial Paid conversion** (Day 14) | Catches "cheap but junk" traffic | ≥ 22% |
| **Diagnostic** | **Hook rate** (3-sec views ÷ impressions) | Did the creative stop the scroll? | ≥ 25% |
| **Diagnostic** | **Hold rate** (15-sec views ÷ 3-sec views) | Did the message land? | ≥ 50% |
| **Diagnostic** | **CTR (link)** | Curiosity click | ≥ 1.8% |
| **Funnel** | **LP Quiz start** | Is the landing hero working? | ≥ 45% |
| **Funnel** | **Quiz Email submit** | Is the chatbot converting attention? | ≥ 60% |

I read these in pairs:
- **High CTR + low LPQuiz** = ad over-promised, LP is broken
- **High hook + low hold** = thumb-stopping but no story
- **Low CPT + low TrialPaid** = wrong audience, not wrong creative

---

## Kill Rules (the unsexy part)

I'd rather kill fast than nurture losers. Hard rules:

| Signal | Day | Action |
|---|---|---|
| Hook rate < 15% | Day 3 | **Kill creative.** It's not the targeting, it's the thumbnail. |
| CTR < 0.8% | Day 4 | **Kill creative.** No curiosity gap. |
| CPT > $60 with 1,000+ impressions | Day 5 | **Kill ad set.** Audience/creative mismatch. |
| TrialPaid < 12% after 25 trials | Day 10 | **Kill ad set even if CPT is good.** This is the dangerous one — cheap junk traffic burns retention. |
| Frequency > 3.5 in week 1 | Any day | **Refresh creative.** Audience is being pounded. |

**What I'd kill first if Week 1 came in soft:**
1. **Angle 2 (Busy Professional)** — it's the safest hook. If it doesn't outperform, the audience was wrong, not the message. Kill it and shift budget into the App Dropout angle (highest emotional charge).
2. **The static formats** before the video formats. Static almost always loses on cold traffic in language learning.
3. **Any creative under 15% hook rate by Day 3**, no exceptions. There's no rescuing a thumbnail miss with budget.

---

## What Success Looks Like (Day 21 Decision Tree)

- **CPT ≤ $30 and TrialPaid ≥ 25%** Scale 3× into ABO with lookalikes; build 2 new variants of winner.
- **CPT $30–$50 and TrialPaid ≥ 22%** Stay flat, iterate landing page, test discount offer in ad copy.
- **CPT > $50 OR TrialPaid < 18%** Pause paid. Audit the post-trial onboarding. Paid won't fix retention.

---

## What I'm Actually Optimizing For

Not CPT. Not even ROAS.
**LTV÷CAC at Day 90.** A $25 trial that churns in 30 days is more expensive than a $45 trial that pays for 6 months. Every kill rule above is designed to filter out the cheap-but-bad traffic that looks great in Ads Manager and bankrupts the company at month-end.
