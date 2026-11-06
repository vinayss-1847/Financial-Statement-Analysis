# Financial-Statement-Analysis
Financial Statement Analysis Dashboard | Multi-period corporate health diagnostic tool built with Tableau. Integrates traditional financial ratios (liquidity, profitability, efficiency) with qualitative market intelligence and brand health sentiment data.

# Financial Statement Analysis & Corporate Intelligence Dashboard 📊

An end-to-end Business Intelligence (BI) and corporate health diagnostic solution. This repository hosts a longitudinal financial dashboard built to audit 10 years of accounting statement history, seamlessly bridging the gap between raw quantitative performance data and strategic qualitative market frameworks.

## 🗂️ Project Architecture

*   `jY&v Financial Statement Analysis.twb`: Core Tableau workbook defining the custom KPI structures, interactive cross-filters, and visual layout.
*   `Data/TableauTemp/`: High-performance Tableau `.hyper` data engine extract optimizing multi-period analytical query speeds.

---

## 📈 Analytical Framework

This project tracks corporate performance through a multi-dimensional lens, ensuring a comprehensive view of operational health:

### 1. Quantitative Performance (Financial Metrics)
*   **Liquidity & Short-Term Solvency:** Current Ratio, Quick Ratio, and Cash Ratio tracking working capital adequacy against near-term obligations.
*   **Profitability Architecture:** Gross, Operating, and Net Profit Margins alongside Return on Equity (ROE) and Return on Assets (ROA).
*   **Capital Structure & Leverage:** Debt-to-Equity (D/E), Debt Ratio, and Interest Coverage metrics to map risk and long-term solvency profiles.
*   **Operational Velocity:** Asset Turnover, Inventory Turnover, and Days Sales Outstanding (DSO) evaluating inventory and receivable lifecycles.

### 2. Qualitative Context (Commercial & Strategic Metrics)
*   **Market & Brand Intelligence:** Net Promoter Scores (NPS), Customer Satisfaction indices (CSAT), and brand valuation trends.
*   **Operational Risk & Governance:** Corporate governance compliance checks, internal workflow friction parameters, and regulatory risk scoring.
*   **Human Capital Health:** Employee retention milestones, organizational productivity curves, and sentiment indexes mapped alongside growth periods.

---

## 🛠️ Tech Stack & Technical Competencies

*   **Data Visualization & BI Tools:** Tableau, Power BI, Microsoft Excel
*   **Infrastructure & Workflow Platforms:** GitHub, Jupyter Notebook, VS Code, Microsoft Fabric (Beginner)
*   **Productivity Optimization:** GenAI Tools & Prompt-Engineered Analytics Workflows
*   **Core Methodologies:** Business Analysis, Data Interpretation, KPI Reporting, Solution Evaluation, Cross-functional Collaboration

---

## 💡 Key Business Insights Discovered

By executing this longitudinal analysis, the data model successfully traced a massive corporate expansion cycle:
*   📈 **92.2% Top-Line Growth:** Tracked a steady rise in sales volume from \$39.2K (2017) to \$75.3K (2026).
*   💰 **271.8% Bottom-Line Surge:** Evaluated capital allocation efficiency that scaled Net Profits from \$9.3K to \$34.7K over the same 10-year period.
*   🔄 **Dual-Perspective Lead/Lag Analysis:** Discovered strong historical correlations showing that spikes in qualitative brand sentiment metrics directly preceded periods of accelerated revenue generation.

---

## 🚀 Deployment & Local Usage

### Prerequisites
*   Tableau Desktop (v2022.1 or newer recommended) or Tableau Public.
*   *Optional:* Python 3.8+ environment if you wish to run the preprocessing source scripts.

### Installation
1. Clone this repository locally:
   ```bash
   git clone https://github.com
   ```
2. Navigate to the project directory and open the Tableau file: `jY&v Financial Statement Analysis.twb`.
3. If prompted to re-establish the connection, point the workbook to the `.hyper` dataset situated inside the `Data/TableauTemp/` folder.
