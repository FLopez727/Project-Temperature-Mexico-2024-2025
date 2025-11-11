# Project-Temperature-Mexico-2024-2025
This report presents an exploratory analysis of monthly temperature data recorded in Mexican states, highlighting seasonal patterns, regional differences, and historical variability.

This project performs exploratory data analysis (EDA) on minimum and maximum temperatures recorded across Mexican weather stations from January 2024 to September 2025. It includes data cleaning, regional grouping, visualization, and hypothesis testing.

## 🔧 Project Structure

- `create_df_temp.ipynb`: Loads and merges monthly Tmin and Tmax files.
- `temperature_data_cleaning.ipynb`: Cleans, standardizes, and assigns regions.
- `analytics_temp.ipynb`: EDA with visualizations and region/year aggregations.
- `hypothesis_testing.ipynb`: Statistical tests comparing temperatures across years and regions.

## 📊 Key Variables

- `temperature_min`, `temperature_max`, `temperature_avg`
- `year`, `month`, `state`, `region`

## 📍 Defined Regions

North, Central-North, Center, West, East, South, Southeast, Northwest

## 📈 Visualizations

- Boxplots and histograms by variable and year
- Aggregations by region and year

## 🧪 Hypothesis Testing

- Has CDMX’s max temperature changed between 2024 and 2025?
- Are there significant differences between regions?
- Has winter’s minimum temperature increased?

## 📁 File

- `temperature_012024_092025.csv`

## 📌 Requirements

- Python 3.8+
- pandas, numpy, seaborn, matplotlib, scipy

---
