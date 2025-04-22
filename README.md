**Tech Stack:**

     Programming Language: Python 

**Libraries & Frameworks: Data Manipulation & Exploration:**
     Pandas – Efficient data loading, cleaning, and transformation.
     NumPy – Numerical operations and array manipulation.

**Data Visualization:**
    Matplotlib – Plotting static, interactive, and animated visualizations.
    Seaborn – Advanced statistical plotting (heatmaps, distribution plots, etc.).

**Machine Learning & Model Evaluation:**
    Scikit-learn – Complete ML toolkit
    train_test_split – For stratified sampling.
    RobustScaler – For robust feature scaling (less sensitive to outliers).

**ML Algorithms Used:**
   1. Logistic Regression
   2. Decision Tree
   3. K-Nearest Neighbors (KNN)
   4. Random Forest
   5. AdaBoost
   6. Voting Classifier (Ensemble model combining all of the above)

**Model Strategy:**
     80/20 Train-Test Split – For unbiased performance evaluation.
     Ensemble Learning – Soft voting classifier aggregates the strengths of all base models for improved accuracy.
     Evaluation Metrics – Accuracy, Precision, Recall, F1-score, Specificity.



Developed a ML model to predict credit card defaults using consumer demographics, credit history, and payment habits data. The models are evaluated based on five performance metrics: accuracy, F-1 score, precision, sensitivity, and specificity.

Implemented a voting classifier model achieving high precision, sensitivity, and specificity, offering a strong alternative to individual models. 

Evaluated various ML models to identify the most effective model for predicting default risk, voting classifier performed well in predicting credit card defaults and Random Forest performed well among the individual models achieving an accuracy of 81.3%.
