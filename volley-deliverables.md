# Volley · Growth Audit Deliverables

**Submitted by:** [Your Name]
**Date:** May 2026
**Brief:** Diagnose Volley's funnel, propose a landing page variant, design 3 Meta ad angles, and lay out a testing plan that shows how I'd run, read, and kill.

---

## TL;DR

Volley's product is genuinely differentiated (AI practice + human accountability), but the current funnel buries the proof. I rebuilt three deliverables to test one core hypothesis:

> **People don't churn from language apps because the apps are bad. They churn because they're alone. Volley's wedge is accountability — and we're under-selling it.**

Everything below tests some version of that thesis.

---

## 📦 Deliverable 1 — Landing Page Variant

**File:** [`lingoflex-landing.html`](./lingoflex-landing.html) (production-ready, single-file build)

### What I changed

| Change | Why |
|---|---|
| **Glassmorphism sticky header** with intent-led nav (How It Works · Languages · Tutors · FAQ) | Removed dead "Pricing" and "Cart" links that pointed nowhere. Every nav item now lands where it promises. |
| **"Get my plan" → Intercom-style chatbot** instead of static form | Form-fills feel like commitment. A conversation feels like help. The chatbot collects 6 signals (language · level · goal · time · style · timeline) and ends with a personalized plan card *inside the chat itself*. |
| **31-language searchable dropdown** in step 1 | The previous "Spanish / French / German / Other" list told visitors that Volley is small. The full picker is a credibility signal in itself. |
| **Tutor section gets nav anchor + pulled higher** | Human tutors are Volley's actual moat vs. Duolingo. Surface them. |
| **Removed all hover-bounce animations on quiz** | Felt like a kids' game. We're charging $149/mo to adults. |

### The hypothesis I'm testing
**H1:** Replacing the static onboarding quiz with a conversational chatbot will lift LP→Trial conversion by ≥ 25%, because (a) the perceived effort drops, (b) the recommendation feels personalized rather than templated, and (c) the conversation itself demonstrates the product (Volley = a chat-based tutor).

### How I'd measure it
50/50 split test, 2 weeks, primary metric **LP → Trial Start**. Significance threshold: 95% with ≥ 800 visitors per arm.

---

## 📦 Deliverable 2 — Three Meta Ad Angles

**Files:** [`volley-meta-ads-strategy.md`](./volley-meta-ads-strategy.md) · [`volley-meta-ads-mockups.html`](./volley-meta-ads-mockups.html) (visual mockups)

I picked three angles that hit *deliberately different* psychologies. The point isn't to find which ad I like — it's to give the algo three honest swings at three different audiences, then let the data crown a winner.

### Angle 1 · "The App Dropout" 🔥
**Audience:** Serial language-app churners (Duolingo, Babbel quitters)
**Hook:** *"~~300-day streak.~~ Still can't order a coffee."*
**Format:** UGC POV / TikTok-native
**Promise:** Accountability instead of dopamine
**Why it could win:** Highest emotional charge. Names the pain everyone feels but no one says.
**Why it could lose:** Negativity-led ads sometimes attract bargain hunters who churn.

### Angle 2 · "The Busy Professional" 💼
**Audience:** Income-rich, time-poor, 30–45
**Hook:** *"Fluent French. Zero free time."*
**Format:** Sleek motion graphic with VS comparison (Old way: 2hr classroom · Volley: 15 min + 1 call/wk)
**Promise:** ROI of time
**Why it could win:** Clearest value proposition. High-LTV audience.
**Why it could lose:** Boring. Easy to scroll past if hook isn't strong enough.

### Angle 3 · "The Real-World Prep" ☕
**Audience:** Travelers, expats, intermediate learners
**Hook:** *"Practice the **exact** chat. Before you ever say it out loud."*
**Format:** B-roll of a Parisian café with chat UI overlay
**Promise:** Hyper-specific, situational practice
**Why it could win:** The most concrete demonstration of the product.
**Why it could lose:** Niche use-case. Could narrow the audience too far.

All three creatives are mocked up at full fidelity in [`volley-meta-ads-mockups.html`](./volley-meta-ads-mockups.html) with:
- Bold, dominant hook typography (≤ 7 words)
- Minimal body copy (one line)
- Lucide icons (no emoji)
- Dark presentation backdrop so the cards pop
- Real CTA chips with social proof (★★★★★ 4.9 · 12,000 learners)

---

## 📦 Deliverable 3 — 1-Page Testing Plan

**File:** [`volley-testing-plan.md`](./volley-testing-plan.md)

The plan covers:
- **Phase sequencing** (Angle Test → Format Test → Scale & Funnel) over 21 days, $4,500 budget
- **Metric hierarchy**: CPT and Trial→Paid are primary; hook rate, hold rate, CTR are diagnostic
- **Hard kill rules** with day-level triggers (hook rate < 15% by Day 3 → dead, regardless of CTR)
- **Decision tree for Day 21** — three explicit branches based on CPT and Trial→Paid bands
- **What I'd kill first if Week 1 is soft**: Angle 2, then static formats, then any creative under a 15% hook rate

The piece I want to be judged on is the **kill discipline section**. Most paid teams nurture losers because they're emotionally invested. The job is to be ruthless.

---

## What I'm Actually Optimizing For

> Not CPT. Not even ROAS. **LTV ÷ CAC at Day 90.**

A $25 trial that churns in 30 days is more expensive than a $45 trial that pays for 6 months. Every kill rule, every metric tier, every audience choice in this plan is designed to filter out the cheap-but-bad traffic that looks great in Ads Manager and bankrupts the company at month-end.

That's also why the landing page changes lean into demonstration (the chatbot *is* the product) over promotion. We want trials from people who get what Volley is — not from people who clicked a clever hook and bounced when reality showed up.

---

## File Index

| File | What it is |
|---|---|
| [`lingoflex-landing.html`](./lingoflex-landing.html) | Production-ready landing page variant (single file, no build) |
| [`volley-meta-ads-strategy.md`](./volley-meta-ads-strategy.md) | Written angles + creative direction + Midjourney prompts |
| [`volley-meta-ads-mockups.html`](./volley-meta-ads-mockups.html) | High-fidelity HTML mockups of all 3 ads |
| [`volley-testing-plan.md`](./volley-testing-plan.md) | 1-page testing plan with phases, metrics, and kill rules |
| [`volley-deliverables.md`](./volley-deliverables.md) | This document |

---

*Open the HTML files directly in any modern browser — no install required.*
