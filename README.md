# Customer Segmentation Using K-Means Clustering

## Project Overview

Customer segmentation is a crucial technique for businesses to group their customers based on purchasing behavior and demographics. This project uses K-Means clustering to segment customers from a mall dataset to help businesses tailor marketing strategies, improve customer satisfaction, and boost sales.

---

## Dataset

The dataset contains customer information such as:

- CustomerID
- Gender
- Age
- Annual Income (in thousands of dollars)
- Spending Score (1-100) — a measure of customer spending behavior

Example data snippet:

| CustomerID | Gender | Age | Annual Income (k$) | Spending Score (1-100) | Cluster |
|------------|--------|-----|--------------------|-----------------------|---------|
| 1          | Male   | 19  | 15                 | 39                    | 2       |
| 2          | Male   | 21  | 15                 | 81                    | 2       |
| 3          | Female | 20  | 16                 | 6                     | 3       |
| 4          | Female | 23  | 16                 | 77                    | 2       |
| 5          | Female | 31  | 17                 | 40                    | 2       |

---

## Methodology

- **Preprocessing:** Removed irrelevant columns and scaled features.
- **Clustering:** Applied K-Means clustering algorithm.
- **Optimal clusters:** Determined using the Elbow method (optimal K = 5).
- **Evaluation:** Silhouette Score of 0.417 indicates a reasonable cluster separation.

Cluster distribution:

| Cluster | Number of Customers |
|---------|---------------------|
| 2       | 54                  |
| 0       | 47                  |
| 1       | 40                  |
| 4       | 39                  |
| 3       | 20                  |

---

![Screenshot 2025-05-15 204628](https://github.com/user-attachments/assets/a2be7d65-5e6e-4f1e-a550-9903b0c6893c)

![Screenshot 2025-05-15 204550](https://github.com/user-attachments/assets/0713f355-0e96-462b-8391-bc6d356b019e)


## Business Insights

- **Cluster 2** represents the largest group of customers.
- Clusters can be used to create targeted marketing campaigns:
  - High spenders
  - Budget-conscious shoppers
  - Younger, trend-sensitive customers
- Tailored promotions and personalized offers can improve customer engagement and sales.

---
# This project successfully segmented mall customers using K-Means clustering, providing actionable insights that businesses can use to improve marketing and sales strategies. The silhouette score indicates meaningful clusters, and the visualizations confirm distinct customer groups.
