# Customer Churn Prediction - Databel

## **Project Overview**

This project aims to predict customer churn by analyzing various factors that influence whether a customer will leave a service. By building classification models, we hope to identify the key drivers of churn and provide actionable insights for reducing churn rates and increasing customer retention.

## **Methodology**

The project follows a structured approach, broken down into several key phases:

1. **Data Exploration**:
   - Summarized both categorical and continuous features to better understand customer behavior.
   - Created visualizations to detect trends and patterns in the data, particularly around churn rates and customer attributes.

2. **Data Cleaning**:
   - Imputed missing values and handled outliers to ensure the dataset was prepared for analysis.
   - Applied transformations where necessary to improve data quality and model performance.

3. **Feature Engineering**:
   - Created new features (such as Age Categories and Monthly GB Data categories) to enhance predictive power.
   - Encoded categorical variables and scaled numerical data to ensure compatibility with machine learning models.

4. **Model Building**:
   - Built several classification models (Random Forest, Support Vector Machines, K-Nearest Neighbors, Decision Tree, Naive Bayes) to predict churn.
   - Compared model performance using key metrics like Accuracy, Precision, Recall, and F1 Score.
   - Conducted cross-validation to ensure robustness of the models.

## **Conclusion**

- **Random Forest** and **Support Vector Machines** delivered the best performance in terms of accuracy and F1 scores, indicating they are strong candidates for predicting churn.
- **Month-to-Month contracts**, **Paper Check payment methods**, and **frequent customer service calls** were some of the key drivers of churn.
- The project provided actionable recommendations such as improving customer service, reviewing contract terms, and tailoring service offerings to specific customer demographics, such as senior customers and regions with high churn.

## **Technologies Used**

- **Python** (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)
- **Jupyter Notebook** for interactive development
- **GitHub** for version control
