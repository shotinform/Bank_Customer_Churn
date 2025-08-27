# Bank Customer Churn Analysis

This project explores and analyzes a dataset of 10,000 bank customers to
identify factors influencing customer churn. It includes data
preprocessing, predictive modeling, clustering, and association rule
mining.

## **Key Features**

-   **Data Preprocessing:** Removed irrelevant attributes, handled
    imbalanced data (SMOTE), binarized categorical variables.
-   **Exploratory Data Analysis:** Identified key features impacting
    churn (Age, NumOfProducts).
-   **Classification Models:**
    -   Decision Trees (with GridSearch for tuning)
    -   Random Forest (with SMOTE for class balancing)
    -   Support Vector Machines (SVM)
    -   HistGradientBoostingClassifier (with RandomizedSearch)
-   **Model Evaluation:** Confusion matrix, F1-score, ROC curve, AUC.
-   **Clustering:**
    -   K-means (with PCA and t-SNE visualization)
    -   Hierarchical clustering.
-   **Association Rules:** Apriori algorithm to discover patterns linked
    to churn behavior.

## **Results**

-   Ensemble methods (Random Forest, HistGradientBoosting) achieved the
    best performance.
-   Clear customer segments and key features were identified for churn
    prediction.
-   Association rules provided actionable insights for improving
    retention strategies.
