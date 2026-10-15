# Ontario Review Index: Method

**Edition:** Second edition wave. Adds Burlington, Oakville and Mississauga to the existing Hamilton edition.

## Pull dates (America/Toronto)
- Hamilton: Oct 15, 2026 (unchanged from first edition)
- Burlington, Oakville, Mississauga: Oct 15, 2026

## Trades (same 5 in every city)
Plumbing (`plumber`), Electrical (`electrician`), HVAC (`hvac`), Roofing (`roofing`), House cleaning (`cleaning`).

## Search
One manual Google Maps search per trade per city on the pull date, e.g. "plumber Burlington ON". Record the first 20 non-sponsored results. Record only star rating, review count and listing URL (plus name, category and locality for boundary checks). No review text, photos, or map images.

## City boundaries
- Use each city's amalgamated limits (Hamilton includes Stoney Creek, Dundas, Ancaster, Glanbrook, Flamborough; Burlington, Oakville, Mississauga use their municipal limits).
- The listing's address must be in that city. Map pin or address elsewhere = excluded.
- Addressless (service-area) listings are kept only if a local area code or the business name states that city.
- Area codes, working assumption for Burlington, Oakville and Mississauga: 905, 289, 365, or toll-free. An area code alone does not prove the city; the name or address must also point there. (Hamilton first edition rule kept as published.)

## Exclusions
- Google category does not match the trade
- Zero reviews
- Address or pin outside the city
- Every exclusion is logged in `data/exclusions.csv` with a reason, and shown on the page.

## De-duplication
Several listings for one brand in a city count as one business, using the larger listing. Mapped in `data/merges.csv`.

## Stats and naming
Median reviews, median rating and under-10 share are calculated on kept listings per trade per city. Only the top 3 by review count are named. Businesses below the median are never named or listed.

## Disclosure
Published by Komi Onipede, Holdvanta Reviews (olarinkomi.komi@gmail.com, 437-577-3066, 266 Graham Avenue South, Hamilton, ON L8K 2M6). Holdvanta Reviews sells a review-request service, so this index is not neutral. No business paid to appear or be left out.

## Source
Google Maps, viewed on each city's pull date. Not affiliated with Google.
