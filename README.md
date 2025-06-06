# Prodigy Infotech – Task 01: Data Visualization
This repository contains a comprehensive data analysis project on world population trends, performed as part of my internship at Prodigy Infotech. The analysis includes data cleaning, preprocessing, and visualization of global population trends over time using Python and various data visualization libraries.

## 📌 Task Overview
**Objective :** Create visual representations (bar charts and histograms) to understand the distribution of population data across different countries and over time.

## 📁 Dataset

The dataset used is the **World Bank Population Data**, containing population information for countries and regions from 1960 to 2023.  
**File:** `world_population_data.csv`

## 📊 Visualizations
- **Histogram** of population distribution in 2023  
- **Barplot** of India's population from 1960–2023  
- **Histogram** of population growth (2000–2020)  
- **Overlapping histograms**: Population in 1960 vs 2020  
- **Top 10 most populated** and **bottom 10 least populated** countries in 2023  
- **Line plots** comparing population growth for India and China  
- **Percentage growth** from 1960–2023  
- **Top 5 countries** population trends over time

- ## 🔍 Exploratory Data Analysis (EDA)

### ✔️ Data Cleaning
- Removed unnecessary columns (`Unnamed: 69`, `2024`)
- Handled missing values by imputing column-wise means
- Filtered out aggregate and non-country entries

### ✔️ Feature Engineering
- Created new column `growth_2000_2020` to study population change
- Calculated percentage growth between 1960 and 2023 for India and China

## 🛠️ Tools & Technologies Used
- **Language:** Python  
- **Libraries:** Pandas, Matplotlib, Seaborn, NumPy  
- **Platform:** Jupyter Notebook
