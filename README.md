# 🎬 Movie Analysis Dashboard

A data analysis project using a real-world movie dataset to explore trends, distributions, and insights across genres, budgets, ratings, and more.

## 📁 Dataset Overview

The dataset consists of 3,800+ movies and 28 features, including:
- Title, director, actors
- Genres
- IMDb score
- Budget and Gross earnings
- Content rating

## 🧹 Data Cleaning

Key preprocessing steps:
- Handled missing values (e.g., aspect_ratio, content_rating)
- Dropped irrelevant or redundant columns
- Converted numerical fields to appropriate types
- Rounded imdb_score for easier analysis

## 📊 Visual Analysis

### 1. IMDb Score Over Time
- Line chart showing how average IMDb scores have changed by year.

### 2. Genre Analysis
- Bar chart of the most common genres
- Boxplot comparing IMDb scores across genres

### 3. Budget vs Gross Earnings And Budget vs IMDB Score
- Scatter plot to understand correlation between budget and gross revenue, and budget and IMDB score

### 4. Duration vs IMDB Score
- Scatter plot to understand correlation between duration and IMDB score

### 5. Movies Analysis by Revenue, IMDB scores and ROI
- Top 10 movies by the gross revenue, IMDB scores and ROI (gross revenue - budget/ budget)

### 6. Actor & Director Insights
- Top directors IMDb score.
- Top actors based on frequency of appearance and IMDB score.

## 📌 Tools & Libraries

- Python (Jupyter Notebook)
- Pandas
- Matplotlib
- Seaborn

## 🚀 Future Enhancements (Optional)
- Build a Streamlit dashboard UI
- Add recommendation engine logic
- Export insights as PDF reports

## 📝 Author

*Debcode2006*
