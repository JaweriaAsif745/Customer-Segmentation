# 🛍️ Retail Customer Segmentation Using K-Means Clustering

**Analyze your customers and segment them into meaningful groups based on purchasing behavior!** This project performs RFM (Recency, Frequency, Monetary) analysis and clusters customers using K-Means for actionable business insights.

---

## 🌟 Features

* **Data Cleaning & Preprocessing**: Handles missing values, converts data types, and computes total transaction amounts.
* **RFM Analysis**: Calculates **Recency**, **Frequency**, and **Monetary** values for each customer.
* **Outlier Detection & Removal**: Cleans extreme values to improve clustering accuracy.
* **Feature Scaling**: Standardizes features for unbiased clustering.
* **K-Means Clustering**: Automatically identifies optimal clusters using the **Elbow Method** and segments customers.
* **Visualizations**:

  * Boxplots for outlier detection
  * Scatter plots for cluster distribution
  * Strip plots for RFM distributions per cluster

---

## 📊 Dataset

* Source: Online Retail Dataset
* Rows: 541,909 transactions
* Columns include:

  * `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `UnitPrice`, `CustomerID`, `Country`
* Preprocessing reduces it to 406,829 rows after cleaning nulls and irrelevant columns.

---

## ⚙️ Installation

1. Clone the repository:

```bash
git clone [<repository-url>](https://github.com/JaweriaAsif745/Customer-Segmentation.git
cd retail-customer-segmentation
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run your Jupyter Notebook:

```bash
jupyter notebook Retail_Customer_Segmentation.ipynb
```

---

## 🏗️ Project Workflow

1. **Load Dataset**
2. **Data Cleaning**: Remove nulls, convert data types, calculate transaction amount.
3. **RFM Calculation**: Compute Recency, Frequency, and Monetary values.
4. **Outlier Analysis & Removal**: Boxplots + IQR method.
5. **Feature Scaling**: StandardScaler on RFM features.
6. **Elbow Method**: Determine optimal number of clusters.
7. **K-Means Clustering**: Segment customers into clusters.
8. **Visualizations**: Scatter plots, strip plots, and cluster analysis.

---

## 🖥️ Visualizations

* **Boxplots**: Identify outliers in Amount, Frequency, Recency.
* **Scatter Plot**: Visualize customer segments in 2D space.
* **Strip Plots**: Compare RFM distributions across clusters.

---

## 🚀 Future Improvements

* Integrate **interactive dashboards** using Streamlit or Plotly.
* Combine with **customer demographics** for deeper insights.
* Use **advanced clustering methods** like DBSCAN or hierarchical clustering.
* Apply **predictive analytics** to forecast customer churn or lifetime value.

---

## 🧰 Tech Stack

* Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
* Data Cleaning & EDA
* Feature Scaling & RFM Analysis
* K-Means Clustering & Visualizations

---

## 📈 Key Takeaways

* Easily identify **high-value, loyal, and at-risk customers**.
* Make **data-driven marketing decisions**.
* Segment customers for **personalized offers and promotions**.

---

## 👩‍💻 Author

**Jaweria Asif**

* GitHub: [JaweriaAsif745](https://github.com/JaweriaAsif745)

---
emojis, badges, and quick highlights.

Do you want me to do that?
