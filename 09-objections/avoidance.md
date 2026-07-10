# Avoidance Objections

**Executive summary.** "The rich will dodge it" is the objection with the best historical evidence behind it — avoidance genuinely helped kill the abolished twentieth-century regimes — and the answer is not to deny that history but to show that every escape route had a specific, now-understood design cause. This file gives the quick-fire rebuttals; the engineering lives in [`../02-proposal/avoidance.md`](../02-proposal/avoidance.md) and [`../07-implementation/enforcement.md`](../07-implementation/enforcement.md).

Rules of engagement: concede, one-liner, full answer. Master table in [README.md](README.md).

## "The rich will always find a way around it"

**Concede first.** They historically did. Avoidance and emigration were cited in every abolition episode, and incidence that fell on the merely comfortable while billionaires escaped is precisely what delegitimised the Swedish and UK regimes ([`../05-history/abolitions.md`](../05-history/abolitions.md)).

**One-line answer.** Avoidance is a design variable, not a law of nature — every historical escape route maps to a specific engineering failure that this design closes, in an information environment (CRS, FATCA, beneficial-ownership registers) the old regimes never had.

**Full answer.** The abolished taxes shared a known anatomy of failure, and each element has a named countermeasure:

| Historical escape route | Design failure behind it | Countermeasure in this proposal |
|---|---|---|
| Give early | Estate basis, no gift aggregation | Lifetime cumulation of all receipts ([`../02-proposal/mechanism.md`](../02-proposal/mechanism.md)) |
| Split among recipients | Estate-level threshold | Per-recipient threshold — splitting is *encouraged*, not avoidance |
| Interpose a trust | Trust opacity | Look-through; distributions taxed as receipts ([`../07-implementation/trusts-and-vehicles.md`](../07-implementation/trusts-and-vehicles.md)) |
| Hold the right asset class | Stale/asymmetric valuation | Mark-to-market and appraisal with capped discounts ([`../07-implementation/valuation.md`](../07-implementation/valuation.md)) |
| Move assets offshore | Purely domestic information | CRS/FATCA automatic exchange; dual nexus; exit tail ([`../02-proposal/avoidance.md`](../02-proposal/avoidance.md)) |

The environment has also changed under the objection's feet: the Common Reporting Standard (over 100 jurisdictions exchanging account data automatically, with the first exchanges in 2017 [1]) and FATCA mean tax authorities now receive offshore financial information automatically — HMRC alone receives data on around 9 million offshore accounts from over 100 jurisdictions [2]. The Kamprad-era assumption that foreign assets were invisible is dead. Avoidance will not be zero. It does not need to be — see the final section below.

**Deep treatment:** [`../02-proposal/avoidance.md`](../02-proposal/avoidance.md) · [`../07-implementation/enforcement.md`](../07-implementation/enforcement.md) · [`../08-capital-flight/international-coordination.md`](../08-capital-flight/international-coordination.md)

## "Lawyers will run rings round HMRC"

**Concede first.** The resource asymmetry is real: top private-client teams out-gun and out-pay revenue authorities. HMRC's wealthy-individuals compliance team runs to about 910 full-time staff covering some 850,000 wealthy taxpayers, and its dedicated unit for those with assets over £10m was disbanded in 2017 [2].

**One-line answer.** The same asymmetry applies to every tax the state nonetheless collects successfully; the answer is bright-line design that starves lawyers of raw material, plus enforcement funding that pays for itself.

**Full answer.**

- **Planning industries feed on complexity.** Reliefs, definitions, elections, and boundaries are where the arbitrage lives. UK IHT is a planner's paradise precisely because of its relief thicket (BPR, APR, normal-expenditure-out-of-income, seven-year taper).
- **This proposal is structurally hostile terrain:** one threshold, one rate above it, few reliefs, all receipts cumulated for life, a general anti-abuse rule, and DOTAS-style promoter disclosure extended to transfer schemes ([`../07-implementation/enforcement.md`](../07-implementation/enforcement.md)).
- **A 0%/100% kink with no relief cliff-edges gives less to lawyer around** than a 40% rate with a dozen doors marked "exempt."
- **Enforcement is a choice, not a constant.** Compliance spending on wealthy non-compliance has among the highest returns per pound in tax administration — HMRC's compliance work on wealthy taxpayers yielded £5.2bn in 2023–24, up from £2.2bn in 2019–20, against costs of roughly £350m [2] — and the endowment gives every 25-year-old voter a direct stake in funding it ([`../02-proposal/endowment.md`](../02-proposal/endowment.md)).

**Deep treatment:** [`../07-implementation/enforcement.md`](../07-implementation/enforcement.md) · [`../07-implementation/administration.md`](../07-implementation/administration.md)

## "It'll only catch the moderately rich; the billionaires escape"

**Concede first.** This described the abolished regimes accurately — incidence inversely correlated with wealth above the threshold was their deepest legitimacy failure, and offshore-evasion research ([Alstadsæter, Johannesen and Zucman](https://www.aeaweb.org/articles?id=10.1257/aer.20172043)) finds evasion rising steeply with wealth: the richest 0.01% of households evade about 25% of their taxes, against under 5% detected on average in random audits [3].

**One-line answer.** That was a fact about *those designs* — estate-based, gift-leaky, trust-blind, domestically informed — not about inheritance taxation as such, and the billionaire-specific escape routes each have a named fix.

**Full answer.** Billionaires escaped historically through four doors, each now addressed:

- **Emigration** — answered by the exit tax, asset-situs taxation, and the 10-year tail ([`../08-capital-flight/exit-tax-design.md`](../08-capital-flight/exit-tax-design.md)).
- **Dynasty trusts** — answered by look-through and taxation of distributions as receipts ([`../07-implementation/trusts-and-vehicles.md`](../07-implementation/trusts-and-vehicles.md)).
- **Valuation games on unlisted assets** — answered by capped discounts and appraisal discipline ([`../07-implementation/valuation.md`](../07-implementation/valuation.md)).
- **Foundation-washing** — answered by anti-cycling charity rules ([spend-it-all.md](spend-it-all.md#theyll-give-it-all-to-charity-and-youll-collect-nothing)).

The moderately rich, conversely, are largely *below* a £500k-per-recipient threshold: the design's incidence gradient runs the right way for the first time. Residual billionaire leakage should be treated the way we treat top-end income-tax evasion — as an enforcement priority, not a reason to abandon the tax.

**Deep treatment:** [`../08-capital-flight/evidence.md`](../08-capital-flight/evidence.md) · [`../08-capital-flight/game-theory.md`](../08-capital-flight/game-theory.md) · [`../07-implementation/valuation.md`](../07-implementation/valuation.md)

## "They'll just gift everything early"

**Concede first.** Inter-vivos giving is the classic route — under the UK's seven-year rule it is practically an invitation, and gift-timing killed the integrity of several historical regimes.

**One-line answer.** Lifetime cumulation abolishes the clock: every gift a recipient ever receives counts against the same £500,000 lifetime total, so giving early changes the *date* of the tax, not its amount.

**Full answer.**

- The proposal taxes *receipts by a person over their lifetime*, not transfers at death ([`../02-proposal/mechanism.md`](../02-proposal/mechanism.md)). A parent who transfers £2m to a child at 40 rather than by will has simply triggered the same liability sooner.
- There is no seven-year survival discount, no annual drip-feed that escapes cumulation above de minimis allowances, and the Central Register of Receipts keeps the running total.
- What early giving *does* achieve — earlier transfer of capital to younger hands — is welcome on the proposal's own terms.
- The genuine boundary questions (school fees, weddings, support in kind) are real and are handled by de minimis and consumption carve-outs in [`../07-implementation/gifts-and-timing.md`](../07-implementation/gifts-and-timing.md) and [`../07-implementation/boundary-problem.md`](../07-implementation/boundary-problem.md).

**Deep treatment:** [`../07-implementation/gifts-and-timing.md`](../07-implementation/gifts-and-timing.md) · [`../02-proposal/mechanism.md`](../02-proposal/mechanism.md)

## The asymmetric-perfectionism fallacy

A closing move worth naming, because it answers this whole file at once.

- Income tax is evaded — HMRC put the 2023–24 UK tax gap at £46.8 billion, 5.3% of theoretical liabilities [4] — and nobody concludes income tax should be abolished.
- VAT is defrauded; VAT stays. Benefits are over- and under-claimed; benefits stay.
- Only for taxes on wealth transfer is "some people will avoid it" treated as decisive. That is asymmetric perfectionism: demanding of this tax a standard (zero leakage) demanded of no other.

The real bar is the one every tax meets or fails on: does it collect most of its base at acceptable cost with incidence that runs in the intended direction? The design work in sections [02](../02-proposal/README.md), [07](../07-implementation/README.md) and [08](../08-capital-flight/README.md) exists to clear that bar, not the imaginary one.

## Sources

1. [OECD, Automatic Exchange of Information: exchange relationships](https://www.oecd.org/en/topics/sub-issues/international-standards-on-tax-transparency/automatic-exchange-of-information-exchange-relationships.html)
2. [National Audit Office, *Collecting the right tax from wealthy individuals* (May 2025)](https://www.nao.org.uk/reports/collecting-the-right-tax-from-wealthy-individuals/)
3. [Alstadsæter, Johannesen and Zucman, "Tax Evasion and Inequality", *American Economic Review* 109(6), 2019](https://www.aeaweb.org/articles?id=10.1257/aer.20172043)
4. [HMRC, *Measuring tax gaps 2025 edition* (estimates for 2023–24)](https://www.gov.uk/government/statistics/measuring-tax-gaps)

## See also

- Why past regimes actually died: [`../05-history/abolitions.md`](../05-history/abolitions.md)
- Capital flight as a distinct threat: [`../08-capital-flight/README.md`](../08-capital-flight/README.md)
- The opposition's use of avoidance narratives: [`../10-opposition/attack-playbook.md`](../10-opposition/attack-playbook.md)
