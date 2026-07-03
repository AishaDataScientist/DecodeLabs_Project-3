# Customer Segmentation Using Unsupervised Learning

A comprehensive **Unsupervised Machine Learning** project developed using **Python**, **Scikit-learn**, **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**. This project builds a complete customer segmentation pipeline by scaling data, reducing dimensionality with PCA, clustering customers using K-Means, and generating meaningful customer personas for business insights.

---

## Project Overview

Customer segmentation helps businesses understand different groups of customers based on their purchasing behavior and demographics.

This project implements an end-to-end unsupervised learning pipeline that:

* Generates a realistic retail customer dataset.
* Standardizes numerical features.
* Reduces dimensionality using Principal Component Analysis (PCA).
* Determines the optimal number of clusters.
* Segments customers using K-Means Clustering.
* Interprets cluster characteristics.
* Automatically assigns business-friendly customer personas.

---

## Project Objectives

* Generate a synthetic retail customer dataset.
* Standardize features using StandardScaler.
* Reduce feature dimensions using PCA.
* Determine the optimal number of clusters.
* Perform customer segmentation using K-Means.
* Analyze cluster characteristics.
* Create meaningful customer personas.
* Visualize customer segments.

---

## Repository Structure

```text
DecodeLabs_Project-3/
│
├── DecodeLabs_Project_3.ipynb
├── README.md
└── requirements.txt
```

---

## Technologies Used

* Python 3
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Dataset

The project uses a **synthetically generated retail customer dataset** containing approximately **400 customer records**.

The dataset includes features such as:

* Age
* Annual Income
* Spending Score
* Purchase Frequency
* Average Order Value
* Gender

---

## Machine Learning Pipeline

The project follows four major phases:

### 1. Data Scaling

All numerical features are standardized using **StandardScaler** to ensure equal importance during clustering.

---

### 2. Dimensionality Reduction

Principal Component Analysis (**PCA**) is applied to:

* Reduce feature dimensions.
* Preserve approximately **95% of the dataset variance**.
* Improve clustering performance.
* Simplify visualization.

---

### 3. Customer Clustering

Customers are segmented using **K-Means Clustering**.

The project automatically evaluates multiple cluster values and determines the optimal number of clusters using:

* Elbow Method (WCSS)
* Silhouette Score

The Silhouette Score is used as the final decision when both methods disagree.

---

### 4. Customer Persona Generation

After clustering, each customer group is analyzed based on centroid characteristics.

The project automatically assigns descriptive personas such as:

* High-Value Customers
* Loyal Customers
* Budget Shoppers
* Premium Buyers
* Occasional Customers

These personas help businesses understand customer behavior and improve marketing strategies.

---

## Cluster Analysis

The project provides:

* Cluster centroids
* Cluster statistics
* Average customer characteristics
* Business-friendly persona labels

---

## Visualizations

The notebook includes visualizations such as:

* Elbow Curve
* Silhouette Score Comparison
* PCA Scatter Plot of Customer Clusters
* Cluster Distribution
* Customer Segment Analysis

These visualizations help interpret clustering performance and customer behavior.

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/AishaDataScientist/DecodeLabs_Project-3.git
```

### 2. Navigate to the Project Folder

```bash
cd DecodeLabs_Project-3
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 4. Run the Notebook

Open the notebook and execute all cells:

```text
DecodeLabs_Project_3.ipynb
```

---

## Required Libraries

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---

## Project Workflow

The pipeline automatically performs:

* Synthetic data generation
* Data preprocessing
* Feature scaling
* PCA dimensionality reduction
* Optimal cluster selection
* Customer segmentation
* Cluster interpretation
* Persona generation

---

## Learning Outcomes

This project demonstrates:

* Unsupervised Machine Learning
* Customer Segmentation
* Feature Scaling
* Principal Component Analysis (PCA)
* K-Means Clustering
* Elbow Method
* Silhouette Analysis
* Business Intelligence
* Customer Persona Development
* Python Data Science Workflow

---

## Future Improvements

* Use real-world retail datasets.
* Compare K-Means with DBSCAN and Hierarchical Clustering.
* Build an interactive dashboard using Streamlit.
* Deploy the model for real-time customer segmentation.
* Add advanced visualizations with Plotly.

---

## License

This project is open source and available under the **MIT License**.

---

## Author

**Aisha Arif**

GitHub: https://github.com/AishaDataScientist

---
 If you found this project useful, consider giving it a star on GitHub!
