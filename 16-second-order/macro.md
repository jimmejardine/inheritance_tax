# Macroeconomic Effects

**Executive summary.** In general equilibrium the policy's macro effects are smaller and more ambiguous than either side's rhetoric: the aggregate capital stock probably changes little (bequest-motivated accumulation falls, but the endowment, annuitisation, and state-fund channels recycle the same resources), labour supply nets slightly positive, and the entrepreneurship effect is a genuinely disputed sign. The strongest macro claims the manifesto can honestly make are distributional (r-vs-g dynamics truncated) and fiscal (steady-state room to cut taxes on work); everything else needs the modelling agenda at the end of this file.

## 1. Does aggregate capital fall?

The folk objection — "a 100% tax destroys the capital stock" — decomposes into channels that partly cancel:

| Channel | Direction for K | Assessment |
|---|---|---|
| Bequest-motivated accumulation above threshold falls | Down | Real but bounded: intentional dynastic bequests are concentrated in a thin tail, and the Kotlikoff–Summers vs Modigliani dispute (inherited share of wealth ~20% vs ~80%) shows the aggregate importance is unresolved [1] |
| Late-life consumption rises | Down | Medium confidence, small aggregate ([savings-consumption.md](savings-consumption.md) §3) |
| Capital flight at the margin | Down | Bounded by exit-tax and situs design; evidence reviewed in [`../08-capital-flight/evidence.md`](../08-capital-flight/evidence.md) suggests migration elasticities are modest for all but the most mobile fortunes (to verify) |
| Endowment recapitalises the young | Up | £35bn/yr delivered to the cohort with the highest marginal returns to capital (education, housing, business entry — [endowment-effects.md](endowment-effects.md)) |
| Annuitisation deepens capital markets | Up / neutral | Insurance reserves are invested, long-duration ([savings-consumption.md](savings-consumption.md) §2) |
| State fund holds receipts in-specie | Neutral for K, changes ownership | Assets are transferred, not consumed — unless fiscal rules let the flow leak into current spending; hence the statutory hypothecation in [`../02-proposal/endowment.md`](../02-proposal/endowment.md) |
| Charitable diversion | Neutral for K | Foundation endowments remain invested ([charitable-giving.md](charitable-giving.md)) |

**Net judgement:** small change in the *level* of K, low confidence on sign; high confidence on a large change in *composition and ownership* — from dynastic passive holdings toward young households, insurance institutions, foundations, and the state fund. The abolition-wave record is consistent: no measurable investment or growth response in either direction to inheritance-tax changes at historical rates ([`../05-history/abolitions.md`](../05-history/abolitions.md)), though a 100% rate is out of the historical support — extrapolation humility is required.

## 2. r vs g feedback

[`../03-case-for/piketty-r-vs-g.md`](../03-case-for/piketty-r-vs-g.md) makes the structural case; here the general-equilibrium feedbacks:

- The tax operates directly on the *transmission term* in wealth-distribution dynamics (Piketty–Zucman; Benhabib–Bisin–Zhu models, where inheritance and its taxation govern the Pareto tail of the wealth distribution [2]). Even with r, g unchanged, truncating transmission at £500k per recipient caps the number of generations over which r > g can compound in one bloodline at exactly one.
- Effects *on* r: if aggregate K is roughly stable (§1), r moves little. Higher asset turnover ([asset-prices.md](asset-prices.md)) and relief-premium unwinds change relative returns, not the aggregate.
- Modest downward pressure on r is plausible if annuitisation and the state fund raise effective capital supply to markets; this would compress r − g slightly — a second-order reinforcement of the policy's own goal, not to be leaned on.

## 3. Interest rates and public finance

The state fund accumulates and the endowment disburses; net government balance-sheet effects depend on the transition path ([`../15-transition/revenue-bridge.md`](../15-transition/revenue-bridge.md)). Steady state: receipts (£40–70bn/yr on the estimates in [`../02-proposal/endowment.md`](../02-proposal/endowment.md), to verify) fund a £35bn endowment obligation with surplus. Demand for long gilts rises via annuity reserves. Nothing here moves policy rates materially; claims of macro-financial disruption lack a mechanism at these magnitudes.

## 4. Entrepreneurship: the disputed sign

| Force | Direction | Evidence base |
|---|---|---|
| Capital constraints relaxed at 25, universally | Up | Liquidity-constraint literature: Evans–Jovanovic; Blanchflower–Oswald ("what makes an entrepreneur? — capital"); Holtz-Eakin et al. inheritance-and-self-employment studies [3] |
| Bequest-motive dampening for older founders ("why build if I can't pass it on?") | Down | Weakest evidence base of any channel — the bequest-motive elasticity of *founding effort* is essentially unmeasured; [`../04-case-against/bequest-motive.md`](../04-case-against/bequest-motive.md) steelmans it; founder motivation research consistently ranks autonomy, mastery, and competitive drive above dynastic transmission (to verify) |
| Heir-financed ventures above threshold close | Down (small) | [heirs-and-work.md](heirs-and-work.md) §4 |
| Succession-driven sales create acquisition and MBO deal-flow | Up (small) | §1 of [dynasties-and-power.md](dynasties-and-power.md) |

**Net: sign disputed; timing argues up.** The policy moves capital access from age ~55-by-luck to age 25-for-all. If entrepreneurship responds to capital at formation age more than to transmission rights at exit age — which the liquidity-constraint literature supports and the bequest-motive literature cannot contradict — the net is positive, but this is the single macro parameter most in need of the modelling agenda below.

## 5. Labour supply

Netting the section's findings: heirs of large fortunes work more ([heirs-and-work.md](heirs-and-work.md) — high confidence, small population, high-productivity labour); endowment recipients work slightly less in hours and invest more in education ([endowment-effects.md](endowment-effects.md) §3 — small per person, large population); expectation effects raise mid-career effort from announcement. Plausible net: slightly positive in effective labour, near-zero in hours (to verify by simulation). No credible channel produces a large decline.

## 6. Optimal-tax theory and fiscal general equilibrium

The Piketty–Saez optimal inheritance-tax framework (2013) delivers optimal rates of 50–60% for middle-class-welfare-weighted social objectives, rising to 70–80%+ when weights concentrate on those who inherit nothing (to verify parameters) [4]. Farhi–Werning reach lower rates under different assumptions about parental altruism internalisation [5]. The proposal's 0/100 kink is an implementable approximation to the high end of this range: the generous threshold delivers the progressivity that the theory's declining marginal weights require, while the 100% rate above it prices dynastic transmission at the level the zero-weight-on-rentiers case implies. This is squarely within, not beyond, the published theory — a point [`../03-case-for/economic-efficiency.md`](../03-case-for/economic-efficiency.md) develops.

**What taxes can fall.** Steady-state surplus (receipts minus endowment cost) plus the efficiency ranking of taxes (transfer taxes among the least distortive per pound — Mirrlees Review hierarchy, to verify [6]) creates room to cut the most distortive margins:

| Candidate cut | Rationale |
|---|---|
| Employee NI / payroll taxes on the young | Directly complements the endowment's life-cycle rebalancing |
| Basic-rate income tax | The legible "tax work less, tax windfalls more" swap — the core fiscal narrative in [`../14-communications/narratives.md`](../14-communications/narratives.md) |
| Stamp duty (UK) | Compounds the housing-turnover gains of [asset-prices.md](asset-prices.md) |

The political economy of naming the tax cut alongside the endowment is developed in [`../06-palatability/framing.md`](../06-palatability/framing.md).

## 7. The modelling agenda

Honesty about what is currently unmodelled, in priority order:

1. **Micro-simulation** of receipts, threshold incidence, and revenue on ONS WAS / SCF data — replaces the back-of-envelope in [`../02-proposal/thresholds.md`](../02-proposal/thresholds.md).
2. **OLG general-equilibrium model** with bequest motives, the endowment, and the annuity channel — the K and r questions of §§1–2; existing inheritance-tax OLG work (e.g. in the Piketty–Saez tradition [4]) provides the chassis.
3. **Wealth-distribution dynamics** (Benhabib–Bisin–Zhu calibration) — how fast does the Pareto tail compress under transmission truncation? [2]
4. **Entrepreneurship module** — the §4 sign question; calibrate the age-25 capital-access elasticity against the liquidity-constraint literature.
5. **Announcement and transition stress tests** — behavioural front-running scenarios feeding [`../15-transition/sequencing.md`](../15-transition/sequencing.md).
6. **Charitable-diversion sensitivity** — revenue under the [charitable-giving.md](charitable-giving.md) §2 scenarios.

## Sources

1. Kotlikoff, L. & Summers, L. (1981); Modigliani, F. (1988) — the inherited-wealth-share debate
2. Benhabib, J., Bisin, A. & Zhu, S. — "The Distribution of Wealth and Fiscal Policy in Economies with Finitely Lived Agents," *Econometrica* (2011); Piketty, T. & Zucman, G., *Handbook of Income Distribution* chapter (2015) (to verify)
3. Evans, D. & Jovanovic, B., *JPE* (1989); Blanchflower, D. & Oswald, A., *Journal of Labor Economics* (1998); Holtz-Eakin, Joulfaian & Rosen, *JPE* (1994)
4. Piketty, T. & Saez, E. — "A Theory of Optimal Inheritance Taxation," *Econometrica* (2013)
5. Farhi, E. & Werning, I. — "Progressive Estate Taxation," *QJE* (2010) (to verify)
6. Mirrlees Review, *Tax by Design* (IFS/OUP, 2011)
