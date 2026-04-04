# 📊 Netflix Data Analysis Project

## 📌 Project Title
Netflix Dataset Analysis – Content Trends and Strategic Insights

## 👨‍💻 Author
**Md Tarik Anvar**  
Final Year B.Tech – Computer Science and Engineering (Machine Learning & Data Science)  
Central University of Jharkhand  

---

# 📖 Project Overview

This project focuses on analyzing the Netflix dataset to understand content distribution patterns, identify key trends, and generate strategic recommendations for content planning and growth.

The dataset contains detailed information about movies and TV shows available on Netflix, including:

- Title
- Director
- Cast
- Country
- Release Year
- Rating
- Duration
- Genre
- Date Added
- Content Type

The goal of this project is to transform raw data into meaningful insights using data cleaning, analysis, and visualization techniques.

---

# 🎯 Problem Statement

With increasing competition from streaming platforms such as:

- Amazon Prime Video
- Disney+
- Regional OTT Platforms

Netflix needs to continuously evaluate its content strategy.

This project addresses the problem:

**"Content Trends Analysis for Strategic Recommendations"**

The objective is to analyze:

- Growth of content over time
- Distribution of Movies vs TV Shows
- Popular genres
- Country-wise content contribution
- Audience rating distribution

These insights help identify opportunities for improving content strategy.

---

# 🎯 Objectives

The main objectives of this project are:

- Analyze the distribution of Movies vs TV Shows
- Identify the most popular genres
- Study country-wise content production
- Analyze content growth over time
- Examine rating distribution patterns
- Provide strategic recommendations based on data insights

---

# 📂 Dataset Information

**Dataset Name:**  
Netflix Dataset

**Total Records:**  
7,789

**Total Columns:**  
11

**Time Range:**  
2008 – 2021

**Dataset Features:**

- show_id
- type
- title
- director
- cast
- country
- date_added
- release_year
- rating
- duration
- listed_in

---

# 🛠️ Technology Stack

## Programming Language

Python

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn

## Development Environment

- Google Colab
- Jupyter Notebook

## Data Format

CSV

## Version Control

GitHub

---

# 🔄 Project Workflow

## Step 1 — Data Loading

The dataset was loaded using Pandas into a structured DataFrame.

```python
import pandas as pd

df = pd.read_csv("netflix_dataset.csv")
df.head()
```

---

## Step 2 — Data Cleaning

Data cleaning was performed to ensure accurate analysis.

Key operations:

- Handling missing values
- Converting date formats
- Standardizing duration format
- Removing duplicates
- Fixing inconsistent values

```python
df["date_added"] = pd.to_datetime(df["date_added"])
df.drop_duplicates(inplace=True)
```

---

## Step 3 — Data Exploration

Exploratory Data Analysis (EDA) was performed to understand patterns and relationships in the dataset.

Techniques used:

- Grouping
- Filtering
- Aggregation
- Statistical summaries

```python
df["type"].value_counts()
```

---

## Step 4 — Data Visualization

Visualizations were created to represent trends clearly.

Charts Used:

- Bar Charts
- Line Charts
- Boxplots
- Heatmaps

```python
import seaborn as sns
import matplotlib.pyplot as plt

sns.countplot(data=df, x="type")
plt.show()
```

---

# 📊 Key Insights

## Movies Dominate the Platform

The number of movies is more than double the number of TV shows.

This indicates that Netflix prioritizes movie content over episodic content.

---

## Rapid Content Growth After 2016

Netflix significantly increased content production after 2016.

Peak content addition occurred in:

2019

This reflects an aggressive expansion strategy.

---

## Focus on Mature Audience

Most content ratings are:

- TV-MA
- TV-14

This indicates that Netflix primarily targets adults and older teenagers.

---

## Top Content Producing Countries

Leading countries:

1. United States
2. India

This shows strong content production from these regions.

---

## Most Popular Genres

Top genres:

- International Movies
- Dramas
- Comedies

This indicates that Netflix focuses on globally appealing content.

---

# 📈 Business Recommendations

Based on the analysis, the following recommendations were proposed:

## Increase TV Show Production

TV shows improve user engagement and retention.

---

## Expand Family-Friendly Content

Increase:

- TV-G
- PG

To compete with platforms like Disney+.

---

## Expand Local Content Strategy

Continue investing in:

- Indian content
- Regional productions

Expand to:

- UK
- Japan

---

# 👥 Target Users

## Primary Users

- Content Strategy Team
- Marketing Team
- Executive Leadership

## Secondary Users

- Competitor Platforms
- Production Studios
- Media Analysts

---

# 📊 Example Visualizations

The project includes:

- Movies vs TV Shows distribution
- Content growth over time
- Country-wise distribution
- Genre popularity
- Rating distribution

---

# 🚀 How to Run the Project

## Step 1 — Clone the Repository

```bash
git clone https://github.com/git-tarik/VOIS_AICTE_Oct2025_MajorProject_Md_Tarik_Anvar.git
```

---

## Step 2 — Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

---

## Step 3 — Run the Notebook

```bash
jupyter notebook
```

Open:

```
Netflix_Data_Analysis.ipynb
```

---

# 📁 Project Structure

```
Netflix-Data-Analysis/
│
├── data/
│     netflix_dataset.csv
│
├── notebooks/
│     Netflix_Data_Analysis.ipynb
│
├── images/
│     charts/
│
├── README.md
│
└── requirements.txt
```

---

# 📌 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Python Programming
- Problem Solving
- Business Insight Generation
- GitHub Project Documentation

---

# ⭐ Future Improvements

- Add Machine Learning prediction model
- Build interactive dashboard
- Deploy project using Streamlit
- Perform sentiment analysis on reviews
- Automate data pipeline

---

# 📜 License

This project is for educational and academic purposes.

---

# 🙌 Acknowledgement

This project was developed as part of academic coursework and practical data analysis learning.
