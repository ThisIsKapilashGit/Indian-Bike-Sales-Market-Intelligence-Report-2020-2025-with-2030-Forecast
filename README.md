# 🏍️ Indian Bike Sales Market Analysis 2020–2025

<p align="center">
  <img src="visuals/08_linkedin_dashboard.png" width="800"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python" />
  <img src="https://img.shields.io/badge/Pandas-2.x-green?logo=pandas" />
  <img src="https://img.shields.io/badge/scikit--learn-1.x-orange?logo=scikit-learn" />
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi" />
  <img src="https://img.shields.io/badge/Excel-Workbook-brightgreen?logo=microsoft-excel" />
</p>

---

## 📌 Project Overview

A comprehensive end-to-end **Data Analytics** project on the **Indian Two-Wheeler Market** covering:

- 📊 **Brand-wise** market share & sales volume (2020–2025)
- 🌆 **Urban vs Rural** demand breakdown
- 🔧 **Segment analysis** by zone (Commuter, Executive, Premium, Performance, Superbike, EV)
- 💳 **Payment mode** trends (Cash, EMI, Digital, Exchange, Corporate)
- 🏦 **Finance company** market share (Bajaj Finance, HDFC, Hero FinCorp, etc.)
- 🔮 **5-Year Forecast** (2026–2030) using ML ensemble models
- 📈 **Power BI Dashboard** ready for LinkedIn publication
- 📋 **Excel Workbook** with 8 formatted sheets + embedded charts

---

## 📁 Repository Structure

```
indian-bike-sales/
│
├── 📂 data/                         # All CSV datasets
│   ├── brand_annual_sales.csv       # 10 brands × 6 years
│   ├── monthly_sales.csv            # 72 months revenue + units
│   ├── urban_rural_split.csv        # Urban/Rural % split by year
│   ├── segment_zone_share.csv       # 6 segments × 2 zones × 6 years
│   ├── payment_modes.csv            # 5 payment channels × 6 years
│   ├── finance_companies.csv        # 9 finance cos × 6 years
│   ├── top_models.csv               # Top 10 models × 6 years
│   ├── forecast_2026_2030.csv       # Base forecast
│   ├── ml_forecast.csv              # ML ensemble + confidence interval
│   └── generate_data.py             # Dataset generation script
│
├── 📂 scripts/                      # Analysis scripts
│   ├── eda_analysis.py              # EDA + 8 chart visualizations
│   ├── forecasting.py               # ML forecasting models
│   └── build_excel.py               # Excel workbook generator
│
├── 📂 visuals/                      # Generated charts (PNG)
│   ├── 01_market_overview.png
│   ├── 02_brand_analysis.png
│   ├── 03_segment_urban_rural.png
│   ├── 04_payment_modes.png
│   ├── 05_finance_companies.png
│   ├── 06_top_models.png
│   ├── 07_forecast_2030.png
│   ├── 08_linkedin_dashboard.png    ⭐ LinkedIn-ready summary
│   └── 09_forecast_models.png
│
├── 📂 powerbi/                      # Power BI resources
│   ├── PowerBI_Setup_Guide.md       # Step-by-step setup guide
│   └── indian_bike_theme.json       # Custom color theme
│
├── 📂 docs/                         # Documentation
│   └── analysis_report.md           # Full written report
│
├── Indian_Bike_Sales_Analysis.xlsx  ⭐ Excel workbook (8 sheets)
├── requirements.txt
└── README.md
```

---

## 🔑 Key Findings

| Metric | Value |
|--------|-------|
| Total Market Size 2025 | **21.4 Million Units** |
| Estimated Revenue 2025 | **₹2.04 Lakh Crore** |
| Market CAGR 2020–2025 | **7.2%** |
| #1 Brand | **Hero MotoCorp (33.2%)** |
| Rural Market Share | **57.4%** |
| Urban Market Share | **42.6%** |
| Top Payment Method | **EMI/Finance (52.3%)** |
| Top Finance Co. | **Bajaj Finance (26%)** |
| Top Urban Segment | **Executive 125–150cc** |
| Top Rural Segment | **Commuter 100–125cc** |
| Forecast 2030 | **30.6 Million Units** |

---

## 🏭 Brand Market Share (2025)

| Brand | Units (000) | Share |
|-------|------------|-------|
| Hero MotoCorp | 7,100 | 33.2% |
| Honda | 4,380 | 20.5% |
| TVS Motor | 3,780 | 17.7% |
| Bajaj Auto | 3,280 | 15.3% |
| Royal Enfield | 1,080 | 5.1% |
| Suzuki | 890 | 4.2% |
| Yamaha | 790 | 3.7% |
| KTM | 360 | 1.7% |
| Others | 940 | 4.4% |

---

## 🌆 Urban vs Rural Deep Dive

### Urban Segments (2025)
| Segment | Share |
|---------|-------|
| Commuter 100–125cc | 20% |
| Executive 125–150cc | 25% |
| Premium 150–250cc | 27% ⬆️ |
| Performance 250–500cc | 16% |
| Superbike 500cc+ | 6% |
| Electric | 6% |

### Rural Segments (2025)
| Segment | Share |
|---------|-------|
| Commuter 100–125cc | 50% 👑 |
| Executive 125–150cc | 32% |
| Premium 150–250cc | 11% |
| Performance | 5% |
| Others | 2% |

---

## 💳 Payment Modes (2025)

| Mode | Share |
|------|-------|
| EMI / Finance | **52.3%** |
| Cash | 16.4% |
| Digital Payment | 16.2% |
| Exchange / Buyback | 9.3% |
| Corporate / Fleet | 5.8% |

---

## 🏦 Finance Companies (2025)

| Company | Market Share |
|---------|-------------|
| Bajaj Finance | **26.0%** |
| HDFC Bank | 20.4% |
| Hero FinCorp | 16.9% |
| TVS Credit | 12.0% |
| Shriram Finance | 9.2% |
| ICICI Bank | 8.4% |
| Others | 7.1% |

---

## 🔮 5-Year Forecast (2026–2030)

| Year | Forecast (M Units) | Lower | Upper |
|------|-------------------|-------|-------|
| 2026 | 23.5M | 21.9M | 25.2M |
| 2027 | 25.2M | 23.4M | 26.9M |
| 2028 | 26.9M | 25.0M | 28.8M |
| 2029 | 28.7M | 26.7M | 30.7M |
| 2030 | **30.6M** | 28.5M | 32.8M |

**Models used:** Linear Regression (MAPE 2.49%) + Polynomial (MAPE 2.45%) + Exponential Smoothing → **Ensemble**

---

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/indian-bike-sales-analysis.git
cd indian-bike-sales-analysis

# Install dependencies
pip install -r requirements.txt

# Step 1: Generate datasets
python data/generate_data.py

# Step 2: Run EDA and create visualizations
python scripts/eda_analysis.py

# Step 3: Run forecasting models
python scripts/forecasting.py

# Step 4: Build Excel workbook
python scripts/build_excel.py
```

---

## 📊 Power BI Dashboard

See `powerbi/PowerBI_Setup_Guide.md` for full setup instructions.

Import datasets → Load DAX measures → Apply `indian_bike_theme.json`

**Dashboard Pages:**
1. Executive Summary (KPIs + brand overview)
2. Market Deep Dive (trends + segments)
3. Payments & Finance
4. Forecast 2030
5. Top Models

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.10+ | Data processing & analysis |
| Pandas / NumPy | Data manipulation |
| Matplotlib | Static visualizations |
| scikit-learn | ML forecasting models |
| openpyxl | Excel workbook generation |
| Power BI Desktop | Interactive dashboard |

---

## 📝 Data Notes

> This project uses **synthetically generated data** modeled on publicly available industry reports from:
> SIAM (Society of Indian Automobile Manufacturers), VAHAN database trends,
> IHS Markit estimates, and annual reports from Hero MotoCorp, Honda, TVS, Bajaj Auto.
> For production use, replace CSVs with actual data from official sources.

---

## 🤝 Contributing

Pull requests welcome. Open an issue first for major changes.

---

## 📄 License

MIT License — free to use and modify with attribution.

---

## 👤 Author

**[Your Name]**
Data Analyst | Python • Power BI • SQL

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://linkedin.com/in/YOUR_PROFILE)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?logo=github)](https://github.com/YOUR_USERNAME)

---

*⭐ If this project helped you, please star the repository!*
