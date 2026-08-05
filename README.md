# UK Electricity Demand Analysis

## Overview
Exploratory data analysis of UK electricity system demand using half-hourly settlement data from National Grid ESO (NESO). This project analyzes demand patterns across time of day, day of week, and season using Python, Pandas, and Matplotlib.

## Dataset
- Source: National Grid ESO (NESO) Historic Demand Data
- ~9,214 half-hourly records (Jan–Jul 2026)
- Key columns: SETTLEMENT_DATE, SETTLEMENT_PERIOD, TSD (Total System Demand)

## Key Findings
- **Weekday vs weekend:** Weekday demand (~29,849 MW avg) is ~11.8% higher than weekend demand (~26,691 MW avg), consistent with commercial/industrial activity patterns.
- **Seasonal trend:** Demand declines steadily from January (~35,494 MW) to July (~24,010 MW), reflecting reduced heating/lighting needs in warmer months.
- **Daily peak:** Demand peaks around 7:00 PM (Settlement Period 39), reaching ~34,876 MW on average — consistent with UK national peak demand patterns (post-work household usage).
- **Daily low:** Demand bottoms out in the early hours (~3:30-4:30 AM), the expected overnight lull.

## Tools Used
Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook

## How to Run
1. Clone this repo
2. Install dependencies: `pip install -r requirements.txt`
3. Open `notebooks/01_data_exploration.ipynb` in Jupyter/VS Code
4. Run all cells

## Project Structure
```
uk-electricity-demand-analysis/
├── data/              # Raw dataset
├── notebooks/         # Analysis notebook
├── outputs/           # Saved chart images
├── src/               # (Reserved for future reusable scripts)
├── README.md
└── requirements.txt
```