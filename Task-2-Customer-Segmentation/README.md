
# SkillCraft Technology - Machine Learning Internship

## Task 2: Customer Segmentation Using K-Means Clustering

## 📌 Project Overview

This project focuses on customer segmentation using the K-Means Clustering algorithm, an unsupervised machine learning technique.

The objective is to group customers into different segments based on their annual income and spending score. Customer segmentation helps businesses understand customer behavior and develop better marketing strategies.

This project was completed as part of the SkillCraft Technology Machine Learning Internship.

## 🎯 Objectives

- Understand customer segmentation using machine learning.
- Explore and analyze customer data.
- Apply the K-Means Clustering algorithm.
- Use the Elbow Method to help select the number of clusters.
- Visualize customer groups using scatter plots.
- Interpret the resulting customer segments for business applications.

## 📂 Dataset

**Dataset name:** Mall Customers Dataset

The dataset commonly contains information about customers, including:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

The analysis uses the following features:

- **Annual Income (k$):** The customer's annual income in thousands of dollars.
- **Spending Score (1-100):** A score representing the customer's spending behavior.

**Dataset source:** Mall Customers dataset, commonly available through Kaggle.

If you use a different source, update this section with the actual dataset link.

## 🛠️ Technologies Used

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🧠 Algorithm Used

### K-Means Clustering

K-Means is an unsupervised machine learning algorithm that divides data points into a specified number of clusters.

The algorithm works by:

1. Selecting the number of clusters, K.
2. Initializing cluster centroids.
3. Assigning each customer to the nearest centroid.
4. Updating the centroids based on the assigned customers.
5. Repeating the assignment and update process until the clusters stabilize.

### Elbow Method

The Elbow Method helps identify a suitable number of clusters.

It plots the number of clusters against the Within-Cluster Sum of Squares (WCSS), also called inertia in scikit-learn.

The point where the reduction in WCSS begins to slow down is considered a possible choice for K.

## ⚙️ Project Workflow

1. Import the required Python libraries.
2. Load the Mall Customers dataset.
3. Inspect the dataset and check for missing values.
4. Explore the customer data using descriptive statistics.
5. Select Annual Income and Spending Score as clustering features.
6. Apply the Elbow Method to help choose K.
7. Train the K-Means clustering model.
8. Assign cluster labels to customers.
9. Visualize the customer segments.
10. Interpret the clusters and summarize the findings.

## 📊 Visualization

The project includes the following visualizations:

### 1. Elbow Method Plot

This graph shows how the inertia changes as the number of clusters increases. It helps identify a reasonable number of clusters for the model.

### 2. Customer Segmentation Plot

A scatter plot displays customers according to annual income and spending score. Different colors represent different clusters.

These visualizations help reveal customer groups with similar income and spending patterns.

## 📈 Results and Analysis

The K-Means model groups customers according to similarities in annual income and spending score.

The resulting clusters can help identify patterns such as:

- Customers with high income and high spending scores.
- Customers with high income and low spending scores.
- Customers with lower income and high spending scores.
- Customers with lower income and low spending scores.
- Customers with moderate income and spending scores.

**Note:** These are possible interpretations, not guaranteed results. Describe your actual clusters based on the cluster visualization and summary produced by your notebook. Cluster numbers themselves do not have a fixed meaning.

## 💼 Business Applications

Customer segmentation can help businesses:

- Develop targeted marketing campaigns.
- Identify high-value customer groups.
- Improve customer engagement.
- Design personalized offers and promotions.
- Understand customer purchasing behavior.
- Support data-driven business decisions.

## 📁 Project Structure

```text
SkillCraft-ML-Internship/
│
├── Task-1-House-Price-Prediction/
│
└── Task-2-Customer-Segmentation/
    ├── SCT_ML_Task2.ipynb
    ├── Mall_Customers.csv
    ├── customer_segments.csv
    ├── README.md
    │
    └── images/
        ├── elbow_method.png
        └── customer_clusters.png
```

This structure is a suggested layout. Include only the files you have actually created. If the dataset cannot be redistributed, omit it and document its source instead.

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Open `SCT_ML_Task2.ipynb` using Google Colab or Jupyter Notebook.
3. Upload or load the Mall Customers dataset.
4. Install any missing dependencies if necessary.
5. Run the notebook cells in order.
6. Review the Elbow Method plot and customer segmentation visualization.
7. Examine the generated cluster assignments and analysis.

## 📚 Key Learnings

- Understanding unsupervised machine learning.
- Applying K-Means clustering to customer data.
- Selecting features for clustering.
- Using the Elbow Method to help select K.
- Visualizing and interpreting customer segments.
- Understanding how machine learning can support business decisions.

## 🔮 Future Improvements

- Compare K-Means with other clustering algorithms.
- Scale features and evaluate how scaling affects the clusters.
- Use additional customer features where appropriate.
- Evaluate clustering quality using the Silhouette Score.
- Develop more detailed customer profiles and marketing recommendations.

## ✅ Conclusion

This project demonstrates how K-Means Clustering can be used to segment customers based on annual income and spending score.

The analysis provides a practical introduction to unsupervised machine learning, data visualization, and customer behavior analysis.

Customer segmentation can help businesses understand their audiences and make more informed marketing decisions.

## 👩‍💻 Internship

**Organization:** SkillCraft Technology  
**Program:** Machine Learning Internship  
**Task:** Task 2 — Customer Segmentation Using K-Means Clustering

---

*This project was created for educational and internship purposes.*