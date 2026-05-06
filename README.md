# EREGL Equity Research — DCF Valuation Model

A comprehensive Discounted Cash Flow (DCF) valuation model for Ereğli Demir ve Çelik (EREGL.IS), Turkey's largest integrated steel producer, listed on Borsa İstanbul.

This is an independent learning project prepared by me as part of equity research portfolio.

## Key Outputs

| Metric | Value |
|---|---|
| Recommendation     | HOLD / REDUCE   |
| Target Price (DCF) | 25.22 TL        |
| Current Price      | 35.12 TL        |
| Implied Downside   | −28%            |
| WACC               | 14.83%          |
| Terminal g         | 2.5%            |
| Exit Multiple      | 10.0x EV/EBITDA |

## Files

- `EREGL_DCF_Model.xlsx` — Full Excel valuation model (6 sheets):
  - `isyatirim` — Source financials (TAS 29 inflation-adjusted real TL, from İş Yatırım database)
  - `Historical` — 6-year cleaned historical financials and trend analysis
  - `Projections_TL` — 5-year FCFF projections with assumptions
  - `WACC` — WACC calculation using Damodaran 2025 country-risk methodology
  - `DCF` — Enterprise Value, Equity Value, and Implied Share Price
  - `Sensitivity` — 5×5 WACC × terminal-g sensitivity table
  - `Comps` — Comparable companies analysis (KRDMD, Nucor, ArcelorMittal)

- `EREGL_Equity_Research_v1.pdf` — One-page sell-side style research note

## Methodology Highlights

- Real TL framework — TAS 29 inflation-adjusted financials throughout the model for internal consistency
- WACC computed via Damodaran's country-adjusted CAPM (Türkiye total ERP = 10.87%)
- Terminal Value = average of Gordon Growth (g = 2.5%) and Exit Multiple (10.0x EBITDA)
- Triangulation with comparable companies analysis (peer median EV/EBITDA = 7.65x)
- Comps use nominal LTM data; multiples are dimensionless and currency-neutral

## Disclaimer

This is a personal educational project, not investment advice. The author holds no position in EREGL.IS at the time of writing. All data sourced from publicly available filings (KAP), İş Yatırım, Borsamatik, Macrotrends, WallStreetZen, and Damodaran's NYU Stern data archive.
