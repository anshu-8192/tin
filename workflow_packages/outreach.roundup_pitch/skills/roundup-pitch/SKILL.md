---
name: roundup-pitch
description: Find published "best of" and comparison articles missing this product and draft a personalized pitch email for each.
---

Buyers researching a purchase often read a "best [category] tools" or "[category] X vs Y"
article before deciding. If a product is missing from these articles, it loses buyers who
never hear about it, even if the product itself is strong.

Do the following:

1. Search for recent, well-ranking articles that list products in the given
   `product_category` (for example "best [category] 2026", "[category] alternatives",
   "top [category] tools compared"). Prefer independent blogs and review sites over the
   company's own site or paid directories.

2. For each article found, check whether it already mentions the product at `product_url`.
   Skip articles that already include it. Keep articles that list one or more of the
   supplied `competitor_names` but not this product; these are the highest-value targets.

3. For each kept article, identify: the article title, its URL, its author or publication
   if visible, and one specific detail worth referencing (for example, a criterion the
   article uses to rank products, or a gap the article's own text points out).

4. For every kept article, draft one short, specific pitch email. Reference the concrete
   detail found in step 3, explain briefly why the product fits the article's own criteria,
   and ask if the author would consider adding it. Keep the email under 120 words, avoid
   generic flattery, and never claim a relationship with the author that does not exist.

5. Write the result to `outreach/roundup/PITCH_LIST.md` as a table of found articles
   (title, url, why it's a target) followed by one drafted email per article. Cite the
   article URL for every claim about what it currently contains. If no qualifying articles
   are found, say so plainly instead of inventing targets.

Do not send any email. Do not claim an article's ranking criteria if the article does not
state them; describe what is actually visible in the page instead of guessing.ZZZZZZZZZZZZZZZZZ
