# K-Means Clustering

This project demonstrates the use of **K-Means Clustering**, an unsupervised machine learning algorithm, to segment customers based on their spending habits and income levels.  
The dataset used is the **Mall Customers** dataset, containing demographic and spending-related data for mall visitors.

## 📌 Project Overview

The main objectives of this project are:
- To apply K-Means clustering on customer data.
- To determine the optimal number of clusters using the **Elbow Method**.
- To visualize the customer segments for better understanding and business insights.

## 📂 Dataset

**File:** `Mall_Customers.csv`  
**Columns:**
- `CustomerID` – Unique customer identifier.
- `Gender` – Gender of the customer.
- `Age` – Age in years.
- `Annual Income (k$)` – Annual income in thousands of dollars.
- `Spending Score (1-100)` – Score assigned based on customer behavior and spending patterns.

## ⚙️ Requirements

Install the dependencies before running the notebook:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/k_means_clustering.git
   cd k_means_clustering
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook k_means_clustering.ipynb
   ```
3. Run all cells to:
   - Load the dataset.
   - Apply the Elbow Method to find the optimal cluster count.
   - Perform K-Means clustering.
   - Visualize the clusters.

## 📊 Methodology

1. **Data Import & Exploration**
   - Load the dataset and check for missing values.
   - Select relevant features for clustering.
2. **Optimal Cluster Selection**
   - Apply the **Elbow Method** to determine the best value of `k`.
3. **Model Training**
   - Train the K-Means model with the chosen `k`.
4. **Visualization**
   - Use Matplotlib to plot clusters and centroids.

## 📈 Results

The customers are segmented into clusters such as:
- High income & high spending
- High income & low spending
- Low income & high spending
- Low income & low spending
- Average income & spending

These insights can help in:
- Targeted marketing campaigns.
- Customer relationship management.
- Optimizing product offerings.

## 🖼 Sample Output

**Elbow Method to determine optimal clusters**  
<img width="750" height="557" alt="image" src="https://github.com/user-attachments/assets/54ba1638-ecf2-465b-880d-4f3716f0f563" />


**Customer Segments Visualization**  
<img width="722" height="557" alt="image" src="https://github.com/user-attachments/assets/003f9dd0-376b-4128-9731-70ce20a820f8" />


