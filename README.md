# Tech Layoffs Analysis

## 📌 Project Overview
This project explores layoffs in the tech industry using data from Kaggle. The dataset tracks layoffs reported in major publications since the COVID-19 pandemic, helping analyze trends and company-specific patterns.

## 📊 Dataset
- **Source:** [Kaggle - Layoffs Dataset](https://www.kaggle.com/datasets/swaptr/layoffs-2022)
- **Timeframe:** 2020–2023
- **Main Features:**
  - `company`: Name of the company
  - `industry`: Sector of the company
  - `total_laid_off`: Number of employees laid off
  - `percentage_laid_off`: Percentage of the workforce affected
  - `date`: Date of layoffs
  - `location`, `country`: Geographic information
  - `funds_raised_millions`: Total funding received by the company

## 🛠️ Data Processing Steps
1. **Data Cleaning**
   - Handled missing values and inconsistencies.
   - Standardized column names.
   - Removed duplicates.

2. **Exploratory Data Analysis (EDA)**
   - Identified companies with the largest layoffs.
   - Analyzed trends by year, industry, and country.
   - Examined startups that shut down completely.
   - Calculated rolling totals of layoffs over time.

## 🔍 Key Insights
- The highest layoffs occurred in 2022, aligning with economic slowdowns.
- Startups with 100% layoffs mostly shut down due to funding shortages.
- The tech industry had the most significant layoffs, particularly in software and fintech.
- Layoffs peaked in major tech hubs like the U.S. and India.
