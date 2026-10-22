# Construction & Evaluation of Equity Portfolios – NIFTY FMCG Sector

## Project Overview

This project evaluates six portfolio construction approaches using ten selected companies from the NIFTY FMCG sector over the five-year period from **September 2021 to August 2026**.

The study compares equal-weighted investing, fundamental-score-based allocation, and Markowitz mean-variance optimisation against the NIFTY FMCG index and two professionally managed mutual funds. The analysis examines returns, volatility, diversification, and risk-adjusted performance.

**Initial investment assumed:** ₹1,00,000  
**Data frequency:** Monthly  
**Study period:** September 2021 – August 2026

## Project Objectives

- Analyse the historical risk and return characteristics of ten FMCG stocks.
- Examine the correlation and covariance between selected stocks.
- Construct portfolios using three different weighting approaches.
- Compare the portfolios against an equity index and two mutual funds.
- Evaluate CAGR, annualised volatility, beta, Sharpe ratio, Treynor ratio, and Jensen's alpha.
- Examine the efficient frontier and the trade-off between portfolio risk and return.
- Interpret portfolio suitability across different investor risk profiles.

## Companies Covered

The study includes ten companies representing different FMCG categories:

1. ITC
2. Hindustan Unilever
3. Nestlé India
4. Tata Consumer Products
5. Varun Beverages
6. Britannia Industries
7. Godrej Consumer Products
8. Marico
9. United Spirits
10. Colgate-Palmolive India

## Portfolio Construction Methodology

### Portfolio P1 – Equal-Weighted Portfolio

Each of the ten selected companies receives a fixed allocation of 10%. This approach provides a straightforward diversification benchmark without requiring forecasting or optimisation.

### Portfolio P2 – Fundamentally Weighted Portfolio

Company weights are determined using a composite fundamental score based on:

- Return on Equity (ROE)
- Return on Capital Employed (ROCE)
- Inverse of the Price-to-Earnings (P/E) ratio
- Inverse of the Price-to-Book (P/B) ratio

The four criteria receive equal weights in the composite scoring framework. The resulting scores are normalised to determine portfolio allocations.

### Portfolio P3 – Markowitz Mean-Variance Optimisation

The Markowitz portfolio is constructed by maximising the Sharpe ratio using the covariance structure of the ten stocks.

Constraints:
- Portfolio weights must sum to 100%.
- Short selling is not permitted.
- No individual portfolio weight can be negative.

### Benchmark Portfolios

The three constructed portfolios are compared with:

- **P4:** NIFTY FMCG Index
- **P5:** ICICI Prudential FMCG Fund
- **P6:** Nippon India Consumption Fund

## Data & Research Methodology

The study uses 60 month-end observations, generating 59 monthly returns for the common study period.

Data sources documented in the report include:

- Investing.com – historical stock prices
- NSE Indices – NIFTY FMCG index data
- ICICI Prudential AMC – historical fund NAV
- Nippon India Mutual Fund – historical fund NAV
- Reserve Bank of India – 91-day Treasury bill yields
- Screener.in – company fundamentals and financial ratios

## Risk & Return Metrics

The portfolios are evaluated using:

- Cumulative return
- Compound Annual Growth Rate (CAGR)
- Annualised standard deviation
- Beta
- Sharpe ratio
- Treynor ratio
- Jensen's alpha
- Terminal value of an assumed ₹1,00,000 investment

The study also examines correlation, covariance, and the efficient frontier to understand the relationship between diversification, risk, and expected return.

## Comparative Portfolio Performance

| Portfolio | CAGR | Annualised Risk | Sharpe Ratio | Ending Value |
|---|---:|---:|---:|---:|
| P1 – Equal Weight | 7.66% | 16.68% | 0.186 | ₹1,43,757 |
| P2 – Fundamental Weight | 7.28% | 16.98% | 0.165 | ₹1,41,289 |
| P3 – Markowitz Optimised | 24.59% | 28.48% | 0.716 | ₹2,94,756 |
| P4 – NIFTY FMCG Index | 2.67% | 16.11% | −0.109 | ₹1,13,850 |
| P5 – ICICI Prudential FMCG Fund | 3.63% | 13.66% | −0.086 | ₹1,19,169 |
| P6 – Nippon India Consumption Fund | 11.74% | 15.10% | 0.437 | ₹1,72,584 |

*Figures are historical results reported by the project and are not forecasts of future performance.*

## Key Findings

### 1. Portfolio Weighting Influenced Performance

The six portfolios produced substantially different outcomes despite being evaluated over the same historical period. The weighting methodology was an important driver of the differences.

### 2. Markowitz Optimisation Delivered the Highest Historical Return

Portfolio P3 recorded a CAGR of 24.59%, a Sharpe ratio of 0.716, and an ending value of ₹2,94,756 from an initial investment of ₹1,00,000.

However, it also recorded the highest annualised volatility at 28.48%.

### 3. Optimisation Produced a Concentrated Allocation

The Markowitz portfolio allocated approximately 73.28% to Varun Beverages, 20.43% to United Spirits, and 6.29% to Marico.

This concentration demonstrates that an unconstrained maximum-Sharpe optimisation can generate highly concentrated portfolios.

### 4. Equal Weighting Outperformed Fundamental Weighting

The equal-weighted portfolio ended at ₹1,43,757, compared with ₹1,41,289 for the fundamentally weighted portfolio. The results indicate that the additional fundamental scoring framework did not improve returns over this particular period.

### 5. The Consumption Fund Outperformed the Sector Index

The Nippon India Consumption Fund recorded a CAGR of 11.74%, compared with 2.67% for the NIFTY FMCG index, while also reporting lower annualised volatility than the constructed equity portfolios P1 and P2.

### 6. Historical Results Require Careful Interpretation

The optimisation used realised returns, volatilities, and correlations from the same period over which performance was evaluated. Consequently, the results are affected by hindsight and do not demonstrate that the same portfolio weights could have been selected in advance.

## Efficient Frontier Analysis

The efficient frontier illustrates the combinations of portfolio return and risk available within the selected ten-stock universe under long-only constraints.

The maximum-Sharpe portfolio sits on the frontier, but the concentration in a small number of stocks highlights the trade-off between maximising historical risk-adjusted returns and maintaining diversification.

## Limitations

- The optimisation uses the same historical period for portfolio construction and evaluation.
- The study covers a single five-year window.
- Transaction costs, brokerage, taxes, and rebalancing are excluded.
- The analysis uses price-return data for individual stocks and the index rather than
