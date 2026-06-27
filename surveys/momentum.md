## TL;DR

Over horizons of roughly **3–12 months**, stocks that recently outperformed keep outperforming and recent losers keep lagging. A long-winners / short-losers portfolio has historically earned on the order of **1% per month**, and the pattern appears in nearly every market and asset class — one of the most robust anomalies in finance. The catch: momentum is **crash-prone**, high-turnover, and concentrated in the hardest-to-arbitrage corners of the market.

## A 30-year arc

- **Jegadeesh & Titman (1993)** — the founding result: buying past 3–12-month winners and shorting losers earns ~1%/month over the next 3–12 months, unexplained by market risk.
- **Chan, Jegadeesh & Lakonishok (1996)** — price momentum *and* earnings-surprise drift (PEAD) each predict returns, additively (the strongest sort ~1.74%/mo). Frames momentum as **underreaction to information**.
- **Rouwenhorst (1998); Asness, Moskowitz & Pedersen (2013)** — momentum is pervasive: across international equities and, in *Value and Momentum Everywhere*, across asset classes (with value as its negative correlate).
- **Moskowitz & Grinblatt (1999)** — much of individual momentum is really **industry momentum**.
- **George & Hwang (2004)** — nearness to the **52-week high** forecasts returns better than past returns (~1.06%/mo vs JT 0.38% / MG 0.25%) and does not reverse.
- **Jegadeesh & Titman (2001)** — profits persist out of sample; only a partial reversal appears, at years 4–5.
- **Novy-Marx (2012)** — momentum is "**echo**": the intermediate horizon (months t-12 to t-7) drives it, not the most recent months.
- **Blitz, Huij & Martens (2011)** — **residual** (factor-neutral) momentum is smoother and less crash-exposed.
- **Moskowitz, Ooi & Pedersen (2012)** — **time-series (trend) momentum**: an asset's own past return predicts its future, across futures markets.
- **Daniel & Moskowitz (2016)** — **momentum crashes**: rare, severe drawdowns in panic-rebound markets.
- **Avramov, Chordia, Jostova & Philipov (2007)** — momentum lives almost entirely in **low-credit-quality** firms (under 4% of rated market cap).

## Sub-threads (the momentum family)

Cross-sectional **price momentum** (Jegadeesh-Titman) · **earnings momentum / PEAD** · **52-week-high** · **intermediate / echo** · **residual** · **industry** · **time-series / trend** · **cross-asset**. They overlap heavily but are not identical — a momentum-aware book treats them as one correlated complex.

## Why it works

The consensus channel is **behavioral underreaction**: investors and analysts absorb news gradually. Hong & Stein model gradual information diffusion; Daniel, Hirshleifer & Subrahmanyam attribute initial underreaction (then delayed overreaction) to overconfidence and self-attribution; Barberis, Shleifer & Vishny invoke conservatism and representativeness. Risk-based explanations exist but struggle to span both momentum's magnitude and its crash profile.

## The dark side

- **Crashes** — momentum suffers rare, severe losses when beaten-down stocks rebound (1932, 2009); the unconditional Sharpe hides a fat left tail.
- **Turnover & costs** — monthly rebalancing makes momentum one of the most cost-sensitive factors (see the [cost-of-trading mission](/curriculum)).
- **Concentration & capacity** — profits cluster in small, illiquid, low-rated names that are hard to short, limiting capacity.

## Does it survive out of sample?

McLean & Pontiff (2016) find published anomalies decay ~30–58% post-publication; momentum is among the **more durable** and remains positive out of sample. Our **[replications](/replications)** recompute the canon from building blocks and score it on the holdout — see Jegadeesh-Titman cross-sectional momentum, industry momentum, time-series momentum, and asset-class momentum.

## Run it yourself

- **[Curriculum](/curriculum)** — Mission 1 uses a planted momentum signal to teach the overfitting trap; the Lab's synthetic market ships `mom_1m / mom_3m / mom_12m` factors.
- **[Playground](/playground)** — prototype a momentum signal in the browser.
- **[Competitions](/compete)** — submit a momentum strategy and see it scored out of sample.
