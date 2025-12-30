# Critical Mineral Forecasting Platform
## Plutus Hackathon 2025 - Team PLEO

---

## LIVE DASHBOARD

| Item | Details |
|------|---------|
| **URL** | https://mineral-forecasting-plutus.vercel.app/login |
| **Email** | judge@plutus.iitism.ac.in |
| **Password** | Plutus2025! |

---

## Repository Contents

```
mineral-forecasting-judges/
├── notebooks/
│   └── mineral_forecasting_models.ipynb   # Runnable ML models
├── data/
│   └── processed/                         # Clean CSV datasets
└── reports/
    ├── FINAL_SUBMISSION_REPORT_FORMAL.md  # Main submission report
    ├── header_banner.png                  # Header image
    └── ...
```

---

## Quick Start for Judges

### Step 1: Access Live Dashboard
1. Visit: https://mineral-forecasting-plutus.vercel.app/login
2. Login with credentials above
3. Explore: Dashboard → Forecasting → Scenarios → Analytics

### Step 2: Run ML Models
1. Open `notebooks/mineral_forecasting_models.ipynb`
2. Click "Open in Colab" badge (or download)
3. Run All cells
4. Review ARIMA, LSTM, and Hybrid model outputs

### Step 3: Review Data
All processed datasets in `data/processed/`:
- `trade_balance.csv` - 8 years × 3 minerals
- `trading_partners.csv` - 155 countries
- `india_production.csv` - State-wise production

---

## Key Results

| Mineral | Import Dependency | Trade Deficit (FY25) |
|---------|-------------------|---------------------|
| Copper | 89% | USD 6.74 Billion |
| Lithium | 78% | USD 275 Million |
| Graphite | 73% | USD 108 Million |

**Best Model:** Hybrid ARIMA-LSTM (R² = 0.94, MAPE = 3.2%)

---

**Presented by:** Team PLEO  
**Competition:** Plutus Hackathon 2025  
**Organizers:** TEXMiN Foundation, FINTECH, NVCTI - IIT (ISM) Dhanbad
