# Finance Analysis Dashboard

An advanced **Power BI Financial Intelligence Dashboard** that provides real-time insights into transactions, customer demographics, and transactional risk. This project implements a deep analytical system to track cross-year transaction behavior, regional distributions, and revenue streams.

##  Project Overview
The **FinSight** business application allows users to toggling seamlessly between two main interfaces:
1. **Overview Analysis:** Focuses on the macro financial landscape, yearly tracking, and user demographics.
2. **Transactions:** Delves directly into raw tabular data for transaction-level audits.

Equipped with a multiple dynamic slicers, the report allows users to isolate financial trends across consecutive years (**2023, 2024, 2025, 2026**), occupations, and merchant categories.

---

##  Key Financial Metrics Monitored

* **Total Amount (Gross Volume):** Tracking the total movement of currency through the system.
* **Total Transaction Volume:** Evaluating total transactions executed along with Year-over-Year (YoY) variance percentages.
* **Average Transaction Value:** Measuring individual transaction sizing behaviors.
* **Total Fees Collected:** Showcasing the platform's processed transaction fees.
* **Total Tax:** Keeping watch over processing taxes.

---

##  Tech Stack & Data Architecture

* **Tool:** Power BI Desktop
* **Dynamic Metrics Switcher:** Configured a native parameters-driven  **Dynamic Metric Slicer** allowing users to shift the focus of entire visuals instantaneously between *Total Amount*, *Total Fees*, *Total Tax*, and *Total Transactions*.
* **Data Refresh & Integrity:** Modeled to reflect performance and distribution dynamics with detailed tracking features like YoY changes relative to previous intervals.

---

## Key Insights from the Dashboard

*   **Socio-Economic Distribution:** The platform breaks down users into key demographic tiers like Premium, Platinum, Blue, Gold, and Silver customers to track exactly which customer segments hold the highest financial weight.
*   **Regional Dominance:** Detailed cross-state analysis showcases performance clusters among critical regions like Maharashtra, Karnataka, and Tamil Nadu.
*   **Preferred Modes of Operation:** High-volume monitoring categorizes transaction models dynamically into Swipe, Chip, and Online actions.
*   **Transaction Status Tracking:** The vast majority of transaction statuses are monitored via distinct lifecycle segments (Success, Failed, and Pending) to instantly report platform health.
*   **Gender Demographics:** Outlines explicit balances between male and female user expenditure patterns.

## 📂 Repository Structure

```text
├── Data/                   # Transactional CSV / Excel source data
├── Dashboard/              #  Power BI (.pbix) template file
├── Screenshots/            # Interactive views & state-by-state captures
└── README.md               # Documentation guide
