# Customer Mall Segmentation (K-Means Clustering)

This project applies K-Means Clustering to segment customers of a mall based on their purchasing behavior and annual income.

## 📌 Project Overview

Customer segmentation helps malls and retail businesses to target their customers based on their purchasing capacity and spending patterns. In this project, we:

- Visualize customer data
- Use the Elbow Method to find the optimal number of clusters
- Apply K-Means Clustering
- Visualize the resulting customer segments

## 📝 Dataset

The dataset contains the following features:
- **CustomerID:** Unique ID assigned to each customer
- **Gender:** Gender of the customer
- **Age:** Age of the customer
- **Annual Income (k$):** Annual income in thousand dollars
- **Spending Score (1-100):** Score assigned by the mall based on customer spending behavior

Dataset Source: (Provide your dataset source here, e.g. [Kaggle](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python))

## 📊 Steps Performed

1. **Data Loading & Exploration**
2. **Data Visualization:**
   - Age Distribution
   - Annual Income Distribution
   - Spending Score Distribution
3. **Elbow Method:**
   - Determine optimal number of clusters based on Within-Cluster Sum of Squares (WCSS)
4. **K-Means Clustering:**
   - Apply clustering with optimal number of clusters
5. **Visualization of Clusters:**
   - Scatter plots showing the clusters

## 📌 Key Libraries Used:
- **Pandas:** Data manipulation
- **Matplotlib & Seaborn:** Visualization
- **Scikit-learn:** K-Means Clustering

## ⚙️ How to Run:
1. Clone this repository:
```bash
git clone https://github.com/yourusername/customer-mall-segmentation.git
Install dependencies:

pip install pandas matplotlib seaborn scikit-learn
Run the Jupyter Notebook or Python script:

jupyter notebook
Follow the notebook to explore customer segmentation.

💡 Results:
Identified distinct customer segments based on spending score and income.

Visualized clusters for better understanding of customer behavior.

📈 Visualizations:
Histograms for Age, Annual Income, and Spending Score

Elbow Curve to determine optimal clusters

Scatter plots to display segmented clusters

📬 Contact:
For any queries or feedback, feel free to reach out:

Email: kishorekannann82@gmail.com
