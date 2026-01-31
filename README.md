# Amazon-Prime-Video
📌 Project Overview

This project performs end-to-end Exploratory Data Analysis (EDA) and data wrangling on Amazon Prime Video movies and TV shows data. The objective is to transform raw, unstructured datasets into an analytics-ready format and generate actionable insights that support content strategy, audience engagement, and platform growth. The project follows a real-world analytics workflow used in product, media, and streaming analytics teams.

🎯 Business Objectives

Understand the distribution of Movies vs TV Shows

Identify top-performing genres and content categories

Analyze content release trends over time

Examine ratings and popularity patterns

Assess the influence of cast and crew on content performance

Prepare clean datasets for machine learning and BI dashboards

📂 Dataset Description

The project uses two datasets:

titles.csv: Metadata for movies and TV shows (title, type, runtime, genres, release year, ratings, popularity)

credits.csv: Cast and crew information (actors, directors, roles)

Both datasets contain missing values, duplicates, and mixed data types, which are handled through systematic data cleaning and preprocessing.

🛠️ Tools & Technologies

Python (Pandas, NumPy)

Data Visualization (Matplotlib, Seaborn)

Data Wrangling & Cleaning

Exploratory Data Analysis (EDA)

Feature Engineering

SQL-ready data modeling

Power BI / Tableau ready outputs

⚙️ Data Wrangling & EDA Steps

Standardized column names for analytics compatibility

Removed duplicate records and handled inconsistent formats

Treated missing values using business logic (median, mode, placeholders)

Cleaned list-type fields such as genres

Merged normalized datasets using relational joins

Engineered new features such as content age and content type flags

Performed univariate and multivariate analysis

Created visualizations to highlight trends and patterns

📊 Key Insights

A small number of genres dominate the platform, indicating focused content investment

Movies outnumber TV shows, but TV shows show higher recent growth

Content production increased significantly after 2015

Ratings and popularity vary by genre and region

Certain cast and crew members are associated with higher-rated content

💼 Business Impact

The insights from this analysis can support content acquisition planning, recommendation system improvement, targeted marketing, and regional content expansion. The cleaned dataset can also be used to build predictive models for rating prediction and content recommendation, improving user engagement and platform retention.
