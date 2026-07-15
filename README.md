# 🛍️ Customer Segmentation using K-Means Clustering

**Internship Project — CodTech IT Solutions (AI/ML Internship)**

## 📌 Overview
This project applies **unsupervised machine learning (K-Means Clustering)** to segment mall customers into distinct groups based on their **Age**, **Annual Income**, and **Spending Score**. Customer segmentation is a core technique used in retail/marketing to understand customer behavior and design targeted campaigns.

## 🎯 Objective
- Explore and visualize customer data
- Determine the optimal number of clusters using the **Elbow Method** and **Silhouette Score**
- Apply **K-Means Clustering** to group customers
- Profile and label each segment with actionable business insights

## 📂 Dataset
`Mall_Customers.csv` contains 200 customer records with the following columns:

| Column | Description |
|---|---|
| CustomerID | Unique customer identifier |
| Gender | Male / Female |
| Age | Customer's age |
| Annual_Income_k$ | Annual income in thousand $ |
| Spending_Score | Score (1-100) assigned based on spending behavior |

## 🛠️ Tech Stack
- Python 3
- Pandas, NumPy — data handling
- Matplotlib, Seaborn — visualization
- Scikit-learn — K-Means clustering, preprocessing, silhouette score

## 📊 Project Workflow
1. **Data Loading & EDA** — inspect data, check distributions, visualize relationships
2. **Preprocessing** — encode categorical features, scale numeric features
3. **Optimal k Selection** — Elbow Method + Silhouette Score
4. **K-Means Clustering** — group customers into 5 segments
5. **Cluster Visualization** — scatter plot of segments with centroids
6. **Cluster Profiling** — label each segment (e.g. "High Income - High Spenders")
7. **Business Insights** — marketing recommendations per segment

## 🧩 Customer Segments Identified
| Segment | Description |
|---|---|
| High Income - High Spenders | Prime target customers for premium offers |
| Young Budget Spenders | Lower income, high spending — trendy/affordable products |
| High Income - Cautious Spenders | Earn more, spend less — upsell opportunity |
| Low Income - Low Spenders | Least profitable — minimal marketing spend |
| Average Customers | Balanced group — general marketing |

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook Customer_Segmentation.ipynb
```

## 📁 Repository Structure
```
customer-segmentation/
├── Customer_Segmentation.ipynb   # Main notebook with full analysis
├── Mall_Customers.csv            # Dataset
├── requirements.txt              # Dependencies
└── README.md                     # Project documentation
```

## 📈 Sample Output
The notebook includes the Elbow curve, silhouette score plot, and a labeled scatter plot showing all 5 customer clusters with their centroids.

## ✍️ Author
AI/ML Intern, CodTech IT Solutions
InternID: CITS5467
