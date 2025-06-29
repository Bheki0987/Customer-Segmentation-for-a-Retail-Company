📦 Customer Segmentation for a Retail Company

👋 Overview:
This project uses real-world e-commerce transaction data to segment customers using RFM analysis (Recency, Frequency, and Monetary value). By grouping customers into meaningful clusters, we gain actionable insights to support data-driven marketing, retention, and loyalty strategies.
🔍 Goal: Understand customer behavior to personalize engagement strategies.
📊 Tech Stack: Python, Pandas, Scikit-learn, Seaborn, Tableau Public
📁 Dataset Source: https://www.kaggle.com/datasets/carrie1/ecommerce-data


🧠 RFM Analysis Summary:	              
Recency: Days since the customer’s last purchase
Frequency: Total number of purchases
Monetary: Total amount spent


📊 Clustering Results
Customers were grouped using K-Means clustering into 4 segments:

Cluster	     Description	                     Suggested Action
2 (🟢)	     High-spending loyal customers	   Launch VIP rewards or early-access deals
1 (🟠)	     Recent but inactive customers	   Nurture via welcome or promo campaigns
0 (🔵)	     Moderate and consistent buyers	   Upsell or cross-sell personalized offers
3 (🔴)	     One-time or disengaged buyers	   Re-engagement offers and surveys


📷 Key Visualizations
Access the interactive dashboard on Tableau Public:
🔗 https://public.tableau.com/views/RetailCustomerRFMSegmentVisualization/CustomerSegmentDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Dashboard Includes:
-Bar chart of average spend by segment
-Scatter plot of recency vs frequency
-Pie chart of segment distribution
-Business-friendly insights and recommendations

🛠 Tools Used
Tool	                    Purpose
Python (Pandas, Seaborn)	Data cleaning, EDA, clustering
Scikit-learn	            KMeans clustering
Tableau Public	          Interactive dashboard and story
GitHub	                  Project documentation and sharing


🚀 How to Reproduce
Clone the repo:
git clone https://github.com/Bheki0987/Customer-Segmentation-for-a-Retail-Company.git

Install dependencies:
pip install pandas matplotlib seaborn scikit-learn

Run the Jupyter Notebook:
-rfm_segmentation.ipynb

Upload the rfm_segmented_for_tableau.csv to Tableau Public to recreate the dashboard.


✨ Credits
Dataset: UCI Machine Learning Repository / Kaggle
Developed by: Bheki Mogola, Aspiring Data Analyst & Software Developer

📬 Contact
📧 Email: bhekimogola123@gmail.com
🔗 LinkedIn: Bheki Mogola
