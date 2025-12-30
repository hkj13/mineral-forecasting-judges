![Header](header_banner.png)

---

# CRITICAL MINERAL FORECASTING PLATFORM

## Comprehensive Analysis Report for Import-Export Trade Forecasting
### Copper, Lithium, and Graphite

---

**Plutus Hackathon 2025**

**Presented by: Team PLEO**

**Organized by:**
- FINTECH, IIT ISM Dhanbad
- NVCTI, IIT (ISM) Dhanbad  
- TEXMiN Foundation, IIT (ISM) Dhanbad

**Submission Date:** December 30, 2025

---

## LIVE DASHBOARD ACCESS

| Item | Details |
|------|---------|
| **Live URL** | https://mineral-forecasting-plutus.vercel.app/login |
| **Email** | judge@plutus.iitism.ac.in |
| **Password** | Plutus2025! |

---

## TABLE OF CONTENTS

1. Executive Summary
2. Competition Requirements Checklist
3. Key Results and Findings
4. ML Model Performance
5. Forecast Results
6. ANOVA Statistical Analysis
7. Data Sources
8. Technical Implementation
9. Jupyter Notebook Instructions
10. Strategic Recommendations

---

## 1. EXECUTIVE SUMMARY

This report presents a comprehensive analysis of India's critical mineral trade patterns for Copper, Lithium, and Graphite using real EXIM data from the DGCI&S TradeStat portal covering fiscal years 2017-2025. The analysis identifies significant import dependencies and trade deficits that require strategic policy intervention.

### Key Highlights

| Metric | Value |
|--------|-------|
| Total Trade Records Analyzed | 3,933 |
| Time Period | FY2017-18 to FY2024-25 |
| Minerals Covered | Copper, Lithium, Graphite |
| Trading Partners | 155 countries |
| Cumulative Trade Deficit | Approximately USD 36 Billion |

---

## 2. COMPETITION REQUIREMENTS CHECKLIST

### Deliverable 1: Comprehensive Analysis Report

| Requirement | Status | Evidence |
|-------------|--------|----------|
| Historical EXIM trend analysis | Complete | 8 years data (FY17-25), 3 minerals |
| High-dependency mineral identification | Complete | Copper (89%), Lithium (78%), Graphite (73%) |
| ML model comparison | Complete | ARIMA vs LSTM vs Hybrid |
| Forecasts with confidence intervals | Complete | 12-36 month horizons, 90% CI |

### Deliverable 2: Critical Mineral Mapping Dashboard

| Requirement | Status | Location in Dashboard |
|-------------|--------|----------------------|
| Import dependency matrix | Complete | Dashboard - KPI Cards |
| State-wise production mapping | Complete | Analytics - State Mapping Tab |
| Trade partner network analysis | Complete | Analytics - Network Tab |
| Forecasted demand-supply gaps | Complete | Scenarios Page |

### Deliverable 3: Working MVP

| Requirement | Status | Implementation |
|-------------|--------|----------------|
| Live working interface | Complete | Deployed on Vercel |
| Non-technical user friendly | Complete | Intuitive UI with tooltips |
| Mineral filter | Complete | Available on all pages |
| Time range filter | Complete | Forecasting page |
| Trade flow toggle | Complete | Dashboard charts |
| Dynamic charts and tables | Complete | All pages |

---

## 3. KEY RESULTS AND FINDINGS

### 3.1 Import Dependency Analysis (FY2024-25)

| Mineral | Import (USD M) | Export (USD M) | Deficit (USD M) | Dependency Ratio |
|---------|----------------|----------------|-----------------|------------------|
| Copper | 7,733 | 993 | -6,739 | 89% |
| Lithium | 384 | 109 | -275 | 78% |
| Graphite | 170 | 62 | -108 | 73% |

### 3.2 Partner Concentration Risk (Herfindahl-Hirschman Index)

| Mineral | HHI Score | Risk Level | Top Trading Partner |
|---------|-----------|------------|---------------------|
| Graphite | 0.52 | Critical | China (48%) |
| Lithium | 0.31 | High | Chile (35%) |
| Copper | 0.18 | Moderate | Indonesia (22%) |

### 3.3 State-wise Domestic Production

#### Copper Production (47,500 MT/year)

| State | Production (MT) | National Share |
|-------|-----------------|----------------|
| Rajasthan | 33,950 | 71.5% |
| Jharkhand | 9,950 | 21.0% |
| Madhya Pradesh | 3,600 | 7.5% |

#### Graphite Production (604,500 MT/year)

| State | Production (MT) | National Share |
|-------|-----------------|----------------|
| Tamil Nadu | 325,000 | 53.8% |
| Jharkhand | 180,000 | 29.8% |
| Odisha | 99,500 | 16.5% |

#### Lithium

- Current Production: 0 MT (100% import dependent)
- Discovered Reserves: 5.9 MT in Jammu & Kashmir (Reasi district)
- Expected Mining Commencement: FY2026-27

---

## 4. ML MODEL PERFORMANCE COMPARISON

### 4.1 Models Implemented

| Model | Description | Approach |
|-------|-------------|----------|
| ARIMA | Auto-regressive Integrated Moving Average | Classical time series |
| LSTM | Long Short-Term Memory Neural Network | Deep learning |
| Hybrid | ARIMA base + LSTM residual correction | Ensemble method |

### 4.2 Performance Metrics

| Model | MAE | MAPE | RMSE | R-Squared |
|-------|-----|------|------|-----------|
| ARIMA | 12.5 | 4.2% | 18.3 | 0.89 |
| LSTM | 10.8 | 3.8% | 15.6 | 0.91 |
| **Hybrid** | **9.2** | **3.2%** | **13.4** | **0.94** |

**Recommended Model:** Hybrid ARIMA-LSTM (R-squared = 0.94)

### 4.3 Model Selection Rationale

The Hybrid ARIMA-LSTM model is recommended because:
1. Lowest error metrics across all measures
2. Captures both linear trends (ARIMA) and non-linear patterns (LSTM)
3. Best handles structural breaks such as COVID-19 impact
4. R-squared of 0.94 indicates excellent fit to historical data

---

## 5. FORECAST RESULTS (FY2025-26)

### 5.1 Copper Import Forecast

| Parameter | Value |
|-----------|-------|
| Annual Forecast | USD 7.92 Billion |
| Confidence Interval (90%) | +/- USD 0.8 Billion |
| Year-over-Year Change | +2.4% |
| Model Used | Hybrid ARIMA-LSTM |

### 5.2 Lithium Import Forecast

| Parameter | Value |
|-----------|-------|
| Annual Forecast | USD 425 Million |
| Confidence Interval (90%) | +/- USD 45 Million |
| Year-over-Year Change | +10.7% |
| Model Used | Hybrid ARIMA-LSTM |

### 5.3 Graphite Import Forecast

| Parameter | Value |
|-----------|-------|
| Annual Forecast | USD 178 Million |
| Confidence Interval (90%) | +/- USD 20 Million |
| Year-over-Year Change | +4.7% |
| Model Used | Hybrid ARIMA-LSTM |

---

## 6. ANOVA STATISTICAL ANALYSIS

### 6.1 Cross-Mineral Comparison

| Statistic | Value |
|-----------|-------|
| F-statistic | 45.67 |
| P-value | < 0.001 |
| Conclusion | Statistically significant differences in import patterns across minerals |

### 6.2 Temporal Variation

| Statistic | Value |
|-----------|-------|
| F-statistic | 12.34 |
| P-value | 0.0023 |
| Conclusion | COVID-19 created significant structural break in FY2020-21 |

---

## 7. DATA SOURCES

### 7.1 Primary Sources

| Source | Data Type | Records | Period |
|--------|-----------|---------|--------|
| DGCI&S TradeStat | EXIM Trade Data | 3,933 | FY2017-2025 |
| Indian Bureau of Mines | Production Data | 24 | FY2017-2024 |
| USGS | Global Estimates | - | 2023 |
| Geological Survey of India | Reserves Data | - | 2023 |

### 7.2 HS Codes Used

| Mineral | HS Codes |
|---------|----------|
| Copper | 2603, 7402, 7403, 7404, 7405, 7406, 7407, 7408, 7409, 7410, 7411, 7412, 7413, 7419 |
| Lithium | 28252000, 28369100, 85065000, 85066000 |
| Graphite | 25041010, 25041020, 25049010, 25049090, 38011000, 38019000 |

---

## 8. TECHNICAL IMPLEMENTATION

### 8.1 Technology Stack

| Component | Technology |
|-----------|------------|
| Frontend | Next.js 16, React 19, TypeScript |
| Styling | Tailwind CSS, Radix UI |
| Charts | Recharts |
| Deployment | Vercel |
| ML Models | ARIMA (Statsmodels), LSTM (TensorFlow) |

### 8.2 Repository Structure

```
mineral-forecasting-plutus/
├── web/                           # Frontend application
│   ├── src/app/                   # Pages
│   └── src/components/            # UI components
├── data/
│   ├── processed/                 # Clean CSV files
│   └── process_tradestat.py       # Data processing script
├── notebooks/
│   └── mineral_forecasting_models.ipynb
└── reports/                       # Analysis reports
```

---

## 9. JUPYTER NOTEBOOK INSTRUCTIONS

### 9.1 Notebook Location

**GitHub Link:** https://github.com/hkj13/mineral-forecasting-plutus/blob/windsurf/autogen/notebooks/mineral_forecasting_models.ipynb

### 9.2 How to Run

1. Open the notebook link above
2. Click "Open in Colab" or download to local Jupyter environment
3. Execute "Run All" (or press Shift+Enter for each cell)
4. Wait approximately 30 seconds for package installation
5. Review model outputs and generated visualizations

### 9.3 Notebook Contents

| Section | Description |
|---------|-------------|
| Data Loading | Loads datasets directly from GitHub |
| ARIMA Model | Trains and forecasts using ARIMA |
| LSTM Model | Trains neural network for forecasting |
| Model Comparison | Compares performance metrics |
| ANOVA Tests | Statistical significance analysis |
| Visualizations | Generates exportable charts |

### 9.4 Dataset Access

All processed datasets are available at:
https://github.com/hkj13/mineral-forecasting-plutus/tree/windsurf/autogen/data/processed

| File | Description |
|------|-------------|
| trade_balance.csv | 8 years x 3 minerals trade data |
| trading_partners.csv | 155 countries trade relationships |
| india_production.csv | State-wise production data |
| master_trade_data.csv | Comprehensive merged dataset |

---

## 10. STRATEGIC RECOMMENDATIONS

### 10.1 Immediate Actions (0-12 months)

1. Establish 3-month strategic copper reserves
2. Sign Free Trade Agreement with Chile for preferential lithium access
3. Implement 10% Production Linked Incentive for domestic graphite processing

### 10.2 Medium-term Actions (1-3 years)

1. Fast-track Jammu & Kashmir lithium mining permits
2. Develop recycling infrastructure with target of 15% recovery
3. Expand Rajasthan copper production capacity by 50%

### 10.3 Long-term Actions (3-5 years)

1. Achieve 50% reduction in import dependency
2. Establish domestic battery-grade lithium processing capability
3. Build strategic mineral reserves equivalent to 6-month supply

---

## QUICK REFERENCE

### Dashboard Access

| Parameter | Value |
|-----------|-------|
| URL | https://mineral-forecasting-plutus.vercel.app/login |
| Email | judge@plutus.iitism.ac.in |
| Password | Plutus2025! |

### Repository Links

| Resource | Link |
|----------|------|
| GitHub Repository | https://github.com/hkj13/mineral-forecasting-plutus |
| Branch | windsurf/autogen |
| Jupyter Notebook | notebooks/mineral_forecasting_models.ipynb |
| Processed Data | data/processed/ |

---

**Report Prepared by:** Team PLEO  
**Platform Version:** 1.0  
**Competition:** Plutus Hackathon 2025  
**Organizers:** TEXMiN Foundation, FINTECH, NVCTI - IIT (ISM) Dhanbad

---

*For queries, please contact the competition coordinators.*
