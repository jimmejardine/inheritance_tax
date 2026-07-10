# Legislative Path: United Kingdom

**Executive summary.** The UK is procedurally the easy case: a majority government can enact the tax through the annual Finance Bill machinery — with anti-forestalling effect from Budget day and the Lords constitutionally unable to block — while the endowment needs its own standalone Act and delivery apparatus. The binding constraints are not parliamentary arithmetic but OBR scoring against the fiscal rules, manifesto pre-commitment (to lock in the Salisbury convention and defuse retrospectivity claims), and a realistic 2–3-session timetable per major phase.

## Two vehicles, not one

| Element | Vehicle | Why |
|---|---|---|
| Tax (basis switch, thresholds, rates, anti-avoidance) | Budget resolutions + annual Finance Bill; possibly a dedicated Taxes Act for the basis switch | Money-bill privileges; commencement-by-announcement; annual amendment cycle for repairs |
| Endowment | Standalone Act (a "Citizens' Endowment Act") | Creates entitlements and a delivery body — outside Finance Bill scope; needs DWP/HMRC machinery, appropriation, and its own political identity |
| Receipts register (Phase 0) | Finance Act provisions + secondary legislation | Extends existing HMRC information powers |

Splitting the vehicles is deliberate: the endowment Act should carry the scheme's name and public identity ([`../14-communications/naming-and-language.md`](../14-communications/naming-and-language.md)), while the tax rides the grey, routine machinery of the Finance Bill.

## The Finance Bill route

**Budget resolutions and same-day effect.** Under the Provisional Collection of Taxes Act 1968, Budget resolutions give tax changes provisional legal effect from announcement, months before the Finance Act receives Royal Assent. This is the statutory basis of the commencement-by-announcement rule in [announcement-effects.md](announcement-effects.md): the rate change and anti-forestalling package take effect at the despatch box.

**Lords limits.** The Parliament Acts 1911–1949 remove the Lords' power to amend or delay money bills (certified by the Speaker) beyond one month. The Finance Bill is the classic money bill: the tax cannot be blocked in the Lords. The endowment Act is *not* automatically a money bill (it creates a programme, not just a charge), so Lords handling matters there — which is where the **Salisbury convention** does the work: the Lords do not wreck legislation delivering a manifesto commitment. Hence a hard design requirement flowing from procedure: **both the tax and the endowment must be explicit manifesto items**, not mid-term surprises. This also strengthens the legitimate-expectation position in [grandfathering.md](grandfathering.md) — the electorate, and the avoidance industry, were on notice. The political question of *getting* it into a manifesto belongs to [`../12-political-adoption/`](../12-political-adoption/README.md).

**Hybrid-bill and human-rights checks.** Section 19 HRA statements of compatibility will be contested on A1P1 grounds; the analysis in [grandfathering.md](grandfathering.md) and [`../10-opposition/legal-challenges.md`](../10-opposition/legal-challenges.md) is what the ministerial statement relies on.

## OBR scoring and the fiscal rules

Every phase is scored by the Office for Budget Responsibility, and the interaction is unusually favourable *and* unusually awkward:

- **Phase 1 (basis switch)** is designed revenue-neutral; the scoring risk is behavioural assumptions about gift re-timing, on which the OBR's published policy costings — collected in its policy measures database — and its IHT forecast methodology provide the template [5].
- **Phase 2** scores as a net cut for most current payers and a rise at the top; the distributional analysis is the political product ([sequencing.md](sequencing.md)).
- **Phase 3** presents the timing mismatch: endowment outlays are certain and immediate; 100%-rate receipts are back-loaded over decades. Under current-style fiscal rules (current-budget balance in-window; debt falling in-window), the naive scoring shows a multi-year deficit — the entire subject of [revenue-bridge.md](revenue-bridge.md). Two treatments matter: whether the endowment is classified as current spending or as a capital transfer/asset-creating vehicle (the fund structure in [revenue-bridge.md](revenue-bridge.md) is partly designed for this), and whether hypothecated borrowing against a legislated future receipt stream can sit outside the operative debt target (precedent: the ONS's December 2018 decision to treat part of student-loan outlay as a capital transfer — the "partitioned loan-transfer approach" — added roughly £12bn a year to the measured deficit at a stroke, demonstrating that classification decisions can move the headline aggregates in either direction [7]).

The honest statement: **fiscal-rule design is endogenous to the policy.** A government committed to Phase 3 will need transition-specific rule language, announced with the policy, not discovered in an OBR footnote.

## Secondary-legislation architecture

Primary legislation should fix what must not drift and delegate what must adapt:

| Fixed in primary legislation | Delegated to secondary (affirmative SIs) |
|---|---|
| Threshold amount and its indexation formula (the anti-erosion lock from [`../05-history/abolitions.md`](../05-history/abolitions.md)) | Valuation methodologies by asset class ([`../07-implementation/valuation.md`](../07-implementation/valuation.md)) |
| The 100% rate; the receipt definition; exemption categories | Reporting formats, register mechanics, penalty administration |
| Sunset requirement on any new relief | Deferral interest-rate resets; appraisal-panel rules |
| Endowment amount, age, unconditionality, indexation | Payment mechanics, identity verification |

Locking indexation and relief-sunsets into primary legislation, and forcing new reliefs through affirmative-resolution daylight, is the procedural encoding of the anti-erosion lessons in [`../05-history/abolitions.md`](../05-history/abolitions.md).

## Devolution

Inheritance tax is a **reserved matter** under the Scotland Act 1998 — fiscal policy, "taxes and excise duties" are reserved by Schedule 5, Part II, Head A1, with exceptions only for specified devolved taxes and local taxes [4] — and under the equivalent Welsh and Northern Ireland settlements: the tax legislates UK-wide, which is essential given the Australian lesson that sub-national assignment is fatal ([`../05-history/abolitions.md`](../05-history/abolitions.md)). Three wrinkles:

- **Precedent pressure.** Scottish income-tax powers (Scotland Act 2016) establish a devolution trajectory; demands to devolve the new receipts tax should be resisted on the tax-competition ground, and the Australian cascade is the argument.
- **The endowment and the Barnett question.** A UK-wide endowment paid directly to individuals bypasses Barnett; alternatively a devolved-delivery model invites divergence in age/amount. Recommendation: reserved, UK-wide, uniform — the entitlement's universality is its political armour.
- **Scots property and trust law** differs — the Scots trust rests on dual patrimony, not the English legal/equitable title split [8], and Scots succession gives children indefeasible "legal rights" (legitim) in the moveable estate [9] — requiring Scots-specific drafting in the receipts definition (see [`../07-implementation/hard-cases.md`](../07-implementation/hard-cases.md)).

## Realistic timetable

| Session | Milestone |
|---|---|
| Pre-election | Manifesto commitment (tax + endowment, explicitly); shadow drafting; register groundwork continues under existing powers |
| Session 1 | Budget-day announcement with immediate anti-forestalling effect; Finance Act 1 legislates basis switch (Phase 1) and register; Endowment Bill introduced |
| Session 2 | Endowment Act passes; pilot payments begin ([pilots.md](pilots.md)); Finance Act 2 repairs Phase-1 defects |
| Session 3 | Phase 2 rate-and-threshold reshaping in Finance Act 3, scored with two years of register data |
| Following parliament(s) | Phase 3 (100% + national endowment) — after re-election on the record, satisfying both Salisbury and the notice principle |

This matches the 10–20-year transit in [sequencing.md](sequencing.md): roughly two parliaments of committed government, plus the infrastructure lead-in. The US equivalent, materially harder, is [legislative-path-us.md](legislative-path-us.md).

## Procedural risks and mitigations

| Risk | Mechanism | Mitigation |
|---|---|---|
| Finance Bill amendment attrition | Committee-stage carve-out lobbying replicates the relief-layering that hollowed out historical regimes ([`../05-history/abolitions.md`](../05-history/abolitions.md)) | Relief-sunset requirement in primary legislation; publish annual effective-rate reports by receipt size |
| Endowment Bill delay in the Lords | Not a certified money bill; convention arguments contested | Explicit manifesto wording; Parliament Acts as backstop (one-year delay maximum) |
| JR of commencement-by-announcement | Challenge to Budget-resolution effect on the anti-forestalling package | PCTA 1968 is settled machinery; the vulnerable element is lookback aggregation, defended on the information-use analysis in [grandfathering.md](grandfathering.md) |
| Machinery-of-government failure | Register or endowment delivery slips, forcing an announced-but-uncommenced gap — the exact scenario [announcement-effects.md](announcement-effects.md) forbids | Phase 0 completed and load-tested before any rate announcement ([sequencing.md](sequencing.md)) |
| Mid-transit change of government | Successor repeals uncommenced phases | Each completed rung is self-defending (Phase 2 repeal = tax rise on ordinary families; Phase 3 repeal = taking £50k from every 25-year-old); see [`../12-political-adoption/wedge-dynamics.md`](../12-political-adoption/wedge-dynamics.md) |

## Sources

1. [Provisional Collection of Taxes Act 1968](https://www.legislation.gov.uk/ukpga/1968/2) — statutory basis for Budget-day effect.
2. [Parliament Act 1911](https://www.legislation.gov.uk/ukpga/Geo5/1-2/13) and [Parliament Act 1949](https://www.legislation.gov.uk/ukpga/Geo6/12-13-14/103) — money-bill certification and Lords limits.
3. [Erskine May — parliamentary practice on Ways and Means resolutions and Finance Bills](https://erskinemay.parliament.uk/).
4. [Scotland Act 1998, Schedule 5, Part II, Head A1 (reservation of fiscal, economic and monetary policy, including taxes and excise duties)](https://www.legislation.gov.uk/ukpga/1998/46/schedule/5/part/II) and [Scotland Act 2016 (income-tax powers)](https://www.legislation.gov.uk/ukpga/2016/11) — the devolution boundary.
5. [OBR — inheritance tax: forecasts in-depth](https://obr.uk/forecasts-in-depth/tax-by-tax-spend-by-spend/inheritance-tax/) and the [OBR policy measures database](https://obr.uk/docs/dlm_uploads/Policy_measures_database_October_2024.xlsx) — costing methodology and behavioural assumptions.
6. [House of Lords Library — "The evolution of the Salisbury convention"](https://lordslibrary.parliament.uk/the-evolution-of-the-salisbury-convention/) — manifesto-bill handling.
7. [ONS (2018). "New treatment of student loans in the public sector finances and national accounts"](https://www.ons.gov.uk/economy/governmentpublicsectorandtaxes/publicsectorfinance/articles/newtreatmentofstudentloansinthepublicsectorfinancesandnationalaccounts/2018-12-17) — the partitioned loan-transfer reclassification, estimated by the OBR to add ~£12bn a year to public sector net borrowing.
8. [Gretton, G. L. "Patrimony Not Equity: the trust in Scotland"](https://www.research.ed.ac.uk/en/publications/patrimony-not-equity-the-trust-in-scotland) — Scots trust law recognises no legal/equitable ownership division.
9. [The Gazette — "What are your legal rights in Scotland for inheritance?"](https://www.thegazette.co.uk/all-notices/content/103869) — children's automatic legal rights in the moveable estate.
