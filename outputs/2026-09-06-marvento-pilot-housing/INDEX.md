# Marvento Homes — student pilot housing ads

**Date:** 2026-09-06  
**Destination:** https://marventohomes.com/student-pilot-housing-st-augustine  
**Platforms:** Google Search RSA (primary, high intent) + Meta feed static  
**Mode:** Generate from scratch (ads 2.3.2 + ad-creative 2.8.2)  
**Recommended launch:** Google Search first (people already looking for a room). On Meta, Concept 01 as the always-on cold ad; 02–04 as a 4-way angle test.

No `.agents/product-marketing.md` was present. All claims are grounded in the live student-pilot landing page and homepage (fetched 2026-09-06).

## Pick these

| # | Concept | Template | Tier | Angle | File | Visual |
|---|---------|----------|------|-------|------|--------|
| 01 | Built for Student Pilots | Headline Statement | B — mid-funnel supporting | Identity | [concepts/01-headline-built-for-pilots.md](concepts/01-headline-built-for-pilots.md) | [images/mh-pilot-ad-built-for-pilots.png](images/mh-pilot-ad-built-for-pilots.png) |
| 02 | Need an SSN or Co-Signer? | FAQ Card | B — supporting / objection | Friction | [concepts/02-faq-no-ssn.md](concepts/02-faq-no-ssn.md) | [images/mh-pilot-ad-no-ssn.png](images/mh-pilot-ad-no-ssn.png) |
| 03 | The Real Monthly Cost | Us vs. Them | B — supporting / comparison | Contrast | [concepts/03-us-vs-them-cost.md](concepts/03-us-vs-them-cost.md) | [images/mh-pilot-ad-vs-apartment.png](images/mh-pilot-ad-vs-apartment.png) |
| 04 | 8 MIN to Florida Flyers | Stat Callout | C — situational supporting | Proximity | [concepts/04-stat-8-min.md](concepts/04-stat-8-min.md) | [images/mh-pilot-ad-8-min.png](images/mh-pilot-ad-8-min.png) |

**If you only launch one Meta ad:** Concept 01. It carries the identity trigger (`student pilots`) plus the commute the landing page leads with.

Open [review.html](review.html) for in-feed mockups. Google search copy is in [google-rsa.csv](google-rsa.csv). Full Meta + Google fields, ad groups, negatives, and extensions are in [UPLOAD.md](UPLOAD.md).

## Grounding sources

- Student-pilot landing page: https://marventohomes.com/student-pilot-housing-st-augustine
- Homepage: https://marventohomes.com/
- Student home photos: https://marventohomes.com/3530-datura
- Brand assets: `marvento-homes-logo-2.jpg` (house + wind + waves + two figures), Instagram/Facebook `@marventohomes`
- Property photo used in creatives: 3530 Datura Street exterior (sage siding, white metal roof, house number 3530)

**Used on-page claims only:** 8–11 minute / 3.9-mile drive to Florida Flyers at 4730 Casa Cola Way and KSGJ; furnished private rooms with en suite baths; no SSN or co-signer; remote lease / room hold (including while waiting on an M1 visa); enterprise Wi-Fi for ForeFlight; weekly housekeeping; lease terms matched to training; from $1,195/month (10–12 month term); typical-apartment true cost ~$2,069 vs Marvento from $1,195; confirm availability within 24 hours; phone (904) 682-9859; Equal Housing Opportunity added for housing-ad compliance (not shown on-page).

**Not used in ads:** shared-room $850 rate (save for a different-offer retarget); named motels (Travelodge / Days Inn) in paid creative; senior-home messaging; invented occupancy or waitlist numbers.

## Compliance (must-run)

- Meta: **Housing** Special Ad Category. Do not use detailed targeting that excludes protected classes. Creative does the targeting (`student pilots`, `Florida Flyers`, `St. Augustine`).
- Google: housing ads — keep copy about the housing and rental terms, not who is “preferred.” “No SSN or co-signer” is a rental policy, not a national-origin preference.
- Keep Equal Housing Opportunity on the image or in primary text.
- Imagery is property-only (no people) to reduce Fair Housing “ad targeting by demographic portrayal” risk.
- Do not promise check-ride outcomes, visa approval, or guaranteed room availability. “Rooms are limited” is on-page; do not invent a count.
- Do not point this campaign at the senior home (3540 Datura). Final URL is the student-pilot page only.

## Campaign notes

- **Search before social.** Incoming pilots (including M1 students still overseas) type “Florida Flyers housing” and “student apartments St. Augustine.” Google harvests that demand. Meta creates it.
- **Do not geo-lock Search to people already in St. Augustine.** Many converters are not in Florida yet. See UPLOAD.md location settings.
- **Tracking blocker:** the student-pilot page loads `gtag` with placeholder `AW-XXXXXXXXXX`. GTM `GTM-MX3WCX3T` is live. Wire the “Check Availability” form submit as the conversion before spending.

## Test plan

Change one variable: **angle** (same destination, same CTA).

1. Launch Google Search (3 themed ad groups) with conversion tracking live.
2. Launch all four Meta statics at even budget for 1,000+ impressions each.
3. Kill on CTR + landing-page submit rate, not thumbstop alone.
4. Winner’s next iteration: same visual, new first line of primary text (hook), per hook-system one-component rule.
5. Retarget non-submitters with the **shared-room from $850** offer (different offer, same audience) — do not re-show the $1,195 private-room ad harder.
