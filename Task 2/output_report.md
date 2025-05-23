# Customer Segmentation Using K-Means

This report summarizes the steps, results, plots, and findings of the Customer Segmentation task using K-Means clustering.

## 1. Model Results
- **Dataset**: Mall Customer Segmentation Data (Kaggle)
- **Preprocessing**:
  - Removed `CustomerID` column
  - Scaled features using `StandardScaler`
- **Clustering Method**: K-Means
- **Optimal Number of Clusters**: k = 5 (determined using Elbow Method)
- **Resulting Clusters**:
  - Cluster 1: High income, high spending
  - Cluster 2: Low income, low spending
  - Cluster 3: Young, high spending
  - Cluster 4: Moderate income and spending
  - Cluster 5: Older, low spending

## 2. Plots
- Elbow Method plot (to determine optimal k)
- Cluster visualization (Annual Income vs. Spending Score)
- Scatter plots showing cluster separation

## 3. Findings
- Clear segmentation of customers based on income and spending score.
- Each cluster represents a distinct behavioral segment.
- Business interpretation provided for each group to aid marketing strategies.

## 4. Live Demo / Notebook Access
You can explore and run the project notebook here:

📓 **Google Colab**: [Open Notebook](https://colab.research.google.com/drive/YOUR_NOTEBOOK_LINK_HERE)

🗂️ **GitHub Repository**: [View Project](https://github.com/YOUR_USERNAME/Credora-Internship/tree/main/Task2_Customer_Segmentation)

*Replace the above placeholders with actual links before submission.*

