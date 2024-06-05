# Mall-Customer-Segmentation
The dataset, typically referred to as "Mall Customers" dataset, contains information about customers who visited a mall. This dataset is often used for clustering and segmentation analysis in marketing.
#Observations from the Plots
1. Elbow Method Graph
Optimal Clusters: The "elbow" is noticeable around 3 to 5 clusters, indicating these as the optimal number of clusters for segmentation.
Diminishing Returns: Beyond 5 clusters, the decrease in WCSS is marginal, suggesting that increasing the number of clusters further does not significantly improve clustering quality.
Cluster Efficiency: Using too few clusters (e.g., 1 or 2) results in high WCSS, indicating poor clustering.
2. Customer Segmentation Scatter Plot
Distinct Clusters: The scatter plot shows clear, distinct clusters based on annual income and spending score, helping to visualize customer segments.
High Spend/High Income: One cluster represents customers with high income and high spending scores, indicating affluent, high-spending customers.
Varied Spending Behavior: There are clusters with high income but low spending, and low income but high spending, highlighting diverse spending behaviors irrespective of income levels.
3. Pairplot
Age vs. Annual Income: There is no strong linear relationship between age and annual income, with customers of various ages having a wide range of incomes.
Annual Income vs. Spending Score: The pairplot shows diverse spending patterns across different income levels, indicating that high income does not always equate to high spending.
Cluster Distribution: Clusters are well separated in the pairplot, showing distinct customer segments based on the combination of age, income, and spending score.
