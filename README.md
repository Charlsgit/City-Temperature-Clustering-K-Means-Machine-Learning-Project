# **City Temperature Clustering — K-Means Machine Learning Project**

Identifying temperature patterns across multiple cities using unsupervised learning.

---

## **Project Overview**

This project applies **K-Means Clustering** to a multi-city temperature dataset to identify climate-based patterns and group cities with similar weather behavior.

The goal is to:

* Understand seasonal temperature variations
* Cluster cities based on temperature patterns
* Visualize climate similarities across regions

---

## **Tech Stack**

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-Learn (KMeans)**

---

## **Steps Performed**

### **1️ Data Cleaning & Preprocessing**

* Extracted numerical values from temperature strings
* Handled missing values
* Converted columns to proper data types
* Selected relevant monthly/seasonal features

### **2️ Exploratory Data Analysis (EDA)**

* Year-wise temperature variation
* Monthly mean temperature comparison
* City-wise boxplots
* Correlation analysis

### **3️ Feature Scaling**

Used:

```
StandardScaler()
```

Scaling ensures all features contribute equally to clustering.

### **4️ Finding Optimal Number of Clusters**

Used **Elbow Method**:

* Calculated WCSS (Within-Cluster Sum of Squares)
* Visualized inertia vs. k
* Selected best *k* value for clustering

### **5️ K-Means Clustering**

Applied:

```
KMeans(n_clusters=k, random_state=42)
```

Generated cluster labels for each city based on temperature patterns.

---

## **Results**

* Cities were grouped into clusters that share similar temperature behavior
* Identified cool-weather cities, moderate cities, and hot-weather cities
* Visualized clusters using scatter plots & heatmaps

(You can insert your actual cluster counts and outputs if you want)

---

## **What I Learned**

* How unsupervised ML models work
* Importance of feature scaling
* Using the elbow method
* Performing clustering on real-world climate data
* Visualizing cluster distributions

---

## **Future Improvements**

* Add humidity, rainfall, wind-speed data
* Compare with Hierarchical Clustering / DBSCAN
* Deploy the model with a simple web app
* Perform seasonal clustering (Summer/Winter groups)

