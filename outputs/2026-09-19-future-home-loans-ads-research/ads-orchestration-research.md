# Future Home Loans — Two Google Ads Accounts: Overlap & Orchestration Research

**Prepared:** 2026-09-19
**Client:** Future Home Loans · future.loans · Future Financial LLC, NMLS #1621953 · Jacksonville Beach, FL
**Context:** A second Google Ads account has been spun up for Future Home Loans that Digital Optimus has **no visibility into**. This brief researches the situation, quantifies the actual overlap/cannibalization risk from the data we *can* see, and lays out how to get visibility and re-establish a single coordinated acquisition strategy.
**Evidence sources:** SE Ranking US database, Sep 2026 snapshot (domain overview, organic + paid keyword footprint, paid-competitor and ads-by-keyword lookups for `future.loans`); the client product-marketing context (`outputs/2026-09-18-future-home-loans-product-marketing/product-marketing.md`); Google Ads platform documentation.

> **What we could and could not observe.** SE Ranking returned a rich **organic** footprint for future.loans but **zero paid records** — no ads-by-domain, no paid keywords, no paid competitors. Third-party ad databases under-sample local, geo-fenced, and recently-launched search campaigns, so this is expected and does **not** mean no ads are running. **The bottom line: no third-party tool can see into the second account. Nothing in this brief reports what either Google Ads account is actually doing — it reports the organic reality both accounts are bidding *against*, the mechanics of the risk, and the exact steps to make the invisible account visible.**

---

## Executive summary

The client's instinct is right, and it splits cleanly into two problems.

1. **Tactical (overlap).** Two accounts can independently target the same searches, geographies, audiences, landing pages, and conversion events. Left uncoordinated this produces duplicated auction coverage, self-competition that inflates CPCs, muddled attribution, and — most expensively — **paid capture of traffic Future already earns for free**. This risk is not hypothetical: brand and Jacksonville-geo terms are exactly where future.loans' organic is strongest.

2. **Strategic (orchestration).** The bigger issue. There is no longer one acquisition strategy. SEO, our paid, their paid, landing pages, conversion tracking, CRM follow-up, and budget are each optimizing their own local number instead of the business outcome — **incremental funded-loan value**. A second campaign can post a great-looking CPL while creating nothing incremental, simply by re-routing leads that would have arrived organically or through the existing account.

**The data sharpens the argument.** Future.loans' organic footprint is concentrated in **brand** and **Jacksonville mortgage-broker/geo** terms, where it already ranks **#1** — the brand term alone is ~12% of all organic traffic. Its **VA-intent** terms — the client's stated growth goal — rank on **page 3–8** and capture almost no organic traffic. That gives a precise, defensible map of where paid should stay lean, where it should dominate, and where two uncoordinated accounts will collide.

**Recommendation:** Reframe the client conversation from "who controls Google Ads" to "who owns acquisition orchestration." Get both accounts analyzed together, establish one acquisition plan, one measurement framework, and clear ownership of audiences / keywords / products / geographies — then prove incrementality before scaling either account. That is a higher-value role than campaign management and it strengthens, not weakens, Digital Optimus' position.

---

## 1. The situation

- Two Google Ads accounts now run acquisition for one brand, one website, and (presumably) one CRM.
- Digital Optimus manages one and has **no read access** to the other — no keywords, geo, budgets, bidding, conversion actions, or search terms.
- Without shared visibility, coordination is impossible: the two accounts can enter the **same auctions**, and Google will let a single advertiser's own campaigns compete against each other, paying more to occupy space it might have won cheaply (or earned organically).

**Why "just add the 20% management argument" is the wrong frame.** Arguing for control because of the management fee is a low-value, self-interested position. Arguing that *someone must own orchestration across SEO + all paid + landing pages + lead follow-up + budget, against one goal* is a high-value, client-interested position — and it happens to be the correct one.

---

## 2. What the data shows (the organic reality both accounts bid against)

SE Ranking, US database, Sep 2026. Organic overview for future.loans: **2,176 ranking keywords, ~1,085 est. monthly organic visits, 210 keywords in positions 1–5.** Estimates, not GA/GSC truth — directionally reliable, confirm against the client's own Search Console before quoting externally.

### 2a. Brand + Jacksonville geo — organic already owns #1 (paid here is mostly re-buying earned traffic)

| Keyword | Volume/mo | Organic pos | CPC | Est. organic visits/mo |
|---|---|---|---|---|
| future home loans (brand) | 390 | **1** | $0.99 | **131 (~12% of all organic traffic)** |
| future loans / future loan (brand) | 70 | **1–2** | $5.60 | ~29 |
| future home loans jacksonville (brand) | 50 | **1** | $1.50 | 13 |
| mortgage brokers jacksonville fl | 320 | **1–2** (local pack) | $7.54 | ~34 across variants |
| mortgage companies jacksonville fl | 320 | **1–2** (local pack) | $6.21 | ~20 |
| jacksonville mortgage loans / mortgage loan jacksonville | 210 | **1–2** (local pack) | $6.77 | ~17 |
| home loans orlando fl | 260 | **1** (local pack) | $5.19 | 4 |

**Implication.** These are the highest-CPC, highest-intent local terms ($5–$7.54/click) — and Future already sits in the local pack / organic #1 for them. Paid dollars spent here largely **cannibalize free clicks**. This is the precise use case for Google's **brand-exclusion / brand restriction** controls and tight negative-keyword hygiene. *Caveat:* a small, deliberate defensive brand budget can be justified **if** a competitor — or the second account itself — is bidding on Future's brand; that is a decision to make on purpose, with data, not to discover by accident across two accounts.

### 2b. VA-intent — organic is weak; this is paid's clean lane (and the client's growth goal)

| Keyword | Volume/mo | Organic pos | CPC | Est. organic visits/mo |
|---|---|---|---|---|
| current va mortgage rates | 20,100 | 56 | $2.00 | 0 |
| va loan rates | 20,100 | 48 | $2.57 | 0 |
| va mortgage rates | 19,100 | **24** | $2.30 | 135 |
| va mortgage rates today | 12,100 | 52 | $2.34 | 0 |
| va loan interest rate(s) | 5,400–8,000 | 58–73 | $2.44 | 0 |
| current va home loan rates | 4,400 | 31 | $2.00 | 0 |
| military mortgage rates / military home loan rates | 590 | 34–71 | $2.84 | 0 |

**Implication.** Future ranks for very high-volume VA queries but almost entirely on **page 3–8**, capturing near-zero organic traffic — and the terms it does touch are informational **rate-shopping** queries on `/mortgage-rates/`, not the transactional VA-purchase intent (e.g. "va loan florida," "va loan lender," "$0 down va loan") the growth push needs. **VA is exactly where SEO cannot carry the load in the near term, so paid should dominate here** — cleanly, without fighting organic for the same click. This is the highest-value, lowest-cannibalization lane for *coordinated* paid spend. It is also the lane where two uncoordinated accounts are most likely to collide, because both will be told "grow VA in Florida."

### 2c. Generic head terms — invisible organically, expensive in paid

"mortgage broker" (74,000/mo, $7.55 CPC) ranks position 45–78; broad broker/advisor terms across GA/TX/FL location pages sit on page 3+. High cost, low intent, easy to waste budget on — and a likely spot for two accounts to both "test broad" and double-spend.

### 2d. Paid footprint — not observable from here

Ads-by-domain, paid keywords, and paid competitors for future.loans all returned **empty** in SE Ranking; brand and "va loan florida" ads-by-keyword lookups returned no captured advertisers. Treat this as **"not visible to this tool,"** not "not running." The only authoritative sources for the second account's paid activity are Google's own surfaces (Section 4).

---

## 3. The overlap risk, made concrete

Where two uncoordinated accounts hurt Future, worst-first:

1. **Cannibalizing free traffic.** Paid bids on brand + Jacksonville-geo terms (§2a) buy clicks Future already wins organically at #1. Every such click is close to pure waste plus the click cost.
2. **Self-competition in the auction.** Two accounts on overlapping VA + Florida keywords (§2b) can raise each other's CPCs and split impression share — the advertiser bidding against itself.
3. **Attribution fog.** Two accounts → two conversion-tracking setups → the same lead double-counted or mis-credited; neither account's CPL/ROAS can be trusted, and blended performance is unknowable.
4. **Inconsistent bidding & budget.** One account on tCPA, the other on Maximize Conversions, chasing different (or duplicate) conversion actions, allocates the brand's budget by neither logic.
5. **Message/landing-page fragmentation.** Divergent creative and landing pages against one brand — and, for a mortgage broker, divergent **compliance** posture (NMLS ID, Equal Housing, "$0 down"→"most VA purchase loans," "no lender fees"+"third-party costs apply," Housing Special Ad Category, no unqualified competitor claims). Two accounts double the surface area for a compliance miss.

**The trap the client already named:** the second account can report a $35 CPL vs. our $40 and *look* better while creating nothing incremental — it simply captured leads that would have arrived organically or through the existing account. **Local metrics can look good while the global outcome is flat or worse.** Only an incrementality view (Section 6) can tell the difference.

---

## 4. Getting visibility into the invisible account (concrete, do-this-week)

Ordered by how fast they yield signal and how little they depend on the other party's cooperation:

1. **Google Ads Transparency Center** — `adstransparency.google.com`, search advertiser "Future Home Loans" / domain `future.loans`, region US. Shows *creatives currently running* by any account promoting the brand, regardless of who owns it. Fastest independent read on what the second account is actually showing. (Shows ads, not keywords/spend.)
2. **Auction Insights** (in the account we manage) — reveals domains competing in our auctions and impression-share overlap. If the second account competes with ours, it can surface here as self-competition.
3. **Ask for read access / MCC linking.** The clean fix: link both accounts under one **Manager (MCC)** account, or at minimum get read-only access to the second. This is the ask that makes orchestration real; frame it as required for measurement, not for control.
4. **Search-terms + brand-traffic diagnostic** on our account — a spend spike or CPC inflation on **brand terms** is the fingerprint of a second account bidding brand. Cross-check GA4/GSC: paid clicks on queries where organic sits #1 quantify the cannibalization in §2a.
5. **One conversion source of truth.** Confirm which conversion actions each account fires and whether both hit the same GTM/GA4/CRM pipeline. Until conversions are de-duplicated, no CPL comparison between accounts is valid.
6. **Google Ads API / GAQL pull** — once access exists, pull both accounts' campaigns, keywords, geo, budgets, bidding, and conversion actions into one overlap matrix (Section 5). The `ad-optimus` repo's Google Ads MCP layer is the place to wire this up.

> Compliance note: pull and analyze account structure and performance only. Do not export or store borrower PII from either account or the CRM.

---

## 5. Overlap audit — the matrix to build once both accounts are visible

For every dimension, map Account A (ours) vs. Account B (theirs) and flag collisions:

| Dimension | What to compare | Collision flag |
|---|---|---|
| Keywords | Exact/phrase/broad lists, match types | Same keyword in both accounts (esp. VA + FL, brand) |
| Brand terms | Is either bidding on "future home loans" & variants? | Any brand bidding without a deliberate defensive rationale |
| Geography | Targeted locations + presence vs. presence-or-interest | Overlapping geos (esp. Duval/Clay/St. Johns, FL) |
| Audiences | In-market, affinity, remarketing, customer match | Same audiences targeted (not just observed) in both |
| Landing pages | Destination URLs per campaign | Different LPs for the same intent; non-VA LPs for VA terms |
| Conversion actions | What each counts as a conversion; primary vs. secondary | Duplicate/undeduplicated conversions; different definitions |
| Bidding | Strategy + targets per campaign | Conflicting strategies chasing the same conversions |
| Budget | Daily budget + pacing per account | Combined spend on cannibalizing/duplicated terms |
| Negatives & brand exclusions | Shared negative lists; brand-restriction settings | Missing brand exclusions; no cross-account negative hygiene |
| Compliance | NMLS/EHL present; claim discipline; Housing SAC | Any missing disclosure or unqualified claim in either account |

Deliverable from this matrix: a de-duplicated, single acquisition plan with **one owner per keyword/product/geo lane**, so no two campaigns (in either account) chase the same query.

---

## 6. The operating model — one goal, SEO and paid as levers under it

Reassert a single objective hierarchy so every channel optimizes the business outcome, not its own number:

```
Incremental funded-loan value      ← the goal
   ↑ applications
   ↑ qualified leads (580+, in-footprint, IRRRL-eligible)
   ↑ leads
   ↑ traffic (organic + paid)
```

SEO and paid are levers under this, allocated **intentionally** by where each wins — the §2 data makes the allocation concrete:

| Lane | Organic strength | Paid role | Rationale (from data) |
|---|---|---|---|
| Brand ("future home loans", variants) | **#1**, ~12% of organic traffic | **Stay out / brand-exclude**; tiny defensive budget only if a competitor or the 2nd account bids brand | Don't pay for clicks already earned free (§2a) |
| Jacksonville mortgage-broker/geo | **#1 local pack** | **Lean**; let organic + GMB carry; paid only for incremental reach | Organic owns the pack; high CPC ($6–7.54) (§2a) |
| **VA-purchase, Florida-first** | **Weak (page 3–8)** | **Dominate** | Growth goal + organic can't deliver near-term; clean, low-cannibalization lane (§2b) |
| Generic head ("mortgage broker") | Invisible (pos 45–78) | **Selective / mostly avoid** | High cost, low intent, easy to double-waste (§2c) |

**Incrementality test (settle the $35-vs-$40 question with evidence):**
- De-duplicate conversions to one source of truth first (§4.5).
- Compare **blended** funded-loan value and total qualified leads *before vs. after* the second account launched — not each account's in-platform CPL.
- Watch organic/brand traffic and total lead volume: if paid CPL "improves" while blended volume is flat, the second account is **re-routing, not creating** — the definition of non-incremental spend.
- Where possible, use geo hold-out or brand-bidding on/off tests to measure true incrementality of the contested lanes.

---

## 7. The client conversation (framing)

Lead with orchestration, not ownership — validated by the data above:

> "My bigger concern isn't that a second campaign exists — it's that we now have multiple acquisition efforts running independently without an overarching strategy. Looking at the data, Future already ranks #1 organically for its brand and for the core Jacksonville mortgage-broker searches — so any paid dollars there are largely re-buying traffic you already get for free. Where you're *thin* is exactly your growth goal: VA searches, where the site sits on page 3–8. Two uncoordinated accounts will tend to collide on the same VA and Florida terms while both underusing that opening. We need to orchestrate SEO, all paid media, landing pages, and lead follow-up around one goal — incremental funded-loan value — otherwise we risk competing for the same demand, paying for traffic we already earn, and optimizing individual campaign metrics instead of total business performance."

Then ask for: (1) both accounts analyzed together (read access / MCC link), (2) one acquisition plan, (3) one measurement framework, (4) clear ownership of audiences / keywords / products / geographies.

---

## 8. Recommended next steps

1. **This week — get visibility.** Pull the Google Ads Transparency Center on future.loans; run Auction Insights on our account; check brand-term spend/CPC and paid-clicks-where-organic-#1 in GA4/GSC. (Section 4.)
2. **Request access / MCC link** to the second account, framed as required for measurement.
3. **Build the overlap matrix** (Section 5) once both accounts are visible; produce a single de-duplicated acquisition plan with one owner per lane.
4. **Fix measurement** — one conversion source of truth, de-duplicated, before any cross-account CPL comparison.
5. **Set the lane allocation** (Section 6 table): brand-exclude paid, let organic own brand + Jax geo, point coordinated paid budget at VA-Florida transactional intent, and gate the funnel to the anti-persona (580+, in-footprint, IRRRL-eligible).
6. **Run the incrementality test** before scaling either account; decide any defensive brand budget on purpose, with data.
7. **Reframe the engagement** around acquisition orchestration ownership.

---

## Appendix — methodology & limitations

- **Data:** SE Ranking US database, Sep 2026 snapshot. Volumes, positions, CPCs, and est. traffic are **modeled estimates**, not the client's GA4/Search Console/Ads truth — confirm before quoting any figure externally.
- **Paid data absent:** SE Ranking captured no paid records for future.loans. This brief therefore does **not** observe either Google Ads account's live activity; it characterizes the organic environment both bid against and prescribes how to obtain real account data.
- **Not analyzed here (needs account access):** actual keywords, geos, budgets, bidding, conversion actions, search terms, and creatives of either account; live CPLs; CRM lead flow.
- **Compliance reminder for any resulting creative:** NMLS #1621953 + Equal Housing Lender on creative/primary text; "$0 down"→"most VA purchase loans"; "no lender fees"→pair with "third-party costs still apply"; Meta = Housing Special Ad Category; 13-state footprint, **exclude Arizona**; no unqualified/ disparaging competitor claims; no guaranteed rate/approval. (Full list in the product-marketing context.)
