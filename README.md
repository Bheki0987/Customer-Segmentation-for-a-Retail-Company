# 📦 Customer Segmentation for a Retail Company

## 👋 Overview
This project leverages real-world e-commerce transaction data to segment customers using **RFM analysis** (Recency, Frequency, and Monetary value). By grouping customers into meaningful clusters, we gain **actionable insights** to drive **data-driven marketing**, **customer retention**, and **loyalty strategies**.

---

## 🔍 Project Goal
Understand customer behavior to **personalize engagement strategies** and **optimize business decisions**.

---

## 📁 Dataset
- **Source:** [Kaggle - E-Commerce Data](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

---

## 🧠 RFM Analysis Summary

| Metric     | Description                               |
|------------|-------------------------------------------|
| **Recency** | Days since the customer’s last purchase   |
| **Frequency** | Total number of purchases                 |
| **Monetary** | Total amount spent                        |

---

## 📊 Clustering Results

Customers were segmented into **4 clusters** using **K-Means Clustering**:

| Cluster | Segment Description                | Suggested Action                             | Emoji |
|---------|------------------------------------|----------------------------------------------|-------|
| **2**   | High-spending loyal customers       | Launch VIP rewards or early-access deals     | 🟢    |
| **1**   | Recent but inactive customers       | Nurture via welcome or promo campaigns       | 🟠    |
| **0**   | Moderate and consistent buyers      | Upsell or cross-sell personalized offers     | 🔵    |
| **3**   | One-time or disengaged buyers       | Re-engagement offers and feedback surveys    | 🔴    |

---

## 📷 Key Visualizations

Explore the interactive Tableau dashboard here:  
🔗 [View on Tableau Public](https://public.tableau.com/views/RetailCustomerRFMSegmentVisualization/CustomerSegmentDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

### Dashboard Features:
- 📊 Bar chart of average spend by segment  
- 🔍 Scatter plot of Recency vs Frequency  
- 🥧 Pie chart of segment distribution  
- 💡 Business-friendly insights and actions  

---

## 🛠 Tech Stack

| Tool | Purpose |
|------|---------|
| **Python (Pandas, Seaborn)** | Data cleaning, EDA, clustering |
| **Scikit-learn** | KMeans clustering |
| **Tableau Public** | Interactive dashboard |
| **GitHub** | Documentation & code hosting |

---

## 🚀 How to Reproduce

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Bheki0987/Customer-Segmentation-for-a-Retail-Company.git

2. **Install dependancies:**
   ```bash
   pip install pandas matplotlib seaborn scikit-learn

3. **Run the jupyter notebook:**
   - Open and run rfm_segmentation.ipynb

3. **Visualize in Tableau:**
   - Upload the exported file rfm_segmented_for_tableau.csv to Tableau Public to recreate the interactive dashboard.


## ✨Credits
- Dataset: Kaggle / UCI Machine Learning Repository
- Developed by: Bheki Mogola, Aspiring Data Analyst & Web Developer

## 📬 Contact
- 📧 Email: bpmogola@gmail.com
- 🔗 LinkedIn: Bheki Mogola
