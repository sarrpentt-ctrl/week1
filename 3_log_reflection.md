# 3_log_reflection.md — AI use, checking and reflection

**Student:** Sulaim Niaz  
**ERP:** 37389  
**Assignment:** The Headline Test — Question 2

## AI coach prompt to use and log

Paste your own two claims and proposed Question 2 into an AI tool and ask:

> Act as a Socratic coach. Criticise this question: “Did the four selected products have different average recorded prices in City 1 and City 2 over the 12 observation dates?” Identify assumptions, ask what evidence is needed, and suggest alternative questions. Do not write my assessed answer.

**Important:** The items below are verification examples based on possible suggestions. In the submitted log, record the suggestions that your AI conversation actually produced. Do not claim a suggestion was made if it was not.

## Verification of possible AI suggestions

| Possible AI suggestion | Decision | Evidence / reason |
|---|---|---|
| Compare the average prices of the same four products in City 1 and City 2. | Answerable | The CSV has `city`, `item`, `price` and `date`; matching same item/date pairs is possible. |
| Determine whether the difference is statistically representative of all cities in Pakistan. | Reject | Only two anonymised cities are included, and the file is illustrative teaching data. |
| Explain why City 2 has higher prices, such as transport or rent costs. | Reject | No transport, rent, supply-chain or other causal variables are present. |
| Compare each product separately between the two cities. | Answerable | The product and city columns are present, and both cities have observations for each product/date. |

## Data checks to record

- Dataset dimensions: 96 rows and 6 columns.
- Distinct products: 4.
- Distinct dates: 12.
- Distinct cities: 2.
- Missing values: none in the supplied CSV.
- Exact duplicate rows: none in the supplied CSV.
- The dataset's `data_label` says: “ILLUSTRATIVE TEACHING DATA - NOT ACTUAL PBS OBSERVATIONS”.
- All prices use the same unit field in the supplied data; inspect the `unit` values in the notebook before comparing.

## Main findings from the supplied CSV

Average prices over the 12 dates:

| Product | City 1 mean | City 2 mean | Difference (City 2 − City 1) |
|---|---:|---:|---:|
| Oil B | 321.83 | 327.83 | 6.00 |
| Pulse C | 202.92 | 208.92 | 6.00 |
| Staple A | 108.17 | 114.17 | 6.00 |
| Sweetener D | 163.75 | 169.75 | 6.00 |

Overall average across all recorded rows:
- City 1: PKR 199.17
- City 2: PKR 205.17
- Difference: PKR 6.00 (approximately 3.01% above City 1's average)

A notable pattern is that City 2 is exactly PKR 6 higher than City 1 for every matched product/date pair in this teaching dataset. This is a pattern in the supplied data, not evidence about actual cities or a real-world pricing mechanism.

## Reflection (about 100 words)

The dataset allows me to compare the recorded prices of the same four products in City 1 and City 2 over 12 dates. The average recorded price is higher in City 2 for each product, and the paired difference is PKR 6 in every matched observation. However, this does not show that prices are higher in every city or for every product. The data is explicitly labelled as illustrative teaching data, not actual PBS observations. It also contains no information about transport costs, income, household spending or the reasons for the difference. I learned that a comparison can describe a pattern without proving its cause or wider representativeness.

## Three sentences on unsupported suggestions

1. A claim about all Pakistani cities is unsupported because the file contains only City 1 and City 2.
2. An explanation based on transport or production costs is unsupported because those variables are not recorded.
3. A claim about affordability or consumer spending is unsupported because household income and expenditure are absent.

## AI-use log — complete with your actual interaction

| Date/time | AI role / prompt | Suggestion received | My decision and evidence |
|---|---|---|---|
| __________ | Socratic coach | __________ | __________ |
| __________ | __________ | __________ | __________ |

## Source check

The assignment handout requests checking any source named by AI. Record the source, what it says, and whether it supports the suggestion. If AI did not name a source, write “No external source was suggested.”

## Note about the course handout

Page 1 mentions `AI_USE_LOG.md`; page 2 lists `3_log_reflection.md` and says it contains the checked/rejected list, log row and reflection. Confirm with the instructor whether a separate `AI_USE_LOG.md` is also required.
