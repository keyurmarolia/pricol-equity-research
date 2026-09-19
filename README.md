# Pricol Equity Research

**How do growth, capital investment and operating margins translate into equity value?**

An Excel study of Pricol Limited combining five years of consolidated financial history, an integrated three-statement forecast, DCF and reverse DCF. The research separates reported performance, analyst assumptions and the operating expectations embedded in a reference price.

## Results at a glance

| Measure | Model result |
| --- | ---: |
| FY2026 revenue | INR 4,040.8 crore |
| FY2031 forecast revenue | INR 6,306.3 crore |
| Base DCF value per share | INR 159.10 |
| Base FY2031 operating EBITDA margin | 11.8% |
| Reverse-implied FY2031 operating EBITDA margin | 32.7% |

The reverse DCF uses an **undated INR 766.75 reference price**, holding revenue, capex and working-capital days at base assumptions. The implied margin is a conditional pricing requirement, not a forecast or management target. The DCF uses FY2026 closing balances and information reviewed through **19 September 2026**; it is not a live-price valuation.

![Revenue history and forecast, with base and reverse-implied EBITDA margins](docs/assets/results-preview.png)

## Explore the research

- **[Download the Excel model](https://github.com/keyurmarolia/pricol-equity-research/raw/refs/heads/main/model/Pricol_Equity_Research.xlsx)** — start with `00_Cover`, then `05_Assumptions`, `10_DCF` and `11_Reverse_DCF`.
- **[Read the model review](research/Model_Review.md)** — reconciliations, valuation treatment and remaining limitations.
- **[View the source register](data/source_register.csv)** — original company filings, presentations and transcripts.

Open the downloaded workbook in Microsoft Excel. Blue numbers are editable inputs, green numbers link to another worksheet, and black numbers are calculations or summary results. Historical statements cover FY2022–FY2026; forecasts cover FY2027–FY2031. Amounts are INR crore unless stated otherwise.

## Workbook structure

| Area | Worksheets |
| --- | --- |
| Starting point | Cover, sources and historical financials |
| Research inputs | Historical analysis, industry data and assumptions |
| Integrated model | Schedules, income statement, balance sheet and cash flow |
| Valuation | DCF and reverse DCF |

## Model design

The acquisition of the injection-moulded plastics business on 31 January 2025 affects year-on-year comparability. Core-business growth moderates from 12% to 7%. Plastics growth starts at 5% on a base excluding the exited foaming business, rises to 15% as capacity becomes available, and moderates thereafter. Operating EBITDA margins range from 11.3% to 11.8%. These are analyst assumptions, not management guidance.

The forecast includes INR 700 crore of capex across FY2027–FY2028, working-capital investment, depreciation, leases, interest and dividends. Explicit borrowing maintains minimum cash, and surplus cash repays debt. No acquisition or demerger uplift is assumed. Other balance-sheet accounts remain constant. Industry data provides context for assumptions rather than mechanically determining revenue.

## Valuation and limitations

The base DCF produces **INR 159.10 per share**, using 12.5% WACC, 4% perpetual growth and 12% terminal ROIC. Annual free cash flow funds increases in required operating cash as well as fixed assets and working capital. Terminal cash flow includes total operating reinvestment at growth divided by ROIC. Lease liabilities are financing and new lease assets are included in investment. Only excess cash above the operating reserve and current investments are added to enterprise value.

The reverse DCF solves the EBITDA-margin uplift required to support the reference share price, holding revenue, capex and working-capital days constant. Inventory and payables respond to the implied operating costs. At INR 766.75, it implies a FY2031 operating EBITDA margin of **32.7%**, compared with 11.8% in the base case. This is an implied requirement, not a forecast. The linear margin solve assumes positive operating EBIT.

The Screener export provides no quote date. Valuation uses FY2026 closing balances and subsequent management commentary, reviewed through 19 September 2026. This is neither a live-price valuation nor a point-in-time backtest.

Operating EBITDA excludes other income, exceptional items and other comprehensive income (OCI). For both FY2025 and FY2026, management-reported EBITDA equals operating EBITDA plus other income and pre-tax OCI. This is an arithmetic reconciliation, not an explicit management definition. OCI is not forecast. Management's margin also uses a revenue denominator excluding other operating revenue. Screener nets deferred-tax assets in its balance-sheet presentation, while the model retains audited gross balances.

[Model review](research/Model_Review.md) records corrections, verification and remaining limitations. This is an educational equity-research model, not an investment recommendation.


## Sources and scope

Audited consolidated annual reports are the primary historical source, using later comparative figures where restated or reclassified. A supplied Screener export is a secondary cross-check. Original third-party PDFs and the Screener export are not redistributed; use the source register to obtain company documents. The workbook retains the financial inputs needed to follow the calculations.

## Related projects

- [InterGlobe Aviation equity research](https://github.com/keyurmarolia/interglobe-aviation-equity-research-model)
- [Momentum in Indian equities](https://github.com/keyurmarolia/momentum-in-indian-equities-research)
- [IFRS 9 mortgage ECL](https://github.com/keyurmarolia/ifrs9-mortgage-ecl)
- [Basel credit capital](https://github.com/keyurmarolia/basel-credit-capital-engine)
- [FRTB market risk](https://github.com/keyurmarolia/frtb-market-risk-engine)
