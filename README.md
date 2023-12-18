# Customer Segmentation Analysis

## Overview

In this section, we performed customer segmentation analysis using the K-means clustering algorithm on a dataset containing information about customers, specifically their 'Age' and 'Spending Score (1-100)'. The goal was to identify patterns and groups within the customer base to gain insights into their spending behaviors.

## Feature Selection

Initially, we considered two features for the analysis: 'Annual Income (k$)' and 'Spending Score (1-100)'. The Elbow Method was employed to determine the optimal number of clusters for the K-means algorithm. The resulting clusters provided distinct groups of customers based on their income and spending behavior.

### Clustering Analysis (Income and Spending Score)

#### Cluster 0 (Medium Income, Medium Spending Score):

This group likely represents a segment of the population with moderate income levels who spend proportionally on goods and services. They may strike a balance between saving and spending on non-essential items.

#### Cluster 1 (High Income, High Spending Score):

Customers in this cluster have high disposable incomes and are comfortable spending on both essential and luxury items. They may have a higher affinity for shopping and indulging in non-essential purchases.

#### Cluster 2 (Low Income, High Spending Score):

This cluster suggests that despite having a low income, customers exhibit a high spending score. Possible reasons include the use of credit or impulsive buying behaviors.

#### Cluster 3 (High Income, Low Spending Score):

Customers in this cluster may be conservative in their spending habits despite having a high income. Possible reasons could include a focus on saving, investment, or a lack of interest in discretionary purchases.

#### Cluster 4 (Low Income, Low Spending Score):

Customers in this cluster may have limited financial resources, leading to a lower spending score. They might prioritize essential expenses and be more cautious about discretionary spending.

### Clustering Analysis (Age and Spending Score)

We further explored customer segmentation using the features 'Age' and 'Spending Score (1-100)'. The Elbow Method was applied to determine the optimal number of clusters for this analysis.

#### Cluster 1 (Age 20-40, High Spending Score):

Customers in this age group exhibit a high spending score, possibly due to higher disposable income, lifestyle choices, and social influences.

#### Cluster 0 (Age 42-70, Medium Spending Score):

This cluster represents individuals with a more stable financial situation, a balanced approach to spending, and potential family responsibilities.

#### Variability in Spending Score (Age 20-70):

The variability observed in spending scores across different age groups can be attributed to diverse preferences, life stage considerations, and economic factors.

## Conclusion

The customer segmentation analysis provides valuable insights into distinct customer groups based on income, age, and spending behavior. These insights can inform targeted marketing strategies, personalized customer experiences, and product/service offerings.
