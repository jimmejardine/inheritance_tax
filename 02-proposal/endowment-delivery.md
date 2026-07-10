# Endowment Delivery

**Executive summary.** Paying £50,000 to roughly 700,000 people a year is an operational programme, not a line in a Budget: the day the first cohort is paid, it becomes the largest concentrated transfer to young adults any state has attempted, and every fraudster, predatory lender, and mis-seller will know the date. This file specifies the delivery vehicle, the scam-protection architecture, eligibility and migration edge cases, and cohort-fairness at commencement — while preserving the unconditionality commitment of [`endowment.md`](endowment.md): everything below is default architecture and protection from third parties, never conditions on the recipient.

## Key commitments

- Delivery via a **National Endowment Account** opened at birth, invested by default in a low-cost fund, with an **absolute right to withdraw 100% in cash at any time from age 25** — defaults, not conditions (§1–2).
- **Anti-assignment rule:** any contract pledging, assigning, or borrowing against an unpaid endowment is void, on the model of pension and Social Security anti-assignment law (§3).
- **30-day cooling period** between claim initiation and first large transfer, plus confirmation-of-payee-only destinations and a funded, optional, regulated-advice voucher (§3).
- **Student-loan offset is optional and advice-gated** — for low lifetime earners early repayment is often value-destroying, so the state must not nudge it (§4).
- Eligibility: **citizens and settled residents with a minimum residence history**, claimable from 25 with no expiry; parameters flagged as open (§5).
- **Commencement taper** for near-miss cohorts, converting the 26-year-old cliff edge into a slope (§6).
- Machinery reuses proven precedents: Child Trust Fund auto-enrolment, NEST/AP7 default funds, Alaska PFD claims processing (§7).

## 1. Delivery vehicle options

| Vehicle | Description | For | Against | Verdict |
|---|---|---|---|---|
| Unrestricted cash lump sum | £50k to a nominated bank account on claim | Maximal autonomy; simplest | Maximal scam surface; loss anecdotes arm the opposition ([`../10-opposition/attack-playbook.md`](../10-opposition/attack-playbook.md)) | Rejected as *default*; remains available on demand |
| Restricted-purpose account | Spendable only on housing/education/business | Reassures sceptics | It is conditionality; already rejected ([README](README.md) variants table; [`endowment.md`](endowment.md) §5) | Rejected |
| Staged tranches (e.g. 25/30/35) | Mandatory instalments | Limits single-point loss | Paternalist; breaks the "your inheritance at 25" legibility; rejected in [`endowment.md`](endowment.md) §4 | Rejected as mandate; offered as opt-in schedule |
| Matched drawdown | State tops up balances left invested | Rewards patience | Adds fiscal cost; regressive (patient recipients skew affluent) | Rejected at this pass |
| **Default investment wrapper + full withdrawal right** | Endowment sits invested in a default fund; recipient may withdraw any amount, any time, after claim | Inertia protects without compelling; one account for statements from 16; benefits disregard attaches cleanly ([`tax-interactions.md`](tax-interactions.md) §4) | Requires fund governance (supplied by [`constitutional-design.md`](constitutional-design.md) §3) | **Adopted** |

**Reconciliation with unconditionality.** The distinction is doing real work and must be policed in drafting: a *condition* restricts what the recipient may do with their money; a *default* sets where the money sits until they act, at zero cost to act. The recipient's right to 100% cash on demand from age 25 is absolute and justiciable. Behavioural-economics precedent — auto-enrolment raised UK pension participation from ~55% to ~88% (to verify) without compelling anyone [1] — shows defaults deliver most of the protective benefit of mandates with none of the coercion.

## 2. The account lifecycle

1. **At birth/registration:** account opened automatically against the NINO/SSN record (Child Trust Fund precedent: ~6.3m accounts opened automatically, 2002–2011 — to verify [2]).
2. **From 16:** annual statements showing the projected grant; financial-education tie-in at school (the CTF's great failure was dormancy through invisibility — ~£1.7bn unclaimed [2]; statements and a claim ritual are the fix).
3. **At 25:** claim window opens; identity-verified claim via the same Gateway/IRS-account rails as [`mechanism.md`](mechanism.md) §6. Unclaimed balances roll forward wage-indexed, no expiry ([`endowment.md`](endowment.md) §6).
4. **Post-claim:** funds remain in the default wrapper until withdrawn; partial withdrawals free and unlimited after the cooling period.

## 3. Fraud and predation defences

The threat model is not primarily benefit fraud (eligibility is a birth-register fact, hard to fake) but **extraction from legitimate recipients**. On the day a cohort is paid, romance scammers, fake-investment platforms, "endowment advance" lenders, and family pressure all activate. Defences, layered:

| Threat | Defence |
|---|---|
| Advance-fee / "unlock your endowment early" lending | **Statutory anti-assignment:** contracts secured on an unpaid endowment are void (precedent: [42 U.S.C. §407](https://www.law.cornell.edu/uscode/text/42/407) for Social Security; UK pension assignment bans — to verify); no legal market in endowment advances can exist |
| Account-takeover and APP fraud at claim | 30-day cooling period between claim and first transfer above a de minimis (figure illustrative: £1,000); confirmation-of-payee-only destinations; delayed-execution default on first large withdrawal |
| Fake investment products targeting the cohort | FCA/SEC financial-promotion rules extended to name endowment recipients as a protected audience; annual pre-payout warning campaign timed to each cohort |
| Mis-selling by regulated firms | Optional **advice voucher**: a funded session with a regulated adviser, redeemable in the claim year; adviser conduct rules apply |
| Coercion within families | Payment only to an account in the recipient's sole name; safeguarding referral route in the claim flow (to be designed with DWP/safeguarding bodies) |

None of these restricts what the recipient may ultimately do — the unconditionality test from §1 is applied to every line of this table.

## 4. Financial capability without paternalism

The support offer is information-rich and mandate-free: statements from 16, a claim-year guidance session (Pension Wise precedent — free, impartial, optional [3]), the advice voucher, and published cohort outcome statistics ([`constitutional-design.md`](constitutional-design.md) §4). Evidence from unconditional transfers — Alaska PFD, GiveDirectly, cited in [`endowment.md`](endowment.md) §5 — does not support fears of systematic dissipation, and the communications strategy should say so pre-emptively rather than defensively ([`../14-communications/inoculation.md`](../14-communications/inoculation.md)). Longer-run behavioural effects are tracked in [`../16-second-order/endowment-effects.md`](../16-second-order/endowment-effects.md) and [`../16-second-order/heirs-and-work.md`](../16-second-order/heirs-and-work.md).

**Student debt.** An offset option lets recipients redeem the endowment against their loan balance at par. It is offered, never defaulted: under income-contingent UK loans, early repayment is value-destroying for low lifetime earners who would never repay in full, and rational mainly for high earners (IFS analysis of Plan 2 repayment — to verify [4]). The claim-flow guidance must present this asymmetry; a state that nudged all graduates to repay would be transferring endowment value straight back to itself. US federal loans, being non-income-contingent in the main, make the offset more often rational — guidance differs by jurisdiction.

## 5. Eligibility and migration edge cases

Baseline rule (parameters open, to be set in legislation): entitlement vests at 25 in **citizens, and settled/permanent residents, with at least 10 years' cumulative residence before the claim** (illustrative parameter). Edge cases:

| Case | Treatment |
|---|---|
| Citizen living abroad at 25 | Entitlement preserved; claimable on taking up residence (aligns the grant with participation in the society funding it); no expiry |
| Arrival at 24 with settled status | Not eligible at 25; residence-years accrue toward a later claim (design choice: entitlement at the *later* of 25 and satisfying residence) |
| Refugees granted protection | Residence clock runs from asylum application date (to verify against precedent in benefits law) |
| Dual nationals / overlapping foreign schemes | Claim requires declaration of comparable foreign grants; offset only if a treaty partner operates a mirror scheme ([`../08-capital-flight/international-coordination.md`](../08-capital-flight/international-coordination.md)) |
| Irish citizens in the UK (CTA) / cross-border workers | Follow residence, not nationality |
| Emigration shortly after claiming | No clawback — the grant is unconditional; the receipts-tax exit rules ([`avoidance.md`](avoidance.md) §4) are the anti-arbitrage backstop on the tax side |

The rule's purpose is to prevent birth-tourism-style arbitrage without creating a stateless-in-practice underclass of young people who grew up here but miss a formality; the residence test, not citizenship alone, carries that weight. Full analysis belongs to [`../07-implementation/hard-cases.md`](../07-implementation/hard-cases.md).

## 6. Commencement and cohort fairness

Any start date creates a neighbour problem: the person who turned 26 the week before receives nothing while funding the scheme through taxes for decades. A cliff invites lasting resentment in a large, politically active cohort. Design: a **commencement taper** — illustrative schedule: those aged 26 at commencement receive £40k, 27 → £30k, 28 → £20k, 29 → £10k, 30+ → nil, payable immediately. Cost: roughly one additional year's endowment spend spread over the taper (illustrative: ~£70bn total across four cohorts at UK scale — a one-off transition cost sitting alongside the revenue ramp in [`revenue-model.md`](revenue-model.md) §5 and [`../15-transition/revenue-bridge.md`](../15-transition/revenue-bridge.md)). The taper does not extend indefinitely backwards; the honest answer to the 45-year-old is that every reform has a start, and they are compensated through the tax cuts in [`tax-interactions.md`](tax-interactions.md) §7 and the system their children inherit. Sequencing detail: [`../15-transition/sequencing.md`](../15-transition/sequencing.md) and [`../15-transition/grandfathering.md`](../15-transition/grandfathering.md).

## 7. Administrative precedents

| Precedent | What it proves | What it warns |
|---|---|---|
| UK Child Trust Fund (2002–11) [2] | Auto-opening millions of accounts against birth records works at low cost | Invisibility breeds dormancy (~£1.7bn unclaimed); engagement must be designed, not assumed |
| Alaska Permanent Fund Dividend (1982–) [5] | Annual mass payment (~600k+ applications) is routine after four decades; near-universal take-up | Application-based model needs a fraud unit; dividend politics are noisy ([`constitutional-design.md`](constitutional-design.md) §6) |
| NEST / auto-enrolment (2012–) [1] | Default funds at national scale, low cost, high inertia benefit | — |
| Sweden AP7 Såfa default fund [6] | A state default investment option can coexist with full individual choice | Choice-overload in the wider PPM menu depressed engagement — keep the menu short |
| Norway GPFG [7] | Fund governance and transparency at sovereign scale — the *governance* precedent, not a citizen-payment one | Norway pays no citizen dividend; the delivery analogue is Alaska, the governance analogue is Norway ([`constitutional-design.md`](constitutional-design.md) §3) |

## Sources

1. [The Pensions Regulator / DWP — Automatic enrolment evaluation reports](https://www.gov.uk/government/collections/automatic-enrolment-evaluation-reports) — participation rates (to verify).
2. [National Audit Office — *Investigation into Child Trust Funds* (2023)](https://www.nao.org.uk/reports/investigation-into-child-trust-funds/).
3. [MoneyHelper / Pension Wise — service model](https://www.moneyhelper.org.uk/en/pensions-and-retirement/pension-wise).
4. [IFS — student loan repayment analysis](https://ifs.org.uk/education-spending/higher-education) (to verify current Plan-year figures).
5. [Alaska Department of Revenue — Permanent Fund Dividend Division, annual reports](https://pfd.alaska.gov/).
6. [AP7 — Såfa default option in the Swedish premium pension](https://www.ap7.se/english/).
7. [Norges Bank Investment Management — Government Pension Fund Global](https://www.nbim.no/en/).
