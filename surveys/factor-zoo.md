## TL;DR

The cross-sectional literature has produced **hundreds** of published "factors," but a large share fail to replicate, decay sharply after publication, or vanish under honest multiple-testing corrections. This meta-literature — on p-hacking, out-of-sample validation, and what actually survives — is the intellectual core ConvexPi is built around.

## A 30-year arc

- **Fama & French (1993, 2015)** — the 3- and 5-factor models that organized the field.
- **Harvey, Liu & Zhu (2016)** — *…and the Cross-Section of Expected Returns*: catalog **~316 factors** and argue the right t-stat hurdle, after multiple testing, is closer to **3.0** than 2.0.
- **McLean & Pontiff (2016)** — published anomalies decay **~30–58%** post-publication, evidence that much "alpha" is statistical and/or arbitraged away.
- **Hou, Xue & Zhang (2015, 2020)** — *Digesting Anomalies* / the replication study: many anomalies are insignificant once microcaps are handled properly; propose the **q-factor** model.
- **Chen & Zimmermann (2022)** — *Open Source Cross-Sectional Asset Pricing*: a transparent, reproducible anomaly dataset (the OSAP project our replications validate against).
- **Bailey & López de Prado (2014)** — the **Deflated Sharpe Ratio**: adjust performance for the number of trials.
- **Feng, Giglio & Xiu (2020); Kozak, Nagel & Santosh (2020); Kelly, Pruitt & Su (2019); Gu, Kelly & Xiu (2020)** — taming the zoo with ML/shrinkage (Lasso factor selection, sparse SDFs, IPCA, deep learning).

## Sub-threads

Multiple-testing corrections · post-publication decay · replication failures & microcap effects · the deflated Sharpe ratio · ML/shrinkage for factor selection · open, reproducible datasets.

## Why it matters

A factor "discovered" by scanning thousands of candidates needs a far higher bar than one tested once — otherwise you publish noise. The corrections (higher t-hurdles, FDR, deflated Sharpe), the discipline (true out-of-sample / walk-forward), and the antidote (transparent, clean-room replication) are what separate durable signal from the zoo.

## The dark side

- **Data mining at scale** — cheap compute + many datasets manufacture spurious factors faster than they can be vetted.
- **Publication & survivorship bias** — only the winning specification gets published; failures stay in the drawer.
- **Fragility** — small changes in universe, weighting, or sample flip many "anomalies."

## Does it survive out of sample?

This *is* the "does it survive" topic. The honest answer: a minority of the zoo survives rigorous OOS testing — momentum, value, profitability/quality, and the low-risk family are among the more durable; many accounting/microstructure anomalies have decayed. Our **[replications](/replications)** recompute the canon clean-room and score every one on the holdout (the **McLean-Pontiff test**), and the **[anomaly graveyard](/anomalies)** tracks what died.

## Run it yourself

- **[Curriculum](/curriculum)** — Mission 1 makes you *feel* overfitting; Mission 3 (alpha discovery) drills multiple-testing, FDR, and walk-forward validation; Mission 8 covers transaction-cost erosion.
- **[Replications](/replications)** — the clean-room antidote: idea + DOI, recomputed and OOS-scored.
- **[Competitions](/compete)** — graded on out-of-sample Sharpe, because in-sample curve-fitting won't save you.
