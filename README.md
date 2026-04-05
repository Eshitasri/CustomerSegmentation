# Mall Customer Segmentation
**Project Overview**

This project performs customer segmentation for a mall using K-Means clustering. The goal is to group customers based on their Annual Income and Spending Score to enable targeted marketing strategies. Age and Gender are used for profiling clusters without affecting the segmentation.

**Dataset**
Source: Mall Customers Dataset
Columns:
CustomerID – Unique identifier
Gender – Male/Female
Age – Customer age
Annual Income (k$) – Annual income in thousands
Spending Score (1-100) – Spending behavior

**Preprocessing:**
Gender encoded (Male = 0, Female = 1)
No missing values

**Methodology**
Exploratory Data Analysis (EDA): Visualized relationships between features.
Feature Selection: Chose Annual Income and Spending Score for clustering.
Clustering: Applied K-Means to segment customers into 5 clusters.
Centroid Visualization: Labeled centroids plotted for clear cluster interpretation.
Cluster Profiling: Calculated average income, spending, age, gender distribution, and cluster size.
Business Insights: Assigned actionable marketing strategies to each cluster.

**Clusters & Insights**
Cluster	Avg Income	Avg Spending	Avg Age	Gender (F/M)	Count	Business Action
VIP	86.5k	82.1	32.7	21 / 18	39	Focus on premium offers
Potential	88.2k	17.1	41.1	16 / 19	35	Targeted campaigns to increase spending
Impulse Buyers	25.7k	79.4	25.3	13 / 9	22	Trendy promotions for young buyers
Average	55.3k	49.5	42.7	48 / 33	81	General campaigns
Budget	26.3k	20.9	45.2	14 / 9	23	Discounts/value deals

**Key Takeaways**
Customers cluster naturally based on income and spending behavior.
Age and Gender help profile the clusters without affecting segmentation.
Each cluster can be targeted with specific marketing strategies, making the segmentation actionable and valuable for business.

**Tools & Libraries**
Python 3.x
Pandas, NumPy
Matplotlib, Seaborn
scikit-learn (StandardScaler, KMeans)
