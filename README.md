# 🚀 Space Missions Analysis with Python

## 📌 Overview

This repository presents a comprehensive analysis of global space missions using Python. The goal is to explore trends and patterns in the historical data of space launches — such as frequency, costs, seasonality, and mission success rates — to gain insights into the evolution of space exploration.

## ❓ Guiding Questions

This project aims to answer the following key questions:

- Which organization launched the most space missions in a given year?
- How many launches were carried out per year?
- How has the cost of space missions varied over time?
- Which months are the most popular for launches?
- Have space missions become safer, or have failure rates remained constant?

## 📊 Dataset

The dataset includes information such as:

- Launch dates  
- Launching organizations/agencies  
- Mission outcomes (success/failure)  
- Estimated costs (when available)

## 🧰 Technologies Used

- Python 3.13.5
- Pandas — data manipulation  
- Matplotlib & Seaborn — data visualization  
- Jupyter Notebook — exploratory data analysis

## 📁 Project Structure
- `Data/`: dataset files or links to data sources
- `Notebooks/`: step-by-step pipeline of the project
- `Plots/`: plots for exploratory analysis
- `requirements.txt`: project dependencies
- `space mission report`: Conclusion report
## 🧠 Methodology

1. Data Cleaning:
   - Converted the Date column to datetime format and extracted Year and ordered Month for temporal analysis.
   - Cleaned and renamed columns (id, removed Unnamed: 0) for clarity.
   - Split the Detail column into Rocket and Mission, then removed the original
   - Converted the Price column to numeric and applied a multi-step imputation strategy using group means and median values.
   - Rounded all price values to two decimal places for consistency. 
2. Exploratory Data Analysis (EDA):
   - Grouped data by year, organization, and outcome
   - Generated visualizations to identify trends and anomalies
3. Visualization:
   - Bar charts, time series to visualize insights
   - 
## ▶️ How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/Sebamir/Space-Missions-Launches-Analysis
cd Space-Missions-Launches-Analysis

