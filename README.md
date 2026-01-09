# Zomoto Restaurant Clustering Project

## Project Overview
This project focuses on analyzing and clustering restaurant data using unsupervised machine learning techniques.  
The objective is to segment restaurants into meaningful groups based on cost and engineered features to derive actionable business insights.

The project follows a complete data science workflow including data cleaning, exploratory data analysis (EDA), feature engineering, hypothesis testing, clustering, and interpretation.

---

## Dataset
The dataset contains restaurant-related information such as:
- Restaurant Name  
- Cost  
- Cuisines  
- Timings  

Source: Zomato restaurant dataset (CSV files)

---

## Project Workflow
1. Data Cleaning & Preprocessing  
2. Exploratory Data Analysis (EDA) with visualizations  
3. Feature Engineering  
4. Hypothesis Testing  
5. Machine Learning Model Implementation  
6. PCA-based Cluster Visualization  
7. Model Comparison & Selection  
8. Business Insights and Conclusion  

---

## Machine Learning Models Used
- Hierarchical (Agglomerative) Clustering  
- DBSCAN  
- Gaussian Mixture Model (GMM)  

Among these, **Hierarchical Clustering** was selected as the final model due to its stability, interpretability, and suitability for the dataset.

---

## Technologies & Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  
- Git & GitHub  

---

## Key Insights
- Restaurants can be segmented into **Budget**, **Mid-range**, and **Premium** categories.  
- Cost and cuisine diversity are major factors influencing restaurant clustering.  
- Density-based clustering helps identify outliers and unique restaurant profiles.  

---

## Project Structure

```text
Zomoto-Restuarant-Clustering-Project/
│
├── data/
│   ├── Zomato Restaurant reviews.csv
│   └── Zomato Restaurant names and Metadata.csv
│
├── notebooks/
│   └── zomoto_analysis.ipynb
│
├── src
│   
│
├── output/
│   └── plots/
│
├── README.md
└── .gitignore
```



## Future Work
- Incorporate customer ratings and review sentiment analysis  
- Add location-based features  
- Apply advanced clustering algorithms such as HDBSCAN  
- Build a recommendation system based on cluster membership  

---

## Conclusion
This project demonstrates how unsupervised machine learning can be used to extract meaningful insights from real-world restaurant data.  
The clustering results can support decision-making for restaurant owners and food platforms.

---

## Author
**Prajjwal**  
GitHub: https://github.com/prajwall20
