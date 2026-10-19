# Sample audit

A full audit produced by the skill, to show the expected depth and tone. The store and product are fictional.

## Input

A mobile screenshot of a product page for a 20 oz insulated travel mug, $32. The hero shows one white-background product photo, the title "TM-20 Pro Travel Mug", the price and a "BUY NOW" button. Below: a paragraph listing specs (double-wall vacuum insulation, 18/8 stainless steel, leakproof lid, BPA-free). No video, no rating, no reviews, no FAQ. Returns policy is linked only from the footer. A "You may also like" row sits at the bottom.

## Output

# CRO Product Page Audit

**Score:** 33 / 100
**Verdict in one line:** A "photo + spec list" page — social proof, benefits and trust are all missing; add real reviews first, then rewrite the hero and description.

## Context
- Platform: own store (inferred)
- Device: mobile
- Category: visual-driven, everyday product
- Price point: mid ($32)
- Likely audience: commuters and office workers

## Section scores

| # | Section | Score | Diagnosis |
|---|---|---|---|
| 1 | Hero | 5/12 | Model-number title, no subheadline, no rating, bare CTA |
| 2 | Images | 4/12 | One studio shot; no in-scale, in-use or customer photos |
| 3 | Video | 0/8 | None — a leak test is the obvious demo |
| 4 | Benefit > feature | 3/15 | Pure spec list; nothing about hot coffee at 11am or a dry laptop bag |
| 5 | Social proof | 0/12 | No rating, reviews or customer photos anywhere |
| 6 | FAQ | 0/5 | None — "Does it fit my cup holder?" is unanswered |
| 7 | Trust & risk reversal | 2/8 | Payment icons only; returns hidden in footer |
| 8 | CTA | 4/10 | "BUY NOW" in caps; not sticky; no risk line |
| 9 | Design & hierarchy | 7/8 | Clean, readable, good spacing |
| 10 | Mobile | 4/5 | Good sizes; no sticky CTA |
| 11 | Marketing hooks | 1/3 | None used |
| 12 | Upsell | 1/2 | Generic "You may also like" — a lid or straw add-on would fit better |

## Cross-page signals
- Category fit: 🟡 — copy is all specs; neither "built to last" (vitamin) nor "no more cold coffee" (painkiller) comes through
- Consistency: 🟢
- Audience match: 🟡 — nothing speaks to commuters
- Localization: 🟢
- Review recency: 🔴 — no reviews at all
- Length / scannability: 🟡 — too short; whole sections missing
- Cognitive load: 🟢

## Top 5 conversion killers

🚨 **Issue #1: No social proof at all** [🔴]
Where: whole page — should appear under the title and near the CTA
Now: "No rating, review count, customer photos or review-platform link anywhere"
Why it hurts: PowerReviews found pages with even 1–10 reviews convert 52.2% better than pages with none; Spiegel Research Center found ~5 reviews make a purchase nearly 4× more likely. These are published averages, not a forecast for this page.
Fix: ① show "★ [real rating] from [real count] reviews" under the title ② feature one representative review with photo near the CTA ③ add a customer-photo strip mid-page ④ if there are no reviews yet, run a post-purchase review request before anything else.
Expected impact: high — going from zero to some reviews is typically the largest single lift available on a page like this.

🚨 **Issue #2: Specs, not benefits** [🔴]
Where: description block
Now: "Double-wall vacuum insulation, 18/8 stainless steel, leakproof lid, BPA-free."
Why it hurts: buyers don't buy insulation, they buy hot coffee hours later — the classic "2000W motor → more time with your family" mistake.
Fix: translate each feature — insulation → "Still hot at your 11am meeting"; leakproof lid → "Throw it in your bag next to your laptop"; 18/8 steel → "No metallic taste, no rust"; BPA-free → "Nothing leaching into your coffee".
Expected impact: medium–high; clearer value usually lifts add-to-cart, especially on mobile where people skim.

🚨 **Issue #3: No video** [🔴]
Where: gallery, position 2
Now: "No video on the page"
Why it hurts: video on product pages is commonly cited as a strong conversion driver; for a "leakproof" claim, showing beats telling.
Fix: a 20–30 s captioned clip — 0–3 s mug turned upside down over a laptop; 4–15 s one-hand lid, car cup holder fit; 16–25 s steam after 6 hours (only if true); end on price and returns.
Expected impact: medium; also reusable for ads and social.

🚨 **Issue #4: Bare, shouting CTA** [🟡]
Where: hero button; no sticky version
Now: "BUY NOW"
Why it hurts: specific CTAs outperform vague ones — in VWO's Veeam test, a more specific label lifted click-through 161%. All caps also reads as shouting and is harder to read.
Fix: "Add to cart — free returns for [N] days" + a sticky bottom bar on mobile + a line beneath: "Ships in 24h · Free shipping over $[X]" (only if true).
Expected impact: medium.

🚨 **Issue #5: Returns hidden, no in-scale image** [🟡]
Where: trust (footer link only) and gallery
Now: "Returns policy only linked from the footer; one white-background photo"
Why it hurts: an unsatisfactory or invisible returns policy is a recurring abandonment reason in Baymard's research, and many shoppers judge size from images.
Fix: put the returns promise beside the CTA; add an in-hand photo and a cup-holder photo to the gallery.
Expected impact: medium.

## Rewrite table

| Section | Before | After | Why |
|---|---|---|---|
| Title | "TM-20 Pro Travel Mug" | "The travel mug that keeps coffee hot past lunch" | Category + promise, not a model number |
| Subheadline | (none) | "20 oz, leakproof, fits standard car cup holders" | Adds audience-relevant specifics |
| First bullet | "Double-wall vacuum insulation" | "Still hot at your 11am meeting" | Feature → benefit |
| CTA | "BUY NOW" | "Add to cart — free [N]-day returns" | Specific, sentence case, risk reversal |

## Next steps (ROI order)

1. **This week — reviews.** Collect and display real ratings and photos; this is the biggest gap.
2. **Next — a 20-second leak-test video.** One asset for the product page, ads and social.
3. **A/B test the hero:** A "TM-20 Pro Travel Mug" vs B "The travel mug that keeps coffee hot past lunch". Run until each variant has enough conversions to call it.
4. **Rewrite the description** feature by feature using the table above.
5. **Install a heatmap / session recording tool** to see where mobile visitors stop scrolling before deciding what to build next.
