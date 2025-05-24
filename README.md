Disney+ Hotstar Data Analysis 📊
This project presents an exploratory data analysis (EDA) and basic predictive modeling on the Disney+ Hotstar catalog dataset. It covers data loading, cleaning, visualization, and a linear regression model to study factors influencing IMDb ratings.

# 📁 Dataset Overview
## Source: disney_plus_shows.csv
## Total Records: 992
## Attributes: 19 features including title, genre, runtime, IMDb rating, language, country, and release year.

# 🔧 Technologies Used:
## Python
## Pandas, NumPy
## Matplotlib, Seaborn
## Scikit-learn

# 🧼 Data Cleaning
### Removed 74 duplicate entries
### Converted runtime, imdb_votes, released_at, and added_at to appropriate formats
### Handled missing and inconsistent values

# 📊 Key Exploratory Insights
## Top Genres: Documentary, Comedy-Family
## Top Languages: English, Spanish, French
## Most Common Content Type: Movies
## Average IMDb Rating: 6.66
## Country-wise Distribution: Dominated by the USA
## Release Trends: Peaks around 2003, 2017, and 2019

# 📈 Visualizations
### Content type distribution
#### IMDb rating distribution
#### Top 10 genres and languages
#### Content release trend over years
#### IMDb rating by content type (box plot)
#### Country-wise content distribution

# 📉 Predictive Modeling
## Simple Linear Regression
### Objective: Predict IMDb ratings using runtime
### Result: Weak correlation — runtime alone is a poor predictor
### R² Score: Low

## Recommendation: Include more features like genre, release year, or director popularity

# 📌 Conclusion
## While runtime has minimal predictive power for IMDb ratings, the analysis provides rich insights into Disney+ Hotstar’s content strategy and audience preferences. Future modeling can be improved with richer feature engineering.


