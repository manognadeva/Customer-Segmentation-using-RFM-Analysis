# 🛍️ Customer Segmentation using RFM Analysis

This project applies **RFM (Recency, Frequency, Monetary)** analysis to segment customers based on their purchasing behavior. The goal is to help businesses better understand customer engagement and design targeted marketing strategies.

---

## 📌 Objectives

- Perform RFM-based customer analysis  
- Segment customers using clustering techniques  
- Provide actionable insights to support marketing and retention efforts

---

## 🧾 Dataset

The dataset is sourced from Kaggle: **[eCommerce Dataset](https://www.kaggle.com/datasets/carrie1/ecommerce-data)**  
It contains one year of historical transaction data from a UK-based online retail company that sells unique all-occasion gifts to customers worldwide.

> Note: The dataset is not included in this repository due to licensing restrictions. Please download it directly from the Kaggle link above.

---

## 🧹 Data Preprocessing

- Cleaned and filtered transaction records  
- Removed incomplete and inconsistent data  
- Handled invalid pricing and quantity issues  

---

## 📊 RFM Analysis

Calculated key metrics for each customer based on purchase behavior:
- How recently they made a purchase  
- How often they purchased  
- How much they spent

These insights were used to group customers into meaningful categories such as:
- Best Customers  
- Loyal Customers  
- Almost Lost  
- Passerby Customers  

---

## 🤖 Clustering & Segmentation

- Standardized the RFM values  
- Applied **K-Means Clustering** for segmentation  
- Used the **Elbow Method** to determine the optimal number of clusters (4)

---

## 📈 Insights & Recommendations

Created customer profiles and provided segment-specific marketing strategies to:
- Retain high-value customers  
- Re-engage inactive or declining customers  
- Encourage loyalty and repeat purchases  
- Optimize marketing budget for low-engagement users  

---

## 🛠️ Tools & Technologies

- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn  
- **Environment:** Jupyter Notebook

---

## 📁 Project Structure

Customer-Segmentation-RFM

├── Dataset

├── RFMAnalysis.ipynb # Main analysis notebook

├── README.md # Project overview

└──  .gitignore # Git ignored files

## 🎬 Getting Started

### 1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/Customer-Segmentation-RFM.git
   cd Customer-Segmentation-RFM
   ```
### 2. Install required libraries
    ```bash
    pip install -r requirements.txt
    ```
### 3.Download the dataset from Kaggle

### 4. Launch Jupyter Notebook and open RFMAnalysis.ipynb
