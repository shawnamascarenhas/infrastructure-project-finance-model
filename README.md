# Solar Project Finance Model - Operating Guide

## Purpose

This portfolio case models the construction, financing, operation, and investor returns of an illustrative 100 MWac Indian solar project. It is designed to demonstrate project-finance modelling discipline rather than recommend a real transaction.

## How to operate the model

1. Open `01_Solar_Project_Finance_Model.xlsx` in Microsoft Excel.
2. Start on `Dashboard` for the investment summary, credit metrics, scenario comparison, and charts.
3. Change the active case only in the case selector on `Assumptions`. Available cases are Downside, Base, and Upside.
4. Edit blue-font assumption cells only. Review the source ID beside each key input and update `Sources` when replacing a benchmark.
5. Review construction and operating schedules before interpreting returns. The calculation flow is: `Assumptions` -> `Timeline` / `Construction` / `Operations` -> `Tax` / `Financial_Statements` -> `Debt` -> `Cash_Waterfall` -> `Returns` -> `Dashboard`.
6. Confirm `Checks` shows `OK` and zero failed checks after every material input change.
7. Use `Sensitivities` to assess return and debt-capacity changes. These tables supplement, but do not replace, a fixed-base-debt downside test.
8. Save a new version before changing transaction assumptions. Do not overwrite the portfolio base case.

## Core outputs

- Project IRR, project NPV, equity IRR, equity NPV, equity MOIC, and equity payback
- Sources and uses, debt sizing, sculpted amortisation, DSCR, LLCR, and DSRA
- Base, downside, and upside cases plus two-variable sensitivities
- Integrated income statement, balance sheet, and cash-flow statement
- Twenty-four model checks and seven deliberate QA shocks

## Important interpretation

The base case is credit-feasible but does not clear the modelled return hurdles. Each scenario independently resizes and sculpts debt, so the scenario minimum DSCR is not a fixed-debt resilience test. For an investment decision, rerun downside assumptions using the committed base-case debt quantum and add asset-specific irradiation, curtailment, offtaker, EPC, tax, and legal diligence.

## Package contents

- `01_Solar_Project_Finance_Model.xlsx` - final QA-tested Excel model
- `02_Investment_Memorandum.pdf` - two-page investment case and recommendation
- `03_Model_Methodology.pdf` - one-page calculation and control methodology
- `04_Assumptions_and_Sources.pdf` - one-page assumptions and public-source summary
- `05_Output_Dashboard.pdf` - one-page PDF of the model dashboard

## Model status

Version 1.7. All 24 core checks and all seven deliberate shock tests pass. This remains an illustrative academic portfolio model, not financial advice.
