# 📊 Social Media Engagement Analytics Using Python

## 📌 Project Overview

This project analyses social media engagement data using Python. The main objective is to understand user behaviour, identify engagement trends, and evaluate content performance across different social media metrics.

The project covers data importing, data cleaning, data transformation, exploratory data analysis, statistical analysis, and data visualization.

## 🎯 Project Objectives

- Import and explore social media engagement data.
- Clean missing values and duplicate records.
- Handle incorrect data types and inconsistent categories.
- Perform data transformation using Pandas and NumPy.
- Calculate statistical measures.
- Analyse engagement patterns across different categories.
- Create meaningful visualizations.
- Generate actionable insights from the dataset.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook / Google Colab

## 📂 Dataset Information

**Dataset:** `social_media_engagement_5000.csv`

The dataset contains social media engagement metrics, including:

- Likes
- Comments
- Shares
- Impressions
- Watch Time
- Engagement Rate
- Followers
- Post Type
- Content Category
- Country
- Age
- Gender
- Device Type
- Account Verification
- Sentiment
- Posted Date

## 📋 Project Workflow

### 1. Data Import & Setup

- Imported the dataset using Pandas.
- Checked dataset structure and dimensions.
- Converted date columns into datetime format.
- Checked data types.
- Performed basic NumPy array operations.

### 2. Data Cleaning

- Identified missing values using `isnull()` and `isna()`.
- Handled missing values using appropriate techniques.
- Identified and removed duplicate records.
- Corrected incorrect data types.
- Standardized categorical values.
- Checked unrealistic engagement values.
- Extracted hashtag counts.
- Cleaned sentiment labels.

### 3. Exploratory Data Analysis (EDA)

Used Pandas functions including:

- `head()`
- `tail()`
- `shape`
- `columns`
- `info()`
- `dtypes`
- `describe()`
- `value_counts()`
- `unique()`
- `nunique()`
- `groupby()`
- Correlation matrix

### 4. Data Wrangling

- Created new analytical features.
- Calculated engagement scores.
- Extracted hashtag counts.
- Grouped data by post type, country, and sentiment.
- Performed data transformation and aggregation.

### 5. Statistical Analysis

Calculated the following statistical measures:

- Mean
- Median
- Mode
- Standard Deviation
- Variance
- Percentiles
- Skewness
- Kurtosis

Statistical analysis was performed on likes, comments, shares, watch time, engagement rate, and followers.

## 📊 Data Visualization

Created visualizations using Matplotlib, Seaborn, and Plotly.

### Matplotlib

1. Scatter Plot – Likes vs Impressions
2. Line Chart – Daily Engagement Trend
3. Bar Chart – Posts by Category
4. Pie Chart – Gender Distribution
5. Histogram – Age Distribution
6. Box Plot – Engagement Rate

### Seaborn

7. Count Plot – Post Type
8. Bar Plot – Average Likes by Category
9. Violin Plot – Followers vs Sentiment
10. Pair Plot – Numerical Features
11. Heatmap – Correlation Matrix
12. Swarm Plot – Engagement vs Device

### Plotly

13. Interactive Line Chart
14. Interactive Bar Chart
15. Interactive Bubble Chart
16. Interactive Scatter Chart

## 🔍 Key Findings & Insights

### 1. Content Performance

- Video posts achieved the highest average engagement rate of **1.1224**.
- Food content was the top-performing category with an average engagement rate of **1.3586**.
- Brazil recorded the highest country average engagement rate of **1.5407**.
- The USA recorded the lowest country average engagement rate of **0.5766**.

### 2. User Trends

- Age 24 recorded the highest average engagement rate of **2.8973** among the analysed ages.
- Verified accounts achieved an average engagement rate of **1.0543**.
- Non-verified accounts achieved an average engagement rate of **0.9547**.

### 3. Behavioural Insights

- Mobile users recorded the highest average watch time of **4,087.83 seconds**.
- Tablet users recorded an average watch time of **3,979.74 seconds**.
- Desktop users recorded an average watch time of **3,974.79 seconds**.
- The dataset contains posting dates but not actual posting times. Therefore, the best time of day for impressions could not be identified.

### 4. Sentiment Analysis

Average engagement rate by sentiment:

| Sentiment | Average Engagement Rate |
|---|---:|
| Negative | 1.0385 |
| Neutral | 0.9912 |
| Positive | 0.9197 |

Additional findings:

- Negative sentiment posts lead in average likes and shares.
- Neutral sentiment posts lead in average comments.
- Positive sentiment posts lead in average impressions.

## 💡 Business Insights

- Video content can be prioritised based on its engagement performance in this dataset.
- Food-related content shows strong engagement potential.
- Verified accounts show a higher average engagement rate than non-verified accounts.
- Mobile users demonstrate the highest average watch time.
- Sentiment analysis helps identify differences in audience engagement behaviour.
- Country-level engagement differences can help guide content strategies.

## 🏁 Conclusion

This project demonstrates how Python can be used to analyse social media engagement data and identify meaningful patterns.

The analysis reveals that engagement varies across post types, content categories, countries, age groups, account verification status, device types, and sentiment.

Video posts and food-related content perform strongly, Brazil records the highest country-level average engagement rate, and mobile users have the longest average watch time.

Negative-sentiment posts show the highest average engagement rate in this dataset.

Overall, this project helped develop practical skills in Python programming, data cleaning, exploratory data analysis, statistical analysis, data visualization, and analytical reporting.

## 📁 Repository Structure

```text
social-media-engagement-analytics/
│
├── README.md
├── Module_5_Social_Media_Engagement_Analytics.ipynb
└── social_media_engagement_5000.csv
```

## 🚀 How to Run This Project

1. Clone this repository.
2. Download or add the dataset to the project folder.
3. Install the required Python libraries.

```bash
pip install pandas numpy matplotlib seaborn plotly jupyter
```

4. Open Jupyter Notebook.

```bash
jupyter notebook
```

5. Open the project notebook.
6. Run all cells to reproduce the analysis and visualizations.

## 👩‍💻 Skills Demonstrated

- Python Programming
- Data Cleaning
- Data Manipulation
- NumPy Operations
- Pandas Analysis
- Exploratory Data Analysis
- Statistical Analysis
- Data Visualization
- Data Interpretation
- Analytical Thinking

## 📌 Project Information

**Project Name:** Social Media Engagement Analytics Using Python

**Module:** Module 5 – Python for Data Analysis

**Project Type:** Data Analytics

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly

---

⭐ If you find this project useful, feel free to explore the repository!
