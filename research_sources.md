# Research Sources for Apple Inc. (AAPL) Investment Analysis

## Financial Data Sources
- **Current Stock Info & Key Statistics**: `get_stock_info` (Yahoo Finance) – 2024‑12‑02.
- **Historical Daily Prices**: `get_historical_stock_prices` (Yahoo Finance) – 2024‑06‑01 to 2024‑11‑30.
- **Annual Income Statement & Balance Sheet**: `get_financial_statement` (Yahoo Finance / SEC 10‑K) – FY 2024.
- **Top Institutional Holders**: `get_holder_info` (Yahoo Finance / 13F filings) – Q3 2024.
- **Analyst Recommendations**: `get_recommendations` (Yahoo Finance / MarketBeat) – last 12 months.
- **Recent News Articles**: `get_yahoo_finance_news` – top 10 headlines as of 2024‑12‑02.

## Background Research
- **Company Overview & History**: Wikipedia article "Apple Inc." – retrieved via `search`.
- **Investor Relations Information**: Apple Investor Relations page – scraped with `browse`. Includes:
  - Quarterly earnings press releases and financial statements links.
  - SEC filings (10‑K, 10‑Q) archive URLs.
  - Dividend history, capital return timeline, and green bond report.
  - Leadership, governance, and ESG information.

## Repository & Project Documentation
- Repository: `mohaintsafcasen/aapl-investment-analysis`
- Branch: `financial-research`
- Files added: `financial_metrics.md`, `research_sources.md`
- Issue created: **Quarterly Earnings Deep Dive** (label: analysis).
- Issue comment lists three deeper‑dive metrics: Revenue Growth Rate, Operating Margin, Free Cash Flow.

---
*All URLs are current as of the data retrieval dates listed above.*