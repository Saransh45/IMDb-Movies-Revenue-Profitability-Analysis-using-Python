**IMDb Movies Revenue & Profitability Analysis**

Overview

This project analyzes IMDb movie data to understand revenue trends, profitability drivers, language dominance, release trends, and movie runtime patterns using Python and Pandas.

The dataset contains ~3000 movies with 23 features including revenue, budget, runtime, language, genres, popularity, and release dates.

Objective

Explore IMDb movie dataset and identify trends in revenue and profitability.

Investigate the impact of original language on revenue.

Analyze release year trends and growth patterns in the global film industry.

Perform feature engineering and data cleaning for accurate analysis.

Examine maximum movie runtimes over the years.

Dataset

Source: IMDb movie dataset (CSV)

**The dataset used in this project is not included in the repository due to GitHub file size limitations.**
**Dataset access (view-only):**
https://drive.google.com/file/d/1kbmUarIMIDq51Y5BqPiC7vu2m3d-p6Cq/view?usp=sharing

Size: ~3000 movies

Key Features:

Revenue, budget, runtime, original_language, genres, popularity, release_date

Libraries Used

pandas – Data manipulation and analysis

numpy – Numerical computations

ast – Parsing JSON-like strings

datetime – Handling date and time features

Data Cleaning

Removed missing values and duplicate records.

Standardized language codes to uppercase (e.g., en → EN).

Converted date columns to datetime objects and extracted year, month, and day.

Feature Engineering

Created Half_runtime = runtime / 2.

Calculated Profit as Revenue - Budget.

Classified profits as positive or negative using profit_value.

Standardized text features: titles to uppercase, taglines to lowercase.

Extracted genre names from JSON-like strings.

Key Analysis & Insights
Revenue Trends by Release Year

Total movie revenue shows steady growth from the late 1990s.

Strong surge observed between 2009–2015.

Peak revenue year: 2015.

Slight decline in 2017, likely due to fewer movies or incomplete data.

Revenue by Original Language

English-language movies dominate total revenue.

Other languages (Japanese JA, Chinese ZH, Swedish SV) contribute significantly less.

Highlights the global commercial dominance of English-language films.

Revenue vs Budget Trends

Budgets and revenues have steadily increased over time.

Revenue growth often outpaces budget growth, indicating improved profitability in peak years.

Higher budgets do not always guarantee higher returns.

Maximum Movie Runtime

Maximum runtime has gradually increased over decades.

1970s–1980s: 120–130 minutes

2000s onward: Movies often exceed 150 minutes

Suggests growing audience acceptance of longer, high-budget films.

Functions Implemented

to_uppercase – Converts string columns to uppercase

to_lowercase – Converts string columns to lowercase

calculate_profit – Computes profit as Revenue - Budget

revised_profit – Alternative profit calculation using a lambda function

func – Extracts genre names from JSON-like strings

How to Run

Mount Google Drive in Colab:

from google.colab import drive
drive.mount('/content/drive')


Load the dataset:

import pandas as pd
data = pd.read_csv('/content/drive/MyDrive/Colab Notebooks/imdb_data.csv')


Execute cells sequentially for:

Data exploration

Cleaning & preprocessing

Feature engineering

Revenue and profitability analysis

Conclusion

The project provides insights into movie revenue trends, profitability, language impact, and runtime evolution.

English-language movies dominate global box-office revenue.

Revenue growth generally outpaces budget increases, but high investment does not always guarantee proportional returns.

Modern films tend to have longer runtimes compared to earlier decades.

Future Work

Extend analysis to genre-based revenue trends

Analyze profitability by production companies and countries

Add visualizations using Matplotlib or Seaborn

Apply predictive modeling to forecast future movie revenues
