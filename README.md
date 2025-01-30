# Zeotap Data Science Assignment

## 📌 Project Overview
This repository contains the solutions for the *Zeotap Data Science Internship Assignment*. The assignment involves analyzing eCommerce transactions data to extract insights, build a lookalike model, and perform customer segmentation using clustering techniques.

## 📂 File Structure

├── Customers.csv                 # Customer details
├── Transactions.csv               # Transactions data
├── Products.csv                   # Product details
├── Alekhya_Vijji_EDA.ipynb    # Exploratory Data Analysis (EDA) Notebook
├── Alekhya_Vijji_EDA.pdf      # EDA Report (PDF)
├── Alekhya_Vijji_Lookalike.ipynb  # Lookalike Model Notebook
├── Alekhya_Vijji_Lookalike.csv    # Lookalike Model Results
├── Alekhya_Vijji_Clustering.ipynb # Customer Segmentation Notebook
├── Alekhya_Vijji_Clustering.csv   # Cluster Assignments
├── Alekhya_Vijji_Clustering.pdf   # Clustering Report (PDF)
├── README.md                       # Project Documentation


---

## 📝 Task 1: Exploratory Data Analysis (EDA)
### *Objective:*
Perform data exploration on eCommerce transactions and derive meaningful business insights.

### *Steps Taken:*
- Merged *Customers, Transactions, and Products* datasets.
- Checked for *missing values* and handled them.
- Performed *data visualizations* (Total Sales Distribution, Monthly Trends, etc.).
- Extracted *top-selling products* and customer spending patterns.
- *Saved insights as a PDF report.*

### *Deliverables:*
- Alekhya_Vijji_EDA.ipynb
- Alekhya_Vijji_EDA.pdf

---

## 🏷 Task 2: Lookalike Model
### *Objective:*
Build a model to find *3 similar customers* for each user based on their profile and transaction history.

### *Steps Taken:*
- Aggregated customer data to calculate *total spending, quantity purchased, and average product price.*
- Applied *StandardScaler()* for normalization.
- Used *K-Nearest Neighbors (KNN)* to find the closest similar customers.
- *Saved lookalike results in CSV format.*

### *Deliverables:*
- Alekhya_Vijji_Lookalike.ipynb
- Alekhya_Vijji_Lookalike.csv

---

## 🔍 Task 3: Customer Segmentation (Clustering)
### *Objective:*
Segment customers into different groups based on spending behavior.

### *Steps Taken:*
- Used *K-Means Clustering* with features like *Total Spending, Quantity Purchased, and Price.*
- Applied *Elbow Method* to determine the optimal number of clusters.
- Evaluated clusters using *Davies-Bouldin Index (DBI) and Silhouette Score.*
- *Visualized clusters using scatter plots.*

### *Deliverables:*
- Alekhya_Vijji_Clustering.ipynb
- Alekhya_Vijji_Clustering.pdf

---

## 🚀 How to Run the Code
1. Clone this repository:
   sh
   git clone https://github.com/vijji5432/zeotap_assignment.git
   cd zeotap-assignment
   
2. Install dependencies:
   sh
   pip install pandas numpy seaborn matplotlib scikit-learn
   
3. Run each notebook in *Jupyter Notebook* or *Google Colab*.
4. Check the generated CSV and PDF reports in the repository.

### 🎯 Final Notes
This project demonstrates data exploration, machine learning (KNN for lookalike model), and clustering (K-Means) on eCommerce transactions data. The insights gained can help businesses improve customer targeting, segmentation, and retention strategies.
