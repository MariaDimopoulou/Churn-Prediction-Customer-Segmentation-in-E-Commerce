# E-Commerce Customer Churn Analysis and Prediction

This project focuses on predicting customer churn in an online retail company using machine learning algorithms. The dataset, sourced from Kaggle, underwent extensive exploratory data analysis (EDA), preprocessing, and classification methods, including Random Forest and XGBoost. Additionally, clustering techniques such as K-Means and DBSCAN were employed to identify customer segments.

## Project Overview

1. **Introduction**: The goal is to predict customer churn and perform customer segmentation to tailor promotional strategies.
2. **Exploratory Data Analysis (EDA)**: Analyzing data shape, types, correlations, imbalances, and missing values.
3. **Data Preprocessing**: Handling missing values, outliers, encoding categorical variables, and balancing imbalanced data.
4. **Classification Methods**: Employing Random Forest, XGBoost, and Logistic Regression with and without balancing data.
5. **Clustering Methods**: Utilizing K-Means, DBSCAN, and Hierarchical clustering techniques.

## Classification Results

- **Random Forest**: Achieved high accuracy, precision, and AUC-ROC; slightly lower recall.
- **XGBoost**: Outperformed other classifiers in most metrics.
- **Logistic Regression**: Showed comparatively lower scores.

## Clustering Results

- **K-Means with t-SNE**: Produced the most accurate clusters compared to other clustering methods.
- **DBSCAN**: Demonstrated less accurate clustering.
- **Hierarchical Clustering**: Used for visualizing dendrogram structure.

## Files Overview

- `Untitled4.ipynb`: Jupyter notebook containing code and detailed explanations.
- `E Commerce Dataset.xlsx`: Dataset used for analysis.
- `README.md`: Overview of the project and instructions.

## How to Use

1. Open `Untitled4.ipynb` for detailed code, analysis, and results.
2. Download and explore the `E Commerce Dataset.xlsx` file.
3. Refer to `README.md` for project overview and details.

## Acknowledgments

- Dataset source: [Kaggle](https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction).
- Libraries used: pandas, scikit-learn, xgboost, seaborn, and others.
