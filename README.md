# COVID-19 Data Analysis

## Project Overview
This project performs an exploratory data analysis (EDA) on publicly available COVID-19 data to understand the spread and impact of the pandemic across different countries. The analysis focuses on identifying temporal trends in confirmed cases and deaths, comparing patterns across selected countries, and exploring the relationship between confirmed cases and mortality.

## Dataset
The dataset used is a country-level aggregated COVID-19 dataset provided by **DataHub**, compiled from publicly available sources including the Johns Hopkins University Center for Systems Science and Engineering (CSSE).  
**Key columns:**
- `Date`: Reporting date
- `Country`: Name of the country
- `Confirmed`: Total confirmed COVID-19 cases
- `Deaths`: Total deaths
- `Recovered`: Total recoveries

Dataset is loaded directly from the public URL, so no local files are required.

## Libraries Used
- `pandas` for data manipulation
- `matplotlib` for plotting
- `seaborn` (optional) for enhanced visualizations

## Notebook Structure
1. **Problem Statement** – Objectives and goals of the analysis
2. **Dataset Description** – Source, structure, and key columns
3. **Data Cleaning and Preparation** – Inspecting, transforming, and filtering the dataset
4. **Exploratory Data Analysis (EDA)** – Trends, comparisons, and relationships
    - Confirmed Cases Over Time
    - Death Trends Over Time
    - Deaths vs Confirmed Cases
    - Top 5 Countries by Confirmed Cases
5. **Key Insights** – Observations from the analysis
6. **Conclusion** – Summary and implications of the findings

## Key Insights
- The United States experienced the highest number of confirmed COVID-19 cases among the selected countries.
- India exhibited a delayed but rapid increase in confirmed cases.
- Germany had comparatively lower case and death counts.
- A positive relationship exists between confirmed cases and deaths.
- A few countries account for a disproportionately large share of global cases.

## Conclusion
This analysis demonstrates how publicly available healthcare data can be used to identify temporal trends, inter-country differences, and relationships between key epidemiological metrics. The findings highlight the importance of data-driven insights in public health decision-making.

## How to Run
1. Open `covid19_data_analysis.ipynb` in [Google Colab](https://colab.research.google.com/).
2. Run all cells sequentially.
3. All data is loaded from a public URL; no local files are required.
