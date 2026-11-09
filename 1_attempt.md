# 1_attempt.md — Initial attempt and research questions

**Student:** Sulaim Niaz  
**ERP:** 37389  
**Assignment:** The Headline Test

> Important: The handout requires this attempt to be written and saved before using AI. This prepared working document is AI-assisted and must not be represented as a genuine pre-AI snapshot. Use it as a structure/checklist and preserve any original independent attempt separately.

## Everyday claims

1. “Everything costs more.”
2. “Prices are the same everywhere.”

## Research questions

**Question 1 (time comparison):** How did the recorded prices of the four selected products change between the first and last observation dates?

**Question 2 (the focus of this notebook):** Did the four selected products have different average recorded prices in City 1 and City 2 over the 12 observation dates?

Question 2 is more precise than the headline “Prices are the same everywhere” because it names the two locations and the products included in this dataset. It does not claim to represent every city or every product.

## Variables needed for Question 2

- `city`: identifies City 1 and City 2.
- `item`: identifies the same product in both cities.
- `price`: records the price to compare.
- `date`: allows matching observations from the same date.
- `unit`: helps check that the prices use a comparable measurement unit.

`data_label` is also useful for understanding the dataset's status.

## Predictions to record before running code

Write your own estimates before running the notebook. Do not copy the observed answers into this section before making your prediction.

- Predicted number of rows: __________________
- Predicted number of columns: __________________
- Predicted number of distinct products: __________________
- Predicted number of distinct dates: __________________
- Predicted number of cities: __________________
- Predicted direction of the City 1–City 2 comparison, with a reason: __________________

## Scope and limitations anticipated

The dataset appears to cover only four selected products, two anonymised cities and a limited period. It cannot automatically support claims about every product, all locations, household affordability, consumer spending or the causes of price differences.
