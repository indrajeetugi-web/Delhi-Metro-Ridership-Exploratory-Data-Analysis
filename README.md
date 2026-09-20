# 🚇 Delhi Metro Ridership — Exploratory Data Analysis

An end-to-end EDA project on a synthetic Delhi Metro ridership dataset, exploring how station type, day of week, weather, and location drive commuter footfall across the network.

## 📊 Project Overview

This project analyzes **11,775 station-day records** across **88 real Delhi Metro stations** and **9 lines**, spanning **Jan–Apr 2024**. The goal was to uncover the key drivers of metro ridership using classic EDA techniques — from data cleaning through univariate, bivariate, and multivariate analysis, feature engineering, and a final data-driven summary.

## 🎯 Key Questions Explored

- Do interchange stations really see more riders than regular stations?
- How much does ridership drop on weekends vs weekdays?
- Does weather (fog, rain, heat) affect commuter footfall?
- Is Delhi Metro's fare structure truly distance-based?
- Which lines and zones carry the most traffic, and why?

## 🔑 Key Findings

- **Interchange stations see ~3x the ridership** of regular stations (median ~35,900 vs ~11,100 riders/day), consistent across weekdays, weekends, and weather conditions.
- **Weekend ridership drops ~40%** network-wide — a clear commuter-driven pattern rather than leisure travel.
- **Fare correlates strongly with distance** (r ≈ 0.85–0.9), reflecting DMRC's real distance-based fare slabs.
- **Fog is the only weather condition with a measurable ridership impact** (~14–16% dip) in this dataset's Jan–Apr window.
- **Stations within 5 km of the city center** see ~74% higher median footfall than stations 20+ km away.

## 🛠️ Tools & Libraries

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn`

## 📁 Project Structure

```
delhi-metro-eda/
├── data/
│   └── delhi_metro_ridership_dataset.csv
├── notebooks/
│   └── delhi_metro_eda.ipynb
├── README.md
└── requirements.txt
```

## 📈 Analysis Workflow

1. Data loading & inspection
2. Data cleaning (missing values, duplicates, dtype fixes)
3. Summary statistics
4. Univariate analysis (distributions, skew, outliers)
5. Bivariate analysis (footfall vs line, interchange, weekend, weather)
6. Multivariate analysis (correlation heatmaps, interaction effects)
7. Feature engineering (amenity score, distance bands, footfall/platform)
8. Key findings & limitations

## ⚠️ Limitations

- Dataset is **synthetic**, generated to mimic realistic Delhi Metro patterns for practice — not DMRC's actual reported ridership.
- Covers only Winter and Spring (Jan–Apr); Summer/Monsoon weather effects are untested.

## 📬 Connect
⭐ If you found this useful, consider starring the repo!
