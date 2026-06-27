## TL;DR

Buying stocks that are **cheap** relative to fundamentals (book, earnings, cash flow, sales) and shorting **expensive** "glamour" stocks has earned a long-run premium across markets and centuries. It is the oldest and most-studied anomaly — but it is slow, cyclical, and endured a brutal **2007–2020 drawdown** that reopened every debate about why it works and whether it still does.

## A long arc

- **Graham & Dodd (1934)** — the intellectual root: buy below intrinsic value with a margin of safety.
- **Basu (1977)** — the first rigorous cross-sectional test: low-P/E (high earnings-yield) stocks earn higher risk-adjusted returns.
- **Fama & French (1992, 1993)** — **book-to-market** is a dominant return predictor; HML becomes a canonical factor.
- **Lakonishok, Shleifer & Vishny (1994)** — *Contrarian Investment, Extrapolation, and Risk*: value works because investors **over-extrapolate** past growth, not because value is riskier.
- **Penman, Richardson & Tuna (2007)** — decompose book-to-price into an operating and a leverage component with opposite signs.
- **Novy-Marx (2010)** — operating leverage explains why value is strong **within** industries but weak across them.
- **Zhang (2005); Fama & French (2015)** — risk/q-theory accounts and the CMA/HML link.

## Sub-threads (how cheapness is measured)

Book-to-market · earnings-yield (E/P) · cash-flow-yield (CF/P) · dividend-yield (D/P) · sales-to-price · enterprise multiple (EV/EBITDA) · intrinsic value-to-price (residual income) · payout yield. They are correlated lenses on the same premium; each has its own data quirks and overlaps.

## Why it works

- **Behavioral (extrapolation)** — LSV's evidence: the market extrapolates glamour firms' growth too far and underprices beaten-down value firms.
- **Risk-based** — value firms may carry distress, duration, or operating-leverage risk (q-theory). The two camps remain unresolved; the truth is likely a mix.

## The dark side

- **The value drought** — value underperformed growth for ~2007–2020, the worst stretch on record, stress-testing every rationale.
- **Intangibles mismeasurement** — expensing R&D/brand depresses book value, making intangible-rich firms look spuriously "expensive" (see R&D and book-to-price work).
- **Overlap & crowding** — value correlates with profitability, leverage, and size; raw cheapness without a quality screen invites value traps.

## Does it survive out of sample?

Value is the canonical factor and remains positive over the long run, though the recent drawdown lowered realized Sharpe and revived the "is value dead?" debate; intangible-adjusted value measures fared better. Our **[replications](/replications)** recompute HML, earnings-yield, cash-flow-yield and dividend-yield from building blocks and score them on the holdout (note dividend-yield reads **dormant**).

## Run it yourself

- **[Curriculum](/curriculum)** — the Lab's synthetic market ships a planted `val_bm` factor; combine it with momentum in the "momentum + value survives" example.
- **[Replications](/replications)** — Fama-French HML, Basu E/P, Lakonishok CF/P, Litzenberger-Ramaswamy D/P.
- **[Playground](/playground)** / **[Competitions](/compete)** — build and score your own value signal.
