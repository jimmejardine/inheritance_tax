# Ireland: The Operating Analogue

**Executive summary.** Ireland already runs the structural core of this proposal: the Capital Acquisitions Tax (CAT) is recipient-based and lifetime-cumulative, with per-recipient group thresholds and a single flat rate above them — the design in [`../02-proposal/mechanism.md`](../02-proposal/mechanism.md) is, in skeleton, an Irish CAT with a higher threshold, a 100% rate, and a hypothecated endowment. Ireland therefore matters less as a probable *first mover at full strength* than as the proof of administrability that every other country file leans on.

## Scorecard

| Criterion | Score /5 | Basis |
|---|---|---|
| C1 Administration | 4 | Revenue Commissioners administer CAT with self-assessment and lifetime aggregation; strong digital tax administration |
| C2 Trust / tax morale | 4 | High compliance culture post-1990s reforms; historical amnesty-era cynicism largely faded |
| C3 Transfer-tax infrastructure | 5 | The world's closest existing analogue: recipient-based, with lifetime cumulation of all benefits within a group threshold since 5 December 1991 [1] |
| C4 Majoritarian institutions | 4 | Unitary parliamentary state; coalition norm adds friction but Finance Acts move fast; constitutional referendums required only for constitutional change |
| C5 Egalitarian norms | 3 | Strong fairness discourse, but property ownership is culturally central and land carries historical charge |
| C6 Housing salience | 5 | Among the most acute housing crises in the OECD; housing/homelessness was the top exit-poll issue at the 2024 election (28% overall, 42% of under-34s) [2]; young-adult emigration framing |
| C7 Wealth-transfer exposure | 3 | Substantial post-Celtic-Tiger property wealth now transferring, but the national balance sheet is smaller and younger than the UK's |
| C8 Crisis windows | 3 | Currently fiscally comfortable (corporate-tax surpluses), which *weakens* the revenue-need window; housing is the operative crisis |
| C9 Constitutional openness | 4 | Art. 40.3/43 property rights are qualified by "principles of social justice" and "exigencies of the common good"; courts historically deferential on taxation (unverified) |
| C10 National assignment | 5 | Fully national tax; no sub-national channel |
| **Total** | **40/50** | Third tier of the ranking in [README.md](README.md) — high structural fit, small-economy constraints |

## What CAT is

Key features of Capital Acquisitions Tax (figures per Revenue, current since 2 October 2024 [1][3]):

| Feature | Ireland today | This proposal |
|---|---|---|
| Tax base | What each **recipient** receives (gifts + inheritances) | Same |
| Cumulation | **Lifetime** aggregation within beneficiary groups (benefits since 5 December 1991) [1] | Same, single universal ledger |
| Thresholds | Group A (child) €400k; Group B (close relative) €40k; Group C (other) €20k [3] | Single £500k/$750k per recipient, relationship-blind |
| Rate above threshold | 33% flat [3] | 100% |
| Reliefs | Agricultural and business relief (90% reduction in taxable value) [4][5], dwelling-house exemption [5] | Replaced by 30-year deferral / state equity ([`../02-proposal/carveouts.md`](../02-proposal/carveouts.md)) |
| Revenue use | General revenue | Hypothecated universal endowment ([`../02-proposal/endowment.md`](../02-proposal/endowment.md)) |

## What Ireland proves

1. **The recipient basis is administrable.** The standard objection that tracking lifetime receipts per person is bureaucratically fantastical ([`../09-objections/practicality.md`](../09-objections/practicality.md)) fails against four decades of Irish practice: self-assessed returns, aggregation across all prior benefits within a group since 5 December 1991 [1], ordinary compliance levels. The Central Register of Receipts in [`../02-proposal/mechanism.md`](../02-proposal/mechanism.md) is an upgrade of existing Irish machinery, not an invention.
2. **The "death tax" frame is escapable.** Irish political argument about CAT is conducted in terms of what *beneficiaries* receive tax-free — the threshold debate is about how much a child may inherit, not what the dead may leave. This is the rhetorical ground [`../06-palatability/framing.md`](../06-palatability/framing.md) wants every campaign to fight on.
3. **Relationship-tiered thresholds are a design mistake worth learning from.** Group B/C recipients (nieces, unrelated carers, cohabitants outside marriage) face tax at a fraction of the child threshold — a recurring fairness grievance in Irish politics, now organised in the EDIT (End Discrimination in Inheritance Tax) campaign against a system it brands discriminatory towards the childless [6] — that a single universal threshold avoids.
4. **Reliefs erode even good structures.** Ireland's 90% agricultural/business reliefs reproduce, at smaller scale, exactly the hollowing-out documented in [`../05-history/abolitions.md`](../05-history/abolitions.md): the structure is sound while the carve-outs make effective rates on the largest transfers collapse. Structure alone does not protect the base.

## What limits Ireland as a first mover

- **FDI dependence.** An economy built on mobile multinational capital and inward-migrating executives is maximally sensitive to any signal read as wealth-hostile; the same logic that shapes Irish corporate-tax politics would be deployed against a 100% rate ([`../08-capital-flight/exit-options.md`](../08-capital-flight/exit-options.md)).
- **Small size and open border.** A five-million-person economy sharing a land border, language, and Common Travel Area with a non-adopting UK offers cheap exit; Ireland is a strong *second* mover behind a UK or EU move ([`../08-capital-flight/international-coordination.md`](../08-capital-flight/international-coordination.md), [`../08-capital-flight/game-theory.md`](../08-capital-flight/game-theory.md)).
- **Recent direction of travel is threshold-raising.** Budget 2025 raised Group A from €335k to €400k (with B and C up to €40k and €20k) in response to house-price salience [3] — evidence of the housing pressure operating in the *opposite* direction absent an endowment to change the offer.
- **No endowment tradition.** Unlike the UK's Child Trust Fund history, Ireland has no asset-based-welfare precedent to build on, though its young-skewing housing anger is a natural constituency.

## Implementation lessons for the Central Register

Details of Irish practice worth importing directly into [`../02-proposal/mechanism.md`](../02-proposal/mechanism.md) and [`../07-implementation/administration.md`](../07-implementation/administration.md):

- **Self-assessment with a filing trigger.** A CAT return (IT38) is required once cumulative benefits exceed 80% of the relevant group threshold [1] — an elegant device that keeps the vast unaffected majority out of the system entirely while creating an early-warning record for those approaching the line.
- **Aggregation vintage rules.** Ireland has moved its aggregation start-date several times (benefits on or after 5 December 1991 for the current grouping [1]), showing that a lifetime ledger can be introduced *prospectively* without reconstructing the past: the register starts at enactment, exactly as [`../15-transition/grandfathering.md`](../15-transition/grandfathering.md) proposes.
- **Gift/inheritance unification.** Gifts and inheritances draw on the same threshold with a small annual gift exemption (the first €3,000 from any one donor in a calendar year, gifts only) [7] — the anti-timing architecture of [`../07-implementation/gifts-and-timing.md`](../07-implementation/gifts-and-timing.md) in miniature.
- **Payment machinery.** CAT offers statutory instalment arrangements (monthly instalments over up to five years, with interest) for property that cannot readily be sold [5] — a small-scale precedent for the 30-year business deferral.

## Threshold politics as a preview

The Group A threshold's history — a peak of €542,544 in early 2009, cut sharply in fiscal emergency to a trough of €225,000 (2012–15), then ratcheted back up as house prices recovered, reaching €400,000 from October 2024 [8][3] — is a two-decade natural experiment in exactly the threshold politics this proposal will face. Lessons: thresholds *can* move both ways when the fiscal case demands it; every downward move generated durable resentment because it was unindexed and unaccompanied by any visible benefit; and the political debate reliably centred on "can a child inherit the family home tax-free" — the question the £500k-plus-indexation design in [`../02-proposal/thresholds.md`](../02-proposal/thresholds.md) is built to answer permanently.

## What to watch

- Whether agricultural/business relief narrows in future Finance Acts — the Irish version of the UK's 2024–25 fight ([uk.md](uk.md)).
- Housing-driven threshold increases outpacing indexation-equivalent, i.e. the base quietly eroding.
- Sinn Féin and Social Democrat wealth-taxation positions in coalition negotiations — the likeliest vector for CAT-strengthening proposals; the Social Democrats' 2024 manifesto proposed a net-wealth tax of 0.5% above €1m (1% above €2m, family home, business assets and farmland excluded) [9], while Sinn Féin has proposed raising the CAT rate from 33% in earlier alternative budgets (its 2024 manifesto position unverified).
- EU-level movement: Ireland's corporate-tax experience with Pillar Two shows it ultimately joins coordinated frameworks it would never initiate ([`../08-capital-flight/international-coordination.md`](../08-capital-flight/international-coordination.md)).

## What Ireland supplies to the rest of the project

| Consuming file | What it takes from the Irish case |
|---|---|
| [`../02-proposal/mechanism.md`](../02-proposal/mechanism.md) | Proof-of-concept for the lifetime receipts ledger and self-assessment trigger |
| [`../09-objections/practicality.md`](../09-objections/practicality.md) | The standing rebuttal to "lifetime cumulation is unadministrable" |
| [`../06-palatability/case-studies.md`](../06-palatability/case-studies.md) | The "this already exists" opener for every campaign audience |
| [`../07-implementation/gifts-and-timing.md`](../07-implementation/gifts-and-timing.md) | Unified gift/inheritance thresholds with a small annual exemption |
| [`../15-transition/grandfathering.md`](../15-transition/grandfathering.md) | Prospective aggregation start-dates as the transition template |
| [`../08-capital-flight/game-theory.md`](../08-capital-flight/game-theory.md) | The small-open-economy second-mover position, stated honestly |

## Analytic judgement

Ireland's role in the global case is evidentiary, not vanguard: it is the country every other file cites to show the mechanism works. Its own adoption of the full variant is plausible only inside a coordinated move — most naturally an EU or UK-plus-Ireland framework — at which point its existing CAT machinery would make it the fastest implementer in Europe. Campaign use: lead with "Ireland already taxes inheritances this way; we are changing the rate and giving everyone a share," per [`../06-palatability/case-studies.md`](../06-palatability/case-studies.md).

## Sources

1. [Revenue Commissioners, "CAT thresholds, rates and aggregation rules" (aggregation of benefits since 5 December 1991; IT38 return required above 80% of threshold)](https://www.revenue.ie/en/gains-gifts-and-inheritance/cat-thresholds-rates-and-aggregation-rules/index.aspx)
2. [Irish Times (30 November 2024), "Housing and homelessness biggest issue for voters, exit poll shows"](https://www.irishtimes.com/politics/2024/11/30/housing-and-homelessness-biggest-issue-for-voters-exit-poll-shows/)
3. [Revenue Commissioners, "CAT group thresholds" (Group A €400,000, B €40,000, C €20,000 for benefits on or after 2 October 2024; rate 33%)](https://www.revenue.ie/en/gains-gifts-and-inheritance/cat-thresholds-rates-and-aggregation-rules/cat-thresholds.aspx)
4. [Revenue Commissioners, "Agricultural Relief" (reduces taxable value by 90%)](https://www.revenue.ie/en/gains-gifts-and-inheritance/cat-reliefs/agricultural-relief/index.aspx)
5. [Citizens Information, "Capital Acquisitions Tax exemptions and reliefs"](https://www.citizensinformation.ie/en/money-and-tax/tax/capital-taxes/capital-acquisitions-tax-exemptions-and-reliefs/)
6. [Irish Examiner, "Cork campaigner says inheritance tax laws discriminate against childless families"](https://www.irishexaminer.com/business/economy/arid-41816102.html)
7. [Revenue Commissioners, "Small Gift Exemption" (first €3,000 from any one person in a calendar year exempt)](https://www.revenue.ie/en/gains-gifts-and-inheritance/cat-exemptions/small-gift-exemption/index.aspx)
8. [Revenue Commissioners, "Historical CAT groups, group thresholds and rates"](https://www.revenue.ie/en/gains-gifts-and-inheritance/cat-thresholds-rates-and-aggregation-rules/historical-cat-thresholds.aspx)
9. [RTÉ (19 November 2024), "5 key points from the Social Democrats election manifesto"](https://www.rte.ie/news/election-24/2024/1119/1481806-social-democrats-manifesto-points/)
