# CinemaScope-Analytics-Unveiling-the-Dynamics-of-Movie-Success

## 📖 Project Overview

CinemaScope Analytics is an end-to-end Data Analytics project focused on uncovering the key factors that influence movie success. Using SQL, Excel, and Power BI, the project analyzes movie industry data to identify trends in financial performance, genre popularity, audience ratings, director impact, and star influence.

The project follows the complete analytics lifecycle, including data cleaning, transformation, exploratory data analysis (EDA), dashboard development, and business recommendations. The final outcome is an interactive Power BI dashboard that provides actionable insights for movie studios, investors, and entertainment industry stakeholders.

---

## 🎯 Project Objectives

- Analyze movie performance across different genres and time periods.
- Identify the relationship between movie budgets and gross earnings.
- Evaluate the impact of directors and lead actors on movie success.
- Study IMDb score distributions and audience preferences.
- Analyze country-wise movie production trends.
- Build an interactive Power BI dashboard for data-driven decision-making.
- Generate business recommendations based on analytical findings.

---

## 🛠️ Tools & Technologies Used

### Database & Data Cleaning
- PostgreSQL
- SQL

### Data Analysis
- Microsoft Excel
- Pivot Tables
- Charts & Visualizations
- Data Cleaning Techniques

### Dashboard Development
- Power BI
- DAX Measures
- Interactive Filters & Slicers

### Version Control
- GitHub

---

## 📊 Dataset Information

The dataset contains detailed information about movies, including:

- Movie Name
- Genre
- Year of Release
- Rating
- Director
- Star
- Budget
- Gross Earnings
- IMDb Score
- Runtime
- Country
- Production Company
- Number of Votes

Total Records Analyzed: **7,665 Movies**

---

## 🔄 Project Workflow

### 1️⃣ Data Cleaning Using SQL

The raw dataset was cleaned and transformed using PostgreSQL.

Tasks Performed:
- Handled missing values
- Removed duplicate records
- Standardized column formats
- Converted data types
- Created derived columns
- Sorted and transformed data for analysis

---

### 2️⃣ Exploratory Data Analysis in Excel

The cleaned dataset was exported to Excel for detailed exploratory analysis.

Analysis Conducted:

- Missing Data Handling
- Data Sorting and Filtering
- Genre Distribution Analysis
- Budget vs Gross Comparison
- IMDb Score Categorization
- Country-wise Production Analysis
- Director Performance Analysis
- Runtime Analysis
- Top Grossing Movies by Year
- Rating Popularity Trends
- Profitability Analysis
- Decade-wise Movie Analysis
- Correlation Analysis
- Budget Evolution Analysis
- Production Company Analysis
- Time-Series Genre Analysis

---

### 3️⃣ Power BI Dashboard Development

An interactive dashboard was developed using Power BI to visualize movie industry trends and performance metrics.

---

# 📈 Dashboard Structure

## 🎬 Page 1: Industry Overview

### Key Metrics
- Total Movies
- Average IMDb Score
- Total Gross Earnings
- Average Budget

### Visualizations
- Movies by Genre
- Rating Distribution
- Movies by Decade
- Country-wise Movie Production

### Interactive Filters
- Genre
- Rating
- Decade

---

## 💰 Page 2: Financial Analysis

### Key Metrics
- Total Gross Earnings
- Average Budget
- Average Profitability

### Visualizations
- Budget vs Gross Earnings Scatter Plot
- Average Gross by Genre
- Top Grossing Movies
- Budget Evolution Over Time

### Interactive Filters
- Genre
- Year
- Decade

---

## 🌟 Page 3: Director & Star Analysis

### Visualizations
- Top Directors by Average Gross
- Top Directors by IMDb Score
- Top Stars by Gross Earnings
- Top Stars by IMDb Score
- Highest Rated Movie
- Top Directors by Profitability

### Interactive Features
- Director Selection
- Star Selection
- Movie Portfolio Analysis

### Interactive Filters
- Director
- Star
- Genre
- Year

---

## 📌 Key Business Findings

### 1. Animation is the Most Financially Rewarding Genre

Animation movies generated the highest average gross earnings relative to budget, achieving approximately 3.1x return on investment. Franchise-driven studios such as Disney, Pixar, and DreamWorks significantly contributed to this trend.

---

### 2. United States Dominates Movie Production

The United States accounts for over 70% of all movies in the dataset, highlighting Hollywood's dominance in global film production and distribution.

---

### 3. Box Office Revenue Has Increased Significantly Over Time

Average movie gross earnings increased nearly sixfold from the 1980s to the 2010s, reflecting global market expansion, franchise growth, and premium viewing experiences.

---

### 4. High IMDb Scores Are Rare

Only a small percentage of movies achieve IMDb scores above 8.0, indicating the challenge of producing critically acclaimed films.

---

### 5. Runtime Shows a Weak Positive Relationship with IMDb Score

Longer movies tend to receive slightly higher ratings, although runtime alone is not a strong predictor of audience satisfaction.

---

## 💡 Business Recommendations

### 🎥 Invest in High-Performing Genres

Prioritize Animation and Action genres due to their strong financial performance and audience appeal.

### 🌍 Expand International Collaborations

Develop partnerships with emerging movie markets, particularly China, to access growing global audiences.

### ⭐ Leverage Proven Talent

Collaborate with directors and actors who consistently deliver strong box office returns and audience engagement.

### 💰 Adopt Data-Driven Investment Strategies

Utilize historical performance metrics, profitability patterns, and audience ratings when greenlighting new projects.

### 📊 Build Predictive Decision Models

Implement predictive analytics models that combine genre, budget, director, star, and IMDb score data to forecast future movie performance.

---

## 📈 Sample DAX Measures Used

### Total Movies

```DAX
Total Movies = COUNTROWS(movies)

## 🔗 Author
Avantika Rawat
