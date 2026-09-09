# Regal-Altra-Merger-Model

Accretion/dilution analysis of Regal Rexnord's (NYSE: RRX) $62.00 per share all-cash acquisition of
Altra Industrial Motion (Nasdaq: AIMC), announced October 26, 2022 and closed March 27, 2023.

Every input comes from information public as of **March 1, 2023**, the date Altra
filed its FY2022 10-K and roughly four weeks before close. Three checks reconcile model output to
figures Regal Rexnord disclosed separately.

---

## Conclusion

Dilutive on GAAP EPS, accretive on cash and adjusted EPS. The GAAP dilution is purchase accounting,
not economics.

| | GAAP | Cash | Adjusted |
|---|---:|---:|---:|
| Acquirer standalone EPS | $7.29 | $7.29 | $10.31 |
| Pro forma EPS | $6.61 | $7.86 | $11.37 |
| Accretion / (dilution) | **($0.68)** | **$0.57** | **$1.06** |
| % | **(9.3%)** | **+7.8%** | **+10.3%** |
| Synergies to breakeven | **$56.5mm** | — | — |

The GAAP result is non-cash: $89.6mm of intangible write-up amortization, $5.5mm of incremental
depreciation, and $8.7mm of financing-fee amortization account for the whole gap to the cash
figure. Sensitivity testing shows the outcome turns on synergies rather than financing — moving the
debt-funded share of consideration from 82% to 100% shifts cash accretion by about $0.20, because
the 6.20% cost of new debt sits close to the yield on the cash it displaces.

---

## Transaction and financing

| | |
|---|---|
| Offer | $62.00 per share, 100% cash; 54.0% premium to the $40.26 unaffected close (10/26/22) |
| Equity value / EV | $4,101.3mm / $4,936.9mm |
| EV / CY2022 adjusted EBITDA | 12.7x (announced: ~13.1x) |
| Target debt | Refinanced ($1,044.5mm) |
| Tax structure | Stock sale — no step-up; DTLs recognized on write-ups |

Regal Rexnord priced $4.7bn of senior notes on January 9, 2023 and closed January 24 — before the
modeling date, so the capital structure is a fact, not an assumption. Three inputs derive from it:
the **6.20%** blended rate (principal-weighted coupon across the 2026, 2028, 2030 and 2033
tranches), the **6.3-year** term (principal-weighted tenor), and the **1.13%** financing fee
($4,700mm gross vs. ~$4,647mm net proceeds).

| Pro forma credit statistics | |
|---|---:|
| Total new debt | $4,892.9mm |
| Gross / net debt | $6,916.4mm / $6,422.5mm |
| Gross debt / adjusted EBITDA | 4.61x |
| Net debt / synergized adjusted EBITDA | 3.87x |

Management guided to 2.5x–3.0x net leverage in 2024.

---

## Three EPS measures

| | Excludes | Pro forma |
|---|---|---:|
| **GAAP** | Nothing | $6.61 |
| **Cash** | Deal-related D&A and financing-fee amortization only | $7.86 |
| **Adjusted** | All intangible amortization, restructuring, transaction costs | $11.37 |

**Each needs its own standalone benchmark.** Cash EPS adjusts only for what the deal *creates*, so
standalone Cash EPS equals GAAP at $7.29. Adjusted EPS adjusts for items that exist regardless of
the deal, so the $10.31 standalone applies the same acquirer-side add-backs used in the pro forma
column. Benchmarking pro forma adjusted EPS against a GAAP standalone would report accounting
convention as deal accretion.

Add-backs are sourced from FY2022 primary filings and detailed on the Data Sources tab. Share-based
compensation and the inventory step-up are excluded, and are the reconciling items against
management's definition.

---

## Reconciliation to disclosed

| | Model | Disclosed | Variance |
|---|---:|---:|---:|
| Goodwill created | $2,695.7mm | $2,614.6mm | +3.1% |
| Offer value (equity) | $4,101.3mm | ~$4,110mm | (0.2%) |
| Acquirer standalone adjusted EPS | $10.31 | ~$10.74 | (4.0%) |

PPA inputs — 30% PP&E write-up over 15 years, 120% intangible write-up over 13 — were set as
ex-ante estimates, not calibrated to the disclosed result, so the goodwill variance is an output
rather than an input. Intangibles are deliberately written up far more than PP&E: a target's book
intangibles reflect only what prior acquisitions capitalized, since internally developed customer
relationships, trade names, and technology never hit the balance sheet, while PP&E is carried at
depreciated cost and sits much closer to fair value.

The EPS check ties to Regal Rexnord's reported FY2022 adjusted diluted EPS (9M $8.10 + Q4 $2.64);
the $0.43 gap is share-based compensation, the inventory step-up, and discrete tax items — exactly
the items scoped out.

---

## Structure

Seven tabs: **Cover** (live headline result, legend), **Summary**, **Assumptions**, **Pro Forma BS**,
**Accretion Dilution** (three EPS builds, six sensitivity tables), **Shares**, **Data Sources**.

Flow runs Assumptions → Pro Forma BS → Accretion Dilution → Summary. Sensitivity inputs sit on the
Accretion Dilution tab because Excel data tables require a same-sheet input cell.

Color: blue = hardcoded input, green = direct cross-tab reference, black = computed, red = external
link (none). Blue also marks Pro Forma BS cells that sum raw 10-K line items — inputs in substance,
formulas in form, with components named in cell comments.

---

## Method

**Basis.** Static single-period pro forma on FY2022 actuals, crediting full run-rate synergies. A
fully-synergized "as-if" construct, not a year-one forecast — structurally comparable to the
Regulation S-X Article 11 pro forma an acquirer files after close.

**Refinancing interest.** Built gross, not netted: 6.20% charged on all new borrowings ($303.4mm),
with Altra's actual FY2022 interest expense of $51.5mm added back separately since that debt is
retired and its cost already sits inside Altra's reported net income. Netting the two — the common
shortcut — would price Altra's pre-2022 debt at Regal Rexnord's 2023 cost of capital and understate
pro forma interest by roughly $13mm pretax.

**EBITDA.** Adjusted, from each company's Q4 2022 earnings release reconciliation: $1,111.7mm (RRX)
and $388.5mm (AIMC).

**Taxes.** Acquirer's 19.4% effective rate across all transaction adjustments, including the
eliminated target interest. The target's 32.9% rate is documented but not separately applied.

**Sensitivities.** Two tables per EPS measure: synergies ($140–180mm) × rate (5.70%–6.70%), and
offer price ($58–66) × debt-funded share (82%–100%). Ranges bracket the actual $62 and 91%.

Every derived input is documented on the Data Sources tab with source and page, and carries a cell
comment.

---

## Scope

- **Single period.** No synergy phasing, debt amortization, or forward forecast. Whether Regal
  Rexnord cleared the ~35% needed for GAAP breakeven, and whether it hit 2.5x–3.0x by 2024, are
  questions this model frames and does not answer.
- **All-cash.** Stock-consideration mechanics are built and toggle correctly but aren't exercised
  by this deal.
- **Balance sheet only.** No pro forma income statement.

---

*Tyler Spencer. Completed September 2026; analysis performed on information available as of
March 1, 2023.*
