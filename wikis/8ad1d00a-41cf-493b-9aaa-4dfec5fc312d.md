# Risk, Return, and Equilibrium: Empirical Tests

**Source:** Fama & MacBeth (1973) · Journal of Political Economy · DOI: 10.1086/260061

## TL;DR

This paper does two enduring things: (1) it introduces the **Fama-MacBeth two-pass cross-sectional regression**, now the workhorse method for testing whether a characteristic is priced; and (2) it provides the canonical early test of the CAPM, finding a positive, roughly linear relation between market beta and average return over 1926–1968, with no extra role for non-beta risk. The methodology outlived the result — Fama & French (1992) later showed the beta-return relation is essentially flat.

## What it documents

- **Methodological contribution (the lasting one):** estimate betas in a first pass, then in each time period run a cross-sectional regression of returns on betas; the time series of the period-by-period slope estimates gives both the average risk premium and a valid t-statistic that accounts for cross-sectional correlation. This "FM regression" is how virtually every cross-sectional asset-pricing claim is now tested.
- **Empirical finding (since overturned):** over the full 1926–1968 sample, average returns rise with beta, the relation is approximately linear, and squared beta and idiosyncratic volatility add no explanatory power — consistent with the Sharpe-Lintner-Black CAPM at the time.
- OSAP predictor: **Beta** (sorting stocks on market beta).

## How to construct it

The FM test (not a tradeable factor per se):

- **First pass:** estimate each stock's (or portfolio's) market beta from a time-series regression of excess returns on the market excess return over an estimation window.
- **Second pass:** for each month t, run a cross-sectional regression: R_{i,t} = γ_{0,t} + γ_{1,t}·β_i + (other characteristics) + e_{i,t}.
- **Inference:** average the monthly γ estimates; the t-stat is the mean slope divided by the standard error of the time series of slopes. A nonzero average γ_1 means beta is priced.
- **Portfolio grouping:** the paper sorts stocks into beta-ranked portfolios to mitigate the errors-in-variables problem from estimating individual betas.

For the "Beta" anomaly itself: sort stocks on estimated beta and form high-minus-low-beta portfolios — though see the BAB literature, which shows the *low*-beta end is the one with positive alpha.

## Evidence and replication

| Period | Finding | Source |
|--------|---------|--------|
| IS (1926–1968) | positive, ~linear beta-return relation; no residual-risk effect | this paper |
| Post-1963 re-examination | beta-return relation **flat** once size/value controlled | Fama & French 1992 |
| Modern (leverage constraints) | low-beta has positive alpha — the SML is *too flat* | Frazzini-Pedersen 2014 |
| OSAP (Beta) | weak / not significant standalone premium | Chen & Zimmermann 2022 |

- The 1973 result was the high-water mark of CAPM empirical support. The same FM methodology was later turned against the CAPM: Fama & French (1992) used cross-sectional regressions to show beta has no marginal explanatory power once size and book-to-market are included.
- Modern work (Betting Against Beta) goes further — the security market line is *flatter* than the CAPM predicts, so high beta is actually associated with *lower* risk-adjusted returns, the opposite of a positive beta premium.

## Why it matters

- **As methodology:** the FM regression is foundational infrastructure — almost every "is factor X priced?" question in this library is answered with some variant of it. Understanding its two-pass structure and the errors-in-variables and portfolio-grouping issues is core to reading empirical asset pricing.
- **As intellectual history:** it documents the CAPM's empirical peak, making the subsequent flat-beta and betting-against-beta findings the central cautionary tale about how a "confirmed" relation can reverse out of sample.

## Limitations and risks

- **Errors-in-variables:** individual betas are estimated with noise, biasing second-pass slopes toward zero; portfolio grouping helps but introduces its own choices.
- **Beta instability:** betas vary over time, so first-pass estimates are stale.
- **The result didn't hold:** the positive beta-return relation is the textbook example of an in-sample finding that failed out of sample — treat the empirical conclusion as historical, not actionable.
- **No free full text:** paywalled; see DOI.

## Key references

- Fama, E. & MacBeth, J. (1973) — *Risk, Return, and Equilibrium: Empirical Tests* — Journal of Political Economy — DOI: 10.1086/260061
- Fama, E. & French, K. (1992) — *The Cross-Section of Expected Stock Returns* — Journal of Finance
- Frazzini, A. & Pedersen, L. (2014) — *Betting Against Beta* — Journal of Financial Economics
- Black, F., Jensen, M. & Scholes, M. (1972) — *The Capital Asset Pricing Model: Some Empirical Tests*
- Chen, A. & Zimmermann, T. (2022) — *Open Source Cross-Sectional Asset Pricing* — Critical Finance Review
