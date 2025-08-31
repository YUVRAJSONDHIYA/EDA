🎬 Amazon Prime Exploratory Data Analysis (EDA)
📌 Project Overview

Amazon Prime Video is one of the leading global streaming platforms offering a wide range of movies, TV shows, and original content across genres.
This project performs Exploratory Data Analysis (EDA) on Amazon Prime’s content dataset (~124K records, 19 attributes) to uncover patterns behind content success and provide actionable business insights.

The primary question explored:
👉 Why do only ~5–10% of titles achieve high IMDb/TMDb ratings?

🎯 Objectives

Clean and preprocess dataset (124,347 rows × 19 columns)

Explore distribution of movies vs shows

Study genre, runtime, age certification, and country patterns

Identify correlations between IMDb/TMDb scores, popularity, and votes

Extract business insights that can guide content strategy

🗂️ Dataset Description

Source: Titles & Credits dataset (merged)

Size: 124,347 records × 19 attributes

Key Features:

title → Content name

type → Movie / TV Show

genres → Genres/categories

release_year → Release year

runtime → Duration (minutes)

production_countries → Countries

imdb_score, imdb_votes → IMDb ratings & votes

tmdb_score, tmdb_popularity → TMDb ratings & popularity

age_certification → Audience certification

🛠️ Tech Stack

Python 🐍

Data Wrangling: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Exploratory Plots: Countplots, Boxplots, Violin plots, Heatmaps, Scatterplots, Line charts, Pie charts

📊 Key Insights

✔ Movies dominate the library compared to TV Shows
✔ Drama, Comedy, Action, and Thriller are the top genres
✔ IMDb ratings cluster around 5.5–7, only a few titles stand out
✔ Runtimes between 90–120 mins tend to attract higher popularity
✔ Strong positive correlation between IMDb & TMDb scores
✔ Content spike observed during 2017–2020
✔ USA & India are top production countries

📈 Example Visualizations

Movies vs Shows Distribution (Countplot)

Top 10 Genres (Pie Chart)

IMDb Score Distribution (Boxplot)

Runtime vs TMDb Popularity (Scatterplot)

Average IMDb Score Trend over Years (Line Chart)

Heatmap of Missing Values (Data Quality)

📬 Author
👤 Yuvraj Sondhiya

💼 Aspiring Data Scientist

📧 yuvraj123son@gmail.com

🔗 www.linkedin.com/in/yuvrajson

