# 02 — The Proposal

**Executive summary.** A recipient-based, lifetime-cumulative tax on capital transfers received, with a 0% marginal rate below a per-recipient lifetime threshold and 100% above it, hypothecated to fund a universal citizen's endowment paid at age 25. The design is a direct response to the eight recurring errors that produced the twentieth-century abolition wave documented in [`../05-history/abolitions.md`](../05-history/abolitions.md); every headline commitment below has a named failure mode it is built to avoid.

## Headline commitments

| Dimension | Commitment |
|---|---|
| Tax structure | Recipient-based, lifetime-cumulative; 0% below threshold, 100% above |
| Threshold | £500,000 per recipient (UK); $750,000 (US); indexed to max(wage growth, median house-price growth) |
| Universal endowment | £50,000 / $60,000 at age 25; unconditional; wage-indexed |
| Business / farm | 30-year deferred payment at gilts + 1%; optional state equity stake |
| Residence | Dual nexus (recipient residence OR asset situs); 10-year exit tail |
| Exemptions | Spouse / civil partner; registered charities (with anti-cycling); disabled-dependant trusts |
| Valuation | Mark-to-market for listed; RICS-style appraisal for real estate; capped minority/marketability discounts |
| Fiscal architecture | Named National Endowment Fund; statutory indexation formulae; annual transparency report |
| Tax coordination | CGT death uplift ended as a windfall; receipts excluded from income tax; trust tax regimes superseded |

## The ten specifications

| File | What it specifies |
|---|---|
| [mechanism.md](mechanism.md) | Legal and administrative architecture — taxable receipts, lifetime cumulation, liability, valuation, returns, Central Register of Receipts |
| [thresholds.md](thresholds.md) | The quantitative case for £500k / $750k — house-price and wage multiples, distribution of receipts, revenue estimates, sensitivity table |
| [endowment.md](endowment.md) | Design of the universal £50k / $60k grant at 25 — intellectual lineage (Paine → Piketty), age and unconditionality rationale, fiscal arithmetic |
| [carveouts.md](carveouts.md) | Spousal, charitable, dependant, residence, business, farm, collectible, and pension reliefs — each tied to a specific historical failure mode |
| [avoidance.md](avoidance.md) | Anti-avoidance spine — gift aggregation, trust look-through, wrapper piercing, exit tax, situs rules, valuation discipline, international coordination |
| [revenue-model.md](revenue-model.md) | The fiscal arithmetic made honest — gross base, behavioural attrition with sensitivities, endowment cost, the early-years funding gap, and which number actually matters |
| [arithmetic.md](arithmetic.md) | The balance sheet — verified flow anchors, the gross-to-net waterfall as destination shares, the scenario-by-horizon funding verdict against the endowment cost, the National Endowment Fund balance-sheet view, and the consolidated micro-simulation spec. **The single owner of the scheme's quantitative ranges** |
| [tax-interactions.md](tax-interactions.md) | Meshing with the existing system — CGT at death, inherited pensions, the income-tax boundary, benefits cliff edges, stamp duty, superseded trust regimes, and the tax-cut dividend |
| [endowment-delivery.md](endowment-delivery.md) | Operations of paying 700k people a year — default investment wrapper, scam and predation defences, eligibility and migration edge cases, commencement taper, delivery precedents |
| [constitutional-design.md](constitutional-design.md) | Entrenchment against post-passage sabotage — statutory indexation, the National Endowment Fund and its guardians, transparency reporting, legal locks where available, the UK political ratchet |

## How the pieces work together

The ten files describe one policy, not ten. The logic chain:

1. **Mechanism** defines *what is taxed* (receipts by a person, not an estate) and *how the ledger works* (one lifetime running total per person).
2. **Thresholds** sets *where the rate kinks* and commits to *how it holds its value* (max-of-two indexation, against the Swedish/Norwegian nominal-drift failure).
3. **Endowment** answers *what the revenue is for* — turning the tax from a Treasury input into every citizen's named entitlement at 25. This is the single biggest structural defence against the abolition pattern.
4. **Carveouts** handles *the politically lethal cases* — surviving spouses, operating businesses, working farms, primary residences — with designs calibrated against the specific abuses that broke UK BPR/APR, US QFOBI, and the German and Austrian regimes.
5. **Avoidance** closes *the escape routes* that, left open, would make the tax's incidence inversely correlated with wealth above the threshold — the deepest structural cause of prior abolitions.
6. **Revenue model** states *what the money actually looks like* — a conservative net range against the endowment's cost, with the early-years gap acknowledged and bridged rather than assumed away, and the distinction drawn between the political success metric (endowment funded) and the structural one (dynasties broken) — with **arithmetic.md** holding the consolidated waterfall, scenario tables, and the funding verdict to which every other file's numbers reconcile.
7. **Tax interactions** makes the scheme *fit the system it lands in* — ending the CGT death uplift as a windfall, closing the inherited-pension leak, avoiding benefits cliff edges, and naming the taxes on work and transactions that the proceeds allow to be cut.
8. **Endowment delivery** turns the grant *from a Budget line into an operation* — default architecture that protects recipients from fraud and predation without ever becoming a condition, plus eligibility rules and commencement fairness.
9. **Constitutional design** makes the whole structure *hard to strangle after passage* — self-executing indexation, an independent National Endowment Fund, radical transparency, legal entrenchment where constitutions allow it, and the stakeholder ratchet where they do not.

## What this proposal is not

- **Not a "death tax."** The tax falls on the recipient, not the estate. Nothing is taken from the deceased.
- **Not confiscation of ordinary inheritance.** 90%+ of current recipients would be entirely unaffected at the baseline threshold; those who are affected are by construction receiving sums several times the median lifetime earning capacity.
- **Not state revenue-grabbing.** Proceeds are hypothecated to the universal endowment; general revenue receives only the surplus once every 25-year-old has been paid.
- **Not unprecedented.** Every element has a historical analogue: [Ireland's Capital Acquisitions Tax](https://www.revenue.ie/en/gains-gifts-and-inheritance/index.aspx) is recipient-based; the [Mirrlees Review](https://ifs.org.uk/mirrlees-review) proposed a lifetime-receipts tax; Paine, Atkinson, Ackerman–Alstott, and Piketty all paired a transfer tax with a universal grant.

## Variants considered and rejected (at this pass)

| Variant | Why not (for now) |
|---|---|
| Progressive schedule to ~90% (Piketty) instead of a binary 0/100 kink | Sharper kink simplifies the rhetoric and the administration; distributional effect is similar above £500k |
| £250k tighter threshold | Bites into ordinary inherited homes in the South East; raises political attack surface without proportionate gain |
| £1m looser threshold | Weakens the dynastic-break effect; would reduce the endowment funding base substantially |
| Flat 100% from £1 (no threshold) | No political coalition; no mechanism to distinguish dynastic from ordinary family transfer |
| Age 18 or 21 endowment | [Child Trust Fund](https://www.gov.uk/child-trust-funds) dormancy evidence, and prefrontal-development literature, favour age 25 |
| Conditional (housing / education only) endowment | Paternalism, administrative cost, weaker ownership framing; cash-transfer evidence does not support earmarking |
| State-level assignment (US) | Australia's 1977–79 cascade shows sub-national inheritance taxation is self-destructive |

## What still needs doing

- **Micro-simulation** of the £500k threshold against IFS and [SCF](https://www.federalreserve.gov/econres/scfindex.htm) distributional data to refine the revenue estimate and share of recipients affected — the consolidated spec (data sources and outputs) is [arithmetic.md](arithmetic.md) §5; [revenue-model.md](revenue-model.md) flags every figure that depends on it.
- **Benefit-interaction regulations** — the tapered capital rules sketched in [tax-interactions.md](tax-interactions.md) §4 need DWP-grade modelling.
- **Constitutional counsel** on the German Art. 14 accommodation and US excise framing set out in [constitutional-design.md](constitutional-design.md) §7.
- **Legal drafting** of the Central Register of Receipts provisions and their interaction with probate.
- **Political-economy modelling** of the endowment's polling lift across different grant sizes and ages.
- **International design** of the Pillar-Two-analogue multilateral floor.
- **Case study work** on Ireland's CAT experience as the closest real-world operating analogue.
