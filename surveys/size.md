## TL;DR

Small-capitalization stocks historically out-earned large ones — the **size effect** (SMB) helped launch factor investing. But the standalone premium **largely disappeared after its 1981 publication**, is concentrated in illiquid microcaps and in January, and today survives mostly as a **conditioning variable**: it reappears once you control for quality/junk, and it amplifies other anomalies among small names.

## A 40-year arc

- **Banz (1981)** — the founding result: small firms earn higher risk-adjusted returns than the CAPM predicts.
- **Fama & French (1992, 1993)** — size becomes a canonical factor (SMB) in the 3-factor model.
- **Post-publication decay** — the standalone size premium weakened sharply after 1981; many argued the "size effect is dead," driven by microcaps, January, and survivorship/data issues.
- **Asness, Frazzini, Israel, Moskowitz & Pedersen (2018)** — *Size Matters, If You Control Your Junk*: size revives strongly once you neutralize quality, because small firms are disproportionately junk.

## Sub-threads

Standalone small-minus-big · the **January/turn-of-year** concentration · microcap vs all-cap construction · size as a **conditioning** variable (anomalies are larger among small stocks) · size-within-quality.

## Why it works (or did)

- **Risk-based** — small firms carry distress, illiquidity, and information risk.
- **Microstructure / data** — much of the raw premium is a microcap, illiquidity, and January artifact.
- **Quality confound** — small firms skew toward low-quality "junk"; controlling for quality restores a clean size premium (AFIMP).

## The dark side

- **Mostly gone standalone** — realized SMB has been near zero for decades in large/all-cap universes.
- **Illiquidity & capacity** — the premium lives in tiny, costly-to-trade names.
- **Fragility** — sensitive to universe (microcap inclusion), weighting, and the January effect.

## Does it survive out of sample?

The standalone size premium is the **most contested** of the classic factors — largely vanished out of sample on its own, but it returns conditionally (within-quality) and as a risk amplifier. Our **[replications](/replications)** recompute SMB from Ken-French building blocks and score it on the holdout.

## Run it yourself

- **[Replications](/replications)** — Fama-French SMB.
- **[Curriculum](/curriculum)** — the synthetic market ships a `size_cap` characteristic; the cost-of-trading mission shows why microcap-concentrated premia are hard to harvest net of costs.
- **[Playground](/playground)** / **[Competitions](/compete)** — build a size-conditioned signal and score it OOS.
