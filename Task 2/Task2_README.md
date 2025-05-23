# Customer Segmentation Using K-Means

## Problem Statement

The goal of this project is to segment customers into distinct groups based on their purchasing behavior using the K-Means clustering algorithm. This helps businesses understand customer traits and tailor marketing strategies, product offerings, and engagement methods accordingly.

---

## Steps Followed

1. **Data Loading & Exploration**
   - Loaded the dataset from Kaggle.
   - Explored data types, null values, and statistical summaries.

2. **Data Preprocessing**
   - Removed irrelevant columns like `CustomerID`.
   - Checked and handled missing values (none found).
   - Scaled features using `StandardScaler` for better clustering performance.

3. **Finding Optimal Number of Clusters**
   - Used the **Elbow Method** to determine the optimal value of `k`.
   - Plotted WCSS (Within-Cluster Sum of Squares) for values from 1 to 10.

4. **Applying K-Means Clustering**
   - Trained the K-Means model with optimal `k` (e.g., 5).
   - Predicted cluster labels for all customers.

5. **Cluster Visualization**
   - Visualized the clusters using scatter plots.
   - Plotted centroids for each cluster.

6. **Cluster Analysis**
   - Interpreted each cluster based on features such as `Age`, `Annual Income`, and `Spending Score`.

---

## Key Results

- The **Elbow Method** identified the optimal number of clusters as **k = 5**.
- Clusters formed:
  - Cluster 1: High income, high spending
  - Cluster 2: Low income, low spending
  - Cluster 3: Young, high spending
  - Cluster 4: Moderate income and spending
  - Cluster 5: Older, low spending

---

## Business Interpretation

- **Cluster 1:** Premium customers – Target with exclusive offers.
- **Cluster 2:** Budget-conscious – Provide value bundles and discounts.
- **Cluster 3:** Young & high spenders – Engage with aspirational branding.
- **Cluster 4:** Moderate shoppers – Retain with loyalty rewards.
- **Cluster 5:** Older customers – Focus on trust and convenience.

These insights enable businesses to tailor personalized marketing strategies for each customer segment.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## Dataset

Kaggle: [Customer Segmentation Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

---

## How to Run

1. Clone this repository.
2. Navigate to the `Task2_Customer_Segmentation` folder.
3. Open `Customer_Segmentation.ipynb` in Jupyter Notebook or Google Colab.
4. Run all cells to see results and visualizations.





