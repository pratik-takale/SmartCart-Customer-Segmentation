#  SmartCart Customer Segmentation System

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Clustering-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

##  Project Overview

This project builds a **customer segmentation system** for an e-commerce platform (SmartCart) using **unsupervised machine learning**.

The goal is to group customers based on:

* Purchasing behavior
* Income
* Engagement

---

##  Objective

* Identify customer segments
* Improve marketing strategies
* Enable data-driven decision making

---

##  Dataset

* 2240 customer records
* Features:

  * Demographics
  * Purchase behavior
  * Website activity
  * Customer feedback

---

##  Tech Stack

* Python
* Pandas, NumPy
* Seaborn, Matplotlib
* Scikit-learn

---

##  Machine Learning Workflow

###  Data Preprocessing

* Missing value handling
* Feature engineering (Age, Total Spending, Children)
* Outlier removal

###  Feature Engineering

* Age calculation
* Total spending aggregation
* Family size

###  Encoding

* OneHotEncoding for categorical variables

###  Scaling

* StandardScaler applied

###  Dimensionality Reduction

* PCA used for visualization

###  Clustering Algorithms

* K-Means Clustering
* Agglomerative Clustering

###  Evaluation

* Elbow Method
* Silhouette Score
* KneeLocator

---

##  Results

* Customers segmented into 4 clusters
* Clear separation based on income & spending

###  Insights

* High-value customers identified
* Low engagement users detected
* Business can target each cluster differently

---

##  How to Run

```bash
git clone https://github.com/your-username/smartcart-clustering.git
cd smartcart-clustering
pip install -r requirements.txt
jupyter notebook
```

---

##  Author

**Pratik Takale**
Data Scientist | ML Engineer |

---

