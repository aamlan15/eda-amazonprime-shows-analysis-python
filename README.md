# 🎬 Amazon Prime TV Shows and Movies (Exploratory Data Analysis)

## 📌 Brief One-Line Summary

An Exploratory Data Analysis (EDA) project on Amazon Prime Video's content library to uncover trends in content distribution, genres, ratings, popularity, production countries, and contributor performance.

---

## 📖 Overview

Streaming platforms have transformed the entertainment industry by providing on-demand access to vast collections of movies and television shows. Amazon Prime Video is one of the leading streaming services globally, offering content across multiple genres, languages, and regions.

This project performs an Exploratory Data Analysis (EDA) on Amazon Prime Video's content catalog using two datasets: **titles.csv** and **credits.csv**. The analysis explores content growth, audience ratings, popularity metrics, genre trends, country-wise contributions, and cast and crew involvement to derive meaningful business insights.

---

## ❓ Problem Statement

As streaming services continue to expand their content libraries, understanding the factors that influence audience engagement and content success has become increasingly important. Amazon Prime Video hosts a vast collection of movies and television shows spanning numerous genres, production regions, and audience demographics. However, the large volume of content and the diversity of available attributes make it challenging to identify meaningful patterns and trends.

This project aims to address this challenge by conducting an Exploratory Data Analysis (EDA) of Amazon Prime Video’s content catalog. By analyzing variables such as content type, genre, release year, ratings, popularity metrics, production countries, and contributor information, the study seeks to uncover insights into content distribution, audience preferences, and performance indicators.

---

## 🎯 Business Objective

The primary objective of this project is to analyze Amazon Prime Video’s content library and generate actionable insights that can support strategic decision-making.

The analysis aims to:

- Understand audience preferences and viewing trends.
- Identify high-performing genres and content categories.
- Analyze content growth over time.
- Evaluate the impact of ratings and popularity metrics.
- Study the contribution of actors, directors, and writers.
- Support data-driven content acquisition and production strategies.
- Improve customer engagement through better content recommendations.

---

## 📂 Dataset Description

### Dataset 1: `titles.csv`

Contains information about movies and TV shows such as:

- Title
- Type (Movie/Show)
- Release Year
- Runtime
- Genres
- Age Certification
- Production Countries
- IMDb Score
- IMDb Votes
- TMDB Score
- TMDB Popularity

### Dataset 2: `credits.csv`

Contains contributor information such as:

- Actor Name
- Character Name
- Role
- Director
- Writer

### Dataset Overview

| Dataset | Rows | Columns |
|----------|------:|---------:|
| title_df | 9,871 | 15 |
| credit_df | 124,235 | 5 |

---

## 🧹 Data Cleaning and Preprocessing

### Duplicate Records

| Dataset | Duplicate Records |
|----------|-----------------:|
| title_df | 3 |
| credit_df | 56 |

### Missing Values

| Column | Missing Values |
|----------|--------------:|
| description | 119 |
| age_certification | 6487 |
| seasons | 8514 |
| imdb_id | 667 |
| imdb_score | 1021 |
| imdb_votes | 1031 |
| tmdb_popularity | 547 |
| tmdb_score | 2082 |
| character | 16287 |

### Data Cleaning Steps

- Removed duplicate records.
- Checked and handled missing values.
- Converted data types where necessary.
- Standardized categorical variables.
- Prepared datasets for visualization and analysis.

---

## 📁 Project Structure

```text
Amazon-Prime-EDA/
│
├── Data/
│   ├── titles.csv
│   └── credits.csv
│
├── Notebook/
│   └── Amazon_Prime_EDA.ipynb
│
├── Project_Report.pdf
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🛠️ Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Exploratory Data Analysis

### Content Distribution
- Movies vs TV Shows Count

### Release Year Analysis
- Releases by Year
- Total Releases per Year
- Average IMDb per Year

### Genre Analysis
- Top 10 Genres by Count
- Average IMDb by Genre
- Genre vs IMDb Heatmap

### Runtime Analysis
- Runtime Distribution
- Runtime Trend Over Years
- Average Runtime by Runtime Category
- Runtime vs IMDb Scatter Plot

### Ratings Analysis
- IMDb Score Distribution
- IMDb vs TMDB Correlation Scatterplot
- Average IMDb by Rating Category

### Popularity Analysis
- Top 10 Popular Titles
- Popularity vs IMDb Scatterplot
- IMDb Votes Trend

### Country-wise Analysis
- Top 10 Production Countries
- Average IMDb by Country

### Age Certification Analysis
- Certification Distribution
- Average IMDb by Certification

### Cast and Crew Analysis
- Top 10 Actors
- Top 10 Directors
- Role Distribution

---

## 📊 Key Insights

- Movies constitute the majority of Amazon Prime Video's content library.
- Content production has increased significantly in recent years.
- Drama, Comedy, and Documentary are among the most common genres.
- Most content receives moderate to high IMDb ratings, indicating generally positive audience reception.
- IMDb and TMDB ratings exhibit a positive correlation, suggesting consistency across rating platforms.
- Highly rated content tends to attract greater audience engagement and visibility.
- The United States dominates content production, followed by several other major entertainment-producing nations.
- Age certification analysis reveals that a large portion of content targets mature audiences.
- Certain actors and directors appear frequently across successful titles, highlighting their influence on content production.
- Runtime alone does not significantly impact content ratings.

---

## 💼 Business Recommendations

Based on the insights obtained from the analysis, the following recommendations can help Amazon Prime Video enhance its content strategy and improve audience engagement:

1. **Invest in High-Performing Genres**
   - Prioritize content acquisition and production in genres that consistently achieve strong ratings and audience engagement.

2. **Leverage Data-Driven Content Decisions**
   - Utilize IMDb ratings, TMDB scores, and popularity metrics to guide content investments and strategic planning.

3. **Strengthen Personalized Recommendation Systems**
   - Enhance recommendation algorithms using genre preferences, viewing trends, and content ratings.

4. **Expand International Content Offerings**
   - Increase investment in content from diverse regions to strengthen global audience reach.

5. **Collaborate with Successful Talent**
   - Build partnerships with frequently appearing high-performing actors, directors, and writers.

6. **Maintain a Balanced Content Portfolio**
   - Combine newly released content with evergreen classics to appeal to a broader audience base.

7. **Target Diverse Audience Segments**
   - Develop content strategies for different age certification groups and viewer demographics.

8. **Monitor Emerging Trends**
   - Continuously analyze audience behavior and content performance to adapt to changing market demands.

---

## 📈 Results and Conclusion

The exploratory analysis provides valuable insights into Amazon Prime Video's content ecosystem. By examining content distribution, ratings, popularity metrics, genres, production regions, and contributor information, the study identifies patterns that influence audience engagement and content success.

The findings demonstrate how data can support strategic decisions related to content acquisition, recommendation systems, and platform growth. Leveraging these insights can help Amazon Prime Video enhance user satisfaction, improve content performance, and maintain a competitive position within the streaming industry.

---

## 🚀 Future Work

- Build a content recommendation system using machine learning.
- Perform sentiment analysis on audience reviews.
- Predict content popularity using predictive modeling techniques.
- Develop an interactive dashboard using Streamlit or Power BI.
- Compare Amazon Prime's content library with other streaming platforms such as Netflix and Disney+.

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/aamlan15/eda-amazonprime-shows-analysis-python.git
```

Navigate to the project directory:

```bash
cd eda-amazonprime-shows-analysis-python
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## 👨‍💻 Author

### Amlan Biswal

Aspiring Data Analyst | Python | Data Visualization | Exploratory Data Analysis

### Connect With Me

- LinkedIn: https://www.linkedin.com/in/amlanbiswal
- GitHub: https://github.com/aamlan15
- Email: aamlan1978@gmail.com

---

## 📚 References

- Amazon Prime Movies and TV Shows Dataset
- IMDb Database
- TMDB (The Movie Database)
- Pandas Documentation
- NumPy Documentation
- Matplotlib Documentation
- Seaborn Documentation

---
