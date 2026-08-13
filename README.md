# retail-customer-segmentation
# 🛒 Retail Customer Segmentation for Nigerian Businesses (3MTT Capstone)

## 📌 Project Overview
In Nigeria, many small-to-medium retail and POS businesses treat all customers equally, using one-size-fits-all marketing strategies. This project uses machine learning to solve this over-generalization problem by segmenting customers based on their purchasing behaviors using transaction data.

By implementing an **RFM (Recency, Frequency, Monetary)** model and **K-Means Clustering**, this solution allows local retailers to identify high-value buyers, retain at-risk customers, and drive targeted promotions.

---

## 🎯 MVP Features
* **Data Processing & Cleaning:** Handles missing values, handles transaction logs, and filters invalid records.
* **RFM Feature Engineering:** Converts transaction history into actionable metrics:
  * **Recency ($R$):** Days since last transaction.
  * **Frequency ($F$):** Total purchase count.
  * **Monetary ($M$):** Total spent in Naira ($\text{NGN}$).
* **K-Means Clustering:** Groups customers into distinct, non-overlapping segments.
* **Model Evaluation:** Silhouette Score and Calinski-Harabasz Index used to validate optimal cluster counts.
* **Customer Persona Profiling:** Maps raw clusters to real-world business actions.

---

## 🛠️ Tech Stack & Tools
* **Language:** Python 3.x
* **Libraries:** `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`
* **Environment:** Jupyter Notebook / Google Colab

---

## 📊 Key Results & Evaluation Metrics
* **Optimal Clusters ($K$):** 3
* **Silhouette Score:** ~0.45+ (confirms well-separated clusters)
* **Identified Customer Personas:**
  1. **High-Value Champions:** Frequent buyers with high total spend. *Action: Enroll in VIP loyalty/cashback programs.*
  2. **Regular Shoppers:** Consistent transaction frequency with moderate spend. *Action: Cross-sell related items.*
  3. **At-Risk / Inactive Customers:** Haven't purchased recently. *Action: Send re-engagement discount SMS/WhatsApp offers.*

---

