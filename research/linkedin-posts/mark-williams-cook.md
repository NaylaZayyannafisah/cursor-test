### Mark Williams-Cook

# Post 1:

Date: 11/06/2026

URL: https://www.linkedin.com/posts/markseo_seo-activity-7470766265666580480-FvFN?utm_source=share&utm_medium=member_desktop&rcm=ACoAAECTLMwBqhAP0hyI2pYs9ZcTiD92eKbqS1k

## Key Themes:

**1. Use Regex to Segment GSC Queries by Intent**
Regex filters can uncover different query types, including:
* Informational
* Comparison
* Product/service
* Transactional
* Navigational
* SaaS-related
* Long-tail questions

**2. GSC Regex Enables Better Search Intent Analysis**
Applying regex filters in GSC Performance reports helps identify opportunities hidden within existing query data.

**3. Regex Works Beyond GSC**
The same patterns can be used in tools like Ahrefs and other platforms that support regex.

**4. Be Aware of Limitations**
For large sites, GSC frontend filtering may be unreliable, and regex filtering can inflate impression metrics.

### Full Post:

Unsolicited hashtag#SEO tip: Instead of spicy 'probably ok' AI, you can reliably* filter your GSC query data to uncover a treasure trove of query types your site is ranking for, with the following regex patterns: 🧙‍♂️ 

📃 Informational intent (Guides, tutorials, how-tos)
\b(how to|guide|tutorial|step by step|tips|tricks|ways to|best way to|learn|help|explain|understand|instruction|methods|examples|meaning of|definition)\b

⚖️ For comparisons (e.g., "best", "vs", "alternative", "cheaper"):
\b(best|vs|versus|compare|comparison|alternative|alternatives|better|cheaper|worse|cheapest|highest|lowest|top|difference|differences|differences between)\b

🛍️ Questions on products/services (e.g., "is X good?", "where to buy X?")
\b(price|cost|buy|purchase|available|best|quality|brand|reviews|ratings|features|specifications|order|discount|warranty|deal|shop|store|version|options|model|type|compare)\b

💰 Transactional intent (Buying, pricing, ;ocations)
\b(buy|purchase|price|cost|cheap|discount|deal|coupon|order|shop|store|near me|online|sale|best price|affordable|available|in stock)\b

🧭 Navigational intent (Brand-specific, reviews, support)
\b(review|reviews|rating|ratings|customer service|support|warranty|return policy|refund|complaint|feedback|scam|legit|trustworthy|experience|testimonial|problems|issues)\b

🛠️ Specific for SaaS (Tool queries from Pietro Mingotti)
\b(?:tool|software|app|system|platform|application|program|solution|portal|suite|service)s?\b

❓ Queries with more than 4 words (Likely to be questions)
([^ ]+\s){4,}

To get this:
1) Open your Google Search Console
2) Go to "Performance"
3) On the filters at the top click on "+ Add filter"
4) Select "Query"
5) Change the drop down to "Custom (regex)"

Paste in the regex and be amazed ✨

🏆 BONUS TIPS and Community comments:

*Malte Landwehr warns using the GSC frontend for large sites can be unreliable.

Stephan Czysch has a GSC Helper Chrome extension with present filters you can use too (link in comments)

Gianna Brachetti-Truskawa defines small site as ~10k pages, medium as 100k, and large above.

Ryan Jones points out regex filters is it changes all the metrics to sum up pages - so you get greatly inflated impression counts. 

🔎 Charles Meaden points out these can be used in other tools such as Ahrefs that support regex
![Photo](/research/photos/mwc.png)

## Insights:

* Regex filtering turns GSC into an intent analysis tool.
* Segmenting queries helps uncover content opportunities.
* Regex patterns are reusable across SEO tools.
* Large sites should validate GSC regex results carefully.
* Filtered metrics may overstate impressions and require caution.