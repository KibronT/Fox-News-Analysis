# Fox News and IMDb Data Analysis

This repository contains a series of Python-based data analysis projects that explore trends, patterns, and statistical relationships within two datasets: a **Fox News dataset** and the **IMDb Top 10,000 Movies dataset**. These analyses leverage popular Python libraries such as `pandas`, `matplotlib`, `statsmodels`, and `scipy`.

## Fox News Data Analysis

This section includes insights and visualizations derived from analyzing Fox News posts:

### Key Analyses:
1. **Dataset Overview**:  
   - Determined the number of rows and columns in the dataset.

2. **Post Analysis**:  
   - Counted posts by type (e.g., `link`, `video`) and specific metrics such as posts with >500 shares.

3. **Statistical Summaries**:  
   - Calculated maximum, average, and minimum values for key metrics: reactions, comments, shares, and more.

4. **Visualizations**:  
   - **Histograms**: Plotted distributions for `num_reactions`, `num_comments`, and `num_shares`.  
   - **Scatterplots**: Visualized relationships between these variables, identifying positive correlations.

5. **Post Type Comparisons**:  
   - Compared average metrics (reactions, comments, shares, etc.) across different `status_type`.

6. **Angry Post Analysis**:  
   - Identified posts with unusually high anger reactions.
   - Examined corresponding `num_likes` and `num_loves` metrics.
   - Provided insights into controversial topics, often political in nature.

7. **Hypothesis Testing**:  
   - Conducted a one-sided Z-test to evaluate if the proportion of people who believe climate change is a major issue has significantly increased.

---

## IMDb Data Analysis

This section focuses on exploring the relationship between movie ratings, metascores, and genres:

### Key Analyses:
1. **Regression Analysis**:  
   - Built an OLS regression model to predict `Metascore` based on `Rating`.  
   - R² Value: **0.541**  
   - Regression Equation: `Metascore = -31.8830 + 13.3961 × Rating`

2. **Genre Analysis**:  
   - Conducted a t-test to determine if "Action" movies have significantly different metascores compared to "Non-Action" movies.

---

## Statistical Insights

### Key Concepts:
- **Confidence Intervals**:  
  - Interpreted intervals (e.g., [2.1, 3.5]) to infer population parameters.

- **Hypothesis Testing**:  
  - Applied statistical tests (Z-test, t-test) to evaluate trends and relationships within the datasets.

---

## Requirements

To run the analyses, ensure you have the following:

- **Python 3.x**
- Libraries:  
  - `pandas`, `matplotlib`, `statsmodels`, `scipy`, `numpy`

---

## How to Run

1. **Clone the repository**

2. Install the required libraries:
  - `pip install pandas matplotlib statsmodels scipy numpy`
3. Run the Jupyter notebooks
  - Navigate to the project directory and execute the scripts to reproduce the analyses and visualizations.

