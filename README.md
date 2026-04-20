# 🌍 COVID-19 Global Trend Analysis

A time-series EDA project analyzing global COVID-19 trends over time using Python. Data is sourced directly from a live GitHub dataset covering 161,568 records across multiple countries from January 2020 to April 2022.

## 📊 Visualizations Included

- **Global COVID-19 Trend** — confirmed cases, deaths, and recoveries plotted over time
- **Top 10 Most Affected Countries** by total confirmed cases (as of latest date)
- **Correlation Heatmap** between confirmed cases, deaths, and recoveries

## 🗂️ Project Structure

```
covid19-global-trend-analysis/
│
├── analysis.py     # Main EDA script
└── README.md
```

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy matplotlib seaborn
```

### Run the Analysis

```bash
python analysis.py
```

> The dataset is loaded directly from a URL — no manual download needed:
> `https://raw.githubusercontent.com/datasets/covid-19/main/data/countries-aggregated.csv`

## 📁 Dataset

| Column | Description |
|---|---|
| `Date` | Date of record |
| `Country` | Country name |
| `Confirmed` | Cumulative confirmed cases |
| `Recovered` | Cumulative recoveries |
| `Deaths` | Cumulative deaths |

- **161,568 entries**, no missing values
- Date range: **January 22, 2020 – April 16, 2022**

## 🛠️ Libraries Used

- `pandas` — data loading and manipulation
- `numpy` — numerical operations
- `matplotlib` — time-series line plots
- `seaborn` — bar plots and heatmaps
