## TL;DR

Past losers tend to rebound — but **reversal is two different phenomena** at two horizons. **Short-term** (1-week to 1-month) reversal is largely **liquidity provision / microstructure** and is high-turnover. **Long-term** (3–5 year) reversal is the **overreaction** story that helped found behavioral finance — and largely overlaps the value premium. Conflating them is a common error.

## A 40-year arc

- **De Bondt & Thaler (1985)** — *long-term* reversal: extreme 3–5-year losers outperform winners over the next 3–5 years; evidence of **overreaction**.
- **Jegadeesh (1990); Lehmann (1990)** — *short-term* reversal: last month's losers beat last month's winners next month.
- **Jegadeesh & Titman (1993, 2001)** — momentum sits *between* the two reversals (3–12 months), and only a partial long-horizon reversal appears at years 4–5.
- Microstructure work — short-term reversal is tied to **bid-ask bounce, inventory, and the price of immediacy**, not mispricing per se.

## Sub-threads

Short-term (1-week / 1-month) reversal · long-term (3–5 year) reversal · the momentum "sandwich" between them · industry/sector reversal.

## Why it works

- **Short-term** — compensation for providing **liquidity**: market makers and contrarians earn the spread/immediacy premium as transient price pressure reverses.
- **Long-term** — **overreaction**: investors extrapolate good/bad news too far, then prices mean-revert (De Bondt-Thaler); this is largely the **value** effect at long horizons.

## The dark side

- **Short-term reversal is costly** — its gross Sharpe is high but turnover is enormous; net of transaction costs much of it is really the *liquidity-provision* return, not free alpha.
- **Long-term reversal ≈ value** — little marginal alpha after controlling for book-to-market.
- **Microstructure noise** — short-horizon results are sensitive to bid-ask bounce and stale prices.

## Does it survive out of sample?

Short-term reversal persists **gross** but is marginal **net of costs** (it's a liquidity-provision strategy); long-term reversal persists but is largely subsumed by value. Our **[replications](/replications)** recompute both short-term and long-term reversal and score them on the holdout.

## Run it yourself

- **[Replications](/replications)** — Jegadeesh short-term reversal, De Bondt-Thaler long-term reversal.
- **[Curriculum](/curriculum)** — the synthetic market ships a `reversal_1w` factor; Mission 9 (pairs trading) covers the mean-reversion machinery; the cost-of-trading mission shows why short-term reversal is so cost-sensitive.
- **[Playground](/playground)** / **[Competitions](/compete)** — build a reversal signal and score it net of costs.
