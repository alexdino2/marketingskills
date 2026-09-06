# Digital Optimus — agency ads

**Date:** 2026-09-06  
**Brand:** Digital Optimus (digitaloptimus.com)  
**Primary destination:** https://digitaloptimus.com/schedule-discovery-call  
**Alternate destinations:** homepage (search message-match), [Market Blueprint](https://digitaloptimus.com/performance-marketing-audit), [Jacksonville](https://digitaloptimus.com/jacksonville-fl-performance-marketing)  
**Platforms:** LinkedIn (primary) + Google Search RSAs + Meta feed statics  
**Mode:** Generate from scratch (ads 2.3.2 + ad-creative 2.8.2)  
**Offer:** Free Custom Growth Strategy call (about 20 minutes, 2 minutes to book) or the written Market Blueprint (15 pages, one business day)

No `.agents/product-marketing.md` was present. All claims are grounded in the live site (fetched 2026-09-06).

## Pick these

| # | Concept | Template | Tier | Angle | File | Visual |
|---|---------|----------|------|-------|------|--------|
| 01 | Borrowers Ask AI | Headline Statement | B — mid-funnel supporting | Curiosity / category | [concepts/01-headline-ai-portal.md](concepts/01-headline-ai-portal.md) | [images/do-ad-ai-portal.png](images/do-ad-ai-portal.png) |
| 02 | Tired of Retainers | Founder Message | S — unicorn cold-scaler | Origin / identity | [concepts/02-founder-retainers.md](concepts/02-founder-retainers.md) | [images/do-ad-founder.png](images/do-ad-founder.png) |
| 03 | 2x in One Week | Stat Callout | C — proof supporting | Social proof | [concepts/03-stat-2x-leads.md](concepts/03-stat-2x-leads.md) | [images/do-ad-stat-2x.png](images/do-ad-stat-2x.png) |
| 04 | Stop Buying Portals | Us vs. Them | B — comparison | Pain / contrast | [concepts/04-us-vs-portals.md](concepts/04-us-vs-portals.md) | [images/do-ad-vs-portals.png](images/do-ad-vs-portals.png) |
| 05 | Don't Start With Ads | Challenging Your Beliefs | B — objection / MOF | Contrarian | [concepts/05-dont-start-with-ads.md](concepts/05-dont-start-with-ads.md) | [images/do-ad-no-ads-first.png](images/do-ad-no-ads-first.png) |

**If you only launch one ad:** Concept 02 on LinkedIn as a Thought Leader Ad from Alex Destino. Founder content is the cold-reach format; the site's origin story is specific enough to stop a lender mid-scroll.

**If you launch a 5-way angle test:** same destination, same CTA, change only the angle (creative testing hierarchy: concept first).

Open [review.html](review.html) for in-feed mockups. Upload fields: [UPLOAD.md](UPLOAD.md). Google Search: [google-rsa.md](google-rsa.md) + [google-rsa.csv](google-rsa.csv).

## Who this is for

Three ICPs that share one problem: a national aggregator sits between them and local buyers.

- **Mortgage lenders** — independent lenders and producing branches tired of buying back their own market from rate-table sites
- **Real estate teams** — teams whose listings get found on Zillow before the team's own site
- **Financial advisors** — firms that can see marketing spend but cannot trace which part produced new assets

Geo: Jacksonville / Northeast Florida first (home market), then Orlando and Tampa, then other metros after a scan. Identity-trigger keywords in the creative do the targeting on Meta; LinkedIn still uses title/seniority filters.

## Campaign structure

```
LinkedIn (Capture — booked strategy call)
├── LI_LeadGen_Lenders_StrategyCall_2026Q3
│     Audience: loan officers, branch managers, mortgage originators — US, seniority Manager+
│     Ads: 02 founder TLA + 01 + 03
├── LI_LeadGen_RETeams_StrategyCall_2026Q3
│     Audience: team leads, managing brokers, brokerage owners
│     Ads: 04 portals + 02 + 01 (identity: real estate teams)
└── LI_LeadGen_Advisors_StrategyCall_2026Q3     (hold until lenders/RE convert)
      Audience: RIA principals, wealth advisors — company size 11–200

Google Search (Capture — independent budgets, never shared)
├── GOOG_Search_Brand_StrategyCall_Ongoing          RSA3
├── GOOG_Search_MortgageMktg_StrategyCall_Ongoing   RSA1
└── GOOG_Search_RealEstateMktg_StrategyCall_Ongoing RSA2

Meta (Create — broad US + FL, creative is the targeting)
└── META_Conv_Lenders_StrategyCall_2026Q3
      CBO, 5 statics, no interest stacking
```

Do not open Performance Max, Display, or Search Partners until non-brand Search has ~30 conversions/month and offline conversions are flowing.

## Grounding sources

- Homepage: https://digitaloptimus.com/ (fetched 2026-09-06)
- Strategy call: https://digitaloptimus.com/schedule-discovery-call
- Market Blueprint: https://digitaloptimus.com/performance-marketing-audit
- Jacksonville: https://digitaloptimus.com/jacksonville-fl-performance-marketing
- FHL case: https://digitaloptimus.com/success/future-home-loans-page-speed
- Methodology: https://digitaloptimus.com/methodology
- Brand mark: `brand/digital-optimus-logo.webp` (four rounded L-chevrons, cyan + mint, plus-shaped negative space, black ground)
- Colors from live CSS: ink `#040D16` / `#061422`, teal `#2DD4BF` / `#14B8A6`, mint `#86EFAC`, Inter

**Used, named, windowed:**

| Client | Claim | Window |
|--------|-------|--------|
| Future Home Loans | 2× lead rate; load time 5.2s → 2.9s; form submissions doubled the week of the speed fix; +180% lead volume at flat CPL (full program) | week one / full program |
| Expert Home Advisors | +300% organic leads; top three for 27 local keywords, above Zillow and Realtor.com | six months |
| North Avenue Capital | $750M prospect demand identified; +85% site conversion | nine months |

Quotes used only when attributed on-site: North Avenue Capital CEO; Expert Home Advisors; Future Home Loans Marketing Director (case page).

**Not used:** roi-tools hub figures (4–6× / +15 leads / 3–5% CVR — unnamed); key-driver-analysis composite rows (unnamed dentist, “Fortune 500”); any Tesla/xAI “Digital Optimus” confusion.

## Compliance

- These ads sell **marketing services**, not loans or securities. Do not add rate, APR, payment, or “pre-approved” language.
- Do not promise the prospect will double leads or outrank Zillow. Named-client results stay named, with the window.
- MAP Rule / Reg Z copy is a **capability** (“we write around trigger terms”), not a loan ad.
- LinkedIn: leave Audience Expansion and Audience Network OFF.
- Meta: broad geo; put the identity word in the headline (`mortgage`, `lenders`, `real estate teams`, `advisors`), not in interest stacks.

## Test plan

Change one variable: **angle** (same destination, same CTA: Book a strategy call).

1. LinkedIn: launch 02 as TLA + company-page 01 and 03. Manual CPC after week 1 (~20% below automated CPC).
2. Google: Brand + Mortgage high-intent first. Add Real Estate only after mortgage Search produces booked calls.
3. Meta: all five statics in one CBO, US or FL only. Kill on booked-call CPA after 2–3× target spend with zero calls, not on CTR alone.
4. Winner’s next iteration: same visual, new first line of primary text (identity-keyword variants in UPLOAD.md).
5. Retarget site visitors 7–30 days with Concept 05 and the Market Blueprint (different offer, not the same call).

**Conversion to optimize:** booked strategy-call event (and Blueprint submit as a secondary). Import CRM stage changes as soon as they exist — do not let smart bidding optimize to “any form fill.”
