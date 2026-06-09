# India CPI Inflation Analysis 📊

**Tools:** Microsoft Excel | EDA | Statistical Analysis  
**Data Source:** Government of India CPI Dataset + PPAC (crude oil prices)  
**Period Covered:** 2013 – 2023

---

## Overview
This project analyzes 10 years of India's Consumer Price Index (CPI) data 
across Rural, Urban, and Combined sectors to uncover inflation trends, 
identify high-contributing categories, and investigate the impact of major 
economic events on price levels.

---

## Objectives & Key Findings

### 1. Category Contribution to CPI Basket
- Analyzed 7 broader categories: Food & Beverages, Apparel, Healthcare,
  Energy, Transportation, Household Needs, and Others
- **Food & Beverages dominates at ~56.9%** of the total CPI basket

### 2. YoY Inflation Trend (2017 onwards)
- Tracked year-over-year CPI movement for the combined Rural + Urban index
- Identified consistent upward pressure in food and energy segments

### 3. Food Price Spike — November 2023
- India's inflation hit a **3-month high of 5.55% in November 2023**
- Root cause traced to sharp price rises in **Vegetables, Cereals, and Spices**

### 4. COVID-19 Impact on Inflation
- Mapped CPI movement from 2019–2022 to pandemic phases
- Imputed missing May 2020 values using category-level monthly averages
- Found supply chain disruptions caused abnormal spikes in essential goods

### 5. Crude Oil Price Correlation
- Imported crude oil price data from **PPAC** for FY2021–22 & FY2022–23
- Traced oil price fluctuations to **Energy sector CPI spikes**,
  revealing imported inflation patterns in India

---

## Data Cleaning Steps
- Imputed missing May 2020 values using same-category monthly averages
- Excluded Housing column for Rural sector (not applicable — 
  rural households don't incur formal rent expenses)
- Standardized category groupings across Rural, Urban, and Combined sectors

---

## Project Structure
```
india-cpi-analysis/
│
├── CPI_Case_Study.xlsx      # Main workbook — all 5 objectives, analysis & charts
├── README.md                # Project documentation
```

## Skills Demonstrated
- Exploratory Data Analysis (EDA)
- Data Cleaning & Imputation
- Time Series Trend Analysis
- Economic Data Interpretation
- Excel Dashboard & Pivot Table Design
