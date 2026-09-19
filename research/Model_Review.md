# Model review

Reviewed 19 September 2026. Scope: consolidated FY2022–FY2026 history, FY2027–FY2031 forecast, DCF and reverse DCF.

## Corrections

| Area | Correction |
| --- | --- |
| Historical cash flow | Replaced standalone figures with consolidated figures. Removed the unsupported FX balancing adjustment. |
| Restated earnings | Used later comparatives, including FY2022 PAT of INR 51.0937 crore and FY2024 tax of INR 45.2931 crore. |
| Exceptional income | Kept FY2023 exceptional income separate from recurring operating EBITDA. |
| Balance-sheet mapping | Corrected goodwill, intangibles, other assets, liabilities and FY2025 supplier-finance reclassification. Removed negative balancing amounts. |
| Forecast interest | Applied interest rates to opening borrowings and lease liabilities, not revenue. |
| Fixed assets and equity | Linked PPE/CWIP commissioning, depreciation and amortisation. Retained earnings deduct actual forecast dividends. |
| Funding | Added explicit cash-shortfall borrowing and surplus debt repayment, without circular formulas. |
| DCF | Applied one WACC to annual cash flows and terminal value. Included terminal reinvestment and retained operating cash. |
| Reverse DCF | Solved the margin uplift required to reproduce reference enterprise value. |
| Price and dates | Removed the unsupported quote date. Screener price is an undated reference input. |
| Operating cash reserve | Included annual increases in required operating cash in FCFF. The opening reserve remains excluded from excess cash. |
| Cash-flow classification | Classified forecast finance costs as financing cash flow and interest receipts as investing cash flow, consistent with historical reporting. Closing cash and profit are unchanged. |
| Reverse DCF working capital | Included the effect of changing margins on inventory and payables. Validated against the same three-statement model with unequal inventory and payable days. |
| Presentation | Removed floating-point negative-zero differences. Reference-price and discount-factor formats retain appropriate precision. |

## Verification

- Compared 11 metrics across five years with Screener: revenue, PBT, tax, PAT, depreciation, finance costs, CFO, CFI, CFF, receivables and inventory. All 55 comparisons agree within INR 0.011 crore.
- Reconciled historical asset and liability components to audited totals, historical profit to reported profit, and cash flows to closing cash.
- Explained Screener asset-total differences through deferred-tax netting. Debt including leases and cash including other bank balances reconcile within source rounding.
- All five forecast balance sheets balance. Cash-flow closing cash equals balance-sheet cash. Minimum cash and non-negative debt constraints hold.
- Independently recomputed DCF discounting and confirmed reverse DCF reproduces reference enterprise value.
- Tested a higher terminal-year margin, INR 250 crore of additional first-year capex, and unequal inventory/payable days. Applying the reverse-implied margins to the full model reproduces reference enterprise value. Valuation and funding respond, balance sheets remain balanced, and history stays unchanged. Restored the base case afterward.
- Recalculated and scanned with the spreadsheet calculation engine; no unexpected formula errors were found. Native Microsoft Excel recalculation was not independently tested.

## Reported EBITDA reconciliation

| INR crore | FY2025 | FY2026 |
| --- | ---: | ---: |
| Operating EBITDA | 312.89 | 469.37 |
| Other income | 16.64 | 11.57 |
| Pre-tax OCI | 4.58 | 11.97 |
| Sum | 334.11 | 492.91 |
| Management-reported EBITDA | 334.11 | 492.91 |
| Difference | 0.00 | 0.00 |

Sources: Pricol Annual Report FY2026 and Investor Presentation May2026. The two-year arithmetic bridge reconciles fully. It does not establish an explicit management policy for the EBITDA measure. OCI is separate from operating profit, and is not forecast. The model's operating-margin denominator includes other operating revenue; management's reported margin denominator excludes it.

## Remaining interpretation limits

- Growth, margins, working-capital days, WACC and terminal ROIC are analytical assumptions, not guaranteed outcomes.
- Other balance-sheet accounts remain constant, with no new acquisitions, demerger accounting, OCI or deferred-tax movements.
- Borrowing and surplus repayments occur at year-end. Interest uses opening balances; actual earlier funding could increase interest expense.
- INR 766.75 is an undated reference price. The resulting 32.7% implied FY2031 margin is a conditional pricing requirement, not a management target or base-case assumption. The linear solve assumes positive EBIT in each year.

The DCF is INR 159.10 per share after including operating-cash investment. Excluding that investment would overstate value by INR 2.62 per share under the base assumptions.
