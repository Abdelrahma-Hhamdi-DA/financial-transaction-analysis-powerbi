# Financial Transaction Analysis Dashboard (FinSight)
## 📌 Project Overview
FinSight is a comprehensive Power BI dashboard designed to analyze financial transactions, customer segments, and organizational risk. It monitors a total volume of **₹23.17M** across **2.54K transactions**, tracking key financial health metrics, temporal trends, and regional distributions to support data-driven decision-making.

## 📁 Project Structure
- `📄 Finance Analysis.pbix` : The core Power BI dashboard file.
- `📂 data/` : Contains the raw datasets (`customers` and `finance_transactions`).
- `📂 docs/` : Documentation including the `Business Requirements` document.
- `📂 images/` : High-resolution screenshots of the dashboard pages.

## 📊 Key Insights & Features
- **Overview Analysis**: Tracks Total Amount, Transaction Volume, Average Transaction Value, Fees, and Taxes with Year-over-Year (YoY) performance indicators.
- **Customer Segmentation**: Breaks down financial performance across segments like Retail (leading with ₹12M), Premium, SME, Corporate, and Wealth.
- **Transaction Profiling**: Analyzes performance by state (e.g., Maharashtra leading at ₹4.1M), status (Success vs. Failed/Pending), and specific transaction types (Loan EMI, Deposits, Transfers, etc.).
- **Detailed Transactions Page**: A granular look at specific transaction logs including individual customer names, dates, amounts, and associated fees/taxes.

- ## 🎯 Business Problem & Objective
The business is experiencing a **3.39% Year-over-Year (YoY) decline** in total transaction amounts, combined with a **9.82% drop in collected fees**. While transaction volume remained flat (+0.52%), the average transaction value decreased by **3.89%**. 

The objective of this analysis is to identify where the revenue leakage is occurring, understand customer segment contributions, and provide actionable recommendations to reverse this decline.

## 💡 Recommendations & Action Plan
1. **Maximize Retail Growth**: Since the Retail segment drives the majority of revenue (₹12M), introduce targeted loyalty programs to increase their average ticket size.
2. **Replicate Maharashtra's Success**: Analyze and document the strategies driving ₹4.1M in Maharashtra to implement them in lower-performing states like Rajasthan (₹1.2M).
3. **Fix Payment Drop-offs**: Collaborate with the engineering team to investigate the root causes of 'Failed' and 'Pending' transactions to capture lost revenue.
4. **Optimize Fee Structures**: Review pricing and fees on high-volume transaction types (like Loan EMIs and Transfers) to recover the 9.82% drop in fee revenue.
