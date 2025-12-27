
#IMDB Movie Performance & Profitability Analysis

📌 Project Overview

This project focuses on exploratory data analysis (EDA) of an IMDB movie dataset enriched with financial, popularity, genre, and release-date information. The goal is to understand what factors influence movie profitability and performance, rather than only ratings.

The analysis emphasizes real-world data handling, feature engineering, and business-oriented insights using Python.

🗂️ Dataset Description

The dataset contains detailed movie-level information, including:

🔹 Financial Metrics

budget

Revenue

Profit, profit, new_profit, profit_value

🔹 Popularity & Engagement

popularity

popularity_new

🔹 Movie Metadata

title, original_title

genres, genre_names

runtime, Half_runtime

original_language

Companies, Countries

🔹 Release Information

release_date

year, month, month_Name, day

release_year

🔹 Feature Engineering

Capitalized titles

Runtime transformation

Derived profit and popularity metrics

🛠️ Tools & Technologies

Python

Pandas – data manipulation and analysis

NumPy – numerical operations

Matplotlib – data visualization

Google Colab – interactive analysis

🔍 Key Analysis Performed

Initial data inspection using head(), info(), describe() and iloc

Handling complex categorical fields such as multi-genre movies

Exploratory analysis of:

Budget vs Revenue vs Profit

Popularity vs Profitability

Runtime impact on performance

Genre-based trends

Release year and seasonal patterns

Feature engineering to improve analytical clarity

📊 Key Insights

Revenue alone is misleading — movies with high revenue may still be unprofitable due to large budgets

Popularity does not guarantee profit, highlighting the difference between audience interest and financial success

Genre plays a significant role in profitability patterns across movies

Release timing shows seasonality effects, impacting movie performance

Extremely long runtimes do not consistently lead to better popularity or profit

💡 What This Project Demonstrates

Ability to work with real-world, non-clean datasets

Strong understanding of exploratory data analysis (EDA)

Use of feature engineering to derive meaningful business metrics

Focus on business and profitability insights, not just surface-level trends

🚀 How to Run the Project

Clone the repository

Open the Jupyter Notebook

Install required libraries:

pip install pandas numpy matplotlib

Run the notebook cells sequentially

📎 Project Structure

├── data/imdb_data.csv
├── notebook/IMDB_Movie_Analysis.ipynb
└── README.md

📬 Contact

Saransh Chahar-Aspiring Data Analyst / Data ScientistGitHub: https://github.com/Saransh45

