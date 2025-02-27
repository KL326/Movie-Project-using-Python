# 🎬 Movie Data Analysis

Welcome to the **Movie Data Analysis Project**! This project explores the relationship between various movie attributes, such as budget, gross revenue, and runtime, using Python for data analysis and visualisation. 📊🎥

---

## 🚀 Project Overview

This project analyses movie data to identify trends and correlations between different features like budget, gross revenue, and ratings. The goal is to uncover insights regarding the financial and critical success of movies using statistical analysis and data visualisation techniques.

---

## 🔧 Tools and Technologies

- **Pandas**: Data cleaning and manipulation.
- **NumPy**: Numerical computations.
- **Seaborn**: Data visualisation.
- **Matplotlib**: Plotting graphs and charts.
- **SciPy**: Statistical analysis (ANOVA test).

---

## 🛠️ Steps in the Analysis

### 1️⃣ Data Loading and Cleaning
- Load movie data from a CSV file.
- Remove missing values to ensure data integrity.
- Convert relevant columns to appropriate data types.

### 2️⃣ Data Exploration
- Display dataset information and check for missing values.
- Sort movies based on `gross` revenue.

### 3️⃣ Visualising Budget vs Gross Revenue
- Use scatter plots to examine the correlation between `budget` and `gross revenue`.
- Implement a regression plot using Seaborn to visualise the trend.

### 4️⃣ Correlation Analysis
- Compute the Pearson correlation between numerical variables such as `budget`, `gross`, `runtime`, `score`, `votes`, and `year`.
- Generate a heatmap to highlight strong correlations.

### 5️⃣ Statistical Analysis (ANOVA Test)
- Convert categorical columns to numerical format using category encoding.
- Perform **ANOVA (Analysis of Variance)** to determine whether categorical variables significantly impact `gross revenue`.

---

## 📊 Key Insights

1. **Budget vs Gross Revenue**: A strong positive correlation (~0.74) exists, indicating that higher-budget movies tend to generate higher revenue.
2. **Other Significant Correlations**:
   - `votes` and `gross revenue` also show a strong correlation (~0.61), suggesting popular movies tend to earn more.
   - `runtime` has a moderate correlation with `gross revenue`, implying longer movies might be more financially successful.
3. **ANOVA Results**:
   - Certain categorical variables may significantly impact movie revenue, but further analysis is required to pinpoint specific categories.

---

## 🛠️ How to Run This Project

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/movie-analysis.git
   ```
2. Install required libraries:
   ```bash
   pip install pandas numpy seaborn matplotlib scipy
   ```
3. Run the Python script:
   ```bash
   python movie_analysis.py
   ```

---

## 📊 Visualisations

This project includes visualisations such as:
- **Scatter plot**: Budget vs Gross Revenue
- **Regression plot**: Trendline for budget and gross
- **Heatmap**: Correlation matrix for numerical features

Screenshots of these visuals can be found in the repository.

