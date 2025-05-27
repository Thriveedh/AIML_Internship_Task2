# AIML_Internship_Task2
This task performs an exploratory data analysis on the Titanic dataset. The goal is to understand the distribution of data, relationships between variables, detect patterns, and visualize key features related to passenger survival.

## Overview of Analysis

### 1. Summary Statistics
- Computed descriptive statistics for all columns.
- Provided insights into the data types, counts, unique values, mean, standard deviation, min/max, and percentiles for numerical and categorical features.

### 2. Histograms and Boxplots
- Created histograms for numeric features to examine distributions and identify skewness.
- Plotted boxplots for these numeric features to detect outliers.
- Additionally, visualized `fare` distributions across passenger classes (`pclass`) using boxplots.

### 3. Correlation Matrix & Pairplot
- Computed the correlation matrix of selected numeric features plus the survival indicator (`survived`).
- Visualized the correlation matrix as a heatmap to assess linear relationships.
- Created a Seaborn pairplot for `survived`, `age`, `fare`, `sibsp`, and `parch` to explore pairwise relationships and differences between survived and non-survived groups.

### 4. Identify Patterns, Trends, or Anomalies
- Created count plots showing survival distribution by `sex` and `pclass`.
- Visualized age distribution for survivors and non-survivors using stacked histograms with KDE overlays.

### 5. Basic Feature-Level Inferences from Visuals
- Used violin plots to compare the distribution of `fare` and `age` between survivors and non-survivors.
- These visualizations helped infer the impact of fare paid and age on survival likelihood.

