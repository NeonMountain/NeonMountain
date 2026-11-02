# Neon Mountain — Meta Ads Launch Plan

**Account:** `NeonMountain_Meta_ads` · ID `1658670216051514` · Business: Neon Mountain (`1094268190011820`) · AUD
**Status:** ACTIVE, MCP-enabled, queryable — **but cannot run yet.**

---

## 0. Blockers — do these first, nothing works without them

| # | Blocker | Who | Where |
|---|---|---|---|
| 1 | **No payment method** on the account | You | Ads Manager → Billing & payments |
| 2 | **No Facebook Page connected** — zero pages returned | You | Business Settings → Pages → Add. Every ad needs a Page identity. |
| 3 | **No pixel / dataset** on this account | You (then me) | Business Settings → Datasets. Install on the Neon Mountain site before spending a cent. |
| 4 | **Lead form ToS not accepted** (if using Instant Forms) | You | facebook.com/legal/leadgen/tos |

Blockers 1 and 2 are absolute — the API refuses campaign creation without them. Ping me when
they're done and I'll build the structure in one pass.

---

## 1. The strategic call: don't advertise the Teardown

**Advertise the free 5-minute teardown video. Not the $2,500 Teardown.**

Three reasons:

1. **$2,500 is not a cold-traffic purchase.** A founder who has never heard of you will not
   buy a diagnostic from a feed ad. The free video is the cold offer; the $2,500 is the warm one.
2. **The video proves competence instead of claiming it.** You're not asking them to believe a
   testimonial — you're showing them three real problems on their own store. Nothing else you
   could put in an ad is as persuasive.
3. **It gives Meta an optimisable event immediately.** A new account with no pixel history has
   to learn from something. Lead submissions at a low cost teach it far faster than a rare
   $2,500 purchase ever could.

The ladder stays intact. It just starts one rung lower:

```
Meta ad  →  free 5-min teardown video  →  call  →  $2,500 Teardown  →  $6,000/mo retainer
```

---

## 2. Targeting: the creative IS the targeting

**The honest constraint:** Meta has removed most reliable B2B and job-title targeting. You
cannot cleanly target "eCommerce business owner" any more. Anyone selling you an interest stack
that does this precisely is guessing.

**So let the creative filter instead.** Write ads only an eCom operator would stop for, and let
everyone else scroll past. Specificity is free qualification.

Use the vocabulary as a filter:
- "If you can't say what your blended MER was last month, this is for you."
- "Your Klaviyo flows haven't been touched since launch, have they."
- "Your reported ROAS and your bank account disagree. Here's why."

A consumer has no idea what any of that means and will not click. That is the point.

### Ad set structure — two to start, no more

**Ad Set A — Broad**
- Location: Australia + New Zealand
- Age 25–55, all genders
- No detailed targeting. Advantage+ audience on.
- Rationale: with good filtering creative, broad usually beats a narrow stack, and it gives
  Meta room to find the pocket.

**Ad Set B — Interest stack (the control)**
- Same geo and age
- Interests: Shopify · Klaviyo · WooCommerce · BigCommerce · Meta Business Suite ·
  E-commerce · Digital marketing
- Behaviours: Small business owners · Facebook Page admins
- Rationale: narrower, likely more expensive per lead, but a useful control. Kill it if it
  loses after two weeks.

**Do not build more than two ad sets.** At a starting budget you will starve them of data.

### Later: retargeting (week 3+, not now)
Once there's video-view and site data, this is where B2B Meta actually earns its keep:
- Video viewers 50%+ (365 days)
- Page and IG engagers (365 days)
- Site visitors 180 days
You cannot build these yet — there's no pixel data. Don't try.

---

## 3. Creative — six concepts, in priority order

Your advantage here is that you're an art director who can make these cheaply and fast. This is
the one part of the plan where you massively out-execute other agencies.

### 1. The screen-record teardown ⭐ highest priority
30–45 seconds. You, scrolling a real store (anonymised or permissioned), calling out three
things you'd fix. No intro, no logo, hook in the first 1.5 seconds.
> *"This store is doing about $300k a month and it's leaking in three places. Here's the first one."*

Make five of these. They are your best asset and the cheapest to produce.

### 2. "Attributed to nothing"
> *"I audited a $3.4M store last month. 59% of its revenue — over a million dollars — was
> attributed to nothing at all. The owner had no idea. Here's how that happens."*

### 3. "20 people"
> *"This brand's website retargeting audience had 20 people in it. They'd been running ads to
> it for months. The pixel had been broken the whole time."*

### 4. "Their best campaign was switched off"
> *"Best performing campaign in the account: 15.7x return. It was paused. Nobody noticed for
> five weeks."*

### 5. The five questions
> *"If you can't answer these five questions about your store, you're flying blind:"*
> blended MER · repeat purchase rate · contribution margin per order · new-customer CAC ·
> what % of revenue is email

### 6. Multi-brand proof — **needs your input**
> *"I've done this across [X] brands — fashion, [category], [category]. Same three problems
> every time."*

**Open question for you:** concepts 2–4 all come from one audit. Name three or four other brands
you've worked with and one concrete outcome each, and I'll write proof creative that spreads the
story across them. Right now I only have verifiable numbers from one, and I won't invent the rest.

---

## 4. Campaign build spec — ready to execute

**Campaign**
- Name: `NM | Leads | Teardown Video | AU-NZ`
- Objective: `OUTCOME_LEADS`
- Budget: campaign-level (CBO), **AU$40/day** to start
- Status: **PAUSED on creation** — nothing spends until you approve

**Ad sets** (two, as above)
- Optimisation: Lead generation
- Conversion location: **Instant Form** (keeps them in-platform; higher convert rate, no landing
  page dependency while the site is new)
- Placements: Advantage+ placements on

**Instant Form — qualifying questions**
Make it slightly harder than it needs to be. You want fewer, better leads.
1. Store URL *(required)*
2. Monthly revenue — `Under $50k` / `$50k–250k` / `$250k–1M` / `$1M+`
3. Monthly ad spend — `Under $10k` / `$10–30k` / `$30k+`
4. Platform — `Shopify` / `Shopify Plus` / `Other`
5. **"What's the single biggest thing holding your growth back right now?"** *(open text)*

Question 5 is the most valuable field in the whole funnel. It's your sales call opener,
in their words.

**Follow-up SLA:** record and send the teardown video within 48 hours of the lead landing.
Past that, the lead is cold and the spend is wasted.

---

## 5. Budget and the break-even maths

Minimum daily budget on this account is AU$1.45. Ignore that — it's a floor, not a plan.

| | |
|---|---|
| Starting budget | **AU$40/day** (~$1,200/month) |
| Minimum honest test | **4 weeks, ~$1,200** |
| Don't judge it before | 50 leads or 2 weeks, whichever is later |

**The break-even frame — fill in with your own numbers, don't trust anyone's benchmarks:**

> One Teardown sold = $2,500. So you can spend up to $2,500 acquiring one Teardown client and
> break even *on the first transaction alone* — before any retainer. Once a Teardown converts
> to a $6,000/month retainer, the acceptable number goes up a long way.

Work backwards once you have real data:
`cost per lead × leads per call × calls per Teardown = your true cost per client`

**I'm not giving you expected CPLs or conversion rates.** I don't have reliable benchmarks for
B2B agency lead gen in AU, and inventing them would make your model worse, not better.
Run 4 weeks, measure your own, then set targets.

---

## 6. What to watch, and when to kill

| Week | Check | Action if bad |
|---|---|---|
| 1 | Is it delivering? Impressions > 0, leads > 0 | If zero spend: check payment, page, approval status |
| 2 | Lead quality — are they real eCom brands at your revenue band? | If junk: tighten the form, not the targeting |
| 3 | Cost per lead, A vs B | Kill the loser ad set. Keep one. |
| 4 | Cost per booked call | If no calls from 50 leads, the problem is follow-up, not ads |
| 6 | Cost per Teardown sold | This is the only number that matters. Judge the channel on it. |

**Hard rule:** do not add budget before week 4, and do not add campaigns while one is still
learning. The classic way to burn $1,200 and learn nothing is to keep changing things.

---

## 7. Honest assessment of this channel

Worth saying plainly, since you're about to spend money:

- **Meta is not the fastest path to your first client — your network is.** The start plan's
  Week 3–6 move (ten free teardown videos to people you already know) will almost certainly
  produce a paying client before these ads do, at zero cost.
- **Run both.** Ads build a pixel, an audience and a creative library that compound. The network
  gets you cash now. They aren't in competition.
- **But don't let ads become the reason you didn't call twenty people.** Building campaigns feels
  like progress. Ten calls to warm contacts *is* progress.
- **Your genuine edge here is creative,** not media buying. Most agencies advertising to eCom
  founders run ugly talking-head ads. You can make five good screen-record teardowns in a day.
  That's the asymmetry — lean on it.

---

## Open items I need from you

- [ ] Payment method added
- [ ] Facebook Page created/connected
- [ ] Pixel installed on the Neon Mountain site
- [ ] **Three or four other brands you've worked with + one concrete outcome each** — so proof
      creative isn't all one story
- [ ] Confirm AU + NZ is the right geo, or whether you want US/UK too
- [ ] Confirm AU$40/day is comfortable
