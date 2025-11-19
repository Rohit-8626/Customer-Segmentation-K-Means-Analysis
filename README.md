Customer Segmentation using K-Means & PCA
Mall Customer Analysis for Targeted Marketing & Revenue Optimization
📌 Project Overview

This project implements Unsupervised Machine Learning techniques to group mall customers into distinct segments based on their Age, Annual Income, and Spending Score.
The goal is to enable targeted marketing, customer-specific strategies, and improved revenue growth.

🎯 Business Problem

Most shopping malls and retail chains spend money on generic marketing campaigns without understanding differences between customer types.
This results in:

Low conversion rates

Wasted advertising budget

Poor customer engagement

Customer Segmentation helps businesses:

Personalize offers

Identify profitable customers

Improve sales strategy and ROI

🧠 Approach
Step	Description
Exploratory Data Analysis	Data cleaning, distributions, feature relationships
Encoding + Scaling	Convert categorical values and standardize numerics
PCA	Reduce dimensions & improve cluster separation
K-Means Clustering	Build customer segments
Elbow + Silhouette	Validate optimal number of clusters
Insights	Create customer personas + business recommendations
📂 Dataset

Mall Customers Dataset

Features used:

Gender

Age

Annual Income (in USD)

Spending Score (1–100 scale)

📊 Model Validation
Metric	Result
Elbow Method	Optimal K = 5
Silhouette Score	0.61 (indicates well-separated clusters)
🪄 Key Visualizations
Elbow Method Curve

(Insert elbow_curve.png here)

Final Clusters (PCA 2-D View)

(Insert cluster_scatter.png here)

🔍 Segment Insights & Marketing Strategy
Cluster	Characteristics	Strategy
Cluster A	Young (18–30), Low Income, High Spending Score	Social media campaigns, discounts, fashion + food offers
Cluster B	Mid-age (25–35), High Income, High Spending Score	VIP memberships, exclusive events, premium brands
Cluster C	Older (40–50), High Income, Low Spending	Personalized family offers, bundle discounts
Cluster D	Mixed age, Avg Income, Moderate spending	Cashback programs, targeted loyalty rewards
Cluster E	Older (45–60), Low Income, Low Spending	Low-cost products, budget offers, avoid aggressive marketing
🚀 Conclusion

Clustering revealed five meaningful customer groups.

Businesses can now target customers more effectively, improving ROI.

ML-based segmentation is significantly better than manual assumptions.

🛠 Tech Stack

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn, Plotly

Jupyter Notebook

💻 How to Run
git clone https://github.com/Rohit-8626/Customer-Segmentation-K-Means-Analysis.git
cd Customer-Segmentation-K-Means-Analysis
pip install -r requirements.txt
jupyter notebook Customer_Segmentation_KMeans_PCA.ipynb

📦 Future Improvements

Compare DBSCAN / GMM / Hierarchical Clustering

Deploy clustering as an interactive Streamlit dashboard

Add predictive modeling for customer churn / lifetime value

👤 Author

Rohit Vastani
AI & ML Student | Data Science Enthusiast
📍 India

## Profile

🔗 LinkedIn: (https://www.linkedin.com/in/rohit-vastani-3a9a18301?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
🔗 GitHub: (https://github.com/Rohit-8626)

⭐ If you like this project, give the repo a star!


## Visualizations

### Elbow Curve
![Elbow Curve](/elbow_curve.png)

### Final Customer Clusters
![Customer Segments](/cluster_scatter.png)

## How to Run

```bash
git clone https://github.com/Rohit-8626/Customer-Segmentation-K-Means-Analysis.git
cd Customer-Segmentation-K-Means-Analysis
pip install -r requirements.txt
jupyter notebook Customer_Segmentation_KMeans_PCA.ipynb
