# nike-revenue-analysis
Revenue growth analysis of Nike, FY2022-FY2026, in Python
# Nike Revenue Analysis (FY2022-FY2026)

A Python analysis of Nike's annual revenue over five fiscal years: totals, average, year-over-year growth, CAGR and a bar chart.

## Data
## Data
Revenue in $ millions, from Nike's SEC filings and earnings releases. Nike's fiscal year ends May 31, so "FY2026" covers June 2025 through May 2026.

| Fiscal year | Revenue ($M) | Source |
| FY2022 | 46,710 | [Nike FY2022 Form 10-K](https://www.sec.gov/Archives/edgar/data/320187/000032018722000038/nke-20220531.htm) |
| FY2023 | 51,217 | [Nike FY2023 Q4 earnings release](https://www.businesswire.com/news/home/20230629371330/en) |
| FY2024 | 51,362 | [Nike FY2024 Form 10-K](https://www.sec.gov/Archives/edgar/data/320187/000032018724000044/nke-20240531.htm) |
| FY2025 | 46,309 | [Nike FY2025 Q4 earnings release](https://www.businesswire.com/news/home/20250626256960/en/nike-inc.-reports-fiscal-2025-fourth-quarter-and-full-year-results) |
| FY2026 | 46,398 | [Nike FY2026 Form 10-K](https://investors.nike.com/sec-filings/all-sec-filings/content/0000320187-26-000088/nke-20260531.htm) |

## What the code does
- Calculates total, average and overall revenue growth
- Calculates year-over-year growth with a loop
- Calculates CAGR with a reusable function
- Plots revenue by fiscal year with matplotlib

## Key findings
- Revenue was $46,710M in FY2022 and $__46,398__M in FY2026, an overall change of -0.7%.
- CAGR over the four years was -0.2%.
- The biggest rise was in FY2023 (+9.6%), and the biggest drop was in FY2025 (-9.8%).
-The bar chart shows Nike’s revenue rising from about $46.7B in FY2022 to a peak of about $51.4B in FY2024. It then dropped to about $46.3B in FY2025 and stayed nearly flat at $46.4B in FY2026, leaving revenue close to where it started.

## Tools
Python, matplotlib, Google Colab
