# Air Quality Analysis (India 2015–2020)

## Project Overview
This project analyzes air quality trends across Indian cities using AQI and pollutant data. The goal is to identify pollution patterns, key drivers, and temporal trends.

---

## Dataset
- Source: Kaggle (Air Quality Data in India)
- Time Period: 2015–2020
- Features: AQI, PM2.5, PM10, NO2, CO, SO2, O3

---

##  Data Processing
- Separated raw and processed data
- Handled missing values using median imputation
- Converted date column to datetime format
- Removed rows with missing AQI values

---

## Exploratory Analysis
Key analyses performed:
- AQI distribution across India
- Top polluted cities
- Pollutant correlation with AQI
- Yearly AQI trends

---

## Key Insights
- PM2.5 is the strongest contributor to AQI
- Some cities consistently show high pollution levels
- AQI shows variation over time but no strong long-term improvement trend
- Data quality varies across monitoring stations

---

## Outputs
- Figures → `/outputs/figures/`
- Tables → `/outputs/tables/`
- Insights → `/outputs/insights/`

---

## Tools Used
- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Jupyter Notebook

---

## Project Structure