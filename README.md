# 📊 Life Insurance Pricing Engine

An Excel-based actuarial pricing model developed to calculate **Net Premium** and **Gross Premium** for a life insurance product using actuarial pricing principles.

The project demonstrates premium pricing, cash flow projection, expense loading, commission modelling, validation checks, and an interactive dashboard.

---

## Features

- Net Premium Calculation using EPV principles
- Gross Premium Pricing
- Mortality Table Integration
- Discounted Cash Flow Projection
- Initial & Renewal Expense Modelling
- Initial & Renewal Commission Modelling
- Profit Loading
- Interactive VBA-powered Dashboard with automated chart updates
- Automated Validation Checks
- Scenario-based Pricing Inputs

---

## Workbook Structure

| Sheet | Purpose |
|--------|---------|
| Inputs | Product assumptions and pricing inputs |
| Mortality_Table | Mortality rates and survival probabilities |
| Calculations | EPV of Benefits |
| Premium_Calculations | Premium present value calculations |
| Cashflow | Projected policy cash flows |
| Premium | Net & Gross Premium Summary |
| Dashboard | Visual summary of results |
| Checks | Model validation and integrity checks |

---

## Pricing Methodology

The model follows the actuarial pricing equation:

PV(Gross Premiums)

=

PV(Benefits)

+

PV(Expenses)

+

PV(Commissions)

+

PV(Profit)

Net Premium is calculated as:

Net Premium = EPV(Benefits) / Premium Annuity Factor

Gross Premium incorporates:

- Initial Expenses
- Renewal Expenses
- Initial Commission
- Renewal Commission
- Profit Loading

---

## Validation Checks

The model includes automated validation for:

- Input validation
- Interest rate validation
- Premium positivity
- Gross Premium ≥ Net Premium
- Pricing equation reconciliation
- Premium PV Factor validation
- Expense loading validation
- Model status indicator

---

## Dashboard

The dashboard summarizes:

- Net Premium
- Gross Premium
- EPV of Benefits
- Premium PV Factor
- Expense Loading
- Profit Loading
- Model Status

---

## Usage

1. Download the workbook (`Life-Insurance-Pricing-Engine.xlsm`).
2. Open the workbook in Microsoft Excel.
3. Click **Enable Editing** (if prompted).
4. Click **Enable Content** to allow VBA macros to run.
5. Enter the required policy inputs in the **Inputs** sheet.
6. The model automatically calculates premiums, projects cash flows, and updates the dashboard based on the selected policy term.

---

## Important Notes

- This workbook contains VBA macros used to automate dashboard updates.
- Please enable macros when opening the workbook to ensure all automated features function correctly.
- If macros are disabled, all actuarial calculations will continue to work, but dashboard automation will not be available.

---

## Future Enhancements

- Whole Life Insurance Pricing
- Endowment Insurance Pricing
- Pure Endowment Insurance Pricing
- Unit Linked Insurance Plan (ULIP) Pricing

---

## Skills Demonstrated

- Actuarial Pricing
- Life Insurance Mathematics
- Cash Flow Projection
- Excel Modelling
- Financial Mathematics
- Risk Analysis
- Dashboard Design
- Model Validation

## Author

Developed by Yash Upadhaya
