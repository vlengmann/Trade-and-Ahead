# Trade and Ahead
 Unsupervised learning measuring performance of stocks within different sectors
 

---

## Purpose

Conduct a data analysis of the provided stock data, segment the stocks into homogeneous groups based on specified attributes, and generate insights into the distinctive characteristics of each group.

---


## Methodology

### Clustering Techniques:

**K-Means Clustering:** Group similar stocks based on their financial metrics.

**Silhouette Coefficient:** Evaluate the quality of the clustering results by assessing the silhouette score comparing it to the K presented within the **Elbow Method**

**Hierarchical Clustering:**

**Distance Metrics:**
- **Euclidean Distance:** Measures the straight-line distance between two points.
- **Chebyshev Distance:** Measures the maximum distance between two points along any coordinate axis.
**Linkage Methods:**
- **Single Linkage:** Merges clusters based on the minimum distance between their closest points.
- **Complete Linkage:** Merges clusters based on the maximum distance between their farthest points.
- **Average Linkage:** Merges clusters based on the average distance between all pairs of points.
- **Centroid Linkage:** Merges clusters based on the distance between their centroids.
- **Ward Linkage:** Merges clusters that minimize the increase in the total within-cluster variance.
- **Weighted Linkage:** Merges clusters based on a weighted average of the distances between all pairs of points.

**Dimensionality Reduction:**

**Principal Component Analysis (PCA):** Reduce the dimensionality of the dataset for visualization and to improve the efficiency of clustering algorithms.

---

## Here's a concise summary of the variables in the dataset:

### Financial Metrics:

- **Current Price:** The current market value of the stock.
- **Price Change:** The percentage change in the stock price over the past 13 weeks.
- **Volatility:** A measure of how much the stock price fluctuates over the past 13 weeks.
- **ROE (Return on Equity):** A profitability ratio measuring how efficiently a company uses its shareholders' investments.
- **Cash Ratio:** A liquidity ratio indicating a company's ability to meet short-term obligations.
- **Net Cash Flow:** The difference between a company's cash inflows and outflows.
- **Net Income:** The company's profit after deducting all expenses.
- **Earnings Per Share (EPS):** The portion of a company's profit allocated to each outstanding share of common stock.
- **Estimated Shares Outstanding:** The total number of shares of a company's stock held by investors.
- **P/E Ratio (Price-to-Earnings Ratio):** A valuation ratio measuring the price investors are willing to pay for each dollar of earnings.
- **P/B Ratio (Price-to-Book Ratio):** A valuation ratio comparing a company's market value to its book value.

### Company Information:

- **Ticker Symbol:** A unique identifier for the stock.
- **Company:** The name of the company.
- **GICS Sector:** The industry sector to which the company belongs.
- **GICS Sub-Industry:** The specific industry group within the sector.

---
## Languages and Utilities used
- Python
- Google Colab 
---
## Environments used
- Windows 11







