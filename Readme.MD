# Data Analytics Project — Group 1 Report

## Table of Contents
- [Team Members](#team-members)
- [Dataset Overview](#dataset-overview)
  - [Selection Process](#selection-process)
  - [About the Data Source](#about-the-data-source)
  - [Dataset Specifications](#dataset-specifications)
  - [Why This Dataset?](#why-this-dataset)
- [Key Insights](#key-insights)
- [Challenges Faced](#challenges-faced)
- [Key Learnings & Takeaways](#key-learnings--takeaways)

---

## Team Members
* Mohamed Ali Abidi
* Venkata Prasanna Dama
* XinXin (Nate) Huang
* Lamia Jarid
* Emma Ma
* Million Meshesha
* Upadya Ratnayake
* Naznin Sharmin Shishir

---

## Dataset Overview

* **Dataset Name:** [US Grocery and Gas Prices (2015–2026)](https://www.kaggle.com/datasets/harshitsama/us-grocery-and-gas-prices-2015-2026)
* **Platform:** Kaggle
* **Original Source:** U.S. Bureau of Labor Statistics (BLS) Average Price Data Program

### Selection Process
Our selection process was guided by the need for timely, actionable economic insights. While we initially evaluated the widely used *Superstore* dataset, we discovered the most recent versions on Kaggle only spanned from 2015 to 2020. That timeframe omitted crucial macroeconomic disruptions from recent years. 

To ensure modern relevance, we pivoted to the **US Grocery and Gas Prices (2015–2026)** dataset. Sourced directly from the U.S. Bureau of Labor Statistics (BLS) Average Price Data program, it monitors monthly retail prices of essential household staples—including dairy, meats, produce, coffee, bread, and gasoline. Covering an 11-year continuous timeline up to the present day, this dataset offers a far more applicable foundation for analyzing modern consumer market trends.

### About the Data Source
The BLS Average Price Data program is a direct by-product of the Consumer Price Index (CPI) survey. Each month, BLS data collectors gather prices on targeted consumer goods across thousands of retail establishments in U.S. urban centers. These individual observations are aggregated to calculate a standardized "U.S. city average" price for each tracked commodity.

### Dataset Specifications
| Property | Description |
| :--- | :--- |
| **Observation Frequency** | Monthly |
| **Units of Measure** | U.S. Dollars ($ USD) per standardized unit |
| **Demographic Coverage** | Representative of the broader U.S. CPI urban population |
| **Time Horizon** | 2015 – 2026 (11 continuous years) |

### Why This Dataset?
The 2015–2026 window encompasses critical economic inflection points that directly impacted household living costs:
* **Pre-2020:** A steady, low-inflation baseline period.
* **2020–2021:** Global COVID-19 pandemic shocks and severe supply-chain bottlenecks.
* **2022–2024:** Energy and fuel price surges following geopolitical crises (e.g., Russia's invasion of Ukraine) alongside severe egg price spikes driven by avian flu outbreaks.
* **Post-Shock Recovery:** Clear transition into post-peak inflation dynamics.

This continuity provides distinct "before, during, and after" phases to conduct rigorous comparative trend analysis.

---

## Key Insights

* **Massive Meat Inflation:** Protein categories, specifically beef, recorded the steepest cumulative price surges across the 11-year window:
  * **Sirloin Steak:** +80.59%
  * **All Uncooked Beef Steaks:** +73.49%
  * **Round Steak:** +65.83%
* **Price Deflation Outlier:** **Flour** emerged as one of the few tracked staples demonstrating overall net deflation, recording a **-0.37%** decrease from its initial baseline observation to the latest reporting period.
* **Low Base, High Volatility (Electricity):** While electricity maintained the lowest absolute unit values (averaging ~$0.15/kWh), it nevertheless experienced an overall price rise of **42.75%** over the analysis period.

---

## Challenges Faced

1. **Narrative & Scope Selection:** Filtering and prioritizing the most impactful metrics from a multi-year, multi-commodity dataset to construct a focused and compelling analytical story.
2. **Dashboard Interoperability:** Designing cohesive, modular dashboard views that synchronize smoothly and deliver an intuitive, interactive user experience across all tracked categories.

---

## Key Learnings & Takeaways

* **Data Wrangling Drives Quality Storytelling:** High-impact narratives require robust foundational preprocessing. Clean, well-structured data directly dictates the depth and accuracy of subsequent analysis.
* **Visual Diagnostics:** Exploratory data visualizations are essential not only for presenting final findings, but also as an indispensable diagnostic tool for identifying anomalies and patterns early in the data cleaning pipeline.
