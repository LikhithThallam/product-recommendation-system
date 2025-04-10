### Product Recommendation System using Clustering

This project is a **Product Recommendation System** built using unsupervised learning (clustering).  
It analyzes user-product ratings to recommend the most relevant products to each user.

---

## 📌 Project Objective

To group similar users using **KMeans clustering** and recommend the most popular products within their cluster, based on their previous ratings.

---

## 🧠 Tech Stack & Tools

- **Python**
- **Pandas** & **NumPy**
- **Scikit-learn (KMeans, TruncatedSVD)**
- **Streamlit** (for deployment)
- **Joblib** (model saving)
- **Matplotlib / Seaborn** (for EDA)

---

## 📂 Files Included

- `product_recommender_app.py` — Streamlit app script
- `pivot_df.csv` — User-product matrix
- `top_products_per_cluster.csv` — Top 5 products per cluster
- `kmeans_model.pkl` — Trained KMeans model
- `svd_model.pkl` — Trained SVD model
- `requirements.txt` — Project dependencies

---

## 🔍 Key Features

- Loads user-product ratings dataset
- Creates a pivot table (users × products)
- Reduces dimensionality using **Truncated SVD**
- Clusters users with **KMeans**
- Recommends top 5 products from the user's cluster
- Fully deployed with **Streamlit** as an interactive web app

---

## 🚀 How to Run

1. Clone the repository
2. Install the requirements:
   ```bash
   pip install -r requirements.txt
