# 10-Year Financial Performance Analysis of State Bank of India (FY2017–FY2026)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1KDeVR04ndZDGQbYMsxwhDTXVNfjhjWvP)

An end-to-end Python data analytics project evaluating SBI's 10-year audited financial statements (FY2017–FY2026), focusing on revenue expansion, cost efficiency, and profitability turnaround.

---

## Executive Summary
- **Revenue Expansion:** Total Income increased from ₹2,98,640 Cr (FY17) to ₹7,12,644 Cr (FY26) at a **10.15% CAGR**.
- **Profitability Turnaround:** Transitioned from a ₹4,556 Cr net loss in FY18 (RBI Asset Quality Review) to an all-time record net profit of **₹83,299 Cr** in FY26 (+346x growth from FY17).
- **Efficiency Gains:** Cost-to-Income ratio dropped from a peak of **54.84% (FY18) to 38.88% (FY26)**, driven by digital adoption (YONO) and disciplined operational cost management.
- **Lending-Driven Growth:** Correlation analysis reveals a **perfect positive correlation (r = 1.00)** between Net Interest Income and Net Profit, confirming core lending as the primary bottom-line driver.

---

## 🛠️ Tech Stack & Methodology
- **Languages/Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn
- **Data Source:** Screener.in (Audited annual BSE/NSE filings for SBI)
- **Pipeline:**
  1. **Data Ingestion & Reshaping:** Extracted 10-year P&L data and transposed horizontal financial years into a tabular time-series format.
  2. **Data Cleaning:** Standardized accounting headers, removed aggregated bank totals, and converted string data to clean float/integer types.
  3. **Feature Engineering:** Calculated Net Interest Income (NII), Cost-to-Income %, Net Profit Margins, and CAGR metrics.
  4. **Visual Analytics:** Plotted time-series trends, expense structures, and correlation heatmaps.

---

## 📊 Key Visualizations & Insights
- **Income vs. Expense Gap:** Operating surplus widened sharply post-FY2021, reaching an operating surplus of ~₹1,14,000 Cr by FY2026.
- **Cost Structure:** Interest paid to depositors accounts for >50% of total expenses, indicating cost growth is balance-sheet driven rather than headcount-driven.
- **Efficiency Link:** A strong negative correlation (**r = -0.94**) between Cost-to-Income ratio and Net Profit confirms that operational discipline directly powered the profit turnaround.

---

## 📂 Repository Contents
- `SBI_Financial_Performance_Analysis.ipynb`: Main Google Colab Jupyter Notebook.
- `SBI.xlsx`: Raw input financial statements.
- `Financial performance analysis of SBI.pdf`: Summary presentation slide deck.
