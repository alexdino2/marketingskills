# Meta titles & descriptions — student content cluster

Keep titles ≤60 characters when possible; descriptions ≤155. Include a clear outcome + location. Do not stuff “best luxury premium.”

---

## New landing page

**URL:** `/student-apartments-st-augustine`  
**Title:** Student Apartments Near St. Augustine, FL | From $1,195  
**Description:** Furnished private rooms with en suite baths near Flagler & St. Augustine Airport. All-inclusive from $1,195/mo — utilities, Wi-Fi, housekeeping. No SSN or co-signer.

**H1:** Student apartments near St. Augustine — without the apartment hassle

---

## Blog: hub guide

**URL:** `/blog/student-apartments-st-augustine-guide`  
**Title:** Student Apartments in St. Augustine, FL: What to Compare  
**Description:** Compare student apartments near St. Augustine — true monthly cost, lease length, furniture, and co-signer rules before you sign.

---

## Blog: true cost

**URL:** `/blog/true-cost-student-housing-st-augustine`  
**Title:** True Cost of Student Housing in St. Augustine  
**Description:** Apartment vs motel vs furnished room — see what students near St. Augustine really pay once fees, utilities, and furniture are included.

---

## Blog: Flagler

**URL:** `/blog/flagler-college-off-campus-housing`  
**Title:** Flagler College Off-Campus Housing Guide  
**Description:** Flagler juniors and seniors: compare downtown houses, apartment complexes, and furnished rooms ~10 minutes from campus.

---

## Blog: no SSN

**URL:** `/blog/rent-without-ssn-st-augustine`  
**Title:** Rent Near St. Augustine Without a Social Security Number  
**Description:** Why St. Augustine complexes ask for an SSN or co-signer — and how incoming students can lease a furnished room without either.

---

## Existing pages — recommended title tweaks

### Homepage (student path visibility)
Keep senior + student balance, but ensure student snippet is crawlable:
**Title (alt test):** Coliving in St. Augustine | Student Housing & Senior Living | Marvento  
**Description:** Furnished private rooms on Datura Street — student housing near Flagler & KSGJ from $1,195, and senior independent living from $1,500. All-inclusive.

### `/3530-datura` (already strong)
Keep airport-led title; add Flagler in description if missing:
**Description add:** About 10 minutes to Flagler College and 8–11 minutes to KSGJ. Furnished en suite rooms from $1,195/month.

### `/student-pilot-housing-st-augustine`
Keep pilot-specific title. Internally link new hub as “Not a pilot? See all student apartment options.”

---

## Schema suggestions (implement on site)

On the new hub and 3530 page:

- `LodgingBusiness` or `ApartmentComplex` is a poor fit for a shared home — prefer `House` + `Offer` for room rates, or FAQPage for FAQs already on-page.  
- Add `FAQPage` JSON-LD using the landing-page FAQs.  
- Add `BreadcrumbList`: Home → Student Apartments → [Post].  

Exact schema examples: use the repo `schema` skill when implementing in code.
