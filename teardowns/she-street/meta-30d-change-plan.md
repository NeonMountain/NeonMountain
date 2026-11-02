# SHE STREET — Meta 30-Day Review & Staged Change Plan

**Account:** SHE STREET ADaccount · `10153703568144823` · AUD
**Window:** last 30 days (to 14 Sep 2026) · **Status: NOTHING EXECUTED — awaiting approval**

| | |
|---|---|
| Spend | **$36,462.89** |
| Attributed revenue | **~$220,010** |
| Blended ROAS | **6.03** |
| Campaigns with spend | 7 of 61 |

---

## STOP — read this before approving anything

**Your website/pixel custom audiences are empty.** Every website-based audience in the account
reports a size of 20 — Meta's minimum display floor, which in practice means zero:

| Audience | Size |
|---|---|
| 001 – Website – All Website Visits – 180 Days | 20 |
| 008 – Website – All Website Visits – 30 Days | 20 |
| SS26 — Website Visitors 30d | 20 |
| SS26 — Add To Cart 30d | 20 |
| SS26 — Purchasers 180d | 20 |
| 015 – Website – Purchase – 180 Days | 20 |
| 016 – Website – AddToCart – 180 Days | 20 |
| All Purchasers 180 / All Web Visitors 180 / 730 Days Purchasers Web | 20 each |

Meanwhile every **social engagement** audience is populated normally — Instagram Engagement
365d at 80,300–94,400, Facebook Engagement 30d at 52,600–61,900.

A store doing ~1.3M sessions a year cannot have 20 website visitors. **The pixel / CAPI
feed into these audiences is broken.** This is the same root cause as Leak 01 in the
Growth Teardown, seen from the other side.

### Three consequences that change everything below

1. **You are not retargeting site visitors.** Your "Retargeting" is running on IG/FB engagers
   only. That's why reach is tiny (16k–37k) and frequency is 4.0–6.4 — it's hammering a small
   social pool repeatedly.
2. **Your exclusions do nothing.** Excluding "Purchasers 180d" excludes 20 people. Every
   prospecting campaign is currently also serving to existing customers. **That is where your
   audiences overlap** — not between campaigns, but between prospecting and your own buyers.
3. **One active lookalike is built on a dead seed.** `Lookalike (1%) - 008 - Website - All
   Website Visits - 30 Days` is seeded from a 20-person audience. It is not a meaningful
   lookalike.

> **Recommendation: fix the pixel before scaling anything.** Scaling retargeting into a broken
> audience layer buys saturation, not growth.

---

## 1. PAUSE — the losers

All three sit in the **Prospecting** campaign (`52560335329505`), which is already paused at
campaign level. **But the ad sets themselves are still set to ACTIVE.** If anyone un-pauses
that campaign, all three relaunch instantly against an $800/day budget.

| Ad set | ID | Spend | Revenue | ROAS | CPA |
|---|---|---|---|---|---|
| 0826D2 | `52579588497305` | $3,948.86 | $6,725.07 | **1.70** | $84.02 |
| 0826D1 | `52574971666105` | $2,869.77 | $6,111.28 | **2.13** | $59.79 |
| 0726D2 | `52560335329705` | $1,895.93 | $2,154.84 | **1.14** | $70.22 |
| **Total** | | **$8,714.56** | **$14,991.19** | **1.72** | |

For comparison, your best ad sets are converting at **$6.75–$9.80** per purchase. These are
paying 6–12× that.

**Proposed action:** set all three to PAUSED at ad set level. This stops no current spend —
it defuses the landmine.

---

## 2. SCALE — the winner you switched off

The entire **Retargeting** campaign (`52560360967505`) is paused. In the window it did:

| Ad set | ID | Spend | Revenue | ROAS | CPA |
|---|---|---|---|---|---|
| 0726D3 | `52566276795705` | $1,418.02 | $24,830.27 | **17.51** | $7.92 |
| 0726D2 | `52560360967705` | $1,087.59 | $13,421.75 | **12.34** | $9.80 |
| 0826D1 | `52574974097705` | $269.81 | $5,089.88 | **18.86** | $6.75 |
| AfterPay Sale_26 | `52575190419105` | $145.44 | $2,629.73 | **18.08** | $7.27 |
| **Total** | | **$2,920.86** | **$45,971.63** | **15.74** | |

**$2,921 of spend returned $45,972, and it is currently off.**

**Proposed action — staged, not live:** restore at the *original* budget only, not scaled.
These ad sets already run at frequency 3.8–4.0 against audiences of 8k–24k. Doubling budget
without fixing the pixel will push frequency past 8 within a fortnight and the ROAS will fall.

The order that actually works: fix pixel → rebuild website audiences → *then* scale.

---

## 3. KEEP — with a watch on fatigue

| Ad set | ID | Spend | ROAS | CPA | Frequency | Note |
|---|---|---|---|---|---|---|
| Main_Products | `52581074721505` | $20,776.80 | 6.24 | $22.56 | 5.68 | 921 purchases. The workhorse. |
| Sale - Retargeting | `6872836182501` | $3,088.56 | 7.89 | $15.29 | **6.41** | Only 36,793 reach. Saturating. |

`Sale - Retargeting` is your most efficient live ad set *and* your most fatigued. At frequency
6.41 on a 37k pool it has roughly 2–4 weeks of headroom before performance decays. New creative
is the fix, not more budget.

---

## 4. Account hygiene — the reason this is hard to manage

- **61 campaigns, 7 with spend.** The rest are dead history cluttering every view.
- **Duplicate ad set names across campaigns.** `0826D1` is both a 2.13 ROAS loser
  (`52574971666105`) and an 18.86 ROAS winner (`52574974097705`). `0726D2` is both a 1.14 loser
  and a 12.34 winner. **You cannot manage this account by name — only by ID.** That alone will
  cause someone to scale the wrong thing.
- **~15 INACTIVE lookalikes**, several dating to Nov 2024.
- **Three campaigns explicitly named "No Exclusions"** (`#6`, `#7`, `#8`) — which, given the
  empty purchaser audiences, is academic: nothing is excluded anywhere.
- **Three other SHE STREET ad accounts are DISABLED** — "flagged because of unusual activity,
  all ads paused." Worth confirming these are legacy and not something needing appeal.

---

## Approval list

Nothing below has been executed.

| # | Action | Entity | ID | Moves money? |
|---|---|---|---|---|
| 1 | Pause ad set | 0826D2 (Prospecting) | `52579588497305` | No |
| 2 | Pause ad set | 0826D1 (Prospecting) | `52574971666105` | No |
| 3 | Pause ad set | 0726D2 (Prospecting) | `52560335329705` | No |
| 4 | Reactivate at original budget | Retargeting campaign | `52560360967505` | **Yes** |
| 5 | Leave untouched | Main_Products | `52581074721505` | — |
| 6 | Leave untouched, brief new creative | Sale - Retargeting | `6872836182501` | — |

**Recommended sequence:** approve 1–3 now (protective, no spend). Hold 4 until the pixel is
fixed and website audiences repopulate — otherwise you are scaling into an audience layer that
cannot support it.

---

## Limits of this analysis

- **Audience overlap is inferred, not measured.** I have audience sizes, reach and frequency,
  plus campaign naming. I do not have Meta's Audience Overlap tool here. The overlap claim
  (prospecting serving to existing customers) follows from the purchaser-exclusion audiences
  being empty, which is solid — but the precise degree is unmeasured.
- **ROAS is Meta-attributed**, and per the Growth Teardown, Meta attribution at SHE STREET does
  not reconcile to Shopify. Blended 6.03 ROAS on $36k spend implies ~$220k of the month's
  revenue came from Meta; Shopify's own numbers attribute far less. Treat these as relative
  rankings between ad sets, not absolute truth.
- **No COGS**, so none of this is contribution margin.
- Campaign membership for ad sets was inferred by matching spend totals exactly; it reconciles
  to the cent, but it is inference.
