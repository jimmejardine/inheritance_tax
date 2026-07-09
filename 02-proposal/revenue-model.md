# Revenue Model

**Executive summary.** The fiscal arithmetic of the proposal is presented here without varnish: at current UK inheritance-and-gift flows of roughly £100bn a year (to verify), a £500k-per-recipient lifetime threshold yields a pre-behavioural gross base of perhaps £30–40bn a year, which behavioural attrition — dispersal, charitable diversion, consumption, avoidance, and payment deferral — plausibly cuts to £12–25bn in early steady state, against an endowment cost of ~£35bn a year. The gap is real, it is bridgeable ([`../15-transition/revenue-bridge.md`](../15-transition/revenue-bridge.md)), and — crucially — it is not the test of the policy's success: the dynastic break occurs whether the money arrives as revenue or dissolves as dispersal.

## Key findings

- UK aggregate annual inheritance flow is ~£100bn and projected by the IFS to roughly double in real terms by the 2040s (to verify against latest IFS/ONS wealth-transfer estimates) [1]. Gift flows on top of bequests are poorly measured and add an uncertain increment (to verify) [2].
- IFS distributional work implies ~30–40% of the aggregate flow sits above £500k per recipient — an illustrative order-of-magnitude inference from the shape of the wealth distribution, not a published statistic (see §2 and [`thresholds.md`](thresholds.md) §4) [1].
- Behavioural attrition is large by design: every pound the tax "loses" to wider dispersal or charitable giving is the policy working, not failing (§4).
- The universal endowment costs ~£35bn/year in the UK (illustrative: ~700,000 people turning 25 × £50,000 [3]) and ~$260bn/year in the US (illustrative: ~4.3m turning 25 × $60,000 — cohort size to verify against Census data [4]).
- Existing UK IHT raises ~£7.5–8bn/year (HMRC receipts, 2023–24 to 2024–25 — to verify) [5]; even the pessimistic end of our net-revenue range is roughly double that.
- Early years run a funding deficit; mature years (2040s flows) plausibly run a surplus. The bridge options are set out in [`../15-transition/revenue-bridge.md`](../15-transition/revenue-bridge.md).
- Politically, the number that matters is "is my endowment funded?"; structurally, the number that matters is the share of dynastic wealth that fails to reach a single concentrated heir — which rises even as measured revenue falls (§8; [`../09-objections/spend-it-all.md`](../09-objections/spend-it-all.md)).

## 1. The flow: what passes each year

The tax base is the annual flow of gratuitous transfers — bequests plus inter-vivos gifts — not the stock of wealth. UK anchors:

| Quantity | Estimate | Status |
|---|---|---|
| Annual UK inheritance flow (bequests) | ~£100bn | IFS projection basis; to verify against latest release [1] |
| Projected flow, 2040s | ~£200bn (real) | IFS; driven by baby-boomer housing and pension wealth [1] |
| Annual inter-vivos gift flow | Poorly measured; material | HMRC only observes gifts that fail the 7-year rule; survey data (WAS) undercounts (to verify) [2] |
| Existing IHT take | ~£7.5–8bn/yr | HMRC receipts (to verify) [5] |
| Effective rate of current IHT on the flow | ~7–8% | Illustrative division of the two rows above |

The last row is the headline indictment of the status quo: a nominally 40% tax collects an effective single-digit share of the flow, because reliefs, exemptions, and planning hollow it out — the incidence pattern that [`avoidance.md`](avoidance.md) is designed to invert.

## 2. Share above the threshold — order-of-magnitude reasoning

No published series measures cumulative lifetime receipts per recipient, so this is inference, clearly labelled **illustrative** throughout. The reasoning: inheritance flows inherit the shape of the wealth distribution they drain, and UK wealth is heavily top-concentrated (top 10% of households hold ~43–50% of wealth — ONS WAS, to verify [6]). IFS work on inheritances received puts the 90th percentile of individual receipts near £280k [1], and estates above £1m — a small percent of deaths — account for a disproportionate share of the aggregate flow. Chaining these:

- If the top ~5% of recipients receive ~40–50% of the flow (consistent with the US finding that the top 1% of heirs receive over 40% [7]), and
- the £500k threshold exempts the first £500k *of each of them*,

then the taxable slice is plausibly **30–40% of the aggregate flow**, i.e. **£30–40bn/year gross at current flows, £60–80bn at 2040s flows** (illustrative). [`thresholds.md`](thresholds.md) §6 tabulates the sensitivity to other thresholds. Proper micro-simulation on cumulative lifetime receipts remains the top item in the [README's](README.md) "what still needs doing" list.

## 3. Gross-to-net waterfall

| Step | Effect on base (illustrative) | Note |
|---|---|---|
| Pre-behavioural gross base | £30–40bn/yr | §2 |
| Spousal exemption timing | defers a large minority of the base ~10 yrs | Tax arrives at second death, not first; a delay, not a loss ([`carveouts.md`](carveouts.md) §1) |
| Distributive estate planning | −20–40% of gross | Splitting estates across more recipients is the *intended* response ([`thresholds.md`](thresholds.md) §7) |
| Charitable diversion | −5–15% of gross | See sensitivity §4; [`../16-second-order/charitable-giving.md`](../16-second-order/charitable-giving.md) |
| Lifetime consumption response | −5–15% of gross | [`../16-second-order/savings-consumption.md`](../16-second-order/savings-consumption.md); [`../09-objections/spend-it-all.md`](../09-objections/spend-it-all.md) |
| Avoidance and flight residual | −5–15% of gross | After the [`avoidance.md`](avoidance.md) spine; evidence base in [`../08-capital-flight/evidence.md`](../08-capital-flight/evidence.md) |
| Business/farm deferral | smooths ~10–20% of receipts over 30 yrs | Cash-flow timing, plus interest income ([`carveouts.md`](carveouts.md) §5–6) |
| **Net near-term steady state** | **~£12–25bn/yr** | Central planning range |
| **Net at 2040s flows** | **~£25–50bn/yr** | Same attrition shares on the doubled flow |

**Reconciling the repo's own spread.** [`thresholds.md`](thresholds.md) §4 estimates £10–25bn; [`endowment.md`](endowment.md) §7 cites £40–70bn. The difference is almost entirely (a) which decade's flow is assumed and (b) how much behavioural attrition is loaded in. This file adopts the conservative near-term range and treats the higher figures as the mature-flow case. Planning should be done on the conservative number; that discipline is itself a defence against the over-promising that invites later sabotage ([`constitutional-design.md`](constitutional-design.md)).

## 4. Behavioural attrition — sensitivity lines

Each channel, with its sensitivity to being wrong (all illustrative, on a £35bn gross base at current flows):

| Channel | Assumption | Sensitivity |
|---|---|---|
| Dispersal to more recipients | 20–40% of gross | Each additional 10pp of dispersal removes ~£3.5bn/yr — and disperses ~£3.5bn of dynastic wealth, the policy goal |
| Charitable diversion | 5–15% | Each 10pp diverted removes ~£3.5bn/yr from revenue and adds it to the charitable sector; anti-cycling rules in [`carveouts.md`](carveouts.md) §4 keep it genuinely public-benefit |
| Consumption ("spend it all") | 5–15% | Each 10pp removes ~£3.5bn/yr and returns it to the economy as demand, partly recouped via VAT/income tax (to verify recoupment share); see [`../09-objections/spend-it-all.md`](../09-objections/spend-it-all.md) |
| Avoidance/flight residual | 5–15% | Most damaging channel per pound because it is regressive; the entire [`avoidance.md`](avoidance.md) spine and [`../08-capital-flight/`](../08-capital-flight/) section exist to hold this down |

Note the asymmetry: three of the four channels convert forgone revenue into policy-consistent outcomes. Only the fourth is a genuine loss, and it is the one attacked structurally rather than assumed away.

## 5. What the endowment costs

- **UK:** ~700,000 residents reach 25 each year [3] × £50,000 = **~£35bn/year** (illustrative; cohort size varies ±5% across years, to verify against ONS mid-year estimates).
- **US:** ~4.3m reach 25 each year (to verify) × $60,000 = **~$260bn/year** (illustrative).

Against the §3 ranges: the UK endowment is *not fully funded* by the tax in the early years (£12–25bn vs £35bn) and *plausibly overfunded* at mature flows (£25–50bn vs a wage-indexed cost). The honest formulation: **the tax funds the endowment across the transition on average, not in every year.** Bridge instruments — phased grant ramp-up, pre-funding the National Endowment Fund before first payout, general-revenue top-up, borrowing against the rising flow — are specified in [`../15-transition/revenue-bridge.md`](../15-transition/revenue-bridge.md), and the fund architecture that smooths across years is in [`constitutional-design.md`](constitutional-design.md) §3.

## 6. US parallel sketch

All figures illustrative and to verify. The US "great wealth transfer" literature projects on the order of $80–100tn passing between 2021 and 2045 (Cerulli and successor estimates — to verify), i.e. roughly **$3–4tn/year** and rising. Federal estate and gift tax currently collects ~$30–35bn/year (to verify) [8] — an effective rate on the flow of ~1%, even more hollowed-out than the UK's. With US wealth concentration steeper than the UK's (top 1% ≈ 30%+ of wealth, Federal Reserve DFA — to verify [9]), the share of flow above $750k per recipient is plausibly **40–50%**, giving a pre-behavioural gross of $1.2–2tn/year and, applying the §3 attrition structure, a net perhaps in the **$500bn–1tn/year** range — comfortably above the ~$260bn endowment cost, reflecting the sheer top-heaviness of US wealth. These are order-of-magnitude sketches pending JCT/CBO-grade modelling.

## 7. Comparison with the existing take

| Measure | Current UK IHT | This proposal (near-term) | This proposal (2040s flows) |
|---|---|---|---|
| Revenue | ~£7.5–8bn (to verify) [5] | ~£12–25bn (illustrative) | ~£25–50bn (illustrative) |
| Effective rate on aggregate flow | ~7–8% | ~15–25% | ~15–25% |
| Share of estates/recipients affected | ~4–5% of estates (to verify) [5] | ~3–7% of recipients ([`thresholds.md`](thresholds.md)) | similar |
| Incidence above threshold | Inversely correlated with wealth (reliefs) | Flat 100% by construction | same |

The proposal's revenue gain over current IHT is real but modest relative to total taxation (~1–2% of UK tax receipts). Anyone selling this policy primarily as a revenue measure is mis-selling it.

## 8. Which number matters

Two different success criteria, and the distinction should be stated plainly rather than blurred:

1. **Politically**, the binding number is whether every 25-year-old's endowment is paid in full, on time, every year. That is what sustains the stakeholder coalition described in [`endowment.md`](endowment.md) §8 and [`constitutional-design.md`](constitutional-design.md) §6. The fund-smoothing and bridge architecture exist to make this number robust to revenue volatility.
2. **Structurally**, the binding number is the share of large fortunes that fails to arrive intact in a single heir's hands. This number *improves* under dispersal, charitable diversion, and consumption — the very responses that depress revenue. A future headline that "the 100% inheritance tax is raising less than forecast" is compatible with the policy succeeding completely; the pre-emptive answer is written at [`../09-objections/spend-it-all.md`](../09-objections/spend-it-all.md) and should be part of the communications toolkit from day one ([`../14-communications/debate-toolkit.md`](../14-communications/debate-toolkit.md)).

## Sources

1. [Institute for Fiscal Studies — "Inheritances and inequality" research programme](https://ifs.org.uk/publications/inheritances-and-inequality-within-generations) — flow projections and receipt distributions (to verify against latest release).
2. [ONS — Wealth and Assets Survey](https://www.ons.gov.uk/peoplepopulationandcommunity/personalandhouseholdfinances/incomeandwealth) — gift and transfer measurement limitations.
3. [ONS — Population estimates for the UK, mid-year](https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationestimates) — single-year-of-age cohort sizes.
4. [US Census Bureau — National Population by Characteristics](https://www.census.gov/data/tables/time-series/demo/popest/2020s-national-detail.html) — US single-year cohort sizes (to verify).
5. [HMRC — Inheritance Tax statistics and annual receipts](https://www.gov.uk/government/collections/inheritance-tax-statistics) (to verify latest year).
6. [ONS — Household total wealth in Great Britain](https://www.ons.gov.uk/peoplepopulationandcommunity/personalandhouseholdfinances/incomeandwealth/bulletins/totalwealthingreatbritain/latest) — wealth-share estimates (to verify).
7. [Federal Reserve — Survey of Consumer Finances, intergenerational transfer module](https://www.federalreserve.gov/econres/scfindex.htm).
8. [Congressional Budget Office — "Understanding Federal Estate and Gift Taxes"](https://www.cbo.gov/publication/57129) (to verify current receipts).
9. [Federal Reserve — Distributional Financial Accounts](https://www.federalreserve.gov/releases/z1/dataviz/dfa/) (to verify).
