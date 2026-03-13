# 🏭 Working Capital Management — Tata Steel Limited
### Internship Project | Financial Statement Analysis | FY2019 – FY2023

---

<p align="center">
  <img src="https://img.shields.io/badge/Company-Tata%20Steel%20Limited-1A3A6C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Sector-Iron%20%26%20Steel-C8A84B?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Period-FY2019--FY2023-2E6DAD?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
</p>

---

## 📌 Project Overview

This project is a comprehensive analysis of **Working Capital Management (WCM)** at **Tata Steel Limited**, one of India's largest integrated steel producers. The study covers **five fiscal years (FY2019–FY2023)** using standalone financial statements, computing 25+ financial ratios to evaluate the efficiency, liquidity, and profitability of the company's short-term financial management.

The project was conducted as part of an internship in finance/strategy and is structured to be both academically rigorous and interview-ready.

---

## 🎯 Objectives

- Analyse how effectively Tata Steel manages its **current assets and current liabilities**
- Compute and interpret the **Working Capital Cycle (WCC)** and its key components
- Track **liquidity, efficiency, and profitability trends** over 5 years
- **Benchmark** Tata Steel against peers: JSW Steel, Jindal Steel & Power, and SAIL
- Build a **clean, interactive Excel dashboard** suitable for professional presentation

---

## 📂 Repository Structure

```
tata-steel-wcm-analysis/
│
├── 📊  Tata_Steel_WCM_Analysis.xlsx   ← Main deliverable (all sheets + dashboard)
│
├── 📁  data/
│   ├── Tata_Steel_FSA_RATIOS_XL.xlsx  ← Source: Financial Statements (raw)
│   └── Cost_of_Sheets.xlsx            ← Source: Cost of Production data (raw)
│
└── 📄  README.md                      ← This file
```

---

## 📊 Excel Workbook — Sheet Guide

The workbook `Tata_Steel_WCM_Analysis.xlsx` contains **6 professionally formatted sheets**:

| Sheet | Description |
|---|---|
| `📊 Dashboard` | Interactive KPI cards + 4 charts (Revenue, WCC, Liquidity, Peer Comparison) |
| `📋 Cover` | Project overview, table of contents & key findings |
| `📁 Financial Statements` | Consolidated Balance Sheet, P&L, and Cash Flow (FY19–FY23) |
| `⚙️ WC Ratios` | 25 ratios across 5 sections with formulas |
| `📦 Cost Sheet` | Cost of Production build-up → COGS reconciliation |
| `🏭 Peer Analysis` | Benchmarking vs JSW, Jindal S&P, and SAIL |

---

## ⚙️ Ratio Framework

Ratios are organized into five analytical sections:

### A. Liquidity Ratios
| Ratio | Formula |
|---|---|
| Current Ratio | Current Assets / Current Liabilities |
| Quick Ratio | (Current Assets – Inventories) / Current Liabilities |
| Cash Ratio | Cash & Equivalents / Current Liabilities |
| Net Working Capital | Current Assets – Current Liabilities |

### B. Efficiency / Activity Ratios
| Ratio | Formula |
|---|---|
| Inventory Turnover | COGS / Average Inventory |
| Inventory Holding Period | 365 / Inventory Turnover |
| Debtors' Turnover | Net Credit Sales / Average Trade Receivables |
| Average Collection Period | 365 / Debtors' Turnover |
| Creditors' Turnover | COGS / Average Trade Payables |
| Average Payment Period | 365 / Creditors' Turnover |

### C. Working Capital Cycle
| Metric | Formula |
|---|---|
| Gross Operating Cycle | Inventory Days + Receivable Days |
| **Net Working Capital Cycle** | **Gross Operating Cycle – Payable Days** |
| Working Capital Turnover | Net Sales / Average Net Working Capital |
| Interest Coverage Ratio | EBIT / Net Finance Charges |

### D. Profitability Ratios
Gross Profit Margin, Net Profit Margin, Operating Profit Margin, ROCE, RONW

### E. Debt & Leverage Ratios
Debt-to-Equity, Net Debt-to-Equity, Short-term Debt Service Coverage Ratio

---

## 📈 Key Findings

> All values in INR Crores. Figures from Tata Steel Standalone Annual Reports.

| Metric | FY2019 | FY2020 | FY2021 | FY2022 | FY2023 |
|---|---|---|---|---|---|
| Revenue (₹ Cr) | 70,611 | 60,436 | 64,869 | 1,29,021 | 1,29,007 |
| PAT (₹ Cr) | 10,533 | 6,744 | 13,607 | 33,011 | 15,495 |
| Current Ratio | 0.67x | 0.65x | 0.80x | 0.58x | 0.73x |
| Inventory Days | 71.6 | 74.0 | 70.1 | 60.4 | 66.8 |
| Receivable Days | 57.6 | 66.4 | 54.4 | 40.4 | 57.6 |
| Payable Days | 82.0 | 82.1 | 87.8 | 75.5 | 77.7 |
| **WC Cycle (Days)** | **47.2** | **58.3** | **36.7** | **25.3** | **46.8** |
| Net Profit Margin | 14.4% | 11.1% | 20.8% | 25.3% | 11.7% |

### 💡 Summary Insights

1. **WCC improved ~36%** from FY19 (47 days) to FY22 (25 days) — driven by aggressive payables management and faster receivables collection
2. **Current Ratio consistently below 1.0** — Tata Steel operates with negative Net Working Capital, reflecting its strong bargaining power with suppliers
3. **FY2022 was the peak year** — PAT of ₹33,011 Cr and Net Profit Margin of 25.3% on record revenue of ₹1.29 lakh crore
4. **Inventory Turnover ~5.4x** maintained consistently — reflects stable operational efficiency despite commodity price swings
5. **Peer-best WCC** — Tata Steel's 32.3 days (FY23) compares favourably to JSW Steel (45.1 days), SAIL (39.2 days), and Jindal Steel & Power (71.3 days)
6. **Interest Coverage dropped from 11.5x (FY22) to 3.95x (FY23)** — reflects rising finance costs and normalisation of profits post commodity super-cycle

---

## 🏭 Peer Benchmarking — FY2023 WC Cycle (Days)

```
Tata Steel      ████████████████████████████████  32.3 days  ✅ Best
SAIL            ███████████████████████████████████████  39.2 days
JSW Steel       ████████████████████████████████████████████  45.1 days
Jindal S&P      ███████████████████████████████████████████████████████████████████  71.3 days
```

---

## 💰 Cost Sheet Summary (₹ Crores)

| Item | FY2019 | FY2020 | FY2021 | FY2022 | FY2023 |
|---|---|---|---|---|---|
| Raw Material Consumed | 19,840 | 17,407 | 13,869 | 35,257 | 54,012 |
| Employee Costs | 5,131 | 5,037 | 5,199 | 6,366 | 6,616 |
| Other Operating Costs | 24,623 | 23,803 | 22,747 | 36,459 | 38,871 |
| Depreciation | 3,803 | 3,920 | 3,987 | 5,464 | 5,435 |
| **Prime Cost** | **56,327** | **53,202** | **48,311** | **87,823** | **1,09,730** |
| **Cost of Goods Sold** | **56,018** | **55,368** | **51,743** | **85,259** | **1,07,647** |
| **COGS / Net Sales** | 77.6% | 89.3% | 74.4% | 65.9% | 83.7% |

---

## 📐 Data Sources

| Source | Coverage |
|---|---|
| Tata Steel Annual Report 2022–23 | FY2023 & FY2022 Standalone FS |
| Tata Steel Annual Report 2021–22 | FY2022 & FY2021 Standalone FS |
| Tata Steel Annual Report 2020–21 | FY2021 & FY2020 Standalone FS |
| Tata Steel Annual Report 2019–20 | FY2020 & FY2019 Standalone FS |
| Peer company annual reports | JSW, Jindal S&P, SAIL benchmarking |

> All financial statements are **standalone** (India operations only), not consolidated.
> All figures are in **INR Crores** unless stated otherwise.

---

## 🛠️ Tools Used

- **Microsoft Excel** — Data compilation, ratio calculation, formatting, and charting
- **Tata Steel Annual Reports (PDF)** — Primary data source

---

## 📝 How to Use

1. **Download** `Tata_Steel_WCM_Analysis.xlsx`
2. **Open the `📊 Dashboard` tab** for an at-a-glance summary with charts
3. Navigate to **`⚙️ WC Ratios`** to see the full ratio table with formulas
4. The **`📁 Financial Statements`** tab contains the 5-year consolidated data used for all calculations
5. All blue-text values are hardcoded inputs from annual reports; black-text values are calculated

---

## ⚠️ Disclaimer

This project is prepared for academic and internship purposes only. All data is sourced from publicly available Tata Steel Annual Reports. This is not investment advice.

---

<p align="center">
  <i>If you found this useful, please ⭐ star the repository!</i>
</p>
