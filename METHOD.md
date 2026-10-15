# Hamilton Review Index: method (DRAFT, nothing collected yet)

Status: draft, 15 Oct 2026. No listings have been collected. Do not collect until the terms question below is settled by Komi.

## Model
Modeled on the Collingwood Review Index by Georgian Bay SEO
(https://georgianbayseo.ca/blog/collingwood-review-index-2026/). What that study does, per its own page:
- Categories: 22 service categories, from appliance repair and plumbing to dog grooming and phone repair.
- Pull date: Google Maps results pulled on a single named day (22 August 2026), "via the same search API we use for client work".
- Fields: review count, average rating, result position, address, phone.
- De-duplication: a business in several categories counts once in town-wide totals.
- Boundary rules, run at collection time: (1) a listing that shows an address must show a Collingwood address; addressless (service-area) listings are kept; (2) addressless listings must answer on an Ontario or toll-free number; (3) Google category data drops retail counters, dealership service desks, storage and unrelated listings.
- Naming: a named leader's Google category must match its trade; an addressless business is named only if its name declares the market. Only leaders are named. "Below-median numbers stay anonymous and aggregated."
- Corrections: a dated correction note (24 August 2026) restated the July figures because the July curation "was never recorded" and could not be reproduced; withdrawn figures appear once, in the note only.
- Cadence: annual re-run with the same method, plus a monthly update.

## Hamilton draft method
1. Scope. Trades only, first edition: plumbing, electrical, HVAC, roofing, cleaning services. Add more later only with a written rule change.
2. Boundary. City of Hamilton, Ontario (amalgamated city). A listing with an address must show a Hamilton address. Addressless listings kept only if they answer on a 905, 289, 365 or toll-free number AND their name or site states Hamilton service. (Area-code list is a working assumption, to verify.)
3. Exclusions. Retail counters, supply houses, dealership service desks, franchise head offices outside Hamilton, listings with zero reviews.
4. Pull. One named pull date per edition. Record per listing: category searched, review count, rating, date seen. Only what is visible on the public listing.
5. De-duplication. One business counted once across categories.
6. Outputs. Count of businesses, total reviews, median reviews, median rating, share of businesses under 10 reviews, share of reviews held by the top 10 percent. Per category: median and the leader.
7. Naming. Name category leaders only. Never name or single out businesses below the median. Never publish a list of low-review businesses (that is a sales list, not an index, and stays private if it exists at all).
8. Reproducibility. Every rule is written here before collection. Any rule applied after collection is logged with a date.
9. Corrections. Errors are fixed with a dated correction note at the bottom; old figures appear only in that note.
10. Disclosure. State plainly that the author is exploring a review-request service, so the index is not neutral.

## Open blocker: Google terms (must resolve before step 4)
- Google Maps End User Additional Terms (https://www.google.com/help/terms_maps/, last modified 27 Jan 2026) bar copying content (unless permitted by the permissions page or law including fair use), mass download or bulk feeds, and using Maps to build a business listings database for a substitute service. They permit "publicly display content with proper attribution".
- Google Maps Platform Terms s.3.2.3(a) (https://cloud.google.com/maps-platform/terms) forbid scraping and "copy and save business names, addresses, or user reviews" outside the Services, if we used the API.
- Safer design options to choose from: (a) small manual sample, aggregate statistics only, no stored listing database, Google attributed; (b) get counts from businesses that opt in; (c) get a legal read on fair dealing (Canada) before any public release.
