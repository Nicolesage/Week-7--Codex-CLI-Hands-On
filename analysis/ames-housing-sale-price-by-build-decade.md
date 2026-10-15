# Ames Housing: sale price by year built

## Finding

Sale prices generally trend higher for homes built in more recent decades. The median sale price is $125,600 for homes built in the 1940s, $146,900 in the 1970s, and $225,500 in the 2000s. The pattern varies by decade rather than increasing steadily. The 2010s median is $394,432, but it represents only three sales and should be interpreted cautiously.

## Summary by build decade

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

## Visualization

[Median sale price by build decade](../home-sale-price-by-build-decade.svg)

## Method and caveats

- Grouped records by decade using `Year Built` and summarized `SalePrice` with the number of sales, median, and mean.
- These are descriptive, unadjusted comparisons. Sale price also depends on factors such as home size, quality, and neighborhood.
- The 1870s and 2010s groups have only three sales each, making their statistics especially sensitive to individual homes.
