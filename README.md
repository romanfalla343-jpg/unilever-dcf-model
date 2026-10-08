# Unilever DCF Valuation

A five-year discounted cash flow (DCF) valuation of Unilever plc (LSE: ULVR), built in Excel using FY2025 reported financials and forecasts for FY2026E–FY2030E.

The model values Unilever using an unlevered free cash flow DCF with a Gordon Growth terminal value, alongside an EV/EBITDA exit multiple cross-check. Sensitivity analysis is included for WACC, terminal growth and exit multiples.

## Valuation Summary

| Valuation Method | Implied Share Price |
|---|---:|
| Gordon Growth DCF | **£44.20** |
| Exit Multiple DCF | **£45.94** |
| Market Reference Price | **£46.23** |

The two valuation methods produce broadly similar results, with the exit multiple approach approximately 3.9% above the Gordon Growth valuation.

## Key Features

- FY2025 actuals rebased from Unilever's reported continuing operations
- Five-year forecast period covering FY2026E–FY2030E
- Revenue and EBIT margin forecasting
- Unlevered free cash flow (UFCF) calculation
- 8.2% DCF WACC
- Gordon Growth terminal value
- EV/EBITDA exit multiple cross-check
- Enterprise value to equity value bridge
- Net debt and non-controlling interest adjustments
- Retained TMICC stake included as a non-operating asset
- WACC vs terminal growth sensitivity analysis
- WACC vs exit EV/EBITDA sensitivity analysis

## Methodology

### Operating Forecast

The model begins with FY2025 reported continuing-operations financials and forecasts revenue, EBIT and free cash flow through FY2030.

Revenue growth and EBIT margins are modelled explicitly rather than applying a single terminal assumption throughout the forecast period.

### Free Cash Flow

Unlevered free cash flow is calculated as:

**UFCF = NOPAT + D&A − Capex + Change in NWC**

This provides the cash flow available to both debt and equity holders before financing costs.

### DCF Valuation

The primary valuation uses an 8.2% WACC and a 2.5% terminal growth rate.

The terminal value is calculated using the Gordon Growth Method:

**Terminal Value = UFCF × (1 + g) / (WACC − g)**

The present value of forecast UFCF and terminal value are then combined to calculate enterprise value.

### Equity Value

Enterprise value is converted to equity value by adjusting for:

- Net debt
- Non-controlling interests
- Retained value of the TMICC stake

The resulting equity value is divided by shares outstanding to calculate the implied share price.

### Exit Multiple Cross-Check

The model also values Unilever using a **12.0x FY2030E EV/EBITDA exit multiple**.

This provides an alternative terminal-value framework and acts as a cross-check against the Gordon Growth valuation.

## Sensitivity Analysis

The model includes two sensitivity tables:

1. **WACC vs Terminal Growth**
2. **WACC vs Exit EV/EBITDA Multiple**

These illustrate how changes in terminal assumptions affect the implied share price and highlight the sensitivity of DCF valuations to the cost of capital and terminal value assumptions.

## Model Structure

| Sheet | Purpose |
|---|---|
| `Cover` | Model overview and methodology |
| `Assumptions` | Key valuation and operating assumptions |
| `FY25 Actuals EUR` | Reported FY2025 source figures |
| `Income Statement & FCF` | Forecast financials and UFCF |
| `DCF Valuation` | Primary DCF and exit multiple valuation |
| `Sensitivity Analysis` | Valuation sensitivity tables |
| `Review Notes` | Model checks and review notes |

## Data & Sources

Financial data is based primarily on Unilever's FY2025 reporting.

Reported EUR financials are converted into GBP for the model. P&L and cash-flow items use the relevant FY2025 average EUR/GBP conversion assumption, while balance-sheet items use a separate year-end FX assumption.

The workbook contains the underlying FY2025 reported figures and model assumptions used in the valuation.

## Disclaimer

This project is for educational and portfolio purposes only and does not constitute investment advice or a recommendation to buy or sell securities.

All valuation outputs are dependent on the assumptions used in the model, including revenue growth, EBIT margins, WACC, terminal growth and exit multiples.
