# Customer Segmentation using K-Means Clustering

## Project Description

This project focuses on identifying hidden customer groups from unlabeled retail data using unsupervised machine learning techniques.

The goal is to segment customers based on their demographic and purchasing behavior using **K-Means Clustering**. Since clustering works with distance-based algorithms, the dataset is preprocessed, scaled, and analyzed to discover meaningful customer patterns.

**Principal Component Analysis (PCA)** is applied to reduce multiple features into 2 dimensions for better visualization, while the **Elbow Method** and **Silhouette Score** are used to determine the optimal number of clusters.

The generated clusters are converted into business-friendly customer personas that can help companies improve marketing strategies, customer targeting, and decision-making.


# Dataset Information

Dataset: Customer Segmentation / Mall Customers Dataset

Features:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

Dataset Type:
- Unlabeled Data
- Suitable for Unsupervised Learning


# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
  

# Machine Learning Techniques

## Data Preprocessing

Performed:

- Dataset inspection
- Missing value checking
- Duplicate checking
- Feature selection
- Categorical encoding
- Feature scaling


## Dimensionality Reduction

### Principal Component Analysis (PCA)

PCA is used to reduce the feature space into 2 dimensions for cluster visualization while maintaining important information from the dataset.


## Clustering Algorithm

### K-Means Clustering

K-Means groups customers into different clusters based on similarity and distance between data points.


## Cluster Optimization

### Elbow Method

Used to find the optimal number of clusters by analyzing Within Cluster Sum of Squares (WCSS).


### Silhouette Score

Used to evaluate how well-separated and meaningful the generated clusters are.


# Customer Personas Generated

The clusters are translated into business personas such as:

### Premium Customers
- High income
- High spending behavior

### High Income Low Spending Customers
- High purchasing power
- Low engagement

### Young Potential Customers
- Lower income
- Higher spending tendency

### Budget Customers
- Lower income
- Lower spending behavior


# Project Features

✅ Unsupervised Machine Learning  
✅ Customer Segmentation  
✅ K-Means Clustering  
✅ PCA Visualization  
✅ Elbow Method Analysis  
✅ Silhouette Score Evaluation  
✅ Business Intelligence Translation  
✅ Customer Persona Generation  


# Results

The model successfully identifies different customer groups based on purchasing patterns and provides meaningful insights that can support:

- Targeted marketing campaigns
- Customer relationship management
- Personalized offers
- Business decision-making


# How to Run the Project

Clone the repository:

```bash
git clone https://github.com/Faiqa-Azhar/DecodeLabs-Internship-Task3-FaiqaAzhar.git

pip install -r requirements.txt

Customer_Segmentation.ipynb
```



# Author
Faiqa Azhar

