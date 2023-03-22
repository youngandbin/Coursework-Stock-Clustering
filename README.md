# Data
- The data was collected from Wharton Research Data Services(WRDS).
- contains information for publicly traded companies in the United States.
  - 1) Quarterly financial statements 
  - 2) Daily prices.

# Task
- As a method of defining asset classes for asset allocation, we use k-means clustering.
- After data preprocessing (e.g., removing outliers, scaling features), clustering was conducted and clusters are evaluated on Silhoueete analysis.
- Finally, various asset classes defined in different ways were compared.
  - 1) k-means clustering with financial statements
  - 2) k-means clustering with style factors
  - 3) Style classification, a traditional method
- The three methods above were compared based on the following criteria.
  - 1. Do they have distinct characteristics?
    - Distribution of financial features (e.g., scatter plot, boxplot)
  - 2. Do they move differently in the market?
    - Return correlations (intra-correlations and inter-correlations)
    - Return and risk characteristics

# Conclusion
- A key determinant of portfolio returns is asset allocation, which requires proper asset classification.
- AI models allow you to classify assets in a different way than traditional methods.
- K-means clustering is one of the simplest and popular unsupervised machine learning algorithms.
- As a result of classifying stocks via clustering with financial properties, stocks are grouped differently from the existing method.
