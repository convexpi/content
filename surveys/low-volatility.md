## TL;DR

Contrary to the CAPM, **low-risk** stocks (low beta, low volatility, low idiosyncratic vol) have earned returns as high as — or higher than — high-risk stocks, on a far better risk-adjusted basis. The "low-risk anomaly" is really a family of closely related effects (beta, volatility, lottery), and it is one of the most robust and most-exploited anomalies in practice.

## A 30-year arc

- **Black (1972); Haugen & Heins (1975)** — early evidence that the security market line is too flat.
- **Ang, Hodrick, Xing & Zhang (2006)** — the **idiosyncratic-volatility puzzle**: high-idio-vol stocks earn "abysmally low" returns (5-1 spread ≈ −1.06%/mo), which diversifiable risk shouldn't command.
- **Baker, Bradley & Wurgler (2011)** — *Benchmarks as Limits to Arbitrage*: an agency/benchmarking story for why the anomaly persists.
- **Bali, Cakici & Whitelaw (2011)** — the **MAX** effect: stocks with extreme recent daily returns (lottery tickets) are overpriced and underperform.
- **Frazzini & Pedersen (2014)** — **Betting Against Beta**: leverage-constrained investors bid up high-beta assets; a beta-neutral long-low/short-high book earns alpha.

## Sub-threads (the low-risk family)

Low beta (BAB) · total volatility · idiosyncratic volatility · the MAX / lottery effect. They are tightly correlated — a single "low-risk" complex viewed through different lenses.

## Why it works

- **Leverage constraints** (Frazzini-Pedersen) — investors who can't lever overweight high-beta stocks, flattening the SML.
- **Lottery preferences** (Bali et al.) — some investors overpay for high-skew "lottery" stocks, depressing their returns.
- **Limits to arbitrage / benchmarking** (Baker-Bradley-Wurgler) — fixed-benchmark managers won't underweight high-vol names, and shorting them is costly.

## The dark side

- **Specification sensitivity** — results depend on the vol measure, weighting, and microcap screens (Bali-Cakici critique).
- **Short-leg costs** — profits lean on shorting hard-to-borrow, high-vol names.
- **Crowding & rate sensitivity** — "defensive equity" became a popular product; low-vol stocks behave like bond proxies and can suffer when rates rise.

## Does it survive out of sample?

The low-risk anomaly is robust but compressed by popularity; BAB and idio-vol replicate, though the standalone idio-vol effect is sensitive to construction. Our **[replications](/replications)** recompute Betting-Against-Beta, idiosyncratic volatility, and the MAX effect, scored on the holdout.

## Run it yourself

- **[Replications](/replications)** — Frazzini-Pedersen BAB, Ang et al. idiosyncratic volatility, Bali-Cakici-Whitelaw MAX.
- **[Curriculum](/curriculum)** — the synthetic market ships a planted `vol_1m` factor (and the realistic-exchange missions cover how volatility shows up in microstructure).
- **[Playground](/playground)** / **[Competitions](/compete)** — build a low-risk signal and score it OOS.
