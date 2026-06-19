# Do Stock Prices Fully Reflect Information in Accruals and Cash Flows About Future Earnings?

**Source:** Sloan (1996) · The Accounting Review · DOI: 10.2308/tar-9608042309 · [SSRN](https://ssrn.com/abstract=2598)

## TL;DR

Earnings decompose into a cash-flow component and an accrual component. The accrual component is **less persistent**, but investors "fixate" on the bottom-line earnings number and fail to discount it. A strategy that buys low-accrual firms and shorts high-accrual firms earned roughly **10% per year** in abnormal returns. This is the founding paper of the **accrual anomaly**.

## What anomaly it documents

- **Predictor:** the accrual component of earnings (earnings minus cash flow from operations), scaled by total assets.
- **Direction:** *negative* — high accruals predict low future returns; low (or negative) accruals predict high future returns.
- **Mechanism:** accruals are more subjective and less persistent than cash flows. Investors who anchor on reported earnings overvalue high-accrual firms (whose earnings will mean-revert downward) and undervalue low-accrual firms.
- OSAP predictor: **Accruals**, classified **1_clear**.

## How to construct it

- **Sorting variable:** operating accruals via the balance-sheet method — the change in non-cash working capital minus depreciation and amortization, scaled by average total assets. (The later Hribar-Collins cash-flow-statement method is cleaner and avoids merger/divestiture contamination.)
- **Universe:** US nonfinancial firms with required Compustat items.
- **Portfolio formation:** annually, after financial statements are public (e.g., 3–4 months after fiscal year-end).
- **Long / short:** long the lowest-accrual decile, short the highest-accrual decile.
- **Weighting:** equal-weighted in the original; value-weighting substantially shrinks the effect.
- **Rebalancing:** annual.

## Evidence and replication

| Period | Sharpe (approx) | Ann. Return | T-stat | Source |
|--------|-----------------|-------------|--------|--------|
| IS (1962–1991) | ~0.7 | ≈10.4% hedge return | significant | this paper |
| OOS (post-1996) | declining | materially weaker | — | Green, Hand & Soliman 2011 |
| OSAP replication | clear, positive IS | — | — | Chen & Zimmermann 2022 |

- The original low-minus-high accrual hedge earned about **10.4% per year** in size-adjusted abnormal returns.
- The anomaly is a textbook **McLean-Pontiff** case: heavily published and then arbitraged. Green, Hand & Soliman (2011) document its decline as hedge-fund capital flowed in during the 2000s.
- Value-weighted and large-cap-only versions are much weaker — the effect leans on smaller firms.

## Why it might work

- **Earnings fixation / functional fixation (the thesis):** investors process the headline earnings number without decomposing its persistence, so they are systematically surprised when high-accrual earnings reverse. This is a mispricing story.
- **Limits to arbitrage:** the anomaly concentrates in smaller, costlier-to-trade, hard-to-short names, which is why it persisted before becoming widely known.
- **Risk-based alternatives:** weaker; some link accruals to investment/growth (the q-theory connection to asset growth), suggesting partial overlap with the investment factor rather than pure mispricing.

## Limitations and risks

- **Post-publication decay:** among the clearest examples of an anomaly shrinking after it was published and traded.
- **Small-cap dependence:** value-weighting and large-cap filters cut the premium sharply.
- **Measurement:** balance-sheet accruals are contaminated by mergers/divestitures; use the cash-flow-statement definition (Hribar-Collins 2002).
- **Turnover and shorting costs:** annual rebalance is manageable, but the short leg (high-accrual, often glamorous growth names) can be costly to borrow.
- **Overlap:** correlated with investment/asset-growth and external-financing anomalies.

## Key references

- Sloan, R. (1996) — *Do Stock Prices Fully Reflect Information in Accruals and Cash Flows About Future Earnings?* — The Accounting Review — DOI: 10.2308/tar-9608042309
- Hribar, P. & Collins, D. (2002) — *Errors in Estimating Accruals: Implications for Empirical Research* — Journal of Accounting Research
- Green, J., Hand, J. & Soliman, M. (2011) — *Going, Going, Gone? The Apparent Demise of the Accruals Anomaly* — Management Science
- Richardson, S., Sloan, R., Soliman, M. & Tuna, I. (2005) — *Accrual Reliability, Earnings Persistence and Stock Prices* — Journal of Accounting and Economics
- Chen, A. & Zimmermann, T. (2022) — *Open Source Cross-Sectional Asset Pricing* — Critical Finance Review
