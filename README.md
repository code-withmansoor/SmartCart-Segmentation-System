# 🛒 SmartCart Segmentation System

A Machine Learning project that segments customers into different groups using clustering algorithms. This helps businesses understand customer behavior and create targeted marketing strategies.

---

## 📌 Project Overview

The SmartCart Segmentation System analyzes customer purchasing behavior and groups similar customers using unsupervised machine learning.

The project includes:

- Data preprocessing
- Feature engineering
- Data visualization
- PCA (Principal Component Analysis)
- K-Means Clustering
- Agglomerative Clustering
- Customer cluster analysis

---

## 🎯 Objectives

- Clean and preprocess customer data
- Create meaningful customer features
- Reduce dimensionality using PCA
- Find the optimal number of clusters
- Segment customers based on purchasing behavior
- Analyze each customer segment

---

## 📂 Dataset

The dataset contains customer information such as:

- Income
- Education
- Marital Status
- Purchase History
- Number of Web Purchases
- Number of Store Purchases
- Customer Recency
- Customer Age
- Total Spending

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- KMeans
- Agglomerative Clustering

---

## 📈 Machine Learning Workflow

1. Load Dataset
2. Handle Missing Values
3. Feature Engineering
4. Remove Outliers
5. Encode Categorical Features
6. Scale Features
7. Apply PCA
8. Determine Optimal K using:
   - Elbow Method
   - Silhouette Score
9. Perform K-Means Clustering
10. Perform Agglomerative Clustering
11. Analyze Customer Segments

---

## 📊 Visualizations

The project includes:

- Pair Plot
- Correlation Heatmap
- PCA 3D Projection
- Elbow Curve
- Silhouette Score Graph
- Cluster Distribution
- Income vs Total Spending Scatter Plot

---

## 📁 Project Structure

```
SmartCart-Segmentation-System/
│
├── SmartCart Clustering System project.ipynb
├── smartcart_customers.csv
├── README.md
└── requirements.txt
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/code-withmansoor/SmartCart-Segmentation-System.git
```

Go to project folder

```bash
cd SmartCart-Segmentation-System
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook.

---

## 📊 Results

- Successfully cleaned and preprocessed customer data.
- Reduced data dimensions using PCA.
- Determined the optimal number of clusters using the Elbow Method.
- Segmented customers into **4 meaningful clusters**.
- Generated insights that can support personalized marketing and customer relationship management.

---

## 🔮 Future Improvements

- Build an interactive dashboard using Streamlit.
- Compare additional clustering algorithms (DBSCAN, Gaussian Mixture Models).
- Deploy the project as a web application.
- Add automated cluster reports.

---

## 👨‍💻 Author

**Mansoor Makandar**

GitHub: https://github.com/code-withmansoor

---

## ⭐ If you found this project useful, please give it a Star!
