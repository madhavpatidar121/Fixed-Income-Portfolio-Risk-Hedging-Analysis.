# Fixed-Income-Portfolio-Risk-Hedging-Analysis.


## Project Overview

This project analyzes the interest-rate exposure of a multi-instrument fixed-income portfolio and evaluates the effectiveness of a static hedge under changing market conditions.

The analysis includes portfolio valuation, interest-rate stress testing, hedge construction, and hedge effectiveness measurement across multiple valuation dates.

## Objectives

The primary objectives of the project were to:

* Value a portfolio of fixed-income and interest-rate instruments.
* Measure portfolio sensitivity to changes in interest rates.
* Evaluate portfolio performance under a parallel yield-curve shock.
* Construct a hedge to reduce interest-rate exposure.
* Measure how hedge effectiveness changes over time.
* Identify risks caused by duration and maturity mismatches.

## Portfolio Characteristics

The portfolio includes instruments with exposure to:

* SOFR
* LIBOR
* Federal Funds rates
* Fixed interest rates

The instruments contain different:

* Notional amounts
* Maturities
* Payment frequencies
* Day-count conventions
* Interest-rate exposures

## Methodology

### 1. Portfolio Valuation

Each instrument was valued using its projected cash flows and applicable discount rates.

The portfolio was revalued across multiple month-end dates during 2025 to observe how changes in market rates and remaining maturity affected portfolio value.

### 2. Interest-Rate Stress Testing

A parallel **+50 basis point interest-rate shock** was applied to evaluate the portfolio's sensitivity to rising interest rates.

The portfolio was then revalued under the shocked rate environment.

This allowed the analysis to measure changes in present value resulting from movements in the yield curve.

### 3. Hedge Construction

A one-year fixed-rate hedge instrument was introduced to offset a portion of the portfolio's initial interest-rate exposure.

The hedge position was calibrated based on the portfolio's initial exposure.

### 4. Hedge Effectiveness Analysis

The analysis compared:

* Original portfolio value
* Shocked portfolio value
* Hedged portfolio value
* Shocked hedged portfolio value

across different valuation dates.

This demonstrated how the hedge performed as market conditions and portfolio duration changed over time.

## Key Findings

The interest-rate hedge reduced the portfolio's sensitivity to rate movements at the initial valuation date.

However, hedge effectiveness declined over time because the portfolio and hedge experienced different changes in:

* Duration
* Remaining maturity
* Yield-curve exposure
* Cash-flow timing

This highlights the limitations of using a static, single-maturity hedge for a portfolio containing multiple instruments with different maturity profiles.

A more effective risk-management framework could involve periodically rebalancing the hedge or using multiple hedging instruments across different maturities.

## Skills Demonstrated

* Fixed-Income Valuation
* Portfolio Analysis
* Interest-Rate Risk Management
* Scenario & Stress Testing
* Hedging
* Present Value Analysis
* Yield-Curve Analysis
* Duration Risk
* Microsoft Excel
* Financial Modeling

## Tools Used

* Microsoft Excel
* Financial Modeling
* Interest-Rate Scenario Analysis



