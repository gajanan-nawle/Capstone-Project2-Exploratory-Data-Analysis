# 🎬 Exploratory Data Analysis: Amazon Prime Video Library

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Libraries](https://img.shields.io/badge/Libraries-Pandas%20%7C%20Seaborn%20%7C%20Matplotlib-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview
This project involves a comprehensive **Exploratory Data Analysis (EDA)** of the Amazon Prime Video dataset. The goal was to analyze the platform's content library (over 9,000 titles) to uncover trends in content strategy, audience preferences, and library growth over time.

Using Python libraries such as **Pandas**, **Seaborn**, and **Matplotlib**, I cleaned the data, engineered features, and visualized key insights to answer business questions regarding content dominance, genre popularity, and quality consistency.

---

## 📂 The Dataset
The analysis uses two primary datasets:
* **`titles.csv`**: Contains metadata for over 9,000 movies and TV shows (ID, Title, Genre, Release Year, IMDb Score, etc.).
* **`credits.csv`**: Contains over 124,000 records of cast and crew members (Actors, Directors) linked to the titles.

**Key Data Cleaning Steps:**
* Handled missing values in `seasons` (filled with 0 for movies) and `age_certification`.
* "Exploded" the `genres` column to allow for accurate multi-genre analysis.
* Merged datasets to analyze actor and director participation.

---

## 📊 Key Findings & Visualizations

### 1. Content Dominance: Movies vs. TV Shows
**Question:** Is the platform focused more on movies or episodic content?
* **Finding:** The library is overwhelmingly dominated by feature films. **Movies make up 86.3%** of the content, while TV Shows account for only 13.7%.

*(Optional: Drag and drop your Pie Chart image here)*

### 2. Top Genres
**Question:** Which genres are most prevalent?
* **Finding:** **Drama** is the #1 genre by a significant margin, followed by **Comedy** and **Thriller**. Niche genres like Sci-Fi and Fantasy are less represented.

*(Optional: Drag and drop your Genre Bar Chart here)*

### 3. Library Growth Over Time
**Question:** How has Amazon's content acquisition evolved?
* **Finding:** There was an **exponential increase** in content added to the library starting around 2015, indicating an aggressive expansion strategy to compete with other streaming giants.

*(Optional: Drag and drop your Line Chart here)*

### 4. Quality Analysis (IMDb Scores)
**Question:** Is the content generally high quality?
* **Finding:** The average IMDb score is **5.98**, with a normal distribution. This suggests the library relies heavily on "average" rated content rather than a high volume of critically acclaimed hits (7.0+).

*(Optional: Drag and drop your Histogram image here)*

### 5. Top Talent
**Question:** Which actors and directors appear most often?
* **Finding:** The list is topped by classic actors (e.g., **George 'Gabby' Hayes**) and directors (e.g., **Joseph Kane**), revealing that Amazon possesses a deep catalog of classic Westerns and older cinema.

---

## 💡 Actionable Business Insights

Based on the data, the following recommendations are proposed for stakeholders:

1.  **Content Strategy (Quality over Quantity):** With a mean rating of ~6.0, there is a clear opportunity to improve perceived value by acquiring titles with proven IMDb scores of **7.0+**.
2.  **Diversification:** The library is saturated with Drama. To attract new subscriber segments, the platform should invest in under-represented high-potential genres like **Animation** and **Sci-Fi**.
3.  **Marketing "Classic" Collections:** The data reveals a strong backlog of classic films. Marketing teams can bundle these into "Classic Movie" or "Western" collections to target specific demographics, leveraging the high volume of content featuring actors like Roy Rogers and Gene Autry.

---

## 🛠️ Technologies Used
* **Python**
* **Pandas** (Data Manipulation)
* **NumPy** (Numerical Operations)
* **Matplotlib & Seaborn** (Data Visualization)
* **Google Colab** (Development Environment)

