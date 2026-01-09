# Video Game Sales Data Mining Pipeline 

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)

##  Project Overview
This project performs an end-to-end Data Mining analysis on global video game sales data. The goal is to extract market insights, segment game performance, and predict future sales success using Machine Learning algorithms.

##  Methodology & Algorithms
We implemented a complete KDD (Knowledge Discovery in Databases) pipeline:

1.  **Clustering (K-Means)**:
    * **Goal**: Customer Segmentation.
    * **Result**: Identified 3 distinct market clusters (Low, Medium, and High-Volume Sales).
    
2.  **Classification (Decision Tree)**:
    * **Goal**: Predictive Modeling.
    * **Result**: Achieved **~91% Accuracy** in predicting whether a game will be a "Hit" or "Flop" based on Platform and Genre.

3.  **Association Rule Mining (Apriori)**:
    * **Goal**: Basket Analysis.
    * **Result**: Discovered strong correlations between the European (EU) market and Global success, suggesting EU is a key trendsetter.

## 📂 Repository Structure
```text
├── data/           # Raw and Preprocessed CSV datasets
├── notebooks/      # Jupyter Notebooks with full analysis code
└── requirements.txt # Python dependencies
