📌 Customer Segmentation using K-Means & PCA
Mall Customer Analysis for Targeted Marketing & Revenue Optimization
📍 Project Overview

This project applies Unsupervised Machine Learning techniques to segment mall customers into distinct groups based on their Annual Income, Spending Score, and Age.
The goal is to enable personalized marketing strategies, better customer engagement, and improved business decision-making.

🎯 Business Problem

Shopping malls often spend money on generic marketing campaigns without understanding customer differences.
This leads to wasted marketing budget and low conversion rates.
By identifying unique customer groups, businesses can:

Target the right customers with the right promotions

Improve customer retention & engagement

Maximize revenue through segmentation-driven strategy

🧠 Approach
Step	Description
Data Exploration	Dataset structure, missing values, distribution analysis
Feature Engineering	Gender encoding, standardization
Dimensionality Reduction	PCA to reduce variance noise & improve cluster separation
Clustering	K-Means clustering + Elbow method + Silhouette Score
Visualization	PCA 2-D scatter plot of clusters
Business Insights	Interpretation of cluster behavior & marketing recommendations
📂 Dataset

Mall Customers Dataset

Features used:

Age

Gender

Annual Income ($)

Spending Score (1–100)

📊 Model Evaluation
Method	Result
Elbow Method	Optimal K = 5
Silhouette Score	0.61 (indicates well-separated clusters)
🔍 Cluster Summary & Business Insights
Cluster	Characteristics	Business Strategy
Cluster 1	25–35 yrs, High Income, High Spending	Premium loyalty programs, exclusive offers
Cluster 2	40–50 yrs, High Income, Low Spending	Discounts, bundle offers to boost engagement
Cluster 3	18–27 yrs, Low Income, High Spending	Youth marketing, combo deals, social media ads
Cluster 4	30–45 yrs, Average income, Moderate spending	Cashback & affordable product promotions
Cluster 5	45–60 yrs, Low income & low spending	Price-sensitive campaigns & essential categories
📉 Visualizations

Distribution Plots for Age, Income, Spending Score

Correlation Heatmap

PCA Cluster Scatter Plot

Elbow Method Curve

(Insert images here after exporting plots)

🚀 Key Takeaways

ML-based segmentation enables better customer targeting

PCA + K-Means is effective for multi-feature segmentation

Strong clusters prove real business value, not just accuracy scores

🛠 Tech Stack

Python, Pandas, NumPy

Scikit-learn

Matplotlib / Seaborn / Plotly

PCA, K-Means Clustering

📦 Future Improvements

Use DBSCAN or Gaussian Mixture Models for comparison

Build automated dashboard in Streamlit

Integrate marketing ROI prediction model

👤 Author

Rohit Vastani
AI/ML Student | Data Science & NLP Enthusiast
📍 India | Open for Internships
LinkedIn: (link here)
GitHub: (link here)

⭐ Support

If you find this interesting, consider giving the GitHub repo a ⭐
