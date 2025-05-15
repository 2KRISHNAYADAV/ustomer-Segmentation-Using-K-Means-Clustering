# Customer Segmentation Using K-Means Clustering

This project performs customer segmentation using **K-Means Clustering**, a powerful unsupervised machine learning technique. By analyzing customer purchasing behavior, the model segments customers into distinct groups based on features such as age, income, and spending score.

## 📌 Objective

To segment customers into clusters that can help businesses:
- Personalize marketing strategies
- Improve customer satisfaction
- Increase sales by targeting the right customers

## 📊 Dataset

- **Source**: [Kaggle - Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial)
- **Features**:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1–100)`

## 🧪 Methodology

- **Preprocessing**: Cleaned and visualized the data using `Seaborn` and `Matplotlib`
- **Algorithm Used**: K-Means Clustering
- **Evaluation**:
  - **Elbow Method** to determine optimal clusters (K=5)
  - **Silhouette Score**: `0.417` indicates moderate cluster separation
- **Tools**: Python, Pandas, Seaborn, Scikit-learn, Jupyter Notebook

## 📈 Visualizations

- KDE plots to compare distributions of Age, Income, and Spending Score across genders
- Scatter plot of customer clusters in 2D space
- Elbow curve to select optimal K

## 📦 Output
---



Example data snippet:

| CustomerID | Gender | Age | Annual Income (k$) | Spending Score (1-100) | Cluster |
|------------|--------|-----|--------------------|-----------------------|---------|
| 1          | Male   | 19  | 15                 | 39                    | 2       |
| 2          | Male   | 21  | 15                 | 81                    | 2       |
| 3          | Female | 20  | 16                 | 6                     | 3       |
| 4          | Female | 23  | 16                 | 77                    | 2       |
| 5          | Female | 31  | 17                 | 40                    | 2       |

---
- 5 customer segments were identified:
  - Cluster 2: 54 customers
  - Cluster 0: 47 customers
  - Cluster 1: 40 customers
  - Cluster 4: 39 customers
  - Cluster 3: 20 customers

---
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

    


## 📘 Conclusion

This project shows how K-Means clustering can provide meaningful business insights through data segmentation. With a Silhouette Score of `0.417`, the segmentation is effective and usable for strategic decision-making.

## 🔗 Project Link

🧪 View the full notebook on Kaggle:  
[Customer Segmentation on Kaggle](https://www.kaggle.com/code/krishnayadav456wrsty/customer-segmentation-using-k-means-clustering)

## 💻 Author

- **Name**: Krishna Yadav
- **GitHub**: [@krishnayadav456wrsty](https://github.com/krishnayadav456wrsty)
- **Kaggle**: [Kaggle Profile](https://www.kaggle.com/krishnayadav456wrsty)

---


![Screenshot 2025-05-15 204628](https://github.com/user-attachments/assets/a2be7d65-5e6e-4f1e-a550-9903b0c6893c)

![Screenshot 2025-05-15 204550](https://github.com/user-attachments/assets/0713f355-0e96-462b-8391-bc6d356b019e)

---

## Business Insights

- **Cluster 2** represents the largest group of customers.
- Clusters can be used to create targeted marketing campaigns:
  - High spenders
  - Budget-conscious shoppers
  - Younger, trend-sensitive customers
- Tailored promotions and personalized offers can improve customer engagement and sales.

---
# This project successfully segmented mall customers using K-Means clustering, providing actionable insights that businesses can use to improve marketing and sales strategies. The silhouette score indicates meaningful clusters, and the visualizations confirm distinct customer groups.



