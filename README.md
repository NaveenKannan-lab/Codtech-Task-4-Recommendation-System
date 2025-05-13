#  Task 4 – Recommendation System using Collaborative Filtering (SVD)

##  Internship Project – Machine Learning (CodTech)

Hello!  This repository contains my solution to **Task 4** of the CodTech Machine Learning Internship. The task was to build a **movie recommendation system** using **Collaborative Filtering or Matrix Factorization techniques**.

I chose to implement **Collaborative Filtering using SVD (Singular Value Decomposition)** on the **MovieLens 100k** dataset.

---

##  Objective

To build a functional recommendation system that:
- Learns user preferences from historical rating data
- Predicts ratings for unseen items (movies)
- Recommends top-rated items to users
- Evaluates performance using metrics like **RMSE**

---

## 🧾 Dataset – MovieLens 100k

MovieLens 100k is a benchmark dataset for recommendation systems:
- Contains **100,000 ratings** from **943 users** on **1682 movies**
- Ratings are from **1 to 5**
- No explicit movie or user features — only user IDs, movie IDs, and ratings

Dataset was loaded using the `surprise` library:
```python
from surprise import Dataset
data = Dataset.load_builtin('ml-100k')
```


Final Output of Recommendation System:

![Image](https://github.com/user-attachments/assets/29c7d2f2-56e7-4bd0-89eb-080d0f4a6b55)




