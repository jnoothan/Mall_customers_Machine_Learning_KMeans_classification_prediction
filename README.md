# Customer Segmentation using KMeans Clustering

This project applies **KMeans Clustering** for customer segmentation based on **annual income** and **spending score**. It is a classic unsupervised machine learning problem where the goal is to identify groups of customers with similar behaviors to help in targeted marketing strategies.

---

## 📌 Project Objective

To analyze customer data and segment them into distinct clusters using KMeans clustering based on their **income** and **spending habits**.

---

- **Attributes used**:
  - `Annual Income (k$)`
  - `Spending Score (1–100)`

---

## 📌 Key Features

- Preprocessing and normalization of data.
- Elbow method to determine optimal number of clusters.
- Implementation of **KMeans Clustering**.
- Visual representation of clusters.
- Labeling of customer segments based on behavior.

---

## 📷 Sample Output

![image](https://github.com/user-attachments/assets/50b631e8-47ce-449b-9608-d9e0258bb1f2)

- Each color represents a unique customer cluster.
- X-axis: **Income (in $1000s)**
- Y-axis: **Spending Score (1–100)**

---

## 🔧 Requirements

- Python 3.9
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

Install requirements:

```bash
pip install -r requirements.txt
