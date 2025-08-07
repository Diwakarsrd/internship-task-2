# ✅ Task Breakdown

1. **Generate Summary Statistics**:
   - Used `pandas.describe()` to compute mean, median, std, min, max, and quartiles.
   - Transposed the result with `.T` for easier readability (column-wise).

2. **Visualize Distributions**:
   - Created **histograms** for numeric features to check their distribution.
   - Used **boxplots** to detect outliers and view the spread of data.

3. **Understand Feature Relationships**:
   - Plotted a **correlation matrix** using `seaborn.heatmap()` to observe linear relationships.
   - Used `pairplot` to visually inspect scatter plots between every pair of features.

4. **Identify Patterns & Anomalies**:
   - Observed skewed distributions in some features (e.g., salary, age).
   - Detected outliers using the IQR method.
   - Noted any strong correlations (positive or negative).

5. **Draw Feature-Level Inferences**:
   - Example: Features X and Y are highly correlated.
   - Example: Age distribution is right-skewed.
   - Example: Feature Z has many outliers and may need transformation.
