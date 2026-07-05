# Amex Customer Treatment Impact Analysis

## Business Problem
Marketing teams need to know whether a campaign, offer, or "treatment" actually changes customer behavior — not just whether customers who received it happened to spend more. This project compares customers who responded to past marketing campaigns against those who didn't, to measure the real impact of marketing treatments on spend and engagement.

## Dataset
**Source:** [Marketing Campaign](https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign) (Kaggle, by rodsaldanha)
Customer demographic and purchase data including income, family structure, spend across product categories, and response to multiple past marketing campaigns. See `data/README.md` for download instructions.

## Objective
Measure the difference in spending behavior and engagement between customers who responded to marketing campaigns ("treated") and those who didn't, control for demographic differences where possible, and quantify the impact of marketing treatment on customer value.

## Tools Used
- Python (Pandas, NumPy, SciPy for statistical comparison)
- Matplotlib / Seaborn (visualization)

## Approach
1. Cleaned and explored customer demographic and spend data
2. Defined "treatment" group (customers who accepted at least one campaign offer) vs. "control" group (customers who didn't)
3. Compared average spend, purchase frequency, and recency between groups
4. Controlled for income and family size differences using grouped comparisons
5. Ran statistical significance tests (t-test) to confirm whether observed differences are meaningful or due to chance

## Key Insight
> *[Fill in once analysis is done — e.g., "Customers who accepted at least one campaign offer spend 35% more on average even after controlling for income — suggesting campaign acceptance is a genuine engagement signal, not just a proxy for higher-income customers."]*

## Recommendation to Stakeholders
> *[Fill in — e.g., "Prioritize re-targeting customers who accepted at least one past campaign, since they show statistically significant higher lifetime spend; for non-responders, test a different offer structure before increasing campaign frequency."]*

## Repo Structure
```
├── data/           → dataset source info
├── notebooks/       → Python analysis
├── images/          → charts/screenshots
└── README.md
```
