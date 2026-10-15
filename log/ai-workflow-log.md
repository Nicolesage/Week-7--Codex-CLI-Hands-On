# AI workflow log

## Dataset analysis: sale price by year built

**Dataset:** `AmesHousing-1.csv` (Ames Housing sales data)

**Date:** 2026-10-15

### Conversation and actions

1. **User asked:** “How does the cost of home sales prices change with the year the house was built in this data set?”
   - Located the CSV and identified `Year Built` and `SalePrice` fields.
   - Grouped sales by build decade and calculated counts, median sale prices, and mean sale prices.
   - Summary: prices generally increase for later build decades, with decade-to-decade variation. The 2010s value is based on only three sales.

2. **User asked:** “Can you please provide me a visualization of this data?”
   - Created `home-sale-price-by-build-decade.svg`, a chart of median sale price by decade built with sale counts noted.

3. **User asked:** “can you please create me a summary table of this data?”
   - Shared the following decade summary:

| Year built | Sales | Median sale price | Mean sale price |
|---|---:|---:|---:|
| 1870–1879 | 3 | $185,000 | $133,667 |
| 1880–1889 | 8 | $127,500 | $165,497 |
| 1890–1899 | 15 | $138,000 | $162,676 |
| 1900–1909 | 40 | $118,000 | $122,217 |
| 1910–1919 | 110 | $126,250 | $126,311 |
| 1920–1929 | 196 | $115,500 | $121,855 |
| 1930–1939 | 109 | $128,000 | $142,261 |
| 1940–1949 | 151 | $125,600 | $125,016 |
| 1950–1959 | 340 | $135,000 | $139,892 |
| 1960–1969 | 357 | $145,000 | $151,394 |
| 1970–1979 | 364 | $146,900 | $151,884 |
| 1980–1989 | 120 | $178,500 | $187,142 |
| 1990–1999 | 334 | $203,068 | $223,267 |
| 2000–2009 | 780 | $225,500 | $248,388 |
| 2010–2019 | 3 | $394,432 | $283,116 |

4. **User entered:** `/prompts/`, followed by `transcript`.
   - Interpreted this as a request for the conversation transcript; provided a brief transcript in chat.

5. **User provided:** `/log/ai-workflow-log.md`.
   - Saved this workflow log at the requested path.

### Notes

- The decade-level figures are descriptive comparisons; they do not adjust for home size, quality, neighborhood, or other factors that influence sale price.
- The 1870s and 2010s summaries each have only three sales and are particularly sensitive to individual properties.
