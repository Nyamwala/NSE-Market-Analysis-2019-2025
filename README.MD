# Nairobi Securities Exchange (NSE) Market Analysis (2019–2025)

## 📌 Project Overview

This project is an end-to-end data analytics capstone evaluating market resilience, risk-adjusted returns, crash drawdowns, and liquidity disparities across the Nairobi Securities Exchange (NSE) from **2019 to 2025**. By analyzing over **121,000 daily trading records** across 72 listed counters and 10 market indices, this repository provides clear, data-driven insights into how Kenyan equities weathered major economic shocks like the COVID-19 pandemic, interest rate shifts, and the 2022 general elections.

## 🚀 Key Functionalities & Roles

1. Multi-Year Data Harmonization
   * Role: Standardizes 7 years of daily trading records and official sector mapping tables into a unified analytical pipeline.

2. Risk-Adjusted Return Profiling
   * Role: Computes Compound Annual Growth Rates (CAGR) and annualized volatility to rank top-performing wealth generators across sectors.

3. Macro-Shock Drawdown Analysis
   * Role: Measures peak-to-trough price crashes and recovery timelines during COVID-19 and election cycles.

4. Liquidity & Thin-Trading Audit
   * Role: Tracks daily turnover and zero-volume ratios to isolate liquid blue-chips from illiquid trap stocks.

5. Intraday Price Spread Tracking
   * Role: Evaluates daily high-low price ranges to assess market efficiency and volatility spikes.

6. Market Index Benchmarking
   * Role: Compares individual stock performance against `^NASI` and `^N20I` indices to determine market correlation.

## 🛠️ Tech Stack & Tools
* Python & Pandas:* structure, and manipulate over 121,000 rows of financial time-series data.
* SQL: Queried structured transactional tables to extract sector aggregates, rolling averages, and custom financial metrics.
* Jupyter Notebooks (`.ipynb`):** The core interactive environment for running exploratory data analysis and computing quantitative KPIs.
* Streamlit: Powers an interactive web application allowing users to explore stock trends, sector filters, and metrics dynamically.
* Tableau: Delivers executive-ready, interactive visual dashboards displaying price crashes, volume distributions, and sector performance.
* VS Code & Git/GitHub: Used for development, virtual environment setup, version control, and repository publishing.

## 📂 Repository Structure

```text
NSE-Market-Analysis-2019-2025/
│
├── Data/
│   ├── NSE_data_stock_market_sectors_2025.csv       # Official sector mapping dimension table
│   ├── NSE_Stocks_2019_Cleaned_v2.xlsx            # Cleaned daily data (2019)
│   ├── NSE_Stocks_2020_Cleaned_v2.xlsx            # Cleaned daily data (2020 - COVID crash)
│   ├── NSE_Stocks_2021_Cleaned_v2.xlsx            # Cleaned daily data (2021)
│   ├── NSE_Stocks_2022_Cleaned_v2.xlsx            # Cleaned daily data (2022 - Election cycle)
│   ├── NSE_Stocks_2023_Cleaned_v2.xlsx            # Cleaned daily data (2023 - Rate hikes)
│   ├── NSE_Stocks_2024_Cleaned_v2.xlsx            # Cleaned daily data (2024)
│   └── NSE_Stocks_2025_Cleaned_v2.xlsx            # Cleaned daily data (2025)
│
├── app.py                                          # Streamlit interactive web application
├── queries.sql                                     # SQL scripts for data extraction and metrics
├── NSE_stock_analysis.ipynb                        # Main exploratory analysis & KPI pipeline
├── project_template.md                             # Detailed project statement, goals, and metrics
├── requirements.txt                                # Python library dependencies
└── README.md                                       # Project documentation (this file)
```

## 📊 How to Run the Project Locally

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Nyamwala/NSE-Market-Analysis-2019-2025.git
   ```
2. Open the project folder in **VS Code**.
3. Install the required Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Streamlit web application:
   ```bash
   streamlit run app.py
   ```
5. Alternatively, open `NSE_stock_analysis.ipynb` in Jupyter Notebook to execute the data pipeline step-by-step.

## 💡 Impact & Benefits

* For Everyday Investors: Replaces financial guesswork with clear, data-backed evidence to help protect savings and identify stable dividend-paying counters.
* For Analysts & The Investment Community: Offers a fully open-source, interactive pipeline and visual dashboard suite for auditing liquidity risks and evaluating capital market resilience in emerging economies.